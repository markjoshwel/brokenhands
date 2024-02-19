# brokenhands

a six-region hand detector for use with a certain sliding and jumping hand rhythm game.  
for use with [4yn's](https://github.com/4yn)
[slidershim/brokenithm](https://github.com/4yn/slidershim). inspired by [logchan/chuni-hands](https://github.com/logchan/chuni-hands).

- [installation](#installation)
- [usage](#usage)
  - [running](#running)
  - [configuration](#configuration)
- [technical details](#technical-details)
- [licence](#licence)

> why not just use chuni-hands?

1. chuni-hands uses opencv, which can be quite cpu-intensive. brokenhands captures
frames from the slider's camera, averages pixels user-defined regions and then
detects changes in the average pixel values to determine if a hand is present in
a region.

2. chuni-hands had zero documentation and i had no idea how to get it working with chun*thm. (i couldn't find/get the chuniio.dll to work which is a skill issue on my part :p)

3. literally nobody on the surface web has any information on how to use chuni-hands. most i could find was a few reddit posts and a bilibili video. who knows, maybe an obscure d*scord server has people who know how to use it, but i don't have the time to scour for presumably invite-only servers for something i just want to play now.

4. the sensing ranges in chuni-hands are not user-configurable. i want to be able to change the region sizes to my liking.

> really? python?

i was going to write this in rust at first, but in any case you would be restricted by the frame rate of the camera. python is good enough, for now.

## installation

TODO

## usage

TODO

### running

TODO

### configuration

TODO

## technical details

> so even after i eventually stop working on this, this code doesn't become a complete black box

TODO

## licence

brokenhands is licensed under the GNU General Public License v3.0, or any later version. see [LICENCE.md](LICENCE.md), or <https://www.gnu.org/licenses>.

```text
brokenhands: a six-region hand detector for use with a certain sliding and jumping hand rhythm game.
Copyright (C) 2024  Mark Joshwel <mark@joshwel.co>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
