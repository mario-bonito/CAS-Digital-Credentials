# Object of Conformity Assessment Specification: Cryptographic Module

## Part 1: Object of Conformity Assessment Specifications

The set of hardware, software, and/or firmware that implements cryptographic security functions (including cryptographic algorithms and key generation) and is contained within the cryptographic boundary.

>**Definition** add definition here

### Related Definitions

Non-normative definitions which may assist in interpretation and application of the conformity.

* **Additional defintions** that may be helpful in the conformity assessment

Further definitions may provided by the evaluator or vendor:

### Appropriate Use Cases

* Provide descriptions of appropriate [use cases](./use-cases.md) that situate the context where the object of conformity is being used.

### Selection of Product, Service or Process

* Provide descriptions of selected the products, services or process that are being tested in relation to the conformity assessment requirements._

### Determination of Activities and Methods of Test

* Provide a description of activities undertaken and [methods of test](./methods-of-tests.md). used to btain information regarding the fulfillment of the conformity assessment  requirements.

## Part 2: Object of Conformity Asssessment Requirements

Conformity assessment requirements:

ISO Conventions for Requirements

* **Requirements** - SHALL, SHALL NOT
* **Recommendations** - SHOULD, SHOULD NOT
* **Permission** - MAY, MAY NOT
* **Possibility and Capability** - CAN, CANNOT

1. All cryptographic algorithms and parameters SHALL conform with [ ITSP.40.111 - Cryptographic algorithms for UNCLASSIFIED, PROTECTED A, and PROTECTED B Information ](https://cyber.gc.ca/en/guidance/cryptographic-algorithms-unclassified-protected-protected-b-information-itsp40111)
2. All data (both at rest and/or in transit) SHALL be treated at PROTECTED B
3. Passphrases and passwords SHOULD follow reccomended best practices [ITSAP.30.032 - Best practices for passphrases and passwords](https://cyber.gc.ca/en/guidance/best-practices-passphrases-and-passwords-itsap30032)
4. Sanitization of all data SHALL be done using the following recognized methods:
  * Crypto erase (CE): This method securely deletes the encryption key used to encrypt data on the media. The encrypted data remains on the media, and SHALL be erased using the Overwrite and Secure Erase method.
  * Overwrite and secure erase (SE): This method uses software to write multiple passes (3 or more series) of random binary code (zeros and ones) on the storage media to prevent anyone from reading the previous data.

## Part 3: Determination of Outputs, Review and Attestation

### Determination of Outputs

_Determination of [outputs](../scheme-definitions.md) that are used as input into the review, decision and attestation stage._

### Review and Decision

_Review is the final stage of checking before taking the decision as to whether or not the object of conformity assessment e.g. product, service and system, has been reliably demonstrated to fulfil the specified requirements._

### Attestation

_The “statement of conformity”, a standardizedc expression used to include then means of communicating that fulfilment of conformity assessment requirements has been demonstrated. It should be noted that a "statement of conformity" may include non fulfilment of specified requirements._
