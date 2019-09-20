# The Impact of "Cosmetic" Changes on the Usability of Error Messages

## Abstract

- Poor usability in error messages makes solving programming errors difficult
- Cosmetic changes to presentation of error messages have significant impact on the usability

## 1 Introduction

- Novice programmers struggle noting and making sense of the error messages
- contribution
  1. they validated that specific techniques work
  2. linking design space of errors to HCI

## 2 Related work

### 2.1 The usability of error messages

- Unintuitive error messages is known to cause problems for both novice and professional developers
- There has been previous research on the style, content, and structure of the messages
- however not about presentation

### 2.2 Presentation theories and techniques

- semiology of graphics
- law of proximity in Gestalt Principles
- Progressive Disclosure

## 3 Redesigning an error message

- the selected snippet caused an error message that included the solution in it, but the user didn't catch it and asked on SO where an answer just copied out the 

### 3.1 The "spaces" variant

- extra whitespace, line breaks, and subheadings

### 3.2 The "color" variant

- use red, blue, grey, and bold to emphasize different parts of the message

### 3.3 The "ellipses" variant

- hiding the more detailed parts of the message

## 4 Experimental design

- 30 and 45 seconds to look at the error message and come up with a description of the problem

## 5 Results

### 5.1 Error comprehension

- the spaces variant was the most successful when users tried to explain the problem
- all variants outperformed the original

### 5.2 

- error resolution did also go up with all the variants

### 5.3 User preference

- in all cases the participants chose the variant over the original error message

## 6 Conclusions

- Small changes to presentation can result in substantial improvements
- previously known perception techniques can guide current error message design
- the framework (flutter) used in testing did not include the structured messages required?

## Personal thoughts about the text

- This should be interesting to me because error messages are one very important part about a good DX in a framework or tool
- they weren't supposed to change the content of the message, and still they added subheadings to it 🤔
- 