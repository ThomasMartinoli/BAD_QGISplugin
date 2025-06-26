🔥 BAD_QGISplugin – Burned Area Detector
BAD (Burned Area Detector) is a QGIS plugin for detecting burned areas and burn severity from satellite multispectral imagery, developed within a GIS environment.
It implements robust algorithms to generate geospatial products that highlight fire-affected regions and evaluate the damage caused to vegetation.

🆓 The plugin is free to download and can be installed in QGIS using the "Install from ZIP" option.

 What's New in BAD v2.0.0
The BAD 2.0 plugin introduces significant enhancements over the original version, streamlining the workflow for burned area detection, severity analysis, and validation.

SCL Band Masking
Mask out unwanted Scene Classification Layer (SCL) classes from Sentinel-2 imagery in both pre-fire and post-fire datasets.
This process removes noise (e.g., clouds, water, snow) and significantly improves classification accuracy.

OWA Layer Preview
Visually inspect Ordered Weighted Averaging (OWA) layers to select optimal threshold values for generating seed and grow layers.
An interactive preview helps fine-tune thresholds using real-time image feedback.

Burned Area Map Validation
Validate the burned area output by comparing it with reference data through a confusion matrix.
Compute metrics such as:

Commission/Omission Errors

Dice Coefficient

Pixel-wise Agreement Map generation

Burn Severity Validation
Assess burn severity by reclassifying and comparing severity layers with reference data.
Includes:

Full error matrix computation

Exportable accuracy metrics for reporting

Modular Workflow
Each tab in the plugin operates independently.
Users can:

Start at any stage (e.g., OWA, Region Growing)

Use intermediate outputs as inputs
This modularity enhances flexibility and efficiency.

📊 Export Validation Results
All validation outputs—including confusion matrices and accuracy metrics—are exportable in .html format, ready for reports or scientific publications.

🌐 QGIS Native Integration
Seamlessly integrated into the QGIS environment with:

A PyQt-based graphical interface

Support for native raster and vector operations
