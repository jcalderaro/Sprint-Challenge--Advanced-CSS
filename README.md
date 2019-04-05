# Sprint Challenge: Advanced CSS - Space Walkers Web Page

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS techniques using Responsive Design and Preprocessing. During this Sprint, you studied how to use the viewport meta tag, media queries, setting up a preprocessor, and advanced use of preprocessing techniques. In your challenge this week, you will demonstrate proficiency by updating a website that is missing content as well as adding mobile styling.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in advanced css and your command of the concepts and techniques in responsive web design and preprocessing.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

The client for this challenge is _Spacewalkers Magazine_. Spacewalkers needs your help to build a small proof of concept website for their marketing team. They have provided designs for both desktop and phone views. In addition to designs and content they have most of the home page coded for you. You just need to finish the navigation and header as well as the mobile styles.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution design files of the desktop and mobile views:

[Click here to review the home design](design-files/home-desktop.png)

[Click here to review the mobile design](design-files/home-mobile.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. What is the difference between an adaptive website and a fully responsive website?

A fully responsive website uses the layout that combines the features of fixed, adaptive, and fluid websites together. The section is generally divided into desktop, tablet, and phone, while using media queries. Despite taking more time to craft, a fully responsive website is the most aesthetically appealing experience for the consumer because based upon any screen size viewport, the page layout will respond by changing orientation to accommodate the device. 

Alternatively, there are adaptive websites that use an overall faster layout by pulling similar concepts from that of a fixed layout. However, they incorporate media queries to create specific breakpoints within the design, generally only at the desktop, tablet, and phone areas. They typically have hard coded pixels that are organized around those queries.

2. Describe what it means to be mobile first vs desktop first.

Essentially both of them will include the same things, however how it is organized and presented, or the focus of the coding, changes based upon the starting point. In a mobile first design, the mindset is to keep everything within the scope of a consumer that is using a variety of phones to scroll and read through the site. Because of the mobile usage, it directly limits how much they can consume textually, as well as the typing function. For example a mobile first product could implore drop down menus and the touch feature, while keeping the usage on brief key points. The limited screen space brings more attention to focusing on what the consumer would want in that moment.

On the other hand there is the desktop first approach. This focuses on showcasing large amounts of text, important information or links, as well as features among the site. Because both the screen and environment is more relaxed, the consumer is able to actually benefit from navigating through different channels to learn. The use of graphics, data, and text can create an in-depth understanding of the product rather than being limited to only accessible features on the go.

To provide an example, in the case of an insurance company if they were to focus on a mobile first approach then their app would be used heavily to file a claim, get roadside assistance, or sift through frequently asked questions. Where as if they took the desktop first approach then they would include more time consuming content like how to contact an agent or how to compare your rates to other companies.

3. What does `font-size: 62.5%` in the `html` tag do for us when using `rem` units?

It's important to first understand what the 62.5% in the html tag is doing. Essentially, that is the percentage to equal 10 pixels. From there you can use rem units with a clear scale in mind. For example making a font size of 1.4 rem is now just 14 pixels. You can combine this to form the font size that can handle both older browsers and newers ones. Combining both in the code allows for consistent and predictable sizing for all browsers. 

4. How would you describe preprocessing to someone new to CSS?

So basically, CSS unchanged or unaltered, in its "vanilla" state functions to add stylistic designs and features onto an already made HTML code. Preprocessors are like modifications, plug-ins, or expansions, that build on vanilla CSS to bring in features that are only accessible within a preprocessor domain. For example the organizational aspect would be the ability to separate all of the different file categories into their own concise documents. This would allow programmers to reference the exact area to improve on in future assignments without having to sift through hundreds or thousands of lines of code. Another key function of preprocessors is the optimization brought in through creating templates or referenceable formats.

Normally in vanilla CSS you would have to manually write the amount of code to produce a button. However in cases where you need to make 10, if not 200 buttons, it becomes significant time wasted. Utilizing preprocessing allows you to create 1 main button that acts as a Queen Bee. From there, you set the remaining future buttons to pull data based on the Queen, in a sense creating a hive of drones and worker bees that take orders from the main.

5. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

My favorite concept with preprocessing is, for lack of a better word, the potential that exists with Queen Bee Design. Having the ability to essentially create one main function that can direct orders to any possible number of drones is an incredible time saver. Through future concepts that add complexity, you can create an entire network of code that all strings back to a handful of codes instead of thousands. My only experience with this previously was with creating in-game macros for popular video games. The idea of having 1 button cast two different abilities based on the context seemed revolutionary. Now with coding and preprocessing, you can expand upon that limitlessly, it's incredible. 

Unfortunately, with the complexity of preprocessing comes the variety of confusing lessons and material. Knowing how to recognize situations where you can apply what you learn, more specifically nesting and media queries are by far my worst area. I find myself often repeating my code or taking significantly more space to reach the same end goal because instead of organizing the code in a methodical manner I have to sift through all of my work. Coding is an environment in which despite the end result being success, you could still fail by comparison to other programmers. Especially when you unlock refactoring and learn how to do what you thought was optimized in half the time. A slow skill floor with a limitless skill ceiling is what makes programming and web design so fulfilling. 

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

Because you are using a preprocessor, there are two parts to setting up your project.  Be sure to run through the git set up first and then set up the preprocessor.

### Git Set up

Follow these steps to set up your project:

- [ ] Create a forked copy of this project.
- [ ] Add your project manager as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your project manager as a reviewer on the pull-request
- [ ] Your project manager will count the project as complete by merging the branch back into master.
 

### Preprocessor Set up

* [ ] Verify that you have LESS installed correctly by running `lessc -v` in your terminal, if you don't get a version message back, reach out to your project manager for help.
* [ ] Open your terminal and navigate to your preprocessing project by using the `cd` command
* [ ] Once in your project's root folder, run the following command `less-watch-compiler less css index.less`
* [ ] Verify your compiler is working correctly by changing the `background-color` on the `html` selector to `red` in your `index.less` file.
* [ ] Once you see the red screen, you can delete that style and you're ready to start on the next task

## Minimum Viable Product

Your finished project must include all of the following requirements:

### Import LESS Files

* [ ] Navigate to your `index.less` file. Notice the file is blank. You have been asked to use a certain import order. That order is as follows:

```markdown
1.variables.less
2.mixins.less
3.reset.less
4.global.less
5.navigation.less
6.footer.less
7.home-page.less
```

_You will know everything is working properly when you see the styles enabled for the provided content._  

### Home Page - Desktop HTML & LESS

* [ ] Take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built.

* [ ] Add a viewport meta tag to the head of your index.html page

* [ ] [Review the provided home desktop design file](design-files/home-desktop.png). You are to build the missing navigation system and header image. You have been provided all content necessary in the [index.html file](index.html)

* [ ] Navigation Styles: Use the `navigation.less` file for styling.

* [ ] Main Content Styles: Use the `home-page.less` file for styling

* [ ] LESS Mixins: Create and use 2 different mixins to aid your styling. Use the `mixins.less` file for your mixins

* [ ] LESS Parametric Mixin: create a parametric mixin that is used to create the `sign up` button styles.

* [ ]  Use at least 2 parameters to create your button

* [ ] Create a hover state that swaps the background color and font color of the base button styles.

### Mobile Design

* [ ] Create a `@phone` variable that contains a `max-width: 500px` media query string. Use the `@phone` variable for all your nested mobile styling.

* [ ] [Review the provided home mobile design file](design-files/home-mobile.png). Match your mobile styling the best you can using the design file.

* [ ] Push your changes and create a pull request if you haven't already.

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items. Come up with content and images that fit the theme.

* [ ] Introduce CSS animations to your site.

* [ ] Create a fixed navigation and add some opacity to the background

* [ ] Create a form that would allow someone to sign up for a Spacewalkers Magazine subscription