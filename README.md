# Welcome to AXIS's SaaS Publishing Platform: An End to End Solution 
## What is Axis? (Intro)
## What are NFTs? (Intro)
## What is the obstacle we are learning from? (Philosopy)

<br>
<hr/>
<br/>

<center><h2>Purpose</h2></center>

### ***The purpose*** of this application is to provide an end-to-end solution for **generating and visualizing our leads data**. A solution that is made for a new company to design web pages and web apps, alter their website's content to act on insights, and track new metrics, all quickly. We are providing everything a prototype-stage company needs for any web based product.

<br>
<hr/>
<br/>

<center><h2>Objective</h2></center>

### ***The primary objective*** is to create an **analytical dashboard** that visualizes data of a Software as a Service's (SaaS) Customer Onboarding process. We will be using Cube.js, React, Postgres, AWS Cognito (Authentication service), and AWS AppSync (GraphQL service).

<br>
<details><summary>What is a analytical dashboard? (Click here)</summary>

<h2>
An analytical dashboard is a type of dashboard that <b>contains a vast amount of data created and used by analyst to provide support to executives.
</b></h2>

[Source](https://databox.com/what-is-a-dashboard)
</details>

<br>
<details><summary>Why this technology stack? (Click here)</summary>

<h2>
<ol>
<li> 
A primary concern for developing this solution is obtaining large-scale production use with a small team of developers. Our reason for going with a serverless solution is to allow Amazon Web Services (AWS) to do all the back-breaking work of managing and interfacing with multiple data sources. 

#### [***Cube.js***, a headless infrastructure for data access and metrics,](https://cube.dev/docs/introduction) promises to have "key components for production-ready analytics" and can be accomplished with a serverless solution.
</li>

<li>
As we explained earlier, our preference for going serverless is for the ability of production at scale. Our chosen technology stack has a shorter development time window by being able to "hideaway" details of SQL queries and many database concerns. We can work at scale and quickly, thanks to GraphQL, by having one HTTP endpoint to connect our clients to our backend services. A serverless and GraphQL combo will provide an reliable, fast, auto-scalable, and secure infrastructure.
</li>

<li>
Finally, the use of React for our dashboard's frontend UI for its fast development time when combined with great libraries like MaterialUI and so many other great libraries and frameworks built for React. React has the ecosystem a prototyping stage company like ourselves needs for rapid development.
</li>
<ol>
</h2>

</details>
<br>

### ***The secondary objective*** is to create a customer-facing **web platform** for our end-to-end solution to generate the data we want to visualize. We will be using Next.js for our frontend framework, TailwindCSS for styling, Strapi for headless Content Management System (CMS), and Google's GCP/Firebase for our backend needs.

<br>
<details><summary>Why this technology stack? (Click here)</summary>
<h2>
<ol>
<li> 
As stated earlier, the desire to put this platform into production as quickly, painlessly, and with all the required features for an above standard production platform led to our choice of using Next.js for our customer-facing web platform. We know that Next.js provides better SEO using pre-rendering than traditional react. SEO is critical for our web platform, but so is our need to spend less time doing page routing and image optimization configurations. Next.js can also be used to create an API if we need it, to create a development version backend, interact with our Firebase backend, or making calls directly to our dashboard's backend if we decide to.
</li>
<li> 
Using a seperate backend for our customer-facing web platform may seem like extra work than just our continued use of our React dashboard's backend. Especially, considering that they are different services made to do the same thing: provide a serverless backend solution. However, the basis behind our choice is that we know the following: 
1) We want our backend to be serverless. 
2) We want to utilize as many built in bells and whistles provided by serverless backend solutions.
3) We want to learn what our best options may be, even if it will require a bit more learning time at first.

The following technical features support our decision for Google's Firebase:
1) To spend less time configuring databases, authentication, and storage services.
2) To have a full featured backend to host our Next.js app, Google's Firestore Functions gives us that ability.
3) To apply efforts in better serving a wide ranging demographic across the world by using features such as A/B testing, localization, and CDNs.

Google's Firebase provides all of that and more such as Machine Learning and Performance Analytics, nicely packaged and documented. We can provide a robust platform while being minimalist at the same time.
</li>
</ol>
</h2>
</details>