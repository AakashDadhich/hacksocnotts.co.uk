# HackSoc Website [![CircleCI](https://img.shields.io/circleci/project/github/HackSocNotts/hacksocnotts.co.uk/master.svg?style=flat-square)](hackscocnotts.co.uk) ![Requires.io](https://img.shields.io/requires/github/HackSocNotts/hacksocnotts.co.uk.svg?style=flat-square)  ![GitHub issues](https://img.shields.io/github/issues/hacksocnotts/hacksocnotts.co.uk.svg?style=flat-square) ![GitHub pull requests](https://img.shields.io/github/issues-pr/hacksocnotts/hacksocnotts.co.uk.svg?style=flat-square) ![GitHub](https://img.shields.io/github/license/hacksocnotts/hacksocnotts.co.uk.svg?style=flat-square)
The current website for HackSoc at the University of Nottingham.

## How it's made
The HackSoc website core dependencies are:
 * [React](https://reactjs.org/)
 * [Semantic UI](https://semantic-ui.com/)
 * [Redux JS](https://redux.js.org/introduction)

## Contributing
Contributions are welcome for both updating our Calendar and improving the website. However, please see the [Contributors Guide](./CONTRIBUTING.md) first.

## Run locally
1. Clone the repository `git clone https://github.com/HackSocNotts/hacksocnotts.co.uk.git`
2. Install node dependencies `npm install` or `yarn install`
3. Start development server `npm start` or `yarn start`

### Validate events manifest
Run `node scripts/validateEventsManifest.js src/_events/eventsManifest.json ./output.xml`

Note that because it's made to be used as a Testkit on CircleCI it must have an output file.
