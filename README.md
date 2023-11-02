# Bambulab Studio / Orca Slicer Presets

Welcome to the Bambulab Studio / Orca Slicer Presets repository! This repository is dedicated to storing presets that have been meticulously crafted and optimized for use in 3D printing and slicing applications. Whether you're a 3D printing enthusiast, engineer, or designer, our collection of presets aims to simplify your workflow and elevate your 3D printing experience.

## Features

 * A growing collection of presets for Orca Slicer based 3D slicer applications.
 * Presets are meticulously optimized for quality and print performance.
 * Regular updates and additions to the preset library
 * Community-driven contributions and improvements.

## Getting Started
 1.  Explore the Presets: Browse through the preset categories and select the ones that match your 3D printing needs.
 2. Import Presets: Import the chosen presets into your 3D slicer software by following the provided instructions in the respective preset folders.
 3. Optimize Your Prints: Use the presets to optimize your 3D printing settings for superior print quality and efficiency.

## Contributing

## Filament Presets

### Bambulab Studio
For the best results please floow these instructions step by step.

 1. Begin with the Flow Dynamics Calibration steps provided in this official guide https://wiki.bambulab.com/en/software/bambu-studio/calibration_pa
 2. Use the Auto Calibration mode first, if that one does not successfully finish, please skip to step 4.
 3. Continue on with Auto Calibration mode for "Flow Rate Calibration" https://wiki.bambulab.com/en/software/bambu-studio/calibration_flow_rate
 4. Now to create preset as optimized as possible again do a manual check with Manual mode in Flow Dynamics Calibration
 5. So do the same Manual Calibration for the Flow Rate Calibration.

 * NOTE: Make sure when ever you got a calibration done, that you select the profile befor doing the next calibration, as selecting a default profile will not result in the best settings for both calibration methods.

### Orca Slicer

1. Begin with the Flow Rate Calibration steps provided in this official guide: https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#flow-rate
2. Also, the line method is highly recommended to fine tune the Pressure Advance: https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#pressure-advance 
3. For refined overhangs or bridging, the temperature tower just finds the perfect spot for the Hotend. Please run this with the recommended temperature range of the manufacturer.
4. (optional) To understand the Maximum Volumetric Speed for each filament you can run through the steps at https://github.com/SoftFever/OrcaSlicer/wiki/Calibration#max-volumetric-speed and determent the Maximum Volumetric Speed. This would help limit also the max speed / volumetric extrusion for the filament. 