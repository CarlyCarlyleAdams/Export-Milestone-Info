# Export-Milestone-Info
An easy, simple way to get a list of IP, MAC and Hardware Name information out of Milestone VMS.
I needed a simple, straightforward method, something an end-user or junior technician can achieve without installing something on the NVR using the Milestone Management application.
So, I extracted the data required for the exportable config .XML file for the older versions of Milestone and the newer versions from the Configuration PDF. (Note: this gets the hardware name, not the camera name. Also, DO NOT export Devices with the PDF) 
I did this in Excel with VBA. I'm not an expert with VBA, so if you can contribute, please share it.
The VBA workbook loops through the data and populates it in a usable table.
