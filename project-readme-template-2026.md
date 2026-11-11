# Project Name

## Team Information

### Team Members
- Yicheng Xia
- Haixin Wang
- Tony Shi
- Yixin Xu
- William Chen

---

## Project Description

A research paper manager that links bio-informatics paper and link papers based on genes mentioned. 

### Domain

Productivity/ Acedemic Research

---

## User Stories

### User Story 1
As a bioinformatics student, I want to find research papers about genes of interest, so that I can conduct my research in an organized manner. 
  - I also want to change the # of papers shown on the search results page. 
### User Story 2
As a bioinformatics student, I want to organize papers based on different genes so I can learn its relationship with the gene of interest.
### User Story 3
As a student reading papers, I want to upload pdf to link so that I can see them later.
### User Story 4
As a researcher, I want to be able to search through my previously annotated/noted papers with keywords
### User Story 5
As a researcher, I want to store all my read papers under different gene categories so that it is organized
### User Story 6
As a researcher, I want to delete papers so that in case the paper is irrelevant to any scope within my project
### User Story 7
As a user, I want to create an account so that all my records are confidential for privacy reasons
### User Story 8
As a user, I want to be able to log off my account so that the next person opening the app will not be able to sabatoge my notes
### User Story 9
As a user, I want to be able to write notes under the abstract so that I can keep track of what each paper is talking about and what are some key information extracted.

---

## Use Cases

### Use Case 1
User upload a pdf and/or a link for a academic paper, saves the paper with a title and description.
Exception: the paper already exists, a popout window asks if user still want to continue. 
### Use Case 2
User had loaded multiple papers sharing research interest on gene A and B. papers are clustered based on whether they focused on these genes.
### Use Case 3

(Add additional use cases as needed.)

---

## Minimal Viable Product (MVP)

| Team Member | MVP Use Case |
|-------------|--------------|
| Name | Use Case |
| Name | Use Case |
| Name | Use Case |

---

## Entities

### Entity 1
paper: one piece of paper, in pdf or link form

### Entity 2
research topic: a piece of gene or other research subject of interest

### Entity 3
mind map: an generated graph illustrating link between research

(Add additional entities as needed.)

---

## API Usage

**API Name:**
arXiv API
**Documentation:** [Link]
https://info.arxiv.org/help/api/user-manual.html
**How it is used in the program:**
Search for academic papers.

**API Name:**
Europe PMC REST API
**Documentation:** [Link]
https://europepmc.org/restfulwebservice
**How it is used in the program:**
Search and categorize academic papers.

**API Name:**
NCBI E-utilities
**Documentation:** [Link]
https://www.ncbi.nlm.nih.gov/home/develop/api/
**How it is used in the program:**
gene normalization
---

## Design Diagrams

### UML Class Diagram


### Sequence Diagrams

---

## How to Run

[Instructions for running the program.]
Start the main program.

---

## Notes

[Any additional project information.]

--
## Data Persistence

Each paper will be stored as a JSON object, including link to the paper, file path to local copy, relevant comments, and a list of genes in that paper. The last shown graph will be cached and saved. 
