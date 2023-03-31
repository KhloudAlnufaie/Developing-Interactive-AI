# Developing-Interactive-AI



---
This is a college project required for an artificial intelligence course.<br>
It is done as teamwork by Alhanouf Almansour, Khloud Alnufaie, Raghad Albosais and Weaam Alghaith.
---

### Project overview
Artificial Intelligence is the science of making agents think and act humanly and rationally. During this course, we were taught some of theoretical knowledge in AI and this project is a sheer implementation of that knowledge. The project is an interactive AI tutorial about Search problem. Search algorithms divided into two types(as illustrated in Figure1): Informed search algorithms and Uninformed search algorithms. The Uninformed Search (Blind Search) is searching without “information” about the goal node. Whereas The Informed Search (Heuristic Search) is searching with “information” about the goal node. We focus here on informed search algorithms, specifically A* and implement it to solve the Route-Finding Problem for emergency exit. We formulated the problem and explained how to implement the A* algorithms from scratch then applied the A* algorithm on the problem and compared between performance of heuristics used.

![Figure1 : the search algorithm](https://github.com/KhloudAlnufaie/Developing-Interactive-AI/blob/main/images%20and%20animation/Search%20algorithm.jpg)

---
### Problem
Problem explanation<br><br>
A scenario where a fire occurred in a building and you would have to look for the nearest emergency exit in one floor of building depending on sign boards provided in the building.

Problem formulation<br><br>
    
- Initial state: location of person that stops and looks to reach the nearest emergency exit.
- Goal state: emergency exit.
- Goal test: is the current state the emergency exit?
- Actions: move from one sign board to another.
- Successor function: gives us one of the possible adjacent sign board from the current sign board.
- Path cost function: distance between two sign boards and between sign board  and emergency exit in meters.
- Solution: is sequence of movement taken by the person from sign board to another until reaching the emergency exit with minimum path cost and least possible time.
- State space: set of sign boards connected with each other to reach the emergency exit.

---
### Tools


- Softwares: 

![Google colab](https://img.shields.io/badge/Googlel%20Colab-0078d7.svg??style=flat&logo=google-colab&logoColor=orang)
---

### Running the project
The whole project is located in the google colab notebook file ``` AI_Project_AlhanoufKholodRaghadWeaam.ipynb ``` and , you can use the Google colab environment to open the Notebook and install the requirement.

---
### Contributors

[@KhloudAlnufaie](https://github.com/KhloudAlnufaie)

[@RaghadKhaled](https://github.com/RaghadKhaled)

[@Weaam20](https://github.com/Weaam20)

