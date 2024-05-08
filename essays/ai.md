---
layout: essay
type: essay
title: "The Potential of AI"
# All dates must be YYYY-MM-DD format!
date: 2024-05-07
published: true
labels:
  - Education
  - Aritifial Intelligence
  - ChatGPT
---

<img width="350" alt="" class="rounded float-start pe-4" src="../img/AI/chatgpt.jpg">

### I. Introduction
The integration of Artificial Intelligence in education marks a shift in how students learn and apply technological skills. AI tools like ChatGPT and GitHub Co-Pilot have become instrumental tools in providing on-demand educational support for code development and enhancing the learning experiences through interactive and personalized assistance. In my coursework for ICS 314: Software Engineering, I have primarily used ChatGPT to assist with various problems such as coding and writing essays. These tools have introduced new dynamics in understanding complex software engineering principles and have changed the direction of the traditional learning process.

### II. Personal Experience with AI:
I have used AI in class this semester in the following areas:

1. Experience WODs e.g. E18  
   I have not used AI for Experience WODs since I did not find it necessary to use. I thought that the tutorial videos and the instructions in the Experience WODs were clear enough for me to understand to finish it.

2. In-class Practice WODs  
   I have used AI for some In-Class Practice WODs but mainly for debugging purposes. I thought that it was important to find the answers on my own until I get stuck on a problem. Initially, I would seek assistance from my classmates in class, but if they were unable to help, I would then turn to ChatGPT for help with debugging my code.

3. In-class WODs  
   I have used AI on some of them for debugging purposes. The reason for this is that I felt that I wanted to code the majority of the WOD and understand the concept we were learning in class without the help of AI. It was my way of seeing if I understood the concepts the WODs were teaching. When I use ChatGPT for In-Class WODs, most of the WOD is coded and debugging fixes are mostly logic fixes and missing parts.

4. Essays  
   I have used AI for writing essays but only one essay is mostly written by ChatGPT and most of them are written by me. I found that using ChatGPT for writing essays does not help show my actual voice. The way that ChatGPT writes is way too formal and written like someone with no emotions. The way I incorporate ChatGPT in my essays is simply for grammar fixes. One instance that I have used ChatGPT for writing an essay is writing “Reflect on Design Patterns”. For example, ChatGPT was used to write the information about Design Patterns. Which simply wrote a robotic-sounding paragraph about Design Patterns.

5. Final project  
   I have used AI for the final project. For example, I have used it to adjust the logic for the filter feature on the project. The filter was based on the BowFolios filter which worked by having the user select interest in the filter and then showing the component cards after the filter was submitted. I have used ChatGPT to help me adjust this logic by having it first show all the card components and filtering it after interest is selected and submitted.

6. Learning a concept / tutorial  
   I have never used AI when learning a concept since the modules and information on the internet were enough. I do think that ChatGPT is great for learning concepts since it is easy to answer a question and have a curated answer for a specific question.

   Before AI
  ```javascript
   const submit = (data) => {
     setSelectedInterests(data.interests || []);
   };
   ```
   After AI
   ```javascript
   const submit = (data) => {
     setInterests(data.interests || []);
     const filteredEmails = data.interests?.length > 0
     ? _.uniq(_.pluck(profileInterests.filter(pI => data.interests.includes(pI.interest)), 'profile'))
      : _.uniq(_.pluck(allProfiles, 'email'));
      setProfileData(filteredEmails.map(email => getProfileData(email)));
   };
   ```
  
7. Answering a question in class or in Discord  
   I have never used AI for writing answers for class and Discord. I rarely used the class Discord to ask for smart questions and have never needed AI to help write them.

8. Asking or answering a smart-question  
   I have never used AI for answering or asking smart-question questions. As I have mentioned previously, I rarely ask for help in Discord, so I have no need to use AI for writing smart-questions.

9. Coding example e.g. “give an example of using Underscore .pluck”  
   For coding examples I did not see the need to use AI since most coding examples were easily accessible on the internet. For example in the Javascript module of the class, I simply used W3Schools and other sites to find examples of code.

10. Explaining code  
    I found AI to be helpful when explaining code but I have only asked AI to explain the code it generated and not the code that I have provided. When using ChatGPT to help write programs, I would often ask and explain what the code is doing. I do this since it helps me understand what it generated but also helps with altering the generated code when I need to.

11. Writing code  
    I have used ChatGPT for writing code. As I have explained above, I used AI for my final project which helped me write the code for altering the logic of the program.

12. Documenting code  
    I have never used AI for documenting codes since I rarely document my codes. The most I would document my code is by writing simple comments which happens infrequently. Therefore, I have not needed to use AI for documenting code since I rarely write them to begin with.
13. Quality assurance  
    As mentioned above, I have used AI for debugging codes for In-Class WODs. I found it useful since it can quickly find what’s wrong. Instead of looking at the code for several minutes and finding the bug, ChatGPT can quickly pick up on it and fix it for me.

14. Other uses in ICS 314 not listed above  
    I did not use AI in ICS 314 that were not listed above.

### III. Impact on Learning and Understanding:
The use of AI in my coursework significantly influenced my learning experience by enhancing comprehension and skill development. AI's instant feedback and vast knowledge base allowed me to explore deeper into software engineering concepts such as React programming and MongoDB integration. It gives a hands-on approach to problem-solving, where AI-generated solutions and examples provide a strong starting point or analysis for my own solutions. This interaction notably boosted my problem-solving skills and allowed me to take on software engineering challenges more confidently and efficiently.

### IV. Practical Applications:
Beyond ICS 314, AI's influence extends into user experience design in software engineering. AI technologies are increasingly used to automate the process of user testing and feedback collection, enabling designers to refine interfaces based on real-time user interactions and preferences. For instance, AI-powered analytics tools can track user behavior patterns, providing designers with precise insights into which features are most engaging or where users encounter difficulties. Additionally, AI can simulate user interactions to test various design scenarios, predicting user responses before the product is even launched. This integration of AI in UX design not only speeds up the design process but also ensures that the final products are more aligned with user expectations, enhancing overall user satisfaction with software solutions.

### V. Challenges and Opportunities:
While AI presents remarkable benefits, it also poses challenges and limitations. One major challenge is the reliance on AI for solutions, which might hinder learning and the development of independent problem-solving skills. There’s also the issue of AI-generated code quality, which may not always be correct or be optimized for all scenarios. However, these challenges also open opportunities for further integration of AI in educational settings, such as developing more interactive AI or creating AI that caters to the user’s learning style.

### VI. Comparative Analysis:
Comparing traditional teaching methods with the use of AI reveals significant differences. Traditional methods emphasize structured learning and foundational theory, which are crucial for deep understanding but may lack the immediacy and customization that AI tools offer. AI learning promotes engagement, immediate application, and high interaction, which can lead to improved knowledge retention and practical skill development, particularly in a fast-moving field like software engineering.

### VII. Future Considerations:
The future of AI in software engineering education looks promising yet challenging. As AI technology advances, its integration into education can become more refined and offer more personalized and adaptive learning experiences. The challenge will be to balance AI with traditional learning methods to ensure that students receive immediate assistance while developing critical thinking and problem-solving skills.

### VIII. Conclusion:
The use of AI in ICS 314 has profoundly impacted my learning experience, providing both enhancements and new challenges. While AI tools have greatly assisted in understanding complex concepts and performing tasks, it is crucial to maintain a balance to ensure comprehensive learning. Going forward, optimizing the integration of AI in the computer science field will require continuous adaptation and evaluation to maximize its benefits while mitigating its limitations.
