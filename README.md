# Future Storage - Filecoin Plus DataCap Allocator - Client Applications

Welcome to the GitHub repository for the Future Storage DataCap Allocator managing Large Dataset Notary (LDN) Applications under the Filecoin Plus program. This repository serves as a transparent public ledger for tracking DataCap allocation requests.

## Allocator Information

- **Allocator Pathway Name**: Future Storage
- **Pathway Type**: Public Open Pathway
- **Organization On-Chain Address**: f2mkq7zjmtoinrjsk7em4i2gnq5vgw723vhhduvvy
- **On-chain Address for DC Allocation**: f2mkq7zjmtoinrjsk7em4i2gnq5vgw723vhhduvvy

## Overview

This allocator focuses on enabling large-scale data storage on the Filecoin network through the Filecoin Plus program. We manage DataCap allocations for clients storing valuable datasets that enhance the Filecoin ecosystem's utility and adoption.

## Allocation Structure

### DataCap Allocation Limits
- **Weekly Allocation**: Typically ranges from 100 TiB to 2 PiB
- **Total Requested Amount**: Based on dataset size and replication needs
- **Single Size Dataset**: Defined per application requirements
- **Allocation Tranches**: Distributed in scheduled tranches to ensure responsible usage

### Replicas and Storage Providers
- **Minimum Replicas**: 4-10 replicas required for data redundancy
- **Storage Provider Requirements**: 
  - Minimum of 5 unique Storage Provider IDs required
  - No single SP should receive >30% of allocated DataCap
  - Geographic distribution across multiple regions encouraged
  - Supported regions include Greater China, Asia, Africa, North America, South America, Europe, and Australia

## Data Diligence

Our data diligence process ensures that stored datasets provide value to the Filecoin network:

- **Public Dataset Verification**: All datasets must be publicly retrievable without specific permissions
- **Data Types Supported**: Including but not limited to research data, open commercial data, enterprise data, and social impact datasets
- **Storage Duration**: Projects commit to storing data from 1 year to permanently
- **Retrieval Patterns**: Supporting various retrieval frequencies from daily to sporadic access
- **Data Distribution Methods**: Supporting cloud storage (S3), HTTP/FTP servers, IPFS, and direct data transfer protocols

## Client Diligence

Client verification ensures responsible DataCap allocation:

- **Organization Verification**: Including industry classification, regional presence, and business legitimacy
- **Project Assessment**: Evaluating project history, ecosystem associations, and data preparation capabilities
- **Technical Capability**: Confirming ability to prepare datasets using tools like Boost and Singularity
- **Compliance Commitment**: Ensuring adherence to Fil+ guidelines and allocation rules

## Additional Metrics and KPIs

We track and report the following metrics to measure pathway success:

- **Allocation Efficiency**: Time from application to allocation
- **Storage Success Rate**: Percentage of allocated DataCap successfully stored
- **Geographic Distribution**: Diversity of storage provider locations
- **Data Redundancy**: Average number of replicas maintained
- **Retrieval Performance**: Success rate and speed of data retrievals
- **Client Compliance**: Adherence to allocation guidelines and SP distribution requirements
- **Network Growth Contribution**: Total data onboarded to Filecoin network
- **Application Processing Time**: Average review and approval duration

## Application Process

Applications are managed through GitHub issues using the LDN (Large Dataset Notary) template, which captures:
- Client information and verification
- Project details and data descriptions
- DataCap requirements and distribution plans
- Storage provider commitments
- Compliance confirmations

Each approved application is tracked through JSON files in the `/applications` directory, providing full transparency of the allocation lifecycle.

## Code of Conduct

This repository adheres to a Code of Conduct to maintain a respectful and productive environment for all participants. By contributing to this project, you agree to comply with its terms.

---

We are committed to enabling a streamlined and transparent process for DataCap allocations within the Filecoin Plus program. Thank you for your interest and participation.
