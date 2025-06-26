🔥 BAD_QGISplugin – Burned Area Detector v2.0.0
BAD (Burned Area Detector) is a QGIS plugin for detecting burned areas and mapping burn severity from satellite multispectral imagery (e.g., Sentinel-2).
Developed entirely within the QGIS environment, BAD produces geospatial outputs that highlight fire-affected zones and quantify vegetation damage.

🆓 The plugin can be downloaded for free and installed in QGIS using Plugins > Manage and Install Plugins > Install from ZIP.

🌟 Key Features in Version 2.0.0
BAD v2.0.0 introduces major improvements to enhance workflow flexibility, accuracy, and usability.

🛰️ SCL Band Masking
Apply Scene Classification Layer (SCL) masking to remove unwanted classes (e.g., cloud, water, snow) in pre-fire and post-fire Sentinel-2 images.
✅ Improves classification quality by eliminating noise and irrelevant pixels.

🧮 Ordered Weighted Averaging (OWA) Layer Preview
Interactively preview OWA composite layers to:

Tune thresholds for seed and grow layer generation.

Get real-time visual feedback.

✅ Helps users choose optimal parameters with higher precision.

🗺️ Burned Area Validation
Compare the generated burned area map with reference data to compute:

Confusion Matrix

Commission & Omission Errors

Dice Coefficient

Pixel-wise Agreement Map

✅ Offers detailed accuracy assessment and spatial agreement visualization.

🔥 Burn Severity Validation
Evaluate burn severity outputs by:

Reclassifying severity levels

Comparing them with reference data

Generating a full error/confusion matrix

✅ Suitable for advanced fire damage analysis and reporting.

⚙️ Modular Workflow Design
Each tab in the plugin is independent.
Users can:

Start from any stage (e.g., OWA, Region Growing)

Use intermediate files as inputs

✅ Flexible, user-driven workflow suited for different project needs.

📁 Exportable Validation Reports
All validation results can be exported in .html format, including:

Confusion matrices

Accuracy metrics

Dice coefficients and summary tables

✅ Ideal for documentation and research publications.

🧭 100% QGIS Native Integration
Built using PyQt for GUI and QGIS Python API

Fully compatible with QGIS native raster and vector layers

✅ Lightweight, fast, and easy to install.

📦 Installation
Open QGIS.

Go to Plugins > Manage and Install Plugins.

Choose Install from ZIP.

Select the BAD plugin ZIP file.

Click Install Plugin.
