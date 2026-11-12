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
As a bioinformatics student, I want to find research papers about genes of interest, so that I can 
conduct my research in an organized manner. 
  - I also want to change the # of papers shown on the search results page. 
### User Story 2
As a bioinformatics student, I want to organize papers based on different genes so I can learn its
relationship with the gene of interest.
### User Story 3.1
As a researcher, I want to view a paper's URL, title, authors, and abstract,
so that I can determine whether the paper is relevant to my research.
### User Story 3.2
As a researcher, I want to save links to research papers,
so that I can easily access them again in the future.
### User Story 4
As a researcher, I want to be able to search through my previously annotated/noted papers with 
keywords，so that I can quickly retrieve information I have previously recorded.
### User Story 5
As a researcher, I want to store all my read papers under different gene categories so that it is 
organized
### User Story 6
As a researcher, I want to remove papers from my saved collection, so that I can keep my research 
library focused on the most relevant and useful literature.
### User Story 7
As a user, I want to create an account so that all my records are confidential for privacy reasons
### User Story 8
As a user, I want to be able to log off my account so that the next person opening the app will not
be able to sabatoge my notes
### User Story 9
As a user, I want to be able to write notes under the abstract so that I can keep track of what each
paper is talking about and what are some key information extracted.



5.As a researcher, I want to manage comments on research papers, so that I can discuss and share insights about the papers with other researchers.

---

## Use Cases
### Search the Paper
Search by keywords(PubMed API) , Adjust result count, View paper details

### Build Personal Paper Library
Save papers, Remove papers, Organize saved papers by gene categories, View Saved Papers, View Papers by Gene

### Gene Interaction Management
Add Gene, Remove Gene, Open Gene in Genome Browser (UCSC), Create gene relationships, Edit gene relationships, Remove gene relationships, Visualize gene relationship graph

### PDF Managment
Upload PDFs, Associate PDFs with papers, Open PDFs, Delete PDFs, Extract Text from PDF, Search Within PDF

### Comment the Paper
Add the common for the paper, Edit the common for the paper, Delate the common for the paper, View the common for the paper

### Manage User Account
create account, login account, logout account

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
