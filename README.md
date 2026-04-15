# Fluffy_slicer_bundle
This repo contains prusa-style configuration bundles for the TechLab 3D printer called Fluffy.

A config bundle is a zip file and is used to add system presets to PrusaSlicer  (and the PreFlight slicer).

The file has system presets for the printer (Fluffy), commononly used print profiles, and also common filament profiles.

Installation instructions:

1. Download the config bundle zip file from the "Releases" section of this repo.
2. Start PrusaSlicer on your computer.
3. In the "Printer" dropdown menu on the main screen, select "Add/Remove Printers", then "Add/Remove Presets". This will start the slicer Configuration Wizard.
4. On the left side of the wizards window, click on "Configuration Sources".
     A. In this window, uncheck the box next to "Other FFF" if it is checked.
     B. Click the "Load" button in the Local Sources section, and navigate to the zip file you downloaded. A Name, Description and source file should be listed and a gree checkmark.
5. Click Next and Prusa printers will be shown. Click Next again to get to the "Other FFF" page.
6. Check the box next to "BARN TechLab". The Click Next.
7. You should see available printer presets and a picture of Fluffy. If the box next to 0.4mm nozzle is not checked, check it.
8. Click Next. This is teh custom printer Setup page. Nothing to do here. Click Next again.
9. This is the Filament profiles section.
     A. Select TechLab Fluffy from the Printer column.
     B. Select (All) from the Tyep and Vendor columns, and the All button under the Profile column (or pick the filament profiles you want).
10. Click the Finish Button.

The Fluffy presets have been installed.  Select "TechLab Fluffy" from the "Printer:" drop down list in the "system Presets" section. This loads the Fluffy Print Settings, Filament, and Printer profiles. You should see the Fluffy build plate in the plater display. 

