# Channel-4-EPG
XML EPG for Channel 4 TV channels

## Overview

This repository contains the XML EPG (Electronic Program Guide) for Channel 4 TV channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/Channel-4-EPG/refs/heads/main/c4.xml

## Features

- XML formatted EPG for Channel 4 TV channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/Channel-4-EPG/refs/heads/main/c4.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/Channel-4-EPG/refs/heads/main/c4.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
| tvg-id | Channel Name  |
|--------|---------------|
| C4     | Channel 4     |
| E4     | E4            |
| M4     | More 4        |
| F4     | Film 4        |
| 4S     | 4Seven        |
| 4M     | E4 Extra      |
