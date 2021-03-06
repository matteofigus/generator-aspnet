# Welcome to ASP.NET 5

We've made some big updates in this release, so it’s **important** that you spend a few minutes to learn what’s new.

You've created a new ASP.NET 5 project. [Learn what's new](http://go.microsoft.com/fwlink/?LinkId=518016)

## This application consists of:

*   Sample pages using ASP.NET MVC 6
*   [Gulp](http://go.microsoft.com/fwlink/?LinkId=518007) and [Bower](http://go.microsoft.com/fwlink/?LinkId=518004) for managing client-side libraries
*   Theming using [Semantic UI](http://semantic-ui.com/)

## Semantic UI

### CSS / JS
This generator uses the Semantic UI bower package. By default it includes the entire Semantic UI .css or .min.css
depending on the environment. You can read the Semantic UI documentation [here](http://semantic-ui.com/introduction/build-tools.html) to learn how to use just the components you need.

### Validation
In order for Semantic UI validation to play nicely with the jQuery unobtrusive validation, a helper has been added to 
hook into the validation calls and update the fields. This module simply highlights the field, and displays a 
validation summary.

For a form to be validated, add the `validate-me` class. To display the error messages use:

`<div asp-validation-summary="ValidationSummary.All" class="ui error message"></div>`

semantic.validation.js is where the magic happens. Upon error (highlight), find the nearest field element and add the error class.
When the error is cleared (unhighlight), remove the error class from the nearest field element.

### MenuLinkTagHelper
To assist with menu highlighting depending on the route, a MenuLinkTagHelper class has been included.

## How to

*   [Add a Controller and View](http://go.microsoft.com/fwlink/?LinkID=398600)
*   [Add an appsetting in config and access it in app.](http://go.microsoft.com/fwlink/?LinkID=699562)
*   [Manage User Secrets using Secret Manager.](http://go.microsoft.com/fwlink/?LinkId=699315)
*   [Use logging to log a message.](http://go.microsoft.com/fwlink/?LinkId=699316)
*   [Add packages using NuGet.](http://go.microsoft.com/fwlink/?LinkId=699317)
*   [Add client packages using Bower.](http://go.microsoft.com/fwlink/?LinkId=699318)
*   [Target development, staging or production environment.](http://go.microsoft.com/fwlink/?LinkId=699319)

## Overview

*   [Conceptual overview of what is ASP.NET 5](http://go.microsoft.com/fwlink/?LinkId=518008)
*   [Fundamentals of ASP.NET 5 such as Startup and middleware.](http://go.microsoft.com/fwlink/?LinkId=699320)
*   [Working with Data](http://go.microsoft.com/fwlink/?LinkId=398602)
*   [Security](http://go.microsoft.com/fwlink/?LinkId=398603)
*   [Client side development](http://go.microsoft.com/fwlink/?LinkID=699321)
*   [Develop on different platforms](http://go.microsoft.com/fwlink/?LinkID=699322)
*   [Read more on the documentation site](http://go.microsoft.com/fwlink/?LinkID=699323)

## Run & Deploy

*   [Run your app](http://go.microsoft.com/fwlink/?LinkID=517851)
*   [Run your app on .NET Core](http://go.microsoft.com/fwlink/?LinkID=517852)
*   [Run commands in your project.json](http://go.microsoft.com/fwlink/?LinkID=517853)
*   [Publish to Microsoft Azure Web Apps](http://go.microsoft.com/fwlink/?LinkID=398609)

We would love to hear your [feedback](http://go.microsoft.com/fwlink/?LinkId=518015)
