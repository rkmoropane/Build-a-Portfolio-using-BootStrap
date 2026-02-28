# Build a Portfolio Using Bootstrap 
___

In this course we created a PortFolio Website, added the projects that was done during the Zaio Bootcamp. I learnt some basic project management, and learnt key skills that employers look for, and built this portfolio of practical experience.

## What we will be doing.
___

- Learn Bootstrap: 
- Build portfolio
- Reinforce Git concepts
Imporve your soft skills:
 + Communication
 + Teamwork
 + Problem Solving
 + Work Ethic
 + Time management
 + Adaptability


**What's BootStrap**
- Allows us to build responsive apps, `https://getbootstrap.com/`

- The ability of BootStrap to automatically adapt to different screen sizes.
- You can link the CSS BooStrap to an HTML Document using the `<link>` tag with the appropriate BootStrap CSS file.
- BootStrap icons: Scalable vector icons designed by BootStrap

**What is a BootStrap theme?**
- A set of predefined color schemes and styles for BootStrap components
- 
 
**How can You apply a bootstrap theme to your project.**
- You can link to the theme CSS file after linking to the BootStrap CSS file.

- We chose the 'Cover' example in one of the Bootstrap examples in the official Bootstrap website.


- Applied the correct link of the Bootstrap to the BootStrap CSS file from official website:
 + replaced: `<link href="../assets/dist/css/bootstrap.min.css" rel="stylesheet" />` with the link `<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">`
 + Boom the Cover Website looks exactly as it should be!!!

**Setting up CI/CD**
- This helps with continuous integration and continuous deployment, everytime when code changes are pushed to the default branch(main), these changes will be deployed to the production code in live.

## some of the Bootstrap classes applied:
e.g.:
> `p-5`: 
```default-set-standard
$spacer: 1rem;
$spacers: (
  0: 0,
  1: $spacer * .25,
  2: $spacer * .5,
  3: $spacer,
  4: $spacer * 1.5,
  5: $spacer * 3,
);
```

## Attempt on the Javascript for functionality.
- use the following to understand the `addEventListener`: https://www.w3schools.com/js/js_htmldom_eventlistener.asp

- **Which JavaScript method is commonly used to toggle the visibility of an HTML element by adding or removing a CSS class?**
 > `element.classList.toggle()`


- **In JavaScript, which event is triggered when a user scrolls a webpage, allowing you to respond to the scrolling action?**
 > `scroll`

- **Which CSS property is commonly used to create smooth transitions between different states of an element, such as changing its color or size?**
 > `transition`

## Some of the BootStrap classes created by default:

- **Which Bootstrap component is used to create visually appealing content containers with headers and footers?**
 > `.card`

- **In Bootstrap, which class is used to create a responsive container for your website's content?**
 > `.container`

- **What does the CSS property "box-sizing: border-box" do?**
 > It includes the element's padding and border within its total width and height

- **What does the class col-md-6 represent in Bootstrap's grid system?**
 > A column with a width of 6 units on medium and larger screens.

- **How would you define a column that takes up 12 units of width on small screens and 6 units of width on medium and larger screens?**
 > col-sm-12, col-md-6

- **What is the purpose of the col-sm-12 class in Bootstrap?**
 > It creates a column that spans 12 units of width on small screens and above.

- **What is the purpose of the Bootstrap class .lead?**
 > It adds extra spacing and increases font size for introducing key content

- **Which HTML tag is used to emphasize text within a document and apply strong importance?**
 > `<strong>`

- **Which Bootstrap class is used to create an image that scales with the size of its parent container?**
 > `.img-fluid`

- **What is the purpose of the Bootstrap class .badge?**
 > It generates a small, circular label or badge to display additional information

- **How can you add a badge to a Bootstrap button using the .badge class?**
 > ``<button class="badge badge-primary">Button</button>``

- **Which of the following statements is true about the Bootstrap .badge class?**
 > It can be used within a `<span>` element to display a badge

- **What does the Bootstrap class mt-3 do?**
 > It applies a large margin to the top of an element

- **Which of the following is the purpose of the class text-md-start in Bootstrap?**
 > It aligns the text to the left in medium-sized screens and larger.

- **What is the role of the text-center class in Bootstrap?**
 > It applies a centered alignment to the text within its container.

- **What is the primary purpose of the Bootstrap class .card?**
 > It creates a container for content with a consistent structure, including header, body, and footer sections

- **How does the Bootstrap class mt-3 affect an element?**
 > It applies a margin to the top of the element, creating vertical spacing

- **What does the Bootstrap class .btn refer to?**
 >  It defines a button element with basic styling and behavior

- **What are Bootstrap Icons**
 > Pre-designed vector icons that can be easily customized and used in Bootstrap projects

- **Which class is used to add a Bootstrap Icon to an element?**
 > `.bi`

- **Which HTML element is commonly used to add Bootstrap Icons to a webpage?**
 > `<i>`

- **In Bootstrap, what does the class .fs-2 represent?**
 > It increases the font size to 2 times the default size

- **In HTML, what is the purpose of the `<mark>` tag?**
> It defines a section of text with a special mark for emphasis

- **What is the purpose of the .form-control class in Bootstrap?**
 > It styles form inputs and textarea elements

- **Which class is used to create a group of checkboxes or radio buttons in Bootstrap?**
 > `.form-check`

- **Which class is used to create a multi-line text input (textarea) in Bootstrap?**
 > `.form-control`

- **Which Bootstrap class is used to create a navigation bar that sticks to the top of the viewport even when scrolling?**
 > `.fixed-top`

- **What does the CSS property opacity control?**
 > The visibility of an element.

- **To create a smooth scrolling effect within a webpage using an anchor tag, what should the href attribute contain?**
 > An ID selector of the target section within the page.

- **Which Bootstrap class is used to create a flexible container that enables a horizontal layout for its child elements?**
 > `.d-flex`

- **What is the purpose of the .align-items-center class in Bootstrap?**
 >Centers an element vertically within its parent.

- **Which Bootstrap class is used to horizontally center the content of a flex container?**
 > `.justify-content-center`

## Typed js
- Access the typedjs repository from github: `https://github.com/mattboldt/typed.js`
- **import the following CDN into your html document:**
 > `<script src="https://unpkg.com/typed.js@3.0.0/dist/typed.umd.js"></script>`

