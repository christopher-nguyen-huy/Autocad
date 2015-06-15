## Lines
- CMD: `L`
### Line 1:
- click start point
- put mouse in line direction
- type length
- rightclick/enter
- Done

### Architectural
- 50' = 600 units
- 50'6 = 50 feet 6 inches

### Refresh screen
- CMD: `rea`

### snap to end points
- CMD: `end`

### Line 2 polar:
- click start point
- put mouse in line direction
- type length
- tab, type angle
- rightclick/enter
- Done

### Line 3 absolute:
- start line CMD
- type `0,0` (x,y start coordonates)
- type `#25,25` (end coordinate # tells autocad it's absolute coordinates)


## Polylines
CMD: `Pline`

### Differecence with Lines
- multiple polylines forming a polygon = 1 object
- multiple lines forming a polygon = multiple objects

### Arcs
- Unlike lines, it can do Arcs
- Arcs are always tangent to the previous polyline section
- Switch to arcs using `A`
- Switch to lines using `L`

### Editing
- CMD: `Pedit`
	- Close: closes the polyline into a polygon with a line
	- Join: Combines lines and arcs into a polyline
		- Pick all the lines
		- press enter
		- press enter again
	- Vertex
		- Endpoints and Midpoints
		- Vertexes are the "endpoints"
		- Add, remove
		- Stretch: repositions the vertexe

## Circles
- CMD: `C`

### Default
- Click starting point
- Select radius

### By diameter
- click starting point
- click `d`
- punch in diameter

### 3 points
- type `3p`
- select first point
- select second point
- select third point

### 2 point
- type `2p`
- select first point
- select angle and diameter point

### Middle
- CMD: `mid`
- gives you the middle point of whichever object you hover over

### Tan Tan Radius
- CMD: `ttr`
- select first tangent
- select second tangent
- select radius

### Tan Tan Tan
- CMD: `ttt`
- select first tangent
- select second tangent
- select third tangent

### Trimming
- CMD: `trim`
- select objects
- press enter
- select objects to erase

## Arc
- CMD: `arc`
- Broken circles are arcs
- Arcs are by default drawn in counter clockwise direction
	- Use ctrl to switch direction

### Default
- select first point
- select mid point
- select end point

### Start center end
- Select the first point
- Select center of another concentric circle/arc
- select end point

#### Center
- CMD: `cen`
- Gives you center point snap of an arc or circle

### Start end angle
- Select start point
- select end point
- Select angle
	- ctrl to switch curve diretion

### Start end radius
- Select start point
- select end point
- type radius value
- Good for perfect pie shape with 2 radiuses

### Center start end
- Select center point
- Select start point
- Select end point (carefull direction)

### Continue
- Draws an arc tangent to another arc from its start/end point

## Polygons
- CMD: `polygon`
- Up to 1024 sides
- Basic:
	- Select number of sides, enter
	- Select select edge or center, enter
	- Select inscribed or circumscribed from circle
	- Select radius of circle enter
- Gives you a closed polyline with regular edges and angles

### inscribed vs circumscribed
- inscribed = from the vertex of the edges
- circumscribed = from the midpoint of the edges

## Rectangles
- CMD: `rec`
- Are like polygons, but only 4 sides

### Basics
- Select first point
- select second point

### Custom dimensions
- Select first point
- Input width, tab
- Input height, tab

### Chamfer
- type `c`, enter
- type delta1 chamfer value, enter
- type delta2 chamfer value, enter
- Run basic rectangle
- Not symetrical

### Fillet
- type `f`, enter
- type radius value, enter
- Run basic rectangle

### Elevation
- Puts stuff on a different Z plane

### Width
- type `w`, enter
- type width value, enter

## Ellipses
CMD: `EL`

### Basics
- Select center point, enter
- Selet width, enter
- Select height, enter

### Axis endpoint
- Select left and right points for width, enter
- Select height, enter

### Arc
- Do basic first
- Specify start point
- Specify end point

## Points/Nodes
- CMD: `po`
- Markers in the UCS
- Can be used to snap to them

### Basics
- Input `xcoord,ycoord`, enter

### Polyline snapping to points
- Start `pline`
- type `nod` (node)
- Play connect the dots

### Display
- CMD: `pdmode`
- Displays points in different stles
	- 1: invisible
	- 2: + sign
	- 3: x sign
- CMD: `pdsize`
- Sets the points to a certain size
- CMD: `ddptype`
- More styles

## Osnaps
- CMD: F3
- Settings: CMD: `OS`
- Select all, except:
	- Nearest
	- Parallel

### Overriding OSnaps
- When you type the correct osnap command (ex: mid, end, cen), the cursor will snap to that type of osnap only.
- Right-click menu also available

### Peculiar Osnaps
- Quadrants: North South East West
- Extension: Be slow and carefull, will save time on construction lines
- Insertion: Main point of an object
- Perpendicular: (per) Create line perpendicular to another line
- Apparent intersection: Like extension

## Move
- CMD: M
- Moves objects

## Offset
- CMD: O
- Starts new objets offset of a certain ditance

## Copy
- CMD: `CP`
