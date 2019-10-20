# Guidelines for including grey literature and conducting multivocal literature reviews in software engineering

https://www.sciencedirect.com/science/article/pii/S0950584918301939

## What is Abstract

- MLR is a SLR which includes the grey literature
- Both state-of-the-art and state-of-the-practice is included from the given area
- MLR differs from SLR, and therefore this paper exists
- The created guidelines cover all steps of an MLR
- The created guidelines can be used in any are of SE 

## 1. What is Introduction

- SLR only consider the formally published literature, while not taking grey literature into account
- This grey literature is constantly produced by SE practitioners outside of academic forums
- Grey literature (GL) can offer a glimpse into emerging research topics in SE, as SE research topics already stem from the industry
- GL is blogs, videos, white papers and web-pages
- Not including GL can hurt both the academia and the industry
- There are MLR guidelines in other areas than SE

## 2. What is Background

### 2.1 What is An overview of the concept of grey literature

- *Luxembourg definition which states that, “<grey literature> is produced on all levels of government, academics, business and industry in print and electronic formats, but which is not controlled by commercial publishers, i.e., where publishing is not the primary activity of the producing body”*
- White, grey, and black literature
- Figure 1. show two dimensions of the literature: expertise and known
- *Expertise is the extent to which the authority and knowledge of the producer of the content can be determined*
- *Outlet control os the extent to which content is producer, moderated or edited in conformance with explicit and transparent knowledge creation criteria*
- In some study, the literature consisted from 75% to 85% of GL

### 2.2 What is Different types of secondary studies

- Secondary study is a study of studies
- "Survey paper" or "Review paper"
- regular surveys, systematic literature review (SLR), systematic literature mapping (SLM or SM)
- "secondary study are cited on average higher than regular primary studies"
- SLM, SLR, GLM, GLR, MLM, MLR
- all different types of studies have started to show up in SE
- **what is the difference between SLM and SLR?**

### 2.3 What is Benefits of and need for including grey literature in review studies (conducting MLRs)

- Key findings
  - *GL can give substantial benefits in certain areas of SE*
  - *the inclusion of GL brings forward certain challenges as evidence in them is foten experience and opinion based*
- A lot of information goes missing if GL is not included
- There is also risks and drawbacks in including GL

### 2.4 What is GL and MLRs in SE

- Rainer created some framework for understanding practitioners
- More and more multivocal studies have been done
- *"relationship of DevOps to agile, lean and continuous deployment seems to be a topic very active in the industry compared to academia."*
- The different types of reviews can be done in any order depending on the goal of the study

### 2.5 What is Lack of existing guidelines for conducting MLR studies in SE

- THE guide on SLR in SE (Kitchenham and Charters) only uses the word "grey" two times
- The need of missing guidelines for MLR in SE is addressed in this paper

## 3. What is an overview of the guidelines and its development 

### 3.1 What is Developing the guidelines

### 3.2 What is surveying MLR guidelines in other fields

- The guidelines were created upon other 24 MLR guideline papers

### 3.3 What is Running example

### 3.4 What is Overview of the guidelines

- *"To prevent duplication, we do not repeat all steps of the SLR guidelines when they are the same for conducting MLRs, but only present the steps that are different for conducting MLRs"*
- These guidelines focus on GL sources and how to handle them 

## 4. What is Planning an MLR

- This section presents guidelines on planning an MLR = Find the reason for an MLR, Create RQ, 
- Steps:
  1. Establishing the need for an MLR in a given topic
  2. Defining the MLRs goal and raising its research questions

### 4.1 A typical process for MLR studies

- The structure in figure 7 can be used to create the protocol (MLR research plan)
- **Guideline 1: The provided typical process of an MLR can be applied to structure a protocol on how the review will be conducted. Alternatively, the standard protocol structure of SLR in SE can be applied and the provided guidelines can be considered as variation points**

### 4.2 Raising (motivating the need for a MLR)

- **Guideline 2: Identify any existing reviews and plan/execute the MLR to explicitly provide usefulness for its intended audience (researchers and/or practitioners).**
- There is a lot of guidelines in existing literature that tells when one should use GL, and when not
  - One guideline suggests to leave GL out when the topic is mature and bounded, which however is not the case with DX
  - In SE this could mathematical aspects of formal methods that have little or no practitioners
- Based on the Table 4, there were many "yes" responses to the questions, and therefore there will be an MLR
- Contextual information = what works for whom, where, when, and why
- The higher amount of "yes" response, the higher the need for an MLR
- **Guideline 3: The decision whether to include the GL in a review study and to conduct an MLR study (instead of a conventional SLR) should be made systematically using a well-defined set of criteria/questions (e.g., using the criteria in Table 4).**

