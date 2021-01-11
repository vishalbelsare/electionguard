# Features

## Component Attributes List

ElectionGuard allows different types of components to be created. Specialized components such as an encrypter do not need to have all the attributes of a fully implemented component of electionguard. This table demonstrates the necessary attributes for particular components.

|  Feature               |  Full                              |  Verifier                         | Encrypter                          |  Audit |
| :--------------------- | :--------------------------------: | :-------------------------------: | :--------------------------------: | :-----: |
| **Ballot**             |                                    |                                   |                                    |
| Encryption             | :fontawesome-regular-check-circle: |                                   | :fontawesome-regular-check-circle: |
| Decryption             | :fontawesome-regular-check-circle: |                                   |                                    |
| Threshold Decryption   | :fontawesome-regular-check-circle: |                                   |                                    |
| Casting                | :fontawesome-regular-check-circle: |                                   |                                    |
| Validation             | :fontawesome-regular-check-circle: | :fontawesome-regular-check-circle:|                                    |
| **Tally**              |                                    |                                   |                                    |
| Accumulation           | :fontawesome-regular-check-circle: |                                   |                                    |
| Decryption             | :fontawesome-regular-check-circle: |                                   |                                    |
| Threshold Decryption   | :fontawesome-regular-check-circle: |                                   |                                    |
| Ballot Confirmation    | :fontawesome-regular-check-circle: |                                   |                                    |
| Validation             | :fontawesome-regular-check-circle: | :fontawesome-regular-check-circle:|                                    |
| **Ceremony**           |                                    |                                   |                                    |
| Key Sharing            | :fontawesome-regular-check-circle: |                                   |                                    |
| Tally Decryption       | :fontawesome-regular-check-circle: |                                   |                                    |
| **Election**           |                                    |                                   |                                    |
| Manifest Validation    | :fontawesome-regular-check-circle: | :fontawesome-regular-check-circle:|                                    |
| Publishing             | :fontawesome-regular-check-circle: |                                   |                                    |
| Verification           | :fontawesome-regular-check-circle: | :fontawesome-regular-check-circle:|                                    |

## Ballot

- **Encryption** - Encrypt a ballot
- **Decryption** - Decrypt a ballot for spoiling with all guardians
- **Threshold Decryption** - Decrypt a ballot for spoiling with the threshold of guardians
- **Casting** - Cast a ballot including the option to spoil
- **Validation** - Validate a ballot

## Tally

- **Accumulation** - Accumulate ballots into a tally
- **Decryption** - Decrypt a tally with all guardians
- **Threshold Decryption** - Decrypt a tally with the threshold of guardians
- **Ballot Confirmation** - Confirm a ballot is in the tally
- **Validation** - Validate a tally

## Ceremony

- **Key Sharing** - Framework for sharing keys between guardians
- **Result Decryption** - Framework for ensuring necessary guardians present and perform their decryptions for tally decryption

## Election

- **Manifest Validation** - Validate an Election Manifest
- **Publishing** - Export a serialized version of the election artifacts
- **Verification** - Verify the election via election artifacts


