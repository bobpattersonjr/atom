# Linux

Ubuntu LTS 12.04 64-bit is the recommended platform.

## Requirements

  * OS with 64-bit architecture
  * [node.js](http://nodejs.org/download/) v0.10.x
  * [npm](http://www.npmjs.org/) v1.4.x  
  * libgnome-keyring-dev `sudo apt-get install libgnome-keyring-dev` (refer to your distribution's manual on how to install packages if you are not on Debian or Ubuntu-based systems)
  * `npm config set python /usr/bin/python2 -g` to ensure that gyp uses Python 2

## Instructions

  ```sh
  git clone https://github.com/atom/atom
  cd atom
  script/build # Creates application at /tmp/atom-build/Atom
  sudo script/grunt install # Installs command to /usr/local/bin/atom
  script/grunt mkdeb # Generates a .deb package at /tmp/atom-build
  ```

## Troubleshooting
