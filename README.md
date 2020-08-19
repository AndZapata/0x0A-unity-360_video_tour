0x0A-unity-360_video_tour

| Task | Description |
|  --- | --- |
| 0. Tour guide | Create a project called 0x0A-unity-360_video_tour and adjust your Project Settings, Build Settings, and Player Settings according to the device you will be building for. Import the four video files (LivingRoom.mp4, Cantina.mp4, Cube.mp4, Mezzanine.mp4) into a folder called Videos in the Assets folders your project. Create a scene called 360VideoTour. Create a Sphere object called LivingRoom and position the VR camera in the center of it. Using the LivingRoom.mp4 video, a Video Player component, and a Render Texture, wrap the video to the Sphere such that the camera is “inside” the video |
| 1. Spheres of influence | Create three new Spheres for the remaining videos and name them accordingly. `Cantina`, `Cube`, `Mezzanine`. You may find that when running or testing your build, your headset or Unity itself may not be able to handle multiple videos or Render Textures at once. Keep videos disabled unless necessary |
| 2. Hotspots | Inside the LivingRoom Sphere, create a Button with the provided image to be a hotspot called CantinaHotspot and a text element with the text “Cantina” next to it |
| 3. The full tour | Create hotspots to link the rest of the Spheres together as illustrated in task #0. The user should start in the LivingRoom and be able to navigate through all four rooms and view the associated 360 video for each. Keep your Hierarchy in mind as you create new GameObjects and organize them accordingly |
| 4. Tell me more | In the LivingRoom Sphere, create a Button with the provided image that activates an informational text box when the user interacts with it |
| 5. Points of interest | Create similar text boxes for the remaining Spheres with the following information |
| 6. No need for silence | Create an Audio Mixer called BGMMixer with a new child group called Music. Apply it to the “Tech Live” audio and lower Music‘s Volume to -10.00dB |
| 7. Building tour | Create a build of the tour in a Builds directory and name it based on your targeted device (ex. 360VideoTour_<TargetHeadsetName> -> 360VideoTour_OculusGo) |
