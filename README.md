# MegaETH Testnet Contract ABIs

Repository containing verified contract ABIs for MegaExplorer.

## Purpose
- Provide ready-to-use verified ABIs for MegaETH testnet contracts
- Maintain a standardized format for explorer verification
- Ensure compatibility with blockchain explorers' ABI validation

## To add new verified contracts:
1. Create an entry in `abis.json` with:
```json
"CONTRACT_ADDRESS": {
  "name": "ExactContractName",
  "abi": [/* Full unmodified ABI from compilation */]
}
```
2. Ensure ABIs are:
   - Exactly as deployed
   - Unmodified from compiler output
   - Properly formatted

## Verification Requirements
- ABIs must match deployed bytecode
- Contract names must exactly match deployed names
---

## Contributor: gttte

This update adds a verified ABI entry for a new test contract to the MegaETH Testnet ABI repository.
All ABIs follow the official verification format and are compatible with MegaExplorer validation tools.

- Verified ABI source: local Remix compilation
- Verification type: Manual validation and formatting check
- Status: Ready for merge

