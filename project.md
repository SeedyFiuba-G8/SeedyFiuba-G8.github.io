---
title: Project Information
description: Administrative and development team details
---

<!-- ##################################################################### -->

# Description

This platform was the integrating project of the subject [**Taller de Programación II**](https://taller-de-programacion-2.github.io/), in which we were challenged to make contact and integrate different [technologies](tech.html) that are used in the current Software Development industry in order to obtain a fully functional system.

<!-- ##################################################################### -->

# Details

- **Subject:** Taller de Programación II
- **Term:** First.
- **Year:** 2021.
- **Tutor:** Gonzalo Petraglia.

## Development team

| Team Member       | University ID | Mail                   | GitHub                                        |
| ----------------- | ------------- | ---------------------- | --------------------------------------------- |
| Mauro Parafati    | 102749        | mparafati@fi.uba.ar    | [mauro7x](https://github.com/mauro7x)         |
| Nicolás Aguerre   | 102145        | naguerre@fi.uba.ar     | [nicomatex](https://github.com/nicomatex)     |
| Santiago Klein    | 102192        | sklein@fi.uba.ar       | [sankle](https://github.com/sankle)           |
| Taiel Colavecchia | 102510        | tcolavecchia@fi.uba.ar | [TaielC](https://github.com/TaielC)           |
| Yuhong Huang      | 102146        | yhuang@fi.uba.ar       | [tonyhuang07](https://github.com/tonyhuang07) |

<!-- ##################################################################### -->

# Team Organization

Although it was of extreme interest to all the team members to be able to have **contact** with [**each of the proposed technologies**](tech.html), given the high level of **complexity** of the project as well as its **extension**, and taking into account the **little time** available to carry it out, we decided to perform an **assignment of components and responsibilities**.

In a first stage, the **different components of the system were identified**, at the same time that the **architecture** to be used was **designed**. This process was carried out with **participation of all members**. Once this was completed, we followed with the _assignment stage_.

When dividing development tasks and system components, we took into account **personal interest** rather than **experience**, as we believe that this assignment presented a very good opportunity to **learn**. The division was as follows:

| Team Member       | System component(s)                             |
| ----------------- | ----------------------------------------------- |
| Mauro Parafati    | `Backend microservices`, `Mobile`               |
| Nicolás Aguerre   | `Mobile`                                        |
| Santiago Klein    | `Backend microservices`, `Smart Contracts`      |
| Taiel Colavecchia | `Backoffice web`, `API Keys`, `Smart Contracts` |
| Yuhong Huang      | `Backoffice web`                                |

In any case, throughout the project all members were able to **contribute their points of view** and **perspective** regarding the work carried out by others, allowing **constant improvement**.

We are very happy with the final division of the project, as we all felt that we learned **a lot** about things that interest us in depth.

## Dates

- **04/15/2021:** Project started.
- **04/22/2021:** Checkpoint 0.
- **05/13/2021:** Checkpoint 1.
- **06/10/2021:** Checkpoint 2.
- **07/08/2021:** Checkpoint 3.
- **07/29/2021:** Partial project presentation.
- **08/02/2021:** Final project presentation.

## Team feedback

- **Mauro Parafati**: _"Personally, I found many opportunities to learn from this assignment, both personally and professionally/academically. I got to know many new technologies that were of interest to me, I had a great space to develop my curiosity in certain areas, as well as I was trained in Team Software Development through the implementation of agile work methodologies along with my teammates. I am very happy with the results obtained!"_
- **Nicolas Aguerre**: _"Even though things can always be improved, I feel like we've come to a point where we are satisfied with our product. All of its functionalities work, and they are enough for it to work as an actual crowdfunding platform."_
- **Santiago Klein**: _"The realization of this project was essential to learn and use cutting edge technologies and practices that are crucial for a software engineer to master. Even though we would like to enhance some features of our project, we are proud to have covered basic functionality by exploring a wide range of technologies."_
- **Taiel Colavecchia**: _"This was a great and challenging experience for the group. Even though the organization (mainly, at the beginning) was poor, with hard work and learning about the new technologies we accomplished a great startup funding application that is based on a decentralized currency."_
- **Yuhong Huang**: _"It has been a pleasure to work with my teammates, during this experience we learned things that we haven't seen before, we orgnizaed and solved problems together, although many things could be improved, I think we achieved something quite significant."_

## Results obtained

We are really happy with the results obtained, again, given the complexity and extent of the work. We believe that many improvements could be made, but it would take more time and greater time availability by the development team, since this work was carried out in parallel with different subjects and the personal work of each of the members, making it impossible to dedicate a longer time for the results to be ideal.

In any case, we believe that **the objective was achieved**, **learning a lot** and achieving a **functional and complete final product**.

<!-- ##################################################################### -->

# Post-mortem analysis

In retrospective, after concluding the project, there are some technical decissions we made that ended up with side effects that were not deeply considered due to the lack of a profound vision at the beginning of the project.

On the one hand, the introduction of an **API Gateway** brought up a significant overhead in development, since we needed to make an additional integration for every endpoint/functionality provided to the clients, as well as mantaining many _API Specs_ at the same time. Even though we could successfully concentrate the authentication in this microservice, providing users a single point of entry to the entire backend, we believe we should have reconsidered incorporing it due to the lack of time we had in the development of the project, and the overhead it meant. Nonetheless, we were able to simplify code in the consumed microservices, relieving them of responsabilities, and avoiding duplicated authentication code, which positively impacted the entire project.

Furthermore, another aspect that we found controversial was the incorporation of tests from the beginning of the development. There were several times in which we had to deeply change the way endpoints worked, forcing us to rewrite tests accordingly. Although we naturally believe testing is essential for ensuring the well functioning of the application and the integrity of development, as well as for the provision of stability, there is always this tradeoff between _flexibility_ and _robustness_ of code. In particular, since we had to develop the project from zero, maybe a more flexible approach should have been more convenient.

There are also some features that we would have liked to implement, but due to the lack of time we could not be able, e.g, the cancellation of projects, password recovery, etc. We are aware that there are always improvements to be made regarding UX in both mobile and web admin, but we are overall satisfied with the final product.

All in all, we have experienced the construction of a complex project from scratch, which has proved to be a substantial contribution to our knowledge and professional (and, not least, personal) development.

<!-- ##################################################################### -->
