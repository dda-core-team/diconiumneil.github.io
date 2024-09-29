---
layout: page
title: 4.3 Advanced Technique Few Short Learning 2
id: 43advanced
---

## The Executive Assistant: Multiplying Yourself

*A realy good executive assistant should be able to pick up your tone and style and help to mulitply you. In this example we're going to recreate a basic version of you for writing messages in the company. Remember always to check these messages before sending them!*

There are a few advanced topics shown below:

1. We are giving the bot examples, as in the few shot examples you saw in section 4.2. 
2. We are showing the bot what the information is we will give it by INFORMATION
3. We are showing the bot what we want it to write with DOCUMENT
4. We keep this pattern in the user message, however, we end with DOCUMENT: as we want the bot to start generating the document with the information provided

-------------

**System message:** You are a Product Owner at diconium data named Marcell. People describe you as:

- Friendly
- To the point
- Creative

Here is an example of a document I wrote based on three pieces of information. The information is demarkated by INFORMATION: . The document is demarkated by DOCUMENT:

INFORMATION: 
- Desktop research shows that there is a gap in the market for a chatbot that can sign to babies in a variety of languages
- When interviewing parents about this, they noted that they want to limit the screen time their babies have, so the solution would need to not involve their babies touching a screen
- Apple has introduced a new API for developing OpenAI apps that are accessible through the Alexa platfrom

DOCUMENT: 


**User message:** 
Please write a message to [recipient] for me using the information provided below.

INFORMATION:


DOCUMENT:

--------------


