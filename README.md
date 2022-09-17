# Proofly

Is a credibility soul bounded token that allows people to proof their financial status to 3rd party entities using zero knowledge. With Proofly you can make your data your own. Protecting your personal information is our top priority, with Proofly to take the control back to your hands.


## Team

- Francisco Espejo 
- Fernando Salvago
- Adrià Torralba Agell
- Edson Alcalá 
- Hassel Alcalá 
- Lorena 
- Denny Portillo 

## How is the project built?

### Zero-Knowledge Proofs

In order to provide privacy in this project, we have used an advanced technology called **Zero-Knowledge Proofs** which enabled us to prove a number of statemens without revealing nothing else than the mere fact that the statement is True. We currently have implemented and tested the **Proof of Solvency** which allow to prove that a certain person has a monthly salary greater than a certain arbitrary amount.

Due to time constraints, we could not include 2 other proofs which are based on the same circuit design. Namely, 

- **Proof of Salary**: allows to prove that someone earn more than a certain amount for a period of 12 months.
- **Proof of Legal Age**: allows to prove that someone is of legal age without disclosing the birthdate or the their age.

We have used Circom with SnarkJS to build circuits which use Groth16 as the proving system.










