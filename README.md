#  Xfade1to2st
##  lv2 plugin utility , crossfade L R  in to 2 L R out

Two knobs parameter.

MIX:
- mix the input to the two outputs
- 
Range :
- at 0 , when mix is in the middle position, the output gain is 0.5 x the input gain for each output.
- at 1,  when mix is in the middle position, the output gain is 1x the input gain for each output. You can choose in between according to your needs. 

A slight smoothing is implemented in order to avoid scale effects. 

--------------------------

Mod devices installation 

• Copy the .lv2 plugin to your Mod: 
```
scp -rp <path to dm-GrainDelay.lv2> root@192.168.51.1:/root/.lv2
```
• Enter password "mod"

• Reboot Mod
