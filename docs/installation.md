---
id: installation
title: Installation
---

To easily try ReasonReact, we offer two solutions with different goals in mind.

## Bsb (No Server)

**Goals**: simplicity, control, traditional app with several html files.

**Prerequisites**: having `bsb` installed, through `npm install -g bs-platform`. Further installation instructions [here](http://bucklescript.github.io/bucklescript/Manual.html#_installation).

`bsb -init my-react-app -theme react`

BuckleScript's [bsb](http://bucklescript.github.io/bucklescript/Manual.html#_bucklescript_build_system_code_bsb_code) build system has an `init` command that generates a project template. The `react` theme offers a lightweight solution optimized for low learning overhead and ease of integration into an existing project.

It compiles to straighfoward JS files, so you can open `index.html` directly from the file system. No server needed.

## Reason Scripts (with Development Server)

**Goals**: single-page app (SPA), builds on best practices from create-react-app community.

[Reason-scripts](https://github.com/reasonml-community/reason-scripts) provides a familiar experience to the ReactJS users who are already familiar with [create-react-app](https://github.com/facebookincubator/create-react-app). It's an all-encompassing solution. However, if it's too heavy for your taste, try the first option above (bsb).

As with `create-react-app`, `reason-scripts` comes with a server and hotloading built in.
