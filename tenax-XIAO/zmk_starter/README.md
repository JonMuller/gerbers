If you already have an existing ZMK repo, these files would all go in their own folder (of the same name. i.e. 'tenaxoled') in your boards/sheilds folder.

Included is all the files you would need to compile for an OLED display attached. You can comment out the display portion if you want to go without a display.
I will also be adding a separate folder with all the necessary config for a Nice!view or other sharp memory display.

Look at the .dtsi and the overlay files for the specifics on pin assignments for rows and columns.
