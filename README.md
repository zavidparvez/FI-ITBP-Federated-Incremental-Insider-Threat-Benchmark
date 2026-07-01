# FI-ITBP: Federated Incremental Insider Threat Benchmark Protocol

This repository provides the implementation of **FI-ITBP**, a federated incremental evaluation benchmark for insider threat detection under concept drift.

## Paper

FI-ITBP evaluates federated insider threat detection systems using:
- client-isolated federated learning,
- chronological incremental data release,
- fixed-reference validation,
- prediction-level drift using PSI,
- representation-level drift using latent centroid displacement.

## Dataset

This implementation uses the CERT Insider Threat Dataset v6.2.

Because CERT R6.2 is not redistributed in this repository, users must download it separately and place the files as:

```text
Dataset_r6.2/
├── logon.csv
├── device.csv
├── http.csv
├── email.csv
└── file.csv

## Note
The complete source code, configuration scripts, and evaluation pipeline will be released upon publication of this article.
