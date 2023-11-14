# Milestone-1/2
Original App Design Project - README Template
===

# Simple timer display

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

[Simple Study Timer is an app designed to help users implement effective study sessions with focused time blocks followed by breaks. It's based on productivity techniques like the Pomodoro Technique and can be customized to fit any study or work session.

App Evaluation]

### App Evaluation

- **Category:** Productivity / Education
- **Mobile:** Mobile-first experience with notifications and background timer capabilities.
- **Story:** Assists users in managing their study or work time effectively, promoting better focus and time management
- **Market:** Students, professionals, and anyone looking to improve their productivity and time management skills.
- **Habit:** Users are likely to use the app daily for time management during study/work sessions.
- **Scope:** V1 is a simple timer with customizable study and break periods. Future versions could introduce statistics, account sync, and social sharing.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can start a focus timer for a predefined amount of time.
* User can start a break timer after completing a focus session.
* User receives an alert when a focus session or break is over.
* User can pause and resume the timer.

**Optional Nice-to-have Stories**

* User can track the number of focus sessions completed in a day/week.
* User can create an account to save preferences and sync across devices.
* User can share their focus session accomplishments on social media.
* User can customize the app theme and timer sound.


### 2. Screen Archetypes

- [ ] Timer Screen
* [list associated required story here]
* User can start, pause, and stop the focus timer.
* User can start the break timer.
- [ ] Settings Screen
* User can adjust the lengths of focus and break sessions.
- [ ] Statistics Screen (Optional)
* User can view statistics of their focus sessions.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Timer
* Settings
* Statistics (optional)

**Flow Navigation** (Screen to Screen)

- [ ] Timer Screen
* => Settings: User can navigate to settings to change timer durations.
* => Statistics: User can navigate to view their focus session statistics (optional).
- [ ] Settings Screen
* => Timer: User returns to the timer after adjusting settings.
- [ ] Statistics Screen (Optional)
* => Timer: User navigates back to the timer to start a new session.

## Wireframes

![Simple Study Timer Wireframe 1](https://github.com/freedom12321/Milestone-1/issues/1#issue-1980407050)

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

[This section will be completed in Unit 9]

## Sprint Planning

### What are Sprints?
Sprints are the core of Agile development, allowing for iterative and incremental development of the product. Each sprint is a time-boxed period where specific tasks are completed.

### Sprint Cycle Components
- **Sprint Planning**: Determine tasks and goals for the upcoming sprint.
- **Daily Stand-Ups**: Quick daily meetings to discuss progress and obstacles.
- **Sprint Review**: Demonstrate completed work to stakeholders for feedback.
- **Sprint Retrospective**: Reflect on the sprint to improve future sprints.

### Our Sprints
- **Sprint 1**: Setup, basic UI, and start/pause functionality.
- **Sprint 2**: Settings UI and timer duration adjustments.
- **Sprint 3**: Notification implementation.
- **Sprint 4**: (Optional) Statistics tracking and user accounts.

 Sprint Planning for Simple Study Timer App

## Sprint Overview

The development of the Simple Study Timer app will be divided into weekly sprints. Each sprint will focus on implementing a set of features and will conclude with a review and retrospective.

## Sprint 1: Project Setup and Basic Timer

**Duration**: 1 week

**Goals**:
- Initialize the project repository.
- Set up the main project structure and development environment.
- Create a basic timer with start, pause, and stop functionality.

**Tasks**:
- [ ] Set up version control with Git and GitHub.
- [ ] Create the initial project files and directories.
- [ ] Implement a countdown timer function in the app.

## Sprint 2: Timer Settings and UI Implementation

**Duration**: 1 week

**Goals**:
- Develop the settings screen where users can adjust the timer durations.
- Design the main user interface for the Timer and Settings screens.

**Tasks**:
- [ ] Create UI elements for adjusting timer settings.
- [ ] Implement the logic for saving and loading the user's settings.

small video review

<div>
    <a href="https://www.loom.com/share/c6e485efe63a4706ba105aa907e240fa"></a>
    <a href="https://www.loom.com/share/c6e485efe63a4706ba105aa907e240fa">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/c6e485efe63a4706ba105aa907e240fa-with-play.gif">
    </a>
  </div>

## Sprint 3: Notifications and User Alerts

**Duration**: 1 week

**Goals**:
- Implement notifications to alert users when the timer ends or a break begins.

**Tasks**:
- [ ] Develop notification functionality to trigger at the end of a timer.
- [ ] Test notification reliability across different devices.

## Sprint 4: Optional Features

**Duration**: 1 week

**Goals**:
- If the core app is functioning well, start working on optional features like statistics tracking and user accounts.




### Models

[Add table of models]

### Networking

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
