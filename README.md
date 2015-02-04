# APEXC3

Oracle APEX region plugin for generating charts using C3 based on D3 engine.

## If you want to use this plugin
### For tryout
If you want to test this plugin you only need to download and install as APEX plugin:

- region_type_plugin_tz_c3_charts.sql

Files are included in this installation. So there is no need to upload anything to your file server. For productive servers I don't recommend using this kind of installation. Files will be generated on the fly.

### For productive systems (with file access)
Download everthing from "productive" folder and upload files to your "/i/your_folder" directory of your APEX installation.
Download and install as APEX plugin:

- region_type_plugin_tz_c3_charts.sql

Open the uploaded plugin in Oracle APEX (shared components) and override in "settings" the default "file prefix" with:

#IMAGE_PREFIX#your_folder/

Replace "your_folder" with your individual path to where you have uploaded the files from "productive".
