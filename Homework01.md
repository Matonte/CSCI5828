# CSCI 5828
# Homework #1
## Matt Weber

 1. Essential Difficulties are problems that arise in software engineering that are inherent to software itself; they lie within the fundamental processes of producing software. An example would be trying to scope and define a software system based on requirements gathered from various shareholder groups.
 
 2. Accidental Difficulties are challenges and problems that arise as part of the software engineering process and the production of software. These difficulties focus more on HOW the software is created, and references the tools and processes engineers may use to generate software. An example would be using an optimized compiler for a project that increases performance but requires sections of the program to be rewritten into a new programming language.
 3. The 4 Essential Difficulties are complexity, conformity, changeability, and invisibility.
	 - Complexity - Software itself is complex, but software systems can be magnitudes higher in complexity, and this seems to be trending upwards.  This nature of software leads to difficulties simply because there are so many "moving parts" within a software system. An example would be a full network stack, with support for various HBA types and conversion to a common format for processing I/O.
	 - Conformity - A lot of complexity in software is due to having to conform to various outside influences and factors. There are specifications, requirements, shareholder requests, legacy support, feature evolution that require software to be adapted and grown. This inherently leads to difficulties as many times the requests can be arbitrary and unpredictable. An example of conformity is updating a software system to handle new requirements as part of a revised interface specification.
	 - Changeability - Software is viewed as easily changed, and ever-updating requirements require constant turnover of code. 
This lack of a static status is a factor of many difficulties, as constant change is not only difficult to implement, but it introduces the risk of adding instability to the software system as well.  An example of changeability is the constant patches and updates many applications are required to receive in order to support various different devices, especially in the mobile segment of software.
	 - Invisibility - Software is not easily visualized; it is extremely hard to graphically represent an entire software system.  This is a basic cause of many difficulties - we simply cannot see all the parts and states at once, there is no way to lay out a system and encapsulate all the needed information.  An example of this is the fact that there are so many different UML diagrams, each needed to convey some aspect of a software system, but there is no "primary" diagram that can capture all the information at once.
 4. Brooks defines a silver bullet as a single technique or technology that by itself can deliver one order-of-magnitude improvement to some aspect of software development. He believes that no such silver bullet exists, as essential difficulties are the underlying factor in software engineering inefficiency, and most attempts at significant improvement in software engineering do not actually address essential difficulties, but rather accidental difficulties that arise as part of the software engineering process.
 5. Software Engineering v. Computer Science - Define Software Engineering.  Its comparison to computer science is that it applies the knowledge and theory produced by computer science and applies in meaningful and beneficial ways.
 6. Define 5 SE concepts and discuss importance. The Core Principles are:
	- Specification - Laying out specific parameters and requirements for every aspect of software engineering.  Makes collaboration easier, and helps drive clean APIs for faster integration of various parts. Makes the SE process more intuitive and easier to learn
	- Translation - Main work of software engineering, to translate data/work from one specification to the next. Example is a network stack, translating from the physical layer up through various layers to produce intended results.
	- Iteration - How the work of software engineering is executed; produces meaningful results in much quicker time.  Agile is built around iterative development.
	
	The primary tools used for software engineering are: 
	- Abstractions - Taking a complex set of steps/processes and breaking them down into understandable parts that can can be developed as part of a complete system.
	- Conversations - Communication is the key to developing good software.  Understanding requirements, interactions with other developers, components, etc all requires conversations in order to successfully drive a software project.

