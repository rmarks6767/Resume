# River Marks
*Software Engineering Intern at [Thorlabs](https://www.thorlabs.com/)*
## Personal Info

**Email Address:** RiverJ.Marks@gmail.com <br>
**Phone Number:** [*See pdf Resume for Phone Number*](https://github.com/rmarks6767/Resume/blob/master/River-Marks-Resume.pdf) <br>
**Linkedin:** [River Marks](https://www.linkedin.com/in/rivermarks/)

## Languages and Technologies
**Higher Knowledge:** C#, .netCore, GraphQL, GraphQL DotNet <br>
**Intermediate:** Python, NodeJs, Git, Github, Locust.io, Markdown, Linux (Fedora & Ubuntu) <br>
**Curious:** Bash, C++, Rust, JavaScript <br>
**Learning:** Swift / IOS development <br>

## Projects

### [Imagine RIT Smart Car Music System](https://github.com/rmarks6767/music-system) <br> 
*2/13/2019 - 4/26/2019 &bull; NodeJs & Javascript*<br>
#### TL; DR
* A middleman API to interface with the Spotify Web API and allow different Smart Car features to control music
* Written in NodeJs and deployed on a local iteration of Openshift, pulling directly from Github
* All requests are made through URL Queries that directly interface with Spotify <br>
#### Summary
A [NodeJs](https://nodejs.org/) REST api that acted as a middleman between Spotify and the Smart Car.  This allowed the other members of the project to make simple requests to the api in order to control different aspects of the music in the car; the volume, song, artist, album, and skip functionalty was included.   <br> 

### [Breakwater Game Engine](https://github.com/rmarks6767/Breakwater) <br>
*1/19/2019 - 3/30/2019 &bull; C# & Monogame*<br>
#### TL; DR
* Team project that uses the MonoGame Graphics Library
* Implemented Pathfinding for enemy AI based on 2D 'Node' grid
* Implemented Quad Tree for collision checking in the created world <br>
#### Summary
A C# game that utilized the [MonoGame framework](http://www.monogame.net/) for graphics processing.  The idea came to us after the disappointing release of Atlas (A reskin of ARK that aimed at being an open world pirate game).  Our thoughts were to create a world in which the story was not forced upon you, you could play with friends, and the world changed all around you.  We began focusing on the engine aspect of the game, creating a collision system, and path finding system for the enemies in the game.  <br>  

### [Concoria](https://github.com/rmarks6767/Concoria) <br>
*8/31/2019 - 11/5/2019 &bull; Gamemaker language & Gamemaker*<br>

## Work Experience 
### Software Engineering Internship - ThorLabs
*5/13/2019 - 8/16/2019 &bull; C#, GraphQL, .NetCore, Locust.IO, & Python*
#### TL; DR
* Developed a proof of concept for utilizing GraphQL DotNet in C# in conjunction with a Cosmos Database
* Developed a method of translating GraphQL requests directly to SQL to query Cosmos Database
* Developed algorithms for filtering against Cosmos Database in an effiecent manner
* Translated the existing REST modeled API to GraphQL and generated a GraphQL schema <br>
#### Summary
Over the summer of 2019, I was given the task of researching the most efficient way of building an API.  I developed several proof of concepts that would lead to the development of the current API.  I directly influenced the adoption of GraphQL and helped build the ground work of the current API (The one that is currently in production at Thorlabs). I also developed a method of filtering data through the use of complex algorithms to build SQL queries that could be run against Cosmos Database.  This directly influenced the amount of time it took to make requests to Cosmos and brought the response time down from 200+ ms to around 20 ms.  I finally took the existing model that had been drawn up for a REST API and wrote up a GraphQL Schema to allow the team to see everything that needed to be done.
