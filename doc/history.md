## 1.8-0.1.0
 * first version after the versions split
 * move js files to tools/js
 * use countType in protocol.json

## 0.4.0
 * add some basic (to be used for manual updating) protocol extractors
 * import protocol.json from node-minecraft-protocol for version 1.8 of minecraft

## 0.3.0
 * remove id indexing from biomes, blocks, entities, items and instruments : let users (for examples node-minecraft-data) provide their indexing (by id, name,...)

## 0.2.1
 * entities is now in the API

## 0.2.0
 * update blocks, entities, items and recipes enums with new wiki extractors
 * add entities displayName
 * add drops in blocks
 * add metadata variations in blocks and drops
 * update recipes with variations of blocks and items
 * amount -> count and meta -> metadata in recipes
 * reorganize and improve wiki extractors

## 0.1.1
 * some new wiki extractors : beginning of work for blocks, entities
 * fix some recipes
 * add entities.json file

## 0.1.0
 * add json schemas to check the enums schemas
 * use circle ci the check the enums schemas automatically
 * add docson documentation for the schemas
 * change the format of recipes
 * add doc/recipes.md

## 0.0.1

 * first version
 * enums in enums/
 * scripts to audit and generate the enums in bin/
 * support minecraft 1.8 with some missing data