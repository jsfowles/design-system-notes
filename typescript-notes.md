## Kyper Design System

#### The Typescript Ecosystem and the Future of Design Systems

### Abstract
JavaScript was initially a scripting language for creating small interactive web pages. However, massive applications, both web pages and server applications, are increasingly being developed using JavaScript. The dynamic nature of the JavaScript language makes it hard to create proper tooling with features such as auto-completion and code-navigation. TypeScript is a JavaScript superset that adds, on top of JavaScript, an optional static type system, which facilitates features such as auto-completion, code navigation, and detection of type errors. 
The two most common ways of type checking are at runtime (`React.PropTypes`), and a static checker ( Typescript). Typescript can intercept errors upstream while coding. `React.PropTypes` will catch them downstream while testing. 
In 2021  Storybook re-architecteed it's core performance, in partnership with Webpack and Shopify UX engineering. 

#### Table of Contents
	1. State of TypeScript
	2. Proof of Concept
	3. Implementation
	4. State of Storybook
	5. Security Mitigation
	

#### List of Figures
	1. Stacked Area chart showing npm downloads over a 5 year period
	2. Scatter graph of technologies change over time
	3. Scatter plot showing satisfaction vs usage
	4. Bar chart of technology usage cardinality
	5. Gantt? Chart of javascript "flavor" rankings
	6. Gantt? Chart of build tool rankings

	
### State of Typescript

TypeScript is a superset of features that enable us to use types in JavaScript. It gives us a module system, classes, interfaces, and a rich type system.
Basically, what TypeScript does is that it will compile the code and generate a compilation of errors if it finds syntax errors, like misspellings.

![image](/Users/jacob.fowles/Library/Containers/co.noteplan.NotePlan-setapp/Data/Library/Application Support/co.noteplan.NotePlan-setapp/Calendar/20220203_attachments/CleanShot 2022-02-03 at 10.38.22@2x.png)  
*Figure 1 - Stacked Area chart showing npm downloads over a 5 year period*

This depicts the number of npm downloads for the following packages:
	1. Flow
	2. PropTypes
	3. React
	4. Typescript
Typescript alone has more than double the installs of all nearest packages combined.

*****

Along with webpack, React, and a few other packages, Typescript has one of the highest adoptions and positive dev experiences.

![image](/Users/jacob.fowles/Library/Containers/co.noteplan.NotePlan-setapp/Data/Library/Application Support/co.noteplan.NotePlan-setapp/Calendar/20220203_attachments/CleanShot 2022-02-03 at 10.50.17@2x.png)
*Figure 2 - Scatter graph of technologies change over time*
*****

Here shows that Typescript has hit the Adoption phase that indicated high usage, high satisfaction, and a safe technology to adopt.

![image](/Users/jacob.fowles/Library/Containers/co.noteplan.NotePlan-setapp/Data/Library/Application Support/co.noteplan.NotePlan-setapp/Calendar/20220203_attachments/CleanShot 2022-02-03 at 10.51.11@2x.png)
*Figure 3 - Scatter plot showing satisfaction vs usage*
---

TypeScript users are returning to TypeScript at a higher percentage than other solutions.
![image](/Users/jacob.fowles/Library/Containers/co.noteplan.NotePlan-setapp/Data/Library/Application Support/co.noteplan.NotePlan-setapp/Calendar/20220203_attachments/CleanShot 2022-02-03 at 10.51.44@2x.png)
*Figure 4 - Bar chart of technology usage cardinality*
---

Again, we see a very high ranking of Satisfaction, interest, usage, and awareness ratio.
![image](/Users/jacob.fowles/Library/Containers/co.noteplan.NotePlan-setapp/Data/Library/Application Support/co.noteplan.NotePlan-setapp/Calendar/20220203_attachments/CleanShot 2022-02-03 at 10.52.06@2x.png)
*Figure 5 - Gantt? Chart of javascript "flavor" rankings*
---

This was a surprise for me. As far as Build Tools go, Typescript has better satisfaction, interest, usage, and awareness ratio rankings than webpack.
![image](/Users/jacob.fowles/Library/Containers/co.noteplan.NotePlan-setapp/Data/Library/Application Support/co.noteplan.NotePlan-setapp/Calendar/20220203_attachments/CleanShot 2022-02-03 at 10.55.05@2x.png)
*Figure 6 - Gantt? Chart of build tool rankings*

### Proof of Concept

A [Proof of Concept](https://gitlab.mx.com/mx/pulse/-/merge_requests/1802) has been create by Bill Bridegroom for the Pulse team. 

### State of Storybook

In previous years, Storybook built new workflows such as documenting and testing components, while also solving multi-framework compatibility. Thanks to these explorations, they now understand what’s needed for a solid UI developer experience.

*But as Storybook expands, it’s trickier to maintain. This is especially painful since frontend frameworks and build tools are rapidly evolving.*

In 2021 we re-architected Storybook’s core for performance, in partnership with Webpack and Shopify UX engineering. Now that we have a better handle on performance, we’re setting our sights on improving stability.

Storybook rearchitected its core performance, in partnership with Webpack and Shopify UX engineering. 

In 2022, they've prioritized refining Storybook’s existing features. They now have full coverage of the primary workflows of develop, test, and document. That means Storybook can continue innovating under the hood. Here’s the roadmap:

 - Speed: Webpack 5 build optimizations
 - Weight: Modern ESM browser target to slim and simplify distribution
 - Dependency conflicts: Pre-bundle dependencies to reduce install size and conflicts
 - Reliability: Define a tight boundary around Storybook’s core and test more rigorously
