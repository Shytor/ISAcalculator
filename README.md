# ISAcalculator
International Standard Atmosphere Calculator

This calculator is designed to provide atmoshperic conditions at altitude per the 1976 US Standard Atmosphere document published by the NOAA, NASA and USAF (NOAA-S/T 76-1562).

The calculator is currently available at http://games.codeandcompose.com/ISAcalculator.html

##License

This code is copyrighted by Trevor Gast 2015. It is available for use under the GNU general public license. http://www.gnu.org/licenses/

##Version history

Version 1.0 - 21 November 2015

Version 1.2 - 27 November 2015

 - corrected density and pressure calculations when a temperature offset is used (previously inverted)
 - added unit conversions
 - added ability to cycle through alternate values for radius of the Earth and specific gas constant for dry air

Version 2.0 - 2 December 2015

  - added temperature adjustment from 80 to 86 km so that it equals 186.8673 at 86 km (geometric altitude)
  - added graph of temperature up to 1000 km (also clickable)
  - density and pressure calculations above 86 km no longer available (next version?)
  - added speed of sound calculation
  - added some nice color gradient to the graphs

##Features

User can enter an altitude (in meters feet or km) and the graph will place a line to indicate, as well as calculate the geometric altitude, temperature, pressure, density, gravity and the speed of sound. There is an option for an offset temperature (for altitude below 84852 meters). Altitudes above 84852 meters do not account for the temperature offset.

User may also click directly on the graphs to select an altitude.

User may also enter a pressure or density and it will attempt to calculate the altitude according to the model. When a temperature offset is used, the density alorithm engages in approximate "guessing" so ther is a small amount of error.

Altitudes above 84852 meters do not report pressure or density values (still in progress).

Units can be changed for Temperature, altitudes, density and pressure.

The pressure and density scale can be changed to a log base 10 scale, by pressing the button.

Constant values for the specific gas constant of dry air and the earth radius can be changed through known values by clicking on the number itself.
