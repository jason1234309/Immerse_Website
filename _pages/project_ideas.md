---
layout: default
title: Project Ideas For IMMERSE
---

### Entry Level Suggestions

* [Create a JSON schema for the Yosys JSON format. #7](https://github.com/SymbiFlow/ideas/issues/7)
    * For this project, the student will need to learn how JSON files are formatted but I feel that this will not be too difficult.

* [Symbiflow Examples Repo](https://github.com/SymbiFlow/symbiflow-examples)
    * I know this is a interesting Repo to work with, especially as it has been improved over the past year.
    * Working with Tim we have the plan that the student working with the Symbiflow Examples Repo will contact the developers for [projectF](https://projectf.io/) and the developers of [FPGA Design Elements](http://fpgacpu.ca/fpga/index.html) to see if we can add their finished examples to the examples repo, and to link our sites together so that the viewers will visit all of our sites.
    * Another step will be to improve the documentation of the examples repo so that all the instructions are clear and easily followed for new and inexperienced users.
    * the Final piece of the project is to convert several examples from the 220 labs into verilog code and then to upload them to the examples repo
    * the parts of this plan can be completed in any order or can be down at all at once, but it would be easier to work on the documentation at the same time as creating new example projects for the repo.
    * this project will take some studying of make and the programs in the tool chain, but I feel that the challenge will not to be to difficult and that the challenge will make this an interesting project

* [SymbiFlow projects documentation audit #56](https://github.com/SymbiFlow/ideas/issues/56)
    * This project will be a documentation audit of the documentation across the key repositories to verify that the documentation covers all the important information needed to be able to understand and work on the repositories in question.
    * the person who issued the request, [Kgugala](https://github.com/kgugala), also asked that the student who works on this project also work with the developers to be able to address key questions that users may have so that the documentation will be able to help all new comers and existing users to be able to continue working.
    * He also asked that the student also look at the introductory paragraphs and make them clearer, and better at grabbing the attention of the reader.
    * This project may not be the most exciting, but it will lead to a great overview of the Symbiflow tool chain as the student will need to study the documentation fo all the major repositories and experiment with them to create the desired documentation changes.
    * the repository that may make this project hard is that the symbiflow-arch-defs repository was listed under the repositories that need to be audited and that repository will not be easy to fix.

* 

### Experienced level Suggestions

* [Create a "common configuration" git repository which is auto-merged into SymbiFlow projects #51](https://github.com/SymbiFlow/ideas/issues/51)
    * This could be a very interesting project, but I feel that it will require understanding the basic formats of all the file types used in symbiflow, which are many.
    * It will also involve learning about how the Symbiflow repositories and projects are organized so that the auto merger can be implemented.
    * There is also a piece involving Travis CL which would be interesting.
    * This issue is a joining of the last few issues that Tim submitted that address common code or documentation formats:
        - [#50](https://github.com/SymbiFlow/ideas/issues/50) -
        - [#49](https://github.com/SymbiFlow/ideas/issues/49) -[#9](https://github.com/SymbiFlow/ideas/issues/9) is related to #49.
        - [#47](https://github.com/SymbiFlow/ideas/issues/47)
        - [#46](https://github.com/SymbiFlow/ideas/issues/46)
    * These issues seem very similar to the issues joined together by Tim:
        - [Standardize formatting across all repos #27](https://github.com/SymbiFlow/ideas/issues/27)
        -[Convert yosys documentation to be sphinx compatible #8](https://github.com/SymbiFlow/ideas/issues/8)
    * These issues could be separated into a few different projects but I feel it is important to see that Tim had joined them all together.
    * People have been working on the above issues but they are not finished.

* [Package all of SymbiFlow dependencies into a conda repository #14](https://github.com/SymbiFlow/ideas/issues/14)
    * I think this project will take a decent understanding of both conda and how conda handles dependencies but this could solve the problem of having multiply environments during instillation of the different tools.
    * I wonder if this could be extended to move all the Symbiflow repos to conda.

* [Community issue / bounty tracker #58](https://github.com/SymbiFlow/ideas/issues/58)
    * I am unsure what is it will take to create the bounty tracker but it seems like it would be an interesting project for someone to create a system in Symbiflow that allows for issues to be voted on and for those issues to receive donated bounties to finish them. I imagine the system will need to organize the issues based on which have the highest vote count.
    * It could also be good to have this system be separate from the issues repo but draw the information from that repo some how.

* SLURM test suites
    * This project involves first learning what SLURM is and how it functions.
    * What I found on SLURM is that it helps with processor task scheduling to allow faster execution.
    * After the student is familiar with SLURM, they would be asked to convert the test suites to run with SLURM across the Symbiflow repositories.

* Improving netlistsvg and other visualization tooling.
    * I am not very familiar with netlists, so I am not sure what this project entails but from my understanding the student would need to research netlists, especially the types that are commonly created and used by the varies programs that make up the Symbiflow toolchain.
    * This project could be interesting because it covers an area that is not well understood, but this could make it difficult to start.

* [SystemVerilog parser using Tree-Sitter #44](https://github.com/SymbiFlow/ideas/issues/44)
    * The issue as listed is not very clear on what is expected, but I believe that Drom was asking for someone to work on making the parser Tree-Sitter compatible with system verilog.
    * From what I found in the issue it appears that Tree-Sitter is one of the verilog parsers used in the Symbiflow tool chain, and Drom is hoping for someone to extent the compatibility from just verilog to work with system verilog as well.
    * I am uncertain how difficult this project would be, as well as I am unfamiliar with the community of Tree-Sitter. both of these problems could prevent this idea from being a student project, but if it is feasible; paving the way for Symbiflow to work with system Verilog would be very large success.
* [Convert the Verilog to Routing test runner from Perl to Python #16](https://github.com/SymbiFlow/ideas/issues/16)
    * This issue discusses how there are several scripts written in different code languages throughout the Symbiflow project, and they should all be converted to python
    * I am unsure if this project was finished, but Professor Goeders and a student were working on this issue last summer, so they would more accuratly know the state of this issue.
    * As this was a student project last summer, if it is unfinished it could be a good project this summer


### High Understanding Required level Suggestions

* [Add a Verilog / SystemVerilog support to Sphinx #11](https://github.com/SymbiFlow/ideas/issues/11)
    * I looked into what Sphinx is and it is a documentation tool that uses reStructuredText as its markup language.
    * Looking at the conversation surrounding the issue, it seems like it would be an interesting project, but I feel that it would be fairly difficult.

* ?[Create a parser for the XDC file format #2](https://github.com/SymbiFlow/ideas/issues/2)
    * This issue was submitted in 2017 so it may be complete and they forgot to close it or it may still be unfinished
    * This issue is that the Symbiflow tool chain needs a parser for the XDC file format
    * I believe that this would be a fairly hard project, as I created a parser this last winter in CS 236, and it took a lot of work with very clear guidelines. I think that maybe a student would be able to contribute to this parser but I am unsure where to begin
    * Looking at yosys-symbiflow-plugins/xdc-plugin/xdc.cc file it seems that XDC files are supported by Yosys using the tcl parser with a XDC plug in, so it seems that there isn't a need for a XDC parser, but maybe it was a temporary fix?

### Group Ideas and Other Ideas

*[Create a series of user stories documents #55](https://github.com/SymbiFlow/ideas/issues/55)
    * This issue is an idea to create a repository that contains stories and case studies of how individuals or groups have used Symbiflow to create unique tool chain elements(or a completely unique tool chain) that allowed them to do things that are not possible in commercial tool chains, or even other more streamlined versions of Symbiflow.
    * I have labeled this a group project idea because it seems like an interesting idea to ask the faculty and students that have been working with Symbiflow to see if they can write their experiences for this repository, but the most likely outcome is that the faculty are the only ones who would have experience creating a unique tool chain with Symbiflow.
    * As an idea for a student project would be to reach out to [Kgugala](https://github.com/kgugala) and see if the student can create and manage this repository, as well as search for the individuals and groups that have the desired stories.
* [Add Contributing Guide to SymbiFlow projects #53](https://github.com/SymbiFlow/ideas/issues/53)
    * this issue sounds interesting, as it would entail contacting the main contributors of Symbiflow and creating a style guide for all the code that is being contributed across the whole Symbiflow project. I imagine it will also give advice and hints on push requests and other important information for contributors.
    * I think this could be a interesting project because it would involve working with several people across all the repositories, but I do not think that it is our place as students at BYU to be forming the contributing guide for the Symbiflow tool chain.
    * This project could be very frustrating as well if the contributors refuse to agree on one style or expectations for the contributions.

### Where Credit is Due

* The majority of these project Ideas are found on the issues page of the Symbiflow github repository followed by notes that I have written to describe the pros and cons of the project ideas. there are a few projects that I worked with others to create the idea and their contributions are listed below.

* [Symbiflow Examples Repo](https://github.com/SymbiFlow/symbiflow-examples)
    * Tim ‘mithro’ Ansell- He asked for this project to be worked on specifically and he answered all questions asked on how the project should be completed.
    * Professor Nelson -He was the one who created the 3 part plan that will lead to a effective completion of what Tim desires to happen.

*SLURM test suites
    * Tim ‘mithro’ Ansell- He asked for this project to be worked on specifically.
*Improving netlistsvg and other visualization tooling.
    * Tim ‘mithro’ Ansell- He asked for this project to be worked on specifically.

