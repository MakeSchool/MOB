# [MOB 1.3] Course Review

<!-- omit in toc -->
## Table of Contents

1. [**Syllabus Updates**](#syllabus-updates)
1. [**Plan Improvements**](#)
   1. [X] Closures and callbacks
   1. [X] Protocols & Delegation
   1. [X] Communication patterns
   1. [X] Memory Management Pt. 1
   1. [X] Memory Management Pt. 2
   1. [ ] JSON in iOS
   1. [ ] Codable Protocol
   1. [ ] Product Hunt Tutorial
   1. [ ] URLSession
   1. [ ] Pokemon assignment
   1. [ ] Requests with authentication
   1. [ ] Lab + Intro final project + Generics
   1. [ ] Testing
   1. [ ] Building a networking layer Pt 1
   1. [ ] Building a networking layer Pt 2
   1. [ ] Firebase

## **Syllabus Updates**

- [X] Update syllabus schedule to be for 13-14 class sessions. Currently at 20 including labs+review days, so would need to combine above 16 lessons into 10-12 lessons.
- [X] Update syllabus schedule and `_sidebar.md` to reflect new titles
- [X] Update schedule section for appropriate term using provided tables in [Make-School-Courses/Syllabus-Template](https://github.com/Make-School-Courses/Syllabus-Template)
  - [X] Change dates
  - [X] Update lesson titles

---

## **Plan Improvements**

### Closures and callbacks

> 👀 **OVERALL**: lots of active learning, and great intro to topic. Just needs some more variety of media and clarification in code blocks

#### OBJECTIVES

1. Identify use cases of closures
1. Understand what capturing values mean
1. Know the difference between escaping and non escaping closures
1. Implement closures as completion handlers

#### In-class Assignments

 - warmup activity around discussing/writing closures
 - Closures Swift Playground
 - mark up scoping in code snippet
 - completion handler questions + implementation
 - creating an analogy

#### After Class Assignments
 - N/A


#### CHANGES

- [X] Add more media! Currently just text and code-blocks, add some other forms of media to create variety
- [X] Provide comments in code blocks - even if simple

---

### Protocols & Delegation

> 👀 **OVERALL**: great starting analogy, and primarily active learning after initial setup!

#### OBJECTIVES

1. Construct and use protocols to define 'contracts' in code
1. Identify delegation in UIKit
1. Implement delegates in code

#### In-class Assignments

- delegate diagram creation - individual and pairs
- Creating our own delegates coding activity
- Completion handlers questions
- build on boss/intern to use completion handler + 3 colors (stretch)

#### After Class Assignments

- Giphy tutorial


#### CHANGES

- [X] Add more media! Currently just text and code-blocks, add some other forms of media to create variety
- [X] No longer doing Giphy tutorial

---

### Communication patterns

> 👀 **OVERALL**: Needs some more active learning integrated with smaller coding challenges

#### OBJECTIVES

1. Identify and implement the Target-Action pattern for event handling.
1. Understand how Notifications work using Notification Center.
1. Analyze and decide which pattern to use based on the requirements of an app.

#### In-class Assignments

- Experimenting with UIButton
- Pomodoro timer

#### After Class Assignments

- Giphy tutorial


#### CHANGES

- [X] Add more media! Currently just text and code-blocks, add some other forms of media to create variety
- [X] No active learning until halfway through the slides - can we get it in earlier? Edit: Will be kept like this due to the async version needing more TT talk.
- [X] add line breaks to codeblocks so scrolling isn't needed
- [X] Add small, shorter active learning (coding) activities for notifications/unsubscribe/etc. Can be small challenges, but get them coding with it before Pomodoro
- [X] No longer doing Giphy Tutorial

---

### Memory Management Pt. 1

> 👀 **OVERALL**: Love the short videos, great for async and to utilize a different medium! Great use of active learning, excellent work!

#### OBJECTIVES

1. Explain how memory management works in Swift, including when and why to use strong, weak, or unowned
1. Identify and resolve strong reference cycles (aka, retain cycles)
1. Demonstrate proficiency in using built-in tools and techniques to find memory leaks caused by retain cycles

#### In-class Assignments

- Leaky starship - individial / pairs
- Q on Weak References
- Fix example person/apartment
- LeakyStarship
- Closures and Retain Cycles reading + questions
- Role Play Exercise


#### After Class Assignments

- Study challenges


#### CHANGES

- None fo this one, I think this is solid!
- Merging Memory Management classes into a single lesson, at least for the async version

---

### Memory Management Pt. 2

> 👀 **OVERALL**: Great active learning and videos in the later 2/3 of the class, first third needs some more active learning

#### OBJECTIVES

1. Explain how memory management works in Swift, including when and why to use strong, weak, or unowned
1. Identify and resolve strong reference cycles (aka, retain cycles)
1. Demonstrate proficiency in using built-in tools and techniques to find memory leaks caused by retain cycles


#### In-class Assignments

- Leaky starship debug - individual + pairs
- Fixing Person/Apartment classes
- Using the Debug Memory Graph Tool tutorial
- read Closures and Retain Cycles article and answer questions
- Fix memory leaks in Leaky Starship


#### After Class Assignments

- practice interview questions


#### CHANGES

- [X] Add more active learning to the first portion of the class (everything before the first Leaky Starship intro). I'd suggest adding code snippets and then having them guess what the expected output or issue would be
- [X] Give them some small replits or similar for practice with `deinit` and reference types prior to Leaky Starship

---

### JSON in iOS / Codable Protocol

> 👀 **OVERALL**: Looks great! Good balance of active learning, and lots of hands-on work

#### OBJECTIVES

1. Identify JSON structures and create your own
1. Reading data from a file
1. Encoding/Decoding a JSON file
1. Turning data into objects using the Codable protocol

#### In-class Assignments

- festival JSON activity
- Film locations
- Using the Codable Protocol guide
- Festival lab
- Interview Questions

#### After Class Assignments

- N/A


#### CHANGES

- [ ]

---

### URLSession

> 👀 **OVERALL**:

#### OBJECTIVES

1. Implement a simple HTTP-based request to a public Internet API using the primary components of URLSession.
1. Validate HTTP response data and guard against common HTTP error conditions.
1. Display text and images fetched from free web services.

#### In-class Assignments

- Make a request jigsaw
- NASA's picture of the day 🪐
- Pokemon API
- Interview question

#### After Class Assignments

- Pokemon API


#### CHANGES

- [ ] that URLSession visual is great! reference it and highlight areas of it throughout the class as you dissect each part
- [ ] In the `URLSessionConfiguration` section, give a short poll on which scenarios they should use each type of `URLSessionConfiguration`
- [ ] Same as above but for the `URLSessionTask` section. Overall bring more engagement/active learning to the sections before `Let’s make a request - one piece at a time 🧩`
- [ ] Add mini coding challenges from `handle the error object` through `format validation` - simple replits or fill-in-the-blanks to lead them into the pokemon assignment

---

### Requests with authentication

> 👀 **OVERALL**: An incredibly active lesson! Great work for API Keys, but doesn't touch on OAUTH beyond the definition. Should incorporate OAUTH activities

#### OBJECTIVES

1. Make authenticated API requests.
1. Distinguish between OAUTH and API Key security models.
1. Identify network layer in Product Hunt Tutorial

#### In-class Assignments

- Initial Activity
- Collaborative activity
- PhotoMatic App
- PhotoMatic App Challenge

#### After Class Assignments

- Product Hunt Tutorial

#### CHANGES

- [ ] `Network Authentication for iOS` - give a one line description for API Keys
- [ ] `Product Hunt Check In` - add in frequently asked questions/points of confusion and address them in the slides here directly
- [ ] Add an activity that gets them to work with OAUTH

---

### Lab + Intro final project + Generics

> 👀 **OVERALL**: Seems like this could be combined with another lesson in the future

#### OBJECTIVES

1. N/A

#### In-class Assignments

- Work on Final Project

#### After Class Assignments

- Work on Final Project


#### CHANGES

- [ ] empty link to mini guide towards end of lesson
- [ ] combine with another lesson

---

### Testing

> 👀 **OVERALL**: Great active learning for Unit Tests, now let's add the same for testing the network layer, and add more simple challenges in general to get them more practice with it

#### OBJECTIVES

1. Define unit testing & its importance
1. Design & implement basic tests in an Xcode project.
1. Navigate Xcode to create and run tests.
1. Test a network layer

#### In-class Assignments

- Benefits of unit tests group brainstorm
- the first unit test - section and tests following
- Given When Then
- TodoItem activity


#### After Class Assignments



#### CHANGES

- [ ] add comments to `MockSession` and `MockTask` classes
- [ ] `Another Approach` section does not have playground linked
- [ ] Add active learning/mini-challenges for testing the network layer
- [ ] add some extra unit test challenges to do as HW or in class to get them practicing with it more

---

### Building a networking layer Pt 1 and 2

> 👀 **OVERALL**: Moviefy is a great longer class activity! Might be good to include some smaller ones so that they get some more practice before doing Moviefy. Or alternatively, create challenges without as much guidance for them to do after Moviefy to get more practice

#### OBJECTIVES

1. Design and construct a network layer that optimizes:
    1. modularity and reusability
    1. maintainability
    1. extendability
1. Demonstrate understanding of key application design principles:
    1. Separation of Concerns (SoC)
    1. Code reuse

#### In-class Assignments

- Moviefy implementations


#### After Class Assignments



#### CHANGES

- [ ] Add in some more smaller challenges before/after Moviefy

---

### Firebase

> 👀 **OVERALL**: Documentation-heavy lesson with 1 big tutorial. Would be great to have more activities or smaller challenges/questions for them to work through.

#### OBJECTIVES

1. Set up a project on the Firebase console.
1. Handle data using Firebase Database using an example app.

#### In-class Assignments

- photo app tutorial


#### After Class Assignments



#### CHANGES

- [ ] Adding in more activities. Right now it's lots of documentation reading, let's sprinkle in some compare/contrast with other tools they've used before
- [ ] Also add in some smaller challenges (besides the photo app) to get them acquainted with Firebase. Though we'd have to explore what that looks like/if it's possible
