#### The Typescript Ecosystem and the Future of Adoption

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

<img width="392" alt="CleanShot 2022-02-16 at 09 27 11@2x" src="https://user-images.githubusercontent.com/17182194/154310817-53b64ccb-2598-431c-b1cc-95c470cc0739.png">

_**Figure 1 - Stacked Area chart showing npm downloads over a 5 year period**_

This depicts the number of npm downloads for the following packages:

	1. Flow
	2. PropTypes
	3. React
	4. Typescript
	
Typescript alone has more than double the installs of all nearest packages combined.

*****

Along with webpack, React, and a few other packages, Typescript has one of the highest adoptions and positive dev experiences.

<img width="399" alt="CleanShot 2022-02-16 at 09 28 49@2x" src="https://user-images.githubusercontent.com/17182194/154310925-00f0d024-b227-47b2-ae6c-63ecc9f4631b.png">

_**Figure 2 - Scatter graph of technologies change over time**_

*****

Here shows that Typescript has hit the Adoption phase that indicated high usage, high satisfaction, and a safe technology to adopt.


<img width="394" alt="CleanShot 2022-02-16 at 09 29 15@2x" src="https://user-images.githubusercontent.com/17182194/154311135-a9ff604f-a178-4941-8767-158855f27ae6.png">

_**Figure 3 - Scatter plot showing satisfaction vs usage**_

---

TypeScript users are returning to TypeScript at a higher percentage than other solutions.

<img width="384" alt="CleanShot 2022-02-16 at 09 30 15@2x" src="https://user-images.githubusercontent.com/17182194/154311185-508d6bec-a7f4-4e29-9c4f-167d886c351c.png">

_**Figure 4 - Bar chart of technology usage cardinality**_

---

Again, we see a very high ranking of Satisfaction, interest, usage, and awareness ratio.

<img width="392" alt="CleanShot 2022-02-16 at 09 30 32@2x" src="https://user-images.githubusercontent.com/17182194/154311270-5c645f04-b57c-4309-b987-13d424fb062f.png">

_**Figure 5 - Gantt? Chart of javascript "flavor" rankings**_

---

This was a surprise for me. As far as Build Tools go, Typescript has better satisfaction, interest, usage, and awareness ratio rankings than webpack.

<img width="393" alt="CleanShot 2022-02-16 at 09 31 04@2x" src="https://user-images.githubusercontent.com/17182194/154311324-1384f8b8-0490-4509-90e0-9fbb132b6da9.png">

_**Figure 6 - Gantt? Chart of build tool rankings**_
