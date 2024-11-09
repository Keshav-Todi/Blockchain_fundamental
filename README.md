# Blockchain_fundamental
This project will demonstrate the principles of blockchain, such as block creation, hashing, and proof of work.

This project involves building a simple blockchain that allows for adding blocks and verifying the chain.

**Explanation**

Block Class: Each block stores its index, previous hash, data, timestamp, nonce (for proof of work), and hash. The calculate_hash function generates a SHA-256 hash for the block.

Mining: The mine_block function finds a hash that meets a difficulty level by adjusting the nonce, simulating proof of work.

Blockchain Class: Manages the blockchain, including creating a genesis block, adding new blocks, and validating the chain.

Validation: is_chain_valid checks that each block’s stored hash is correct and that each block’s previous_hash matches the hash of the previous block.

**How to Run :**

Save the code to blockchain_fundamental.py.
Run with python blockchain_fundamental.py.
This project serves as a foundational example, showcasing how blockchains store data securely through hashing and linking, as well as verifying data integrity.
