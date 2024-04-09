# ZK-SNARK-Designer

# Final Challenge Project

This repository contains the implementation for the Final Challenge project, which involves writing a circuit, compiling it, generating proofs, deploying a Solidity verifier contract, and verifying the proof.

## Project Structure

- `circuit.circom`: Contains the implementation of the circuit using circom.
- `compile.js`: Script to compile the circom circuit into JSON format.
- `generateProof.js`: Script to generate proofs using the compiled circuit.
- `Verifier.sol`: Solidity verifier contract to verify proofs on-chain.
- `deploy.js`: Script to deploy the Verifier contract to the Sepolia or Mumbai Testnet.
- `test.js`: Script to test the verification of proofs using the deployed Verifier contract.

## Getting Started

1. Clone this repository to your local machine.
2. Install dependencies: `npm install`.
3. Update the circuit implementation in `circuit.circom` as needed.
4. Compile the circuit: `node compile.js`.
5. Generate proofs: `node generateProof.js`.
6. Deploy the Verifier contract: `node deploy.js`.
7. Test the verification: `node test.js`.

## Requirements

- Node.js
- Hardhat
- Circom

## Project Rubric

To successfully complete the Final Challenge, the project should:

1. Have a correct circuit implementation.
2. Compile the circuit to generate circuit intermediaries.
3. Generate a proof using specific inputs, for example, A=0 and B=1.
4. Deploy a Solidity verifier to the Sepolia or Mumbai Testnet.
5. Call the `verifyProof()` method on the verifier contract and assert the output is true.

## License

This project is licensed under the [MIT License](LICENSE).
