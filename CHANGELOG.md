# Changelog

## v0.1.0
#### Added
- Import any feature type from OSM
- Height computation for buildings using metadata keys "height", and if not present, then "floors"

#### Changed
- No bottom-left point needed to move imported OSM region to origin, uses given bounds in OSM file

#### Fixed
- Using double precision to read lat/long data from OSM files, fixed jagged lines bug
