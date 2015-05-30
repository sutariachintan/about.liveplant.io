---
layout: page
title: Roadmap
permalink: /roadmap/
---

Interested in contributing? Pop over to the [Getting Started][getting-started] page to find how.

## Phase 1: Initial MVP

The first version liveplant will incorporate the following criteria:

- Interface with live feed of plant and ability to submit bot action requests to
  server.
- Server is able to receive requests from liveplant.io interface and submit
  them to bot.
- Bot is able to listen to incoming requests from server.
- Bot is able to water plant.

### Blockers:

#### liveplant.io

- Define action frequency
- Interface needs to be designed.
- [Front-end framework needs to be chosen.](https://github.com/liveplant/liveplant.io/issues/1)

#### liveplant-server

- Go server needs to be bootstrapped.

#### liveplant-bot

- [Microcontroller needs to be decided upon.](https://github.com/liveplant/liveplant-bot/issues/1)

## Phase 2 and beyond:

If you'd like to contribute ideas to what liveplant.io should be able to do
after phase 1 is completed, [submit a ticket][] and prefix the issue title with
"Idea:".

- Temperature control
- Grow light
- Play music and have users be able to change music (perhaps public domain music?)
- [Ilumi light](http://ilumi.co/) that users can change the color of.


## Future Ideas for Improved Engagement:

### Non-action prompts

- Should be able to create prompts that trigger voting but is not related to a plant action. Examples could be:
  - What should the plan be named?
  - What do you estimate the height of the plant to be next week?
  - Who loves the plant the most? (by Country)

### Competitiveness

- Organize 2+ live plans and arbitrarily define teams using a heading above the plant. The teams would compete with each other on the growth of their plant. Prompts for action could be:
  - Vote to provide water to your plant or block water access to competitor plant. You can only have 1.
  - Vote to provide water to competitor plant or block water access to your plant. You can only have 1.
  - Change team name.
  - Change opponent team name.

### RPG Mode

- Develop a frame work for creating prompts and vote actions. Actions can be related to the website or the plant. Users can submit the prompts and choose what the options are. Users can vote which prompts will come up for the voting agenda (first you vote to put something to a vote, then you actually vote on it). Certain elements of the site should be available as options for voting. Examples include:
  - Change a CSS element
  - Change the page title
  - Change the font
  - Change the name of the plant


[getting-started]: /getting-started/
[submit a ticket]: https://github.com/liveplant/about.liveplant.io/issues/new
