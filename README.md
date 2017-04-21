# Mark Genest Portfolio Project

Uses [Bootstrap 4](http://v4-alpha.getbootstrap.com/). It includes a Sass compiler and a set of Panini HTML templates. [Panini](https://github.com/zurb/panini) is a super simple flat file generator for use with Gulp. It compiles a series of HTML pages using a common layout. These pages can also include HTML partials, external Handlebars helpers, or external data as JSON or YAML.

## Installation

To use this template, your computer needs:

- [NodeJS & NPM](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

To set up the project, first download it with Git:

```bash
git clone git@github.com:markgenest/portfolio.git
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd portfolio
npm install
bower install
```

Finally, run `npm start` to run the Sass and HTML template compiler. It will re-run every time you save a Sass or HTML template file and compile to `/docs` folder which is the root folder from where the files will be served on GitHub pages.
