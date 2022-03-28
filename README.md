# SmartChart-Core

This repository contains the core deployment of SmartChart, including:
- RC-API
- CQF Ruler

For full documentation, please see: READ THE DOCS LINK

# Quick Deployment
This section of this README is intended for a fast reference. Please read the full documentation linked above before deploying for the first time.

## 1. Clone
Clone the core repository and its submodules with the following command:
```
git clone --recurse-submodules https://github.com/SmartChartSuite/SmartChart-Core.git
```

As CQF Ruler uses Git LFS (Large File System) you may to additionally do the following. Navigate into the submodule directory with `cd cqf-ruler`.

Then execute the Git LFS Fetch with:
```
git lfs fetch --all
```

This should indicate a significant amount of data is being fetched. From there you can navigate back into the parent (core) directory with `cd ..`.

## 2. Configure

## Deploy