# Calcium_Signaling_Analysis
Developed on 01/15/2019.

Pipeline written in MATLAB to analyze Calcium Signaling video data acquired from live awake mice, using a two-photon microscope. I first proccess the imaging data using the open-source software Suite2p, and use the output from it as the input for this pipeline.  

Output:
- Find and plot spikes and its characteristics (amplitudes, locations, widths, prominences)
- Frequency of spikes
- Mean Interval between spikes
- Correlation matrix
- Correlation coefficient
- Export results to excel files

Observations:
- "width" and "prominence" values cannot be taken into consideration if the input was the deconvolved "spks.py", only if the input was the DF/F0.
- Change duration in seconds according to experiment.
