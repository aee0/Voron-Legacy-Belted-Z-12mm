# Voron-Legacy-Belted-Z-12mm
Collection of my attempts to make a triple-belted-Z version of a Voron Legacy with parts I had on-hand. 

See the original Voron Legacy here: https://github.com/VoronDesign/Voron-Legacy

Some notes about this modification:
- Uses 12mm rods for Z instead of 8mm
- Uses 20T toothed idlers that go into the upper Z-rod holders. The size I uesd was 6mm wide (belt), 5mm bore for M5 bolt.
- Uses 20T pulleys, same ones as the Legacy uses for the A/B motors. 
- Uses heatset inserts in the upper bearing holders, which is used to tension the z-belts by putting an M3 bolt/screw through the bottom of the lower-bearing holder and threading into the heated insert.
- Uses some Trident bed parts, mainly the piece that bolts to the 370 mm 2020 extrusion with the GE5C bearing inside it (see the Voron Trident CAD or manual for that bit).
- This arrangement loses around 20mm Y-travel, but it suited me because the 8mm rods I had on hand were 20mm shorter than the Voron Legacy spec.

**WARNING:** Because the bed is driven directly by the motors without gearing, it will drop under its own weight when the motors are disengaged. This can make for a bit of a scare if you do a SAVE_CONFIG or FIRMWARE_RESTART when the bed is raised! In the future, I'm considering either using a "Keyback"-like system as often done for the Voron Switchwire or seeing if it's possible to adapt the Voron 2.4 Z-drive assembly in place of what I currently have. However, I've not tried either of those yet. 
