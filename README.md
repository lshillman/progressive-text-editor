# YOLO Editor

[![Hippocratic License HL3-FULL](https://img.shields.io/static/v1?label=Hippocratic%20License&message=HL3-FULL&labelColor=5e2751&color=bc8c3d)](https://firstdonoharm.dev/version/3/0/full.html)

### Check out the [deployed app](https://yolo-editor.herokuapp.com/) on Heroku

A lightweight, installable progressive web app to edit text files. Uses indexedDB to keep track of changes. Syntax highlighting courtesy of [CodeMirror](https://codemirror.net/).

Why use a browser-based app to edit text files? YOLO, that's why.

---
**Table of Contents**
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)
---

## Installation

Using Chrome (for desktop users) or your mobile browser of choice, simply visit the deployed app and click 'install' on the header. This will add a shortcut to the app to your applications directory (desktop users) or your homescreen (moobile users).

To roll your own, you'll need Node.js and npm to be installed before you begin. Clone this repo. From your command line, go to the repo directory and run `npm install`, followed by `npm run start`. This will use webpack to bundle the app into the `dist` directory and launch it on your local machine.

## Usage

Edit the text in the window, and click away from the window to save. All window contents will be stored in indexedDB if available, or localStorage if not.

## License
This project uses the [Hippocratic License, v3.0](https://firstdonoharm.dev). TL;DR, it's not *quite* open source, but as long as you're not violating human rights, being a fossil fuel company, conducting military operations, etc (see license for full details), you can essentially treat it as open source.

## Questions?

Contact [lshillman](https://github.com/lshillman) via methods described at [lukehillman.net](https://lukehillman.net).
