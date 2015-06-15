# Eraser
- CMD: `Delete`
- CMD: `E`

## Basics:
- Select stuff
- Hit delete

## Unerase:
- CMD: `oops`

# Delete Duplicates
- CMD: `overkill`
- Removes duplicate lines above lines & merges polylines
- If ever there are ghost osnaps, there are probably duplicate lines stacked

# Move
CMD: `M`

## Basics
- Select objects, enter
- Select grab/displacement point
- Select destination point

## Options
- Can be ortho mode
- Can enter distance
- Can enter specific destination point

# Copy
- CMD: `CO`
- Like move command
- Leaves the original where it was

# Rotating
- CMD: `RO`

## Basics
- Select objects, enter
- Select pivot point
- Select angle (0deg starts right horizontal)

## By reference
- Select objects, enter
- Select `R` for reference
- Select line start
- Select line end

# Scaling
- CMD: `SC`

## Basics
- Select objects, enter
- Select reference point
- Select zoom factor, enter

## To make smaller
- Scale factor between 0 and 1

## Divide in 3
- Select a line
- Copy option
- Scale factor = 1/3

# Stretching
- CMD: `S`

## Basics
- Select objects, enter
- Select base point
- Select displacement point

## Theory
- You actually select vertices, and move them

## Circles and ellipses
- Cannot be stretched properly

# Offset
- CMD: `O`
- Usefull for:
 	- Concentric circles
	- Parallel lines
	- Parallel curves

## Basics
- Type distance, enter
- Select object to offset
- Put cursor on the side where you want the offset

## By point
- Select `T` (through)
- select object to offset
- Snap to a point

# Mirror
- CMD: `MI`
- Usefull for:
	- Symetrical objects
	- You only need to draw half of it!

## Basics
- Select objects
- Select first point of mirror line
- Select second point of mirror line
- Erase source objects yes/no no (deletes source of mirrored object)

## As rotation substitute
- Select object
- Select mid point of object as firt miror point
- Select mid point of object as second miror point
- Erase source objects yes/no yes

# Trim
- CMD: `TR`

## Basics
- Select the cutting line, enter
- Select the line to be cut

## Fence
- Select all objects, enter
- Type `f`
- Make polylines, anything that cuts through will be trimed

# Extend
- CMD: `EX`

## Basics
- Select a stopper line, enter
- Select other lines
    - These lines will extend to touch the stopper line

## Inverting
- Hold shift
- Trim becomes extend
- Extend becomes trim
- To not break workflow

# Fillet
- CMD: `F`
- Rounds corners

## Basics
- Type in r (radius),enter
- Type in radius value, enter
- Select first edge
- Select second edge

# Fillet
- CMD: `CHA`

## Basics
- Type in deta1, enter
- Type in deta2, enter
- Select first edge (delta1)
- Select second edge (delta2)

## Settings corners
- Set radius to 0

# Rectangular Array
- CMD: `AR`
- Selet Rectangular

## Basics
- Select objects, enter
- Start playing with parameters

## Grip edits
- Far ones determine how many in which direction
- Close ones determine spacing in which direction
- Origin is moving grab handle

# Polar Array
- CMD: `AR`
- Select Polar

## Basics
- Select object, enter
- Specify centerpoint of array, press enter

## Specifications
- # of items
- Angle between each items
- Angle of circle filled
- Rows: Concentric circles
- Rotate items: Items face same direction or centerpoint
- Direction: Spawn direction
- Base point: Grab point to move the entire array
- Associative: Off = cannot edit chairs as a group

# Path Array
- CMD: `AR`
- Select Path

## Basics
- CMD: `AR`
- Select object
- Select Path

## Specifications
- # of items
- Align: items face same direction or not
- Measure/Divide
    - Measure will space each item at a set distance
    - Divide will divide # of items along entire Path
- Rows: Concentric offset
- Rotate items: Items face same direction or centerpoint
- Direction: Spawn direction
- Base point: Grab point to move the entire array
- Associative: Off = cannot edit chairs as a group

# Copy Array
- CMD: `CP`
- Copy objects many times in the same line

## Basics
- Select objects, enter
- Select base point
- Type `A`, enter
- Type # of repitition, enter
- Type distance between each item, tab
- Type angle of propagation

## Fit mode
- Select objects, enter
- Select base point
- Type `F`, enter
- Select end point

# Object properties
- CMD: `Ctrl-1`
- Works like Visual Studio properties window
