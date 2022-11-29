# Object of Conformity Assessment Specification: Cryptographic Module

## Part 1: Object of Conformity Assessment Specifications

The set of hardware, software, and/or firmware that implements cryptographic security functions (including cryptographic algorithms and key generation) and is contained within the cryptographic boundary.

### Related Definitions

### Appropriate Use Cases

### Selection of Product, Service or Process

### Determination of Activities and Methods of Test

## Part 2: Object of Conformity Asssessment Requirements

1. All cryptographic algorithms and parameters SHALL conform with [ ITSP.40.111 - Cryptographic algorithms for UNCLASSIFIED, PROTECTED A, and PROTECTED B Information ](https://cyber.gc.ca/en/guidance/cryptographic-algorithms-unclassified-protected-protected-b-information-itsp40111)
2. All data (both at rest and/or in transit) SHALL be treated at PROTECTED B
3. Passphrases and passwords SHOULD follow reccomended best practices [ITSAP.30.032 - Best practices for passphrases and passwords](https://cyber.gc.ca/en/guidance/best-practices-passphrases-and-passwords-itsap30032)
4. Sanitization of all data SHALL be done using the following recognized methods:
  * Crypto erase (CE): This method securely deletes the encryption key used to encrypt data on the media. The encrypted data remains on the media, and SHALL be erased using the Overwrite and Secure Erase method.
  * Overwrite and secure erase (SE): This method uses software to write multiple passes (3 or more series) of random binary code (zeros and ones) on the storage media to prevent anyone from reading the previous data.

## Part 3: Determination of Outputs, Review and Attestation

### Determination of Outputs

### Review and Decision

### Attestation
