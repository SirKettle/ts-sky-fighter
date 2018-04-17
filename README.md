# Sky fighter game

### Written in TypeScript using Phaser 3 game framework

---

Based on the [simple starter template](https://github.com/joshuamorony/phaser3-typescript-webpack-capacitor) by Josh Morony.

Using Phaser with TypeScript, Webpack, and Capacitor for native iOS and Android builds. Using this repository will require a working knowledge of Capacitor - you can find documentation [here](https://capacitor.ionicframework.com/docs/) and additional learning resources [here](https://www.joshmorony.com/tag/capacitor/).

As of this commit, Phaser 3 is not feature complete and Capacitor is still in alpha. I would not recommend using this in a production environment - proceed with caution.

## Install

```
npm install
```

```
npx cap init
```

## Develop

```
npm run dev
```

## Build

```
npm run build
```

## Add Native Platforms

```
npx cap add ios
```

```
npx cap add android
```

## Run

```
npm run build
```

```
npx cap open ios
```

```
npx cap open android
```
