# Scsi50F-to-IDC26

Little adapter to plug on the back of any 50 pin male scsi devices and output 13x2 (26pin) scsi hosts. Like Blizz* SCSI module for example.

# Pinout

From the 50 pin connector to the 26 pin connector.

(50 Female) 2 - 50 to (26 IDC Male) 1 - 25 signals.

(50 Female) 1-49 GND

(26 IDC Male) 26 not connected.

# Note

This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

If you like the project, buy me a beer or a Mercedes Benz SLR whatever you want :) - info@arananet.net

# Updates

12/11/2019: Updated license stuff (I usually not do this but I must start it with this).

12/09/2018 Fixed a problem with the scsi data pinout.

05/09/2018 Initial release.


# Images

<img src="https://github.com/arananet/Scsi50F-to-IDC26/blob/master/images/top.png?raw=true" width="700">

# Bill of materials

| Part          | Value                   
| ------------- | --------------------------------- 
| CONN1         | 2x25 pin female 2.54 connector  |
| CONN2         | 2x13 idc male 2.54              |

Also a IDC 26 female to female cable needed in order to connect the board to the host.

# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
