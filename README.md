## Student Information
- Name: Galgalo Molu Halake  
- Registration Number: 669377  
- Course: APT3020B  

## Project Description
This project implements a simple **rule-based knowledge inference system** using forward chaining.  
Facts are represented as triples in the form **(subject, relation, object)**, and logical rules are applied to infer new facts from existing knowledge.

The system demonstrates classical logical reasoning using well-known philosophical examples such as Socrates, Plato, and Hypatia to determine whether individuals are mortal based on their classification as men or women.

## Implemented Logic
- Initial facts describe individuals and their classifications (man or woman).
- Two inference rules are defined:
  - If a subject *is a man*, then the subject *is mortal*.
  - If a subject *is a woman*, then the subject *is mortal*.
- A forward-chaining mechanism repeatedly applies these rules to the known facts.
- Newly inferred facts are added to the knowledge base until no more inferences can be made.
- A query function allows retrieval of all subjects that satisfy a given condition.

## Originality Change
To ensure originality, the knowledge base was extended by adding **Plato** as an additional example of a man alongside Socrates.  
This modification preserves the original reasoning logic while expanding the set of inferred results and differentiating the submission from standard examples.

## Output
The program displays:
- The initial set of facts
- Newly inferred facts as they are generated
- The complete list of inferred facts after reasoning concludes
- The result of a query identifying all individuals classified as **mortal**

The final output confirms that **Socrates, Plato, and Hypatia** are all inferred to be mortal based on the applied rules.
