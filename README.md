# ACM Basilisk

<img src="https://i.imgur.com/R72xEqf.png" width=1000>

## About

This website serves to provide information about UC Riverside's ACM and ACM-W chapters.

### Technologies Used
* Node.js
* Sass

## Getting started
* Clone this repository
  * `git clone https://github.com/ptumb001/acm-basilisk.git`
* Navigate to cloned directory
  * `cd acm-basilisk`
* Install Node dependencies
  * Run `npm install`

You're ready to go! Run any task by typing `npm run task` (where "task" is the name of the task in the `"scripts"` object). The most useful task for rapid development is `watch`. It will start a new server, open up a browser and watch for any SCSS or JS changes in the `src` directory; once it compiles those changes, the browser will automatically inject the changed file(s)!

## Editing

### Content

Just edit the respective HTML file. No compilation needed.

### Styling

The Sass (`.scss`) files can be found in `src/scss`. While `npm run watch` is running, changes to `.scss` files get compiled to `dist/css/style.css`.

## Previous Versions

* [Phoenix2](https://github.com/acm-ucr/phoenix2)
* [Phoenix](https://github.com/acm-ucr/acm-phoenix)
