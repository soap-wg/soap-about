---
title: "Sources"
date: 2022-10-06T11:46:35+02:00
draft: false
---

## Formal Proofs

The formal model and proofs for SOAP were encoded for the [Tamarin model checker](https://tamarin-prover.github.io/).
The source code archives contain a README detailing how to check the proofs.

* [Source code (zip)](https://github.com/soap-wg/soap-proofs/archive/refs/tags/usenix-pre.zip)
* [Source code (tar.gz)](https://github.com/soap-wg/soap-proofs/archive/refs/tags/usenix-pre.tar.gz)

## Web-based Prototype

The web-based prototype can be reached under https://soap-proto.net.
Find all source code for the web-based prototype below.
The source code archives contain a README.

Note that the build archive is hardcoded to work for the prototype's URL only.

* [Build (minified sources)](https://github.com/soap-wg/soap-web/releases/download/initial-relase/build.zip)
* [Source code (zip)](https://github.com/soap-wg/soap-web/archive/refs/tags/initial-relase.zip)
* [Source code (tar.gz)](https://github.com/soap-wg/soap-web/archive/refs/tags/initial-relase.tar.gz)

## Signal Prototype

The Signal prototype is available as precompiled debug .apks, and as source code.
To install an .apk, you need to load it on your phone and enable to install apps from unknown sources.

The prototype uses the standard Signal servers, i.e., you need to register with a valid phone number to use the prototype.
The prototype is backwards-compatible with other Signal clients.
SOAP messages will be rendered as text messages containing base64-encoded data.

To import the source code in Android Studio, please follow the instructions of the [signalapp/Signal-Android](https://github.com/signalapp/Signal-Android) repository.

* [Signal-Android-play-prod-arm64-v8a-debug-6.18.3.apk](https://github.com/soap-wg/Signal-Android/releases/download/ccs-proto/Signal-Android-play-prod-arm64-v8a-debug-6.18.3.apk)
* [Signal-Android-play-prod-armeabi-v7a-debug-6.18.3.apk](https://github.com/soap-wg/Signal-Android/releases/download/ccs-proto/Signal-Android-play-prod-armeabi-v7a-debug-6.18.3.apk)
* [Signal-Android-play-prod-universal-debug-6.18.3.apk](https://github.com/soap-wg/Signal-Android/releases/download/ccs-proto/Signal-Android-play-prod-universal-debug-6.18.3.apk)
* [Signal-Android-play-prod-x86-debug-6.18.3.apk](https://github.com/soap-wg/Signal-Android/releases/download/ccs-proto/Signal-Android-play-prod-x86-debug-6.18.3.apk)
* [Signal-Android-play-prod-x86_64-debug-6.18.3.apk](https://github.com/soap-wg/Signal-Android/releases/download/ccs-proto/Signal-Android-play-prod-x86_64-debug-6.18.3.apk)
* [Source code (zip)](https://github.com/soap-wg/Signal-Android/archive/refs/tags/ccs-proto.zip)
* [Source code (tar.gz)](https://github.com/soap-wg/Signal-Android/archive/refs/tags/ccs-proto.tar.gz)
