# Introduction 
## Motivation 
> “Look up at the stars and not down at your feet. Try to
  make sense of what you see, and wonder about what makes
  the universe exist. Be curious.” — Stephen Hawking

The use of online services is part of our daily lives. An example of an online services is ,Google, and there is a need for an account touse these services.
A digital identinty can be represented as an account.

Companies that own these online services hold identity related data for millions of users in digital silos. These silos attract attackers with the incentive
of having accessto huge amounts of data.

Managers of digital identies need to ensure data security and privacy. Users also have to trust the managers since they have no control over their data
and even if they are not fully conviced about the security and privacy of the identity managing party.

SSI(Self Soverign Identity) addresses the central trusted party of traditional IdM(Identity Management) systems by using DL(Distributed Ledger) Technology.
However in SSI, identity are often self-asserted with being trusted poorly. Additionally, users are able to make claims about themselves and other parties can attest
these claims or even attest claims that are not self-asserted.

Another issue with SSI is, it's applicability is limited bacuse there is lack of a trusted and well orgainsed data issuer to ensure correctness and validity of the data. Thus in SSI systems, the data quality can still be interpreted as low and thus cannot be used for services that require higher data quality.

Similar to most new models, SSI struggles to be widely accepted and adopted. Due to this, SSI systems need to be built on top of current identity systems than being operated in parallel or being an alternative. 

Several initiatives and projects are develpoing SSI systems for various areas of application. These are also developing different revocation mechanisms to improve security and privacy. Although, these systems may not be compatible with each other. 

SSI uses identiy wallet to store and manage related users identity data within the user's domain. Currently, these lack strong user authentication and offline verification of identity data.

> This thesis tackles the before-mentioned issues by introducing novel trust models in
the SSI field as well as addressing privacy concerns. Additionally, we enable the identity
data derivation by building a chain of trust between identity systems, enhancing identity
systems, and improving data quality. Moreover, this thesis also proposes new methods for
authentication by introducing strong authentication mechanisms for SSI identity wallets,
but also offline verification of identity data. Besides, we introduce a service that is able
to combine varying revocation mechanisms for SSI systems. We further evaluate and
showcase how our improved system can be utilized.

## Methodology
This thesis follows a methodology detailed in this section and schematically illustrated here: 
![schematic-structure](https://user-images.githubusercontent.com/60394916/213809208-aa7ef091-337d-4836-a688-3d2a587ca4dd.PNG)
