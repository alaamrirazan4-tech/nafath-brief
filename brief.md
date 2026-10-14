Version: NAFATH-V3

Your track: AI

## Overview
Bringing a public-service AI chat assistant into a government mobile app means we have to carefully tie together six core technical areas so everything runs smoothly, securely, and legally. Software engineering handles the structured release cycles and keeps API integrations stable. On the AI side, Retrieval-Augmented Generation (RAG) pulls factual answers straight from verified policy documents to cut down on mistakes. Mobile development and networking work together to secure data in transit across modern networks, while cybersecurity protects the model from prompt manipulation attempts. Finally, data management puts strict privacy safeguards in place for user logs. Altogether, these pieces form a dependable and trusted digital service for the public.

## Software
nder Semantic Versioning 2.0.0, the public API has to increment its MAJOR version whenever we introduce breaking changes that alter request structures or drop existing endpoints, which forces clients to update. The MINOR version goes up when we add backwards-compatible features or new optional parameters. We only bump the PATCH version for backwards-compatible bug fixes or minor code adjustments that leave the public API contract completely intact.
Resource: Semantic Versioning 2.0.0 Specification - https://semver.org/spec/v2.0.0.html

## AI
Retrieval-Augmented Generation (RAG) is an architecture that links a large language model with an external, authoritative knowledge base. Instead of relying purely on internal training memory, the system takes a user query, converts it into embeddings, pulls matching chunks from official databases, and feeds that verified context right into the prompt. This anchors the model in real documents, which heavily reduces hallucinations and incorrect statements.
Resource: Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks - https://arxiv.org/abs/2005.11401

## Mobile
iOS App Transport Security (ATS) enforces secure connections by requiring apps to use HTTPS with TLS 1.2 or higher, strong ciphers, and valid certificates for all network calls. If the mobile app tries calling a plain HTTP endpoint, ATS blocks the connection instantly at the OS level to stop unencrypted data from leaking out over public networks.
Resource: Apple Developer Documentation - Preventing Unsecure Network Connections - https://developer.apple.com/documentation/security/preventing_unsecure_network_connections

## Networking

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
