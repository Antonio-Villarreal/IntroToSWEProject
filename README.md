# edYOU - The Educational Social Media Application

This was a project created for a class (CEN3031: Introduction to Software Engineering) at the University of Florida between February 2022 and April 2022. Feel free to view our final demonstration of our application right [here](https://www.youtube.com/embed/07hM9DYSllw).

<p align="center">
  <img 
    src="/wireframes/Header.png"
  >
</p>

## Table of Contents
- [Product Vision Statement](#product-vision-statement)
- [Project Overview](#project-overview)
	- [Challenge Statement](#challenge-statement)
	- [Product Description](#product-description)
	- [Technology](#technology)
- [Software Quality](#software-quality)
- [Requirements Documentation](#requirements-documentation)
	- [Story Map](#story-map)
	- [Use Case Model](#use-case-model)
	- [Visual Application Page Breakdown](#visual-application-page-breakdown)
		- [Welcome Page, Login Page, Forgot Password Page, and Registration Page](#figma-wireframes-part-1)
		- [Home Page, Profile Page, and Edit Interests Page](#figma-wireframes-part-2)
- [System Documentation](#system-documentation)
	- [System Architecture](#system-architecture)
	- [System Context Model](#system-context-model)
- [Developer Documentation](#developer-documentation)
- [Sprint Presentations](#sprint-presentations)
	- [Sprint 0](#sprint-0-presentation)
	- [Sprint 1](#sprint-1-presentation)
	- [Sprint 2 & Demo](#sprint-2-presentation-and-demo)
- [Team](#team)

## Product Vision Statement

“FOR students WHO feel unmotivated to learn in a virtual environment, edYOU is an educational mobile app THAT centralizes learning resources based on topics that interest users. UNLIKE other learning apps, where you have to search for only one type of content (videos, articles, courses) manually, OUR PRODUCT will automatically show students a “feed” of all types of content that will help them learn in the field(s) they are interested in.”

## Project Overview

### Challenge Statement
Due to the pandemic and the shift to online learning, the education system continues to face multiple challenges in terms of the quality and delivery of education. Tech-based solutions can bridge the gap in learning and streamline the education system. The education system includes students at all levels, parents, schools, administration and the effects of quality education can have long-term implications on how things evolve in the world.

#### Overall Objectives
-   Gain experience with the software engineering Agile methodology.  
--  Learn the agile methodology   
-- Project planning, backlog, forecasting, and retrospectives.   
--Learn continuous integration, collaboration, version control and software testing.
-   Work in a team oriented environment.   
 --Task distribution, communication and coordination.   
 --Learn to break down tasks and define responsibilities.    
 --Learn to use supporting tools for team collaboration.
-   Create solutions systematically.    
--Learn to create design models.   
--Develop implementation that is consistent with design.
    
#### Our solution addresses the following challenges:
#1 Shared or online learning experiences

#2 Increase student engagement

With our product, we mostly focus on addressing challenge statement #1 (Shared or online learning experiences) because it focuses on combating the lack of interest in online learning experiences. This product mimics common social media platforms' behavior but instead provides a continuous stream of learning and educational resources in short bursts. In addition, we address challenge statement #2 because our product reemphasizes education which can also increase students’ engagement in the online classroom and provide educational resources on specific topics.

### Product Description

An educational social media mobile app that streamlines information (videos, articles, news, etc.) about specific topics that the user is interested in. It formats the information in shorter bursts of consumption like a typical social media platform but emphasizes educational content.

#### Target Audience: 
FOR students WHO feel unmotivated to learn in a virtual environment
  
### Technology
Project Management Tools: Github, Circle CI, Asana
  
Programming Languages/Frameworks: Flutter (Dart), NodeJs, MongoDB, GraphQL, Google APIs, and iPhone/Android Emulators

## Software Quality

![](https://lh5.googleusercontent.com/XBVn3K14F5UzD7yEtEbiFUq07_LO192dB4NoUfGQsKnPcC0I3z5Zr2jqsRvfN8nMmWIn_7raYL4WDBORVIfp8EqdktS20TK_50-JZb_q0W6m1NeLh52xeSDRpzD2vwRrebAebF8II9UNZBfgf60F8OQoNqS7d2G6kRcPoddOZqPQ8Q9d0KBfSUOz7fXg)

#### Reliability

The product’s goal was to be simple in concept but powerful in functionality. This concept forced the team to focus on the quality of the product to make the user features count the most which enabled us to produce a reliable product.

 
####  Availability

We spent time choosing the technology behind the product to ensure that there would be minimal user problems, allowing it to be consistently available to the users.

#### Resilience

We put emphasis on creating a product that utilizes clean code and reliable programming. This enables the product to endure most technical problems because the software team can easily find the source of the problem. In addition, the quality of the code in both the frontend and backend was held to a higher standard to prevent any unforeseeable problems that could arise. The team also spent time researching the appropriate tech stacks that could fulfill the purpose of the application while making it resilient.

#### Maintainability

The code is thoroughly organized by each frontend page. This enables us to easily add new content to a specific page or incorporate a completely new page with ease. Another main component that enables maintainability is our interest options. We are able to stay up to date with popular topics that the users enjoy by adding new interests to the application which enables it to remain relevant.

#### Responsiveness

The application is responsive to the user because of its unique customizations. The user can always go to their profile page to edit their interests and refresh to immediately receive new, personalized content.

#### Usability

The functionality of our product focuses on executing the basic goal of the application which is to act as a tool for the user to learn about their educational interests. This means that the user is able to create an account, set their interests, and access the homepage with personalized content without any complex hurdles.

#### Security

Our product has built-in security on both sides of the application. From a user perspective, the user is required to make an account with a username, password, and email to protect their account. We use input validation to ensure that the user is entering accurate information to further ensure security. On the backend, we encrypted the user’s information, such as their passwords, to take the extra steps to protect user information.

## Requirements Documentation

### Overview
This mobile app lets you choose different educational topics, which gives you articles and videos related to that topic in return.

### Story Map

 Users can register an account with the app while developers confirm the user registration via email. After, users can log in and see the profile page, reset their password if it’s forgotten, and log out. Also, users can select and change preferences, also save and unsave contents that can be seen on the saved page. Below is our story map for the features and the tasks of each feature, and a use case model that demonstrates the flow of actions of the user.

  

![](https://lh6.googleusercontent.com/Dy_dMSnrcusASHuubM-0rtaduIG4f9oNAM4cXUEjhKVdgAJpjCaZX1EvZB4y7CTbBIiOwk_cxzm1C3BkbXTl-hWrtcrAFRBkIiRn9Kj9M_zLsVS6eYZe-rbm2dZ-TPq3cq-XlEP2Adl0PxGAaKoJCX1KDS_ficr_A0s1wgQXlVkq33Iugj2J-iUfhVuI)

  

### Use Case Model

![](https://lh5.googleusercontent.com/javoI_c_GRZHGr1MzkgNl0TcQAEI6xOogthZGhqFZkRkCfU70C02-EPn4aDEfZfkntD3FDAl-cjaERhgZK0WcmNsPnJbNPB1CWSzfIKbv8GFf7mnnlxUX__Hy00FxGZMxDBYJP-jFlPlrDmu3NXl67Wp_6hpT2PshogaTKWHHej9YNxFPUyJ4stkbA1h)

When the user opens the app for the first time (or if they are logged out), they will be greeted with the Welcome Page, where they can choose to either sign up or login. Sign up and Login are very similar in UI, the difference being the functionality (when you click register, it takes you back to the welcome page, when you click login, it takes you to the app itself). The forgot password page sends an email to reset the password.

### Visual Application Page Breakdown

#### Welcome Page, Login Page, Forgot Password Page, and Registration Page
  ##### Figma Wireframes Part 1
<p align="center">
  <img src="https://lh5.googleusercontent.com/jhyYFnyWwoaS7loGnGSwP_RveEZrj7XVCjVxLohz0TGvQIFmzDCEGMrHNqWRNx-9On4pr5SgxRZBPm8SYQKvPPFUk4l9vIZKU_zlnCh3dAXW74qZ-A2mbqLlhsACzMkBX-16FmSWkeDfNowmFTvhy47cdruByHyVv-hdn4O_MAsho6irMD3gmZlTvUek" width="150" />
  <img src="https://lh5.googleusercontent.com/p6i1MYtkEtawxPLKHb48_f26VslmPVJhtMD1h_tN7qRDBeqdRIZExx-ZiTDKT8sDcxHfVuCpxnWBuk6emgqS6sX8lgwPBeWhZvJ5ZPVFe2r31TmGJ5O4DoyLrstn_jjw9Jo05NoIJrWb3Xxf0xp-IyEva5rdBg3WIcnN12CxMVz5AMX-e4EzO5vqr2hA" width="150" />
  <img src="https://lh4.googleusercontent.com/s1cJIxlmr4HrcSXatI5qaYuPTAx-kqxCHjcQ4lD06cL1yXIF0Ob-qEysJY8FdQM3u6fd1YVRoFEdEz50D2dTRv_-N94WHUp67DHXBHP3gCKZBzyIA_eoq1Uge_8_FO1lptd5wbCTe2g24hF8bWmugXTlBH-NoVPoD2d0suZdsAsLCcIsKQoFjx1VeLlk" width="150" />
  <img src="https://lh4.googleusercontent.com/BEhaB1qBqsniy8vsqA822QH2C-xXyc6zhgZXiO43zOjtnJ-rcymyQGjfeyzzgmR2QIKU_0l8R4j8ovuVIbDPD4rxfVh-zC3gmOSLdIGlRTDINCtBDo4yOLKyGKB5638P-8EcjUhyeOKJGMRFb3aw-craeyou-cgDG42Mkad5SOATturNqfnjPvbBWGo-" width="150" /> 
</p>




  

##### Application Screenshots
<p align="center">
  <img src="https://lh4.googleusercontent.com/W9UzuWr81tZ46EPy_GY6d9ax4la_5QmXyYrfN6U_-oU_V0Lo-DYKG0PHm0en5p0VHOsZZPKrTZziObg5owWxpBi1UMTbpi7afY2wjEwtJcmcd_dfegkk4sP0EmGXR1mAaVxMsg-KYmFYgeaslmrDrujVjButfARTmDpoj_864itS9Me5DOm3XyWq2Xe3" width="150" />
  <img src="https://lh6.googleusercontent.com/A6aPgbrr_E9GZDMAJqpyn5TLvLuWB-G2mgQFkOKKklZxs2iA7_mG_UmqAgO6kgvUpamhjST3M3Y_z9zpouxoTbmS5rjiUWF-6AgEWX9itdkmdtgSBNbJgo8c4DgiuB6GtbUiIt-KEUWyksVztfB8DV3d1lAte0HTF5YchLjIVXZJz7ZXFEdm-YB8drAb" width="150" />
  <img src="https://lh4.googleusercontent.com/pySecYY0_qIGF_iyRJc-Zh3U3TT8VrwQwAYBLtBKMsPGvoAutcNz4bvkZ7Y8oy5o8Bmr0HKRyNDx1t3vXQmDn0aTPo6BVDhxvw7AIAt94ncF1Tdhuzqg_t9We5HgPI6iDDOUuo4dHtPQ-JOvfIC2HMOaOnhyJg5vWiJJzd7LiKTC3IDr8z4HUNDd2Nq9" width="150" />
  <img src="https://lh3.googleusercontent.com/TDmC-RzwUbkmz5nCYWPrtOdezM9ID7n6FGSVU3Ei0V0zmATSEnhSy0bAaDrU0NENkDUruWNHk7UdJlguiJWAJyiFUa4Rt3MFrevcN2iBCfywv3WrRIvnQ3BcrWvr1P5KqQQ_xlGKV31eWzTwxmnUmU5kbAkfGohHOHxgNxuTEvQzCtwwgmzvUgKcKZpi" width="150" /> 
</p>

When you login, you go to the homepage where the content is. You can open external links and save content. The Saved page is like the Home page except it has only saved content. The profile shows the user’s information and two buttons. The edit preferences button leads you to a list where you can star and unstar different topics. The logout button takes you back to the welcome page.

  

#### Home Page, Profile Page, and Edit Interests Page
##### Figma Wireframes Part 2
<p align="center">
  <img src="https://lh3.googleusercontent.com/zXs5pNs4SS9fy5RUzSirhkGli6_E05oF8EyKqvEH-4wJyvaUyTQEntLeIo5lcb4I65_N9WN0P8Mqseq2ret1TB80Nn9g9X7JDdVhzgszQDXBDgtNg4MzdC3DKxssq8rigzmX6-yPYrbiYGAX2aPhnpPMD1ITYmxyufPZ1gYYPddd7JRi6R4tsLO0Cqm0" width="150" />
  <img src="https://lh6.googleusercontent.com/F06fHrh28w1QkFTSggbVS7MFoabe86Q1zbK3Tltsu6LNdnVeNlTiOrslay-zeL3BvHe0Kg8NDhBIeFu5ZpJ_WjYLR-EdJDGtPHr36WXJ0Re9ELzgXQSzOcZqLWh2hQgjb_vEzU10iQfNWMvtcHha7b682PvfflmHLN_ZQeFoyZK0ze9Ll0zv-PM2vpFT" width="150" />
  <img src="https://lh5.googleusercontent.com/JFZPREHOJCTMruu6m9UMNhH9KkQkgvksjC2q1KbiEkvUuD9xL1N1IrV8DezHEOlqRpkI3SoZrLT-RoRald-9JEaxLIVizt7KeO5ZYTkVwyI9iYD7Ur-kj9xlMK-Nj51U_8u4Cp2Sldd6M3y_ojc9Q_yR6t7BuCPjvGsdapG1-c-583xQsjZ2AmKcH4i4" width="150" />
</p>



##### Application Screenshots
<p align="center">
  <img src="https://lh5.googleusercontent.com/qrqb32Zj85CSZ8sVPtrmym5g7NxUq7UJDzRTK9hgllUFSHTTX-hayk5RSLzHIRBAM_6XWOFO9kL0wGvgAU8wPk0q16VL6BB71JfcSaxd5NGeuiEOOrX3yViFbBXkpzy_jueSFVlsSLfsBL1sLMkOQoqIAAamqp8_-o0LWSTd4Ir_FVkRp5g1i2UCN5rQ" width="150" />
  <img src="https://lh3.googleusercontent.com/Lu37PIjD6wm15AmPzCEf3APIv4_trLtXzyMSQUm9ctn7SdypH6kS_9z4H3-uRqPkoqEzAxh2cpwupgefAf74Sr-9fYBTab84twQ3bvUDCFN_R-8qjMXCUkXs9w_Eydwyf5Xyr-tyaVAuUJWyf77tvefhnWbWPqnUNBetjrDHHisUSaZk4ncQpzYB5tMT" width="150" />
  <img src="https://lh3.googleusercontent.com/UoetpmHBenU0mT6yVzIdfrAsMiWAZfjq7Y5mQknelsQ2ZQg74lMxHYO48oX6BupaNA0XDm-jDSl5_LUXOn3eiymDvG8cFmZ_MYbuggvHAPH2FsV-gHmxCjZsCdppinEmYjHnPVYLhIhhVsbvGuOWxHK77CBcHEaBKAQ3sipkz2_EnuzBU20Kl_8r1uIa" width="150" />
</p>

## System Documentation
### Overview
The system is built on the client-server architecture and the system context model shows our built environment for our app, edYOU.

### System Architecture
  

The architecture we chose is Client-Server architecture since our product enables the user to request content relevant to a specific educational topic. The server utilizes APIs and an algorithm to pull the content for the user, in the order of relevance, and returns it to the client. These actions fit directly to the advantages of a client-server architecture pattern, which focuses on providing an environment for clients to make requests from the server.

  

![](https://lh6.googleusercontent.com/QJexzf9h5nXisT7JfOliDK_WJeQGV8sqOOOyUV7OPqK-PvuvFt2Z5Ww8myYsKa9ZDLmRrUNWMIOxlArx-I_SeclKRd0fztxdwTZd1SR_R2JYoLzNtAnL6c_1oatQK3w4_tA-rNHAUr0yFSFa1BGYdTYz2LyQn9es8XhWcrHqomWwlgPGvDU-yEqXtacQ) 

### System Context Model

The system uses NodeJS as a runtime environment for back-end servers while GraphQL is the language to create mutations and queries, and Flutter is our framework for front-end to build the user interface of our app. MongoDB is a database for storing user data and contents. We will also use APIs such as YouTube API, and Google API for the contents on homepage.

 ![](https://lh6.googleusercontent.com/CGSwycttH26fuQh096H7rJFS_3_im4VAx_IoKlVydEuTeUIYVcDcnd2trsdejobRIIXUQJSClYl-WG7NGV3gwcJd1O8Be23FJrx3gqd_OQ8Sz6H6PuFa8mNVEgKyI5OWLPjdCAMpw53-rNltmrO7GSUkjTa3i_ewgUR134TnGekSS2j-pTbW4ozPLqbr)

# Developer Documentation

How to run the edYou app:

1.  Have git, npm, nodejs, and Flutter installed in your computer. See [https://docs.flutter.dev/get-started/install](https://docs.flutter.dev/get-started/install) for details on how to set up Flutter.
    
2.  In the terminal, run  git clone [https://github.com/MarianaTorresTorres/IntroToSWEProject.git](https://github.com/MarianaTorresTorres/IntroToSWEProject.git)
    
3.  Run the server:
    1.  Go into the server directory
    2.  Add a .env file (see at the bottom of these instructions for the content of that file) in that same directory
    3.  Run  `npm install` to get node_modules
    4.  Run `node index` (or `nodemon` if you have nodemon installed)
    5.  To check that it works, go to localhost:5000 and the GraphQL Playground (where you can run queries and mutations) should appear.
  
4.  Run the client:
	1.  In another terminal (keep the server running), go into the client directory
	2.  Run `flutter pub get` to install dependencies
	3.  From step #1, you should have an emulator setup (through Android Studio for Windows or xcode for Mac). Run the emulator. The app should not show up yet.
	4.  Open the repo on Virtual Studio Code (we recommend you have the Flutter and Dart plugins for VSCode). At the bottom, you should see something like this. If it says something other than “Phone,” click on that and select your emulator in the dropdown that shows up in the top center of the screen.
    ![](https://lh4.googleusercontent.com/nxGOF-yaurg9MRSCrCdZwF6pfwFte_8Lr1DvarniT2o4Q3wcnqnTi9Ak1No0S1ZRImFu6YAHTtpR2E6nCiZc6lq_D0cnjfkaZAwKcZuD08HNQgbepBdDqiBN1deHh0k3AZBs7qOOl88-Qk8HZy_ABcLwnnDT81GPxJ5MeEMlx_NYYt0r0jgvIlrXSpAj)
	5.  Go to lib/main.dart and run with debugging. If everything was done correctly, our edYou app should appear in the emulator.

The code inside the.env file:

URI=mongodb+srv://admin:wCFP6KfHR2pawjK@cluster0.3szop.mongodb.net/DB?retryWrites=true&w=majority

SECRET=daymwearethebestteam

SENDGRID_API_KEY=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

PORT=5000

CLIENT_ORIGIN=http://localhost:3000

YOUTUBE_API_KEY=AIzaSyA1zwXRtu42csU1eCfxQ_BMFlmylepYEfA

NEWS_API_KEY=665631c3b57f47b79b0bda13de78cabe

## Sprint Presentations

### Sprint 0 Presentation
[Sprint 0 Presentation](https://www.youtube.com/embed/SXnvakehMOw)


### Sprint 1 Presentation
[Sprint 1 Presentation](https://www.youtube.com/embed/euD2k7JsRis)

### Sprint 2 Presentation and Demo
[Sprint 2 Presentation](https://www.youtube.com/embed/07hM9DYSllw)

## Team
Antonio Villarreal - https://www.linkedin.com/in/antoniovillarreal2024/  
Yair Temkin - https://www.linkedin.com/in/yair-temkin/ 
Mariana Torres Torres - https://www.linkedin.com/in/mariana-torres-torres/
Diane Chae - https://www.linkedin.com/in/seunghui-chae-7a12411aa/
