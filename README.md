# Skylanders-NFC-guide

You need:
 -ACR122U NFC Reader/Writer
 -NFC Tags that are 13.56MHZ,Rewritable UID and 1K Storage
 -MifareOneTool: https://github.com/xavave/MifareOneTool-English
 -Skylanders NFC DUMPS: https://shorturl.at/mswy0 (From TheVault Discord Server)
 -ACS ACR122U Driver:https://www.acs.com.hk/en/driver/3/acr122u-usb-nfc-reader/
 -Skylanders GUI Tool (optional):https://www.pyrofersprojects.com/blog/skylanders-gui-tool/
 -Skyreader (optional): https://github.com/hegyak/SkyEditGUI/releases/tag/Alpha-6
 -Skylanders Portal (optional)
 -Skylanders NFC cards cover pictures (optional):https://drive.google.com/drive/folders/1pOTIA9LpLQ5l1LigjtjOMyvrhUv9bYC9 (from spenny discord server)
 -Inkscape (optional):https://inkscape.org/
 -Color printer (optional)
 
Step 1:
 Extract the folder with the drivers
 On Windows install the drivers by opening the MSI file and following the steps
 You may also be able to install the drivers on Mac/Linux but you will have to use other software for writing the NFC cards (may on linux it will work with wine)
 On Mac open the DMG file to install
 On Linux install pcsc lite then run the configure file in the folder and use the make and make install command
 could be a bit difficult to install, look for guides online and you also need other things to install for that

Step 2:
 Extract [skylandersdumps].zip
 Open the folder with the dumps
 Look for the Skylanders you want to make
 
Step 3:
 Connect the NFC Reader/Writer
 Put an NFC Card on the reader
 Extract MifareOneTool.zip
 Open MifareOneTool.exe
 Click on 'Detect connection' and make sure its connected and the card is readable
 Click on 'Write (UF) UID card' or 'Write C/FUID Card' i tried both and it doesnt matter what option you click on but dont lock the card
 Select the DUMP of the Skylander you want
 After that you should get an output like that:
 
	starts executing UID card writing...
	nfc-bin64/nfc-mfclassic.exe uses libnfc 1.8.0
	1 device(s) found using pcsc driver with connection string: pcsc:ACS ACR122 0 
	1 device(s) found using acr122_pcsc driver with connection string: acr122_pcsc:ACS ACR122 0 
	Unable to open NFC device: pcsc:ACS ACR122 0
	NFC device: ACS ACR122 0 / ACR122U216 found
	NFC reader: ACS ACR122 0 / ACR122U216 opened
	Found MIFARE Classic card:
	ISO/IEC 14443A (106 kbps) target:
		ATQA (SENS_RES): 0f  01  
		UID (NFCID1): cf  d6  e5  fa  
		SAK (SEL_RES): 88  
	RATS support: no
	Guessing size: seems to be a 1024-byte card
	Sent bits:     50  00  57  cd  
	Sent bits:     40 (7 bits)
	Received bits: a (4 bits)
	Sent bits:     43  
	Received bits: 0a  
	Card unlocked
	Writing 64 blocks |................................................................|
	Done, 64 of 64 blocks written.
	
  For Swappers make one card for the top and the other one for the bottom
  Traps also work like Skylanders
  
Step 4 (optional): 
 Extract SkylandersGUITool.zip or Skyreader.zip
 Open Skylanders GUI Tool.exe or Skyreader.exe
 Click on 'Portal' and then on 'Connect' or 'Connect to portal'
 Put the NFC card on the portal
 Click on 'Portal' and then on 'Read Figure' or 'Read Skylander from portal'
 If your figure shows up it works and optional you can edit gold level and skill path in skyreader and then click on 'Portal' and then 'Write Skylander to portal'
 
Step 5 (optional):
 Install Inkscape
 Extract the Skylanders NFC Cover Pictures
 Open Inkscape
 Create a new file
 Drag and drop the Skylanders pictures in Inkscape (max. 9 per page)
 Make them all 54x85mm
 Put them on the Page
 Click on 'File' and then on 'Export'
 Export as png or pdf
 Print it
 Cut all the pictures in perfect size
 Put them on the cards with glue or tape



DONE!!!!
