---
imname:
  name: "img/overview.png"
  alt: "Design idea of SOAP"
  type: image/png

name: "SOAP"
personal_title: "An OpenID Connect-based Social Authentication Protocol Applied to Messaging Applications"

title: "SOAP: OpenID Connect-based Social Authentication Protocol Applied to Messaging Applications"
date: 2022-10-06T11:46:35+02:00
draft: false
---

SOAP is a social authentication protocol.
When performing social authentication, users verify that their chat partner controls accounts at different identity providers (IdPs) which they know are controlled by their intended chat partner.
Using social authentication, users can verify, for example, that their messaging application chat is not intercepted by a MITM.
By building on top of the popular OpenID Connect protocol, SOAP automates the authentication ceremony and does not require adoption from any OpenID Connect-IdP.
The paper contains four contributions.

* We formally define the notion of *Social Authentication* as a security property.
* We present the protocol design of SOAP.
* We formally verify SOAP's security using the Tamarin model checker.
* We implement SOAP in two prototypes: a [web-based prototype](https://soap-proto.net), and an extension of the Signal Android application.
A video demo of the Signal prototype is shown below.

SOAP was developed in the [Centre for Cyber Trust](https://cyber-trust.org/) which is funded by the Werner Siemens-Stiftung (WSS).

---

* SOAP has published at [USENIX Security 24](https://www.usenix.org/conference/usenixsecurity24/presentation/linker)!
* You can find all sources related to this project [here](/sources).

{{< youtube Ip_RAF8PRrM >}}
