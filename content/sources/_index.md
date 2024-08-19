---
title: "Sources"
date: 2022-10-06T11:46:35+02:00
draft: false
---

All sources related to SOAP can also be found in the repositories of our [GitHub organization](https://github.com/orgs/soap-wg/repositories).

## Formal Proofs

The formal model and proofs for SOAP were encoded for the [Tamarin model checker](https://tamarin-prover.github.io/) and are provided within [our repository](https://github.com/soap-wg/soap-proofs).
The source code archives contain a README detailing how to check the proofs.


## Web-based Prototype

The web-based prototype can be reached under https://soap-proto.net.
The source code is hosted in [this repository](https://github.com/soap-wg/soap-web).

## Signal Prototype

The Signal prototype is available as precompiled debug .apks, and as source code in the releases section of [open-source repository](https://github.com/soap-wg/Signal-Android).
To install an .apk, you need to load it on your phone and enable to install apps from unknown sources.

The prototype uses the standard Signal servers, i.e., you need to register with a valid phone number to use the prototype.
The prototype is backwards-compatible with other Signal clients.
SOAP messages will be rendered as text messages containing base64-encoded data.

To import the source code in Android Studio, please follow the instructions of the [signalapp/Signal-Android](https://github.com/signalapp/Signal-Android) repository.
