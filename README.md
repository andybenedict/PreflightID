# PreflightID
A collection of preflight profiles for Adobe InDesign

## Preflight Profiles
Adobe InDesign's preflight system allows you to check for a lot of very common issues that could cause problems when your designs go to press. Unfortunately, a lot of people don't actually use it because it has a somewhat steep learning curve for those who aren't familiar with the printing process.

These profiles were developed during a couple of years I spent working with a variety of commercial print shops. They are very strict, so in most cases, if these profiles pass your files are much less likely to incur any artwork fees from the printer.

### Style-Strict Profiles
The standard profiles do not perform a check for style overrides. If you adhere to a strict StyleSheet, or if you like a cleanly power-styled document like me, you can use the style strict profiles which will throw an error if any style has it's formatting overridden.

### Turning on Preflight
If the preflight panel is not visible:

Select *Window > Output > Preflight* from the menu

  -or-
  
Press *Command + Option + Shift + F* on a Mac or *Control + Alt + Shift + F* on a PC

Check the "On" Checkbox and Select a preflight profile from the list at the top right of the panel to get started.

For a more complete explanation, visit the [Adobe Help Site](https://helpx.adobe.com/indesign/using/preflighting-files-handoff.html)

### Installing Preflight Profiles
From the preflight panel, click the panel's dropdown menu and select *Define Profiles...*

In the Preflight Profiles dialog, under the list of profiles, click the menu and select *Load Profile...* and browse to the file you wish to load.

So far as I know, and please let me know if there is a way, there is no way to re-order profiles after they are imported, so it's good to import them in an order that will make them easier to find later.

### Image Options
The most common variable from printer to printer is image resolution, because of this, these profiles do not have a check for effective image resolution. If you or your printer have a strict minimum, I recommend adding it to the profiles you use.

### Preflight Performance
Preflight can be a bit processor and ram intensive, so if you experience a slowdown, particularly on large documents, it is often beneficial to only turn it on for occasional checks rather than leaving it on at all times.

## Bonus Job Options
A generic press quality pdf output profile is included as well, if your printer does not provide you with a profile, this one will produce a high-quality pdf that is compatible with all the major prepress systems commonly in use.
