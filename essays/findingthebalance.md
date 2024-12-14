---
layout: essay
type: essay
title: "Finding the Balance: AI in Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2024-12-13
published: true
labels:
  - Software Engineering
  - AI
  - Learning with AI
---

<p align="center"> <img src="../img/aiprogramming.jpg" width=550px> </p>

# I. Introduction: 

Artificial Intelligence (AI) has become an increasingly important tool in education, providing new ways to enhance learning and problem-solving. In software engineering, AI tools like ChatGPT, Claude, and GitHub Copilot are especially valuable for writing, debugging, and understanding code. During ICS 314, I relied on ChatGPT and Claude to assist with coding challenges, debug errors, and deepen my understanding of key concepts. This essay reflects on how these tools shaped my experience and learning in the course.

# II. Personal Experience with AI:

## 1. Experience WODs:

For coding assignments, I didn’t rely much on AI to complete them. Most of the time, the demonstration video provided at the end of the instructions was enough. I watched it and followed along when I was stuck. In the demonstration, the professor went over the solution step by step, which helped complete the assignment. Because the video covered the necessary details, I usually didn’t need to use AI for these tasks.

## 2. In-class Practice WODs:

I tried to complete the practice WODs on my own first. When I got stuck, I used ChatGPT for assistance. Although the practice WODs were timed to simulate the actual WOD environment, I didn’t feel pressured to rush. I gave myself time to figure things out before turning to ChatGPT for help. My prompts often included the instructions and the code I had already written, such as: “Here are the WOD instructions: [instructions] and here’s what I have so far: [code snippet]. How can I modify it so that it meets the requirements?” This approach allowed me to receive tailored advice that helped me move forward. ChatGPT’s responses were generally useful, though they occasionally required further refinement to fully address the specific task.

## 3. In-class WODs:

I used AI during the in-class WODs to ensure I completed them within the time limit, as the score was either 0/100 or 100/100. I started by reviewing the mock-up WODs we had practiced earlier and reusing similar parts. Reusing familiar code not only saved time but also reinforced my understanding of the concepts, which was especially helpful for debugging and restyling. If there were parts I couldn’t figure out, I turned to ChatGPT for guidance, asking specific questions about the task, such as: “Here are the WOD instructions: [instructions], and here’s what I have so far: [code snippet]. How can I modify it so that it meets the requirements?” While ChatGPT provided useful starting points, the output didn’t always match the exact design or functionality I needed, so I polished and refined the code on my own to meet the requirements.

## 4. Essays: 

I did not use AI for essays. When the prompts focused on technical concepts about coding, I did some quick research on the internet to gather information and brainstorm ideas for my writing. In the past, I had tried using AI for essays in other classes, but I found that the results often didn’t sound natural or align with what I wanted. Additionally, revising the AI-generated output into something usable took a significant amount of time. The essays in this class required me to think creatively and write for a broader audience rather than just the professor. I believed that using AI would make my papers lack creativity and a personal touch. To make my essays more engaging, I often included metaphors and personal experiences—elements that AI couldn’t replicate effectively. For these reasons, I chose to focus on developing my thoughts independently and did not rely on AI for essays in this class.

## 5. Final Project: 

<img width="250px" class="rounded float-start pe-4" src="../img/landing.png">

AI played a crucial role during the final project. To deploy our team’s website on Vercel, I needed to resolve lint and build errors. While lint errors were straightforward to fix, build errors required more effort, especially since I wasn’t the author of much of the code. I used ChatGPT with the prompt: "I am encountering this error while running 'npm run build.' Here is the relevant code causing the issue. Can you explain why this error is occurring and suggest modifications to fix it?" ChatGPT helped me understand the error messages, identify the causes, and receive suggestions for fixes.

We also encountered issues where functionalities worked locally but failed after deployment, even though the database was updated correctly. For example, our “Approve” and “Delete” buttons on the admin page worked locally but didn’t immediately update the “Buy Page” on Vercel without redeploying the site. ChatGPT explained that this was due to server-side rendering and caching issues, which helped me debug and refine the code. Although it didn’t provide a direct solution, the insights were crucial for resolving these challenges and ensuring the website worked as intended.

## 6. Learning a Concept/Tutorial:

