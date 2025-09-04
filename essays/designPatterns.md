---
layout: essay
type: essay
title: "Blueprints for Better Software"
# All dates must be YYYY-MM-DD format!
date: 2024-12-04
published: true
labels:
  - Software Engineering
  - Design patterns
  - Object Oriented Programming
  - Autiobiography
---
<img width="300px" class="rounded float-start pe-4" src="https://static5.depositphotos.com/1000892/512/i/950/depositphotos_5123430-stock-photo-part-of-architectural-project.jpg" alt="BluePrint">


*"Have No fear of perfection, you'll never reach it.-- Salvador Dali, Artist"*

Salvador reminds us that perfection is an unattainable idea, and the pursuit of it should not paralyze our creativity or efforts. In software development, much like art, striving for flawless code can hinder progress. On the otherhand, embracing imperfection fosters learning and innovation. Instead of fearing imperfection, we should focus on continuous improvement and creating solutions that are effective and adaptable.

### From Chaos to Order
When building software, design patterns act as the guiding principles or blueprints that bring order to potential chaos. They are solutions to common problems in software engineering and design. They offer a standard approach tot tackle recurring challenges. These patterns aren't strict rules but rather adaptable guidlines that developers can tailor to fit their specific needs. By uding design pattenrs, programmers can write code that is easier to understand, maintain, and extend over time, which saves effort by reducing the likelihood of errors. Like a craftsman using proven techniques to construct furniture, developers rely ont ehse patterns to build complex systems.

### Unlocking the Power of Design
Design patterns are categorized based on their purpose, and this organization makes them easier to learn and apply. Creational patterns, for instance, focus on object creation. They include patterns like Singleton, which ensures that a class has only one instance, and Factory, which creates objects without specifying the exact class type. Meanwhile, Structural patterns deal with the composition of classes and objects, offering methods to combine these elements to create flexible and efficient structures. Examples include Adapter, which allows incompatible interfaces to work together, and Composite, which organizes objects into tree-like structures to handle hierarchies. Finally, Behavioral patterns concentrate on communication between objects, with examples like Observer, which facilitates notifications of state changes, and Strategy, which enables the interchangeability of algorithms.


### The Power of Shared Solutions
The beauty of design patterns lies in their universality. They act as a shared vocabulary among developers, making it easier for teams to collaborate. For example, when someone mentions using an Observer pattern, others on the team can instantly grasp the underlying concept without additional explanation. This shared understanding streamlines communication and accelerates problem-solving. Furthermore, patterns help avoid reinventing the wheel, as they leverage time-tested strategies that reduce the risk of unforeseen complications. Developers can focus on the unique aspects of their projects rather than grappling with problems that have well-established solutions.

### Finding the Right Balance in Design
However, design patterns aren’t a cure-all. They require thoughtful application, as using them unnecessarily can lead to overcomplicated designs. A simple problem doesn’t always need a complex pattern to solve it. Developers must balance simplicity with scalability, choosing the right pattern for the task at hand. Mastery of design patterns comes with experience, but their value becomes clear as projects grow in complexity. Whether creating a simple app or designing a large-scale system, these patterns provide a strong foundation for success.


### Painting my Software Through my Design Patterns
When I first started coding in 8th grade, my approach often felt like reinventing the wheel. I felt like solving problems in isolation without the benfit of established solutions. Learning design patterns transformed how I wrote and structured my code, which provided a toolbox of strategies for common problems. One of the first patterns I applied was the Singleton pattern, which I used in my Final Project: Study Buddy. I used this pattern to figure out how to display a Study Session title to all users of the website. This pattern ensured that the title was consistent for everyone using the site. It also made the code easier to manage since there was only one source of truth for the title. I didn't focus on adding other fields just yet to know exactly which problem to fix first. Using the Singletone pattern helped me see how design patterns can make projects more organized and efficient. From starting witht he basics. It was essential for me to get narrow it down to one item so I can reuse this logic to figure out add the rest of the data fields.

Continuing with the Study Buddy project, I found myself using the Observer Design Pattern. This pattern is essentially about a behavioral design pattern that defines a one to many dependency between objects. When one object changes state, all its dependents are notified and updated. In my project, this is used to design my user to sessions relationship. One user is connected or owns many Study Sessions which is a one to many relationship. The observer which is the study session, updates the field of organizer/owner of the study session. The Observer Design Pattern made it easy to keep the user's sessions updated automatically whenever changes occured such as editing the fields or removing a session. This approach reduced the need for manual updates, and ensured that the data stayed consistent across the application. As a result, it improved both functionality and user experience.

Lastly, for my Study Project, I used the Prototype Design Pattern. This pattern enables the creation of new objects by copying an existing object. I used this pattern when I had to clone a session card but make it different based on the state of the current user session. I made it so that the session cards that are created by a current user contain the button called edit which allows for edit permissions. In contrast, the session cards the current user doesn't own contain the button add. This pattern helped me avoid writing repetitive code for creating similar but slightly different session cards. It made the codebase more efficient and easier to manage by reusing the existing card structure as a template.

### Conclusion: Patterns That Shape Possibilities
Design patterns are more than just tools for solving coding problems. They are the essence of thoughtful, deliberate craftsmanship in software development. They allow developers to harness collective wisdom, turning complex challenges into manageable, elegant solutions. In my journey with the Study Buddy project, these patterns not only brought clarity and efficiency to my code but also taught me the importance of structure and adaptability. By using design patterns like Singleton, Observer, and Prototype, I learned to build systems that are both functional and flexible, meeting the needs of users while staying maintainable for the future. Embracing these patterns isn’t just about writing better code; it’s about approaching software design with creativity, precision, and the confidence to transform ideas into reality.

