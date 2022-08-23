# TwilioQuest Workshop Guide

This guide will walk you through using [TwilioQuest](https://twilio.com/quest), Twilio's free to play game, to teach coding and software development concepts in a workshop setting.

## What is TwilioQuest

TwilioQuest is a free roleplaying game for Windows, Linux, MacOS, and Raspberry Pi, built by Twilio. TwilioQuest helps you learn about software development tools and concepts through in-game tutorials and challenges, called Objectives. Players will journey to different destinations in a series of missions, each covering a different topic, skill, or technology.

### Why use TwilioQuest in a workshop

**Quick summary:** TwilioQuest is great for workshops because:

- Batteries included: all of the content is ready to go, you just need to help players through it!
- Fun and engaging: as a game, TwilioQuest is something different and interesting vs the usual tutorial format.
- Progress & incentives: TwilioQuest's XP system helps you keep track of how everyone is doing, or reward high performance.

**Long version:**
As a game, TwilioQuest is a novel and engaging way to learn coding concepts. The challenges in the game, the objectives, are "self-grading", and contain all of the instructions and tutorialization needed for a player to complete them. This makes it great for workshops with self-paced or independent practice portions, as students can progress at their own pace, still progress if they get stuck, and continue after the workshop at home.

As an instructor, using TwilioQuest reduces the amount of preparation to present a workshop. The game can act as your slides, as you guide players around the level, visiting and explaining each objective, and attempting to complete it with them.

TwilioQuest uses in-game XP to track player progress. You can create an event in TwilioQuest (called an Operation) to track XP earned by your players. You can use this to keep an eye on everyone's progress, to help people when they get stuck, or you can use this as an incentive through competitions to earn the most XP in the available time.

### What can you learn and teach with TwilioQuest

TwilioQuest is always growing and adding new content, but right now, here's some of the missions available in the game:

- **Node.js (Javascript)** with the Javascript Test Lab
- **Git & GitHub** with The Forest of Open Source
- **Python** with The Pythonic Temple
- **HTTP and REST APIs** with The API Academy
- **Twilio** with the VR Training.

You can also create your own missions with [TwilioQuest Extensions](https://twilioquest.github.io/extension-docs/).

## Sample workshop plan

- For a 60 minute workshop
- Schedule
  - Intro & Operation setup (10 minutes)
  - Instructor presents 1-2 objectives (variable on which objectives/mission) (20 minutes)
    - Complete with solutions
  - Independent study (20 minutes)
  - Next steps and conclusion (10 minutes)
- Sections to present/independent work by objective #

## Preparing for a workshop

### Installation instructions

The TwilioQuest launcher can be downloaded from the [TwilioQuest site](https://twilio.com/quest). It is available for Windows, Mac, and Linux, and Raspberry Pi (minimum RPi4 with 4GB Ram).

The downloaded application is the TwilioQuest Launcher. Once started, the Launcher will check for the latest version of the TwilioQuest game, and download it. You can change TwilioQuest versions from the launcher by clicking the "more" button.

To save time in the workshop, it is recommended that you instruct students to download the TwilioQuest launcher, and allow it to download the latest TwilioQuest version, ahead of the workshop. See [preparing your students]() for more info.

### Complete the prologue

When you first start the game, you will create your character, watch a cinematic, and then play a short introductory tutorial called The Prologue. The Prologue takes about 20 minutes to complete, and introduces the characters, story, and mechanics of the game. It's recommended you play through this on your first time playing the game.

When using TwilioQuest in a workshop setting, it's important to remember that first-time players will also encounter the cinematic and prologue. To save time in the workshop, it is recommended that you ask students to complete the prologue before the workshop. See [preparing your students]() for more info.

### Choose what you are going to teach

TwilioQuest has many different missions and pieces of content available.

- Who are you teaching?
  - Flow chart of mission selection
    - Do they know another programming language?
      - Yes: Javascript test lab
      - No: Tower of infinite knowledge

- Preparing the mission content
  - Missions aren't all the same length
  - Missions may have prerequisites
  - Missions have different jump off points
  - Missions may require additional setup
    - Language missions: start with downloading the language interpreter
    - Additional accounts:
      - GitHub in the open source mission
      - Twilio in API academy and VR
        - Country: service status in the country
        - Verification requirements/signup requirements
      - Postman in API academy
  - Hidden content in some missions
  - Knowing the objectives
    - Knowing the critical path
    - Sample solutions
      - Failure cases (what do different TwilioQuest error messages mean)
    - What are the linked resources in the Objective and Help screen
    - Objective screen: the todo list for the objective
    - Help screen: the sample code provided for each objective
      - VR SMS mission: reply objective, has some ruby sample code in it despite having a JS editor
  - Structure of mission, order of objectives, linear/non-linear
    - Map of the map
  - NPCs - what do they say, how do you complete the conversation trees

Variables effected:
- Session length (how long is the workshop)
- Number of facilitators 
- Experience level of the student
  - Who are the students
- Length of pre-session prep for the students

Advice:
- Read the mission overviews in this guide TODO: make mission overviews
- Play the mission and make sure it fits their goals
- How much of the mission can you cover in the time?
- What do students do after the workshop?

### Preparing to present

Workshop structure - before or after this section?

- Order of objectives
- What's the goal of each objective
- What is the key information in objective/help?
- What can go wrong/what questions might people have?

### Preparing to facilitate

- Familiarize themselves with the example code, the linked resources, and the validators TODO: Document the failure cases for each objective, pull out the linked resources, sample code, and todo lists

### Preparing the students

- When to pre-prologue or not
  - How long is the workshop
  - Is it a one off

## Delivering the workshop

### Presenting

- Legibility of multi window/screens
- Editor setup

### Facilitating the workshop

- Keep an eye on progress/questions: bring people back together if needed

### Using the Operation

- Progress tracking
- Joining
- Presenting the operation leaderboard
- Operation permissions