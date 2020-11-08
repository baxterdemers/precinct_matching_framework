# precinct_matching_framework

This project is intended to help speed up to process of matching similar precinct names (e.g. `LEHIGH TWP DIST PENNSVILLE` to `LEHIGH District PENN`) in a way that is self-documenting and easy to reproduce. 

BEFORE using this framework

1. Do sanity check validation on the election results
2. Do a statewide check to confirm that there are fields for most counties that match up 

Goals:

1. Improve iteration speed of County Matches
2. Isolate changes to a particluar county to enable parallel data processing.
