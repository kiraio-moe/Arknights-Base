# Arknights Game Resources 

[Last updated on v24.2.21]

## Overview

This repository contains [Arknights](https://arknights.global "Arknights") game assets such as character [spine](http://en.esotericsoftware.com/ "Spine 2D") + Spine project, UI, etc. that usable to be used in many ways.

Checkout my other project on collecting [Blue Archive](https://bluearchive.nexon.com/home "Visit Blue Archive official website") game assets: [Schale-Archive](https://github.com/kiraio-moe/Schale-Archive "Schale-Archive")

## How to Properly Import Character to Spine Editor

- First, you **must** have Spine Editor v3.8.x because Arknights characters spine is produced in Spine Editor v.3.8.99.
- Create a new project.
- Delete the default skeleton in `Hierarchy` on the right.
- Click Spine logo on top left, then select `Import Data`.
- Select skeleton data (`.skel`) file. Uncheck `New Project` and select `Create a new skeleton`. Name it whatever you want then `Import`.
- After successfuly imported, click Spine logo and select `Texture Unpacker`. Select atlas (`.atlas`) file where the texture is located and set the output folder then `Import`.
- After imported, click `Images` in `Hierarchy`. Set the path on botttom right to where the unpacked texture is located.
- That's it, you have successfully import the character to Spine Editor.
- If you want to see the animations, click `SETUP` on top left then expand the `Animations` in `Hierarchy`. Click `little dot` on the left of animation name and click Play Backward `<` or Play Forward `>` in the `Dopesheet` on the bottom left.

## Disclaimer

The game assets in this repository is of course property and copyright of Hypergryph.

