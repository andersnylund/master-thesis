# Informing the design of new mobile development methods and tools

## What is Abstract

- It has become difficult to develop for mobile settings
- aim to gain a better understanding of the engineering problem and how developers currently work
- commonalities and differences between various native mobile and web-based approaches including the different kinds of tasks and the effort expended on them

## What is Introduction

- it's a major challenge to create UIs for all the different mobile technologies
- requires different programming language skills, SDKs, and also design and maintenance
- The New York times offer 6 application, but does not cover all devices
- discussions between native and web
- this study aims to understand the design and implementation effort when migrating from desktop applications to mobile platforms
- diary study
- the aim
  - identify the main tasks for development on current mobile platforms
  - determining commonalities and differences in the approach (**of what?**)
  - collecting feedback on the development experience
  - identifying factors that contribute to better development experience (DX) 
- observations
  - framework usability and productivity
  - both technical and subjective criterion
- contribution
  - metrics and approaches to guide selecting an mobile strategy for an application

## What is Experiment

## What is Results

- different kinds of work: reading docs, UI design and impl, impl of application logic, testing and debugging, other
- during the time of the experiment, the iterations got faster and faster as there was many concepts that were the same e.g. JSON, HTTP requests, even if the language and development framework changed
- most commonly UI was implemented first, and then after that the logic
- in the diaries and interviews the researchers picked up statements from the participants, and they can be found from table 3
- android UI was difficult
- iOS good IDE, but Objective-C caused problems
- Windows Phone well established support of Visual Studio, link between UI and code was good
- Web was non-standardized but ran of course on all platforms
- experience with the platforms was divided into
  - technical
  - subjective
  - productivity 
- no real overall winner, even if the web had the best score. This score is caused by the possibility to deploy to all platforms
- conclusion of the best platform was: IDE like XCode, main-stream programming language as Java or JavaScript, link between UI and Code as in Visual Studio, easy deployment as with Android or web

## What is Discussion and Future Work

- device-specific implementation has problems, but has become the new norm
- mismatch between framework usability and platform reachability
- the more platform can be reached with one tool, the worse the development experience
- there is a need for multi-device engineering solutions
- the authors are going to explore environments where the authoring could be performed with help of the real device, and not emulators or by simulating the device 
- 

## Personal thoughts about the text

- Quite old article, from "pre-react-native" era 
- It will be interesting to see how the mobile development ecosystem look like in 2013 and before that. Will it have the same problems as now, or will it have changed? 
- Even if there is no explicit mention of DX, the research topic looks like it could be about measuring the developer experience between 
- Developing software is difficult to measure, because no one ever wants to write the same stuff twice
  - It seems however like that they did write the same application 4 times in this study?