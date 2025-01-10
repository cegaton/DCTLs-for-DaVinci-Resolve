# DCTL
Some DCTLs for DaVinci Resolve.
Made mostly to simplify my life. 

Place in the LUT directory for resolve.

Linux: /opt/resolve/LUT
MacOS: /Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT
Windows: C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT

Channel_Viewer.dctl
Display individual channels as monochrome or multiple channels as combined color.
Different versions.

Lens Distortion
Based on https://github.com/thatcherfreeman/utility-dctls?tab=MIT-1-ov-file
Added a K3 Parameter 

Simple 3x3 Matrix

Restore Red Channel
Used to restore fade dyes on chromogenic film prints
by taking residual red channel infrmation on green and blue channel

Modify color channels
A simple RGB Channel mixer 
RGB with no luma compensation

Normalize color channels
Originally used for film restauration and changing distorted color channels
No luma compensation when changing RGB channels
