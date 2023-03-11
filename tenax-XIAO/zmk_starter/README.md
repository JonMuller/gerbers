If you already have an existing ZMK repo, these files would all go in their own folder (of the same name. i.e. 'tenaxoled' or 'tenaxxiao') in your boards/sheilds folder.

Included are all the files you would need to compile working firmware. You can comment out the display portion if you want to go without a display.

If using an OLED display, use the files in the OLED folder. If using a nice!view, use the view folder. This setup DOES NOT require the extra nice!view shield. All the necessary SPI/display config is setup already.

Look at the .dtsi and the overlay files for the specifics on pin assignments for rows and columns.
