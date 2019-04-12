# Climber KPI
<a href="http://www.climberextensions.com/" class="image_link" target="_blank"><img src="./screenshots/downloadbutton.png?raw=true" 
alt="Download latest release" width="400" height="40" border="0" /></a>

>The Climber KPI is fully responsive and works for all screen sizes. Features include background trends for both actual and target, navigation and tooltip on hover to show values. It is also possible to include images as background or use the extension just to show images. Colors are completely flexible but have easy standard settings to allow quick and easy creation of nice looking KPIs. For more details take a look at the video found here: https://youtu.be/9zdfYshNel4

***Tested from Qlik Sense June 2017 (in the initial release of June 2017, extensions load slow. It's fixed in patch 1 )***

## Most recent update 1.6.2 - 2019-03-12
### Fixed
- Fixed arrow-circle-up

Full CHANGELOG can be found end of this file.

<div style="page-break-after: always;"></div> 

## Purpose and Description
The Climber KPI extension brings a clear presentation of KPIs including trendlines and navigation from your dashboard to details on other sheets. Getting started is extremely quick when using Master Items.  
<img src="./screenshots/samplevideo_CreateObject.gif?raw=true" alt="Sample video of object creation" />

The large number of options for the layout including the possibility to use an image background allows a flexible layout. Finetuning of graphs, colors and even margins are possible in the extensive settings menu.  
<img src="./screenshots/samplevideo_MainLayouts.gif?raw=true" alt="Sample video of the main layout and hover options" />

## Getting started
To get started (after installation) add one or two measures. To get the trendline, add a dimension in the Trend section of the extension settings. 

## Settings and Features
1. Target Mode - Target mode includes feedback on target fulfillment. This may include both color and icon. The target mode setting is found in the "Target" section of the settings.  
<img src="./screenshots/screenshot_TargetModeEnabledDisabled.png?raw=true" alt="Target Mode Enabled/Disabled" />
2. Layout Mode - Choose between Fill or Top. Settings are located in Appearance/Layout.   
<img src="./screenshots/screenshot_FillTopMode.png?raw=true" alt="Fill or Top Layout Mode" />
3. Text Layouts - Choose text layout you like. Or remove the text altogether for just graphs, icons or images. (Works well to use for navigation too!)  
<img src="./screenshots/screenshot_TextLayoutModes.png?raw=true" alt="Text Layout Alternatives" />
4. Hover modes - Select what you want to show "on mouse over" the object. This is also where you enable navigation mode. The setting is found in Appearance/Hover.  
<img src="./screenshots/screenshot_HoverModes.png?raw=true" alt="Hover mode alternatives" />
5. Color settings - Full control of color settings for both text and trend. You can choose to have quick access to banding for Target color mode (two or three colors) or you can use an expression to set the Target color. The trend color is independent of the target (icon) color and can also be set either to a specific color or an expression.  
<img src="./screenshots/screenshot_ColorSettings.png?raw=true" alt="Color Settings" />
6. When new versions of the extensions are released it is now possible to update (rather than recreate) the object to include any new properties. This will improve the maintainability of the extension between versions.  
<img src="./screenshots/screenshot_UpdateProperties.png?raw=true" alt="Color Settings" />

## Installation

1. Download the latest version
2. Qlik Sense Desktop
	* To install, copy all files in the .zip file to folder "C:\Users\\%Username%\Documents\Qlik\Sense\Extensions\cl-kpi"
3. Qlik Sense Server
	* See instructions <a href="http://help.qlik.com/en-US/sense/3.2/Subsystems/ManagementConsole/Content/import-extensions.htm"> how to import an extension on Qlik Sense Server </a>

## Recommended Versions
Qlik Sense Version | Recommended
------------- | -------------
February 2019|*1.6.2*
November 2018|*1.6.2*
September 2018|*1.6.2*
June 2018|*1.6.2*
April 2018|*1.6.2*
February 2018|*1.6.2*


<div style="page-break-after: always;"></div> 

## Climber Extensions
Like this extension? Check out the other Climber made extensions below.

**Custom Report**
* https://github.com/ClimberAB/ClimberCustomReport
* https://www.youtube.com/watch?v=mCb2t4aNppE

**Selection Bar**
* https://github.com/ClimberAB/ClimberSelectionBar
* https://www.youtube.com/watch?v=4fxrphADRKw

**Cards**
* https://github.com/ClimberAB/ClimberCards
* https://www.youtube.com/watch?v=k_IEt8TvB_c


<div style="page-break-after: always;"></div> 

## Change Log
## 1.6.2 - 2019-03-12 
### Fixed
- Fixed arrow-circle-up 
 
## 1.6.1 - 2019-01-08 
### Fixed
- Github issue 27 Font appear small on first load
- Domain error if contains NaN 
 
## 1.6.0 - 2018-12-03 
### Added
- Support for November 2018
- Bundle information 
 
## 1.5.3 - 2018-11-20 
### Fixed
- Icons were too big 
 
## 1.5.2 - 2018-10-29 
### Fixed
- ES-10256 Can't hide snapshot symbol bug 
 
## 1.5.1 - 2018-10-22 
### Fixed
- ES-10193 Zero value doesn't show 
- ES-10194 Background color property is not easy to understand 
 
## 1.5.0 - 2018-06-28 
### Added
- Update for June 2018 
 
## 1.4.5 - 2018-04-11 
### Fixed
- Icon fix for mashup. Relative path 
 
## 1.4.4 - 2018-04-05 
### Changed
- Removed old code 
 
## 1.4.3 - 2018-04-04 
### Fixed
- Export problem solved from QS 201706 
 
## 1.4.2 - 2018-03-20 
### Fixed
- Fixed bug for select values (action) 
 
## 1.4.1 - 2018-03-11 
### Added
- New preview logo and about panel 
 
## 1.4.0 - 2018-02-14 
### Added
- Updated for February 2018 
 
## 1.3.1 - 2018-01-18 
### Added
- Changeble Up/Down/Right Arrows 
 
## 1.3.0 - 2017-09-05 
### Changed
- Change Up/Down Arrow
- Equal to comparison is "good" color 
 
## 1.2.2 - 2017-09-05 
### Added
- Added space between label and target value 
 
## 1.2.1 - 2017-09-05 
### Fixed
- Fixed bug with relative and absolute comparison 
 
## 1.2.0 - 2017-08-16 
### Added
-Working export 
 
## 1.1.1 - 2017-08-11 
### Fixed
- Fixed bug with colorized bars/line/points 
- Fixed bug with negative values in trend chart 
 
## 1.1.0 - 2017-06-01 
### Added
- Colorize data points/bars
- Larger navigation text
- Hide labels
- More icons
### Fixed
- Absolute banding and add explanation text 
 
## 1.0.0 - 2017-05-04 
* Initial Release 
 
## 1.6.2 - 2019-03-12 
### Fixed
- Fixed arrow-circle-up 
 
## 1.6.1 - 2019-01-08 
### Fixed
- Github issue 27 Font appear small on first load
- Domain error if contains NaN 
 
## 1.6.0 - 2018-12-03 
### Added
- Support for November 2018
- Bundle information 
 
## 1.5.3 - 2018-11-20 
### Fixed
- Icons were too big 
 
## 1.5.2 - 2018-10-29 
### Fixed
- ES-10256 Can't hide snapshot symbol bug 
 
## 1.5.1 - 2018-10-22 
### Fixed
- ES-10193 Zero value doesn't show 
- ES-10194 Background color property is not easy to understand 
 
## 1.5.0 - 2018-06-28 
### Added
- Update for June 2018 
 
## 1.4.5 - 2018-04-11 
### Fixed
- Icon fix for mashup. Relative path 
 
## 1.4.4 - 2018-04-05 
### Changed
- Removed old code 
 
## 1.4.3 - 2018-04-04 
### Fixed
- Export problem solved from QS 201706 
 
## 1.4.2 - 2018-03-20 
### Fixed
- Fixed bug for select values (action) 
 
## 1.4.1 - 2018-03-11 
### Added
- New preview logo and about panel 
 
## 1.4.0 - 2018-02-14 
### Added
- Updated for February 2018 
 
## 1.3.1 - 2018-01-18 
### Added
- Changeble Up/Down/Right Arrows 
 
## 1.3.0 - 2017-09-05 
### Changed
- Change Up/Down Arrow
- Equal to comparison is "good" color 
 
## 1.2.2 - 2017-09-05 
### Added
- Added space between label and target value 
 
## 1.2.1 - 2017-09-05 
### Fixed
- Fixed bug with relative and absolute comparison 
 
## 1.2.0 - 2017-08-16 
### Added
-Working export 
 
## 1.1.1 - 2017-08-11 
### Fixed
- Fixed bug with colorized bars/line/points 
- Fixed bug with negative values in trend chart 
 
## 1.1.0 - 2017-06-01 
### Added
- Colorize data points/bars
- Larger navigation text
- Hide labels
- More icons
### Fixed
- Absolute banding and add explanation text 
 
## 1.0.0 - 2017-05-04 
* Initial Release 
 


## License

See <a href="License.pdf"> LICENSE </a>




