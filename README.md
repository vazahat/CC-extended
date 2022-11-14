# CC-level-editor


###### Below is the list of New API commands that we can use in the custom client.

**ccbGetAnimatedJointCount(animatednode)**                  <sub>  - Returns the number of bones(joint) of an animated scenenode	</sub>

**ccbGetAnimatedJointName(animatednode,jointIndex)**		     <sub> - Returns the name of the bone(joint) of an animated scenenode, joint index is the index of bone it should be less than the AnimatedJointCount </sub>

**ccbGetCurrentAnimationFrame(animatednode)**	         	     <sub> - Returns the current animation frame playing in the scene by the animated scenenode </sub>

**ccbSetCurrentAnimationFrame(animatednode, framenumber)**	 <sub> - Set the current animation to be played from a supplied animation framenumber. </sub>

**ccbSetAnimationFromSceneNode(node1, node2, animationname)**  <sub>	- Set animation of animated scenenode from the animation of another animated scenenode that poses same skeleton(rig). First node is to which the animation will be applied, second node is from which the animation will be used, Animation name is the name of the animation that should be used. </sub>

**ccbGetTextureWidth(texture)**					                    <sub>  - Returns the Width of a texture. </sub>

**ccbGetTextureHeight(texture)**					                  <sub>  - Returns the Height of a  texture. </sub>

**ccbPauseAllSounds(true/false)**					                 <sub>   - Pause and unpause all sounds node (True means pause, False means unpause).  </sub>

**ccbSetDopplerEffectParameters(DopplerFactor, DistanceFactor)**	<sub>- Sets the DopplerEffect parameters to a different value. CC uses (1.0,1.0) as default parameters.The value ranges from 1.0 to 10.0 </sub>

**ccbSetMousePos(mouseX,mouseY)**				                    <sub>	- Set new position of the mouse on the game screen </sub>

**ccbRenderToTexture(node, camera, material index, X resolution, Y resolution)**		<sub>- Captures the screen and apply it as a texture on a scenenode  </sub>

**ccbSplitScreen(cam1,x1,y1,x2,y2, cam2,x3,y3,x4,y4)**	<sub>	- Splits the Screen into two with 2 camera's rendering at the same time </sub>

->Fixed the bug for Texture parameter fo the external scripted extensions.

