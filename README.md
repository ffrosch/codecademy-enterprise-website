# Codecademy Enterprise Website Project

This project is part of Codecademy's Front End Engineer Career Path.
The goal is to build a responsive website from scratch using plain CSS.

## Project Plan

### Topic Idea

A sleek company that focuses on enabling athletes of different sports to achieve new heights in their success.
Their product is the holy grail of supplements.
They showcase athletes from the disciplines of climbing, car racing and body building.
Their website should represent their uniqueness as well as their credibility.

### Design

Goals:

1. Use Atomic Design Principles
1. Get used to common design processes

Use [Penpot](https://penpot.app/) for an iterative design process:

1. Create Wireframes for a Mobile and a Desktop Version
1. Create a Low Fidelity Prototype
1. Create a Color Palette
1. Create a High Fidelity Prototype

### Architecture

Goals:

1. Use Atomic Design Principles
1. Use KISS and DRY and make atomic commits

## Development & Production

### Development

1. Run the development server with `npm start`

### Deployment

1. Deploy the site with `npm run deploy`

## Archive

### Initial Project Creation

I decided to use React due to it's modularity and to get some more practice setting up a well structured React App.
It is very easy to deploy a React App as a static site and there are good tools and instructions on how to easily [publish it on Github Pages](https://create-react-app.dev/docs/deployment/#github-pages).

The project was setup with these 4 steps:

1. Run `npx create-react-app codecademy-enterprise-website`
1. Within the new folder add `"homepage": "https://ffrosch.github.io/codecademy-enterprise-website",` to `package.json`
1. Install `gh-pages` with `npm install --save gh-pages`
1. Add `"predeploy": "npm run build", "deploy": "gh-pages -d build",` to the `"scripts"` section in `package.json`
