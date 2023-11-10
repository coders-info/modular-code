# [Modular Code by Hypermodularity](https://www.coders.info/)

From #clean ideas to code #smells ... Let's talk about The Pragmatic Development based on Hypermodularity

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



## The Pragmatic Development

development = production of **code** to implement **services** based on **requirements**

![hypermodularity](https://github.com/tom-sapletta-com/modular-code/assets/5669657/87475ed6-5a5e-432a-a6e2-8174952f14d7)



## Modular principles

### Environment
+ **management** over production
+ **requirements** over expectations

### Source-code
+ **reusability** over code development
+ **writing** over refactoring code

### Data
+ data **standardization** first
+ **fat-data** over fat-function


## Why and How?

Modular programming is a software design approach that focuses on breaking down programs into independent, interchangeable modules where each contains everything necessary to execute a specific functionality. This separation simplifies complex systems, makes the code easier to manage, and promotes code reuse. Here’s how each of the principles you've mentioned fits into modular programming:

### 1. Management over Production
   - **Why to Use:** Emphasizing management over mere production ensures that codebases are well-organized and easy to navigate, making the development process more efficient and faster.
   - **How to Use:** Employ a clear modular structure where every module has a single responsibility. Organize code repositories and document the functionalities and interfaces of each module. This not only helps in current production but also in future management and scaling of the codebase.

### 2. Requirements over Expectations
   - **Why to Use:** Prioritizing requirements ensures that the modules developed will meet the actual needs of the users or system, instead of being based on developers' assumptions or expectations that may not align.
   - **How to Use:** Start with a comprehensive analysis of the requirements and use those to define the scope and design of each module. Ensure that you are creating test cases based on requirements, not expectations, to validate that the module performs as intended.

### 3. Reusability over Code Development
   - **Why to Use:** A focus on reusability can substantially cut down on development time and effort, as well as reduce the chance for errors, since well-tested modules can be reused rather than rebuilt.
   - **How to Use:** Design modules with generality and loose coupling in mind. Develop utility libraries, follow standard interfaces, and use design patterns that facilitate reuse. Ensure that the module does not depend heavily on the specific context or other modules.

### 4. Writing over Refactoring Code
   - **Why to Use:** Writing code correctly from the outset reduces the need for extensive refactoring later on, which can be resource-intensive and risky if it leads to unforeseen issues.
   - **How to Use:** Spend more time on the design and planning phase to get a clear understanding of what’s required. Write simple, clean, and understandable code, and incorporate reviews and pair programming to catch potential issues early.

### 5. Data Standardization First
   - **Why to Use:** Standardization simplifies data interchange between modules and systems, promotes interoperability, and reduces complexity when scaling or integrating with other systems.
   - **How to Use:** Define clear protocols, data formats, and interfaces from the beginning. Stick to well-accepted industry standards wherever possible, and ensure that all modules conform to defined data standards.

### 6. Fat-Data over Fat-Function
   - **Why to Use:** This principle encourages the creation of data structures with rich information content, reducing the logic complexity within functions, and making the system more flexible and scalable.
   - **How to Use:** Design your data models to be comprehensive, encapsulating all the necessary information. This approach often entails favoring object-oriented designs where data and the related behaviors are bundled into objects. Make functions operate on these rich data structures, which can lead to more straightforward and modular code.


## Hypermodularity

Hypermodularity is not about writing, but about reusing code in a network of dependencies

Hypermodularity shifts the burden of programming:
+ from development to management
+ from programming to defining services based on available source-code and data

The smallest element of a modular network is one running service that can be written or reused thanks to successive modular building blocks of reusable code.


This is the hyper modular network of code ...


## Theory


In modular networks of code, these principles help by encouraging the development of concise, focused, and reusable modules that interact with well-defined interfaces, making the overall system robust and adaptable to change. When using these principles, developers are encouraged to be mindful of the big picture, strive for coherence in the codebase structure, and promote maintainability and scalability.

Hypermodularity refers to an advanced or extreme degree of modularity in the design and organization of systems, products, technologies, or processes. 
Modularity itself is a design principle that involves creating complex systems from smaller, manageable, interchangeable, and often standardized parts or modules.
The hypermodularity concept is taken to a higher level, where the modularity is exceptionally pronounced, allowing for even greater flexibility, customization, interchangeability, and scalability. 


## Contexts

+ **Technology and Computing**: In software development, a hypermodular architecture would allow for easier updates, maintenance, and scale, as individual modules or components can be modified or replaced without impacting the entire system.

+ **Manufacturing and Industry**: Hypermodular design in manufacturing processes or equipment can enable factories to quickly adapt to new product lines or changes in demand by reconfiguring modular components.

+ **Urban Design and Architecture**: Hypermodularity in urban design might involve the creation of living spaces or structures that can be quickly assembled, disassembled, and reassembled in different configurations depending on the changing needs of the inhabitants.

+ **Organizational Structures**: In management, a hypermodular organizational structure would reflect a highly flexible and adaptable model where teams or units can be formed, reformed, and disbanded as needed to respond to various projects and challenges.


## Disadvantages 

Hypermodularity is often associated with terms like agility, resilience, and innovation, as it provides a framework for easily adapting to change and fostering continuous improvement. 
Depending on the context of use, hypermodularity can also have drawbacks, such as potential issues with integration, increased complexity in coordination, or loss of optimization for specific functions due to the emphasis on general interchangeability.

## Use Case

+ resuable, modular hardware [Modular Edge Computing Hardware - Militarity](https://www.militarity.com/)
+ modular data storage [Newline Delimited Objects Format - NDOF.org](https://www.ndof.org/)
+ modular network of services based on DNS records configuration [Dynamic Infrastructure for network of Services in SaaS - Dynapsys](http://www.dynapsys.com)
