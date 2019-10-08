# Selecting Empirical Methods for Software Engineering Research

https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.81.9285&rep=rep1&type=pdf

## Abstract

- Benefits and challenges with each different method are not catalogued
- This is a basis for understanding and selecting from the variety of methods

## 1. Introduction

- Inappropriate methods are selected because of lack of knowledge
- software engineering is a multi-disciplinary field
- cognitive processes surrounding software engineers
- because of the importance of human activities, many of the methods are derived from studying individuals and teams
- there is no silver bullet as the selected method depends on so many different things like resources, access to subjects, skills of the researcher
- Jane and Joe are used as examples throughout this paper
- Their research questions are addressed, and after that each type of research is looked from their point of view

## 2 What kind of research question are you asking?

- *exploratory questions*
  - Existence questions, description and classification questions, descriptive-comparative questions
- the research questions can be answered through literature survey or empirical studies
- *base-rate*
  - frequency and distribution questions
  - descriptive-process questions
- *relationship*
  - relationship questions
- common mistake to confuse correlation with causality
- much harder to demonstrate causality than to show correlation
- *correlation and causality*
  - causality questions
  - causality-comparative questions
  - causality-comparative interaction
- *non-empirical*
  - design questions

## 3 What will you accept as an empirical truth?

- the nature of the truth will be different for academic researchers and industry practitioners
- epistemology (the nature of human knowledge, and how we obtain it) and ontology (the nature of the world irrespective of our attempts to understand it).
- be explicit about the philosophical stance you are taking 
- *positivism* ≃ reductionists
  - has been under a lot of critic lately
  - dominates the natural sciences
  - controlled experiment, survey research, and case studies
  - you have to convince yourself that the phenomenon you are interested in can be studied in isolation from its context
- *constructivism* ≃ interpretivism
  - the human context is always there, and therefore as important as the actual meaning of the theory
  - concentrates more on understanding how different people make sense of the world
  - For example, an anthropologist studying the culture of a software design team might seek to find out how different members of the team think about and use the tools they have available, and build local theories that explain why this particular team uses tools in the way that they do
  - ethnographies, exploratory case studies, and survey research
- *critical theory*
  - research is a political act
  - prefer participatory approaches
  - critical theorists tend to take emancipatory and advocacy roles
  - open source movement, process improvement community and the agile community
  - case studies to draw attention to things that need changing
  - action research most closely reflect the philosophy of critical theorists
- *pragmatism*
  - truth is whatever works at the time
  - truth is relative to the observer
  - pragmatism adopts an engineering approach to research
  - mixed methods research
- 

## 4 The Role of Theory Building

- the different philosophical stances differ in their ideas about the role of theory
- *positivism*
  - expect their theories to have strong predictive power => generalized models of cause-and-effect
- *constructivists*
  - expect theories to strengthen their understanding of complex situations
- simpler more elegant theories are preferred
- the theory becomes a *"lens"* trough which the world is observed
  - quantitative => theoretical lens used to determine which variables to isolate and measure
  - qualitative => theoretical lens is often applied after data is collected, to focus the process of labeling and categorizing ("coding") the data
- *Grounded Theory*
  - initial analysis of the data begins without any preconceived categories
  - then during the research the theory "emerges" from the analysis
  - new qualitative data is compared with old qualitative data 
- traditionally software engineering researchers have been poor at making theories explicit and therefore results have been difficult to compare

## 5 Selecting Methods

- Research Design is the process of selecting a method for a particular research problem
- the following methods are derived from other fields, but are typical to software engineering

### 5.1 Controlled Experiments

- uses dependent variables and measures how they are related to each other and whether cause-effect relationship exists between them
  - simplest example is using a tool vs. not using a tool
- requirement is clear hypothesis
- experimental method is closely tied to the positivist stance
- reductionist => reduce complexity by limiting and controlling variables
- experiments are theory-driven
  - strength: reduces problems of "fishing for results"
  - weakness: being theory-driven forces us to decide in advance which variables to ignore, that might turn out to be important outside the laboratory setting
- quasi-experiments
  - subjects are not assigned randomly to the treatments

### 5.2 Case Studies

- exploratory vs confirmatory
  - a detailed case study of a real situation in which a theory fails may be more convincing than failed experiments in the lab
- precondition: clear RQ of how or why certain phenomena occur
- study proposition
- purposive sampling instead of random sampling
- critical case, extreme or unique case, typical case
- literal replications vs theoretical replications
- qualitative data as interviews and observation play a central role
- unit of analysis: company, project, team, individual dev
- weaknesses
  - data collection and analysis is more open to interpretation and researcher bias
- exploratory case studies (Kitchenham 2005)

### 5.3 Survey research

- questionnaires for data collection
- structured interview or data logging techniques
- precondition is a clear RQ
- with the example of Joe there are many different ways he could design the study
- positivist tradition
- "if joe is more interested in understanding the culture of information sharing within development teams, he might instead adopt a constructivist stance, and use ethnography or action research"

### 5.4 Ethnographies

- goal is to study a community of people to understand how the members of that community make sense of their social interactions (Robinson et al 2007)
- avoids imposing any pre-existing theories, instead focuses to explain the member's own social and cultural setting
- researcher explicitly considers his/her own pre-conditions and how they influence understanding of the studied community
- chain sampling => informants within the community are asked to identify representative members of the community
- Joe: "He identifies a development team that allows him to observe design meetings for several weeks"
- participant observation
  - not trying to understand the community via the observations of an outsider, but by the privileged view that comes from membership
  - in software engineering becoming a member might require the right technical background
