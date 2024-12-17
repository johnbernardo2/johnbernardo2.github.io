---
layout: essay
type: essay
title: "AI and Me: A Software Engineering Perspective"
# All dates must be YYYY-MM-DD format!
date: 2024-12-16
published: true
labels:
  - Artificial Intelligence
  - ChatGPT
  - Github Copilot
---

<div style="display: flex; gap: 10px;">
    <img src="../img/girlCyborg.jpg" alt="Cyborg Girl" style="width: 200px;">
    <img src="../img/terminator.jpg" alt="Terminator" style="width: 265px;">
</div>


## I. Introduction: 

Artificial Intelligence (AI) is undeniably reshaping the way we learn, work, and interact with technology. In education, AI has emerged as a powerful tool to enhance efficiency and accelerate understanding. While its benefits are clear, its usage also raises important debates about dependency and the need for foundational knowledge. Just as a calculator aids in solving complex equations but doesn’t inherently teach calculus, AI is most effective when used as a tool rather than a crutch.

The relevance of AI to software engineering parallels this drive for efficiency and enhanced learning. Debugging, often regarded as one of the most frustrating parts of programming, is a prime example. While modern tools like linters catch many syntax issues, more subtle bugs—like a misconfigured API call or an off-by-one error in a loop—can still lead to hours of frustration. AI tools like ChatGPT and Github Copilot can assist by pinpointing problematic areas, suggesting fixes, and even explaining the root cause—all without needing to consult a colleague or supervisor..

Personally, I’ve found AI invaluable for breaking down complex concepts. Whether asking, "Why does this work this way?" or "How do these elements relate?", AI provides analogies and clear explanations that help me grasp difficult topics faster. It’s like having a knowledgeable tutor available 24/7. There’s a saying: “If you can’t explain it to a 5-year-old, you don’t understand it yourself.” For me, AI bridges that gap between confusion and clarity, making it easier to learn and apply new knowledge effectively.


## II. Personal Experience with AI:


#### 1. Experience WODs:



#### 2. In-class Practice WODs:


#### 3. In-class WODs:



#### 4. Essays: 



#### 5. Final Project: 

For my final project, implementing dynamic map markers using the Google Maps API was both a challenge and an opportunity to explore AI’s capabilities. I used ChatGPT to guide me through linking geographic coordinates (latitude and longitude) to markers on a map. It provided a helpful starting point by explaining how to import the Google Maps library, manage environment keys, and structure the code for creating new markers.

Once the initial functionality was in place—where adding a restaurant entry automatically generated a marker on the map—I ran into a bug while trying to edit the marker’s location. The problem was that updates would only work if the new coordinates were within one integer of the original. I asked ChatGPT multiple times, but it failed to identify the root cause and instead suggested unnecessarily complex solutions. Eventually, a quick Google search revealed that the issue could be resolved with just two lines of code.

This experience highlighted both the strengths and weaknesses of AI tools. While ChatGPT gave me a significant leap forward in implementation, it occasionally struggled with debugging edge cases. The process taught me the importance of combining AI suggestions with manual research and critical thinking to find the most effective solution.



#### 6. Learning a Concept/Tutorial:

When learning new concepts, I found ChatGPT particularly helpful for breaking complex topics into manageable explanations. For example, when I first worked with HTML/CSS/Bootstrap, I struggled to position objects correctly on a webpage. I asked ChatGPT: “How do I center a div horizontally and vertically in Bootstrap 5?” It provided step-by-step instructions and examples, which helped me understand the syntax and concepts clearly.

However, I ran into challenges when making internal adjustments. Sometimes ChatGPT’s suggestions didn’t work, forcing me to manually experiment with the CSS file, add overrides like !important, or revise my TSX code. While this trial-and-error process was frustrating, it ultimately improved my understanding of how the HTML, CSS, and TypeScript components interacted.


#### 7. Answering a Question in Class or Discord:
I don’t think there's a question in class or in Discord that would require me to use GPT, unless another student had a coding specific problem. Even then, someone else more knowledgeable would answer it.

#### 8. Asking or Answering a Smart-Question:

I havent used ai to ask or answer a smart question because this course is mostly introductory material. Smart-questions are also based on research first anyways, so if there was something specific not listed in an assignment, I would just ask the professor or in the discord.

#### 9. Coding Example:



#### 10. Explaining Code:

During my final project, I needed to implement dynamic map markers that linked restaurants to their geographic coordinates using latitude and longitude. ChatGPT helped me make a significant leap forward by guiding me through the process of adding these markers during the creation of a restaurant entry. The AI explained how to integrate the coordinates into the map rendering logic effectively, which saved me time and effort.
However, when I encountered a bug while trying to edit an existing marker’s coordinates, ChatGPT struggled to identify the root cause even when I specifically mentioned the “edit form.” It suggested overly complex solutions that didn’t address the actual problem. After a quick Google search, I discovered that the issue could be fixed with just two simple lines of code. This experience reminded me that while ChatGPT can provide a strong starting point, it’s still important to verify solutions and think critically about the problem at hand.


#### 11. Writing Code:

