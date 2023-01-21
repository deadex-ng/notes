# Indentity Management
> “In the social jungle of human existence, there is no feeling
of being alive without a sense of identity.” — Erik Erikson
## Digital Identity
Digital Identity: Information about an entity that is sufficient to identify that entity in a
particular context (International Telecommunication Union (ITU), 2009).

Three types of data related to Digital Identity:identifiers, attributes and credentials.
- identifiers

The main objective of an identifier is to relate to an entity and is used to
identify its subject.

The identifier trilema:

![trilema](https://user-images.githubusercontent.com/60394916/213888344-9aed15e8-fadc-4667-a814-3345addcb795.PNG)

- attributes

Attributes describe the characteristic of a subject.

- credentials

Credentials are a set of data used to prove claims, parts, or the entire
digital identity to a verifying party.

## Identity Management
IdM defines the stakeholder of the identity system, the lifecycle of a digital identity, and also the access management.
Various models describe specializations of IdM systems with specific characteristics.

Identity Assurance: the level of confidence in the provided identity data of the
subject by the IdP(Identity Provider) towards the RP(Relying Party).

### Stakeholders
main stakeholders of an identity system
- Subject
- Identity Provider
- Relying Party
- Controlling Party

### Identity Lifecycle

The identity lifecycle describes the four main stages of a digital identity such as creation,
usage, update and revocation.

![lifecycle](https://user-images.githubusercontent.com/60394916/213888742-b928fe76-36d3-42cb-997c-3bdf03be23e2.PNG)

## Identity Models
We describe four identity models: isolated, central, federated, and user-centric identity model

- isolated

One organization operates both the IdP as well as the RP.

![isolated](https://user-images.githubusercontent.com/60394916/213888948-fca211aa-f582-4af9-9d51-51820728bea0.PNG)

Only one organization is responsible for securely storing identity data.

The subject has to trust this organization to do so and further that the identity
data will not be misused.

- central

Separates the roles of the IdP and the RP. 

![central](https://user-images.githubusercontent.com/60394916/213889066-6e903612-1e53-455d-bed9-a3fcf07f7f5e.PNG)

The advantage of this model over the isolated model lies clearly in the separation of IdP and RP because
the subject does not have to register individually at each service providing RP.

One of the main disadvantages of this model is that the IdPs store the identity data of many subjects, thus,
providing a huge amount of information to this party.

- federated

Separates the roles even more so that not only one IdP stores the identity data. Instead, identity data are stored distributed across several IdPs
and sometimes even RPs.

![federated](https://user-images.githubusercontent.com/60394916/213889201-fc4b8927-ba79-4a8d-86b6-10fb4c6d0f1e.PNG)

The overhead of linking the
digital identity throughout the federation is a clear disadvantage.

When a subject authenticates at an RP, more than one IdP learns from the metadata that
a specific subject or group is using certain services and other meta-information which is
raising privacy concerns.

- user-centric

The User-Centric Identity Model follows the approach
of putting the subject in the center. This means that in contrast to the other identity
models, the user actually stores their identity data in the subject’s domain.

![user-centric](https://user-images.githubusercontent.com/60394916/213889386-b89b64bb-01ab-4198-8a2e-6ea29de60577.PNG)

The subject stores the credentials within the subject’s domain.

When the subject attempts to access a resource or
service at the RP, the user directly provides the required authentication means to the RP.

Nevertheless, when the IdP offers a revocation
mechanism, such as a revocation list, the IdP could learn meta data from the revocation
requests made by the RP to the IdP about a subject.

Still, this model provides many
benefits for the subjects such as that the subject’s consent is required before the identity
data can be shared.

