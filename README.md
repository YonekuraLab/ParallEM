![Top](ParallEM.png)
# ParallEM
# Running parallel to other EM operating programs
GUI programs for controlling and monitoring the JEOL electron microscope through TEM External functional calls<BR>
Developed by Koji Yonekura<BR>
  &nbsp; ChkLensDef<BR>
  &nbsp; SamplePositioner (and 4k)<BR>
  &nbsp; SetDiff (and CryoARM300)<BR>
  &nbsp; Rotation (and CryoARM300)<BR>
  &nbsp; Flashing<BR>
  
Citations and usage<BR>
  &nbsp; https://doi.org/10.1016/j.jsb.2019.03.009<BR>
  &nbsp; https://doi.org/10.1016/j.jsb.2019.04.011<BR>
  &nbsp; https://doi.org/10.1016/j.jsb.2020.107549<BR>
  &nbsp; https://doi.org/10.1093/jmicro/dfaa052<BR>
  &nbsp; https://doi.org/10.3389/fmolb.2020.612226<BR>
  <BR>
  Installation<BR>
  &nbsp;&nbsp;1. Run ParallEM*.msi<BR>
  &nbsp;&nbsp;2. Run ParallEMbin.exe in C:\Program Files\ParallEM\ as Administrator<BR>
  &nbsp;&nbsp;3. Run Install.bat or InstallCRYOARM.bat in C:\Program Files\ParallEM\ as Administrator<BR>
<BR>
  Note<BR>
  Rotation<BR>
 &nbsp; The goniometer runs at 0.000841043 degree / pulse (for CRYO ARM and standard machine) or at 0.000252313 degree / pulse (special).<BR>
 &nbsp; You can check this value with JEOL Goniotools.<BR>
 &nbsp; Rotation shows the rotation speed as 0.000252313 * 1kHz * f, where f = 1, 2, 3, ... 12 for your reference.<BR>
 &nbsp; You can calculate the actual speed based on your gonio spec. in degree / pulse.<BR>
  ChkLensDef<BR>
 &nbsp; You can change default values for lenses and deflector coils in C:\ProgramData\ParallEM\chkLensRegistered.dat.<BR>

 