### 4.3 What is Setting the goal and raising the research questions

- RQ are the most important part of a SLR and affect:
  - the search process because the primary studies that address the RQ has to be found
  - data extraction as the data items need to answer the RQs
  - data analysis so that the result answers the RQs
- RQ should be objective and as measurable as possible
- **Guideline 4: Based on your research goal and target audience, define the research (or “review”) questions (RQs) in a way to (1) clearly relate to and systematically address the review goal, (2) match specific needs of the target audience, and (3) be as objective and measurable as possible.**
- **Guideline 5: Try adopting various RQ types (e.g., see those in Table 6) but be aware that primary studies may not allow all question types to be answered.**

- *RQ: What is the difference in definition of Developer Experience in academic and industry literature?*

## 5. What is Conducting the review

- This section is about conducting the review

### 5.1 What is Search process

- defined search strings
- snowballing?
  - where one follows citations either backward or forward from a set of seed papers
  - 

#### 5.1.1 What is Where to search

- White literature can be found from abstract databases Scopus, Web of science, google scholar or full-text databases with more limited coverage IEEE Explore, ACM digital library or ScienceDirect
- GL can be found from
  - general web search engine
    - google
  - specialized databases and websites
    - stackoverflow, programmer-experience.org, quora
  - contacting individuals directly or via social media
    - they might have unpublished papers or information that is not otherwise available
  - reference lists and backlinks
- They recommend to perform an informal pre-search to find different synonyms
- SWEBOK could be used to find the right keywords to search with
- MLR-AutoTest used white papers, blog posts and even YouTube videos
- **Guideline 6: Identify the relevant GL types and/or GL producers (data sources) for your review study early on.**
- **Guideline 7: General web search engines, specialized databases and websites, backlinks, and contacting individuals directly are ways to search for grey literature.**

#### 5.1.2 What is When to stop the search

- Data exhaustion stopping criteria
- If evidence is mostly qualitative, one can reach theoretical saturation
- **What is the difference between qualitative and quantitative material**
- GL on google can produce ridiculous amounts of results, 
- One has to rely on the search algorithm that the search engine uses
- The quality will start to drop the deeper on list one goes
- **Guideline 8: When searching for GL on SE topics, three possible stopping criteria for GL searches are: (1) Theoretical saturation, i.e., when no new concepts emerge from the search results; (2) Effort bounded, i.e., only include the top N search engine hits, and (3) Evidence exhaustion, i.e., extract all the evidence.**

### 5.2 What is Source selection

- At this point the potential primary sources have been selected and now they need to be assessed if they are suitable
- Normally this includes a selection criteria
- Selecting from GL is difficult and time consuming
- Look at table 7 to understand if the source has a relevant source type and quality

#### 5.2.1 What is Inclusion and exclusion criteria for source selection

- _"Source selection criteria are intended to identify those sources that provide direct evidence about the MLR's research question"_ 
  - If we would be looking at the definition of DX, 
- Source selection criteria can overlap with study quality assessment
- **Guideline 9:Combine inclusion and exclusion criteria for grey literature with quality assessment criteria (see Table 7).**

#### 5.2.2 What is Source selection process

- The source selection process for GL should be done with the formal literature in mind
- Both parts should take about the equal amount of time
- **Guideline 10: In the source selection process of an MLR, one should ensure a coordinated integration of the source selection processes for grey literature and formal literature.**

### 5.3 What is Quality Assessment of sources

- The quality of GL is difficult to assess because of the lack of formal publication processes
- Table 7 shows the quality assessment
- Some checks are only usable to a specific type of material like comments are available only on e.g. blog posts
- Methodology, the date of publication, or the number of backlinks
  - *What could the quality assessments be for this thesis?*
- The more is excluded in the selection criteria, the less there are to perform quality assessment on
- **Guideline 11: Apply and adapt the criteria authority of the producer, methodology, objectivity, date, novelty, impact, as well as outlet control (e.g., see Table 7), for study quality assessment of grey literature.**
  - **Consider which criteria can already be applied for source selection.**
  - **There is no one-size-fits-all quality model for all types of GL. Thus, one should make suitable adjustments to the quality criteria checklist and consider reductions or extensions if focusing on particular studies such as survey, case study or experiment**
- The scoring can be a yes or no, but also a yes, party, and no. This is however not relevant as the author is working alone
- Table 8 and 9 is an excellent example on how to score the sources

### 5.4 What is Data Extraction

#### 5.4.1 What is Design of data extraction forms

