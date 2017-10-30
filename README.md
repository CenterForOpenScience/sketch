# sketch

Shared Sketch files for COS.

Requires Sketch>=47.

## Project structure

```
├── color-palettes  # Requires Sketch Palettes plugin
│  └── bootstrap.sketchpalette  # Bootstrap color palette used across COS products
├── libraries  # Library files. Add these in File / Add library...
│  └── COS_Common.sketch  # Common symbols used across products
├── osf  
│  └── ProjectOverview.sketch
|  └── ... more pages
|  ... reviews, preprints, etc. will follow same structure as osf
```

## Contributing

- **Mocking up a new feature?**
  1. Open the relevant sketch file, e.g. `osf/ProjectOverview.sketch`
    - If a sketch file doesn't exist for the page you are mocking up,
    create one.
  1. Create a new branch, e.g. `new-files-widget`.
  1. Do great work.
    - Be sure to add symbols to `libraries/common.sketch` when appropriate
    so that others can re-use them!
- **Adding symbols?**
  1. Open `libraries/common.sketch` and add your symbols.
  1. Before committing, make sure to run "Plugins/Symbol Organizer/Run
     Symbol Organizer" (Cmd+Option+Control+O)


## Required plugins

### [Icon Font](https://github.com/keremciu/sketch-iconfont)
This plugin helps you easily insert and manage icons from icon fonts - such as FontAwesome, Ion or Material Design Icons - in your Sketch designs. Make sure to follow the instructions on the linked font-bundle repository to install the fonts.

**NOTE**: The FontAwesome icon font can be installed with homebrew-cask:

```
brew cask install font-fontawesome
```

### [Sketch Palettes](https://github.com/andrewfiorillo/sketch-palettes)
A Sketch plugin for exporting and importing fill presets. It supports colors, gradients, and Pattern fills.

### [Symbol Organizer](https://github.com/sonburn/symbol-organizer)
Organize your symbols page, and layer list, alphabetically and into groupings determined by your symbol names.

## Recommended plugins

### [Dynamic Button 3.5](https://github.com/fuggfuggfugg/sketch-dynamic-button-3.5) (**Highly recommended**)
Automatically resize buttons to size of text with specified padding.

### [Sketch Measure](https://github.com/utom/sketch-measure) (**Highly recommended**)
Make it fun to create specs for developers and teammates.

### [Sketch Data Populator](https://github.com/preciousforever/sketch-data-populator) (**Highly recommended**)
We believe designers should work with meaningful and realistic data as early as possible in the design process for the following reasons...

### [Sketch Runner](http://sketchrunner.com/)
Runner helps you to get around Sketch quicker by giving you an intuitive interface to supercharge your daily workflow. Stop searching through your menu & start running commands directly from your keyboard.

### [Magic Presenter](http://magicsketch.io/presenter/)
With a single shortcut, you can put your artboards into presentable slides. No more switching between presentation tools and re-exporting assets when the content is updated.
