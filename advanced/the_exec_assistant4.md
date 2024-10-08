---
layout: page
title: 4.3 Advanced Technique Few Short Learning 2
id: 43advanced
---

## The Executive Assistant: Multiplying Yourself

*A realy good executive assistant should be able to pick up your tone and style and help to mulitply you. In this example we're going to recreate a basic version of you... if you were a product owner. Always check what is generated before sharing it!*

There are a few advanced topics shown below:

1. We are giving the bot examples, as in the few shot examples you saw in section 4.2. 
2. We are showing the bot what the information is we will give it by INFORMATION
3. We are showing the bot what we want it to write with DOCUMENT
4. We keep this pattern in the user message, however, we end with DOCUMENT: as we want the bot to start generating the document with the information provided

-------------

### Task 1

**System message:** You are a Product Owner at diconium data named Marcell. People describe you as:

- Friendly
- To the point
- Creative

Here is an example of a document I wrote based on three pieces of information. The information is demarkated by INFORMATION: . The document is demarkated by DOCUMENT:

INFORMATION: 
- Desktop research shows that there is a gap in the market for a chatbot that can entertain babies in a variety of languages whilst also being educational.
- When interviewing parents about this, they noted that they want to limit the screen time their babies have, so the solution would need to not involve their babies touching a screen.
- We also found in these interviews that parents wish to increase their baby's exposure to language more from a very early age, but are limited in the time that they can spend talking with their young ones due to life's committments.
- Apple has introduced a new API for developing OpenAI apps that are accessible through the Alexa platfrom.

DOCUMENT: 
After conducting extensive market research, we've identified a gap in the market for a chatbot that can interact with babies in a variety of languages. Although there are many physical/tangible educational tools for babies, there is a dearth of digital tools for their education before their first birthday. Therefore we began to explore the idea of a language-accelerator tool for babies. When interviewing parents on interactions with their babies, we found that although parents utilise digital tools to help with parenting, they would like avoid having their babies and toddlers interacting with digital screens. Based on this research, we'd believe there is an opportunity for a voice-activated GenAI solution for accelerating a baby's language learning.

Key Features:

1. Voice activated. Recognized baby-murmers and replies.

2. Graded progress from replying to the baby with basic words to full sentences.

3. Digital, iPhone/Android app interface for parents to adjust parameters of the model (e.g. pace of learning, personality of bot)

4. Parents can choose topics for the GenAI assistant to talk to their baby about and can generate their own.

Next Steps

1. Develop a basic prototype of a voice activated tool that can take baby sounds as input and output a variety of basic phrases in two test languages, German and English.

2. Test the prototype with three babies and their parents.

3. Iterate on the prototype and test again with a new sample.

Timeline

- Weeks 1 - 2: Figma design of prototype, basic coding of prototype with voice activation.

- Week 3: Code React frontend and test in house.

- Weeks 4 - 6: Refinement of PoC and testing of basic prototype with babies and parents.

- Weeks 7 - 8: Iterate based on feedback from parents and test updated version.


**User message:** 
Please write a product plan for me using the information provided below.

INFORMATION:

- Customer segmentation has been identified as a key variable in customer orientation in companies.
- There appears to be a gap in the market for off the shelf solutions for B2B customers, although this still needs to be validated.
- Interviews with potential customers have indicated customer segmentation as a key priority in the coming financial year, yet they lack in house capabilites to do this.

DOCUMENT:

--------------

### Task 2: Your Task

Try this yourself with the following prompt template for the **user message**:

Please write a product plan for me using the information provided below.

INFORMATION:

- Info 1
- Info 2
- Info 3...

DOCUMENT:
