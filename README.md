# BAD_QGISplugin
Burned Area Detector is a plugin for Burned Area (BA) Detection from satellite multi-spectral images developed in GIS environment.
BAD implements a burned area and a burn severity mapping algorithm to produce output geo-products depicting the fire affected areas and the level of damage induced to the vegetation.
The plugin can be downloaded for free and installed in QGIS using the feature "Install from ZIP"
#BAD_V.2.0.0
The BAD 2.0 plugin introduces major enhancements over the original version to streamline the workflow of burned area detection and validation. These include:

#SCL Band Masking
Perform masking of unwanted Scene Classification Layer (SCL) classes from Sentinel-2 imagery for both pre-fire and post-fire datasets. This removes noise (e.g., clouds, water, snow) and improves classification accuracy.

# OWA Layer Preview
Visually inspect Ordered Weighted Averaging (OWA) layers to help select optimal threshold values for generating seed and grow layers. An interactive preview allows accurate threshold tuning using real-time image feedback.

✅ Burned Area Map Validation
Validate the burned area output by comparing with reference data using a confusion matrix. Compute accuracy metrics such as commission/omission errors, Dice coefficient, and generate a pixel-wise Agreement Map.

🔥 Burn Severity Validation
Validate burn severity output by reclassifying and comparing the severity layer with reference data, including full error matrix evaluation and export of metrics for reporting.

# Modular Workflow
Each tab in the plugin works independently—users can start at any stage (e.g., OWA, Region Growing) using intermediate inputs, enhancing flexibility and efficiency.

📊 Export of Validation Results
All validation results, including accuracy metrics and confusion matrices, are exportable in .html format for inclusion in reports or publications.

🌐 QGIS Native
Fully integrated within the QGIS environment with a PyQt-based graphical interface and support for native raster and vector operations.
