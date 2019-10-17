# Supporting the Developer Experience with Production Metrics

## Abstract

- utilization of APM (application performance management) produces a lot of data that is not utilized in providing information to developers
- data can be harnessed to enhance the developer experience, and possible tools
- tracing and monitoring services give clues about how the software is behaving in the production environment

## 1 Introduction

- aim to harness production data to add targeted actionable information to developer tooling

## 2 Problem areas

### 2A Exposing execution trees

- the mental model of what is verified by tests might differ from the software running in the production environment
- this could be e.g. the execution paths of the software

### 2B Reporting Exceptions

- process production logs and report that to the developer working on exactly that part of the codebase

### 2C What is deployed where?

## 3 Related work

## 4 Challenges

### 4A Tracking changes

### 4B Collecting Data

## 5 Research Road Map

- end-to-end toolchain that collets data from web applications, stores it in som metric database, and later shows it in the IDE e.g. JetBrains family
  - collecting metrics in a way that doesn't harm the performance
- can data be presented to the developer when change in the code happens?
- building tools for developer productivity, and therefore the evaluation will be focused around the developer experience
- how does this all affect the everyday life of developer's work 

## Personal thoughts about the text

- the idea of showing how the software behaves in real time will probably be something that will improve significantly in the future
  - generally the feedback loop of software development has gotten shorter and shorter the whole time
  - in the time of the punch cards the feedback loop could be days, as first the programmer had to write the instructions, and then wait for their turn to run the software on the expensive and rare machine
  - today replication of production environments allow developers to run the whole system on their local machine, and in e.g. web development the feedback loop is instant
- in the future there could be a possibility to constantly run the software e.g. backend code, with simulated usage, and that usage could be represented in the IDE as in this article   