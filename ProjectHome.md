# Welcome to EVE Intel Monitor Project #

This tool allows a player of EVE Online to monitor Intel channels and detect important inelegance information.

The features of the tool include:
  * Read multiple EVE Channel log files
  * Configure the refresh rate for reading changes
  * Detecting when new items are written to the log files.
  * Parsing the Intel and trying to detect useful information - i.e. Solar Systems, player names, etc..
  * Configuring multiple keywords to match against.
  * Synthesize Speech - speak important Intel out-loud.

# How It Works #

I know that there is an EVE chat monitor, but this would be a bit different.

Basically the tool will read the Intel channel logs (from EVE Online folder) and try to present useful information to the user.

Future versions of the tool might include custom Intel parsing logic, more and better speech features, and a centralized server that would be able to collect all Intel through the day, and possibly overlay it over the EVE map.

# Install it using ClickOnce #

<table width='50%'>
<tr><td><b>Name:</b></td><td>EVE Intel Monitor</td></tr>
<tr><td><b>Version:</b></td><td>0.4.0</td></tr>
<tr><td><b>Publisher:</b></td><td>Open Source</td></tr>
<tr><td></td></tr>
<tr><td></td><td><a href='http://eve-intel-monitor.googlecode.com/svn/trunk/ClickOnceDeployment/setup.exe'>Download &amp; Install</a></td></tr>
</table>

## Version 0.4 includes ##
  * New UI
    * Settings is now its own window (similar to EVEmon)
    * Intel tab supports both, Grid View and List View
    * Improved overall user interactivity
    * Lot's of small bug fixes
    * Keywords used for Intel analysis can be ease ally displayed using [-> Show Active Keywords](Options.md) menu

  * Improved Intel Parsing
    * Will correctly parse player names after the system names.
    * Will detect if the player is docked, or the system is clear

  * Improved Speech Synthesis
    * System names will now sound better
    * The Speech Synthesize will now skip really old Intel messages and will only read the latest 5 (configurable)

  * Automatic Update using ClickOnce™ Microsoft Deployment technology
    * There is also internal auto-installer just in case ClickOnce does not work.

  * Improved tool-tips and error messaging.

## Version 0.3 includes ##
  * improvements to UI (I simplified several tabs),
  * better Intel parsing
  * better control over speech
  * simpler configuration (in my opinion, so I need your feedback about this)