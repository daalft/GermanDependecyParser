# GermanDependecyParser

## Test

This is an attempt at getting some dependencies for German after having failed to get any German Dependecy Parsers to work
out of the box.

The program uses the Stanford Parser with a German model and only computes the dependencies that are indicated
in the relmap.txt file.

The program does not have access to morphological information, and as such cannot perform morphological
checks for congruence etc.

The program might not work for all intents and purposes. For my purposes, it works well enough (identify the SUBJECT and 
ROOT relations).
