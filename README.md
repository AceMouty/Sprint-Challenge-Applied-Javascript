# Sprint-Challenge Applied Javascript - Lambda Times

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored the DOM and the concept of components. During this Sprint, you studied the DOM, DOM Events, and Components, as well as HTTP GET requests, and the axios library. In your challenge this week, you will demonstrate proficiency by creating an online Lambda newspaper called "Lambda Times."

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your Tead Lead and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in Applied JavaScript.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your Team Lead.

## Description

You are going to create a Lambda Newspaper. Your job is going to be to create the components that make up the newspaper's home page. You will do this at first with static data, then you will request data from a server to create dynamic components.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. What is the DOM?
   
	 The DOM is `an API for HTML and XML documents`, every element in page is actually a `DOM node`. The DOM represents the page structure and developers can change the structure, style and content on a page using JavaScript. The DOM gets its default structure from the HTML or XML pages it recieves but can be drastically changed from its original state using a client side scripting language such as JavaScript. You can view the DOM by accessing your browsers dev tools. Most people think this is the HTML when infact it's not, this is a visual representation of the current state of the DOM. With dev tools open you can view live changes happening to the DOM when interacting with the page.

2. What is an event?

	 An event is how a user can interact with a page. Events occur from user interaction from keyboards, mice, etc. an event can also happpen from pages loading this is the `load` event. When events happen the DOM creates what is called an `event object` and `propagtes` the event. The event object carries information about the event that has occured so that it can be handled at either that DOM node or at any point up the DOM tree from the point of origin.   

3. What is an event listener?

	 Event listeners are used to capture an event and do something with it. Event listeners take in two arguements, the event you want to capture and a callback funciton. Event listeners are applied to DOM nodes and when a correspoing event occurs, the node will capture that event and do somehting with it based on the instructions in the callback function.

	

4. Why would we convert a NodeList into an Array?

	 NodeList look like arrays with their syntax however this data type only has access to one array like method, the `forEach` method. If you want to have accesss to the rest of all the array methods you have to use `Array.from()`. 

5. What is a component?
	 
	 A `component` is a samller part or an element of a larger whole. Components are single modular pieces of reuseable code that can be used like legos to build a big end product that has a bunch of little pieces to it. Componets can stand on their own, all you need to do is pass data to it and it will build out an entire lego piece for you. Components are mad up of JS, HTML and CSS.

### Git Set up

* [ ] Fork the project into your GitHub user account
* [ ] Clone the forked project into a directory on your machine
* [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
* [ ] You are now ready to build this project with your preferred IDE

## Minimum Viable Product

Your finished project must include all of the following requirements:

* [ ] Look through the HTML code and familiarize yourself with the different sections. Some of them already exist, but some need to be filled in. DO NOT add any code to the HTML file itself.

* [ ] Following the instructions in the `Header/index.js` file, create the Header component. 

* [ ] Following the instructions in the `Tabs/index.js` file, create individual Tabs components.

* [ ] Following the instructions in the `Cards/index.js` file, create individual Cards components.

## Stretch Problems

Your stretch challenge is to write the functionality of a `Carousel` component. This is an advanced challenge, so you are not expected to be able to complete it. If you begin and don't finish, you should still submit with what you have. This is going to be a bit different because you are going to need to create some advanced functionality for the carousel. There is no need to request data for this exercise.

* [ ] Complete the carousel functionality in `Carousel.js`

* [ ] If you complete the Carousel, add functionality so that the carousel slides when the buttons are pressed instead of just appearing.

* [ ] Create an 'infinite loop' carousel. In which as long as you click on an arrow, the array of images will loop over itself.

* [ ] If you have finished the above, research `data attributes`. Implement data attributes within your tabs as well as your cards. Give the tabs functionality so that when they are clicked they filter the cards to only display the cards that contain that topic.
