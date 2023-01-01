# Project Brainstorm - Software Architecture Document

## Table of Contents
- [Table of contents](#table-of-contents)
- [Introduction](#1-introduction)
    - [Purpose](#11-purpose)
    - [Scope](#12-scope)
    - [Definitions, Acronyms and Abbreviations](#13-definitions-acronyms-and-abbreviations)
    - [References](#14-references)
    - [Overview](#15-overview)
- [Architectural Representation](#2-architectural-representation)
- [Architectural Goals and Constraints](#3-architectural-goals-and-contstraints)
- [Use-Case View](#4-use-case-view)
    - [Use-Case Realizations](#41-use-case-realizations)
- [Logical View](#5-logical-view)
    - [Overview](#51-overview)
    - [Architectural Significant Design Packages](#52-architectural-significant-design-packages)
- [Process View](#6-process-view)
- [Deployment View](#7-deployment-view)
- [Implementation View](#8-implementation-view)
    - [Overview](#81-overview)
    - [Layers](#82-layers)
- [Data View](#9-data-view-optional)
- [Size and Performance](#10-size-and-performance)
- [Quality](#11-quality)

## 1. Introduction

### 1.1 Purpose
This Software Architecture Document (SAD) describes all architecture specifications for the application "Brainstorm". It includes an overview about the purpose of this project, its architectural goals and its processes.

### 1.2 Scope
The project is going to be realized as an Android, IOS and WebApp.

Actors of this App can be users or group-administrators. Whereby users can be bestoved with roles created and managed by the admin, which grant them with more possibilities to interact with the App.

Planned Subsystems are:
- User Management
- Storage Warehouse
- User Experience
- Apps

### 1.3 Definitions, Acronyms and Abbreviations
| Abbrevation | Explanation                            |
| ----------- | -------------------------------------- |
| SAD         | Software Architecture Document    |
| UC          | Use Case                               |
| n/a         | not applicable                         |
| tbd         | to be determined                       |
| UCD         | overall Use Case Diagram               |
| FAQ         | Frequently asked Questions             |

### 1.4 References
| Title                                                                                             | Date       | Publishing organization   |
| -------------------------------------------------------------------                               |:----------:| ------------------------- |
| [Project Brainstorm Blog](https://github.com/TimSchoendorf/Brainstorm/discussions/categories/blog)| 18.10.2022 | Preoject Brainstorm Team  |

### 1.5 Overview
The following chapter provides an representation of the the architecture. The third chapter delivers more specific details of our goals and the related constraints that are coming with this. 

## 2. Architectural Representation

## 3. Architectural Goals and Contstraints
Brainstorm's most important architectural goal is to offer a good usability to the users, as we want the user to have a pleasant and enjoyable time while using the application.
Our way to accomplish this goal is to have a good looking and feeling user interface as well as linking it with other architectural goals like availabilty on different devices and security.
Usability also means that no apparent faults in the system should exist.

## 4. Use-Case View
### 4.1 Use-Case Realizations
![image](https://user-images.githubusercontent.com/86354671/210170427-85907fcb-6bf7-422d-bbe6-e5ffd1a2ae25.png)

## 5. Logical View
### 5.1 Overview


## 6. Process View
### 6.1 Download File:
![Screenshot 2022-12-07 201442](https://user-images.githubusercontent.com/115456327/206276646-4067a6ba-9f15-40d5-833c-39b66dec35a1.jpg)

### 6.2 Upload File:
![Screenshot 2022-12-07 200556](https://user-images.githubusercontent.com/115456327/206276638-d879e239-c835-40df-9a13-3d5a56fcc69d.jpg)

## 7. Deployment View


## 8. Implementation View
### 8.1 Overview
![WhatsApp Image 2022-12-07 at 13 14 55](https://user-images.githubusercontent.com/86354671/206203939-6512dc5a-008c-465c-9a73-ad061130e62f.jpeg)

## 9. Data View
Date is saved in two possible ways. Chats and personal data is managed with a database. Uploaded files will be directly saved into a storage system. Because of this there will be a miximum of filespace for each user to control the required sotrage space.    

## 10. Size and Performance
With the modulith structure of our project the size can be changed afterwards, but in general it can be said that the speed of uploading messages or files depends a lot on the number of requests to the server.

## 11. Quality
In order to be able to guarantee quality according to our usability standards, we use Flutter for our frontend. This gives us the opportunity to develop for Android, IOS, PC applications and web applications and thus make our app usable on all currently popular devices.
In addition, we develop according to the four-eyes principle in order to quickly identify possible errors and thus not to endanger the usability of our program.
