{
  "title": "Zero Knowledge Battleship",
  "date": "2025-11-12",
  "link": "https://github.com/zeinshehab/battleship-zk",
  "image": "/img/basic_merkle_tree.png",
  "description": "A full zero-knowledge proof implementation of the Battleship game using the gnark proving system (Groth16) and a custom MiMC-based circuit. The project demonstrates private board commitment, constraint programming, and on-chain/Verifier-level proof checking for secure gameplay without revealing secret information.",
  "tags": ["Cryptography", "Zero-Knowledge Proofs", "gnark", "Go", "Groth16", "MiMC", "Constraint Systems"],
  "fact": "",
  "featured":true,
  "weight": 100
}

Zero-Knowledge Battleship is a fully functional implementation of the Battleship game using modern zero-knowledge proof systems. The system allows players to prove the correctness of their moves without revealing their private board configuration.

The project uses the **gnark** ZK framework in Go and implements:

- **Board commitment:** Players commit to their hidden board using a MiMC-based hash Merkle tree.
- **Custom ZK Circuit:** A Groth16 circuit enforces legal Battleship placement, adjacency rules, boundary constraints, and hit/miss correctness without revealing ship positions.
- **Proof Generation & Verification:** Every move produces a Groth16 proof that the verifier checks against the committed board.
- **Constraint Programming:** Full constraint logic for board encoding, adjacency rules, ship structure, and witness consistency.
- **CLI Tooling:** A commandline interface for generating commitments, producing proofs, and verifying moves step-by-step. Designed for reproducibility and debugging.
- **Web Interface:** A web frontend that allows two players to play Battleship interactively while all shots and responses are verified through real zero-knowledge proofs behind the scenes. The web UI communicates with the prover and verifier components transparently.

This project demonstrates how zero-knowledge proofs enable private, verifiable computation and provides a practical introduction to ZK engineering, including circuit design, witness generation, constraint reasoning, and proof serialization.
