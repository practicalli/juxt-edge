# juxt-edge

A draft landing page for the JUXT edge project

## Overview

A single page application written in ClojureScript (with figwheel-main, reagent and Bulma.io) as a starting point for the project.

The [bulma launch page video](https://scrimba.com/p/pV5eHk/cvrwyfR) was used as inspiration for this design.

## Development

### Spacemacs

Open the file `src/juxt_edge/core.cljs`

`, "` or `M-RET "` to start the REPL using `cider-jack-in-clojurescript`

Select `figwheel-main` when prompted for the build tool (in a helm menu popup)

Enter `dev` when prompted for the build name (in the mini-buffer)


### Run in a terminal window

To get an interactive development environment run:

    lein fig:build

This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files:

    lein clean

To create a production build run:

    lein clean
    lein fig:min


## License

Copyright © 2019 jr0cket

Distributed under the Creative Commons Attribution Share-Alike 4.0 International
