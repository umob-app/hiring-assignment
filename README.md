# umob engineering hiring assignment
## Introduction

- The purpose of the assignment is to test your ability to:
	- Document and communicate your way of thinking.
	- Design and build a functional, usable software.
	- Understand and integrate an external API.
	- Consuming and storing data.
- Invest maximum 6 hours over 1 week.

We hope you have fun building this! 
## Deliverables

- A git repo with:
	- Source code.
	- Instructions to build and run.
	- Architecture overview.
	- Things you would change if you had more time.
## The assignment: Fun with GBFS

- GBFS is a simple standard for publishing bike sharing feeds. https://github.com/MobilityData/gbfs/blob/master/gbfs.md
### Requirements
- Integrate at least 3 providers of GBFS from this list https://github.com/MobilityData/gbfs/blob/master/systems.csv
- Allow users to create an account with a simple authentication flow.
- Generate multiple choices questions for the user to guess the answer to. 
	- You can choose what kind of questions to present, as long as they rely on the data received from the GBFS feed. Example question would be number of bikes in a city or a street, longest distance between bikes, shortest distance between bikes, biggest provider in a city, ..etc
	- The user has 1 minute to answer as many questions as possible.
	- Each correct answer earns the user 50 points.
	- Each wrong answer takes away 20 points. 
	- The user wins the game if they keep a positive balance of points for the duration of the game.
	- After the end of the game, the user can see a list of their attempts and scores and can restart the game.
- You have freedom in deciding on the UX/UI of the game, wether it's a map, a command-line game or anything else.

### Bonus Points

- Include automated tests.
- Deployed version online.
- Implement additional features such as:
	- Implement multiplayer leaderboard.
	- Allow users to upload an avatar.
	- Allow users to export their history.
	- Any fancy feature you think of! 
