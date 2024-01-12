### An interactive d3-js taxonomy

This repository contains a standalone implementation for an interactive taxonomy / hierarchical structure based on d3.js v6. The taxonomy has some pretty nice features:
- rearranging subtrees or single leaves
- deleting subtrees or single leaves
- renaming nodes
- changing the layout (horizontal / radial) as well as the width, depth and text properties of the d3 tree object
- importing / exporting a hierarchy in json format (see `a_taxonomy.json` for an example)

![](https://github.com/slvnwhrl/interactive-d3-taxonomy/demo.gif)

The code is contained in a single file: `interactive_d3_taxonomy.html`. I wrote the code a while ago and since it took me quite some time to get it working with all its features, I thought it's worth sharing... maybe it's helpful for someone to get started with some related project / code. Let me know if you run into any problems. :)