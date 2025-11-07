# Fair Data Publisher

<div align="center">
  <img src="./images/mission-ki-logo.png" alt="MISSION KI Logo" height="100">
  <img src="./images/bmdv-logo.png" alt="BMDV Logo" height="100">
</div>

---

## Repository Status: Archived Original Implementation

This repository has been repurposed for new content. The **original Fair Digital Objects (FDO) implementation** has been completely archived and remains permanently accessible through multiple methods.

---

## Access the Original FDO Implementation

### Download Complete Archives

| Format | Size | Download Link |
|--------|------|---------------|
| TAR.GZ | 3.3 MB | [fair-data-publisher-original-2025-09-02.tar.gz](https://github.com/Mission-KI/Fair-Data-Publisher/releases/download/archive-original/fair-data-publisher-original-2025-09-02.tar.gz) |
| ZIP | 3.5 MB | [fair-data-publisher-original-2025-09-02.zip](https://github.com/Mission-KI/Fair-Data-Publisher/releases/download/archive-original/fair-data-publisher-original-2025-09-02.zip) |
| Checksums | 223 B | [checksums.txt](https://github.com/Mission-KI/Fair-Data-Publisher/releases/download/archive-original/checksums.txt) |

### Browse Online

- **Archive Branch**: [archive/original-implementation](https://github.com/Mission-KI/Fair-Data-Publisher/tree/archive/original-implementation)
- **Release Page**: [archive-original release](https://github.com/Mission-KI/Fair-Data-Publisher/releases/tag/archive-original)

---

## Archive Information

### What's Included

The archived implementation contains the complete Fair Digital Objects infrastructure with **15 modules**:

#### Core Components
- fdo-manager-service - Core service for FDO management
- fdo-manager-sdk - SDK for FDO Manager integration
- fdo-manager-clients - Client libraries
- fdo-doip-request-models - DOIP request models

#### Adapters
- fdo-aas-adapter - Asset Administration Shell integration
- fdo-edc-adapter - Eclipse Dataspace Components connector
- fdo-doip-b2share-adapter - B2SHARE integration
- fdo-s3-doip-adapter - S3 storage integration

#### User Interface
- fdo-manager-webui - Web-based management interface

#### Testing & Development
- fdo-manager-e2e-tests - End-to-end tests
- fdo-local-testbed - Local test environment
- fdo-test-handle-system - Handle system tests
- fdo-testbed-jupyter-notebooks - Jupyter notebooks for testing

#### Deployment
- fdo-manager-deploy - Deployment configurations

### Archive Details

- **Archive Date**: November 7, 2025
- **Last Commit**: `69be7afb660d99fb235d236d53459f215a9abab0`
- **Commit Date**: September 2, 2025
- **Total Files**: 459 files
- **Author**: P.C.

---

## How to Use the Archives

### Extract TAR.GZ Archive

```bash
tar -xzf fair-data-publisher-original-2025-09-02.tar.gz
cd fair-data-publisher-original-2025-09-02
```

### Extract ZIP Archive

```bash
unzip fair-data-publisher-original-2025-09-02.zip
cd fair-data-publisher-original-2025-09-02
```

### Verify Archive Integrity

```bash
# Download checksums file
curl -LO https://github.com/Mission-KI/Fair-Data-Publisher/releases/download/archive-original/checksums.txt

# Verify checksums (macOS/Linux)
shasum -a 256 -c checksums.txt
```

**Expected Checksums (SHA256):**
- `fair-data-publisher-original-2025-09-02.tar.gz`:
  `5ac678f2cf30874d3591338f34d5773112e2758898f57690535e27f8522cd820`
- `fair-data-publisher-original-2025-09-02.zip`:
  `e3cc4dd6eb76fcbccbb6ca91c8c40630b5a64da0a41c7b52c01f87fe04570337`

---

## Original Project Information

### Goal

Implementation of Fair Digital Objects (FDOs) for standardized data exchange between data spaces.

### Key Features

- **Standardization**: Unified format for data and metadata
- **Interoperability**: Seamless exchange between different data spaces
- **Persistent Identification**: Legally traceable through PIDs
- **Integration**: Compatibility with Eclipse Dataspace Components (EDC)

### FAIR Principles Implementation

- **Findable**: Unique and persistent identification
- **Accessible**: Secure access and exchange
- **Interoperable**: Cross-system compatibility
- **Reusable**: Sustainable data structuring

For more information about the FDO concept, visit [FAIR Digital Objects](https://fairdo.org/).

---

## New Content

*This section will be updated with new project information.*

---

## License

This project is licensed under the MIT License.

## Contact

For questions about the archived FDO implementation:
- General: git-mission-ki@acatech.de

---

**Last Updated**: November 7, 2025
