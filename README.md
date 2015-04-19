![Icon](http://silverux.com/sketchplugins/userflows/assets/icon_crop.png)
# User Flows
A plugin for generating user walkthroughs from Artboards in [Sketch](http://www.bohemiancoding.com/sketch/).  

##### Example Output  
![UserFlows Example](http://silverux.com/sketchplugins/userflows/assets/exampleflow.jpg)

## Demo
[![Video](http://silverux.com/sketchplugins/userflows/assets/video_title.png)](https://vimeo.com/abynim/userflows)  
[Watch on Vimeo](https://vimeo.com/abynim/userflows)

## Supported Versions
UserFlows is only supported in Sketch 3.3 or later. To check what version you have installed, go to `Sketch` > `About Sketch`.  
![About Sketch](http://silverux.com/ig-auth/assets/sketchsquares-8a.png)

## Installation  
[Download](https://github.com/abynim/UserFlows.sketchplugin/archive/master.zip) and extract the contents of this repository into your `Plugins` folder. If you don't know where your plugins folder is, [follow these steps](http://bohemiancoding.com/sketch/support/developer/01-introduction/01.html) to find it.

## Usage

#### Generate Flows
1. Select Layers that you want to use as hotspots (one Layer or Group per Artboard).
2. If you don't need hotspots, select the Artboard itself.
3. Run the plugin from `Plugins` > `User Flows` > `Generate a Flow`.
![Generate Flow Dialog](http://silverux.com/sketchplugins/userflows/assets/generate_flow_dialog1.png)
4. Enter details for the flow and hit `Generate`.

_Note: The sequence of screens in a flow is based on the `x` position of your Artboards. Sketch does not allow event-tracking (yet) so it's not possible to determine the order in which layers or Artboards were selected, although that would be ideal._

#### Settings
To manage settings for the plugin, go to `Plugins` > `User Flows` > `_Settings`.  
![Settings Dialog](http://silverux.com/sketchplugins/userflows/assets/settings_dialog1.png)

## Shortcut
Once you've installed the plugin you can trigger it using: `control` + `shift` + `f`.

## Bugs, Features and Feedback
If you encounter bugs, or think of some awesome enhancements, please create an Issue on Github or send a message on Twitter [@abynim](http://twitter.com/abynim).

---

MIT License © Aby Nimbalkar. I'm on [Twitter](http://twitter.com/abynim) and [LinkedIn](http://tw.linkedin.com/in/abynim/).
