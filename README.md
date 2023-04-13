# logo

Repository for everything related to the eupnea logo.  
Contains the systemd service and the logo itself.  
Used by package building scripts.

The SVGs are converted to PPMs like this:

1. Import svg into GIMP
2. Scale to 512x512
3. Use built it "Crop to content" function of GIMP
4. Export as ppm and select "raw" as format