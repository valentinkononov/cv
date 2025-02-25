<link rel="stylesheet" type="text/css" media="all" href="assets/styles.css" />

# Valentin Kononov
### Full-Stack Developer, Speaker, Trainer

[Link to this CV online](https://valentinkononov.github.io/cv/)

## Summary

Senior Backend Software Engineer and Architect with 17 years of experience. 
Enthusiast of Strong Typed Languages like GOlang, Typescript, and C#.
In every project, I design data schema and infrastructure as a code, set up CI and CD to streamline processes, and focus on actual business goals.
I'm using the validated output of AI assistants like Claude as tooling daily.
Open for new knowledge, skills, and opportunities! I enjoy attending conferences as a speaker and giving technology talks.
Flexible and self-motivated, I enjoy technical challenges and engineering problems, architecture, and infrastructure work. 
Prefer to move fast and take pragmatic weighted decisions, based on real necessity. 
Proud husband and father of two daughters! Junior yacht skipper!
Live in Portugal and benefit from working in the UTC timezone.


### Facts

- Architecture design of complex backend systems, architecture review, analysis, and improvement
- Skilled in GOlang backends, web APIs, and parallel computation
- TypeScript Expert and Enthusiast, skilled in UI and Backend development using TypeScript with TypeOrm, NestJS, and other modern techniques including the design of relational data models
- ReactJS as a full stack, prepared several conference talks on state management matters, completed a range of Angular and React projects
- Database experience with SQL and NoSQL databases. Have special love to Postgresql
- Practical experience with testing (and little stress testing) of APIs. Attended https://testjssummit.com/ once as a speaker about API testing with NestJS
- Hands-on experience building data storages with BiqQuery, data pipelines in GCP stack / AWS stack
- Experience with Kafka and PubSub topics, Cloud Functions, microservices
- Worked with different cloud infrastructures such as AWS (with CloudFormation), GCP (with Terraform), and Azure
- Designed and implemented AWS infrastructure from scratch for a mid-size project with audio data processing
- Experience and desire to do conference talks and articles on technical aspects of software development
- English as a primary working language
- Effectively work remotely (since 2020)

<!-- ![Photo Valentin Kononov 2024](Valentin_2024.jpg) -->

## Contacts

Email: valentin.kononov@gmail.com

Twitter / Telegram: @ValentinKononov

LinkendIn: https://www.linkedin.com/in/valentin-kononov

Github: https://github.com/valentinkononov

Facebook: https://www.facebook.com/pinckrow

Musical Stories Blog: https://asynctunes.substack.com/

## Story

I've been working in software development since 2008. Initially from a C++ and .NET background, I grew into management of projects inside EPAM Systems company, was involved in company processes at some level, working with people, building growth and career plans. 
Later I pivoted back into a technical role and architecture. Gained experience with several modern technologies and stacks. After working in a big corporation, I switched several places working in startups (Akveo, Mapbox), bigger companies (Unity), and startup again (Stems for http://lowkeyremix.com/). I use the benefits of both worlds - solid processes of enterprise businesses with a will for change and the fast pace of startups. 

I work with backend code, architecture, and infrastructure, but keep an eye on team leadership. I'm experienced in web development with Typescript and Javascript, Angular, and React. Backend development with GOlang, Typescript, NodeJS, NestJS, .NET, .NET Core, and Python with different infrastructure providers (AWS, GCP, Azure). Several projects were built based on microservices architecture, with data consumption from stores like Kafka or BigQuery. Have experience in mobile cross-platform development with React Native.

My daily work is mostly related to GOlang, PostgreSQL, AWS infrastructure, and Python scripts. 

When it comes to the selection of technology or solutions to engineering problems, I am using a pragmatic approach - trying to find a minimal change that leads to maximum benefit in the long term. I'm not chasing technology and tools just because it's new, but only when it serves a purpose.

Apart from code writing, I lead a team of developers and handle customer communication for projects, provide planning and staffing allocation, project review, and estimation. Write articles and release notes, support technical backlog.

Starting from 2017 I'm into conferences speaking about TypeScript, JavaScript, NestJS, .NET, and Angular area. I provided deeply prepared technical talks at international conferences from 2017 to 2022. 

Published NPM Typescript library for Runtime Types Verification [ts-stronger-types](https://www.npmjs.com/package/ts-stronger-types) - this is a thing for myself, as strong types enthusiast.


## Conferences and MeetUps

#### Completed

Some of the most exciting are here:

- [jsPoland 2020](https://js-poland.pl/speaker/valentin-kononov/) Runtime Type Safety in Typescript for jsPoland online conference.
- [xTechnology meetup](https://xtechnology.dev/), talk about React Query Hooks (24-12-2022) [video](https://www.youtube.com/watch?v=rLasA328dEM)
- Angular Bad Practices for ngHeidelberg - online meetup (29-07-2020) - [video](https://www.youtube.com/watch?v=9LPxrfssbiE)
- [ngVikings](https://ngvikings.org) conference, talk about Angular Bad Practices, [video recording](https://www.youtube.com/watch?v=QU739zZvkhE)

### Magazine Articles about me
- [Interview with me by ngVikings member - Marta Wisniewska](https://www.flipsnack.com/MartaWPL/behind-the-code-ngvikings.html)

### Projects and Case Studies

Stems - **lowkey remixing app** -
March 2023 - current time, Portugal

Started as part time consultant to support backend and improve infrastructure, I transformed this role into a full time job to build complex backend in GOlang, create and maintain audio data processing using AWS infrastructure and GCP Cuda environment. 
My primary role is backend code implementation and technical management of the project. 

The project goal is to create an app for making music remixes, even though if you don't have related musical experience. Apart from the normal data storage and CRUD operations with the database, Backend provides audio processing like split mix track from the uploaded video into 4 stems for separate handling, gathering audio analysis info like beats per minute etc, working with ffmpeg and other tooling to prepare video and audio and other related processing. The main challenge is to make most of the processing in near to real-time mode. 

The infrastructure of the project is mostly implemented in AWS as ECS cluster with RDS cluster based on Postgresql Engine, used infrastructure as a code approach and full-scale CI/CD. Deployment happens using GitHub actions including database migration scripts. AWS contains most of the project including push notifications with delivery checks, file caching, background data processing, and so on.

Google infrastructure is used to utilize Cuda environment and GPU computations for various analysis and AI tasks.

Apart from the performance, the bigger challenge of this project is using of the new tools, testing and integrating various open-source tools and libraries. My personal goal here is to make the decision for the new tooling weighted and serving a purpose so that the team spends minimal time on tooling change and maximum time on business goals. 

**Stack**: React Native with Typescript, GOlang, GQL, PostgreSQL, AWS and GCP, S3, SNS, Cloudformation for AWS infrastructure, Kubernetis cluster in GCP, ffmpeg, Python for running ffmpeg commands and background processing ...

Unity - **Advertising Suggestions Project** -
October 2021 - September 2024, Helsinki, Finland

Full stack project to implement data pipelines, API and React components with Javascript as part of the huge customer facing dashboard.
Aim of the project is to help clients select better settings for the advertising campaigns and gain more installs or views.

Backend part consists from several micro-services written in GOlang, which fetchs data from BigQuery and provide it to the dashboard or to the API clients.
Data pipelines are implemented using Cloud Functions and Scheduled Queries.

Data infrastructure is pretty diverse, consisted of GCP Big Query Tables, Kafka topics and other external sources as Druid.

All infrastructure is managed by terraform configuration, so that it can be consistent and trackable. Team is responsible to manage own infrastructure.

My role on the project was to develop components, create TDD (technical documents with architecture planning), work with the team, mentor some team members, participate in planning sessions, testing sessions and wide communications with other teams.

Apart from that, I participated in Reporting project, which goal was to migrate reporting tool to the new design and implement gathering data from new APIs.

The biggest achievement I gained through 3 years of working at Unity is promoting Typescript (instead of Javascript) as a primary language for the big react js repository, which was used by 400 developers on daily basis. I worked on this project alongside with my main work almost a year.

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

My articles can be found in my [blog](https://kononov-space.fly.dev/tag/article/) and [habr](https://habr.com/ru/users/pinckrow/posts/), but some of them I'd like to mention here:

- [Runtime Type Safety in Typescript](https://kononov-space.fly.dev/runtime-type-safety-in-typescript/)
- [Typescript Decorators](https://kononov-space.fly.dev/ts_decorators/)
- [CQRS and Event Sourcing in backend systems](https://kononov-space.fly.dev/cqrs-and-event-sourcing-in-backend-systems/)
- [Application State Management with MobX in Mobile](https://kononov-space.fly.dev/state-management-how-we-do-it-with-mobx-in-mobile-app/)


### Personal Facts

I initially from Russia, town [Syzran](https://www.google.com/maps/place/Сызрань,+Самарская+обл.,+Россия/@53.098456,48.315132,11z/data=!3m1!4b1!4m5!3m4!1s0x416852c369318ecd:0x82ac8e575891c738!8m2!3d53.1504504!4d48.397896),
close to Samara city. I moved to another bigger city in Russia, [Saratov](https://www.google.com/maps/place/%D0%A1%D0%B0%D1%80%D0%B0%D1%82%D0%BE%D0%B2,+%D0%A1%D0%B0%D1%80%D0%B0%D1%82%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F+%D0%BE%D0%B1%D0%BB.,+%D0%A0%D0%BE%D1%81%D1%81%D0%B8%D1%8F/@51.5343639,45.7292701,10z/data=!3m1!4b1!4m5!3m4!1s0x4114c709059bbc41:0x1c685156439035f6!8m2!3d51.5923654!4d45.9608032),
for education and then during the university I joined EPAM Systems Saratov office and software developer.
During several years in parallel with software development I was working in university as tutor.

As part of my EPAM activities I was highly involved into people management, motivation, attrition management and other related activities.

In 2016 I have relocated to [Minsk, Belarus](https://www.google.com/maps/place/%D0%9C%D0%B8%D0%BD%D1%81%D0%BA/@53.8847604,27.4529416,11z/data=!3m1!4b1!4m5!3m4!1s0x46dbcfd35b1e6ad3:0xb61b853ddb570d9!8m2!3d53.9006011!4d27.558972), with my wife and two daughters.

In 2021 I move to [Helsinki, Finland](https://www.google.com/maps/place/%D0%A5%D0%B5%D0%BB%D1%8C%D1%81%D0%B8%D0%BD%D0%BA%D0%B8,+%D0%A4%D0%B8%D0%BD%D0%BB%D1%8F%D0%BD%D0%B4%D0%B8%D1%8F/@60.1100964,24.6890541,10z/data=!3m1!4b1!4m6!3m5!1s0x46920bc796210691:0xcd4ebd843be2f763!8m2!3d60.1698557!4d24.9383791!16zL20vMDNraG4?entry=ttu&g_ep=EgoyMDI1MDIxOS4xIKXMDSoASAFQAw%3D%3D) with offer from Unity. 

After 3 cold years in Finland, I changed job and moved to [Estoril, Portugal](https://www.google.com/maps/place/%D0%AD%D1%88%D1%82%D0%BE%D1%80%D0%B8%D0%BB/@38.7097483,-9.4103927,14z/data=!3m1!4b1!4m6!3m5!1s0xd1ec5c602d62353:0x82c0f730439d4cb1!8m2!3d38.7133152!4d-9.3936558!16zL20vMDE5ODZo?entry=ttu&g_ep=EgoyMDI1MDIxOS4xIKXMDSoASAFQAw%3D%3D) where I plan to stay for a while living by the ocean side.

I have lovely family - wife, two daughters, dog and cat. My wife is psychologist (therapist) and HR. We try to do joint projects together when it's possible.

I love travelling with my family, especially when it's possible to stay in some place for month or more.
It gives me the opportunity to know the country and people better, understand culture and manners.
That's why it's very cool for me when I can travel for work and stay with particular business in some place for quite a long time.
