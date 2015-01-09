# Streamlined-Scene-Controls---SMARTTHINGS

I currently have 9 modes.  4 modes are "automatic", and are run based on time of day or sunset/sunrise (Sleepytime, Morning, Day, and Night).  The other 5 modes are used when I invoke them manually (Dinner, BabySitting, Late, Movies, Vacation).  As I discuss below, I don't set up Home/Away modes - instead rely on virtual switches to check if certain family members are present.

-----

Whole House Scene Creation and Control App - sets up Color, Levels, and/or On/Off for any Mode you have.  Most of the code of this App comes from the wonderful "Dim & Dimmer" App by geko@statusbits.com .

  - First, Select the Hues, Dimmers, and/or Switches that you want.
  - Second, for each Mode, just enter the desired Scene Lighting parameters.  These will be used whenever the Mode is invoked.
  - Third, use my "Motion and Contact Trigger" App to set up accompanying motion and contact trigger events for use with 1 or more Modes/Scenes.

-----

Motion and Contact Trigger App - sets up motion & contact triggers that invoke the scenes from above.  Turns off lights if no motion after "X" minutes.

  - I use virtual switches to identify whether certain family members are present (and thus whether motion/contact should trigger), but you could easily change that to run based on one or more Presence sensors.   

-----

Individual Scene Selection App - can be used in conjuction with above or used completely separately.  User can select Color, Level, and On/Off, and can select motion & contact sensors to trigger.  

- Again, I use virtual switches to identify whether certain family members are present (and thus whether motion/contact should trigger), but you could easily change that to run based on one or more Presence sensors.   

-----

Please let me know if you like/dislike, identify any bugs, or have any suggestions.  Thanks!!!
  
