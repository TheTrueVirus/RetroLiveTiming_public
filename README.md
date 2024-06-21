<h1 align="center">
  <br>
  <img src="https://github.com/TheTrueVirus/RetroLiveTiming_public/assets/86475165/1550b2a9-ebae-4a35-b4d9-97b281c5415b" width="150">
  <br>
  <br>
  <b>RetroLiveTiming for F1</b>
</h1>

<p align="center">
  Retro LiveTiming is an app made to display formula 1 live timing statistics in a layout style the teams have in they're garages and on the pitwall.<br>
  This app uses the api of <a href="https://multiviewer.app/download">F1MuliViewer</a> to fetch data off of archived sessions or live sessions of Formula1-Races, Qualifying or Practice-Sessions.<br>
  <br>
  The goal to achieve is a fully functional app that can display different layouts of different years with the possibility for the user to customize as much as possible.<br>
</p>
<!--   <span align="left">For example:</span>
  <ul>
    <li>Color Customization</li>
    <li>Selectable Font-Family and automatic scaling</li>
    <li>Possibility to customize and own layout</li>
    <li>Color Customization</li>
    <li>Color Customization</li>
    <li>Color Customization</li>
  </ul> -->


## Dependencies
This app needs F1MultiViewer to run. Download the F1MultiViewer <a href="https://multiviewer.app/download">here</a>
> [!Important]
> In order to use both apps (or at least MultiViewer), a paid <a href="https://www.formula1.com/de-de/subscribe-to-f1-tv">F1TV Pro subscription</a> is required!

## Usage
As for now, this app is only available as a portable version for Windows. Download the zip from the <a href="">latest releases</a>, unzip it into a folder and run it with the exe file.

## Features
> [!NOTE]
> The first early access versions are a "nearly identical copy" of the official Formula 1 documentation from 2007. Functional requests will be taken into account as soon as this is completed and running stable.

This app features currently one main window with 4 pages. Each page displays a different set of data.

### **Page 1**
  
  This is the main page. Depending which session is currently playing, a different layout is displayed.

  - **Practice**
 
    ![image]()
    `soon`

    During practice, the layout in the above picture is displayed. Each column represents different data:
      - Current Position
      - Racing or Car Number
      - Last Name of the Driver
      - Best Lap Time
      - Last `Sector 1 (Intermediate 1)` time
      - Last `Intermediate 1 Speed` [taken as soon as the driver passes the `Intermediate 1` line]
      - Last `Sector 2 (Intermediate 2)` time
      - Last `Intermediate 2 Speed` [taken as soon as the driver passes the `Intermediate 2` line]
      - Last `Sector 3 (Finish Line)` time
      - Last `Finish Line Speed` [taken as soon as the driver passes the `Start/Finish Line`]
      - Last Lap Time
        - This column also shows if the driver is in the pits [`IN PIT`], leaves the pitlane [`PIT OUT`] or has stopped on track [`STOPPED`]
      - Lap Count
   
      The header of the timing table will show information as followed:
      - a title `BEST LAP` above the column displaying the best lap of the driver.
      - above all 3 sector and speed columns, the overall best sector time and achieved speed is displayed, changing all 10 seconds between the value and the Tla [`Three letter abbreviation`] of the respective driver.
      - above the column displaying the last lap, the possible best lap time will show in yellow, calculated by summing all 3 best sector times together.
      
  - **Qualifying**

    ![image]()
    `soon`

    During qualifying, the layout in the above picture is displayed. Each column represents different data:
      - Current Position
      - Racing or Car Number
      - Last Name of the Driver
      - Best Lap Time
      - Best `Sector 1 (Intermediate 1)` time
      - Best `Intermediate 1 Speed` [taken as soon as the driver passes the `Intermediate 1` line]
      - Best `Sector 2 (Intermediate 2)` time
      - Best `Intermediate 2 Speed` [taken as soon as the driver passes the `Intermediate 2` line]
      - Best `Sector 3 (Finish Line)` time
      - Best `Finish Line Speed` [taken as soon as the driver passes the `Start/Finish Line`]
      - Last Lap Time
        - This column also shows if the driver is in the pits [`IN PIT`], leaves the pitlane [`PIT OUT`] or has been knocked out of qualifying [`KO`]
      - Lap Count

    - During the qualifying:<br>
      drivers at risk of getting knocked out in the current stage of qualifying (Q1 and Q2) will have they're racing number marked in red.<br>
      Has a qualifying session finished, all drivers that have been knocked out will get displayed gray. The timings will stand.<br>
      For drivers who passed the session and are eligible for the next session will get they're timings deleted and shown into number order.



  - **Race or Sprint**

    ![image](https://github.com/TheTrueVirus/RetroLiveTiming_public/assets/86475165/41c151d3-3edf-41f1-8283-48d9183806f7)
    `Content in this picture can be different from the latest released version.`
    
    During races, the layout in the picture is displayed. Each column represents different data:
      - Current Position
      - Racing or Car Number
      - Last Name of the Driver
      - GapToLeader [marked as `Gap` in the header]
      - IntervalToPositionAhead [marked as `Int` in the header]
      - Last `Sector 1 (Intermediate 1)` time
      - Last `Intermediate 1 Speed` [taken as soon as the driver passes the `Intermediate 1` line]
      - Last `Sector 2 (Intermediate 2)` time
      - Last `Intermediate 2 Speed` [taken as soon as the driver passes the `Intermediate 2` line]
      - Last `Sector 3 (Finish Line)` time
      - Last `Finish Line Speed` [taken as soon as the driver passes the `Start/Finish Line`]
      - Last Lap Time
        - This column also shows if the driver is in the pits [`IN PIT`], leaves the pitlane [`PIT OUT`], has stopped on track [`STOPPED`] or has retired from the session [`RETIRED`]
          These values will be displayed with a red color as will the respective driver number
      - PitCount


> [!IMPORTANT]
> This description is not up to date and has not been finished yet. It should be finished soon this week


## Transparency
This application is not open-source yet. As long as this app is in full development, it will stay as it is.<br>
Plans to open the relative repository to the public are not present. I want to focus on making this app as stable and user friendly as possible. Getting my head into code transparency so you are able to read what I produce is not my main focus.
> [!NOTE]
> If you have a very good and waterproof reason to why you need to get access to my code, feel free to contact me by opening an Issue. Reasons like "*im just interested*" or "*you are a scammer*" or something else troll-like are not valid and will get deleted. Thank you for your trust.


## TODO [Plans / Fixes / Future]
- [ ] Better file structure -> Minimizing and optimizing code, outsource code like functions and components to differnt files. / Better structure of css files (one file per page/component) / Better classification of elements
- [ ] get the session timer running
- [ ] Biggest todo: SETTINGS
- [ ] Create page 4
- [ ] Revise page 1 and 3

> [!TIP]
> Well, I'm not a native English speaker, so excuse any grammatical errors. I'll try my best :)
