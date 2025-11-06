# emDepthFog 1.2
**emDepthFog** is a gizmo for creating 2D Fog and Sky Ramp using P or ZDepth channels, and also adding a subtle glow following these masks.

![emDepthFog_Knobs](https://github.com/user-attachments/assets/bf71838c-412c-4abe-bfb9-c80d09b40a2e)

You have control over where you want to pick the near and far points.

![emDepthFog_gizmo](https://github.com/user-attachments/assets/9b4b9592-441c-491c-ab44-9e1f283cdcd7)

# Updates
**Version 1.2**
* Improved Fog system (made it simple and better!). No need it more units knob.
* Added hardness knob in the Fog (depth/P) and Sky Ramp.
* Added falloff colors knob to blend between colors.
* Added mirror checbox to mirror the P fog (beta version)
* Added invert checkbox to invert the P and depth fog. 
  
**Previous versions**
* Added a Sky Ramp coming from the green channel (Y coordinate) to add pollution coming from the sky and sun.
* Picker knobs to position the sky ramp.
* Opacity knob for the sky.
* Start and end color for the sky.
* Glow now follows the depth fog and sky map. If the sky is disabled, it won't be affected by glow.
* Generate IDs for the FXs.
* Added new views in the view mode. 
* Pulldown choice of 'preview' to see the different views of the node: Final Image, Fog, Fog Color, and Glow.
* Pulldown choice of 'mode' to choose the P_World and depth mode. 
* Option to add additional color in the 'near' contribution.
* Premultiply fog, recommended use it for smooth results. 
* Opacity and color knobs for the fog.
* Unit knob to control the size of your near/far point relationship. 
* Some knobs from the emGlow gizmo (https://github.com/emateofabregas/emGlow) when this is following the Fog mask too.
