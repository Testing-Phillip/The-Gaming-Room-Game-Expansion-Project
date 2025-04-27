# The Gaming Room: Software Design Documentation

## Overview
For this project, I worked with **The Gaming Room**, a client who wanted to expand their Android game, *Draw It or Lose It*, into a web-based version that could run on different platforms like Windows, Linux, macOS, and mobile devices. Their main requirements were to support multiple teams and players, make sure all the names (for games, teams, and players) were unique, and only allow one active instance of the game service at a time. I created a detailed software design document that laid out how I would meet all these needs using object-oriented programming, a base `Entity` class for shared attributes, and a Singleton pattern for the game service. I also focused on making sure the design would be scalable, secure, and reliable so it could handle a lot of users without issues.

# Reflections on the Software Design Process

## 1. Summary of the The Gaming Room client and their software requirements.
The Gaming Room wanted to take their Android app and expand it into a web-based game that would work on many different platforms. They needed the game to allow multiple teams with lots of players, make sure every game, team, and player name was unique, and only have one instance of the game running at any time to keep everything organized and efficient. They also cared about making the game scalable, secure, and reliable across different systems.

## 2. What did you do particularly well in developing this documentation?
I think I did a good job keeping the design clean, organized, and modular. Creating the `Entity` base class helped avoid repeating code, and using the Singleton pattern made sure only one game service could run at a time, which was a big requirement. I also made sure the document had clear explanations and comments, which would make it easier for anyone else reading or working with the design later.

## 3. What about the process of working through a design document did you find helpful when developing the code?
Having a design document made a big difference because it helped me plan everything out before writing any code. Instead of just jumping in and figuring it out as I went, I had a clear structure to follow. It helped me catch potential problems early, like handling name uniqueness and managing memory better, so by the time I started coding, the process was way smoother.

## 4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could go back and improve one thing, having a visual would have made it a lot clearer, especially for other developers or the client. Next time, I would create some UML diagrams earlier in the process to back up my explanations.

## 5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I paid close attention to what the client asked for and made sure I built those needs directly into the design. For example, I made sure the system supported multiple teams, enforced unique names, and used the Singleton pattern to keep things organized. It is super important to consider the user's needs because the whole point of the project is to solve their problem. If you only focus on technical stuff and ignore what the user actually wants, you could end up with something that does not really help them.

## 6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I approached the design by breaking down the client's requirements into smaller parts and figuring out how to meet each one step-by-step. I would use object-oriented programming ideas like inheritance and design patterns to make the code more organized and reusable. In the future, I would keep doing that but also start making diagrams earlier and maybe do some user story mapping to really stay focused on what the client needs. I think it would also help to build small prototypes or sketches before locking down the full design.
