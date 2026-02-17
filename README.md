# mathCrossWordPuzzle

This program is free software; you can redistribute it and/or modify it under the terms and conditions of the GNU General Public License, version 3, as published by the Free Software Foundation.

This program is distributed in the hope it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

![alt text](https://github.com/QusaiHroub/mathCrossWordPuzzle/blob/master/image.PNG)

## Build

```bash
# Install Python, Ninja & Meson
# See also: https://mesonbuild.com/ for how to install on other OS
sudo apt-get install python3 ninja-build meson

# Setup and compile meson project
meson setup . ./out
meson compile -C out

# …the binary should be in ./out/src/
```
