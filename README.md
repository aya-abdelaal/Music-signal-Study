# Music-signal-generator


## Procedure: 

- Constructed arrays containing the right frequencies, left frequencies, start times, and end times of the signal . 
- Defined a function to return the unit step conditions. 
- Used a for each loop to add the signals in the array to the resulting signal x. 
- Plotted x using matplotlib.pyplot  
- Converted x into the frequency domain using the scipy library and plotted x_f 
- Generated random noise signals with a frequency between (0, 512) exclusive 
- Added noise signals to x to create altered song 
- Displayed altered song in the frequency domain 
- Found the new added frequencies by searching for the frequencies greater than max(x_f) 
- Removed randomly generated noise signals by removing sinusoidals with the obtained added frequencies from x 
- Plotted the new xfiltered in the time and frequency domain, and played it using the sounddevice library to ensure original x was restored 
