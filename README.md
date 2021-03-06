# scratch-blocks

This is a fork from the MIT LLK Scratch Blocks, which in turn is based on Blockly.
At the moment there are no plans to do any significant changes to this code base. All changes are listed here:

* Add to the repository the blockly compressed build output 
    * `blockly_compressed_horizontal.js`
    * `blockly_compressed_vertical.js` 
    * `blockly_uncompressed_horizontal.js`
    * `blockly_uncompressed_vertical.js`
    * `blocks_compressed.js`
    * `blocks_compressed_horizontal.js`
    * `blocks_compressed_vertical.js`
* At the moment to build blockly correctly we need to copy the `msg/json/` directory back from [d65c27465272b898733af889b331278f01c365c9](https://github.com/LLK/scratch-blocks/tree/d65c27465272b898733af889b331278f01c365c9). This hasn't been added to the repository yet as we are waiting for [#685](https://github.com/LLK/scratch-blocks/issues/685) to be resolved.

The rest of the original readme can be found below.


#### Scratch Blocks is a library for building creative computing interfaces.
[![Build Status](https://travis-ci.org/LLK/scratch-blocks.svg?branch=develop)](https://travis-ci.org/LLK/scratch-blocks)
[![Dependency Status](https://david-dm.org/LLK/scratch-blocks.svg)](https://david-dm.org/LLK/scratch-blocks)
[![devDependency Status](https://david-dm.org/LLK/scratch-blocks/dev-status.svg)](https://david-dm.org/LLK/scratch-blocks#info=devDependencies)

![](https://cloud.githubusercontent.com/assets/747641/15227351/c37c09da-1854-11e6-8dc7-9a298f2b1f01.jpg)

## Introduction
Scratch Blocks is a fork of Google's [Blockly](https://github.com/google/blockly) project that provides a design specification and codebase for building creative computing interfaces. Together with the [Scratch Virtual Machine (VM)](https://github.com/LLK/scratch-vm) this codebase allows for the rapid design and development of visual programming interfaces.

*This project is in active development and should be considered a "developer preview" at this time.*

## Two Types of Blocks

![](https://cloud.githubusercontent.com/assets/747641/15255731/dad4d028-190b-11e6-9c16-8df7445adc96.png)

Scratch Blocks brings together two different programming "grammars" that the Scratch Team has designed and continued to refine over the past decade. The standard [Scratch](https://scratch.mit.edu) grammar uses blocks that snap together vertically, much like LEGO bricks. For our [ScratchJr](https://scratchjr.org) software, intended for younger children, we developed blocks that are labelled with icons rather than words, and snap together horizontally rather than vertically. We have found that the horizontal grammar is not only friendlier for beginning programmers but also better suited for devices with small screens.

*Only the horizontal grammar is available for preview at this time. The vertical grammar is in the design phase and will be added to the project over the next several months.*

## Documentation
The "getting started" guide including [FAQ](https://scratch.mit.edu/developers#faq) and [design documentation](https://github.com/LLK/scratch-blocks/wiki/Design) can be found in the [wiki](https://github.com/LLK/scratch-blocks/wiki).

## Donate
We provide [Scratch](https://scratch.mit.edu) free of charge, and want to keep it that way! Please consider making a [donation](https://secure.donationpay.org/scratchfoundation/) to support our continued engineering, design, community, and resource development efforts. Donations of any size are appreciated. Thank you!
