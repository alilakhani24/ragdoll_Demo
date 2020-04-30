# ragdoll_Demo
This is a demo video of my ragdoll project. The code can be shared upon request 

### App platform 

Ali Lakhani 20671281 a25lakha openjdk version "12.0.2" macOS 10.13.6 High Sierra (MacBook Pro 2018)
This app was made on Android Studio and works for the Pixcel C on API 29 as required.

### Objective 

This application is a custom ragdoll. The human body ragdoll can be manipulated using direct manipulation. In addition the legs and feet can be enlarged (scaled) using pinch on the device. Other limbs can be rotated with custom restrictions as shown below. There are two resets allowing the user to reset the application with the generic human ragdoll or with the addition of a dog. Both can be manipulated simultaneously! Enjoy :) 

### Restrictions

- The torso is the only body part that can be translated.
- Touching and dragging the torso should move the entire paper doll. 
- The torso cannot be rotated. 
- All other body parts can be rotated around their contact point. 
- The head can tilt left and right relative to the torso, but should not deviate more than 50 degrees in either direction from the primary axis defined by the torso. 
- The upper arm is attached to the torso and may rotate an entire 360 degrees about its point of attachment to the torso. When rotating the upper arm, the lower arm should retain its same relative orientation to the upper arm. For example, if the lower arm is at a 30 degree angle relative to the upper arm, and the upper arm is rotated, the lower arm should retain its 30 degree angle relative to the upper arm. 
- The lower arm should have a movement range of 135 degrees in either direction relative to the primary axis defined by the upper arm. 
- The hand can pivot 35 degrees in either direction relative to the lower arm. It should maintain its same relative orientation to the lower arm independent of any rotations of the lower or upper arm. 
- The upper leg can pivot 90 degrees in either direction relative to the primary axis defined by the torso. The lower leg can also pivot 90 degrees in either direction relative to primary axis defined by the upper leg. 
- Assume the feet are attached at a 90 degree angle to the lower leg. Given this, they can pivot 35 degrees in either direction from this initial orientation. Upper and lower legs can be scaled. The upper and lower legs can each be "stretched" by scaling them along their primary axes. 