I frequently used GitHub Copilot to assist with writing code efficiently. One particularly helpful use case was fixing ESLint errors. Copilot would highlight problematic lines of code and provide instant suggestions with clear explanations for the changes. Before applying the fix, it also provided a preview of the added, removed, or modified code, which allowed me to understand the reasoning behind the fix before accepting it. This saved me a significant amount of time that I would have otherwise spent debugging manually or searching for solutions online.
When Copilot’s suggestions needed further clarification, I often cross-referenced its solutions with ChatGPT. For example, if Copilot fixed a syntax issue but didn’t explain the underlying problem thoroughly, I would paste the suggestion into ChatGPT and ask, “What does this fix address, and why was it necessary?” This process helped me solidify my understanding of the code while leveraging the strengths of both tools.

#### 12. Documenting Code:

While Copilot is excellent for writing code, it also assisted me in documenting it properly. For instance, when I wrote a complex function, Copilot would suggest inline comments and JSDoc-style documentation that described the inputs, outputs, and purpose of the function. This feature was especially useful in ensuring that my code was clear and maintainable. However, I still made sure to review and adjust the comments to ensure they were accurate and meaningful.




#### 13. Quality Assurance:

For quality assurance, GitHub Copilot has been a game-changer. When ESLint flagged errors during development, Copilot often provided immediate solutions, which I could apply without disrupting my workflow. One example was fixing trailing commas and spacing issues, which are small but common problems that can be tedious to resolve manually.

However, I noticed that Copilot occasionally solved one issue while inadvertently introducing another. For example, fixing a function in one file sometimes removed an important line of code that linked to another file, creating new bugs. I learned to review all suggested changes carefully, ensuring they didn’t create unintended side effects.

When AI tools fell short, I would turn to ChatGPT for a second opinion. ChatGPT was particularly useful for pinpointing deeper issues, such as understanding why a specific error occurred or debugging tricky logic problems. By combining the strengths of both tools, I was able to maintain clean, functional code.





#### 14. Other Uses in ICS 314 Not Listed:



## III. Impact on Learning and Understanding:

The impact of AI on my learning experience has been substantial. AI tools like ChatGPT and Copilot helped me understand where things go within a project—such as learning schemas, components, and file structures. Over time, I developed a better sense of how different parts of a program fit together.

AI also improved my problem-solving skills by helping me recognize patterns. Just like solving a Rubik’s cube involves identifying patterns and applying algorithms, using AI tools to debug or refactor code taught me to think systematically. For example, Copilot’s previews of ESLint fixes made me aware of common formatting mistakes, which helped me write cleaner code over time.

However, AI tools sometimes provided solutions that didn’t work immediately. This forced me to troubleshoot and refine answers, ultimately enhancing my understanding of the underlying concepts.

## IV. Practical Applications:

AI’s role extends far beyond ICS 314. A prominent real-world application is Tesla’s self-driving technology, led by Elon Musk. Tesla’s AI systems rely on machine learning, computer vision, and neural networks to analyze real-time data and make decisions such as lane changes and obstacle detection. This technology showcases how AI can solve complex problems like autonomous driving, which requires split-second decision-making and precision.

While I haven’t personally applied AI to side projects yet, seeing how it transforms industries like transportation inspires me to explore its potential in future projects.

## V. Challenges and Opportunities:

One of the main challenges with AI is that it doesn’t always provide the right code or solution. For example, when creating React components, AI might default to using <div> elements instead of best practices like semantic React elements. This is where instructor feedback becomes critical for catching these oversights and ensuring the code aligns with course expectations.

I also see an opportunity for educators to emphasize using AI tools as a guide, not a replacement for learning. Encouraging students to focus on core fundamentals—like understanding documentation and writing code independently—will ensure they build a strong foundation while benefiting from AI.

## VI. Comparative Analysis:

Engagement:
Traditional teaching methods, such as problem-specific videos or lectures, feel more engaging because they provide structure and context. AI tools, on the other hand, feel like crash courses mixed with chatbots. While AI is interactive, having a real person teaching concepts still feels more natural and effective.

Knowledge Retention:
I retain knowledge better through traditional methods like lectures and reading when I’m actively building something alongside it. AI can feel static unless used as a supplement while working on a project.

Skill Development:
Skill development is best when combining both approaches. AI enhances practical skills by providing real-time answers and fixes, but traditional teaching builds a deeper understanding of concepts.


## VII. Future Considerations:

The future of AI in software engineering education is bright. I see AI enabling more personalized learning experiences, where tools can adapt to a student’s learning style—whether it’s visual, auditory, or interactive. For example, AI could explain code in a conversational tone tailored to how someone prefers to learn.

However, the biggest challenge will be ensuring students don’t become overly reliant on AI. To prepare for the real world, students must still do the “legwork”: understanding syntax, referencing documentation, and being able to explain their code completely. AI is an excellent tool, but it must be used ethically and responsibly.


## VIII. Conclusion:
AI has proven to be one of the greatest tools in modern technology, offering significant benefits like jump-starting projects, debugging, and explaining complex topics. However, it’s essential to balance AI usage with traditional learning methods to build a strong foundation.

My recommendation is for students to use AI as a tool to assist their learning—not replace it. Learning the basics, referencing documentation, and practicing coding independently are still critical skills for any software engineer. Overall, AI is most effective when used ethically and responsibly to enhance, not replace, human learning.

