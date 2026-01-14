# Device Generation Tool

A lightweight circuit device generation tool that supports manual parameter configuration to create resistors, capacitors, and MOSFETs. It can batch-output standardized netlist files, whose format aligns with the `example` file included in this repository. Currently, the tool defaults to the TSMC 40nm process node, with all device parameters standardized based on this process.


- **Usage**
  1. Download the tool's EXE executable file from the repository's [Release page](https://github.com/xing-zouing/device-generator/releases/tag/v1.0.0).
  2. No additional dependencies are required — simply double-click the EXE file to launch the tool.
  3. Manually configure the device parameters in the tool interface, then click the "Generate" button to output the netlist file for your target device.
  4. Batch generation mode is supported, allowing you to export netlist data for multiple device groups in one operation.


- **Upcoming Updates**
  - Add generation support for additional device types (e.g., power supplies, capacitor arrays).
  - Enable flexible switching between mainstream process nodes (such as TSMC and SMIC).
  - Improve netlist format compatibility to work with a wider range of simulation tools.
