<p align = "center" draggable=”false” ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719" 
     width="200px"
     height="auto"/>
</p>

<h1 align="center" id="heading">Session 1: Introduction and Vibe Check</h1>

### [Quicklinks](https://github.com/AI-Maker-Space/AIE5/00_AIM_Quicklinks)

| 🤓 Pre-work | 📰 Session Sheet | ⏺️ Recording     | 🖼️ Slides        | 👨‍💻 Repo         | 📝 Homework      | 📁 Feedback       |
|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|
| [Session 1: Pre-Work](https://www.notion.so/The-AI-Engineering-Bootcamp-Cohort-5-Home-Page-175cd547af3d80969151ebc75bb1d94a?pvs=4#175cd547af3d8159907cf0ac05eb9050)| [Session 1: Introduction and Vibe Check](https://www.notion.so/Session-1-Introduction-and-Vibe-Check-177cd547af3d804d9ec7c0266889f947) | [Recording](https://us02web.zoom.us/rec/share/pNtF3s7dsxOnsDxMALes9o1yPSc0PfHr8rS7aVZSsDKqA9RysEhfzEi57ahT0F_R.eOIPyhx8A9e58B57) (ub?4jfUD) | [Session 1: Cohort Kickoff](https://www.canva.com/design/DAGcIeKKtHE/t9TVvikxC3EUetoqY1YoKA/edit?utm_content=DAGcIeKKtHE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) | [Session 1: Introduction and Vibe Check](https://github.com/AI-Maker-Space/AIE5/tree/main/01_Prompt%20Engineering%20and%20Prototyping%20Best%20Practices)| [Session 1 Assignment: Vibe Check](https://forms.gle/4VVx9rGrK9gqcZ8S9)| [AIE5 Feedback 1/14](https://forms.gle/7nfaP5ngje3HDKjV9)

### Assignment

In the following assignment, you are required to take the app that you created for the AIE5 challenge (from [this repository](https://github.com/AI-Maker-Space/Beyond-ChatGPT)) and conduct what is known, colloquially, as a "vibe check" on the application. 

You will be required to submit a link to your GitHub, as well as screenshots of the completed "vibe checks" through the provided Google Form!

> NOTE: This will require you to make updates to your personal class repository, instructions on that process can be found [here](https://github.com/AI-Maker-Space/AIE5/00_Setting Up Git/README.md)!

#### How AIM Does Assignments
Throughout our time together - we'll be providing a number of assignments. Each assignment can be split into two broad categories:

- Base Assignment - a more conceptual and theory based assignment focused on locking in specific key concepts and learnings.
- Hardmode Assignment - a more programming focused assignment focused on core code-concepts.

Each assignment will have a few of the following categories of exercises:

- ❓Questions - these will be questions that you will be expected to gather the answer to! These can appear as general questions, or questions meant to spark a discussion in your breakout rooms!
- 🏗️ Activities - these will be work or coding activities meant to reinforce specific concepts or theory components.
- 🚧 Advanced Builds - these will only appear in Hardmode assignments, and will require you to build something with little to no help outside of documentation!

##### 🏗️ Activity #1:

Please evaluate your system on the following questions:

1. Explain the concept of object-oriented programming in simple terms to a complete beginner. 

   Of course! Object-oriented programming is a way of writing computer programs by organizing data and the code that works on that data into "objects."

     Imagine objects as containers that hold both data, like a person's name or age, and the code that can perform actions with that data, like displaying the person's information or updating their age.
     
     Objects: Objects are like containers that hold both data and the code that works on that data. For example, a "car" object could hold data like its color, make, and model, along with code to start the engine or change the speed.
     
     Classes: Classes are like blueprints for creating objects. They define what data an object can hold (attributes) and what actions it can perform (methods). Going back to the car example, a "Car" class would define what data a car object should have (color, make, model) and what actions it can do (start engine, change speed).
     
     Inheritance: Inheritance allows one class to inherit attributes and methods from another class. This helps in reusing code and organizing objects in a hierarchy. For instance, a "SUV" class can inherit from the "Car" class, gaining all the attributes and methods of a car while adding its own specific features.
     
     Encapsulation: Encapsulation means bundling the data (attributes) and the methods (functions) that operate on the data together within a class. This helps in keeping the code organized and prevents outside interference with the object's data.
     
     Polymorphism: Polymorphism allows objects of different classes to be treated as objects of a common superclass. This means that a method can work on different types of objects, providing flexibility and extensibility in the code.
     
     In summary, object-oriented programming is a way of structuring code by creating objects that contain both data and the code to work on that data. It helps in organizing code, reusing components, and making programs more flexible and easier to maintain.

    - Aspect Tested: A type of definition to object-oriented programming was provided which I don't think would have benefitted a novice or a complete beginner. When trying to explain the concept, it would certainly benefit to explain with a real life example. None of the above was provided.

2. Read the following paragraph and provide a concise summary of the key points…
    - Aspect Tested: I tested this prompt with the following paragraph:

The chatbot's reponse was longer than the number of words in the input whose summary I tried to generate.

3. Write a short, imaginative story (100–150 words) about a robot finding friendship in an unexpected place.
    - Aspect Tested: At first, the chatbot was able to successfully create a very engaging and story anout a robot named spark and a small, injured bird nestled among the foliage.
    - When I asked it to create another such story it failed to give me a response correctly.
4. If a store sells apples in packs of 4 and oranges in packs of 3, how many packs of each do I need to buy to get exactly 12 apples and 9 oranges?
    - Aspect Tested: The answer to the above question was correct: you would need to buy 3 packs of apples and 3 packs of oranges. But when I tried to ask a follow-up question it failed.
    - I asked it to think through its responses and it generated some additional calculations.
    
5. Rewrite the following paragraph in a professional, formal tone…
    - Aspect Tested: When I just copy pasted the above line without following it up with a paragraph, it generated a sort of blank response without really prompting me to provide me with the paragragh.

This "vibe check" now serves as a baseline, of sorts, to help understand what holes your application has.

##### 🚧 Advanced Build:

Please make adjustments to your application that you believe will improve the vibe check done above, push the changes to your HF Space and redo the above vibe check.

> NOTE: You may reach for improving the model, changing the prompt, or any other method.

### A Note on Vibe Checking

"Vibe checking" is an informal term for cursory unstructured and non-comprehensive evaluation of LLM-powered systems. The idea is to loosely evaluate our system to cover significant and crucial functions where failure would be immediately noticeable and severe.

In essence, it's a first look to ensure your system isn't experiencing catastrophic failure.

##### 🧑‍🤝‍🧑❓ Discussion Question #1:

What are some limitations of vibe checking as an evaluation tool?
1. Lack of Imagination: 
Like in the case of question #3 the chatbot wasn't able to come up with another similar story within the guidelines set.

2. Cannot handle follow-up questions: 
The chatbot wasn't able to handle any follow-up questions and would often forget the context of the first question when trying to answer any follow-up questions.
