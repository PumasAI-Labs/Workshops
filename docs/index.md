---
title: Pumas-AI Workshops Templates
description: Workshops templates for Pumas-AI PKPD workflows.
---

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

| Category                         | Title                                                                  |                   Site                    |            Repository            |               Reference               |           Instructor Notes            |
| -------------------------------- | ---------------------------------------------------------------------- | :---------------------------------------: | :------------------------------: | :-----------------------------------: | :-----------------------------------: |
| Julia                            | Julia Variables and Types                                              | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Julia                            | Julia Syntax                                                           | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Julia                            | Julia Functions                                                        | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Julia                            | Julia Functional Programming                                           | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| NLME                             | Population, Model Blocks and Fitting                                   | [:material-window-maximize:](https://pumasai-labs.github.io/NLME-Model/) | [:material-github:](https://github.com/PumasAI-Labs/NLME-Model) | [:material-eye-outline:](https://pumasai-labs.github.io/NLME-Model/reference/) | [:material-plus-circle:](https://pumasai-labs.github.io/NLME-Model/instructors/) |
| NLME                             | Model Assessment                                                       | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| NLME                             | Covariates, Dose Control Parameters, and PKPD Indirect Response Models | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| NLME                             | Visualization with `PumasUtilities`                                    | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| NLME                             | Non-Gaussian and Time Manipulation                                     | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Discrete Modeling                | Logistic Regression                                                    | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Discrete Modeling                | Poisson Regression                                                     | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Discrete Modeling                | Time to Event                                                          | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Bayesian                         | Introduction to the Bayesian Workflow                                  | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Bayesian                         | Markov Chain Monte Carlo (MCMC)                                        | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Bayesian                         | Model Comparison                                                       | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| `DeepPumas`                      | Introduction to `DeepPumas`                                            | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Data Wrangling and Visualization | Data I/O and `DataFramesMeta`                                          | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Data Wrangling and Visualization | Visualizations with `AlgebraOfGraphics`                                | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |
| Simulation                       | Simulation and Decision Making using Pumas                              | [:material-window-maximize:](PLACEHOLDER) | [:material-github:](PLACEHOLDER) | [:material-eye-outline:](PLACEHOLDER) | [:material-plus-circle:](PLACEHOLDER) |

## Requirements Workflow

```mermaid
graph TB
  J1[Julia Variables\nand Types] --> J2[Julia Syntax];
  J2 --> J3[Julia Functions];
  J3 --> J4[Julia Functional\nProgramming];
  J2 --> N1[Population,\nModel Blocks\nand Fitting];
  N1 --> N2[Model Assessment];
  N2 --> N3[Covariates,\nDose Control Parameters,\nand PKPD Indirect\nResponse Models];
  N2 --> N4[Visualization\nwith PumasUtilities];
  N3 --> N5[Non-Gaussian and\nTime Manipulation];
  N1 ----> D1[Logistic\nRegression];
  N1 ----> D2[Poisson\nRegression];
  N1 ----> D3[Time to\nEvent];
  N1 --> B1[Introduction\nto the\nBayesian\nWorkflow];
  B1 --> B2[Markov Chain\nMonte Carlo];
  B2 --> B3[Model\nComparison];
  N1 ----> DP1[Introduction\nto DeepPumas];
  J2 --> DA1[Data I/O\nand DataFramesMeta];
  J2 --> DA2[Visualizations\nwith\nAlgebraOfGraphics];
  N2 & J3 ----> S1[Simulation\nand Decision\nMaking\nusing Pumas];

  %% This is a good color blind friendly palette
  %% https://gist.github.com/tpoisot/ad38a5ed789cc549b2140f9688447ccd
  %% From https://www.nature.com/articles/nmeth.1618
  classDef orange fill:#e69f00, color:#000000;
  classDef blue fill:#0072b2, color:#ffffff;
  classDef skyblue fill:#56b4e9, color:#000000;
  classDef yellow fill:#f0e442, color:#000000;
  classDef green fill:#009e73, color:#ffffff;
  classDef vermillion fill:#d55e00;
  classDef reddishpurple fill:#cc79a7;

  class J1,J2,J3,J4 orange;
  class N1,N2,N3,N4,N5 blue;
  class D1,D2,D3 yellow;
  class B1,B2,B3 skyblue;
  class DA1,DA2 green;
  class S1 vermillion;
```

## Workshop Checklist

If you are planning to run a Pumas workshop please make sure you have checked
for all of the items above:

1. :material-check: **Decide on which workshop curriculum** from the table above
   would best serve your learners.
   Check for all the pre-requisites in the curriculum,
   specially previous pharmacometrics knowledge.
   Some workshops curricula depend on another workshop curriculum
   for the best learning experience,
   make sure that your learners can fully enjoy the workshop you are planning.
   Finally, all of the workshops curricula have learning personas,
   learning objectives, teaching notes, and timetables.
   For the best experience, we recommend following them.
1. :material-check: **Clone the desired workshop template repository** by clicking the
   GitHub green button "Use this template".
   This will create a copy of the workshop template as your personal repository.
   We don't recommend additions or modifications to the curriculum,
   except for changing the data files examples.
1. :material-check: **Rehearse** at least once with the curriculum timetables to build confidence
   and also make sure that the workshop will be properly conducted.
   Check the teaching notes to avoid common pitfalls
   while conducting the workshop.
1. :material-check: **Arrange for all required materials and equipment**.
   If your workshop is virtual provide an online meeting platform
   with the required capabilities for screen sharing and
   attendees participation.
   If your workshop is on premises provide the space, seating,
   and any other necessary equipment such as projectors
   to the execution of the workshop;
   don't forget to plan for coffee breaks with beverages and food.
   If you plan to record your workshop, either virtual or on premises,
   make sure you have the consent for all attendees, and,
   if necessary the hosting institution.
1. :material-check: **Email learners with instructions** on how to have access to Pumas,
   installation procedures, and any other requirements such as
   downloading data and code.
   Additionally, users should be aware of the **Code of Conduct**
   and abide by it at all times not only during the workshop,
   but in any related activities.
1. :material-check: **Keep close contact with learners** by reminding them about deadlines,
   and emailing them a couple days before the workshop to remind them
   about any requirement.

## Get in touch

If you have any suggestions or want to get in touch with our education team,
please send an email to <training@pumas.ai>.

## License

This content is licensed under [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/).

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)
