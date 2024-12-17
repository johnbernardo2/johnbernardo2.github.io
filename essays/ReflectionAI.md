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

<div style="display: flex; gap: 10px; justify-content: center;">
    <img src="../img/girlCyborg.jpg" alt="Cyborg Girl" style="width: 200px;">
    <img src="../img/terminator.jpg" alt="Terminator" style="width: 280px;">
</div>



## I. Introduction: 

Artificial Intelligence (AI) is undeniably reshaping the way we learn, work, and interact with technology. In education, AI has emerged as a powerful tool to enhance efficiency and accelerate understanding. While its benefits are clear, its usage also raises important debates about dependency and the need for foundational knowledge. Just as a calculator aids in solving complex equations but doesn’t inherently teach calculus, AI is most effective when used as a tool rather than a crutch.

The relevance of AI to software engineering parallels this drive for efficiency and enhanced learning. Debugging, often regarded as one of the most frustrating parts of programming, is a prime example.  AI tools like ChatGPT and Github Copilot can assist by pinpointing problematic areas, suggesting fixes, and even explaining the root cause—all without needing to consult a colleague or supervisor..

Personally, I’ve found AI invaluable for breaking down complex concepts. Whether asking, "Why does this work this way?" or "How do these elements relate?", AI provides analogies and clear explanations that help me grasp difficult topics faster. It’s like having a knowledgeable tutor available 24/7. There’s a saying: “If you can’t explain it to a 5-year-old, you don’t understand it yourself.” For me, AI bridges that gap between confusion and clarity, making it easier to learn and apply new knowledge effectively.


## II. Personal Experience with AI:


#### 1. Experience WODs:

Initially, I would rely heavily on the instructional videos for the Experience WODs, simply copying the code the instructor provided. For example, during E12 and the Jamba Juice WODs, I followed the videos closely to ensure I didn’t make mistakes. However, as the course progressed, particularly with assignment WODs like E46: Island Snow in Next.js, I used ChatGPT to generate code based on the instructions, sometimes pasting the entire task prompt into GPT. I felt this was fine as long as I understood the syntax, logic, and language being used. GPT gave me a quick way to get started, but I still ensured I reviewed the output to understand the implementation.


#### 2. In-class Practice WODs:

For practice WODs, my approach was pretty much the same. Whether working at home or in class, I would use ChatGPT to generate solutions based on the instructions. This process helped me quickly identify what needed to be done and reduced time spent getting stuck on small issues. For example, if a WOD involved styling elements or creating a React component, GPT’s output provided a strong starting point. I often made minor changes afterward to ensure I understood the solution fully.

#### 3. In-class WODs:

During the actual WODs, I continued the same method—copying the instructions and using GPT to generate the code quickly. This gave me a huge head start, especially when dealing with repetitive components like footers, navbar, and body content that required specific styling. Having the basic structure already set up with the correct colors and sizes allowed me to focus on smaller tweaks and completing the functionality.

#### 4. Essays: 

For essays, I primarily used Grammarly to refine my grammar and tone. Occasionally, I would use ChatGPT to ask myself questions about the topic to brainstorm ideas. For instance, if I had to explain a personal topic, I’d ask GPT: “What can I ask myself to answer this”?” This helped me organize my thoughts and ensure I addressed the topic clearly. However, I avoided using GPT to rewrite entire essays because it often made the writing too formal and less authentic. I feel that my voice is an important part of my writing, and overusing GPT removes that personal touch.

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
A simple coding example where I used GPT was for the WOD E30: BrowserHistory1. The task was to create an HTML document with four sections: "Introduction," "A brief history of IE," "A brief history of Firefox," and "A brief history of Chrome."

Instead of starting from scratch, I asked GPT to generate a basic structure with this prompt:

