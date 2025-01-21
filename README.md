
# Water Seller

This is a tool for handling local processes in order to run OasisLMF products. 

## Installation
To install the package with pip use the following command:

```bash
pip install git+https://github.com/OasisLMF/water_seller.git     
```

## Usage
Water seller currently supports the following processes:

### Local OasisLMF Installation
This process installs the OasisLMF (v2.3.5) package locally and installs the required dependencies. This is essential if you
want to run OasisLMF on a Mac ARM64 machine. To install the package locally use the following command:

```bash
ws-install-oasislmf --extra
```
This will install the [OasisLMF](https://github.com/OasisLMF/OasisLMF) (v2.3.5) package  directly from the [corresponding tag](https://github.com/OasisLMF/OasisLMF/releases/tag/2.3.5).
