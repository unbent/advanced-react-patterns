<div>
  <h1>--------------Read This First---------------</h1>
  <p>
  The purpose of forking this repo is so that I have a log of all the work I have done for the Epic React course. Feel free to look at how I solve problems, and watch as I improve! This is the React Hooks portion of the course.
  </p>
  <h1>--------------------------------------------</h1>
</div>
<div>
  <h1 align="center"><a href="https://www.epicreact.dev/modules/advanced-react-patterns-v1/advanced-react-patterns-welcome">🤯 Advanced React Patterns 🚀 EpicReact.Dev</a></h1>
  <strong>
    Learn how to build simple and flexible React Components and Hooks using
    modern patterns
  </strong>
  <p>
    Not only learn great patterns you can use but also the strengths and
    weaknesses of each, so you know which to reach for to provide your custom
    hooks and components the flexibility and power you need.
  </p>

  <a href="https://epicreact.dev">
    <img
      alt="Learn React from Start to Finish"
      src="https://kentcdodds.com/images/epicreact-promo/er-1.gif"
    />
  </a>
</div>

<hr />

<!-- prettier-ignore-start -->
[![Build Status][build-badge]][build]
[![All Contributors][all-contributors-badge]](#contributors)
[![GPL 3.0 License][license-badge]][license]
[![Code of Conduct][coc-badge]][coc]
[![Gitpod ready-to-code][gitpod-badge]](https://gitpod.io/#https://github.com/kentcdodds/advanced-react-patterns)
<!-- prettier-ignore-end -->

## Prerequisites

- Read my blog post
  [Inversion of Control](https://kentcdodds.com/blog/inversion-of-control). Or
  watch
  [Implement Inversion of Control](https://egghead.io/lessons/egghead-implement-inversion-of-control?pl=kent-s-blog-posts-as-screencasts-eefa540c&af=5236ad)
- The more experience you have with building React abstractions, the more
  helpful this workshop will be for you.

> NOTE: The EpicReact.dev videos were recorded with React version ^16.13 and all
> material in this repo has been updated to React version ^18. Differences are
> minor and any relevant differences are noted in the instructions.

## Quick start

It's recommended you run everything in the same environment you work in every
day, but if you don't want to set up the repository locally, you can get started
in one click with [Gitpod](https://gitpod.io),
[CodeSandbox](https://codesandbox.io/s/github/kentcdodds/advanced-react-patterns),
or by following the [video demo](https://www.youtube.com/watch?v=gCoVJm3hGk4)
instructions for [GitHub Codespaces](https://github.com/features/codespaces).

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/kentcdodds/advanced-react-patterns)

For a local development environment, follow the instructions below

## System Requirements

- [git][git] v2.13 or greater
- [NodeJS][node] `>=16`
- [npm][npm] v8.16.0 or greater

All of these must be available in your `PATH`. To verify things are set up
properly, you can run this:

```shell
git --version
node --version
npm --version
```

If you have trouble with any of these, learn more about the PATH environment
variable and how to fix it here for [windows][win-path] or
[mac/linux][mac-path].

## Setup

> If you want to commit and push your work as you go, you'll want to
> [fork](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo)
> first and then clone your fork rather than this repo directly.

After you've made sure to have the correct things (and versions) installed, you
should be able to just run a few commands to get set up:

```shell
git clone https://github.com/kentcdodds/advanced-react-patterns.git
cd advanced-react-patterns
node setup
```

This may take a few minutes. **It will ask you for your email.** This is
optional and just automatically adds your email to the links in the project to
make filling out some forms easier.

If you get any errors, please read through them and see if you can find out what
the problem is. If you can't work it out on your own then please [file an
issue][issue] and provide _all_ the output from the commands you ran (even if
it's a lot).

If you can't get the setup script to work, then just make sure you have the
right versions of the requirements listed above, and run the following commands:

```shell
npm install
npm run validate
```

If you are still unable to fix issues and you know how to use Docker 🐳 you can
setup the project with the following command:

```shell
docker-compose up
```

## Running the app

To get the app up and running (and really see if it worked), run:

```shell
npm start
```

This should start up your browser. If you're familiar, this is a standard
[react-scripts](https://create-react-app.dev/) application.

You can also open
[the deployment of the app on Netlify](https://advanced-react-patterns.netlify.app/).

## Running the tests

```shell
npm test
```

This will start [Jest](https://jestjs.io/) in watch mode. Read the output and
play around with it. The tests are there to help you reach the final version,
however _sometimes_ you can accomplish the task and the tests still fail if you
implement things differently than I do in my solution, so don't look to them as
a complete authority.

### Exercises

- `src/exercise/00.md`: Background, Exercise Instructions, Extra Credit
- `src/exercise/00.js`: Exercise with Emoji helpers
- `src/__tests__/00.js`: Tests
- `src/final/00.js`: Final version
- `src/final/00.extra-0.js`: Final version of extra credit

The purpose of the exercise is **not** for you to work through all the material.
It's intended to get your brain thinking about the right questions to ask me as
_I_ walk through the material.

### Helpful Emoji 🐨 💰 💯 📝 🦉 📜 💣 💪 🏁 👨‍💼 🚨

Each exercise has comments in it to help you get through the exercise. These fun
emoji characters are here to help you.

- **Kody the Koala** 🐨 will tell you when there's something specific you should
  do
- **Marty the Money Bag** 💰 will give you specific tips (and sometimes code)
  along the way
- **Hannah the Hundred** 💯 will give you extra challenges you can do if you
  finish the exercises early.
- **Nancy the Notepad** 📝 will encourage you to take notes on what you're
  learning
- **Olivia the Owl** 🦉 will give you useful tidbits/best practice notes and a
  link for elaboration and feedback.
- **Dominic the Document** 📜 will give you links to useful documentation
- **Berry the Bomb** 💣 will be hanging around anywhere you need to blow stuff
  up (delete code)
- **Matthew the Muscle** 💪 will indicate that you're working with an exercise
- **Chuck the Checkered Flag** 🏁 will indicate that you're working with a final
- **Peter the Product Manager** 👨‍💼 helps us know what our users want
- **Alfred the Alert** 🚨 will occasionally show up in the test failures with
  potential explanations for why the tests are failing.

## Contributors

Thanks goes to these wonderful people
([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://kentcdodds.com"><img src="https://avatars.githubusercontent.com/u/1500684?v=3?s=100" width="100px;" alt="Kent C. Dodds"/><br /><sub><b>Kent C. Dodds</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=kentcdodds" title="Code">💻</a> <a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=kentcdodds" title="Documentation">📖</a> <a href="#infra-kentcdodds" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=kentcdodds" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/FWeinb"><img src="https://avatars0.githubusercontent.com/u/1250430?v=4?s=100" width="100px;" alt="FWeinb"/><br /><sub><b>FWeinb</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/issues?q=author%3AFWeinb" title="Bug reports">🐛</a> <a href="#ideas-FWeinb" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/dlannoye"><img src="https://avatars2.githubusercontent.com/u/1383720?v=4?s=100" width="100px;" alt="David Lannoye"/><br /><sub><b>David Lannoye</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/issues?q=author%3Adlannoye" title="Bug reports">🐛</a> <a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=dlannoye" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/colinrcummings"><img src="https://avatars2.githubusercontent.com/u/9815009?s=460&v=4?s=100" width="100px;" alt="Colin Cummings"/><br /><sub><b>Colin Cummings</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=colinrcummings" title="Code">💻</a> <a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=colinrcummings" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/bkoltai"><img src="https://avatars2.githubusercontent.com/u/464764?v=4?s=100" width="100px;" alt="Benji Koltai"/><br /><sub><b>Benji Koltai</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=bkoltai" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://baggasumit.github.io"><img src="https://avatars1.githubusercontent.com/u/1779959?v=4?s=100" width="100px;" alt="Sumit Bagga"/><br /><sub><b>Sumit Bagga</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=baggasumit" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Tarabyte"><img src="https://avatars0.githubusercontent.com/u/2027010?v=4?s=100" width="100px;" alt="Yury Tarabanko"/><br /><sub><b>Yury Tarabanko</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=Tarabyte" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://www.wendtedesigns.com/"><img src="https://avatars2.githubusercontent.com/u/5779538?v=4?s=100" width="100px;" alt="Alex Wendte"/><br /><sub><b>Alex Wendte</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=themostcolm" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/CompuIves"><img src="https://avatars3.githubusercontent.com/u/587016?v=4?s=100" width="100px;" alt="Ives van Hoorne"/><br /><sub><b>Ives van Hoorne</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=CompuIves" title="Code">💻</a> <a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=CompuIves" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://team.thebrain.pro"><img src="https://avatars1.githubusercontent.com/u/4002543?v=4?s=100" width="100px;" alt="Łukasz Gandecki"/><br /><sub><b>Łukasz Gandecki</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=lgandecki" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/deniztetik"><img src="https://avatars0.githubusercontent.com/u/14167019?v=4?s=100" width="100px;" alt="Deniz Tetik"/><br /><sub><b>Deniz Tetik</b></sub></a><br /><a href="#content-deniztetik" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Ruffeng"><img src="https://avatars1.githubusercontent.com/u/18511772?v=4?s=100" width="100px;" alt="Ruffeng"/><br /><sub><b>Ruffeng</b></sub></a><br /><a href="#content-Ruffeng" title="Content">🖋</a> <a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=Ruffeng" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://stackshare.io/jdorfman/decisions"><img src="https://avatars1.githubusercontent.com/u/398230?v=4?s=100" width="100px;" alt="Justin Dorfman"/><br /><sub><b>Justin Dorfman</b></sub></a><br /><a href="#fundingFinding-jdorfman" title="Funding Finding">🔍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://alexmunoz.github.io"><img src="https://avatars3.githubusercontent.com/u/3093946?v=4?s=100" width="100px;" alt="Alex Munoz"/><br /><sub><b>Alex Munoz</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=AlexMunoz" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/marcosvega91"><img src="https://avatars2.githubusercontent.com/u/5365582?v=4?s=100" width="100px;" alt="Marco Moretti"/><br /><sub><b>Marco Moretti</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=marcosvega91" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/emipc"><img src="https://avatars1.githubusercontent.com/u/26004903?v=4?s=100" width="100px;" alt="Emili"/><br /><sub><b>Emili</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=emipc" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/balavishnuvj"><img src="https://avatars3.githubusercontent.com/u/13718688?v=4?s=100" width="100px;" alt="balavishnuvj"/><br /><sub><b>balavishnuvj</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=balavishnuvj" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.linkedin.com/in/pritamsangani/"><img src="https://avatars3.githubusercontent.com/u/22857896?v=4?s=100" width="100px;" alt="Pritam Sangani"/><br /><sub><b>Pritam Sangani</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=PritamSangani" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://linkedin.com/in/katarzynakosturek/"><img src="https://avatars3.githubusercontent.com/u/36547835?v=4?s=100" width="100px;" alt="Kasia Kosturek"/><br /><sub><b>Kasia Kosturek</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=kocvrek" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/emzoumpo"><img src="https://avatars2.githubusercontent.com/u/2103443?v=4?s=100" width="100px;" alt="Emmanouil Zoumpoulakis"/><br /><sub><b>Emmanouil Zoumpoulakis</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=emzoumpo" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://peter.hozak.info/"><img src="https://avatars0.githubusercontent.com/u/1087670?v=4?s=100" width="100px;" alt="Peter Hozák"/><br /><sub><b>Peter Hozák</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=Aprillion" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/nawok"><img src="https://avatars3.githubusercontent.com/u/159773?v=4?s=100" width="100px;" alt="Pavel Fomchenkov"/><br /><sub><b>Pavel Fomchenkov</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=nawok" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.seemaullal.com"><img src="https://avatars0.githubusercontent.com/u/8728285?v=4?s=100" width="100px;" alt="Seema Ullal"/><br /><sub><b>Seema Ullal</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=seemaullal" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://git.io/JfYj5"><img src="https://avatars0.githubusercontent.com/u/25733135?v=4?s=100" width="100px;" alt="Patrick Clery"/><br /><sub><b>Patrick Clery</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=patrickclery" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/degeens"><img src="https://avatars2.githubusercontent.com/u/33414262?v=4?s=100" width="100px;" alt="Stijn Geens"/><br /><sub><b>Stijn Geens</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=degeens" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://michaeldeboey.be"><img src="https://avatars3.githubusercontent.com/u/6643991?v=4?s=100" width="100px;" alt="Michaël De Boey"/><br /><sub><b>Michaël De Boey</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=MichaelDeBoey" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.daleseo.com"><img src="https://avatars1.githubusercontent.com/u/5466341?v=4?s=100" width="100px;" alt="Dale Seo"/><br /><sub><b>Dale Seo</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=DaleSeo" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://bobbywarner.com"><img src="https://avatars0.githubusercontent.com/u/554961?v=4?s=100" width="100px;" alt="Bobby Warner"/><br /><sub><b>Bobby Warner</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=bobbywarner" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://www.sophiabrandt.com"><img src="https://avatars0.githubusercontent.com/u/16630701?v=4?s=100" width="100px;" alt="Sophia Brandt"/><br /><sub><b>Sophia Brandt</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=sophiabrandt" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ph08n1x"><img src="https://avatars.githubusercontent.com/u/4249732?v=4?s=100" width="100px;" alt="ph08n1x"/><br /><sub><b>ph08n1x</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=ph08n1x" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.suhas010.com"><img src="https://avatars.githubusercontent.com/u/8597576?v=4?s=100" width="100px;" alt="Suhas R More"/><br /><sub><b>Suhas R More</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=Suhas010" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/0xnoob"><img src="https://avatars.githubusercontent.com/u/49793844?v=4?s=100" width="100px;" alt="0xnoob"/><br /><sub><b>0xnoob</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=0xnoob" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://pavlos.dev"><img src="https://avatars.githubusercontent.com/u/100233?v=4?s=100" width="100px;" alt="Pavlos Vinieratos"/><br /><sub><b>Pavlos Vinieratos</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=pvinis" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/infoxicator"><img src="https://avatars.githubusercontent.com/u/17012976?v=4?s=100" width="100px;" alt="Ruben Casas"/><br /><sub><b>Ruben Casas</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=infoxicator" title="Code">💻</a> <a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=infoxicator" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/marioleed"><img src="https://avatars.githubusercontent.com/u/1763448?v=4?s=100" width="100px;" alt="Mario Sannum"/><br /><sub><b>Mario Sannum</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=marioleed" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://wrongabhishek.com"><img src="https://avatars.githubusercontent.com/u/47311875?v=4?s=100" width="100px;" alt="Abhishek Rawat"/><br /><sub><b>Abhishek Rawat</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=AbePlays" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://fullchee.com"><img src="https://avatars.githubusercontent.com/u/11246258?v=4?s=100" width="100px;" alt="Fullchee Zhang"/><br /><sub><b>Fullchee Zhang</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=Fullchee" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/YaseenAlGailani"><img src="https://avatars.githubusercontent.com/u/23329119?v=4?s=100" width="100px;" alt="Yaseen"/><br /><sub><b>Yaseen</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=YaseenAlGailani" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://mangovoice.com"><img src="https://avatars.githubusercontent.com/u/2466729?v=4?s=100" width="100px;" alt="Jeff Potter"/><br /><sub><b>Jeff Potter</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=jpotts18" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kenneth-gray"><img src="https://avatars.githubusercontent.com/u/10341832?v=4?s=100" width="100px;" alt="Kenny Gray"/><br /><sub><b>Kenny Gray</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/issues?q=author%3Akenneth-gray" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://jorgearuv.dev"><img src="https://avatars.githubusercontent.com/u/7416811?v=4?s=100" width="100px;" alt="Jorge Ruvalcaba"/><br /><sub><b>Jorge Ruvalcaba</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=jorgeruvalcaba" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://creador.dev"><img src="https://avatars.githubusercontent.com/u/40248406?v=4?s=100" width="100px;" alt="Pawan Kumar"/><br /><sub><b>Pawan Kumar</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=creador-dev" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://junagao.com"><img src="https://avatars.githubusercontent.com/u/615616?v=4?s=100" width="100px;" alt="juliane nagao"/><br /><sub><b>juliane nagao</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=junagao" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.ianjmacintosh.com"><img src="https://avatars.githubusercontent.com/u/1103259?v=4?s=100" width="100px;" alt="Ian MacIntosh"/><br /><sub><b>Ian MacIntosh</b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=ianjmacintosh" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Creeland"><img src="https://avatars.githubusercontent.com/u/518406?v=4?s=100" width="100px;" alt="Creeland A. Provinsal "/><br /><sub><b>Creeland A. Provinsal </b></sub></a><br /><a href="https://github.com/kentcdodds/advanced-react-patterns/commits?author=Creeland" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the
[all-contributors](https://github.com/kentcdodds/all-contributors)
specification. Contributions of any kind welcome!

## Workshop Feedback

Each exercise has an Elaboration and Feedback link. Please fill that out after
the exercise and instruction.

At the end of the workshop, please go to this URL to give overall feedback.
Thank you! https://kcd.im/arp-ws-feedback

<!-- prettier-ignore-start -->
[npm]: https://www.npmjs.com/
[node]: https://nodejs.org
[git]: https://git-scm.com/
[build-badge]: https://img.shields.io/github/actions/workflow/status/kentcdodds/advanced-react-patterns/validate.yml?branch=main&logo=github&style=flat-square
[build]: https://github.com/kentcdodds/advanced-react-patterns/actions?query=workflow%3Avalidate
[license-badge]: https://img.shields.io/badge/license-GPL%203.0%20License-blue.svg?style=flat-square
[license]: https://github.com/kentcdodds/advanced-react-patterns/blob/main/LICENSE.md
[coc-badge]: https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square
[gitpod-badge]: https://img.shields.io/badge/Gitpod-ready--to--code-908a85?logo=gitpod
[coc]: https://github.com/kentcdodds/advanced-react-patterns/blob/main/CODE_OF_CONDUCT.md
[emojis]: https://github.com/kentcdodds/all-contributors#emoji-key
[all-contributors]: https://github.com/kentcdodds/all-contributors
[all-contributors-badge]: https://img.shields.io/github/all-contributors/kentcdodds/advanced-react-patterns?color=orange&style=flat-square
[win-path]: https://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/
[mac-path]: http://stackoverflow.com/a/24322978/971592
[issue]: https://github.com/kentcdodds/advanced-react-patterns/issues/new
<!-- prettier-ignore-end -->
