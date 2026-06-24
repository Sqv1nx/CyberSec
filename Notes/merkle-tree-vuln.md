# Merkle Tree Vulnerabilities

## Second Preimage Attack
- Given leaf node, forge proof for different data
- Affects naive implementations without leaf prefix

## Length Extension
- Internal nodes not distinguished from leaves
- Fix: prefix leaves with 0x00, internal with 0x01
