# How To Contribute to UIForge

If you want to contribute to UIForge, you can help the project by contributing to IconsDB.

## IconsDB

IconsDB is split into two files; `iconsdb.lua` and `iconsdb-prod.json`. The first one. `iconsdb.lua` is the file were you should be making changes, it is the readable version of `iconsdb-prod.json` and will be converted to JSON and overwite `iconsdb-prod` eventually. Do __NOT__ make commits to `iconsdb-prod.json`, they will be denied as the file will be overwriten anyway. `iconsdb-prod` will is overwritten regularly with changes from `iconsdb.lua`. Feel free to contribute to `iconsdb.lua` with keywords, groups/group alts, or fix typos in the database. If you make changes to icon entries themselves, you should make sure any newly uploaded icons are the correct size (typically 1024x1024), #FFFFFF in colour, and have [bleeding pixels](https://rbxxaxa.github.io/chipng/). Details on the format of icons are given in the file.

### IconsDB Structure

...