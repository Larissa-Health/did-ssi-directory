---
description: https://www.w3.org/TR/did-core/
---

# Dezentralized Identifiers (DID)



{% hint style="info" %}
**Good to know:** Splitting your product into fundamental concepts, objects, or areas can be a great way to let readers deep dive into the concepts that matter most to them.
{% endhint %}

[Decentralized identifiers](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers) (DIDs) are a new type of identifier that enables verifiable, decentralized digital identity. A [DID](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers) refers to any subject (e.g., a person, organization, thing, data model, abstract entity, etc.) as determined by the controller of the [DID](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers). In contrast to typical, federated identifiers, [DIDs](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers) have been designed so that they may be decoupled from centralized registries, identity providers, and certificate authorities. Specifically, while other parties might be used to help enable the discovery of information related to a [DID](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers), the design enables the controller of a [DID](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers) to prove control over it without requiring permission from any other party. [DIDs](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers) are [URIs](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-uri) that associate a [DID subject](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-did-subjects) with a [DID document](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-did-documents) allowing trustable interactions associated with that subject.

Each [DID document](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-did-documents) can express cryptographic material, [verification methods](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-verification-method), or [services](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-service), which provide a set of mechanisms enabling a [DID controller](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-did-controllers) to prove control of the [DID](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers). [Services](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-service) enable trusted interactions associated with the [DID subject](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-did-subjects). A [DID](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-decentralized-identifiers) might provide the means to return the [DID subject](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-did-subjects) itself, if the [DID subject](https://www.w3.org/TR/2022/REC-did-core-20220719/#dfn-did-subjects)is an information resource such as a data model.