- explicit constructivist stance
  - don't seek to prove hypotheses and theories, but rather create local theories
- biggest challenge in ethnographic research is to avoid preconceptions
- Ethnographies in SE are important to discover what actually is going on in particular technical communities, and to reveal subtle but important aspects of work practices

### 5.5 Action Research

- attempt to solve a problem, and at the same time studying the experience of solving the problem
- adopted in education and information science as the results might take several years to emerge
- debate if action research is a valid empirical method
- problem owner
- criteria
  - problem must be authentic
  - there must be authentic knowledge outcomes
- characterized by a commitment to effect real change, and an iterative approach to problem solving
- Joe could test out MDD with some practitioners
- it would be unethical to withhold the intervention (the change) from some groups
- emphasis is on identifying useful lessons that help others
- The key characteristic that differentiates action research from longitudinal case studies and ethnographies is that the researcher is also an agent of change.
- biggest challenge is immaturity
- action research suitable for practitioners

### 5.6 Mixed-Methods Approaches

- a more complex research strategy that emerged with the recognition that all methods have limitations
- the researcher might have to deal with multiple data sources, both quantitative and qualitative,
- *sequential explanatory strategy (Damian et al 2000)*
  - quantitative data collection and analysis followed by the collection and analysis of qualitative data
  - good when the initial quantitative data shows some unexpected results
- *sequential exploratory strategy (Damian and Chisan 2006)*
  - qualitative data collection and analysis followed by quantitative
  - use quantitative data to assist in interpretation of qualitative findings
  - as a results of Joe's ethnographic study, he plans and conducts a survey of many different software development projects
- *concurrent triangulation strategy (Bratthall and Jørgensen 2002)*
  - uses different methods concurrently to confirm, cross-validate, or corroborate findings
  - by collecting data concurrently results from one study can be used to the another one
- positivist: combine experiments with confirmatory case studies
- constructivist: mix ethnographies and surveys
- mixed methods research is more often associated with a pragmatist stance, where focus in on using methods that most effectively address the research problem

## 6 Data Collection Techniques (Wohlin, et al. (2003), Seaman (Chapter 2))

- triangulation
- researchers should be familiar with the selected techniques
- pilot-test the collection, but also the analysis

## 7 Empirical Validity

- *construct validity*
  - if jane designs an experiment to test her claims about the efficiency, will she interpret "efficiency" the same way as others?
- *internal validity*
  - whether the results really do follow from the data, misuse of statistical analysis
- *external validity*
  - students as subjects might not be generalizable
- *reliability*
  - same result yielded when others replicate? 
- when reporting positivist empirical studies, it is important to include a section on "threats on validity"
- constructivists have more difficult assessing validity
  - assumption that the reality is "multiple and constructed", therefore repeatability is simply not possible
  - Creswell (2002) eight strategies for improving validity of constructivist research
    1. triangulation
    2. member checking
    3. rich, thick descriptions
    4. clarify bias
    5. report discrepant information
    6. prolonged contact with participants
    7. peer briefing
    8. external auditor
 - Dittrich, et al. (2007) define also a similar set
- critical theorists
  - redressing a perceived injustice, or challenging existing perspectives
  - repeatability not relevant because of context specific problems
  - there should be clear knowledge outcomes for the participants

## Practical considerations

- important to document the original planned research protocol, and all the deviations from it so that other researchers are able to follow
- *methods that are primarily qualitative*
  - ethnography, case study, and action research
  - participant observation and interviews
  - ethnography requires the status of member
  - action research requires balance between involvement of the organization to set goals and remaining objective => research should not become merely consulting
- *methods that are primarily quantitative*
  - controlled experiments and survey research
  - plan ahead for smooth collection and analysis
- in industry it can be very hard to find out what actually is done or needs improvement, rather than what is said to be done and stated to require improvement (Singer and Vinson 2002, 2004)
- Hawthorne effect

## Conclusions

- clear research question + explicit philosophical stance + appropriate research method = success
- research method helps to design a study and what data to collect and analyse
- theory helps to explain the data and relate it to the research question and previous studies
- appropriate set of criteria
- replication and meta-analysis is not discussed in this paper
  - results need to hold up across many different studies to be considered reliable
  - meta-analysis is hard in software engineering contexts
- empirical research never produces certain knowledge

## Personal interpretations from the text

- intro in this text is quite interesting from a point of view of developer experience
  - it could be used in the introduction of the thesis
- divide down the research question as in chapter 2 in this text
  - define what type the questions that are asked are
- this study is going to be "exploratory"
- what will the philosophical stance be in this thesis?
  - constructivism and critical theory?
- could there be some kind of ethnography study made at the company based on the observations
  - there would be a lot of bias
- write more about the different steps of the MLR
- what could the unit of analysis be in this master thesis?
  - individual developer?
- no problem owner in this thesis?
- *example*
  - conduct a workshop(s) with the think-pair-share format, where the initial findings and definition of DX is formed
  - based on the results of the workshop(s) create a survey that will be sent out for all the developers in the company
  - or then conduct interviews
- what are focus groups?
- where did the think-pair-share framework come from?