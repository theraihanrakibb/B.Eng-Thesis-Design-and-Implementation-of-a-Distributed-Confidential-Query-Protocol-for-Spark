# Design and Implementation of a Distributed Confidential Query Protocol for Spark

**B.Eng. Thesis** — School of Computer Science and Technology, Northwestern Polytechnical University (NWPU), 2024.

> **Abstract:** This thesis designs and implements a distributed confidential query protocol for Apache Spark, combining fully homomorphic encryption (CKKS) with the Spark computing engine so that sensitive data can be queried and processed without being decrypted — preserving **95% privacy protection** while keeping computation practical.

## Key Results

| Metric | Result |
|--------|--------|
| Privacy preservation | **95%** (CKKS homomorphic encryption, no plaintext exposure) |
| Performance | **~20% gain** over the direct-encryption baseline |
| Platform | Apache Spark (distributed, fault-tolerant) |

## Highlights

- **Confidential query protocol** on top of Apache Spark, so existing distributed pipelines can run over encrypted columns.
- **CKKS homomorphic encryption** for arithmetic-friendly ciphertext operations (addition/multiplication).
- End-to-end query evaluation: encrypted data in → encrypted results out, without server-side decryption.

## Repository Contents

- `Design_and_Implementation_of_a_Distributed_Confidential_Query_Protocol_for_Spark.pdf` — full English thesis.

## Tech Stack

Apache Spark · CKKS Homomorphic Encryption · Scala · Distributed Systems

## Author

**MD RAKIBUL ISLAM RAIHAN** — B.Eng. Computer Science, NWPU
- Email: raihanrakib.143@gmail.com
- GitHub: [theraihanrakibb](https://github.com/theraihanrakibb)
- Portfolio: [theraihanrakibb.github.io/Online-Portfolio](https://theraihanrakibb.github.io/Online-Portfolio/)

---

Related M.Eng. research: [M.Eng. Thesis](https://github.com/theraihanrakibb/M.Eng-Thesis-Multimodal-Deepfake-Audio-Visual-Temporal-Framework).
