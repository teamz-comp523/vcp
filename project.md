# SAS App for Volumetric Capture Processing

[Home](https://teamz-comp523.github.io/vcp/index.html) | [Project](https://teamz-comp523.github.io/vcp/project.html) | [Team](https://teamz-comp523.github.io/vcp/team.html) | [Journal](https://teamz-comp523.github.io/vcp/journal.html) | [Deliverables](https://teamz-comp523.github.io/vcp/deliverables.html)

## Project Summary
This project will build the public-facing interface to a computer vision volumetric capture project being built by the Reese Innovation Lab. VCP, standing for Volumetric Capture Processor, is an app created by the Resse Innovation lab that produces volumetric 3D models from multiple video and data sources.

## Project Description

### Motivation

### Target Platform

### Target Users

### Our Client

### Impacts

### Goals

a longer project description (~1 page max; target audience: your mom), describing:

- the need for the software
- the target software platform (e.g. web app, mobile app, etc.)
- the target users of the software
- who the client is
- why we should care about it
- what the primary goals of the project are

VCP produces volumetric 3D models from multiple video and data sources. This project will build the public-facing interface to a computer vision volumetric capture project being built by the Reese Innovation Lab.

We are going to present the VCP app created by the Reese Innovation Lab to the public using websites. Our website will allow authorized members to modify the data, publish new projects, scenes (within the projects) and captures (within the scenes) and download after the upload process is done.

Technology applied:
Python/Django hosted on AWS for managing and processing multiple camera data files
HTML, CSS, JavaScript template/views
Code managed in Github

Data Modeling (what our project does):
- Superusers will be able to create, login and manage user accounts and data 
- Users will be able to create and log in to an account.
- Users can have multiple Projects
- Projects can have multiple Scenes
- Scenes have multiple captures (at least 2 but can be more) 
- Users will be able to create a new project with a new scene and upload the captures of that scene. Those captures are then processed in the cloud 
and a 3D model is output for download and displayed in the page.
- Status updates include: Uploading, Processing, Complete
- Once the processing is complete, the file stored on S3 is downloadable.

Views (what are within our websites):
- Home page to describe the project/app with login/signup buttons
- Logged in user home page
- List of projects
- Project View
- List of scenes
- Scene View
- Sign Out
- Sign In
- Sign Up
- Support