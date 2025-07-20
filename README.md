# GlazeWM, Zebar, Windhawk, Rainmeter Combined Theme Windows

## Table of Contents

* [Preview](#preview)
* [Installation](#installation)
* [Setup](#setup)
  * [Windhawk](#windhawk)
  * [Rainmeter](#rainmeter)
  * [GlazeWM](#glazewm)
  * [Zebar](#zebar)

## Preview

![Result of the setup](/Img/ThemePreview.png)

## Installation

Download this file to you home folder by downloading this using the git command

```bash
git clone https://github.com/Nevyin32/GlazeWM-Zebar-Sunset-Config-Theme.git
```

or you could download as a zip file, by clicking [here](https://github.com/Nevyin32/GlazeWM-Zebar-Sunset-Config-Theme/archive/refs/heads/main.zip)

### Download these tools/dependencies below, if you don't have it

* __GlazeWM_x64__ - [Download](https://github.com/glzr-io/glazewm/releases/download/v3.9.1/standalone-glazewm-v3.9.1-x64.msi)

* __GlazeWM_arm64__ - [Download](https://github.com/glzr-io/glazewm/releases/download/v3.9.1/standalone-glazewm-v3.9.1-arm64.msi)

* __Zebar_x64__ - [Download](https://github.com/glzr-io/zebar/releases/download/v2.7.0/zebar-v2.7.0-opt1-x64.msi)

* __Zebar_arm64__ - [Download](https://github.com/glzr-io/zebar/releases/download/v2.7.0/zebar-v2.7.0-opt2-arm64.msi)

* __Windhawk__ - [Download](https://windhawk.net/)

* __Rainmeter__

  * [Rainmeter Tool](https://windhawk.net/)
  * [Mond Skin](https://visualskins.com/media/p/565/mond.rmskin)

## Setup

### Windhawk

In windhawk, install these mods in the image below

![Installation Mods Below](/Img/InstallMods.png)

In, Windows 11 Taskbar Styler, copy the json code below

<details>

<summary> JSON CODE</summary>

```bash
{
  "controlStyles[0].target": "Taskbar.TaskbarFrame > Grid#RootGrid > Taskbar.TaskbarBackground > Grid > Rectangle#BackgroundFill",
  "controlStyles[0].styles[0]": "Fill=Transparent",
  "controlStyles[1].target": "Taskbar.TaskbarBackground#HoverFlyoutBackgroundControl > Grid > Rectangle#BackgroundFill",
  "controlStyles[1].styles[0]": "Fill=#CC222222",
  "controlStyles[2].target": "Taskbar.TaskListButtonPanel@CommonStates > Border#BackgroundElement",
  "controlStyles[2].styles[0]": "CornerRadius=5",
  "controlStyles[2].styles[1]": "Background:=<AcrylicBrush TintColor=\"Black\" TintOpacity=\"0.8\" FallbackColor=\"#BB222222\" />",
  "controlStyles[2].styles[2]": "Background@InactivePointerOver:=<AcrylicBrush TintOpacity=\"0.2\" TintColor=\"Gray\" FallbackColor=\"#DD222222\"/>",
  "controlStyles[2].styles[3]": "Background@ActivePointerOver:=<AcrylicBrush TintOpacity=\"0.2\" TintColor=\"Gray\" FallbackColor=\"#DD222222\"/>",
  "controlStyles[2].styles[4]": "Background@ActiveNormal:=<AcrylicBrush TintColor=\"Gray\" TintOpacity=\"0.8\" FallbackColor=\"#CC222222\" />",
  "controlStyles[2].styles[5]": "Background@InactiveNormal:=<AcrylicBrush TintColor=\"Gray\" TintOpacity=\"0.1\" FallbackColor=\"#BB222222\" />",
  "controlStyles[2].styles[6]": "Background@InactivePressed:=<AcrylicBrush TintColor=\"Black\" TintOpacity=\"0.8\" FallbackColor=\"#CC222222\" />",
  "controlStyles[2].styles[7]": "Background@ActivePressed:=<AcrylicBrush TintColor=\"Black\" TintOpacity=\"0.8\" FallbackColor=\"#CC222222\" />",
  "controlStyles[3].target": "Grid#SystemTrayFrameGrid",
  "controlStyles[3].styles[0]": "Background:=<AcrylicBrush TintColor=\"Gray\" TintOpacity=\"0\" FallbackColor=\"#BB222222\"/>",
  "controlStyles[3].styles[1]": "CornerRadius=5",
  "controlStyles[3].styles[2]": "Margin=0,5,14,5",
  "controlStyles[3].styles[3]": "Padding=10,0,0,0",
  "controlStyles[4].target": "Rectangle#RunningIndicator",
  "controlStyles[4].styles[0]": "Fill=Transparent",
  "controlStyles[4].styles[1]": "RadiusX=5",
  "controlStyles[4].styles[2]": "RadiusY=5",
  "controlStyles[4].styles[3]": "Height=38",
  "controlStyles[4].styles[4]": "Width=40",
  "controlStyles[5].target": "Taskbar.TaskListLabeledButtonPanel > TextBlock#LabelControl",
  "controlStyles[5].styles[0]": "Margin=4,0,0,0",
  "controlStyles[5].styles[1]": "Foreground=White",
  "controlStyles[6].target": "Taskbar.SearchBoxButton",
  "controlStyles[6].styles[0]": "Foreground=White",
  "controlStyles[6].styles[1]": "Margin=-11,0,0,0",
  "controlStyles[7].target": "TextBlock#SearchBoxTextBlock",
  "controlStyles[7].styles[0]": "FontSize=12",
  "controlStyles[7].styles[1]": "Foreground=White",
  "controlStyles[8].target": "Rectangle#BackgroundStroke",
  "controlStyles[8].styles[0]": "Fill=Transparent",
  "controlStyles[9].target": "Grid",
  "controlStyles[9].styles[0]": "RequestedTheme=2",
  "controlStyles[10].target": "Taskbar.TaskListButton#TaskListButton[AutomationProperties.Name=Copilot] > Taskbar.TaskListLabeledButtonPanel#IconPanel > Border#BackgroundElement",
  "controlStyles[10].styles[0]": "Background:=<AcrylicBrush TintColor=\"Red\" TintOpacity=\"0.8\" />",
  "controlStyles[11].target": "Border#BackgroundBorder",
  "controlStyles[11].styles[0]": "Margin=0,3,0,3",
  "controlStyles[11].styles[1]": "CornerRadius=5",
  "controlStyles[12].target": "Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel > Border#BackgroundElement@CommonStates",
  "controlStyles[12].styles[0]": "Background@InactivePointerOver:=<AcrylicBrush TintColor=\"Black\" TintOpacity=\"0\" />",
  "controlStyles[12].styles[1]": "Background:=<AcrylicBrush TintColor=\"Black\" TintOpacity=\"0.8\" FallbackColor=\"#BB222222\" />",
  "controlStyles[13].target": "Border#MultiWindowElement",
  "controlStyles[13].styles[0]": "Background:=<AcrylicBrush TintColor=\"Black\" TintOpacity=\"0.8\" FallbackColor=\"#CC222222\" />",
  "controlStyles[14].target": "TextBlock#TimeInnerTextBlock",
  "controlStyles[14].styles[0]": "Foreground=White",
  "controlStyles[15].target": "TextBlock#DateInnerTextBlock",
  "controlStyles[15].styles[0]": "Foreground=White",
  "controlStyles[16].target": "SystemTray.TextIconContent > Grid > SystemTray.AdaptiveTextBlock#Base > TextBlock",
  "controlStyles[16].styles[0]": "Foreground=White",
  "controlStyles[17].target": "Border#BackgroundElement",
  "controlStyles[17].styles[0]": "BorderThickness=0",
  "controlStyles[18].target": "Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton",
  "controlStyles[18].styles[0]": "Margin=-11,0,0,0",
  "controlStyles[19].target": "Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.Name=Task View]",
  "controlStyles[19].styles[0]": "Margin=-12,0,0,0",
  "controlStyles[20].target": "taskbar:TaskListLabeledButtonPanel@RunningIndicatorStates > Border",
  "controlStyles[20].styles[0]": "Background@ActiveRunningIndicator:=<AcrylicBrush TintOpacity=\"0.5\" TintColor=\"Gray\" />",
  "controlStyles[20].styles[1]": "Background@InactiveRunningIndicator:=<AcrylicBrush TintOpacity=\"0.2\" TintColor=\"Gray\" />",
  "controlStyles[20].styles[2]": "Background@InactiveRunningIndicatorPointerOver:=<AcrylicBrush TintOpacity=\"0.8\" TintColor=\"Black\" />",
  "controlStyles[21].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Border#BackgroundElement",
  "controlStyles[21].styles[0]": "Background@InactivePointerOver:=<AcrylicBrush TintOpacity=\"0.2\" TintColor=\"Gray\" FallbackColor=\"#DD222222\"/>",
  "controlStyles[21].styles[1]": "Background@ActivePointerOver:=<AcrylicBrush TintOpacity=\"0.2\" TintColor=\"Gray\" FallbackColor=\"#DD222222\"/>",
  "controlStyles[21].styles[2]": "Background@InactiveNormal:=<AcrylicBrush TintOpacity=\"0\" TintColor=\"Gray\" FallbackColor=\"#BB222222\"/>",
  "controlStyles[21].styles[3]": "Background@ActiveNormal:=<AcrylicBrush TintOpacity=\"0.3\" TintColor=\"#fccccc\" FallbackColor=\"#CC222222\"/>",
  "controlStyles[21].styles[4]": "Background@ActivePressed:=<AcrylicBrush TintOpacity=\"0.8\" TintColor=\"#333333\" FallbackColor=\"#BB333333\" />",
  "controlStyles[21].styles[5]": "Background@InactivePressed:=<AcrylicBrush TintOpacity=\"0.8\" TintColor=\"#333333\" FallbackColor=\"#BB333333\" />",
  "controlStyles[21].styles[6]": "CornerRadius=5",
  "controlStyles[21].styles[7]": "Margin=1",
  "theme": "",
  "styleConstants[0]": "",
  "resourceVariables[0].variableKey": "",
  "resourceVariables[0].value": ""
}
```

</details>

<br>

*__COPY THE MOD JSON IN A NOTEPAD BEFORE YOU PASTE THE COPIED JSON__

Then, click details and go to advanced tab and paste it in the mod settings and click save

![alt text](/Img/Windhawk.png)

If you don't like it or doesn't align as it suppose to be,

* Paste the mod json that you copied into your notepad.
* go to details and choose which taskbar you like.
* After choosing your taskbar, go to settings
* click none
* select the chosen taskbar
* click save settings

---

### Rainmeter

In the system tray, right click the rainmeter icon and click the manage

![Rainmeter manage button placement](/Img/RightClick.png)

* Then navigate through these folders as shown in the image below

![Rainmeter manage window](/Img/ManageWindow.png)

* Click Load (where Unload button is there to me)

* Set the transparency to 20% to blend with the wallpaper

* Set the check box as it is shown below

* Click the edit button and config the text below

  * <details>

      <summary>Config</summary>

      ```bash
      [Rainmeter]
      Update=1000
      Author=Connect-R
      BackgroundMode=2
      SolidColor=0,0,0,1
      DynamicWindowSize=1
      AccurateText=1
      MouseScrollUpAction=[!SetVariable Scale "(#Scale#+#ScrollMouseIncrement#)"][!WriteKeyValue Variables Scale "(#Scale#+#ScrollMouseIncrement#)"][!Refresh] 
      MouseScrollDownAction=[!SetVariable Scale "(#Scale#-#ScrollMouseIncrement# < 0.5 ? 0.5 : #Scale#-#ScrollMouseIncrement#)"][!WriteKeyValue Variables Scale "(#Scale#-#ScrollMouseIncrement# < 0.5 ? 0.5 : #Scale#-#ScrollMouseIncrement#)"][!Refresh] 
      LeftMouseDoubleClickAction=!ToggleConfig "Mond\Settings" "Settings.ini"

      [Variables]
      @include=#@#Variables.inc
      @include2=#@#Language\#Language#.inc
      Scale=1.7

      ;-------------------------------------------------------------
      ;-------------------------------------------------------------

      [MeasureTime]
      Measure=Time
      Format="%#Format#:%M"

      [MeasureAmPm]
      Measure=Time
      Format="%p"

      [MeasureDay]
      Measure=Time
      Format=%A
      Substitute=#Date#

      [MeasureDate]
      Measure=Time
      Format=%d  %B,  %Y.
      Substitute=#Date#

      ;-------------------------------------------------------------
      ;-------------------------------------------------------------

      [Meter12hClock]
      Meter=String
      MeasureName=MeasureTime
      MeasureName2=MeasureAmPm
      StringAlign=Center
      StringCase=Upper
      FontFace=Quicksand
      FontColor=#TextColor#
      FontSize=(14*#Scale#)
      X=(340*#Scale#)
      Y=(120*#Scale#)
      Text="- %1 %2 -"
      AntiAlias=1
      Hidden=#Hidden2#

      [MeterDay]
      Meter=String
      MeasureName=MeasureDay
      StringAlign=Center
      StringCase=Upper
      FontFace=Anurati
      FontColor=#TextColor#
      FontSize=(40*#Scale#)
      X=(340*#Scale#)
      Y=(0*#Scale#)
      Text="%1"
      InlineSetting=CharacterSpacing | 10 | 10
      AntiAlias=1
      DynamicVariables=1


      ```

   </details>

* Save the file

* Click Refresh in the Manage Rainmeter Window

* Edit Scale in the notepad and Coordinates in teh Manage Rainmeter Window to fit your screen

---

### GlazeWM

Open Explorer and go to `C://Users/YourUserName/.glzr/GlazeWM` and remove the config.yaml and move my config.yaml (my config is inside glazeWM folder in the downloaded github folder) to this path.

---

### Zebar

Open Explorer and go to `C://Users/YourUserName/.glzr/Zebar/starter` and replace with-glazewm.zebar.json to my json (which is inside zebar foler in the downloaded github folder) and copy the .css and .html files and paste it in the `.glzr/Zebar` folder

There are variables in .css file to edit the colors that match your wallpaper if you have a different wallpaper.

## Credits

The Zebar theme was inspired from [echosonusharma zebar neon theme](https://github.com/echosonusharma/zebar_neon_theme.git) and customized it to my needs.

Thanks `echosonusharma` for the inspiration.
