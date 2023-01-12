# I DID IT!!

## Main Project(s)

### Partitioned Array | Managed Partitioned Array / File Context Managed Partitioned Array [Manager]

Partitioned Array Library Repo: https://github.com/ZeroPivot/partitioned_array

* README: https://github.com/ZeroPivot/partitioned_array#readme
* YARD Documentation: https://midscore.io/partitioned_array_library/doc/index.html

### Usage
* Installation

`git clone https://github.com/ZeroPivot/partitioned_array.git`

* In Ruby:

`require 'lib/file_context_managed_partitioned_array_manager'`

* Data structures available:

```ruby
FileContextManagedPartitionedArrayManager
FileContextManagedPartitionedArray
ManagedPartitionedArray
PartitionedArray
```

* "Inheritance Tree"

`FileContextManagedPartitonedArrayManager.FileContextManagedPartitionedArray.(ManagedPartitionedArray < PartitionedArray)`

* Example:

```ruby
a = FileContextManagedPartitionedArrayManager.new
a.database_table("database", "table").get(0) # Resembles the "inheritance" tree in terms of object calls, and ManagedPartitionedArray < PartitionedArray implies that ManagedPartitionedArray inherits from PartitionedArray, and MPA < PA is being called with get(0)
```

### Note

A rubygem will be available at some point, or not--depending upon time. For the time being, cloning and requiring whichever parts of the partitioned array you want works fine. And an update is as easy as a `git pull` in the same directory. Rubygems are honestly a hassle and all they really are for is making access faster and resolving directories, to put it into a single name you can require.

At the time, I would suggest just requiring 'file_context_managed_partitioned_array_manager' and all those data structures become available; the ones higher up the heirarchy depending upon the ones below them. That is, they are independent libraries on their own, but the FileContextManagedPartitionedArrayManager was the goal of this data structure algorithm project.

## Legacy Released Projects

TBA/Work In Progress

## Game and Game Theory Algorithma

TBA/Work in Progress

## Bio & Info


I am a formally trained Computer Scientist, Software Engineer & Mathematician, as well as partially self-taught Artist--who focuses on Algorithms primarily written in the Ruby Programming Language

I am also starting a long-term game project in DragonRuby, and transitioning to becoming a full-time Indie Game Developer, doing the code and assets myself, making what music I can and buying assets to test the BashAsset engine at a more rapid pace

I work often with Server Backends, Ruby, The Linden Scripting Language, C/C++, and now, Game Development in DragonRuby

📫 How to reach me: eigenfruit@gmail.com, wolf.on.twitter@gmail.com, aritywolf@outlook.com


📲 Telegram: https://t.me/aritywolf


📲 Discord: ArityWolf#0001


🐦 Twitter: https://twitter.com/SimulWolf


🐦 Organization Twitter: https://twitter.com/Midscore_io



🖼️ Gallery: https://aritywolf.net


🗣️🎭🎨🖼️ "Actors: Computer Science Rockstars" (webcomic): https://compscirockstars.net



🔢 Organization Homepage/URL / API Backend Server / 🏫 Landing Site (hudl.ink): https://midscore.io


🚂 BashAsset Engine Builds: https://hudl.ink/bashasset_eng

Organization: https://midscore.io

HUDlink API: https://hudl.ink


💬 Ask me about Ruby, Crystal, C, Javascript LSL, Nginx, Perl, Php, JS, ...


## Etc.

**I am now calling the partitioned array platform agnostic**

**Updated the readme file for the Managed Partitioned Array/Partitioned Array, there are bits and pieces on how to go about using it. If you need help or are curious, I'm but a DM away**


## Focused Project
https://github.com/ZeroPivot/partitioned_array

Particularly: https://github.com/ZeroPivot/partitioned_array/blob/master/lib/managed_partitioned_array.rb

Long term project to use this managed partitioned array on:

* The basic array of hashes data structure that cen flexibly store any kind of json related data
* Translating/Porting the ManagedPartitionedArray/PartitionedArray )https://github.com/ZeroPivot/partitioned_array, https://github.com/ZeroPivot/partitioned_array/blob/master/lib/managed_partitioned_array.rb) to PYTHON. 

Long term project away from 100% ruby is porting every aspect of the array to Python - 10.5.2022 - 5:58PM


## Update 10.1.2022 - 2:25PM
ManagedPartitionedArray v1.2.8
* Fixed a bug through regression. Bug arose out of adding more code and not taking certain lines of code into account (`managed_partitioned_array.rb`)

## Update 9.27.2022 - 10:34am
* Fixed allocation bugs in partitioned array; it it now working as intended!

## Update 9.26.2022 - 3:46AM
Worked a bit to understand *.github.io and now have a website on github! It is still a WIP, but you can see it here: https://ZeroPivot.github.io
* TODO: Port my basic flat file blogging system to github.io

## Update 9.25.2022
Most of my activity in the past has been directed towards the Partitioned_Array repository, and within lib, managed_partitioned_array.rb. 🌠

# Milestone 9.25.2022
Several days back I completed a project that took me since 2011 to accomplish. That is, (https://github.com/ZeroPivot/partitioned_array)partitioned_array. It is not yet fully documented but the theory of it is all there if you'd like to 🌠

At a basic level, ArrayOfHashes explains the theory of it in a full fledged ruby array that allocates up to infnity, and allows you to do things to arbitrary locations of the array. Partitioned Array is stricter and safer, and the essential data structure is an array of hashes. That is, ManagedPartitionedArray (partititioned_array repo) follows the array of hashes data structure in its internals, but with several lines of code and a change of logic, perhaps by a class inheritance, you could make  the partitioned array function however you want in terms of a data structure.🌠

TODO: Create documentation for managed partitioned array (https://github.com/ZeroPivot/partitioned_array/blob/master/lib/managed_partitioned_array.rb) and the main, https://github.com/ZeroPivot/partitioned_array/ 🌠
