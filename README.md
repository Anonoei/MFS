# MFS
 Modular Filament Shelf

 ![image](https://github.com/user-attachments/assets/8f0951a1-3db9-40e6-ba95-9b685288a816)

## Features
 - Expandable, just print more sides
 - Optionally secured with bolts
 - Fits spools and spool boxes

## BOM (per full side)
 All hardware is optional (except rods), and helps secure the pieces together
- 4x 5/16" rods, length by preference, designed around 1000mm
- 18x M3 heatsets
- 8x M3 nuts
- An M3 bolt for each fastner (26x)

### Breakdown
 - M3 heatsets (voron spec)
   - 18x total
     - rod-joint (x4)
       - 2x vertical -> rod-joint
       - 2x horizontal -> rod-joint
     - rod-joint foot (x2)
       - 2x foot -> rod-joint
     - horizontal (x2)
       - 1x horizontal left -> right
 - M3 nuts
   - 8x total
     - per rod (x4)
       - 2x, rod-joint -> rod

## Assembly
 The file number at the end indicates quantity for **one** shelf side, with two heights
 - `rod-joint` (x4): Corner pieces that also connect the `vertical-joint` and `horizontal-joint`
   - Each piece that connects to the `rod-joints` can be secured with 2x M3 bolts, and 2x M3 heatsets
   - Inside the slot, M3 nuts can be pressed in to use a bolt to secure the rod
     - there are 2x holes to allow two rods to be inserted and the shelf expanded
 - `vertical-joint` [top & bottom] (x2): Connects `rod-joints` vertically
   - `top` (1x female 1x male slot) can take 2x heatsets to lock it to bottom
   - Both are are secured using M3 bolts to M3 heatsets on `rod-joint`
 - `horizontal-joint` [left & right] (x2): Connects `rod-joints` horizontally
   - `right` (2x male) can take 1x heatset to lock it to left
   - Both are secured using M3 bolts to M3 heatsets on `rod-joint`
 - `foot` (x2): Bottom piece to ensure open spools don't touch the ground
   - Each foot is secured using M3 bolts to M3 heatsets on `rod-joint`

## Print settings
 - Layer height: 0.2
 - Nozzle: 0.4
 - Material: PLA
