# [Modular Code by Hypermodularity](https://www.coders.info/)

From #clean ideas to code #smells ... Let's talk about The Pragmatic Development based on [HyperModularity](https://wiki.opensourceecology.org/wiki/Hypermodularity)

## Code Expectations

### everyone expect:
  + [clean code](https://en.wikipedia.org/wiki/SOLID)
  + [patterns](https://en.wikipedia.org/wiki/Software_design_pattern)
  + [KISS](https://en.wikipedia.org/wiki/KISS_principle)
  + ...
    
![KISS](https://github.com/tom-sapletta-com/clean-code/assets/5669657/96c736d2-a189-4894-9a1a-cfdf79232bfd)

  
### no one expects the spanish inquisition
  

![no one expects the spanish inquisition](https://github.com/tom-sapletta-com/modular-code/assets/5669657/af423bc7-8112-4d35-8145-882f85299750)



## Code Reality

+ [Legacy Code](https://en.wikipedia.org/wiki/Legacy_system)
+ [Spaghetti Code](https://en.wikipedia.org/wiki/Spaghetti_code)
+ [Code Smell](https://en.wikipedia.org/wiki/Code_smell)
+ ...



## Software Development


+ **software development** is the ongoing **refinement** of code to meet evolving service **requirements** and user **expectations**
+ **software development** is continuous **code improvement** for the implementation of **services** based on **requirements** resulting from changing **expectations**


## SDLC

That flowchart represents the software development life cycle with its stages and some of the units that need to be controlled at each stage. 

![sdlc2](https://github.com/coders-info/www/assets/5669657/c13803af-7335-41fb-8c4d-33e096d4d055)



## Modular code of network

In modular code of network, modular principles help by encouraging the development of concise, focused, and reusable modules that interact with well-defined interfaces, making the overall system robust and adaptable to changes.
Using these principles, developers are encouraged to pay attention to the bigger picture, strive to maintain consistency in code structure, and promote maintainability and scalability.
The concept of hypermodularity has been taken to the next level, where modularity is extremely pronounced, allowing for even greater flexibility, customization, interchangeability and scalability.


![Modular code of network](https://github.com/coders-info/www/assets/5669657/ccee5072-87d6-413c-ba33-37d4777d8a8f)



## Modular principles

It emphasizes the key attributes of modules in a modular code network, including being concise, focused, reusable, and having well-defined interfaces that enhance robustness and adaptability.

### Environment
+ **management** over **creation**
+ **requirements** over **expectations**

### Source-code
+ **reusability** over code **development**
+ **writing** over **refactoring** code

### Data
+ data **standardization** first
+ **fat-data** over **fat-function**



## Expected Outcomes

Hypermodular design principle of creating complex systems from smaller, easily managed, interchangeable and often standardized parts or modules, offers more of flexibility, customization, interchangeability, and scalability.
By following the modular design principles, developers should aim for the larger framework by ensuring the code structure remains consistent and the product becomes maintainable and scalable.



## What Hypermodularity is?

Hypermodularity refers to specialized modularity to design configurable systems, products, technologies or processes.
The more modules there are, the more combinations we have at our disposal. The increase in the number of modules forces their specialization.

Hypermodularity is not about writing, but about reusing code in a network of dependencies

Hypermodularity shifts the burden of programming:
+ from development to management
+ from programming to defining services based on available source-code and data

The smallest element of a modular network is one running service that can be written or reused thanks to successive modular building blocks of reusable code.

This is the hyper modular network of code ...


![hypermodularity](https://github.com/tom-sapletta-com/modular-code/assets/5669657/87475ed6-5a5e-432a-a6e2-8174952f14d7)




## How?

Modular programming is a software design approach that focuses on breaking down programs into independent, interchangeable modules where each contains everything necessary to execute a specific functionality. This separation simplifies complex systems, makes the code easier to manage, and promotes code reuse. 

Here’s how each of the mentioned principle fits into modular programming:

### 1. Management over Production
   - **Why to Use:** The emphasis on management rather than production ensures that codebases are well-organized and easy to navigate, making the development process more efficient and faster.
   - **How to Use:** Use a clear modular structure in which each module has one responsibility. Organize code repositories and document each module's functionality and interfaces. This helps not only with current production, but also with future management and scaling of the code base.

### 2. Requirements over Expectations
   - **Why to Use:** Prioritizing requirements ensures that the modules developed will meet the actual needs of the users or system, instead of being based on developers' assumptions or expectations that may not align.
   - **How to Use:** Start with a comprehensive requirements analysis and use it to define the scope and design of each module. Make sure you create test cases based on requirements rather than expectations to verify that the module works as expected.

### 3. Reusability over Code Development
   - **Why to Use:** Focusing on reusability can significantly reduce development time and effort, as well as reduce the risk of errors because well-tested modules can be reused rather than rebuilt.
   - **How to Use:** Design modules with generality and loose coupling in mind. Create tool libraries, follow standard interfaces, and use design patterns for easy reuse. Make sure that the module does not depend heavily on a specific context or other modules.

### 4. Writing over Refactoring Code
   - **Why to Use:** Writing code correctly from the start reduces the need for extensive refactoring later, which can be resource-intensive and risky if it leads to unforeseen problems.
   - **How to Use:** Spend more time in the design and planning phase to thoroughly understand the requirements. Write simple, clean and understandable code and include reviews and pair programming to detect potential problems early.

### 5. Data Standardization First
   - **Why to Use:** Standardization simplifies data exchange between modules and systems, promotes interoperability, and reduces complexity when scaling or integrating with other systems.
   - **How to Use:** Define clear protocols, data formats and interfaces from the beginning. When possible, stick to well-accepted industry standards and ensure that all modules comply with specific data standards.

### 6. Fat-Data over Fat-Function
   - **Why to Use:** This principle encourages the creation of data structures with rich information content, reducing and moving the logical functions to interfaces and middleware
   - **How to Use:** Design your data models to be comprehensive and include all necessary information. This approach often favors object-oriented designs, where data and related behaviors are combined into objects. Divide objects into data models that do not contain method functions and those that contain them but do not have attributes, i.e. data. Separation of data from functions facilitates expansion and does not create artificial dependencies. For OOP - [Object-oriented programming](https://en.wikipedia.org/wiki/Object-oriented_programming), [Single-responsibility principle](https://en.wikipedia.org/wiki/Single-responsibility_principle) and [Dependency injection](https://en.wikipedia.org/wiki/Dependency_injection) will be helpful



## Hypermodular SDLC

Hyper-modular development emphasizes the use of highly reusable, encapsulated code modules that can be configured and connected through dependencies to create complex systems.
In this paradigm, rather than writing extensive new code, developers focus on integrating existing modules, each providing a specific piece of functionality that can be independently developed, tested, and maintained.

![hypermodular-development2](https://github.com/coders-info/www/assets/5669657/a8c06fbe-66d5-4970-88eb-2e866be0f1d4)


In this flowchart, each node represents a step or unit of control within the hyper-modular development process:

- **Planning**: Establishes the necessary requirements and assesses the inventory of available modules, mapping out the needed dependencies for the project.
- **Integration**: Involves selecting suitable modules, configuring dependencies between them, and conducting integration tests to ensure the modules work well together.
- **Iteration**: Iterations are shorter and more flexible, focusing on updating modules based on feedback, while improving performance and handling any technical debt.
- **Deployment**: The configured system is deployed to a staging environment for final verification before being released into production.
- **Maintenance**: Ongoing monitoring of the system, tracking issues, and refining individual modules occur post-deployment.

This methodology streamlines the development process, prioritizing composition over custom development, and made possible by advances in package managers and the widespread availability of software modules.


## Tools?

We need more tools, something called:
+ Service-based component management tools
+ Network of Source-code management system 


### Git is about versioning code

In the development of a modular network versioning system extending the capabilities of [Git](https://en.wikipedia.org/wiki/Git) a distributed **version control system** that tracks changes in any set of computer files, usually used for coordinating work among programmers who are collaboratively developing source code during software development. 
Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different computers).


### Service-based component management tools

is about network of code (Service-based components)
The tool based on git versioned code will help to manage the level of **resuabuility**

The next layer system should help managed **network of code**, Service-based component management tools provide the ability to view, install and register components according to a model-based approach. 
Moreover, in practice, reuse is not a binary concept: there is a need to control and administer levels of reuse. 
Such component management tools are important in hypermodularization.




## Where?

+ hypermodular solutions, examples, use cases on [hypermodular.com is a blog about the hypermodular world](http://www.hypermodular.com)


## More... 

+ more about [HyperModularity](https://www.hypermodularity.com/) in draft of book


## Author

+ Hyper Modules Developer [Tom Sapletta](https://tom.sapletta.com/) 

  
---

+ [edit](https://github.com/coders-info/www/edit/main/README.md)
+ [project](https://github.com/coders-info/)
