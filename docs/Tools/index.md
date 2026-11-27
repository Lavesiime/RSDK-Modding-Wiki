# Tools

The Retro Engine uses a combination of common file formats (such as `.gif` for spritesheets and `.ogg` for music) and its own proprietary formats (such as its `.bin` files).

When a Retro Engine game is first installed, its data is all packaged into a single `.rsdk` file. This file contains all of the game's assets, and much be [extracted using external tools](../Guides/RetroED/ExtractDatapack) in order to access them for modding purposes.

Once extracted, a variety of tools can be used to view and edit the different types of assets. This page provides an overview of the most commonly used tools.

## [RetroED](RetroED/README.md)
An all-purpose tool suite for the Retro Engine. Used for working with all proprietary Retro Engine formats, including animations, scenes, and other internal assets.
- (should i manually list out every type it can edit? would it be better to list them in terms of "format"? this editor supports RSDK v1-v5, so that's a lot of stuff to list..)

## [GraphicsGale](GraphicsGale.md)
A sprite editor for editing `.gif` spritesheets.

## Audacity
An audio editor for modifying `.ogg` and `.wav` files.
