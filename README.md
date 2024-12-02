# Artificial Creativity: Combining Evolutionary Computing with LLMs for Creative Scriptwriting
This repository contains my **Master's Thesis** developed at Instituto Superior Técnico (University of Lisbon) in collaboration with Politecnico di Milano.

- [View short version (10 pages article)](https://github.com/rodrigosdlopes/thesis-2024/blob/main/Rodrigo_Lopes___MSc_Thesis_Extended_abstract.pdf)
- [View full thesis document (PDF)](https://github.com/rodrigosdlopes/thesis-2024/blob/main/Rodrigo_Lopes___MSc_Thesis.pdf)

**Abstract:** This thesis explores the integration of Large Language Models (LLMs) with Evolutionary Computing, as a tool for creative writing, particularly in the domain of movie idea generation. Our work adopts an exploratory approach, designed to assist human scriptwriters (users) in their creative process.

Our methodology involves generating new movie plots based on traits of existing films, using them as 'inspirational' movies, along with user-provided guidelines. In this context, movies are treated as free-form text objects, that will be generated and manipulated by the LLM and evolved by the Evolutionary Algorithm. The usage of a Genetic Algorithm (GA) serves the purpose of combining, mutating, selecting and evaluating new ideas for movie plots, allowing the most promising ideas to be further exploited. The LLM will be employed during the recombination, mutation and evaluation phases of the GA. Since the evaluation phase involves utilizing different objective functions to determine the overall quality of the newly generated ideas, both single- and multi-objective optimization methods were tested, alongside GPT-3.5 and GPT-4o models.

Our approach showed significant potential, with movie plots evolving through generations, resulting in new ideas that meet the desired requirements. We consistently generated new plots by selecting three 'inspirational' movies from a database of 42,306 films. Best results were achieved with GPT-4o, single-objective optimization and a large population size. 
Finally, we collected human feedback to validate the fitness scores assigned by the LLM. Regardless of the limitations encountered, our work successfully combined different Data Science paradigms to generate creative content. 

**Key Words:** Large Language Models (LLMs); Evolutionary Computing; Genetic Algorithms; Evolution Through Large Models; Scriptwriting
