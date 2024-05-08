---
layout: essay
type: essay
title: "AI: My Tutor"
# All dates must be YYYY-MM-DD format!
date: 2024-05-07
published: true
labels:
  - AI
  - Reflection
  - ChatGPT
  - Education
---

### I. Introduction

Artificial Intelligence or AI has dominated the minds of tech professionals in the recent year. Originally depicted in literature and films as fictional, it has been brought to life by the efforts of companies such as OpenAI. In the fields of education and software engineering, AI has established itself as a valuable tool for numerous students, owing to its accessibility. I am part of the many students who have developed AI into their toolbox for education. Of the many AI chatbots that have come out this year, I have used ChatGPT to help with schoolwork and increase my efficiency in software development.

### II. Personal Experience with AI:
I have used AI in class this semester in the following areas:

1. Experience WODs e.g. E18
  I have not used AI for Experience WODs since I did not find it necessary to use. I thought that the tutorial videos and the instructions in the Experience WODs  were clear enough for me to understand to finish it.
  
2. In-class Practice WODs
  I have used AI for some In-Class Practice WODs but mainly for debugging purposes. I thought that it was important to find the answers on my own until I get stuck on a problem. Initially, I would seek assistance from my   classmates in class, but if they were unable to help, I would then turn to ChatGPT for help with debugging my code.

3. In-class WODs
  Similar to the In-Class Practice WODs, I have used AI on some of them for debugging purposes. The reason for this is that I felt that I wanted to code the majority of the WOD and understand the concept we were learning   in class without the help of AI. It was my way of seeing if I understood the concepts the WODs were teaching. When I use ChatGPT for In-Class WODs, most of the WOD is coded and debugging fixes are mostly logic fixes      and missing parts.

4. Essays
  I have used AI for writing essays but only one essay is mostly written by ChatGPT and most of them are written by me. I found that using ChatGPT for writing essays does not help show my actual voice. The way that         ChatGPT writes is way too formal and written like someone with no emotions. The way I incorporate ChatGPT in my essays is simply for grammar fixes. One instance that I have used ChatGPT for writing an essay is writing    “Reflect on Design Patterns”. For example, ChatGPT was used to write the information about Design Patterns. Which simply wrote a robotic-sounding paragraph about Design Patterns.

5. Final project  
  I have used AI for the final project. For example, I have used it to adjust the logic for the filter feature on the project. The filter was based on the BowFolios filter which worked by having the user select interest    in the filter and then showing the component cards after the filter was submitted. I have used ChatGPT to help me adjust this logic by having it first show all the card components and filtering it after interest is       selected and submitted.
  
Before AI
```js
const submit = (data) => {
  setSelectedInterests(data.interests || []);
};
```

After AI
```js
const submit = (data) => {
  setInterests(data.interests || []);
  const filteredEmails = data.interests?.length > 0
  ? _.uniq(_.pluck(profileInterests.filter(pI => data.interests.includes(pI.interest)), 'profile'))
  : _.uniq(_.pluck(allProfiles, 'email'));
  setProfileData(filteredEmails.map(email => getProfileData(email)));
};
```
  
6. Learning a concept / Tutorial
  I have never used AI when learning a concept since the modules and information on the internet were enough. I do think that ChatGPT is great for learning concepts since it is easy to answer a question and have a      curated answer for a specific question.

7. Answering a question in class or in Discord 
  I have never used AI for writing answers for class and Discord. I rarely used the class Discord to ask for smart questions and have never needed AI to help write them.


8. Asking or answering a smart-question 
I have never used AI for answering or asking smart-question questions. As I have mentioned previously, I rarely ask for help in Discord, so I have no need to use AI for writing smart-questions. 


9. Coding example e.g. “give an example of using Underscore .pluck”  
  For coding examples I did not see the need to use AI since most coding examples were easily accessible on the internet. For example in the Javascript module of the class, I simply used W3Schools and other sites to find   examples of code.


10. Explaining Code
  I found AI to be helpful when explaining code but I have only asked AI to explain the code it generated and not the code that I have provided. When using ChatGPT to help write programs, I would often ask and explain  what the code is doing. I do this since it helps me understand what it generated but also helps with altering the generated code when I need to.

11. Writing code  
  I have used ChatGPT for writing code. As I have explained above, I used AI for my final project which helped me write the code for altering the logic of the program.

12. Documenting code
  I have never used AI for documenting codes since I rarely document my codes. The most I would document my code is by writing simple comments which happens infrequently. Therefore, I have not needed to use AI for          documenting code since I rarely write them to begin with.

13. Quality assurance  
  As mentioned above, I have used AI for debugging codes for In-Class WODs. I found it useful since it can quickly find what’s wrong. Instead of looking at the code for several minutes and finding the bug, ChatGPT can      quickly pick up on it and fix it for me.

14. Other uses in ICS 314 not listed above
  I did not use AI in ICS 314 that were not listed above.

### III. Impact on Learning and Understanding:

I have integrated AI into my education and I found it helpful for learning new concepts quickly. When learning new concepts on my own, I tend to have a lot of questions and AI has helped. Since most AI tools are chatbots I can easily ask questions regarding topics in a quick manner. This has enhanced my learning as it can be easy to ask a question without having to wait for professors or my peers to write a reply.

### IV. Practical Applications:

For practical applications of AI, I think it has a lot of great potential. For example, it can be used to help with organizing schedules, help write recipes, and as complicated as an online tutor for software engineering. One great thing about AI and chatbots is their vast knowledge of different concepts. In my opinion, AI chatbots can be seen as a search engine like Google that skips the search parts and goes straight to the answer. Like I said this improves efficiency whether you are making schedules or coding a program.

### V. Challenges and Opportunities:

One challenge that I have encountered when using AI in class is when it is generating code. I found that AI can be helpful to point in the correct direction and provide code but sometimes it will generate code that has problems and will not be helpful. You can try to help the AI fix it but sometimes I find that it will constantly produce buggy codes. One potential opportunity for further integration of AI in software engineering education is becoming a tutor. In one instance, I have used AI to help me learn concepts in the Algorithms class. I asked ChatGPT to generate Dynamic Programming problems that I could solve, which made ChatGPT my teacher.

### VI. Comparative Analysis:

In the realm of software engineering education, traditional teaching methods, characterized by lectures and face-to-face discussions, can be highly engaging and foster robust knowledge retention through structured interactions and peer learning. However, what I found it lacking is personalized learning. AI-enhanced approaches offer personalized learning experiences through adaptive platforms and real-time feedback. In short, AI can give a customizable and adaptable experience for every student.

### VII. Future Considerations:

AI will improve in the future. It is impressive what AI can accomplish having it only come out recently. Further work and research will improve AI and can be a helpful tool for students and professors in terms of software engineering. AI can be used to develop software engineering lessons and create a hybrid educational model where AI and traditional teaching methods are used together. One challenge that AI poses now and in the future is the concern with ethics. AI needs to be developed in a way where it is ethical and benefits everyone.

### VIII. Conclusion:

In summary, AI has significantly enriched my software engineering education by offering personalized learning experiences and real-time problem-solving assistance. Traditional teaching methods, while effective for systematic learning and peer engagement, are enhanced by AI's ability to tailor learning to individual needs. As we look ahead, I recommend that educational institutions focus on a hybrid model that combines AI with traditional methods to maximize the strengths of both. To optimize AI integration in future courses, educators should consider developing AI tools that can function as interactive learning companions, ensuring these tools are adaptable and ethically designed to complement standard curricula and support diverse learning styles effectively. This approach will not only improve educational outcomes but also prepare students for a technologically advanced workforce.

