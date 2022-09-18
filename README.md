# ProofID
Is a credibility soul bounded token that allows people to proof their financial status to 3rd party entities using zero knowledge. With ProofID you can make your data your own. Protecting your personal information is our top priority, with ProofID to take the control back to your hands.


## Team

- Fernando Salvago
- Adrià Torralba Agell
- Hassel Alcalá 
- Lorena Koehlmoos
- Denny Portillo 

## How is the project built?

### Zero-Knowledge Proofs

In order to provide privacy in this project, we have used an advanced technology called **Zero-Knowledge Proofs** which enabled us to prove a number of statemens without revealing nothing else than the mere fact that the statement is True. We currently have implemented and tested the **Proof of Solvency** which allow to prove that a certain person has a monthly salary greater than a certain arbitrary amount.

Due to time constraints, we could not include 2 other proofs which are based on the same circuit design. Namely, 

- **Proof of Salary**: allows to prove that someone earn more than a certain amount for a period of 12 months.
- **Proof of Legal Age**: allows to prove that someone is of legal age without disclosing the birthdate or the their age.

We have used Circom with SnarkJS to build circuits which use Groth16 as the proving system.


## Development Stack

- **NextJs**: A very popular React framework. It is one of the most loved framework from the community.

- **Wagmi**: A collection of React hooks which bundle all the requirements to build with Ethereum. From queries to signs, going through interaction with Smart Contracts.

- **RainbowKit**: Conectivity made easy for React Developers. Mady by the Rainbow Wallet team.

- **TailwindCSS**: A utility framework that enable a configuration set which is consistent with a lot of custom development components.


- **Alchemy**: RPC provider. This platform make dev life easier when doing the dApps architecture. OpenSea, Chainlink and Meta are between its available clients.

- **Hardhat**: Integrated Development Environment (IDE) for Ethereum, Smart Contracts, Testing, Debugging and Tooling for Solidity.

- **Typescript**: Typed Javascript-like programming language.

Repo links:
- Backend: https://github.com/fernantho/proof-id-backend
- Contracts: https://github.com/EdsonAlcala/proof-id)
- Circom circuits: https://github.com/0xAdriaTorralba/EthBerlin3Hackathon
- Video demo: https://www.youtube.com/shorts/aocf9FwsCzk



