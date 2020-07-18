# Design
Following is the XD design for the project.
[https://xd.adobe.com/spec/122792da-d1c5-458f-7ac1-6a4fdbf12ae3-6416]()

* Click the objects to see the CSS specifications (in the right panel)
* Assets like images/icons should be available to download (let Ranveer know, if you're not able to download any asset out of the designs)
* **MOST IMPORTANT:** *Pay close attention on designs (margin, padding, font-size etc.) and achieve pixel perfect pages.*

# Development Workflow Setup

* Use Webpack 4. Feel free to use additional Node.js modules or webpack-plugin to achieve the required functionalities.
* Serve your project on localhost using express.js/webpack server.

## Automation:
* HTML validation
* CSS Lint (syntax check/validation)
* Accessibility check as per WCAG 2.0 AA

## Features
* Semantic
* Unobtrusive
* Accessible (as per WCAG 2 - AA)
* Make the pages responsive (Use of CSS framework like Bootstrap is strictly not allowed). Target following devices (portrait & landscape):
	* iPhone 5+ /Android
	* iPad/Tablet
	* Laptops and higher
* Make the application offline
* Integrate [favicon generator](https://realfavicongenerator.net/) to automatically generate the set of favorite icons into your HTML automatically.
* Place the application resources (e.g. images, CSS etc.) in appropriate sub-directories. Overall follow well-defined folder structure for src and dest as well.

## Project Management and Code repository
* We need to maintain the project on the [GITLab repository](https://tagitlab.techaspect.com/UI/Training/ui-june-2019/ta-ascent)
* This is a team effort, so we will divide this project to different tasks and each member would be assigned with one or more task(s).
* The tasks will be created and tracked on GITLab in the same repository.
* We will have individual branch created for every task.
* After commit and push, you need to create a "Pull Request" on GITLab.