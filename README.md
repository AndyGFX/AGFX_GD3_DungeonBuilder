# Godot 3.2 Dungeon builder

 Spelunky inspired dungeon cell builder with option to create connected cells fromused defined side:
 - from TOP
 - from LEFT
 - from RIGHT
 - from BOTTOM


- ## DungeonBuilder
    - class: `ProceduralDungeon`
        - properties:
            - width
            - height
            - buildeMode
            - add extended cell
            - extended cell probability
            - connect extended cell
        - method:
            - xyz.new(width,height)
            - xyz.Build()
            - xyz.Reset()            
        - result:
            - is stored in 2D array


``` java
        class DungeonCell:
	        var up:int = eSideType.EXIT
	        var right:int = eSideType.EXIT
	        var down:int = eSideType.EXIT
	        var left:int = eSideType.EXIT
	        var visited:int = 0
	        var cellType:int = eCellType.UNUSED_CELL
	        var nextCell:Vector2 = Vector2(0,0)
	        var currentCell:Vector2 = Vector2(0,0)
	        var prevCell:Vector2 = Vector2(0,0)
	        var userData:Dictionary = {}
```
# Examples

![Alt text](Screenshots/Godot_v3.2-stable_win64_2020-02-23_20-56-32.png?raw=true "PREVIEW") 
![Alt text](Screenshots/Godot_v3.2-stable_win64_2020-02-23_20-56-49.png?raw=true "PREVIEW") 
![Alt text](Screenshots/Godot_v3.2-stable_win64_2020-02-23_20-57-24.png?raw=true "PREVIEW")

RED -  unused cell
GREEN - main dungeon cells
BLUE - randomly added extended cells

# Screenshots

                    