"Do 6, Structure the document into four subsections: “Introduction“, “A brief history of IE“, “A brief history of Firefox“, and “A brief history of Chrome“. The links take you to text you can use for each of these sections. Be sure to preserve the paragraphs."

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>A history of browsers</title>
</head>
<body>
  <!-- Table of Contents -->
  <section id="table-of-contents">
    <h1>Table of Contents</h1>
    <ul>
      <li><a href="#introduction">Introduction</a></li>
      <li><a href="#ie">A brief history of IE</a></li>
      <li><a href="#firefox">A brief history of Firefox</a></li>
      <li><a href="#chrome">A brief history of Chrome</a></li>
    </ul>
  </section>

  <!-- Introduction Section -->
  <section id="introduction">
    <h2>Introduction</h2>
    <p>
      The history of web browsers dates back to the early 1990s, where the first browsers enabled users to explore the World Wide Web. Since then, browsers have evolved tremendously to become powerful tools for accessing the internet.
      Learn more about the <a href="https://en.wikipedia.org/wiki/History_of_the_web" target="_blank">history of the web</a>.
    </p>
  </section>


```

And so forth, a jump into the WOD with the boilerplate, formatting, and everything rather than having to type it all manually.



#### 10. Explaining Code:

I use GPT to break down things if I don't understand them, or if I'm on a hunch.

Let's say I don't understand what the boiler plate is for, I'll simply ask "What does this mean? <insert boiler plate from #9>"

GPT's response:

```

<!DOCTYPE html> declares the document as HTML5 for proper browser rendering.
<html lang="en"> sets the primary language to English.
The <meta charset="UTF-8"> ensures correct character encoding for all symbols and text.
<meta name="viewport" content="width=device-width, initial-scale=1.0"> makes the page responsive on all screen sizes.

```

Okay, so then some of it is pretty self explainable, I learned that html lang sets the language, and if I wanted it to be Frenchs I can simply change "en" to "fr".
#### 11. Writing Code:

I frequently used GitHub Copilot to assist with writing code efficiently. One particularly helpful use case was fixing ESLint errors. Copilot would highlight problematic lines of code and provide instant suggestions with clear explanations for the changes. Before applying the fix, it also provided a preview of the added, removed, or modified code, which allowed me to understand the reasoning behind the fix before accepting it. This saved me a significant amount of time that I would have otherwise spent debugging manually or searching for solutions online.
When Copilot’s suggestions needed further clarification, I often cross-referenced its solutions with ChatGPT. For example, if Copilot fixed a syntax issue but didn’t explain the underlying problem thoroughly, I would paste the suggestion into ChatGPT and ask, “What does this fix address, and why was it necessary?” This process helped me solidify my understanding of the code while leveraging the strengths of both tools.

#### 12. Documenting Code:

While GitHub Copilot is excellent for writing code, it also assisted me in improving code clarity by suggesting inline comments when working with TypeScript and adhering to Airbnb ESLint standards. For example, when writing a complex function, Copilot would propose comments describing what certain parts of the function did, making it easier to understand at a glance.

This was particularly helpful for maintaining clean and readable code, especially since Airbnb ESLint enforces strict formatting and clarity rules. If I missed something, such as adding clarity for a parameter’s purpose or the role of a conditional statement, Copilot would automatically highlight areas where comments would be helpful.

That said, I always made sure to review and refine the suggested comments to ensure they reflected the true logic and purpose of the code. While Copilot’s suggestions were helpful, they sometimes lacked context or were overly generic, so refining them was still a necessary step for accuracy and readability.




#### 13. Quality Assurance:

For quality assurance, GitHub Copilot has been a game-changer. When ESLint flagged errors during development, Copilot often provided immediate solutions, which I could apply without disrupting my workflow. One example was fixing trailing commas and spacing issues, which are small but common problems that can be tedious to resolve manually.

However, I noticed that Copilot occasionally solved one issue while inadvertently introducing another. For example, fixing a function in one file sometimes removed an important line of code that linked to another file, creating new bugs. I learned to review all suggested changes carefully, ensuring they didn’t create unintended side effects.

When AI tools fell short, I would turn to ChatGPT for a second opinion. ChatGPT was particularly useful for pinpointing deeper issues, such as understanding why a specific error occurred or debugging tricky logic problems. By combining the strengths of both tools, I was able to maintain clean, functional code.





#### 14. Other Uses in ICS 314 Not Listed:

Everything used in ICS 314 is already listed.

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

