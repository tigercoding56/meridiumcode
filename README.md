MeseCode
========

A readable modding format for Minetest. Scripts are written in MeseCode, which is then converted into Lua.
The copyright of mesecode scripts, and any resulting Lua files, remains with their author.

Created by rubenwardy, license: GPL 3.0 or later

```
mod candy_gem

craftitem Candy Gem
  groups food=2
  eatable 5

node Candy Gen in Stone
  groups ground, cracky
  drops Candy Gem

script script_one.lua
```


Usage
-----

```Shell
# installed
$ sudo make install
$ mesecode.py path/to/file.mese output/directory

# or portable version
$ python mesecode.py path/to/file.mese output/directory
```
