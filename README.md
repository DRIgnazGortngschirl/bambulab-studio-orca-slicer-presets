![Presets](https://img.shields.io/github/directory-file-count/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets/filament?type=file&extension=json&label=Presets%20in%20collection)
![](https://img.shields.io/github/last-commit/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets?label=Last%20preset%20added)
![](https://img.shields.io/github/contributors/DRIgnazGortngschirl/bambulab-studio-orca-slicer-presets?label=Preset%20contributors)

# Bambulab Studio <img src="https://wiki.bambulab.com/admin/home/logo-large.png" width="26"> / Orca Slicer Presets <img src="https://github.com/SoftFever/OrcaSlicer/blob/main/resources/images/OrcaSlicer_192px_transparent.png" width="27">

Welcome to the Bambulab Studio / Orca Slicer Presets repository! This repository is dedicated to storing / collecting presets that have been meticulously crafted and optimized for use in 3D printing and slicing applications. Whether you're a 3D printing enthusiast, engineer, or designer, our collection of presets aims to simplify your workflow and elevate your 3D printing experience.

## Features

 * A growing collection of presets for Bambulab Studio / Orca Slicer based 3D slicer applications.
 * Presets are meticulously optimized for quality and print performance.
 * Regular updates and additions to the preset library.
 * Community-driven contributions and improvements.

## Getting Started
 1.  Explore the Presets: Browse through the preset categories (Machine, Filament and Process) and select the ones that match your 3D printing needs.
 2. Optimize Your Prints: Use the presets to optimize your 3D printing settings for superior print quality and efficiency.
 3. Import Presets: Import the chosen presets into your 3D slicer software by downloading the repository and dropping them into the folder respective preset folders.
Full Path: 
```
C:\Users\USER\AppData\Roaming\OrcaSlicer\user\default
```  
Relative Path: 
```
%AppData%\Roaming\BambuStudio\user\[NUMBER]\filament
```

# Contributing

## Filament Presets

### Bambulab Studio <img src="https://wiki.bambulab.com/admin/home/logo-large.png" width="17">
For the best results, please follow these instructions step by step.

 1. Begin with the "Flow Dynamics Calibration" steps provided in this official guide https://wiki.bambulab.com/en/software/bambu-studio/calibration_pa
 2. Use the auto calibration mode first, if that one does not successfully finish, please skip to step 4.
 3. Continue on with auto calibration mode for "Flow Rate Calibration" https://wiki.bambulab.com/en/software/bambu-studio/calibration_flow_rate
 4. Now to create preset as optimized as possible again run a manual check with Manual mode in Flow Dynamics Calibration
 5. So do the same manual calibration for the "Flow Rate Calibration".

 * NOTE: Make sure when ever you got a calibration done, that you select the profile before continuing  the next calibration, as selecting a default profile will not result in the best combined settings for both calibration methods.

### Orca Slicer <img src="https://github.com/SoftFever/OrcaSlicer/blob/main/resources/images/OrcaSlicer_192px_transparent.png" width="15">
For the best results, please follow these instructions step by step.

1. Begin with the "Flow Rate Calibration" steps provided in this official guide: https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#flow-rate
2. Also, the line method is highly recommended to fine tune the Pressure Advance: https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#pressure-advance 
3. For refined overhangs or bridging, the "Temperature Tower" just finds the perfect spot for the Hotend. Please run this with the recommended temperature range of the manufacturer.  https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#Temp-tower
4. (optional) To get the "Maximum Volumetric Speed" for each filament, you can run through the steps at https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#max-volumetric-speed and determining the "Maximum Volumetric Speed". This would help limit the max speed / volumetric extrusion for the filament.

#### ToDo
- [ ] ...
