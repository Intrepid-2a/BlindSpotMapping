# Blind Spot Mapping

A short PsychoPy task where a marker is moved and resized until it can just _not_ be seen by one eye: when it is in the blind spot of that eye. This should be done _after_ color calibration (different repository in Intrepid-2a) since this task assumes the participant is wearing red-blue glasses and needs to read the calibrated colors for the participant such that the marker can be made invisible to the contralateral eye to begin with.

Use the arrow-keys to move the marker.

Use Q-W to in/decrease the height.

Use A-S to in/decrease the width.

The procedure starts with the left eye (green marker), and then does the right eye (red marker).

It stores both the left and right eye blind spots in `../data/mapping/` in a file for each eye called: `{participant}_{RH|LH}_blindspot_{#}.txt` filling in participant ID, hemisphere and the number of times the mapping procedure has been done. It also stores screenshots of the final stimuli as png's but otherwise the same file name.

