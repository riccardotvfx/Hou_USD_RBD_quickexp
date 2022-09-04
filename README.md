# Hou_USD_RBD_quickexp
Hi, this is a quick exporter with USD Stitching for RBDs, it will take the transforms from the PTS and it will apply them on the render geo and on the proxy objs by using the instancer LOP node, the settings for the Stitching will become visible is you select a sequence instead of a single frame
There is a bug in Houdini 19.0.589 Stitch ROP node that doesn't allow to save the Stitch usd file in another folder but the file has to be put next to the sequence, if you find a way around it please let me know 

These are the settings for the *Frame Range*
![settings_sequence](/images/RBD_settings.png)
