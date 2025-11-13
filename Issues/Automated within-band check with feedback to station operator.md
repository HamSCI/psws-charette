
# Automated within-band check with feedback to station operator
## Description
An issue I've encountered, which can be subtle or blatant, is that of spectral clipping in the +/- 5Hz bandwidth (10 Hz sampling rate) used by the RX888 Mk2 stations (and perhaps others?). Accurate measurement of Doppler shift requires a spectrum without instrumental clipping of its high or low skirts. This can occur for a spectrum of modest width (~1 Hz) if the Doppler is substantial - as I see on multihop trans auroral oval WWVH to the UK for example. Or if the spectrum is wide, e.g. two hop sidescatter. Thinking ahead to the Antarctic deployments, checking that stations are using and reporting with adequate sampling rates is important for highest quality reduced data.

### Suggested by:
Gwyn Griffiths, G3ZIL, gwyn@autonomousanalytics.com

### Additional comments:
With existing data I have resorted to clipping the Fourier components of the the other skirt to have a balanced spectrum for Doppler calculation where I've seen this behaviour.
 
