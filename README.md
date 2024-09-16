# Visualisation
Toolbox for data visualisation and integration.

## MultiPlot_UI
GUI to load and display and **replay** different raw and/or preprocessed signals for a given recording session.
This includes:
1) Modular and in-GUI toggable "plot areas" for:
   - Behavioural movies (with tracking overlay if available)
   - Calcium imaging movies (raw, with optional and adjustable filtering option, overlay of extracted ROIs)  
   - Heatmaps (e.g. heart rate or neuronal activity mapped onto the paradigm, adjustable binning size and contrast)  
   - Occupancy map or trajectory, location of events within the paradigm (e.g. optogenetics stimulations)  
2) Traces data:  
   - Heart rate, speed, motion measure, etc  
   - Behaviours and/or Keypoint Moseq sylables as rasters, subselection possible from a dropdown list
   - Calcium imaging traces (the ROIs on the movies possess callback that allow to select the neurons to display)
  
![image](https://github.com/user-attachments/assets/dcd4444f-4b70-4c15-99a5-f2e0e13e7a95)


