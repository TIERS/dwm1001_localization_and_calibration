# dwm1001_localization_and_calibration
Custom localization and calibration firmware for Decawave's DWM1001 Ultra-Wideband modules
## Installation
  1. Download Segger Embedded Studio (SES) version V3.34a (Note the version to ensure compatibility)
  2. Download Decawave's code example from https://github.com/Decawave/dwm1001-examples.git

## How to program the devices
# Initiator
	1. Go to dwm1001-examples/examples/ss_twr_init but replace the files ss_init_main.c and main.c with the ones of the same name provided in folder Initiator in this repository.
	2. Paste the file shared_var.h provided in this repository inside the folder dwm1001-examples/examples/ss_twr_init/SES/
	3. Open the project in Segger, set the device ID to the desired value and click Build and Run

# Responders
	1. Go to dwm1001-examples/examples/ss_twr_init but replace the files ss_init_main.c and main.c with the ones of the same name provided in folder Responder in this repository.
	2. Paste the file shared_var.h provided in this repository inside the folder dwm1001-examples/examples/ss_twr_init/SES/
	3. Open the project in Segger and click Build and Run
