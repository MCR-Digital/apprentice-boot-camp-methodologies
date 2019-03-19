<!--- ORGANISER THINGS TO CONSIDER 
- Which technical competencies, behaviours and knowledge module topics does the bootcamp cover/meet
- Structuring retros so that they can inform thinking for individual's personal learning records (off the job training record tab in their learning logs)
- Introducing some sort of test or quiz on basic concept learning points from the bootcamp to validate that they have taken stuff in, and provide organisation mentors with results to help them focus follow ups
--->

## Competencies, Behaviours and Knowledge units

* Software Methodologies

## Resources 

* Slides
* Laptops
* Internet access
* Post-its
* Pens
* Whiteboard

## Mentors / Languages
 
Two–three mentors required in addition to leads. These should be able to cover support for the required languages.

Several exercises (katas and code starters) will need to be ported to required languages.

## Prep-work for apprentices

None

### Follow-on tasks

#### The Task

For the 2018/19 cohort, the schedule of bootcamps has been designed so that each bootcamp builds on the last - teaching skills and concepts relating to the next stage in the development lifecycle.

We would like each apprentice to complete an individual project in their workplace, with each stage of the project being tackled after the relevant bootcamp has taught them the skills they need to carry out the activites of that stage (e.g. UX Design & Analysis, System & Database Design, Database/API Creation, etc.) 

#### Benefits

This approach is designed to allow all the apprentices the chance to complete an end-to-end project that moves through each stage of the SDLC/covers all the Technical Competencies. The benefit of these projects are two-fold:

* to practice and cement skills learnt at bootcamps
* to include this in portfolio as evidence

#### Defining the Project Scope

The project has been introduced to the apprentices in this latest bootcamp - and they have been given the task of coming up with a set of requirements for their own project and performing a splitting and slicing exercise to define a list of priorities (splitting and slicing techniques were covered on Day 2 of the Methodologies Bootcamp).

There are a few requirements they must work to in defining their projects:

* Must include front-end and server-side aspects
* Must have a database
* Must have some form of UI
* Should be a reasonable scope (it should be able to be completed primarily as a learning exercise alongside other studies in 20% off-the-job time, so should not be anything overly complex/ambitious.)
 
The project can either be a business project or a completely personal project. The benefits of it being a business project are that it allows for stakeholders and possible team interaction - which helps cover the underpinning behaviours and the more business-y competencies, for their portfolio.

However, if a business project is selected - it should be something non-critical that can be spread over the term of 6-7 months- allowing the apprentice to cover each stage of the project in the weeks following each bootcamp. Examples of suitable projects are, updating the company intranet site, or developing an meeting-room booking system (examples are real projects apprentices have worked on for their companies).

If there is no suitable project available - then a personal project may be used instead. Ideally this would be something that might realistically be used in the workplace or as part of the appretniceship programme (e.g. a learning dashboard/resource sharing system).
 
As a manager and/or mentor, please could you aid your apprentice in selecting a suitable project.

## Further reading / learning resources

<!--- For end of boot camp: Signposting for apprentices self study, further learning, online resources, practice etc. --->

* [BCS Course Textbook - Methodologies](https://drive.google.com/open?id=1-sdUo-Ra6CbSp0MPY4_nvMi8iPMDEN1T)
 
## Slides

The slides can be found in the docs folder of the repository.


# Boot Camp Summary


## Planned

* Working with products and Refining requirements
* Agile + related methodologies
* Coupling and Cohesion
* Revisit data store - Relational vs Not
* CRC + Diagrams / OO Design
* Composition vs Inheritance

## Carried over

* Test Doubles
* Dependency Injection
* Mocking frameworks
* 2nd Tier of Testing Pyramid
* Intro to Data Stores - Repo Pattern
* Continuous Integration as a demo
* CI practical
* Branching / PRs
* Trunk development vs branch development
* How the internet works

<!--- 

## Continuous Integration

* What is CI
* Why is CI important
* Demo of how CI can be applied to a project (Travis or similar against public repo)
* CI practical—setting up Travis or similar on own repo?

## More on source control

* Branching
* Pull requests
* Trunk vs branch development

# How the internet works

* Hostnames, IP, DNS
* Networking
* Physical infrastructure
* HTTP

--->

# Briefing for organisation mentors

This bootcamp has been designed around the syllabus of the Software Methodologies Exam and has introduced apprentices to many of the core concepts they will need to pass this exam. Further study will be required to ensure that the apprentices are able to achieve a pass grade, but this bootcamp will have laid solid foundations on which to build. 

The exam syllabus focuses on the stages of the SDLC, Roles & Responsibilities within SD teams and how these operate at the various stages of SDLC, and effective team-working practices. 

With the learning from this bootcamp, appretnices should be able to better identify opportunities to demonstrate their ability to operate effectively as part of a team. They should be able to recognise how the work they are doing relies on and impacts other roles. 

A slicing and splitting activity has also been undertaken as part of this bootcamp, to demonstrate how to identify and prioritise tasks. This learning should be applied in defining the scope fo the individual projects detailed in the 'Follow-on Task' section above. 

# Working with the slides

The slides are stored as Markdown files in `docs/_posts` and are presented using a combination of Jekyll and [reveal.js](https://revealjs.com/#/). A [remote Jekyll theme](https://github.com/autotraderuk/jekyll-revealjs) is used to help make changes to the Jekyll code centrally.

The easiest way to preview your changes locally is to use docker to run Jekyll. To do this, [install docker](https://www.docker.com/get-started) if you haven’t already and run `docker-compose up` from the root of this project in a terminal. Your changes will be visible on <http://localhost:4000/>. Any changes you make to the slides will be reflected in your browser—there’s no need to restart docker. You can hit `ctrl-c` to stop the process.

Once you push your changes the slides will be published using GitHub Pages automatically (see the link at the top of the repository).
