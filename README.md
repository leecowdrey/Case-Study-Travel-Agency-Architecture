# Technical Architect Case Study

[Jump to presentation slides and diagrams](#Presentation)

## Introduction

As part of the interview process we’re inviting candidates to take part in an example client meeting with the candidate performing the role of the consultant and the interviewers taking on the role of the clients.  This case study will provide you with the background to the potential piece of work for the fictitious client.  During the meeting we expect you to present the approach you are suggesting for the clients, along with a proposed delivery approach with any supporting infrastructure. In addition, you may also want to expand on these features/discussion points to demonstrate knowledge not covered by them.  Please note there is only 30 minutes within the interview to cover this scenario (20 minutes to present, then 10 minutes for questions), so please consider the amount of time you have available and the level of detail you provide.

## Expectations

As interviews are currently are being carried out remotely over Zoom, please consider how you will present the information based upon tools you have available.  We are not expecting you to write code, build software or infrastructure, or write detailed design documentation. You might want to prepare some diagrams, because drawing on a Miro whiteboard in real time in an interview can be tricky!  Any diagrams or descriptions you share on the day will be used to talk about the approach you are presenting. It’s an open-ended exercise; we are not expecting to cover all aspects of your approach, just an MVP approach to prove the concept would work. This is to form the basis of the discussions to explore your knowledge, approach and how you would architect and some fundamentals in delivery.

## Background

The fictional client is a Travel Agency, this agency is currently selling holidays, where their unique selling point is a customer always buys a package holiday that MUST include flights, car hire **and** a hotel.  The Travel Agent’s customers currently either phone or visit the travel agent to look for and book holidays.  The Travel Agent’s staff use a terminal connected to three different systems, each system caters for each of the flights, hotels and car hire.  To make a booking the Travel Agent must confirm with the client their needs, book the items on each of the three systems and take a payment. Sometimes the prices change and availability drops between the customer wanting the item and the booking happening. This then means the customer may cancel, or they agree to a new flight, hotel or car hire instead.  The three booking systems are on-premises services at the travel agency, the systems are connected to third party providers via an internet connection.  We take a deposit from the customer on a handheld terminal, sometimes it's only a deposit and the customer pops back in or rings up to make further payments before their holiday.

## Requirement and delivery

### Requirements

The Travel Agents management team want to get their presence on the Internet, they believe they’ve got a model that would work well but they have no idea of the market uptake, it could be small and local, or national, maybe even international.  The travel agency wants to get off the ground with something simple and be able to rapidly scale up if the MVP is successful, with the ability to learn from what works with the customers and adding new features.  We want to explore options for how customers could use the web site, the customers must book a hotel, car and flights.  The following are all high-level requirements, remember you do not need to produce anything beyond a high-level view;

- How they would search and book
- How they could pay, the travel agency needs to support the customer not paying everything in one go
- What data we need from them
- We have a constraint that the three booking systems we have for flights, cars and hotels are on the travel agents’ premises, but you can connect to these from elsewhere and you can assume the three booking systems have an API
- The travel agency has no development capability and little IT capacity of their own, so you are free to choose the technology approach that best suits this project. It is expected that you provide an indication as to what technologies you might choose and why they are suitable.
- Any risks/issues/constraints in the approach you are presenting.

### Delivery

- We will want to know how we then go from this conceptual model to delivery.
- What kind of team you’d need to deliver and any artifacts you may produce to support this delivery.
- Again, we are looking for only a high-level approach here.

## Presentation

- [PDF](./TRAVELcliqueCaseStudy.pdf)
- [PowerPoint](./TRAVELcliqueCaseStudy.pptx)

## Technical Architecture Diagrams

- [Functional](./functional.svg)
- [Application](./application.svg)
- [Integration](./integration.svg)
- [Data](./data.svg)
- [Deployment](./deployment.svg)
- [DevOps](./devops.svg)


> [All architecture diagrams also available in Draw.io](./TRAVELcliqueArchitecture.drawio)

