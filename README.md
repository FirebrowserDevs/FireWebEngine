# FireWebEngine

  # Welcome
  - introducing a new service that was brought to you by the people of FireBrowser-uwp and FireBrowser - Windows forms
This is a look at our new and improved engine that will be its own seprit browser instead of using WebView2, this also could give us more room for customization, note that this product is in very early alpha and is very buggy, and there are no implamented solutions at this current moment for bugs, we are hard at work fixing any issues that may accure in this softwhare

# Currently Known Issues;

+ The Render Pipline fails and crashes the Framework
+ if you render pages with css files that arent meant to handle new rendering engine layers
+ engine crashes when in HTML3 Playback
+ the Pipline for The VIdeo Encoder Crashes during resource collection for debugging
+ Constarints of the engines level to communicate with the systems hardware
+ constraints with the engine not using the needed ammount of resources

  # implamented Fixes
  + Memory Leaks
  + double debug
  + process creation
  + .js rendering failing to load micro javascript that communicates with the HTML and CSS layouts of webpages
  + Implamented UI elements that tell the Browser To Render sets of unsupported ui elements in a set fashion
  + added v8 rendering
  + Added Extra Extensive Layer under the contextmenu binding to ensure smooth right response
 
  # Building

    make sure that when you are compiling the engine you give it the proper target response and configure the piplines as needed
    to avoid any problems make sure you have "Visual Studio 2022" or later

  # Documentation
  -- at this current moment there are no spacific documentation on publicly buildig the engine to support other platforms and other known issues
  thiswill come at a later date and will give thero instruction and need to know basics.

  # System Compatibility

    at minimum you should use windows 8 and up for the best compatibility use windows 10/11
    if you wish to know any bits of intermation contact the support pole and we will do our best to ensure you have a great experince and get what you need fixed and initiled.

  # Engine Platform
  as of now the enginen is only for windows 32 am64 and 64 bit systems and can be configured with any cpu option in debug

 # Encoding
   currently video encoding is very detrimental to the engine core and can cause crashes if not implamented properly

   # Framework infermation
    currently this rendering engine is only for winforms but wpf uwp and other frameworks will be implamented at some point

# Engine Implamentation into MainForm
 'test'
