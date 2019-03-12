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

Organisation mentors should look to exercise the knowledge we’ve covered in the boot camp. Below are suggestions for tasks that would do this, but please use your own judgement to work out what to do. There is no need for anything to be returned to MD or the presenters—it’s just a learning exercise.

* TBC

## Further reading / learning resources

<!--- For end of boot camp: Signposting for apprentices self study, further learning, online resources, practice etc. --->

* TBC
 
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

* TBC

# Working with the slides

The slides are stored as Markdown files in `docs/_posts` and are presented using a combination of Jekyll and [reveal.js](https://revealjs.com/#/). A [remote Jekyll theme](https://github.com/autotraderuk/jekyll-revealjs) is used to help make changes to the Jekyll code centrally.

The easiest way to preview your changes locally is to use docker to run Jekyll. To do this, [install docker](https://www.docker.com/get-started) if you haven’t already and run `docker-compose up` from the root of this project in a terminal. Your changes will be visible on <http://localhost:4000/>. Any changes you make to the slides will be reflected in your browser—there’s no need to restart docker. You can hit `ctrl-c` to stop the process.

Once you push your changes the slides will be published using GitHub Pages automatically (see the link at the top of the repository).