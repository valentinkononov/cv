<link rel="stylesheet" type="text/css" media="all" href="assets/styles.css" />

# Valentin Kononov
### Full-Stack Developer, Speaker, Trainer

[Link to this CV online](https://valentinkononov.github.io/cv/)

## Summary

Senior Full-Stack Software Engineer and Architect, Team Lead, TypeScript / Strong Typed Languages Enthusiast.
Experienced with Typescript/Javascript, NodeJS / NestJS, C# / Java, GOlang, Data Design with SQL and NonSQL, Cloud Infrastructure setup.
But not limited to and open to new skills, languages, and opportunities! Enjoy attending conferences as a Speaker with technology talks.

Flexible and self-motivated, I enjoy technical challenges, and architecture work.
Experienced in team setup and management, process improvement, project breakdown, and estimation.

I love comprehensive tasks, learning new technologies, and solving tech problems, making people's life better with technology solutions.

### Facts

- Architecture design of complex frontend and backend systems, architecture review, analysis, and improvement
- Skilled in .NET / .NET Core development, experienced with EntityFramework, WEB API, Parallel Programming in .NET area
- TypeScript Expert and Enthusiast, skilled in UI and Backend development using TypeScript with TypeOrm, NestJS, and other modern techniques including design of non-relational data models
- Skilled in Angular and React, development, prepared several conference talks on these matters, completed a range of Angular and React projects
- Database experience with SQL and noSQL databases. Have special love to Postgresql
- Hands-on experience building data storages with BiqQuery, data pipelines in GCP stack
- Experience with Kafka and PubSub topics, Cloud Functions, microservices
- Java / Scala / Kotlin experience
- Worked with different cloud infrastructures such as AWS (with cloudformation), GCP (with Terraform) and Azure
- Experience and desire to do conference talks and articles on technical aspects of software development
- English language as a primary working language
- Can effectively work remotely (actually doing that since 2020)

<!-- ![Photo Valentin Kononov 2019](Valentin_2019.png) -->

## Contacts

Email: valentin.kononov@gmail.com

Twitter / Telegram: @ValentinKononov

LinkendIn: https://www.linkedin.com/in/valentin-kononov

Github: https://github.com/valentinkononov

Facebook: https://www.facebook.com/pinckrow

Medium: https://medium.com/@valentinkononov

Habr: https://habr.com/ru/users/pinckrow/posts

Own site: https://kononov.space/

## Story

I've been working in software development since 2008. Initially from C++ and .NET background, I grew into management of projects inside EPAM Systems company, was involved into company processes at some level, working with people, building growth and career plans. 
Later I pivoted into more technical roles, code writing, architecture and technical leadership. Gained experience with number of modern technologies and stacks.

Now I dedicate more time to architecture design and coding, but keep also working on team leadership. I'm experienced in web development with Typescript and Javascript, Angular and React.
Backend development with .NET, .NET Core, NodeJS, NestJS, GOlang and Python, Java with different infrastructure providers (AWS, GCP, Azure). Several projects were built based on microservices architecture, with data consuming from stores like Kafka or BigQuery.
Have experience in mobile cross-platform development with React Native.
Special place in my dev heart is dedicated to C# and Typescript, as strong typed languages.

Lately I started to dedicate more attention to technical proposals, systems analysis and architecture review.

Apart from the code writing, I usually lead a team of developers and handle customer communication for projects, provide planning and staffing allocation, project review and estimation.
Write articles and release notes, support technical backlog.

Starting from 2017 I'm into conferences speaking about TypeScript, JavaScript, NestJS, .NET and Angular area. I had speaking and training experience before, but now I provide deeply prepared technical talks, submit and participate in international conferences. Was part of Minsk GDG Org community in 2020-2021, participate in Meetup organizations, conference program committee member and writer and periodical community blog posts.

Published NPM Typescript library for Runtime Types Verification [ts-stronger-types](https://www.npmjs.com/package/ts-stronger-types) - this is a thing for myself, as strong types enthusiast.

## Conferences and MeetUps

#### Completed

Full List of conferences I attended as speaker is in my [blog](https://www.kononov.space/conferences-and-meetups/), but some of the most exciting are here:

- [jsPoland 2020](https://js-poland.pl/speaker/valentin-kononov/) Runtime Type Safety in Typescript for jsPoland online conference.
- [xTechnology meetup](https://xtechnology.dev/), talk about React Query Hooks (24-12-2022) [video](https://www.youtube.com/watch?v=rLasA328dEM)
- Angular Bad Practices for ngHeidelberg - online meetup (29-07-2020) - [video](https://www.youtube.com/watch?v=9LPxrfssbiE)
- [ngVikings](https://ngvikings.org) conference, talk about Angular Bad Practices, [video recording](https://www.youtube.com/watch?v=QU739zZvkhE)

### Magazine Articles about me
- [Interview with me by ngVikings member - Marta Wisniewska](https://www.flipsnack.com/MartaWPL/behind-the-code-ngvikings.html)

### Projects and Case Studies

Unity - **Advertising Suggestions Project** -
October 2021 - current time, Helsinki

Full stack project to implement data pipelines, api and React components and pages with Javascript as part of the huge customer facing dashboard.
Aim of the project is to help clients select better settings for the advertising campaigns and gain more installs or views.

Backend part consists from several micro-services written in GOlang, which queries data from BigQuery and provide it to the dashboard or to the API clients.
Data pipelines are implemented using Cloud Functions and Scheduled Queries.

Data infrastructure is pretty diverse, consisted of GCP Big Query Tables, Kafka topics and other external sources as Druid.

All infrastructure is managed by terraform configuration, so that it can be consistent and trackable. Team is responsible to manage own infrastructure.

I have Special feelings to the Dataflow project, which was quite new to the company stack. I have implemented it using Python (usually GCP dataflows are written in Java).

My role on the project is to develop components, create TDD (technical documents with architecture planning), work with the team, mentor some team members, participate in planning sessions, testing sessions and wide communications with other teams.

----

**Stack**: JS / TS, React, React Query Hooks, GO, GCP Infrastructure, GCP Data flow in Python, Terraform to manage GCP settings and number of other tools, BiqQuery, Kafka, CloudFunctions

Mapbox - **Annotation Tool** -
November 2019 - September 2021, Minsk

Worked on image annotation tool from scratch. The tool is used by company workers, and it's result is a source for neural network education cycles in Mapbox.
The tool looks simple from a first glance, but it supports range of use cases in UI, project metrics tracking and a lot of integrations with other backends.
Primary goal was to improve general process of annotation, make it fast and reliable from user perspective.

The project started as support of existing code in JS and GO, but later we come up with new better architecture approach and implemented a brand new application based on React frontend and NodeJS (NestJS) backend.
Solution has big test coverage (85%), relational data model based on Postgresql database, 100% request validation on the backend side (with custom decorators and class-validator decorators) in NestJS backend.
Deployment happens to AWS infrastructure using cloudformation configuration.

Additionally, I've implemented special java plugin for JOSM to support custom type of map annotation with splines

**Stack**: JS / TS, React, Redux, Go, NestJS, everything happens in AWS infrastructure including S3 file storage, Java

----

Akveo - **Nebular and Ngx-Admin Training** - Summer 2019, Minsk.

I did several training sessions about our company open source products (Nebular and NGX-Admin) and Angular in general.

----

Akveo - **Backend Bundles** -
November 2018 - October 2019, Minsk.

I've created architecture approach and implemented a significant part of a code for this project. The idea is to create development template for both frontend and backend, integrated together via REST services.
Angular frontend and bunch of different backends - .NET, .NET Core, Java, Node.JS, Nest.JS and some others. Product is commercial.
I was also involved into clients interaction, planning and continuous integration using SH scripts to prepare, build and test code before putting to the store.

The main project challenge is to make sure the single UI with several variants works with the range of backends, the second biggest challenge is to make sure each variant of Angular UI is built without errors automatically.

**Stack**: Angular, Nebular, Ngx-Admin, .NET Web API, .NET Core Web API, Entity Framework, Node.JS, Nest.JS, Mongoose, MongoDB, SQl Server, SH Scripts, Git, Java

---

Akveo - **TV Advertisement Management App** - September 2018 - November 2019, Minsk.

Angular CRUD application to organize the process of adding and editing advertisements for TV company including schedule management. Our company did initial architecture work to provide base Angular Application backbone, services and state management.

**Stack**: Angular, MobX, Git

---

Akveo - **Mobile app for electrical service workers in Canada** - May 2018 - January 2019, Minsk.

I worked as technical lead, architect and mobile developer for this project. We created cross-platform mobile app using React Native framework for the mobile part and .NET Web API with Dapper as mini ORM for the backend part.
Application was designed as offline first to support full offline mode and synchronization. Now it is officially in production and several companies in Canada uses it.

The main challenge was in creation stable data synchronization process. We used SQL Server Change Tracking for this from the backend perspective.
On the mobile side we needed to securely store data per user, we choose to use Realm database for it. It has own challenges in terms of performance.

**Stack**: React Native, Realm database, MobX, .NET Web API, SQl Server, Dapper, Git

---

Akveo - **Legal Document Storage and Analytics** - November 2017 - October 2018, Minsk.

CRUD application with Angular frontend and .NET Web API with Entity Framework on a backend side. I worked as Technical Lead, Architect and full-stack developer on this project. Application was designed to help legal officers to fill legal data and see visual analytics. UX was complicated because of necessety to add big amount of textual information to the UI.

Another challenge was related to Angular performance due to big amount of different components in the UI.

**Stack**: Angular, MobX, .NET Web API, SQL Server, Autofac, Rotativa, Git

---

EPAM - **Oil and Gas Account** - October 2013, Russia, Saratov - November 2017, Belarus, Minsk.

Group of Projects for one of the largest Oil&Gas company, implementation of the software for the internal business process of the customer. Sample of the business area is Risk Assessment or well certification. Business value of projects is to setup, simplify and speed up processes for Customer, which will lead for finance benefits. Total amount of people under my supervision is 25 – 30. During this period I was mostly involved into coordination, staffing, communications, security questions, but also participated in serious bug fixes, estimation and performance improvements.

This project is one of the most important and interesting in my career. I started it as code quality specialist from EPAM. Then we managed to increase team and take bigger tasks. Eventually the project was re-written and used across all customer offices across the globe in 23 different time zones.

Desktop / Web application with offline mode and data synchronization. Business idea - unification of processes for Risk Assessment and others in different business units. Initially it was win forms application, later we created WPF framework to host both WPF modules and web modules, some of which were offline ready. End users setup the app just by downloading the initial small desktop application.

Challenges: auto-update feature, performance for different locations, security, offline data storage, performance for Entity Framework queries, making data schema scalable. At the later stages of the project it was partially turned into CMS with ability to create custom data types.

In 2016 I relocated to Minsk, Belarus, working in this project.

**Stack**: AngularJS, .NET Web API, WPF, Entity Framework, SQL Server

---

EPAM - **Business Intelligence Support in Media** - February 2016 - August 2016, Russia, Saratov

I worked in group of 10 projects in media and advertising domain. I was responsible for projects staffing, support processes setup and delivery in location. Average size of projects is from 2 to 10 ppl. Technically most projects are connected with MS BI technologies and .NET stack. Total people amount under my supervision was about 30.

The biggest challenge here was related to the staffing process - we setup customer interview preparation process to make sure staffing is successful.

---

EPAM - **Financial Data Services** - February 2010 - September 2013, Russia, Saratov

I worked as backend developer and then Team Lead in the project with
implementation of backend services and middle layer between UI client and data services. Project goal was to implement data loading from different data sources, data transformation so that clients can consume data in the same way, retry process for loading and caching to ensure stability of this service bus (data sources was very unstable).

Another part of a project was to implement Data facades - middle layer between UI client code and data service. This library provided easy to use mechanism to access data, metadata for UI, mapping, filtering and caching.

**Stack**: .NET, WCF, XML, SQL

---

Postgraduate Education and work in Saratov State University www.sgu.ru - February 2010 - September 2013, Russia, Saratov

In parallel with EPAM work, I worked in Saratov State Univercity as tutor and researched mathematical modelling and calculations of stabilized missiles flight as my postgraduate work. I have implementated range of mathematical algorythims in C++ to calculate mathematical models and find the best parameters. During that period I had published several science articles on this topic.

---

EPAM - **Bank Web System** - July 2008 - January 2010, Russia, Saratov

I worked as UI and then backend developer in Web project for russian Bank. Project was to implement banking system for client internal usage, credits process and other internal processes. I worked closely in collaboration with Business Analysts and QA team, as a result we managed to increase quality and improve timeline in the unit I was involved in.

**Stack**: .NET, ASP.NET, jQuery, WCF, SQL

---

MOSSAR Techno - **Factory IoT** - September 2007 - February 2008, Russia, Saratov

Company worked to create automated system, which can get data from remote electric counters, store it in data base and proved easy access. System aimed to be setup in different factories, where electric counters should be distributed across big facility.

I worked as C++ developer for backend tasks.

---

### Education

Graduation Year: 2010

**Name of the Education Establishment**: N.G. Chernyshevsky Saratov State University

**Faculty/College**: Computer Science and Information Technologies

### Articles

My articles can be found in my [blog](https://www.kononov.space/tag/article/) and [habr](https://habr.com/ru/users/pinckrow/posts/), but some of them I'd like to mention here:

- [Runtime Type Safety in Typescript](https://www.kononov.space/runtime-type-safety-in-typescript/)
- [Typescript Decorators](https://kononov-space.fly.dev/ts_decorators/)
- [CQRS and Event Sourcing in backend systems](https://kononov-space.fly.dev/cqrs-and-event-sourcing-in-backend-systems/)
- [Application State Management with MobX in Mobile](https://kononov-space.fly.dev/state-management-how-we-do-it-with-mobx-in-mobile-app/)


### Personal Facts

I initially from Russia, town [Syzran](https://www.google.com/maps/place/Сызрань,+Самарская+обл.,+Россия/@53.098456,48.315132,11z/data=!3m1!4b1!4m5!3m4!1s0x416852c369318ecd:0x82ac8e575891c738!8m2!3d53.1504504!4d48.397896),
close to Samara city. I moved to another bigger city in Russia, [Saratov](https://www.google.com/maps/place/%D0%A1%D0%B0%D1%80%D0%B0%D1%82%D0%BE%D0%B2,+%D0%A1%D0%B0%D1%80%D0%B0%D1%82%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F+%D0%BE%D0%B1%D0%BB.,+%D0%A0%D0%BE%D1%81%D1%81%D0%B8%D1%8F/@51.5343639,45.7292701,10z/data=!3m1!4b1!4m5!3m4!1s0x4114c709059bbc41:0x1c685156439035f6!8m2!3d51.5923654!4d45.9608032),
for education and then during the university I joined EPAM Systems Saratov office and software developer.
During several years in parallel with software development I was working in university as tutor.

As part of my EPAM activities I was highly involved into people management, motivation, attrition management and other related activities.

In 2016 I have relocated to [Minsk](https://www.google.com/maps/place/%D0%9C%D0%B8%D0%BD%D1%81%D0%BA/@53.8847604,27.4529416,11z/data=!3m1!4b1!4m5!3m4!1s0x46dbcfd35b1e6ad3:0xb61b853ddb570d9!8m2!3d53.9006011!4d27.558972) city,
Belarus, with my wife and two daughters.

I have lovely family - wife, two daughters, dog and cat. My wife is psychologist (therapist) and HR. We try to do joint projects together when it's possible.

I love travelling with my family, especially when it's possible to stay in some place for month or more.
It gives me the opportunity to know the country and people better, understand culture and manners.
That's why it's very cool for me when I can travel for work and stay with particular business in some place for quite a long time.