When learning new concepts, I often asked ChatGPT to explain them in simple terms. For example, I would ask, “Please explain what [concept] is in simple terms.” By specifically requesting straightforward explanations, I found it easier to grasp the material because the responses were concise and clear. I usually began with broader questions and then gradually narrowed them down to focus on more specific aspects of the concept. For instance, I asked ChatGPT for an easy-to-understand example to reinforce my understanding. If the example made sense, I would follow up by requesting a slightly more complex one. When something wasn’t clear enough, I adjusted my questions to target the specific points of confusion. This step-by-step approach helped me break down complex topics into manageable parts, significantly improving my understanding of the concepts.

## 7. Answering a Question in Class or Discord:

I didn’t ask questions on Discord, so I didn’t use AI in this context. When I encountered issues, I often found that someone else had already asked about the same problem, and helpful responses were available. This allowed me to debug my code by reading through the discussions without needing to post my own question.

## 8. Asking or Answering a Smart-Question:

I didn't ask questions directly on Discord or other platforms because I found that many of my issues had already been addressed in previous discussions. By thoroughly reviewing these responses, I was able to debug my code effectively without needing to post my own questions.

## 9. Coding Example:

When I needed an example of integrating React and Bootstrap, I asked AI to provide code snippets for specific functionality, such as creating a button that routes to another page. For instance, I asked, “Can you show me how to create a functional component in React with a Bootstrap button that navigates to another route?” The example demonstrated how to use React Router’s useNavigate hook and a Bootstrap-styled button to handle routing. I was able to adapt this to my project by adjusting the route and styling as needed. This process not only saved me time but also helped me better understand how to effectively combine React and Bootstrap in my components.

## 10. Explaining Code:

In my team's second-hand marketplace project, the "Approve" and "Delete" buttons on the admin page worked locally but didn’t update the "Buy Page" on Vercel without redeployment. Since this was my team's code, I first needed to understand how it worked before making any modifications. I asked ChatGPT, “Why doesn’t the Buy Page reflect changes made by these buttons without redeployment, and how can I fix it?” ChatGPT explained that the issue was related to server-side rendering (SSR) and caching. With this guidance, I was able to adjust the code to make it functional, improving both the feature and my understanding of SSR.

## 11. Writing Code:

For generating code, I used AI to focus on specific snippets or approaches rather than full solutions. For example, when I wanted to change a dropdown menu in the navbar to a sliding bar using Bootstrap in React, I asked ChatGPT, “How can I implement a sliding bar for the navbar using Bootstrap in React?” Since all the links were already in place, I didn’t want to disrupt the existing structure, so I requested examples that I could modify on my own. The suggestions provided a solid starting point, enabling me to implement the sliding bar while maintaining control over the final design and ensuring the links remained functional. This approach saved time and helped me avoid unnecessary changes to the existing code.

## 12. Documenting Code:

Although I used AI to understand the code, I did not rely on it to document my code. When reviewing the code, I already had a good understanding of what it was doing, so I didn't see the need to ask AI to document it for me.

## 13. Quality Assurance:

I used AI for quality assurance, particularly during the build process when resolving errors. For instance, if a build failed, I would ask, “Why is this error occurring during the build, and how can I fix it?” while providing the relevant error message and code snippet. AI helped me understand the root cause of issues, such as dependency conflicts or misconfigurations and suggested potential fixes. These insights were especially helpful when dealing with complex build errors, allowing me to resolve them efficiently while ensuring the project remained functional and met all requirements.

## 14. Other Uses in ICS 314 Not Listed:

For assignments where I had to set something up on my own, I first checked the #smart-questions channel on Discord. Usually, someone else had experienced the same issues. If I couldn’t find anything helpful there, I turned to Claude for assistance. I would ask for a step-by-step process to resolve my issue. When running certain commands, I occasionally encountered errors. In those cases, I described what I was trying to set up and included the error messages in my query to Claude. For example, “I am trying to connect pgAdmin to my PostgreSQL database, and I keep getting this error: <error>. How can I resolve this?” By doing so, Claude was able to identify what wasn’t working and provide clear instructions to fix the issues.

# III. Impact on Learning and Understanding:

The use of AI tools like ChatGPT and Claude significantly influenced my learning experience in ICS 314. These tools enhanced my comprehension of complex concepts by providing simple explanations and tailored examples. For instance, using AI to break down topics like server-side rendering or caching improved my understanding and enabled me to apply these concepts in my projects. Additionally, AI-assisted with debugging and offered hints or suggestions while still allowing me to maintain control over the final implementation.

Since this class followed a flipped classroom model, where we were expected to learn independently with minimal direct instruction, AI became a crucial resource. While screencasts were available, they often used a different tech stack, making them less applicable. As a result, AI became a tool I both had to and could rely on to complete assigned tasks effectively.

