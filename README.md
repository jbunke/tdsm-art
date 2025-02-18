# Art for *Top Down Sprite Maker*

This repository is intended to house the sprite assets for [*Top Down Sprite Maker*](https://github.com/jbunke/tdsm), my pixel art character creation tool. It contains finished assets as well as project workspaces with content that is still work-in-progress.

Assets are made in [*Stipple Effect*](https://github.com/stipple-effect/stipple-effect), a scriptable pixel art editor that I developed.

Contributions from enthusiastic pixel artists are welcome -- please see the [**Contributing** section below](#contributing).

***Happy pixel pushing!***

<!-- TODO - replace with original work generated in TDSM -->
![](./pokemon/study/all-sprites.gif)

## Folder structure

Each folder in the root is associated with a **sprite style**. This is the general folder structure within each sprite style folder:

* `bases` -- Contains finished base sprites and *Stipple Effect* projects that act as workspaces for work-in-progress sprites. **Base sprites** are customization elements drawn in a color-agnostic way that are modified at runtime by *TDSM* based on user customization input.
  * *`layer-name`* -- Sprites inside `bases` are organized in folders according to their layer. Common layer names may include `head`, `body`, `eyes`, `torso`, `hair-back`, etc.
  * `palettes` -- *Stipple Effect* color palettes; generally replacement palettes for different sprite components such as skin, hair, eyes, or clothes
* `scripts` -- *Stipple Effect* scripts to assist in preparing base sprites, such as color replacements, UV mappings, animating texture atlases, etc.
* `study` -- References. These files do not end up as *TDSM* resources.

## File types

An overview of the types of files found in the repo

* **PNG images** `.png` -- Finished base assets are saved as PNG images
* **_Stipple Effect_ projects** `.stip` -- Workspaces and work-in-progress
* **_Stipple Effect_ scripts** `.ses` -- Auxiliary scripts to automate tasks
* **_Stipple Effect_ palettes** `.stippal` -- [**\[ Example use case \]**]() <!-- TODO -->

## Contributing

<!-- TODO, _contrib folders (at root, in layer folders) -->

[**\[ Contribution Guide \]**]()

## To-Do List

<!-- TODO - link -->
If you want to contribute but are unsure of where to start, check out the [to-do list](). This is the list of high-priority sprite styles, animations, or customization options that need to be drawn.
