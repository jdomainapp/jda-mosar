Generating RESTful Full Stack Software
=============


| Author | Version | Date 
| :--: | :--: | :--: |
| [Duc Minh Le](mailto:lemduc@gmail.com) | 1.0 | 05 Oct 2021 |

# Technical report
[Full version](docs/jda-restful-report-full.pdf) of the paper submitted to the ICISN'22 conference.

# CourseMan Example
## Domain Model
![The domain model of CourseMan](docs/images/courseman-model.png)
<div align="center">Figure 1. The domain model of CourseMan.</div>

## Source code
[Source code zip file](dist/example/restfstool-example-courseman.zip)
- `modules`: the domain model and associated MCCs, organised into modules
- `software`: the SCC and executable software
- `utils`: domain-specific utility classes
- `exceptions`: domain-specific exceptions
- `backend`: the generated backend (in Spring Boot)
- `frontend`: the generated frontend (in React.js)

# Binary distribution 
Binary distribution of module RESTFSTool as part of the JDA framework.

[Download link](dist/module-restfstool.jar)

## How to execute the generator functions

