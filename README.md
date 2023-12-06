# mobx-reactive2015-demo

[Original repository](https://github.com/mobxjs/mobx-reactive2015-demo.git)

[MST-based example history](https://github.com/mobxjs/mobx-state-tree/tree/master/packages/mst-example-boxes). This repo was pulled from [this commit](https://github.com/mobxjs/mobx-state-tree/commit/9fb09972b5836a72cec851c737bf7345dafcef7b) and augmented

Demo of MobX (formerly called Mobservable) on [ReactiveConf](https://www.youtube.com/watch?v=FEwLwiizlk0)

Simple drag & drop editor that uses [mobx](https://github.com/mweststrate/mobx) and React.
The slides can be found [here](https://docs.google.com/presentation/d/16hE-cxJ8C5XQVjql17krNAeYNF_9I3n3j13ho-KLWYU/edit#slide=id.p).

To interact with the application:

- Click to select.
- Boxes can be dragged around.
- Use the input box to rename stuff.
- CTRL + click to add new boxes. If there is an active selection an arrow will be added as well.
- use the tiny buttons in the bottom left to generate a bunch of random boxes and arrows, and to travel forward and backward in time.

### Run the example (requires Node v16, does not work on Node v18 or v20)

```
yarn
yarn start
open http://localhost:4000 # This used to be localhost:5000, but [that no longer works on Mac OS](https://stackoverflow.com/a/71634378)
```
