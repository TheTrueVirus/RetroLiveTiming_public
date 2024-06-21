# RetroLiveTiming for Formula 1

## Introduction
> [!Note]
> Well, this is my first app so I don't know what to write here exactly.
> Since the app is in alpha/beta or something else, this readme is not really helpful. I will get my head into it. So then, happy exploring! 😊

## Dependencies
This app needs F1MultiViewer to run. Download the F1MultiViewer <a href="https://multiviewer.app/download">here</a>
> [!Important]
> In order to use both apps, a paid <a href="https://www.formula1.com/de-de/subscribe-to-f1-tv">F1TV Pro subscription</a> is required!

## Installation
As for now, this app is only available as a portable version. Download the zip from the <a href="">latest releases</a>, unzip it into a folder and run it with the exe file.

## Main Features
This app features currently one window with 4 pages. Each page displays a different set of data.

### Page 1
Page 1 shows depending which session is running a set of timing data.

All three session tables have the same data:
  - Position
  - DriverNumber
  - DriverName
  - SectorTimes and Speeds
Differences of the sessions:
  - Practice / Qualifying:
      - Best Lap
      - SectorTimes and Speeds
      - LastLap
        - also shows if the driver has stopped, is retired, is knocked out of qualifying, is in pit or leaves the pit lane.
      - LapCount

  - Race:
      - Gap: time difference between the driver and the race leader
      - Int: time intervall between the driver and the driver in front
      - PitCount
   
At the top of all 3 different session types, it shows the overall best sector times and speed, switching between the value and the tla of the driver which has the best value in the topic. In the last lap column, it shows the best possible lap time, calculated by summing all 3 best sector times togehter.


### Page 2
Page 2 is currently in work. It normally shows a list of completed new lap times with the newest on top. At the bottom is a list of the best top 6 speeds and the top 6 speed trap values.
Since this data is not normally generated/provided, I have to manually iterate every completed lap so the list is not empty once the app is started while a session is running. This take a lot of work, so for now the page is empty and just showing "Page coming soon"

### Page 3
Page 3 shows the newest race control messages. The newest message is colored in magenta. At the bottom half of the screen is for now only the weather data. Once I got my head more into all the stuff, it will show a track map with an arrow displaying the wind direction and a line chart showing the weather data within a 3 hour range swichting between all the weather data list on the right.

### Page 4
Page 4 is empty for now. Later it displays a different version of page 1.
Different screens will also apear according to the session type (Practice, Qualifying and Race)


## TODO [Plans / Fixes / Future]
- [ ] Better file structure -> Minimizing and optimizing code, outsource code like functions and components to differnt files. / Better structure of css files (one file per page/component) / Better classification of elements
- [ ] get the session timer running
- [ ] Biggest todo: SETTINGS
- [ ] Create page 4
- [ ] Revise page 1 and 3
