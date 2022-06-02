---
layout: layouts/post.njk
title: Institutional Awards Module at UC San Diego
metaTitle: Institutional Awards Module at UC San Diego
date: 2022-06-02T03:42:38.143Z
tags:
  - projects
  - development
  - workflows
---
The Graduate Division of UC San Diego in conjunction with representatives from each academic department managed a manual workflow on quarterly basis in to determine how much funding graduate students should and would receive according to multitude of criteria, including employment, citizenship, and fellowship/grant awards.

As part of a four person development team, interfacing with two distinct stakeholder groups, we created an Angular web application for the Department Staff to manage awards and funds for each of their students. The numbers could then be passed along to the Graduate Division for review and approval without the Graduate Division having to heavy work up front in the process and/or sift through large, static spreadsheets.

## The Task

Previously, the Departments and Grad Division would normally interface through spreadsheets or email outlining each student's award status. This would then get entered into the central awards database, which in turn interfaced with financial aid and payroll services.

With the volume of students and; also, the shear size of the University in breadth of Departments, this was becoming untenable for the Graduate Division staff. Information about a student could change almost daily, and it made a much more sense for the Department to be able to input information about their own students, with whom they had direct contact.

## The Challenges

On the technical side, the underlying database (Award Module) was an older system that only exposed an XML-based SOAP API.

Additionally, this disparate sources of data were quite challenging in terms of consistency and access. We needed pieces of student data that had never been accessed via API and/or they were spread across two/three/four different teams' area of data governance. Organizationally, it was a challenge to piece together the data points that needed to be displayed for the Departments to be effective in a centralized web app environment. 

In terms of process, it was going to be a complete, foundational shift for Graduate Division and Departments to accomplish this. This was a completely new way of handling a very time and labor intensive process - not to mention that Grad students' livelihood really depended on this going smoothly. Hiccups in the process meant that they would not get paid for that pay period.

## The Solution