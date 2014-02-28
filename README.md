# Potree Converter

## Changes

* Added support for las files. <br>
Previous loader must be reimplemented. <br>
<b>Only las files can be converted at the moment</b>

## Usage

Converts las files to the potree file format.


    # pointDensity:		specifies the distance between points at root level. Each subsequent level has half the point density from the previous level
    # maxRecursions:	number of levels
    PotreeConverter <sourcePath> <targetDir> <pointDensity> <maxRecursions>
    
    # example
    PotreeConverter C:/pointclouds/pointcloud.las C:/pointclouds/converted 1.0 5
