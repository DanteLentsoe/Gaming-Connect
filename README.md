# Gaming Connect

Mutilple Platform gaming API's for knowing which games to play, and when to play. For the first time, be able to know the ratings, first impressions, and platforms , games can be found, including trailers, all in one. No more, website investigates, made by a gamer for gamers.

[ Gaming Connect Website](https://www.Gaming-Connect.com/)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [Node](https://nodejs.org/en/download/) minimum v12.18.0
- [Typescript](https://www.typescriptlang.org/download)
- [Angular CLI](https://github.com/angular/angular-cli) version 12
- Your preferred text editor or IDE

### Preferred package manager

The preferred package manager for this project is `yarn`

### Installing

- Clone the repository using SSH

```
git clone git@github.com:Topl/Gaming-Connect.git
```

- Navigate to the cloned repo

```
cd Gaming-Connect
```

- Install dependencies

```
yarn
```

- Run the server locally

```
yarn start || ng serve
```

## Running the tests

- To run tests normally, use

```
yarn test
```

### Detail testing methods

- To run tests with coverage reporting, use

```
yarn run coverage
```

- To run tests with coverage reporting and update snapshots, use

```
yarn run coverage:update
```

- For more testing scripts, have a look at the `scripts` section in the `package.json` file

## Environments

There are 2 environments each corresponding to a branch on the repository:

- Production - `main` branch
- Development - `dev` branch

## Deployment

The application is deployed on [Netlify](https://Gaming-Connet-dev.netlify.app) | [Netlify](https://Gaming-Connet-prod.netlify.app)

## Built With

Details of the tech stack that has been used.

- [Angular](https://angular.io/) - The client framework used
- [Angular Material](https://material.angular.io/) - The component library

## Architecture

A basic architecture diagram or description of the chosen architecture should be detailed here. Lol, I did not include it.

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/DanteLentsoe/Help-an-en-eye-gee-gee-ay) for details on the followed standards standard for commit messages and the accepted pull request process.

## Authors

- **Dante Lentsoe** <dllentsoe@gmail.com>

## Licenses

Results from `npx license-checker --summary`

```
├─ MIT: 953
├─ ISC: 78
├─ BSD-3-Clause: 37
├─ BSD-2-Clause: 29
├─ Apache-2.0: 26
├─ MIT*: 8
├─ BSD: 5
├─ (MIT OR CC0-1.0): 5
├─ CC0-1.0: 4
├─ WTFPL: 2
├─ Unlicense: 2
├─ 0BSD: 2
├─ Custom: https://github.com/tmcw/jsonlint: 1
├─ BSD-3-Clause OR MIT: 1
├─ (MIT OR Apache-2.0): 1
├─ CC-BY-4.0: 1
├─ Public Domain: 1
├─ AFLv2.1,BSD: 1
├─ (MIT AND Zlib): 1
├─ (MIT AND BSD-3-Clause): 1
└─ CC-BY-3.0: 1
```

## Troubleshooting

Here is a list of common errors and possible solutions:

Failed to push to Github due to out of date snapshots:

- Run

  > yarn test:update

- or
  > yarn coverage:update

## Meta

| Version | Author                              | Date       |
| ------- | ----------------------------------- | ---------- |
| 0.0.1   | Dante Lentsoe <dllentsoe@gmail.com> | 17/03/2020 |
