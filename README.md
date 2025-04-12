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
  "abi": [/* 0x6080604052600080fdfea264697066735822122095fed2c557b62b9f55f8b3822b0bdc6d15fd93abb95f37503d3f788da6cbb30064736f6c63430008000033 */]
}
```
2. Ensure ABIs are:
   - Exactly as deployed
   - Unmodified from compiler output
   - Properly formatted

## Verification Requirements
- ABIs must match deployed bytecode
- Contract names must exactly match deployed names