- MLR and SLR studies have a SM (Systematic Mapping) in step first?
  - Should this also be done in this thesis?!
- _What is going on in Table 10?_ 
  - Maybe look at reference [102]
  - Spreadsheets with direct traceability to MLR's research questions
  - Is this an explanation on how the data will be categorized
- In the data extraction form, create links so that it is easy to find where in the source GL the data was found

#### 5.4.2 What is Data extraction procedures and logistics

- GL has only a subset of the original important data in available, and the rest is in the "people's heads"
- There might be situations where the formal and GL literature describe the same study
  - then chose the formal and use GL as the supplement
- It might be difficult to find the source, when the verbatim text has been altered and put into the shared research database
- Peer reviewing the analyzes and the extracted data from the GL is crucial
- **Guideline 12: During the data extraction, systematic procedures and logistics, e.g., explicit “traceability” links between the extracted data and primary sources, should be utilized. Also, researchers should extract and record as much quantitative/qualitative data as needed to sufficiently address each RQ, to be used in the synthesis phase.**

### 5.5 What is Data Synthesis

- Descriptive (narrative) synthesis, quantitative synthesis, qualitative synthesis, thematic analysis, and meta-analysis
  - Look up what these all mean
- The data in this thesis will probably be only qualitative data
- The GL is often qualitative and experience based
- Surveys and questionnaires lack the standard deviation and therefore are not that reliable to be used as qualitative data in GL
- StackOverflow can be used to both qualitative and quantitative data. Counts of questions and views on specific topics can reveal quantitative data. Qualitative data can be extracted from the problems people have with e.g. a specific testing tools
- There might be a limitation in the initial factors => new factors are created in the coding phase
- Suitable level of abstraction should be used in the selection of factors
- Figure 9a shows the initial factors used, and Figure 9b shows the emerged factors after some work on them
- There are some critical questions to assess the expert's opinion
  - The 6 questions should however not be taken to rigorously
- Rigor on the GL should be based on the level of GL
- **Guideline 13: A suitable data synthesis method should be selected. Many GL sources are suitable for qualitative coding and synthesis. Some GL sources allow combination of survey results but lack of reporting rigor limits the meta-analysis. Quantitative analysis is possible on GL databases such as Stack- Overflow. Also argumentation theory can be beneficial for data synthesis from grey literature. Finally, the limitations of GL sources w.r.t. their evidence depth of experiment prevent meta-analysis.** 

## 6. What is Reporting the review

- Two important issues
  1. reporting style for different audience types
  2. ensuring usefulness to the target audience
- MLR should benefit both researchers and practitioners
- Studies can also be targeted for practitioners by publishing shorter versions of the studies
- Feedback from practitioners can be useful
- Include a section of the implications of the results, and also about the benefits of the results
- Papers in scientific journals include the whole process, including the planning and the search process
- IEEE Software papers are practitioner oriented and do not include the details of the process
- Table 12 shows where the papers and articles of the whole automated test studies where published
- Publishing the data repository is also important, as it can be useful for other researchers
- **Guideline 14: The writing style of an MLR paper should match its target audience, i.e., researchers and/or practitioners.**
  - **If targeting practitioners, a plain and to-the-point writing style with clear suggestion and without details about the research methodology should be chosen. Asking feedback from practitioners is highly recommended.**
  - **If the MLR paper targets researchers, it should be transparent by covering the underlying research methodology as well as an online repository and highlight the research findings while providing directions to future work.**

## 7. What is Conclusions and future works

- This section draw conclusions and suggest areas for further work
- Practitioners literature can improve the relevance of software engineering research
- Even if there has be been interviews done with practitioner subjects, the text produced by the very same practitioners has been ignored
-  The guidelines in this paper are living entities and should be assessed and improved

## Interpretations from the text

-

## Personal thoughts about the text

- This should be a very relevant article with specific guidelines on how I should conduct my MLR
- There is a lot of information, so I need to draw some kind of line on what I include in my work and how complex my work is going to be
  - It is still after all a master's thesis that is in the making
- Things that could be considered in the MLR:
  - blogs
  - question-answer sites (StackOverflow)
- Could contextual information be here that different context's define DX in their own way
  - E.g. I find a lot of DX about the library or tool authors, that use the term in their marketing material
- In this case there will probably only be one research question 
- It could be interesting to contact someone that is having the title "Working on the developer experience @ <company>"
- This MLR will be interesting, as there is very little good quality GL sources on the topic
- The master thesis (and also the doctoral thesis) on the topic are GL?
- Create a good reasoning on why this study is performed as a MLR
- The nature of SE is that there is a lot of blogs and online books about it. It might even be more than in other fields?