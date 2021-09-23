# GEOGRAPHY 495B: Web & Mobile GIS

**Meetings:**
-   **Lectures:** Tuesdays and Thursdays 1:00 - 2:20 PM PST on [Zoom]()
-   **Labs:** Friday 12:30 - 1:20 PM PST in [SMI 401](https://www.google.com/maps/place/Smith+Hall+(SMI)/@47.6564039,-122.3096954,17z/data=!3m1!4b1!4m5!3m4!1s0x5490148d3c47332b:0x804039aa1d9e590b!8m2!3d47.6563716!4d-122.3074586)

**Personnel:**
-   **Bo Zhao**, Instructor, zhaobo@uw.edu | Office Hour: Thursdays 3 to 6:00 PM PST on [Zoom](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UUZvU2gxXzVlZnZpfGRlZmF1bHR8NzM4ODA5MzUyNjAxZDU2Y2ViNTZiMzk2ZmM0N2VmNzI) or by appointment
-   **Steven Bao**, Teaching Assistant, bxq98@uw.edu |  Office Hour: Fridays 10 to 11:30 AM PST on [Zoom](https://washington.zoom.us/j/96550080363) or by appointment

> _This web page is the syllabus - There is no printed version, please refer here instead. Make sure refer to this page as often as possible. Also, Feel free to ask the instructor for clarifications whenever needed._

![course cover](assets/img/cover.jpg)

Web & Mobile GIS, the combination of web, mobile technology, and GIS, is a promising and fast-growing field. It has extended the power of GIS from local servers to the cloud, and put online maps and geospatial intelligence in multiple aspects of human society. This course aims to provide students with the essential knowledge needed for managing web & mobile GIS projects, teach students the latest geospatial cloud technologies needed for building modern web GIS applications, and inspire students with real-world case studies. To cultivate the spirit of open source, all the required software, packages are open source, and the course handout will be shared on GitHub. 

This course introduces concepts and techniques of web programming, digital storytelling, online project management, and web-based cartographic principles for developing, evaluating, and using web maps. To promote the equal access to web mapping technology, we ensure all the web mapping applications from course materials can be opened, debugged or further developed in either Windows or Mac OSX operating systems, and all the relevant software or services are either open source or free. This course is comprised of two major components, including lectures and lab exercises. The lectures focus on the theories and principles behind web mapping, including system architecture, responsive user graphic design, map design and geo-narrative. The lab exercises focus on practical skills for web programming, 2d and 3d web mapping, web mapping services, and digital storytelling. 

From this course, students can learn both the principles of web-based cartography and the practical skills for web mapping, and develop the capabilities of map aesthetics and critique. **The course schedule might be slightly updated when the quarter unfolds, the latest schedule will be on the github repository front page. Please ensure to check it frequently.** If you have any question :raising_hand:, feel free to contact [Dr. Bo Zhao](mail://zhao2@oregonstate.edu).


## :calendar: Weekly Schedule

- **Preparation:** [Gear up the working environment](assets/gearup.md) :computer: :beer:
- **Weekly Expectations:** Each student is supposed to a) attend both lecture and lab sections each week, b) complete all weekly readings before the lecture begins.

### Week 1: Intro to Web GIS

<!-- Sept 29 -->

-   **Readings:** 
    - [Intro to Web GIS]()
    - [Git Handbook `Optional`](https://guides.github.com/introduction/git-handbook/). Git is an example of a distributed version control system (DVCS) commonly used for open source and commercial software development. DVCSs allow full access to every file, branch, and iteration of a project, and allows every user access to a full and self-contained history of all changes. Unlike once popular centralized version control systems, DVCSs like Git don’t need a constant connection to a central repository. Developers can work anywhere and collaborate asynchronously from any time zone.
    - [Mastering Markdown `Optional`](https://guides.github.com/features/mastering-markdown/). Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. 

-   **Lab 1:** [Project management using GitHub](labs/lab01) `Due: Oct 8th, by 11:59pm`

### Week 2: Web Fundamentals

<!-- Oct 4 -->
    
-   **Readings:** 
    - [Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web). This is a concise series introducing you to the practicalities of web development. You'll set up the tools you need to construct a simple webpage and publish your own simple code.
    - [The web and web standards](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards). This article provides some useful background on the Web — how it came about, what web standard technologies are, how they work together, why "web developer" is a great career to choose, and what kinds of best practices you'll learn about through the course.
    - [Common questions on Web mechanics](https://developer.mozilla.org/en-US/docs/Learn/Common_questions#web_mechanics). This document covers questions relating to general knowledge of the web ecosystem and how it works.

-   **Quiz 1:** [Web Basics](https://canvas.uw.edu/courses/1479441/quizzes/1531301) `Due: Oct 8th, by 11:59pm`


### Week 3: Front-end Coding: Html and CSS

<!-- Oct 11 -->
To build websites, you should know about HTML — the fundamental technology used to define the structure of a webpage. HTML is used to specify whether your web content should be recognized as a paragraph, list, heading, link, image, multimedia player, form, or one of many other available elements or even a new element that you define.

Cascading Stylesheets — or CSS — is the first technology you should start learning after HTML. While HTML is used to define the structure and semantics of your content, CSS is used to style it and lay it out. For example, you can use CSS to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features.

-   **Readings:** 
    - [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML). This document sets the stage, getting you used to important concepts and syntax, looking at applying HTML to text, how to create hyperlinks, and how to use HTML to structure a webpage.
    - [Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding) This document explores how to use HTML to include multimedia in your web pages, including the different ways that images can be included, and how to embed video, audio, and even entire other webpages.
    - [CSS First Steps](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps) CSS (Cascading Style Sheets) is used to style and lay out web pages — for example, to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features. This module provides a gentle beginning to your path towards CSS mastery with the basics of how it works, what the syntax looks like, and how you can start using it to add styling to HTML.
    - [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors) In CSS, selectors are used to target the HTML elements on our web pages that we want to style. There are a wide variety of CSS selectors available, allowing for fine-grained precision when selecting elements to style. In this article and its sub-articles we'll run through the different types in great detail, seeing how they work.
    - [Introduction to CSS layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Introduction) This article will recap some of the CSS layout features we've already touched upon in previous modules, such as different display values, as well as introduce some of the concepts we'll be covering throughout this module.

-   **Quiz 2:** [HTML Fundamentals](https://canvas.uw.edu/courses/1479441/quizzes/1531299) `Due: Oct 13th, by 11:59pm`
-   **Quiz 3:** [CSS Fundamentals](https://canvas.uw.edu/courses/1479441/quizzes/1531540) `Due: Oct 15th, by 11:59pm`

-   **Lab 2:** [Responsive web page design](labs/lab03) `Due: Oct 22th, by 11:59pm`
    - [Responsive SideBar](https://www.w3schools.com/howto/howto_css_sidebar_responsive.asp)
    - [Mobile Menu](https://www.w3schools.com/howto/howto_js_mobile_navbar.asp)
    - [a Sidebar with Icons](https://www.w3schools.com/howto/howto_css_sidebar_icons.asp)


### Week 4: Front-end Coding: Javascript and GeoJSON

<!-- Oct 18 -->

-   **Readings:** 
    - [JavaScript First Steps](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps). In this document,we first answer some fundamental questions such as "what is JavaScript?", "what does it look like?", and "what can it do?", before moving on to taking you through your first practical experience of writing JavaScript. After that, we discuss some key building blocks in detail, such as variables, strings, numbers and arrays.

    - [Javascript Building Blocks](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks). In this document, we continue our coverage of all JavaScript's key fundamental features, turning our attention to commonly-encountered types of code blocks such as conditional statements, loops, functions, and events. You've seen this stuff already in the course, but only in passing — here we'll discuss it all explicitly.


    - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON). JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax. It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be displayed on a web page, or vice versa). You'll come across it quite often, so in this article we give you all you need to work with JSON using JavaScript, including parsing JSON so you can access data within it, and creating JSON.
    
    - [Making asynchronous programming easier with async and await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await) More recent additions to the JavaScript language are async functions and the await keyword, added in ECMAScript 2017. These features basically act as syntactic sugar on top of promises, making asynchronous code easier to write and to read afterwards. They make async code look more like old-school synchronous code, so they're well worth learning. This article gives you what you need to know.
    
    - [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON). GeoJSON is an open standard format designed for representing simple geographical features, along with their non-spatial attributes. It is based on the JSON format. In addition, a notable offspring of GeoJSON is TopoJSON, an extension of GeoJSON that encodes geospatial topology and that typically provides smaller file sizes.

-   **Quiz 4:** [Javascript Fundamentals](labs/lab02) `Due: Oct 22th, by 11:59pm`

-   **Lab 3:** [Asynchronous GeoJSON data loading and visualization](labs/lab03) `Due:Feb 12th, by 11:59pm`

        - [Zebra Striped Table](https://www.w3schools.com/howto/howto_css_table_zebra.asp)
        - [Sort a Table](https://www.w3schools.com/howto/howto_js_sort_table.asp)

### Week 5 : UX/UI Design

<!-- Oct 25 -->

-   **Readings**

    - [Meet The Team" Page](https://www.w3schools.com/howto/howto_css_team.asp)
    - [Section Counter](https://www.w3schools.com/howto/howto_css_section_counter.asp)
    - [Scroll Drawing](https://www.w3schools.com/howto/howto_js_scrolldrawing.asp)


### Week 6 : Thematic Map Design on the web

<!-- Nov 1 -->

-   **Readings:**
    - [making thematic map using mapbox](https://docs.mapbox.com/help/tutorials/create-a-map-with-data-visualization-component/)
    - [Add custom markers in Mapbox GL JS](https://docs.mapbox.com/help/tutorials/custom-markers-gl-js/)


-   **Lab 4:** [Interactive web mapping](labs/lab04) `Due: Jan 16th, by 11:59pm`
    - https://docs.mapbox.com/help/tutorials/choropleth-studio-gl-pt-1/


### Week 7 : Geocoding 

<!-- Nov 8 -->

This week we will explore the concept of geo-narrative, the use of storytelling in mapping practice, by looking at existing geo-narrative mapping projects and engaging in a group discussion and map critique.

-   **Readings:** 
    - [Local search with the Geocoding API](https://docs.mapbox.com/help/tutorials/local-search-geocoding-api/)


### Week 8 : Web-based spatial analysis I: Sorting by distance

<!-- Nov 15 -->

-   **Readings:** 
    - [Sort data by Distance](https://docs.mapbox.com/help/tutorials/geocode-and-sort-stores/)
-   **Final Project:** [Web-based spatial analysis](labs/lab05) `Due: Jan 16th, by 11:59pm`

### Week 9 : Dealing with time on the web

<!-- Nov 22 -->

-   **Readings:** 
    [Visualize geographical changes over time](https://docs.mapbox.com/help/tutorials/show-changes-over-time/)


### Week 10 : Web-based spatial analysis II

<!-- Nov 29 -->

-   **Readings:** 
    - [Nearest neighbor analysis](https://docs.mapbox.com/help/tutorials/analysis-with-turf/)
    - [Buffer and isochrone analysis](https://docs.mapbox.com/help/tutorials/get-started-isochrone-api/)


### Week 11 : Summary and Final Project Presentation

<!-- Dec 6 -->

During the last two meeting sessions, each group will present their final projects. More information about final project will be shared after the mid-term.



## :bell: Course Requirement

**Student Tech Support:**

The Student Tech Loan Program is expanding as quickly as possible. We announced this to undergrads as soon as it hit the airwaves, in hopes some of them who need hardware can reserve for spring quarter. They expect new/additional machines to arrive in April. STLP Website: <https://stlp.uw.edu/> (check the [Spring Announcement](https://drive.google.com/file/d/1qlbUBPdQFJt_jXS2fAOtORwNrBVtZqCb/view)).

**GitHub:** This course material will be hosted on GitHub instead of UW Canvas. On this dedicated GitHub repository, you can find most of the course material, participate in group discussions by submitting GitHub issues, and create new GitHub repositories to turn in the lab deliverables. By the end of this quarter, you will be more proficient in operating a cloud-based coding environment and able to host your work online as a way to gain public and peer attentions.

**Labs:** You need to finish all four labs by the due date. In order to help you work on each lab, we will walk through most of the labs during the lab sessions.

**Participation in in-class discussion:** Complete all assigned readings and get familiar with the lab instructions before class meetings, and actively participate in critical discussions of those readings. You should have completed all of the weekly readings before our Friday lab sections as these sections will be devoted to critical discussion and engagement with the required readings.

**Final Project:**  [the detailed requirement for final project](project/project.md)


## :heavy_check_mark: Grading

| Grading items   | %   |
| --------------- | --- |
| Participation   | 5%  |
| Quizzes         | 25% |
| Lab Assignments | 30% |
| Final project   | 15% |

> The item `participation` includes your participation in the class (e.g., self-introduction, answer questions in class, etc.) and/or your response on GitHub issues (ask questions via GitHub issue, and help your classmates using the GitHub issues function). As well as participation in the weekly lab/discussion sections.

## :notebook_with_decorative_cover: Equity & Inclusivity

Our very highest priorities include creating a brave and supportive class environment where each of us contributes, we can ask big questions, we give and receive critiques in a supportive way, we notice and engage the ways that we are differently situated within past and present relationship of power, privilege and oppression. I invite you to think hard about how race, gender identity, religion, age, citizenship status, first language, ability, sexuality, class, and other axes are at work in our interactions, and what this might mean in terms of when to speak up, when to step back, how to listen, and much more. Each of you is a welcome and invaluable part of our collective whole.

## :love_letter: Disability Accommodations

We welcome the opportunity to work with any students with disabilities in this class to ensure equal access to the course. If you have a letter from Disability Resources for Students (DRS) outlining your academic accommodations, please present the letter to me (or email us, to confirm, if the letter is electronic) as soon as possible so that we can discuss the accommodations you may need for this class. Any discussions between student and professor need to occur as early as possible in order for adequate arrangements to be made. If you do not yet have a letter from DRS, but would like to request academic accommodations due to a disability, please contact DRS [here (Links to an external site.)](https://depts.washington.edu/uwdrs/), or in-person at 011 Mary Gates Hall, or at 206-543-8924 (Voice & Relay), <mailto:uwdrs@uw.edu>.

## :church:  Religious Accommodations

Washington state law requires that UW develop a policy for accommodation of student absences or significant hardship due to reasons of faith or conscience, or for organized religious activities. The UW’s policy, including more information about how to request an accommodation, is available at [Religious Accommodations Policy](https://registrar.washington.edu/staffandfaculty/religious-accommodations-policy/). Accommodations must be requested within the first two weeks of this course using the [Religious Accommodations Request form](https://https:/registrar.washington.edu/students/religious-accommodations-request/).

 ## :memo:  Student Care & Safety

It is important that you take care of yourselves inside and outside of class as you work through stress and other obstacles. There are many different support services on campus that can help, such as the Counseling Center, Hall Health, and the IMA. UW’s Student Care program can help you connect to these and other resources. Learn more an contact them directly: http://depts.washington.edu/livewell/student-care/, livewell@uw.edu, or 206.543.6085. If you are concerned about yourself or a friend who is struggling SafeCampus is a helpful resource. Please add 206.685.7233 to your phones

## :book: Copyright

 This course advocates for the open culture. The course materials are open source for both students and open source community to access.

 Notably, students are not allow to videotape or audio-tape (record) this class in any form, and sharing recordings outside of class without the written consent of each student in the class is not permitted by [FERPA](https://registrar.washington.edu/students/ferpa/). However, I will try to record most of the classes via Zoom and share them via Canvas. Even so, I still encourage each of you attend the lectures instead of watching the recorded videos afterwards. Your in-class participation is a key factor to yield the best learning outcome. The instructor determines if their class can and cannot be recorded. This decision should be clearly communicated by the instructor at the beginning and throughout the quarter. In Zoom, the recording feature can be controlled by the instructor, as the meeting host.