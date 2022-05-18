---
layout: layouts/post.njk
title: UC San Diego Pattern Library
metaTitle: UC San Diego Pattern Library
date: 2020-07-26T22:41:27.766Z
tags:
  - projects
  - design-system
---
I created a component library for the applications in my team’s portfolio at UC San Diego. The library was organized in a contextual format, written for the scenarios devs will encounter when creating a UI.

## The Task

With legacy code bases and dev teams working independently of each other, our applications developed disjointed and distinct interfaces. We wanted to create a resource for developers as a reference when creating new UIs in order to give users a homogenous experience when using our applications.

## The Challenges

With applications primarily written in three different languages, how could we abstract the markup and styles  in the library so that devs could easily implement the UI elements but maintain create a consistent experience for users?

In addition, we did not want to depart too drastically from central campus systems, which are based on Bootstrap, but also develop a hint of our own identity. Essentially we wanted users to be sure that they are using a secure, UC San Diego system, while also noticing that they are enjoying an application developed by our team.

## The Solutions

<http://provost.ucsd.edu/faniola/components/contextual/>

I hesitate to use the term Design System here only because I feel it is not as comprehensive as a full system should be - perhaps it is a proto-Design-System?

The system is a Bootstrap-based library of components and design patterns for devs to freely use within their outlined contexts. The provided markup will render correctly with the inclusion of provided CSS and JS files. (our applications written in Angular obviously have a different set up).

Admittedly, the overall aesthetic is not very much different than vanilla Bootstrap, but a necessary compromise for maintaining consistency with other campus systems.