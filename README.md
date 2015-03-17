# Automation: The Must-Have Trend of 2015

So you want to ship software fast? AND you want some confidence that what you are shipping is high quality? Then you need to start doing automated testing, NOW; no excuses. Seriously, what are you waiting for?

Automation is cheap, fast, repeatable and accurate-- not to mention way more fun than repetition.

In this talk Jeff Koenig will discuss the advantages of automated tests, some basics about what automated tests should be, and what they should NOT be. He'll also dive into why and how automation and continuous integration should be part of your organization's culture.

#### [View Slides](http://el-jefe-.github.io/automation)

## Presentation Frameworks is [Reveal.js](https://github.com/hakimel/reveal.js)

### SETUP

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the repository
   ```sh
   $ git clone https://github.com/el-jefe-/automation.git
   ```

5. Navigate to the reveal.js folder
   ```sh
   $ cd automation
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.

## License

MIT licensed

Copyright (C) 2015 Hakim El Hattab, http://hakim.se
