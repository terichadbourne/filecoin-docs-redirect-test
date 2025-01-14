# New Filecoin Docs Site (WORK IN PROGRESS)

This repo is a **work in progress** by the Filecoin Storage & Dev Tools team, building off of the work done in [VuePress](https://github.com/vuejs/vuepress) by the IPFS Docs team to create their [spiffy new IPFS docs site](https://docs-beta.ipfs.io/) (in beta).

**Please visit [docs.filecoin.io](https://docs.filecoin.io/) to reference current documentation.**


## View a live demo of the new docs site (WIP)
You can view the [live demo](https://filecoin-docs.netlify.app/) of this new site (WIP), compiled from the `master` branch, on Netlify. During this transition period, you'll see a mix of new Filecoin content, stubs for planned Filecoin content, and old IPFS content that needs to be replaced with similar articles.

[![Netlify Status](https://api.netlify.com/api/v1/badges/b3586cdd-c0e3-404c-b451-875025e0e990/deploy-status)](https://app.netlify.com/sites/filecoin-docs/deploys)

## Working on this beta platform

To spin up a local instance of this new VuePress site, see below:

1. Install the NPM dependencies:

    ```bash
    npm install
    ```

2. Boot up the application in _dev mode_:

    ```bash
    npm start
    ```

3. Open [localhost:8080](http://localhost:8080) in your browser.

## Code organization
- Navigation is generated from [docs/.vuepress/config.js](https://github.com/filecoin-project/filecoin-docs/blob/master/docs/.vuepress/config.js) and the metadata within each Markdown file. Be sure to create an entry in this config file when adding new content.
- Content lives in Markdown files in the `docs` folder. Each major section has its own subfolder.

## License

All software code is copyright (c) Protocol Labs, Inc. under the **MIT license**. Other written documentation and content is copyright (c) Protocol Labs, Inc. under the [**Creative Commons Attribution-Share-Alike License**](https://creativecommons.org/licenses/by/4.0/). See [LICENSE file](./LICENSE.md) for details.
