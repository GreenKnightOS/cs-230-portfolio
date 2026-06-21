# CS 230 Portfolio

This repository contains my completed software design document for CS 230: Operating Platforms. The main project focuses on The Gaming Room and their game application, Draw It or Lose It.

## Portfolio Artifact

- CS 230 Software Design Document
- Client: The Gaming Room
- Project: Draw It or Lose It web application expansion

## Reflection

The Gaming Room was the client for this project. They had an Android-based game called Draw It or Lose It and wanted to expand it so users could play across multiple platforms. The game is similar to Win, Lose or Draw, where players guess what is being drawn. The client needed a software design that would support multiple teams, multiple players, unique game and team names, and future expansion into a web-based distributed application.

One thing I think I did well in this documentation was organizing the client’s needs into a design that made sense for a real application. Instead of only thinking about the code, I had to think about the full system: operating platforms, server-side deployment, browser support, storage, memory, distributed systems, and security. That helped me see how software design is bigger than just getting a program to run.

Working through the design document was helpful because it forced me to slow down and think about the structure before jumping into code. The domain model, requirements, and design constraints helped me understand what classes and services the application needed. For example, using a centralized GameService made sense because the application needed to manage games, teams, players, and unique names in one organized place.

If I could revise one part of my work, I would improve the system architecture section with a clearer diagram or explanation of how the client, server, database, and storage would communicate. I understood the basic idea, but I think a visual layout would make the design easier for a client or development team to understand.

I interpreted the user’s needs by focusing on what The Gaming Room wanted the application to actually do. They needed the game to move beyond Android, support multiple users, manage game sessions, and work across different operating systems. Considering the user’s needs is important because software is not useful just because it works technically. It has to solve the client’s actual problem and give players a smooth experience.

My approach to designing software was to break the problem into smaller parts. I looked at the client requirements first, then considered the platform options, then thought about storage, memory, networking, and security. In the future, I would use the same strategy: understand the client’s goals, identify constraints, compare possible platforms, and then recommend a design that is practical, secure, and scalable.
