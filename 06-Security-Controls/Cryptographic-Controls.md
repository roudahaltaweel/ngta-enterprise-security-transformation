# NGTA Cryptographic Controls

## Purpose

This document defines how the National Government Technology Authority (NGTA) uses fundamental cryptographic controls to protect government information and systems.

The controls in this document apply CompTIA Security+ cryptography concepts to the NGTA enterprise environment.

## 1. Data Encryption
NGTA will use encryption to protect the confidentiality of sensitive government information.

Sensitive data stored in databases, servers, and other storage systems will be encrypted at rest. Symmetric encryption is suitable for protecting large amounts of stored data because it is fast and efficient.

Data transmitted between NGTA systems will also be protected using secure encrypted communications to maintain confidentiality while the data is in transit.

### Security+ Connection

- Encryption protects confidentiality.
- Symmetric encryption uses the same shared secret key for encryption and decryption.
- Symmetric encryption is efficient for protecting large amounts of data.

## 2. Integrity and Hashing
NGTA will use cryptographic hashing to verify the integrity of important files, software, and security documents.

A hash can be calculated and compared with a trusted expected hash. If the hash values are different, the data may have been modified or corrupted.

### Security+ Connection

- Hashing helps verify integrity.
- Hashing is a one-way process.
- Hashing does not provide confidentiality.
- A change to the original data produces a different hash value.

## 3. Password Protection
NGTA will not store employee passwords in plaintext.

Employee passwords will be protected using salted password hashing and appropriate key-stretching techniques. Salting helps ensure that identical passwords do not produce identical stored hashes, while key stretching makes password-guessing attacks more computationally expensive.

### Security+ Connection

- Passwords should not be stored in plaintext.
- Salting adds random data before hashing.
- Salt helps make identical passwords produce different hashes.
- Key stretching increases the computational effort required for password guessing.

## 4. Digital Signatures
NGTA will use digital signatures for important official documents, security policies, and authorized administrative approvals.

Digital signatures help verify that information has not been modified, confirm the authenticity of the signer, and provide non-repudiation.

### Security+ Connection

- Digital signatures provide integrity, authentication/authenticity, and non-repudiation.
- The sender's private key is used to sign.
- The sender's public key is used to verify the signature.

## 5. PKI and Certificates
NGTA will use Public Key Infrastructure (PKI) and digital certificates to establish trust and support secure communications between users, devices, servers, and services.

Certificate Authorities (CAs) issue and sign digital certificates. Certificates help associate an identity with a public key.

If a certificate can no longer be trusted, it may be revoked.

### Security+ Connection

- PKI provides a framework for managing digital certificates and public/private keys.
- A Certificate Authority (CA) issues and signs certificates.
- CRL provides a list of revoked certificates.
- OCSP checks the current status of a specific certificate online.
- Private keys must remain protected.
