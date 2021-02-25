# Example Charts

# Encryption

```mermaid
graph LR
    PlaintextBallot -- Encrypt --> CiphertextBallot
```

# Voting

```mermaid
graph LR
    CiphertextBallot -- Cast / Spoil --> SubmittedBallot
```

# Tally

```mermaid
graph LR
    SubmittedBallot -- Accumulate --> CiphertextTally
```

# Decryption

```mermaid
graph LR
    CiphertextTally -- Decrypt --> PlaintextTally
```

```mermaid
graph LR
    SubmittedBallot -- Decrypt --> PlaintextTally
```
_Note: For spoiled ballots_