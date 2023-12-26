
# ASP.NET

ASP.NET is an open source web framework, created by Microsoft, for building modern web apps and services with .NET.

ASP.NET is cross platform and runs on macOS, Windows, Linux, and Docker.

Here are some things included in the .NET platform:

The C#, F#, and Visual Basic programming languages
Base libraries for working with strings, dates, files/IO, and more
Editors and tools for macOS, Windows, Linux, and Docker


# MCV
MVC (Model-View-Controller) is a pattern in software design commonly used to implement user interfaces, data, and controlling logic.

# Routing In MVC

The URL pattern for routing is considered after the domain name.
https://localhost:55555/Category/Index/3
https://localhost:55555/{controller}/{action}/{id}

| URL | Controller | Action | Id |  |
| --- | --- | --- | --- | --- |
| https://localhost:55555/Category/Index | Category | Index | Null |  |
| https://localhost:55555/Category | Category | Index | Null |  |
| https://localhost:55555/Category/Edit/3 | Category | Edit | 3 |  |
| https://localhost:55555/Product/Details/3 | Product | Details | 3 |  |

# Tag Helpers 
- Tag Helpers are introduced with ASP.NET Core.
- Tag Helpers enable server-side code to participate in creating and rendering HTML elements in Razor files.
- Tag Helpers are very focused around the html elements and much more natural to use.