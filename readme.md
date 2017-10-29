# chancenFREIHEIT Website

This is the working repository for the Website of http://chancenfreiheit.de.
It is based on the official ZURB Foundation Template for Sites.

# About chancenFREIHEIT

[![devDependency Status](https://david-dm.org/versuchshaus/chancenfreiheit/dev-status.svg)](https://david-dm.org/versuchshaus/chancenfreiheit#info=devDependencies)

**Please open all issues with this template on the main [chancenFREIHEIT](https://github.com/versuchshaus/chancenfreiheit/issues) repo.**

This site is based on the official ZURB Template for use with [Foundation for Sites](http://foundation.zurb.com/sites). We use this template to develop static site code for chancenFREIHEIT. It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript module bundling with webpack
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Installation

To work with this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

Install the Foundation CLI with this command:

```bash
npm install foundation-cli --global
```

Download the project from Git:

```bash
git clone https://github.com/versuchshaus/chancenfreiheit projectname
```

Then open the project folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
```

## Working on chancenFREIHEIT

Finally, run `foundation watch` to run Gulp. Your production site will be created in the folder called `dist`.

Add and edit only the files in the folder `src`. On saving your edited files the changes will automatically reload in your webbrowser at this URL:

```
http://localhost:8000
```

Settings for Browser Sync can be found here:

```
http://localhost:3001
```
To create compressed, production-ready assets, run `foundation build`. Your finished and compressed site will be created in the folder called `dist`.
