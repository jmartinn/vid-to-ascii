# Video to ASCII Converter (C++)

This GitHub repository hosts a C++ program that transforms live video feeds or video files into captivating ASCII art in real-time. It harnesses the capabilities of the OpenCV library to manage video input and conduct video-to-text transformations.

## Table of Contents

1. [Features](#features)
2. [Dependencies](#dependencies)
3. [Building and Running](#building-and-running)
4. [Usage](#usage)

## Features

- Real-time video-to-ASCII conversion
- Adjustable ASCII character set and resolution
- Easily customizable to suit your needs

## Dependencies

This project depends on the following libraries:

- [OpenCV](https://opencv.org/) (>= 4.0)

## Building and Running

### MacOS

1. Install OpenCV and set up the environment.
2. If you are using vim edit the compile_commands.json. Find the path of opencv and change with the path in compile_commands.json 
3. Modify the opencv path in build.sh
4. Modify the opencv libraries path in build.sh
5. Give permission to build.sh by:<br />
      $ chmod +x build.sh
6. Run in terminal:<br />
      $ ./build.sh

## Usage

1. Edit the path of video in main.cpp
2. Run in terminal: <br />
      $ ./build.sh
