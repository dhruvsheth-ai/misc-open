Hi, I’m Dhruv and this is my maker portfolio. Last Summer, I interned at Luxonis corporation to learn the intricacies of Spatial AI and its practical applications. Before the end of the term, I developed a tool called HapticCV, which bicyclists can plug onto a bicycle and receive alerts through tactile motors on a wristband depending on the depth and velocity of the vehicle detected.

To run object detection models that powerful processors can run easily on a small bicycle attached device, I quantized object detection models into smaller models. With this, HapticCV was able to detect objects in real-time despite its low computational efficiency. To calculate the depth and velocity of objects, I used a triangulation algorithm which uses projection lines from two monocular cameras to geometrically calculate the depth for all objects. Then, I used an opticalflow method to approximate the velocity through RGB as well as depth frames.

To alert the rider in real time, I extended Neosensory Bluetooth SDK to develop a bluetooth API between the tactile motors and Raspberry Pi running object detection. Then, I categorized the field of view into grids to send haptic signals on the wrist depending on the spatial location of the detected object. 

Finally, this tool was deployed on Bicycles in the form of a small form factor attachment. In the future, I’m looking forward to commercializing HapticCV with Neosensory corporation.