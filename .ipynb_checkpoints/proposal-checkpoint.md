# Community Software Analysis Proposal

Please edit this file and push to your repository.

## Software: LinearSolve

The software is meant to help with solving linear systems within Julia while not taking an eternity. The package itself is meant to be able to perform fast on relatively small problems while being able to handle large-scale systems in a reasonable time. The main audience for this package is those that want to use the SciML package to perform at a better rate. The reason for that is the SciML is meant to be for scientific machine learning which is why they would need a fast linear algebra solver hence LinearSolve.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL |  https://github.com/SciML/LinearSolve.jl?tab=contributing-ov-file  |
| Main/documentation website |  https://docs.sciml.ai/LinearSolve/stable/  |
| Year project was started | 2021 |
| Number of contributors in the past year | <!--- `git shortlog -se --since=2024-03-01` may be useful -->  Not including bots, it would be 28 since Oct. 8th, 2024|
| Number of contributors in the lifetime of the project | 63 |
| Number of distinct affiliations | 5-10 <!--- Julia Lab at MIT, Carnegie Mello University, JuliaHub, Weierstrass Institute, Carbon Engineering, University College London, WIAS-PDElib, with atleast 10 commits --> |
| Where do development discussions take place? | <!--- e.g., GitHub/GitLab issues, mailing list, Slack, etc. --> They use a combination of Zullip and Slack |
| Typical number of emails/comments per week? | It seems that they usually have 20ish comments a day so most likely 100 comments per week |
| Typical number of commits per week? | From 5-15 commits on average |
| Typical commit size | <!--- `git log --shortstat`  may be useful --> Around 5-10 bullet points |
| How does the project accept contributions? | <!--- e.g., pull requests, patches on mailing lists --> This project accepts contributions through pull requests |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | no |

### Install and run

Check the following boxes when complete or add a note below if you encountered a problem.

- [X] I have installed the software
- [X] I have run at least one example
- [X] I have run the test suite
- [ ] The test suite passes (Note 1)


### Notes/concerns/risks

Please comment on any anomalies or known risks to following this project, if you were unable to answer any questions above, or otherwise have concerns about the appropriateness of the software.
If the project requires a contributor license agreement or other procedural steps, please explain here.
"None at this time" is acceptable for this question.

(Note 1) The test suite will not run, I am not sure what it is. But my most likely guess is that there is not enough memory to run the whole suite on coding.csel.io environment which is what is causing the issue. 
None at this time for the contributor license agreement

#### Note on copyright

Students retain copyright on any work done in completion of a CU course, so you are authorized to sign a [contributor license agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement), affirm a [developer's certificate of origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin), etc.
If you have concerns about this, please note them and/or reach out to your professor directly.
