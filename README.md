# Built with Spaghetti

Built with Spaghetti aims to function as a gateway to web art / non-commercial and subversive experiments in web weirdness / experimentation with the language and technology of web / etc

## How to submit

To submit a site suggestion, [open an issue](https://github.com/gordonbisnor/built-with-spaghetti/issues/new) or [create a pull request](https://github.com/gordonbisnor/built-with-spaghetti/issues/new). Pull requests will be given higher priority since they are easier to include.

* Make sure the screenshot is 1000×625
* Run the screenshot through an image optimizer such as ImageOptim  
* Add data in src/ui/components/built-with-spaghetti/component.ts in the following format, incrementing the id based on the last entry

    {
      id: 1,
      title: "zc2 gowrth of gor",
      description: "borth of the western magnificence",
      url: "http://vkhpulkxol.s3-website-us-east-1.amazonaws.com/",
      img: "1.jpg"
    }

* Add your image to the public/ folder in the format{id}.jpg
* Double check that everything works and looks as expected before submitting

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Yarn](https://yarnpkg.com/en/)
* [Ember CLI](https://ember-cli.com/)

## Installation

* `git clone <repository-url>` this repository
* `cd built-with-spaghetti`
* `yarn`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Building

* `ember build` (development)
* `ember build --environment production` (production)

## Further Reading / Useful Links

* [glimmerjs](http://github.com/tildeio/glimmer/)
* [ember-cli](https://ember-cli.com/)
