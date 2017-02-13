[![build status](https://secure.travis-ci.org/webpack/webpack.js.org.svg)](http://travis-ci.org/webpack/webpack.js.org)

# webpack.js.org

Guides, documentation, and all things webpack.

## Contributing

To develop, please pull the project, `cd` into the directory and run:

- `npm install` to pull all dependencies.
- `npm run build` to create a production version of the site.
- `npm start` to develop on a local webpack-dev-server (should be [here](http://localhost:3000/)).

If you want to fetch the documentation on additional loaders/plugins hosted in [separate repositories](https://github.com/webpack), run `npm run fetch`. The script will help you download those documentations and put them under `content/loaders` or `content/plugins` folder.

For more information see the [contributors page](https://github.com/webpack/webpack.js.org/blob/master/CONTRIBUTING.md)

## Translation Guide

* Fork `translation` branch.
* Translate documentation.
* Regularly merge from `translation` branch to your own `translation` branch in order to get the updated documentation (especially plugin and loader documentation). Then you can compare the new and the old content.

## Content Progress

Check out the [MVP Milestone](https://github.com/webpack/webpack.js.org/milestones) for the current status.

## License

The content is available under [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.