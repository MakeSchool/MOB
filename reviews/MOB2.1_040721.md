# [MOB 1.1] Course Review

<!-- omit in toc -->
## Table of Contents

1. [**Syllabus Updates**](#syllabus-updates)
1. [**Plan Improvements**](#)
   1. [ ] Introduction to Persistence Technologies in iOS
   1. [ ] Plist & UserDefaults
   1. [ ] NSCoding & Codable
   1. [ ] The FileSystem
   1. [ ] Keychain
   1. [ ] CD - Introduction
   1. [ ] CD - Relationships
   1. [ ] CD - Fetcing Data
   1. [ ] CD - Multiple Contexts
   1. [ ] Realm
   1. [ ] Core Data Notifications

## **Syllabus Updates**

- [ ] Update syllabus schedule and `_sidebar.md` to reflect proper titles (disconnect between Cloud Kit pt 1. and Core Data Notifications)
- [ ] Update schedule section for next term using provided tables in [Make-School-Courses/Syllabus-Template](https://github.com/Make-School-Courses/Syllabus-Template)
  - [ ] Change dates
  - [ ] Update lesson titles
- [ ] Clear start and due dates posted for tutorial and project
- [ ] Evaluation criteria needs to be more specific to the course - name the assignments, what scores they need, etc.

---

## **Plan Improvements**

### Introduction to Persistence Technologies in iOS

> 👀 **OVERALL**: Seems like a great introduction! Could utilize a bit more active learning in the back half of the lesson, but may be hard to do so given the topics. Overall looks good!

#### OBJECTIVES

1. Identify the main tools to persist data in iOS.
1. Compare and contrast – at a high level – every method of persistence.
1. List some advanced persistence technologies for iOS.

#### In-class Assignments

- Zen Counting
- Intro - review databases
- In Class Activity 1 - explore all the options
- Closing Exercise - 2 things you hope to get out of this course


#### After Class Assignments

- N/A

#### CHANGES

- [ ] You may do this already, but when you go over the class schedule, go over the assignments at a high level and when they're assigned and due
- [ ] For the Advanced Persistrence Technologies section, it would be cool to have examples of each to show so students can actually play around with each and compare/contrast themselves. This may be a big lift though, perhaps there are other samples tht already exist? 

---

### Plist & UserDefaults

> 👀 **OVERALL**: Concepts are covered well, but needs more active learning pieces (currently only 2 activities)

#### OBJECTIVES

1. Identify use cases for persisting information in a plist.
1. Use a plist to store and retrieve data.
1. Identify use cases for persisting information with UserDefaults in iOS
1. Use UserDefaults to store and retrieve data.
1. Familiarize with property wrappers.

#### In-class Assignments

- in-class activity 1 - Plist table
- in-class activity 2 - UserDefaults & Property Wrappers

#### After Class Assignments

- N/A

#### CHANGES

- [ ] `Creating an Information Property List File` - text after the image is cut off on the slides, consider re-formatting
- [ ] `ADDING KEYS` - this could be a great spot to put in a GIF or video showing how to do it, rather than just saying in text
- [ ] `READING FROM A PLIST` - add more comments to explain what's going on
- [ ] `WRITING TO A PLIST` - add more comments to explain what's going on
- [ ] More smaller activities - get them playing around with PLists and UserDefaults prior to the 2 activities. Could even be small challenges, very similar to the examples or existing activities, just trying to get more hands-on practice 

---

### NSCoding & Codable

> 👀 **OVERALL**: Seems like a shorter lesson, and could benefit from more active learning componenets

#### OBJECTIVES

1. Store custom objects into UserDefaults


#### In-class Assignments

- Put it to use - Person class

#### After Class Assignments

- N/A


#### CHANGES

- [ ] This lesson seems really short, but seems like they needed more time to complete the property wrappers activity from before. Either way, needs more activities/challenges for them to practice NSCoding/Codable with, similar to what existed in the previous lesson

---

### The FileSystem

> 👀 **OVERALL**: Solid concepts, but the First half needs more engagement/active learning

#### OBJECTIVES

1. Identify the parts of the filesystem in an iOS app.
1. Access, store & edit data from the filesystem.
1. Combine persistence methods with the filesystem.

#### In-class Assignments

- Where would you store table
- Playground walkthrough
- in class activity - add file system support
    - stretch challenge

#### After Class Assignments



#### CHANGES

- [ ] Where would you store table - text is cut off on slide, break it down into 2 slides
- [ ] Put comments on code snippets
- [ ] first half of the lesson could benefit from being more interactive: if coding challenges would be too hard to get togther, maybe a Jigsaw where they each research the parts of the bundle/containers and present to the class?

---

### Keychain

> 👀 **OVERALL**: Only one activity for the lesson. Need to create more

#### OBJECTIVES

1. Describe how to handle the Keychain in iOS.
1. Implement data storing/retrieval through Keychain.
1. Implementing unit tests for the Keychain

#### In-class Assignments

- in class activity - keychain practice


#### After Class Assignments



#### CHANGES

- [ ] Needs more than the one activity. Here are some examples/suggestions below:
    - `Keychain Use Case - Logging in a User` - have them build the flowchart themselves by filling in the arrows/causes (i.e. Found, Success, Failure, Not Found)
    - `Terminology` Have them define the terminology themselves
    - Other smaller activities involving using KeychainSwift or KeychainAccess

---

### CD - Introduction

> 👀 **OVERALL**: great primary activities in this lesson, just need to make the Teacher Talk areas a little more interactive with ways to engage the students

#### OBJECTIVES

1. Describe Core Data, what it is and how it works.
1. Design models to use with Core Data using Xcode's model editor.
1. Understand key concepts and components of the Core Data Stack.
1. Get started with Core Data in Xcode (add/fetch/display)

#### In-class Assignments

- In class activity 1 - core data componenets
- In class activity 2 - core data first steps

#### After Class Assignments



#### CHANGES

- [ ] Could have students research and discuss what they think the features of 3 Core Data are, and then show them your slides about them. Trying to think of ways to make the first part of the lesson more interactive
- [ ] `ADD CORE DATA TO A NEW XCODE PROJECT` you may already do this for this section, but have them code it in real-time, and then give them the key terms and have them define it before going over as a group

---

### CD - Relationships

> 👀 **OVERALL**: Very text-heavy class, needs more activities/examples for students to get more hands on pratice beyond the 1 activity

#### OBJECTIVES

1. Create our own Core Data Stack.
1. Subclassing NSManagedObject for entities.
1. Use the model editor to create relationships between properties.
1. Identify different types of relationships.

#### In-class Assignments

- in class activity 1 - Creating the CoreData Stack

#### After Class Assignments



#### CHANGES

- [ ] `THE CORE DATA STACK` - have the students define the terms, and then review them as a class after they give their definitions. Also the first visual is great, would it benefit from having more?
- [ ] This lesson in general is very text-heavy, only 1 activity - are there other small activities or playgrounds they could work with to see the various relationship types in practice?

---

### CD - Fetcing Data

> 👀 **OVERALL**: This is solid, great activities, could benefit from some more example input/ouput of running the code snippets, and some smaller activities for NSFetchedRequest and NSSortDescriptor

#### OBJECTIVES

1. Fetch data from Core Data with NSFetchedRequest
1. Refine a search using NSPredicate
1. Sort data with NSSortDescriptor
1. Fetch and display data with NSFetchedResultsController

#### In-class Assignments

- In class activity: NSPredicate playground
- IN CLASS ACTIVITY - NSFETCHEDRESULTSCONTROLLER


#### After Class Assignments



#### CHANGES

- [ ] Gist of Predicates section could be something you do a recording of with a screencast so students can see the result of commands in real time
- [ ] It's great that there are lots of code snippet examples, but I think students would benefit more seeing the results of running the code. So showing the example input and output of running these snippets. This could also be a mini-activity! Ex: given this snippet, what do you expect the output to be?
- [ ] Perhaps adding activities for NSSortDescriptor and NSFetchedRequest to give students more practice with these? Don't have to be as involved as the current activities, could be smaller challenges.

---

### CD - Multiple Contexts

> 👀 **OVERALL**: Solid explanations/tutorial, but give them a little more hands on practice with smaller challenges

#### OBJECTIVES

1. Learn about having multiple ManagedObjectContexts.
1. Discuss and use child contexts.
1. Discuss thread safety with ManagedObjectContexts.

#### In-class Assignments

- ManagedObjectContext tutorial

#### After Class Assignments



#### CHANGES

- [ ] Tutorial looks like it would take up most of the class time, but I would like to see a few more smaller coding activities before the tutorial, just to give students a bit more hands-on practice before jumping into the tutorial

---

### Realm

> 👀 **OVERALL**: Great intro to realm, just provide more small challenges (rather than 1 large one), and make sure to state why you may use Core Data over Realm cause as it currently stands, seems like Realm is better in every way

#### OBJECTIVES

1. Describe how Realm works and it's ties with Core Data.
1. Implement CRUD methods using Realm.
1. Design a solution for an app using Realm.

#### In-class Assignments

- Realm Practice


#### After Class Assignments

- Realm tutorial


#### CHANGES

- [ ] from your Core Data Vs Realm chart, it looks like Realm beats Core Data in every way. If that's true, why would we ever want to use Core Data over Realm? There may be reasons, but make sure these are stated
- [ ] all the slides that explain how to do things in Realm, give mini-activities where students get to practice this themselves. Could even take the current Bookstare activity and break it up to do across the lesson rather than all at the end

---

### Core Data Notifications

> 👀 **OVERALL**: Seems like a short lesson, is there another component to this like final project lab time? If not, may need to add more content/topics

#### OBJECTIVES

1. Use Code Data notifications to notify objects of changes in a managed object context.
1. Implement a visual indicator to users that an action was successful in an app.

#### In-class Assignments

- Why would we listen to these events? - discussion Question
- In Class Activity - Implementing CoreData’s notifications


#### After Class Assignments



#### CHANGES

- [ ] Would be good to add 1-2 more challenges for them to do on their own where you don't give them the code. Ex: have them do the same thing for their other projects, but don't give them the source code. Or have them give notifications based on different triggers and they need to review the documentation for it

---