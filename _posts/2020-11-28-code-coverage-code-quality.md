---
layout: post
title: "Code coverage gate of hell :fire:"
---

# {{page.title}}

## Big number does not make me smarter

I was reading Alan Tai's nice article [Why don’t developers use TDD in practice](https://ayltai.medium.com/why-dont-developers-use-tdd-in-practice-b1e2362d4676) when a sentence punched me:

> Code coverage has nothing to do with code quality (...)

It seems an obvious statement to me. But does it sound obvious to every tech people in my company ? No.

![bart](/blog/assets/2020-11-28_bart.png)

## Focus on what matters

I used to work in companies where code quality and code coverage are seen as synonyms. CTO and architects define once and for all a gate limit (e.g. 80 %) in the company's code analysis tool (e.g. [SonarQube](https://www.sonarqube.org/)), and some kind of linting rules. Projects have now to respect these constraints to be built or deployed. Then they think that projects' code quality is going to improve, thanks to these hardcore constraints. 

What it really does:
- it forces developers to reach this absurd limit
- it infantilizes developers 
- it does not promote writing high valued tests, but it creates a distrust climate, a "whatever makes this fucking code coverage/quality gate happy will be fine"
- some developers are going to bypass or troll the quality gate, because of annoyance or project needs (users don't care about code coverage, but they want new features or bugs to be fixed) 

This is harmful. A virtuous circle could be to incite developers to write tests, to use linters, instead of forcing them to do so. 

We cannot focus on everything. So we need to choose wisely which topics to focus on, and how to start working on them or improving them. Then we can find tools to help achieving the defined goals. Only humans can assess what can be improved, how to work on code quality in a specific context.

Metrics can help ? Sure can use them. As the tools, they have to be guided by goals, not just for the sake of having figures.  


## Going further 

These long articles can help to grab more information about code coverage.  

- [Is Code Coverage a Useless Metric?](https://medium.com/better-programming/is-code-coverage-a-useless-metric-bc76e0fde9e)
- [Why code coverage is not a reliable metric](https://dev.to/conectionist/why-code-coverage-is-not-a-reliable-metric-327l)
- [What is Code Coverage and Why It Should Not Lead Development](https://capgemini.github.io/testing/What-Is-Code-Coverage-and-Why-It-Should-Not-Lead-Development/)
- [Code Coverage vs Test Coverage — Which Is Better?](https://dzone.com/articles/code-coverage-vs-test-coverage-which-is-better)
- [Code coverage is a useless target measure](https://blog.ploeh.dk/2015/11/16/code-coverage-is-a-useless-target-measure/)
