# Detecting and Reporting Object-Relational Mapping Problems: An Industrial Report

## Abstract

- a framework that detects and reports a family of ORM problems
- aim to assess how practitioners perceive the framework
- observational study
- DX: developers experience with the framework
- overall better results when using the framework, but some unintuitive annotations

## Introduction

- 67.5% of Java developers use ORM frameworks
- redundant data problems might cause loss of performance in enterprise applications
- misuse of RM code: using wrong annotation or referring to wrong column
- ORM-related problems are very domain specific

## 2. Background

## 3. Context

- a development team had to write JPA entity classes without always having the most up to date version of the database at hand
- this caused problems that are now reported

## 4. The mapping problems

- a series of programming errors occurred when implementing the entity classes
- there was often no time to fix the errors and new features were prioritized before fixing old problems
- the result of the errors cause burden and stress on the development team

## 6. The Developer Experience study

- developers with very different skill leves should be able to use the framework and point out strong points and opportunities

### 6. A DX Findings

- Benefits
  - find what is missing
  - better error messages
  - developers with no experience of JPA were able to complete the task
  - training material
  - forces best practices
- challenges
  - custom annotation were not intuitive
  - documentation is scarce
  - poses many constraints 