# IV. Practical Applications:

Outside ICS 314, I explored the practical applications of AI in collaborative projects. AI helped my team create an efficient, well-developed website that earned us second place in HACC. The project my team created was complex and required significant work, including debugging, implementing new features, and optimizing performance. AI was especially helpful in streamlining the development process by suggesting solutions.

Beyond this specific project, AI has become an essential tool in modern software development. It streamlines workflows by automating repetitive tasks, such as debugging, testing, and code formatting, saving time and reducing human error. AI is also valuable for improving code quality, offering suggestions for optimization, and generating clear explanations for complex technical concepts. Additionally, it supports creative problem-solving by providing alternative approaches and fresh perspectives, making it a powerful resource for tackling challenges in both individual and team-based coding projects.

# V. Challenges and Opportunities:

Throughout this class, I was challenged to find a balance in using AI. Relying entirely on AI could negatively impact my learning while avoiding it altogether would limit efficiency and problem-solving. I believe using AI as a supportive tool while ensuring I still complete tasks independently is the most effective approach. However, one challenge was the occasional inaccuracy or lack of context in AI responses, which sometimes required additional research and troubleshooting.

Despite these challenges, AI presents significant opportunities to reimagine how software engineering is taught and learned. For instance, integrating AI into courses could help students tackle real-world scenarios by offering dynamic simulations or interactive coding exercises. AI can also act as a mentor, guiding students step-by-step through challenging problems and suggesting alternative approaches to solutions. By encouraging students to think critically while using AI as a learning partner, software engineering education could become more engaging and adaptable to individual needs.

# VI. Comparative Analysis:

Traditional teaching methods, such as lectures and written instructions, provide a structured and comprehensive foundation for software engineering concepts. These methods encourage knowledge retention by systematically presenting material and reinforcing theoretical understanding through repetition and practice. However, traditional approaches sometimes lack the flexibility to adapt to individual learning styles or provide immediate feedback, which may leave some students struggling with specific challenges. While these methods establish a strong theoretical base, they are not always as effective for real-time problem-solving or hands-on application.

In contrast, AI-enhanced approaches offer immediate, contextualized assistance, making them more engaging and effective for practical skill development. They provide personalized responses tailored to individual needs, addressing specific areas where students may struggle. Since every student learns at a different pace and brings varying levels of prior knowledge, AI fosters engagement and deeper understanding by adapting to these differences. Additionally, AI can simulate real-world scenarios, allowing students to apply concepts in a practical context, which enhances knowledge retention and builds critical skills. By complementing traditional methods, AI tools bridge the gap between theoretical learning and practical experience, creating a more flexible and effective learning environment.

# VII. Future Considerations:

Looking ahead, AI is likely to play a central role in shaping software engineering education. With advancements in AI technology, tools could seamlessly integrate into learning platforms to provide dynamic feedback on assignments, personalized study paths, and real-time suggestions for improving projects. These features would not only make learning more engaging but also enable students to better understand complex concepts and enhance their skills. AI could also assist with group projects by offering guidance on teamwork and effectively managing task distribution.

However, the increasing reliance on AI also raises challenges that must be addressed. Ensuring the accuracy of AI-generated responses is essential, as errors could mislead students. Over-reliance on AI might also reduce opportunities for developing problem-solving and critical thinking skills, which are crucial in software engineering. To mitigate these issues, incorporating AI literacy into the curriculum would help students use these tools responsibly and effectively. Additionally, concerns such as data security and unintended biases in AI systems must be considered as these technologies become more prevalent in education. By thoughtfully integrating AI, educators can maximize its benefits while addressing its limitations.

# VIII. Conclusion:

Reflecting on the use of AI in the Software Engineering course, I found it to be an incredibly helpful tool for understanding concepts, debugging errors, and solving problems efficiently. However, overusing AI can hinder long-term learning. While it may help resolve immediate issues, relying too heavily on AI often means missing the opportunity to fully internalize solutions, making it harder to recall or apply the same concepts independently in the future. This is particularly relevant in a flipped course model, where students are expected to take charge of their learning. AI can serve as a valuable support system in this context, but striking the right balance between assistance and independent problem-solving is crucial.

If more up-to-date resources were available for students to learn from, it would likely reduce over-reliance on AI for classwork. While AI will inevitably become a prevalent tool in software engineering, users should avoid relying on it entirely and focus on developing their critical thinking and problem-solving skills.

<br/>
