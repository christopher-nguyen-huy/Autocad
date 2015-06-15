# Creating
- CMD: `block`
- Create
- Select Name
- Select Base Point
- Select Objects

## Export
- CMD: `wblock`

## Layers
- Blocks take on the properties of a layer they're on
- Create them on layer 0
- Then move them to the correct layer

# Inserting
- CMD: `I`
- Use Dropdown if block is already in file
- Browse to file if not in current file

# Editing
- If you edit a block, every copy of it will update

## Block editor
- Background is different
- When done, close block editor

## In place
- Everything else is still selectable, but not editable

# Attributed Blocks
- Mostly text blocks
- Meta data for Blocks
	- Part number
	- Manufacturer
	- Name
- Double click block to get attribute window
- Ctrl-click block field to edit just that attribute

## Editing
- Tag: variable name
- Prompt: prompt message to get data
- Default: placeholder text

## Attribute definition
- Hit Attribute Definition
- Insert Tag, Prompt, Default values
- Hit OK
- Place item wherever

## Attribute Order
- Right-click object -> attribute Order
- Send Up
- CMD: `battman` (block attribute manager)
- Hit sync

## Enhanced Attribute editor
- Double click an attribute of a block

# Exploding
- Create a new block from an old block
- Makes a block its components
- Makes polylines/polygons individual sections

## Basics
- CMD: `x`
- Select object, enter
- Start editing

## Text blocks
- Exploding text blocks converts values to tag names (back to definition mode)
- CMD: `burst`
- Burst will keep the text values of each attribute
	- Use it to pull out data from a text block

# Dynamic Blocks
- ex: doors of different lengths
- Investigate
