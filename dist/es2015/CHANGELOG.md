# amCharts 4 Geo Data Changelog

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [4.0.18] - 2018-11-11

### Fixed
- Fixed map of Austria.

## [4.0.17] - 2018-11-11

### Fixed
- Refined areas of the world maps.

## [4.0.16] - 2018-11-07

### Fixed
- Updated some area names in Dominican Republic municipal maps.

## [4.0.15] - 2018-10-30

### Fixed
- South Korean maps had some areas missing.

## [4.0.14] - 2018-10-29

### Changed
- IMPORTANT! The area IDids have been changed in U.S. County maps (`geodata/regions/usa`) to support latest 5-digit FIPS standard (XXYYY where XX is number code of the state and YYY is code for the county).

## [4.0.13] - 2018-10-01

### Fixed
- Fixed map of Azerbaijan.

## [4.0.12] - 2018-09-28

### Added
- U.S. county maps added to sub-folder `/region/usa/`. In JavaScript these maps are available in global variable `am4geodata_region_usa_*`, e.g. `am4geodata_region_usa_akLow` for a file `geodata/region/usa/akLow.js`.

### Fixed
- Added "name" attributes to polygons in `continents*` maps.

## [4.0.11] - 2018-09-18

### Added
- New maps: Ecuador, Egypt, El Salvador, Estonia, Eswatini (Swaziland), Faroe Islands, Fiji (East and West), Finland, French Guiana, Georgia (2 versions), Greece, Greenland, Guinea, Honduras, Hong Kong, Hungary, Iceland, Ireland, Italy.

### Removed
- `usa2*` maps that were invalid. Use `usaAlbers*` instead.

## [4.0.10] - 2018-09-01

### Added
- New maps: Bermuda, Israel (two versions: w/ Palestine subdivisions and Palestine as a single unit), Palestine, Cambodia, Cameroon, Cape Verdi, Central African Republic, Chad, Channel Islands, Chile, Colombia, Congo, Congo (Democratic Republic), Costa Rica, Croatia, Czech Republic, Denmark, Djibouti, Dominican Republic, Dominican Republic (Municipalities).

## [4.0.9] - 2018-08-13

### Added
- New maps: Bahrain, Bangladesh, Belarus, Belgium, Belize, Bhutan, Bolivia, Botswana, Brunei Darussalam, Bulgaria, Burkina Faso, Burundi.

### Fixed
- Fixed wrong id for Agdas district on map of Azerbaijan.

## [4.0.8] - 2018-08-08

### Added
- New maps: Albania, Algeria, Andorra, Angola, Argentina, Armenia, Austria, Azerbaijan.

### Fixed
- Antarctica was mishaped in worldLow.

## [4.0.7] - 2018-07-29

### Added
- New maps: World map (India version), United Nations World Regions map, United Kindom, United Kindom Counties, India.

### Changed
- Increased detail of World map (high-detail version)

## [4.0.6] - 2018-07-26

### Added
- New maps: Russia, Russia w/ Crimea, Spain, Spain w/ Provinces

## [4.0.5] - 2018-07-25

### Added
- New maps: Australia, Brazil, Canada, China, Japan, France Departments, Germany, Mexico, South Korea.

## [4.0.4] - 2018-07-19

### Fixed
- USA map was broken

### Added
- New maps: France, USA (Albers projection)

## [4.0.3] - 2018-05-10

### Added
- Added this `CHANGELOG.md`.