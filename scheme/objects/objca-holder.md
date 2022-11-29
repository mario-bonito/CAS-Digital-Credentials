# Object of Conformity Assessment Specification: Holder

## Part 1: Object of Conformity Assessment Specifications

**Holder** A process, service or component from which a Presentation can be expressed to a Verifier. A Holder is usually under the control of a User

### Related Definitions

**Holder Role** A role in which an entity that controls one or more Credentials from which a Presentation can be expressed to a Verifier. A Holder is usually, but not always, the Subject of a Credential.

### Appropriate Use Cases

### Selection of Product, Service or Process

### Determination of Activities and Methods of Test

## Part 2: Object of Conformity Asssessment Requirements

1. The Holder Component SHALL detect indications of credential misuse or compromise of the identity information. _NOTE:_ As an example, the expiry date having been exceeded or the detection of suspicious activity.
2. The Holder Component SHALL be able to request a credential from an issuer

    * The credential request SHALL allow the request to enable holder and subject binding where:
        * The Holder Component MAY be able to generate identifiers enabling proof of identifier control
            * Examples include pairwise decentralized identifiers, other decentralized identifiers, and other methods resulting in a URI identifier that can serve as subject in a Verifiable Credential or a holder in a Verifiable Presentation
    * The Holder Component MAY be able to generate proofs of identifier control

3. The Holder Component SHALL be able to request a credential in response to a holder action.
4. The Holder Component MAY be able to request a credential using a subscribe model in which verifiable credentials representing earned credentials from one or more issuers are requested/received/persisted so that the Holder component stays up-to-date with available credentials from those issuers.
5. The Holder Component SHALL be able to receive credentials.
6. The Holder Component SHALL be able to decline credentials.
7. The Holder Component SHALL be able to persist credentials with native format encoding from approved standards to ensure that it can fully produce the original record intact.
8. The Holder Component SHALL store credentials with sufficient metadata to allow execution of the minimal functions described in these requirements.
9. The Holder Component MAY be able to unpack the credential payload, but it is not required to do so.
10. The Holder Component MAY be able to request, listen for, or subscribe to credential updates, if offered, and if the holder chooses to enable.
    * The holder SHALL be able to decline a credential received via subscription.
11. The Holder Component SHALL be able to respond to a holder's request to remove a credential and stop persisting that credential.
12. The Holder Component SHALL assign control over an issued credential so as the Holder’s control of the Credential MAY be subsequently verified.
13. The Holder Component SHALL have a mechanism to create and submit a Verifiable Presentation to a relying party in response to:
    * A Holder component owner action
    * A request for a Verifiable Presentation obtained by a verifier, if approved by the Holder component owner.
14. A Holder Component MAY have a mechanism for receiving and processing presentation requests.
15. A Holder Component MAY be able to generate identifiers enabling proof of identifier control.
    * Examples include pairwise decentralized identifiers, other decentralized identifiers, and other methods resulting in a URI identifier that can serve as subject in a Verifiable Credential or a holder in a Verifiable Presentation.
17. A Holder Component SHALL be able to manage connections (e.g. to issuers, requesting parties, and other parties)
18. A Holder component SHALL be able to manage privacy and sharing settings.
19. A Holder Component MAY be used in conjunction with digital credentials. If so, the following requirements SHALL be considered:
    * Ensuring adherence to applicable wallet security standards and specifications;
    * Enabling receipt and presentation of credentials according to applicable credential standards and specifications;
    * Enabling the user to control the sharing of credential data, in whole, in part, or as a derivation;
    * Notifying the user of any changes to credentials;
    * Ensuring consent of the user prior to any transaction; and
    * Ensuring adherence to applicable accessibility requirements.
20. The Holder Component SHALL preserve digital credentials in accordance with the general characteristics specified in (Digital Credential)[./objca-digital-credential.md] of this Specification.

## Part 3: Determination of Outputs, Review and Attestation

### Determination of Outputs

### Review and Decision

### Attestation
