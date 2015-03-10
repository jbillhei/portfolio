### Code Samples

Right now this just contains the old TFTP server implementation from the (no longer public) Sapphire Operating System.

This module is actually no longer used, but demonstrates the threading, socket, and file APIs present in SapphireOS.

The socket API winds its way down to an 802.15.4 based radio, while the file system runs on a SPI flash memory chip.  The server could be used to transfer any files to and from the device, but was mostly used for firmware updates.

It's functionality has been replaced with the development of a more powerful command and admin protocol, so it was deactivated.

