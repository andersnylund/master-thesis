# API Designers in the Field: Design Practices and Challenges for Creating Usable APIs

## Abstract 

- APIs are a growing industry
- APIs suffer from usability problems
- API design is learned on the job
- use case design
- lacking tools of gathering feedback 

## 1 Introduction

- APIs are very common in all kind of different contexts
- primary way that businesses deliver data
- DX is impacted by the quality of the API
- early feedback is important
- user testing
- documentation
- SDK generators

## 2 Related Work

### 2A API Usability

- good usability results in better code, and incorrect use results in bugs and security problems
- semantic design, level of abstraction, the quality of docs, error handling, preconditions and deps all affect the difficulty of learning and using an API
- backwards compatibility is tricky

### 2B API Design

- static analysis tools can provide valuable information about API usability issues
- API style guide by Google and Microsoft
- some software engineering books also provide guides on API design

### 2C Understanding The API Design Process

- The usability of APIs is known the some degree, but the design process is not known that well
- lacking
  - understanding the needs of API designers
  - process of design, implementation, release, and maintenance
- however, the overall software engineering process has been studied

## 3 Methodology

- structured interviews with API designers
- 505 code -> 41 specific labels -> themes

## 4 Participants

- average of 16 years of programming experience
- REST API, other Web API, Other library or SDK API

## 5 Results

### 5A Learning to Design APIs

- learned only from work experience
- API designers primary goal is to understand their user's goal  
- a non API designer would only look from their own viewpoint
- teaching could be done without the pressure from business critical real-world scenarios and with basic usability and UX methods

### 5B Using Existing Guidelines

- subjects were active contributors to API guidelines
- some subjects felt that the guidelines weren't specific enough for application => custom team specific guidelines were often created 
- code reviews and linters to enforce consistent API
- **consistent experience to the learning curve**
- clashing guidelines is a problem and designers need to learn to decide which guideline to follow

### 5C Who designs an API?

- the requirement of an API comes from upper management
- UX people would be beneficial in creating the high-level abstractions and naming conventions, but often the case is that UX designers get overwhelmed by the technicality of designing an API
- usability concerns around the DX is the responsibility of the API designers (software engineers)
- designing an API should be an interdisciplinary team effort

### 5D Designing an API from scratch

- too much effort and time is put into edge cases that is not the major selling point of the API
- bottom-up API design, is when not understanding the customer, the API is designed to mirror the underlying implementation and not like the users actually want it
- API users have been known to depend on aspects of the API as line numbers 🤯
- abstractions and core methods has to be right the first time
- early user input and feedback is valuable

### 5E Getting User Feedback on Initial API Design

- when creating public APIs, designers tried to imagine themselves as future users
- user stories and personas of UX have been used in API design
- peer reviews with other developers
- prototyping
- 0 to 200 (HTTP OK response) / Time to Hello World
- formal usability testing is rare and too time consuming
- hackathon style lunch where users do "think aloud" protocol
  - predefined tasks
  - no teaching
  - be open to negative feedback

### 5F API Design Review: Key to Ensuring Quality

- **ALL** participants used design and code reviews
- automatic tools like linters take care of the low level stuff, so that doesn't need to be in the review 
- a dedicated person or group who does the reviews

### 5G Web and REST APIs

- pagination seemed to be a problem in REST APIs
- amount of information is difficult to get right
- solved by GraphQL?

### 5H Documentation & User Starting Experience with an API

- first encounter with API determines adoption or not
- discoverability of documentation and the intuitive usage is a problem for designers
- designers use also stackoverlfow and other sources of information to fill gaps in their documentation
- Stripe API was mentioned to be excellent 
- new APIs might have the cold start problem (lack of community on SO)
- example projects and code snippets help to get people going (framer-motion)

### 5I Feedback & Usage are Hard to Measure, Hard to Interpret

- feedback in internal API is easier to get
- even if public APIs provide metrics and data, it is difficult to infer and make conclusions based on that
- most reliable public feedback comes trough GitHub issues

### 5J Automatic Generation of SDKs & Documentation

- some designers really liked the auto-generated SDKs and said they were indistinguishable from the hand written APIs 
- Swagger API tooling was used, but not for auto-generation
- generation required huge amount of processing power => limited the available changes that could be made 

### 6 Limitations

### 7 Conclusions

## Personal thoughts about the text

- Is creating an API for a backend service included in this?
- The subjects are probably from the massive corporations like Google and Microsoft
- This article is considering the different roles required in API design quite well
- It captures the developer experience in itself, not from the point of view of the user, but the designer themselves
- This paper relates to requirements engineering in so many different ways
- **User Starting Experience**