# philiplinden.github.io
This the source code for my personal website. It is a companion to my [resume](https://github.com/philiplinden/resume).

The site is a fork of the template for [Astrofy](https://github.com/manuelernestog/astrofy), a free and open-source
website template.

## develop
1. Install astrofy: `pnpm install`
2. Build artifacts and host them on a local server: `pnpm run dev`

Now that the site is up and running locally, edit away.

## deploy
Deployment follows the example from [the Astro docs](https://docs.astro.build/en/guides/deploy/github/) using GitHub
Actions to build the site artifacts and upload them to [philiplinden.github.io](https://philiplinden.github.io).

For safety, the deployment pipeline only runs when a new commit appears on `main`.

## License
This website is built upon the template created by `manuelernestog` under the MIT license.

<a href="https://github.com/manuelernestog/astrofy/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=manuelernestog/astrofy" />
</a>
