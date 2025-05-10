# ClassChangeEdit
Engage code editing
Done!  
Levels are not reset when changing classes.  
Interval levels are not considered when calculating ability of units.  
If the original class before changing is **a basic class, or a special class with the level of the unit <20**, and the target class is an advanced one, the level of the unit is set to 20 after the class change.  
Prevent units from changing class from **advanced ones, or special class with level>20** to basic ones.  
Prevent units from changing to the same class with the same weapon.  
When changing the class, if the unit is already at the max level, they learn the class skill immediately