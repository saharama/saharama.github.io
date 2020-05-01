---
layout: essay
type: essay
published: true
title: Patterns of Power

# All dates must be YYYY-MM-DD format!
date: 2020-04-30
labels:
  - Design Patterns
  - Software Engineering
  - Power Systems
---

## Patterns: A Power Play

<img class="ui medium right floated rounded image" src="https://images-na.ssl-images-amazon.com/images/I/41JIh4KMHRL._SX355_BO1,204,203,200_.jpg">

The 48 Laws of Power, by Robert Greene, explains 48 different concepts that can be applied to different situations in order to maintain power and control. In the text, the author goes in depth in case studies to highlight the strengths and detriments that a particular "law of power" can be used. For example, Law 15 states to "Crush your enemy totally." The author then elaborates on the historical moves in the Chinese war for democracy where leader Chiang Kai-shek did not crush his opponent's army completely, and paid the price for it much later. While this book follows a fairly one-sided view, these values and situations can theoretically be applied in wars, politics, and even everyday life, preferably also taking ethics into account. The book identifies issues, identifies patterns, and provides solutions in the form of "laws" that can be used to retain the greatest amount of power possible in the respective situation.

Similarly, we can define and choose a *design pattern* for optimal operation of a system. To summarize the module content, a design pattern in software engineering is a particular solution or setup of a system that is known to be a good remedy to a specific problem or task. In addition to knowing the commonplace solution to a commonly occurring issue, it is also important to acknowledge the trade-offs of the design pattern. Examples of design patterns, given by this module, are Factory, Singleton, Observer, Publish-Subscribe, and Model-View-Controller (MVC).

Photo from Amazon.com.

## Watt Did You Do?
My team's final project for ICS314 is called Cram Connect. We are designing a web application that allows UH Manoa students to find study locations that fit their respective needs and receive real-time notifications regarding the current status of those locations. As discussed in the Design Patterns module, we are using Meteor for our project and it clearly uses a Subscription-Publication design pattern to pass data between the server and client. Given that our project's system design uses the same patterns as Bowfolios, we are also using the Model-View-Controller design pattern to connect MongoDB, Blaze, and Flow Router, respectively.

In addition to my experiences in with Javascript in ICS314, I am now more aware of design patterns we have used in my Electrical Engineering (EE) classes. Design patterns were not explicitly taught, and it was up to individual students to get a feel for them on their own. In the C++ programming class, EE205, I can now identify that my team used the Observer design pattern to implement our game. We used the Simple Fast Multimedia Library (SFML) as a graphics library, which also helped to handle events. We needed to continuously check game conditions for specific events. The game was created as a state machine, so once certain conditions were meant, the game needed to change states, for example: from maze state to battle state. We did experience a common drawback of this pattern, as the code was quite a pain to trace and debug. In EE260 and EE361, our labs incorporated programming, and in some cases circuit building, of Microprocessors and FPGAs. In terms of bridging both hardware and software, one could say that we used the MVC design pattern. In the case of the microprocessor, the Model consisted of the input buttons and temporarily stored data, the View referred to the LEDs or displays in our circuits to communicate to the user, and a Controller such as the microprocessor to connect the Model and View components.

## A "Shocking" Twist

<img class="ui medium right floated image" src="../images/pattern-power/design-power.jpg">

As a student studying electrical engineering, there are definitely existing design patterns in terms of pure hardware. For instance, you can apply different circuit configurations to the different pins of a transistor to give it either the qualities of a switch or an amplifier. During my summer internship, as depicted in the adjacent photo, I helped to design parts of a microgrid power system for a small community. In this case, my mentor explained a list of different switchgear and electrical circuit breaker configurations and challenged me to justify why we had chosen the design that we did. In addition to the power configuration, I also worked on the development of the network and control connections, as different portions of our power grid would need to be monitored or controlled remotely. Noting that the majority of my target audience at the moment are software-oriented individuals, I do not expect the average reader to completely understand what I just said. However, I wanted to stress the fact that very similar to software design patterns, I was also able to identify design patterns for electric power systems and networks. In the end, design patterns help us to generalize problems and understand the benefits of certain methods from a system level perspective. Many times in engineering, these patterns are not explicitly explained to entry-level hires. Therefore, it has been very beneficial to me to understand that many complex system follow general design patterns, and I definitely hope to use this new perspective to my benefit in the near future!
