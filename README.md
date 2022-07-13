# M1-D13-Calculator

## Overview - the phase of a software project

### 1) Analysis phase

https://en.wikipedia.org/wiki/User_story

Called also requirements gathering phase or discovery phase.

Going to be talking with customer / client with about the requirements to understand:

- What are the problems that your application needs to solve
- How it is going to solve them

The output are usually requirement documents.
They usually contain a list of things at a higher level that the software will need to address
(business requirements, functional requirements)

Usually performed by different roles together:

- Stakeholders
- Business analysts
- Designers (UX)
- Software developers / architects

### The Calculator

Let's write the requirements. Which are usually written in the form of USER STORIES:

- As a user, I want to solve basic math operations, and receive the result easily, so that I don't have to compute them mentally
- As a user, I want the result of the previous operation to be preserved, so that I can solve a chain of operations

### 2) UX / UI Design phase

https://en.wikipedia.org/wiki/User_interface_design

https://en.wikipedia.org/wiki/User_experience_design

UX - Design the structure of the page

- Wireframe

UI - The interface design

- Mockups
- Interactive Prototypes

Tools that make the design interactive in the early stages:

- Figma (Mockup) https://www.figma.com/
- Adobe XD & Sketch app
- UX Pin https://www.uxpin.com/ or Invision App https://www.invisionapp.com/
- Miro https://miro.com/index/ facilitate discussions with stakeholders / users / team members

### 3) Software Design Phase

https://en.wikipedia.org/wiki/Software_design

https://en.wikipedia.org/wiki/Software_architecture

Software developers, egineers, software architects, designing the architecture of a software.

How to structure data, how to structure the frontend / backend / frameworks to use etc...

In simple terms: in this phase the developers talk about how to code what needs to be coded, so that they are all aligned before starting.

### Calculator software design

This is a simple application, with few buttons and requirements, we will have no server, no data to serve the user. We are simply going to focus on the bare minimum functions. Addition, Subtraction, Multiplication, Division. Then display the result, and use it for the next operation.
