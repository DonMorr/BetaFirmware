This repository contains beta firmware for download to Ciseco radio devices to configure the device for a specific function.
This firmware is under development and as such may not work as expected.

To download select the firmware you are interested to view the binary file and then press the RAW button (upper right hand of the text)
You can download the files for all devices by clicking on the "Zip" link

For Raspberry Pi/ Linux users: the move to git hub has change the line endings so you will need to run (for example)
awk 'BEGIN {RS="\n";ORS="\r\n"} {print $0}' llapThermistor-V0.56-24MHz.bin > llapThermistor-V0.56-24MHz-ok.bin
before uploading - otherwise you will get errors when uploading.

PLEASE READ THE RELEASE NOTES TO UNDERSTAND THE CHANGES AND DETERMINE IF THIS BETA FIRMWARE IS SUITABLE

Release notes can be found at the OpenMicros site
http://openmicros.org/index.php/articles/84-xrf-basics/224-firmware-release-notes

