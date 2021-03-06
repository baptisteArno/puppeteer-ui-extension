# 🧶 Tinking

## Extract data from any website without code, just clicks

A Chrome extension that allows you to create a scraping recipe by directly selecting a page's elements with your mouse.

<img src="https://user-images.githubusercontent.com/16015833/106378952-d4c0e900-63a8-11eb-936b-18dead5e6e97.png" alt="Tinking allows you to define stepwise rules for scraping a website's content." width="300px"/>

[Watch a video demo](https://cleanshot-cloud-fra.accelerator.net/media/8732/gyXl0WDpJ0jpHVN3ccd5sf5kOOlzdPpugDhhcQKv.mp4)

_This tool is under active development. The code could use some cleanup, and there may be bugs. PRs are very welcome!_

💌 [Receive updates in your inbox](https://tinking.substack.com/subscribe)

👇

# Getting Started

[Download from the Chrome Web Store.](https://chrome.google.com/webstore/detail/tinking-scrapping-tool/ibidcmokfddpkgdoobeihkfnajmodlkp?hl=fr&authuser=0)

👉 [How to use the generated code?](https://github.com/baptisteArno/tinking-code-starter)

# Couldn't scrape a particular website?

While Tinking aims to be a universal tool, it's still a work in progress, and you may run into issues scraping certain websites.

Please [submit an issue](https://github.com/baptisteArno/tinking/issues/new/choose), and we'll look into a potential fix.

# Contribute

## To-Do
- [x] Infinite scroll
- [x] Pagination
- [x] Documentation on how to use the generated code
- [x] Multiple export options (playwright, others?)
- [x] Regex to filter data from scraped text
- [x] Drag-and-drop steps
- [ ] Test for different popular sites: Amazon, LinkedIn, Twitter...
- [ ] [DOC] Write examples of several popular sites
- [ ] Unit tests
- [ ] Cool logo

## 1. Clone the repository

HTTPS:

```sh
git clone https://github.com/baptisteArno/tinking.git
```

SSH:

```sh
git clone git@github.com:baptisteArno/tinking.git
```

## 2. Install dependencies, lint code, and build the extension

Using `yarn`:

```sh
yarn && yarn build
```

Or using `npm`:

```sh
npm i && npm run build
```

## 3. Install the extension in Google Chrome (or any Chromium browser)

Navigate to the following URL in Chrome:

```text
chrome://extensions/
```

Make sure `Developer Mode` is turned on, and click the `Load unpacked` button. Select the `build` folder of the project.

You should now see Tinking listed among any other extensions that you have installed, and you can begin using it to scrape websites.
