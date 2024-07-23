# FullStackDevelopment

HTML Evolution: From 1989 to HTML5

Historical Context
- HTML invented by Tim Berners-Lee in 1989
- World Wide Web (WWW) introduced in 1989
- HTML formally introduced in 1991

Semantic Elements

HTML (Older Versions)
In older HTML versions, generic block-level elements like `<div>` and `<span>` were used to structure content. These elements didn't convey any specific meaning.

HTML5
HTML5 introduces semantic elements that provide meaning to the structure. For instance:
- `<header>`: Represents the header section of a page
- `<nav>`: Defines navigation links
- `<article>`: Represents a self-contained piece of content
- `<section>`: Defines a thematic grouping of content

Example:
```html
<header>
    <h1>Welcome to My Website</h1>
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li>
            <!-- More navigation links -->
        </ul>
    </nav>
</header>
```
Multimedia Support

HTML (Older Versions)
Relied on third-party plugins like Flash for multimedia content.

HTML5
Provides native support for audio and video using `<audio>` and `<video>` tags.

Example:
```html
<video controls>
    <source src="my-video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```
Local Storage

HTML (Older Versions)
Used cookies or server-side storage for client data.

HTML5
Introduces the localStorage API for storing data locally on the user's device.

Example (JavaScript):
```javascript
localStorage.setItem('username', 'John');
const storedUsername = localStorage.getItem('username');
```

Geolocation Services

HTML (Older Versions)
No native geolocation support.

HTML5
Allows websites to access a user's geographical location.

Example (JavaScript):
```javascript
navigator.geolocation.getCurrentPosition(position => {
    const latitude = position.coords.latitude;
    const longitude = position.coords.longitude;
    // Use the coordinates
});
```

Drag and Drop

HTML (Older Versions)
No built-in drag-and-drop functionality.

HTML5
Enables drag-and-drop interactions.

Example:
```html
<div id="draggable" draggable="true">Drag me!</div>
```

Drawing Shapes

HTML (Older Versions)
No native support for drawing shapes.

HTML5
Allows drawing shapes using the `<canvas>` element.

Example:
```html
<canvas id="myCanvas" width="200" height="100"></canvas>
```

Browser Compatibility

HTML (Older Versions)
Worked with older browsers.

HTML5
Supported by modern browsers (Firefox, Chrome, Safari, etc.).

Doctype Declaration

HTML (Older Versions)
Had a lengthy doctype declaration.

HTML5
Has a simpler one: `<!DOCTYPE html>`

Mobile-Friendly

HTML (Older Versions)
Less mobile-friendly.

HTML5
More mobile-friendly by default.

# Frontend Frameworks

| Framework   | Version   | Description                                                                                        | Features                              |
|-------------|-----------|----------------------------------------------------------------------------------------------------|---------------------------------------|
| React       | 18.2.0    | A JavaScript library for building user interfaces, developed by Facebook.                          | React Router, Redux, Middleware API   |
| Angular     | 18.0.0    | A TypeScript-based open-source front-end web application framework led by the Angular Team at Google. | Angular Router, NgRx                  |
| Vue.js      | 3.4.33    | An open-source model–view–viewmodel front-end JavaScript framework for building user interfaces.   | Vue Router, Vuex                      |
| Svelte      | 4.2.18    | A new approach to building user interfaces where components are compiled at build time.            | SvelteKit                             |
| Ember.js    | 5.10.0    | An open-source JavaScript web framework employing a component-service pattern.                     | Ember Router, Ember Data              |

# Backend Frameworks

| Framework       | Version                   | Description                                                                                         | Middleware/API                                | Databases Supported                        |
|-----------------|---------------------------|-----------------------------------------------------------------------------------------------------|----------------------------------------------|--------------------------------------------|
| Express.js      | 4.19.2                    | A minimal and flexible Node.js web application framework providing a robust set of features.         | Express Middleware                           | MongoDB, PostgreSQL, MySQL, SQLite         |
| Django          | 5.0.7                     | A high-level Python web framework that encourages rapid development and clean, pragmatic design.     | Django Middleware                            | PostgreSQL, MySQL, SQLite (development), MariaDB |
| Flask           | 3.0.3                     | A micro web framework written in Python.                                                            | Flask Middleware, Flask-RESTful, Flask-SQLAlchemy | PostgreSQL, MySQL, SQLite (development), MongoDB |
| Ruby on Rails   | 6.1.7.8, 7.0.8.4, 7.1.3.4, 7.2.0.beta2 | A server-side web application framework written in Ruby.                                             | Rack Middleware                              | PostgreSQL, MySQL, SQLite (development)    |
| Laravel         | Version 11                | A PHP framework for web artisans.                                                                   | Middleware API                               | MySQL, PostgreSQL, SQLite (development)    |
| Spring Boot     | 3.3.2                     | A Java-based framework used to create stand-alone, production-grade Spring-based applications.       | Spring Middleware (Interceptors, Filters)    | PostgreSQL, MySQL, Oracle, SQL Server      |
| ASP.NET Core    | 8.0.7                     | A cross-platform, high-performance framework for building modern, cloud-based, Internet-connected apps | ASP.NET Middleware                           | SQL Server, PostgreSQL, MySQL              |



Full-Stack Frameworks	
	
Meteor.js, the MERN Stack (MongoDB, Express.js, React, Node.js), and the MEAN Stack (MongoDB, Express.js, Angular, Node.js) are all full-stack frameworks that primarily use MongoDB as their database of choice. The LAMP Stack, which consists of Linux, Apache, MySQL/MariaDB, and PHP/Python/Perl, typically utilises MySQL or MariaDB for its database needs. On the other hand, the JAMstack (JavaScript, APIs, and Markup) leverages content APIs and headless CMS solutions like Strapi or Contentful, allowing flexibility in choosing any database backend that provides APIs.


General-Purpose Text Editors
Visual Studio Code (VS Code)
Sublime Text
Atom
Brackets
Integrated Development Environments (IDEs)
WebStorm
Adobe Dreamweaver
IntelliJ IDEA
Language-Specific Editors/IDEs
PhpStorm
PyCharm
RubyMine
NetBeans
Eclipse
Front-End Development
CodePen
JSFiddle
JSBin
Responsiveness

1. Media queries
2. Css flex/Grid Concept
3.Inbuilt responsive Css framework like bootstrap , Foundation , Bulma


Applications

1.Instagram
2. Facebook
3.TikTok






