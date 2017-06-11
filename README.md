# ASP.NET Core - App Building Workshop

## Setup

### .NET Core SDK 2.0 Preview 1 build 005977
Follow instructions from step 1 here: https://www.microsoft.com/net/core/preview

### Visual Studio 2017 Preview (Version 15.3.0 Preview 2.0)
If you're using Windows, you'll want to install Visual Studio 2017 Preview. You can install multiple versions of Visual Studio 2017 side by side, so you won't need to modify your existing Visual Studio 2017 install if you don't want.

#### Web Based Installer
1. Download the installer from the link at the bottom of this page: https://www.microsoft.com/net/core/preview
1. Select **only** `.NET Core` and `Web Development` workloads

#### (if available) Offline Installer
> Since conference wifi can be a little slow, we'll try to have some USB sticks with an offline installer.
1. Run vs_community.exe in vs2017 folder
1. Select **only** `.NET Core` and `Web Development` workloads

### VS Code (on USB drive)
1. Install VS Code from USB drive or http://code.visualstudio.com.

## What you'll be building
In this workshop, you'll learn by building a full-featured ASP.NET Core application from scratch. We'll start from File/ New and build up to an API back-end application, a web front-end application, and a common library for shared data transfer objects using .NET Standard.

![Architecture Diagram](https://rawgit.com/jongalloway/aspnetcore-app-workshop/master/docs/architecture-diagram.svg)

## Day 1
| Time | Title |  |
| ---- | ----- | ---- |
| 9:00 AM - 10:30 AM | Session #1 | Get bits installed, build the back-end application with basic EF model |
| 10:30 PM - 10:45 AM | Breakfast Snack | |
| 10:45 AM - 12:30 PM | Session #2 | Build out back-end, extract EF model |  |
| 12:30 PM - 1:30 PM | Lunch | |
| 1:30 PM - 3:00 PM | Session #3 | Add front-end, render agenda, set up front-end models |
| 3:00 PM - 3:15 PM | Break | |
| 3:15 PM - 5:00 PM | Session #4 | Add Admin auth, add / edit sessions, users can sign-in with Twitter and favorite sessions |

## Day 2
| Time | Title |  |
| ---- | ----- | ---- |
| 9:00 AM - 10:30 AM | Session #5 | Caching and bundling |
| 10:30 AM - 10:45 AM | Break | |
| 10:45 AM - 12:30 PM | Session #6 | Deploy to Azure |
| 12:30 PM - 1:30 PM | Lunch | |
| 1:00 PM - 1:30 PM | Optional Lunch Session | Single Page Applications | Jon |
| 1:30 PM - 5:00 PM | Session #8 | Challenges |

* Conference Planner
  * Admin
  * Attendee (customize session)
  * Public
* Search
* Schema
  * Speakers
  * Tracks
  * Tags
  * Sessions
  * Users
* Need architecture diagram
* Conference DTO
  * .NET Standard
* API App has Entity Models referencing DTOs
* DTOs with buddy types
  * Follow Damian's code in live.asp.net (preview 2 branch)
  * Input / Output models in API
  * Front end will have page models