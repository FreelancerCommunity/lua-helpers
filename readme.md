# What are these scripts?

These are a set of simple lua 3.2 compatible scripts that can be plugged into Freelancer's cutscene files in order to make working in them a little easier.

## What's included?

- **math.lua**: Includes a very basic sphere collision calculator, a proper rounding function for 3.2, and reassigns some math functions to something a bit more modern.
- **utils.lua** - Includes a function to write variables being set in a script to an external log file.
- **convert.lua** - Includes a Quaternion to Rotation Matrix function, and a Euler to Matrix function.

## How do I use these?

In order to call these in a script, you'll need to include `dofile('..\\DATA\\SCRIPTS\\helpers.lua')` at the top of your file.
