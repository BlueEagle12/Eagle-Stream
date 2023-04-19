# Eagle Stream

### Usage

- Download the master branch
- Extract the folder 'EagleStream' into your MTA resources dictonary
- Start 'EagleStream' then start any map or resource that use the EagleStream functionality.

# File Formatting

### MSD - (MTA-Stream-Defintions) [Previously JSD]
`ID(Nick Name) ,dff file name ,txd file name ,col file name ,drawdistance(170-300) ,Alpha Flag(boolean) ,Backface culling(boolean) ,Assign low LOD(boolean) `

#### Example
`ugoeast_zem294,ugoeast_zem294,southland,ugoeast_zem294,290,false,false,true`

### MSP - (MTA-Stream-Placement) [Previously JSP]
###### Line 1
`X-Offset,Y-Offset,Z-Offset` - World offset
###### Other Lines
`ID(Nick Name) ,Interior ID ,Dimension ID,x Position,y Position,z Position,x Rotation,y Rotation,z Rotation`

#### Example
`gados_p3a,0,-1,2060,1376,17,0,0,90`

# Folder Structure
## /Root

```
meta.xml (Meta file, defines file locations)
gta3.MSD (Object Definitions)
gta3.MSP (Object Placement)
```
## /Content

### col (COL dictonary)
`object.col` - Contains the collision files
### models (DFF dictonary)
`object.dff` - Contains the model files
### textures (TXD dictonary)
`object.txd` - Contains the texture files

Want to help support development? Buy me a Pepsi

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/BlueJayL)
