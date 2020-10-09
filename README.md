# "Multi-language Code Generation for Computational Workflows" book

This repository has chapters, code, and organizational materials for the (very technical) book
"Multi-language Code Generation for Computational Workflows".

***The book is not finished yet -- it is a work in progress...***

## Mission statement

To describe how from natural and programing languages specifications to make parsers and interpreters
for the generation of actionable or executable code.

## The approach in brief

We develop and utilize Domain Specific Languages (DSLs) for natural language workflows.

For the target computational workflows we assume the existence of packages that provide 
monadic programming pipelines for the workflows.     

We have parsers for DSLs that interpret DSL sentences (commands) into code for
targeted (monadic) packages.

## Programming languages

- Parsers and interpreters: [Raku](https://raku.org), [Wolfram Language (WL)](https://www.wolfram.com/language/).

- Computational workflows: Julia, Python, R, WL.

## Exposition plan

More or less a "standard" exposition plan is followed:

- Motivation 
 
  - (Why we care? What we try to accomplish?)
 
- Brief overview 

  - Approach taken
  
  - Functionalities or challenges to address
  
  - Limitations
  
- How the parsers are made?

- How the interpreters are made?

- Special efforts and use cases

- Future work 

  - And how to redo the whole thing

## Who is the intended reader?

Developers interested in:

- Computational workflows

- Parsers and interpreters

## Code and related repositories

Two major types of code and related repositories: for parsing and interpretation, for computation.
See the references below.

## Videos

- ["useR! 2020: How to simplify Machine Learning workflows specifications (A. Antonov), lightning"](https://www.youtube.com/watch?v=b9Uu7gRF5KY),
(2020), 
R Consortium at YouTube.

- [Multi language Data Wrangling Translation - talk advertisement](https://www.youtube.com/watch?v=OHY64ezgnm4),
(2020),
Anton Antonov at YouTube.

## References

### Articles

[AA1] Anton Antonov,
["How to simplify Machine learning workflows specifications? (useR! 2020)"](https://mathematicaforprediction.wordpress.com/2020/06/28/how-to-simplify-machine-learning-workflows-specifications-user-2020/),
(2020),
[MathematicaForPrediction at WordPress](https://mathematicaforprediction.wordpress.com).


### DSL repositories

[AAdr1] Anton Antonov, 
[DSL::English::DataQueryWorkflows Raku package](https://github.com/antononcube/Raku-DSL-English-DataQueryWorkflows), 
(2020),
GitHub.

[AAdr2] Anton Antonov, 
[DSL::English::EpidemiologyModelingWorkflows Raku package](https://github.com/antononcube/Raku-DSL-English-EpidemiologyModelingWorkflows), 
(2020),
GitHub.

## Computational workflows repositories

[AAcr1] Anton Antonov, 
[Epidemiology Compartmental Modeling Monad in R](https://github.com/antononcube/ECMMon-R), 
(2020),
GitHub.

----
Anton Antonov   
Windermere, Florida, USA   
2020-10-09
