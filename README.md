# elm-review-rules

## Introduction

My personal `elm-review` config for all Elm projects. Check out [`elm-review`](https://package.elm-lang.org/packages/jfmengels/elm-review/latest/) if you don't know what this is.

This repository was based on [SiriusStarr/elm-review-rules](https://github.com/SiriusStarr/elm-review-rules).

## Usage

You can try this out by running:

```bash
npx elm-review --template henriquecbuss/elm-review-rules
```

For more permanent usage, run:

```bash
npm install elm-review --save-dev
git submodule add https://github.com/henriquecbuss/elm-review-rules.git review
```

and then use:

```bash
npx elm-review
```

in your development.
