# Learning Vue.js
### Introduction
#### 1.1 Is Vue for you?
Welcome to Learning Vue.js. I'm Uzzal Kumar Roy and if you're looking to become a more efficient and versatile front end developer, then you're in the right place. In this course, I'll talk about the reasons that we use frameworks like Vue.js in the first place and how to quickly get up and running with nothing more than a browser and a text editor. We'll take a detailed look at how to manage form controls and dynamic attributes of HTML elements. You'll learn how to take advantage of Vue's powerful reactivity system that allows us to keep our UI in sync with our data model and how to use Vue's flexible computed properties that are cached for optimal performance. There are many different reasons that developers choose one framework over another or end up loving a particular framework. If you're not a regular user of any framework yet, or if you're looking to switch to one that you're more comfortable with, then by the end of this course, you'll have a solid understanding of whether Vue can play a role in helping you get your work done or build your next passion project.
#### 1.2 What you should know
To get the most possible out of this course, you should already be comfortable working with basic HTML and CSS. You should also have some experience with JavaScript including ECMAScript2015 syntax or ECMAScript 6 as it was formerly known. Some familiarity with the command line, Node.JS, and the npm package manager will be helpful, but the overwhelming majority of videos involve only the use of a text editor and a browser.

### 1. Managing Dynamic Content and Behavior
#### 1.1 What problems does Vue.js solve?
Before writing any code. I want to spend a few minutes talking about our motivation for using Vue.js and the problems that it aims to solve as a framework for JavaScript applications. In the days when libraries like jQuery were first widely used, or even earlier, it was common to write JavaScript code that looked like this. The purpose of this function is to add an element to the Dom or document object model. Our in memory representation of the webpage. In turn, updating the onscreen representation for the user. But after the call to appendElement on the first line this function is almost entirely concerned with updating the rest of the UI to make sure everything stays in a consistent state. While we could extract some of this logic to another reusable function, the point is that we need to explicitly do this additional work to keep the UI in sync, whenever we make a small change. And the more complex the UI becomes the more code it takes to manage all of that. Managing complexity is something I often think about when using Vue, the concept is self-explanatory but I probably first came across the term in Steve McConnell's classic book, Code Complete. He calls it Software's Primary Technical Imperative. If we can accept that managing complexity is at least one of our chief concerns as web developers whether we're talking about the code itself or just how our software can help a user complete a complex task, then it makes sense to use tools that are designed to manage or reduce that complexity that go beyond what's available out of the box. The native Dom API that you see used here on this MDN web docs page, was really designed with just making dynamic updates to the Dom even possible and not with managing the complexity that's involved with doing that in a large application. A better approach for our hypothetical example, if we could achieve it somehow, would be to set up triggers, when we initialize the app for those cascading updates to happen automatically, whenever we add or even remove or edit a row in our table. Then we could just call appendElement without having to wrap it in the function that also handles keeping the UI in sync. This makeSureEverythingStaysInSyncFromNowOn concept is where frameworks like Vue.js really shine. And it's a large part of why we use them to build our applications. We say that Vue is reactive. Its easy to set things up so that the UI is kept in sync with the underlying data, by automatically reacting to changes in that data. It's also progressive. It's easy to get started with nothing more than a script tag in order to add a small amount of dynamic behavior to your app. And then you can progressively add more features and tools as needed, as your app grows and becomes more sophisticated. It's declarative, we can set up the relationships and calculations required to keep our UI in sync when our application starts and then not have to worry about them later when managing user interactions and other updates. Finally, it's composable. We'll see that you can structure your application using Vue's component system for easier code reuse and easier reasoning about your applications logic and state. In the next video, we'll jump right in and talk about how to add Vue.js to a new or existing project.
#### 1.2 Adding Vue.js to a project
Whether you're starting a new project or you have an existing project that you're considering using Vue for, getting set up is simple. At the time I'm recording this course, the Get Started button on the vuejs.org homepage still points to the version 2 guide. So instead, we'll click up here to get to the version 3 guide and then click Get Started. So, if I click this Installation button here I'm presented with several different ways to get set up. The first, Import from a CDN, really just means adding a script tag to an HTML page. And I could do that with the CDN URL, or I could download it and host the script locally. If you're familiar with the command line package manager, NPM then you probably know that most JavaScript libraries and frameworks that are still used today are available as downloadable packages that can be automatically installed with those tools. Vue CLI, or command line interface, is just a more sophisticated way of installing Vue with a package manager along with some other useful development tools and some skeleton code to help you get started. To keep things simple for now, we'll grab the URL from the CDN page, but instead of using this script tag I'm going to copy this URL and then use the URL of the specific version that that redirects to. So, in case, you are following along, you can ensure that you're using the same version that I'm using in the video, which is 3.0.7. In the exercise files for this video you'll find index.hmtl. This will be the starting point for our example project, which will be a flashcard app. This page pulls in a style sheet and a data file, none of which is specific to vue.js. The CSS just helps us see what's changing a little bit better as we build out the app and makes it a little prettier. So don't worry about its content. And the data file just contains an array of JavaScript objects that represent flashcards, each with a front and a back property. So, the front is the name of an item, or a concept and the back is its description, sort of like questions and answers. So, we'll add the script tag down here under the data file. And then, in the next video, we'll talk about how Vue can manage this section of the document, this div, to dynamically render it using some of the flashcard attributes from our data file.
#### 1.3 Configuring dynamic elements
#### 1.4 Binding to inner text and HTML
#### 1.5 Dynamic attributes and v-model
#### 1.6 Handling events with v-on

### 2. Form Control Bindings
#### 2.1 Text field bindings
#### 2.2 Using v-model with related checkboxes
#### 2.3 Configuring radio buttons and select elements
#### 2.4 Adding modifiers
#### 2.5 Computed properties

### 3. Rendering and Styling Logic
#### 3.1 Conditional rendering with v-if
#### 3.2 Conditional rendering with v-show
#### 3.3 Looping and list rendering with v-for
#### 3.4 Binding style attributes
#### 3.5 Binding CSS classes

### 4. Using Vue Components
#### 4.1 Creating and registering components
#### 4.2 Using component props
#### 4.3 Configuring custom events
### 4.4 Using component slots
#### 4.5 Installing Vue CLI
### Creating single file components

### Next steps

