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
The Graduate Division of UC San Diego and representatives from each academic department managed a manual workflow on a quarterly basis to determine how much funding graduate students should and would receive according to multitude of criteria, including employment, citizenship, and fellowship/grant awards.

As part of a five person development team, interfacing with two distinct stakeholder groups, we created an Angular web application for the Department Staff to manage awards and funds for each of their students. The numbers could then be passed along to the Graduate Division for review and approval without the Graduate Division and Departments having to the heavy work up front in the process and/or sift through large, static spreadsheets.

## The Task

Previously, the Departments and Grad Division normally interfaced through spreadsheets or email, outlining each student's award status. This would then be entered into the central awards database (Award Module), which in turn interfaced with financial aid and payroll services.

With the volume of students and; also, the shear size of the University in breadth of Departments, this was becoming untenable for the Graduate Division staff. Information about a student could change almost daily, and it made a much more sense for the Department to be able to input information about their own students, with whom they had direct contact.

## The Challenges

On the technical side, the Award Module was an older system that only exposed an XML-based SOAP API, which was not immediately accessible via web application.

Additionally, the disparate sources of data were quite challenging in terms of consistency and access. We needed pieces of student data that had never been accessed via API and/or they were spread across two/three/four different teams' area of data governance. Organizationally, it was a challenge to piece together the data points that needed to be displayed for the Departments to be effective in a centralized web app environment. 

In terms of process, it was going to be a complete, foundational shift for Graduate Division and Departments. This was a completely new way of handling a very time and labor intensive process - not to mention that Grad students' livelihood actually depended on a smooth transition. Hiccups in the process meant that they would not get paid for that pay period.

## The Solution

We created an Angular application that allowed Department staff to not only view a student profile, with combined data from various sources, but also a "fund profile" indexed by award so that they could have insight into different funding sources and what hand been allocated to each student. Additionally, there was visibility into the review/approval process surfaced in the app which granted insight into the status of awards to Departments that had never existed before.

To help with redundant data entry, we developed "Batch entry mode," to improve efficiency and user experience.

The Graduate Division benefited in that the Departments were essentially taking over the data entry portion by managing their own students and submitting awards directly into the Award Module database. They could then shift focus to review and approval, ensuring accurate and correct awards were given to students.

Technical solutions: We developed an xml-json translation app to interface with the front end application and the SOAP service for the Award Module database. We also interfaced with partners in other development teams to expedite and/or create APIs for student data.

Organizational solutions: In partnership with the Graduate Division, we held "town-hall" meetings explaining how/when/why the changes would be taking place. This including a live demo of the application led by me, followed by a Q&A session