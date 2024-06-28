# Car-Customization-Application-using-Augmented-Reality

### Project Overview

The Car Customization Application is a sophisticated augmented reality (AR) tool designed to enhance the car customization experience using ARFoundation. ARFoundation is a framework within Unity that allows developers to work with multiple AR platforms in a unified way. Although ARFoundation itself doesn't support AR features directly, it leverages the ARCore XR Plugin for Android to deliver a rich set of AR functionalities.

### Key Features

- **Plane Detection**: The application detects horizontal and vertical surfaces within the real environment, such as tables, floors, walls, and countertops. This markerless tracking allows virtual objects to be placed accurately on these surfaces.
- **Device Tracking**: The application tracks the device's position and orientation in physical space, ensuring that virtual objects remain correctly positioned relative to the user’s movements.
- **Light Estimation**: The AR system estimates the lighting conditions of the real environment, allowing virtual objects to blend seamlessly with the real world by adjusting their lighting accordingly.
- **Raycasting**: This feature helps in determining the exact point in the real world where the user wants to place or interact with the virtual object.
- **Session Management**: Efficiently manages AR sessions, ensuring smooth performance and a seamless user experience.

### Technical Implementation

Upon launching the application, the user's device camera provides a live feed of the real world, which acts as the AR camera. The application then performs plane detection, creating GameObjects for each detected plane. These planes are represented by their dimensions and boundary points, enabling the placement of virtual objects without the need for markers.

Users can place, scale, and rotate virtual car parts or accessories in the real environment. The rendering component of the application combines the live camera feed with the virtual objects, creating an augmented view that is displayed on the device screen. This integration of real and virtual elements provides users with a realistic preview of their customized car in the actual environment.

### Architectural Diagram

The Mobile Augmented Reality System Architecture Diagram illustrates the workflow of the application:

1. **Live Camera Feed**: Captures real-world images through the device's camera.
2. **Plane Detection**: Identifies flat surfaces in the environment.
3. **Device Tracking**: Monitors the device’s position and orientation.
4. **Virtual Object Placement**: Allows users to place and manipulate virtual objects in the detected planes.
5. **Rendering**: Combines real-world and virtual elements to create an augmented view.

### Conclusion

This Car Customization Application showcases advanced AR capabilities, leveraging the power of ARFoundation and ARCore XR Plugin to provide a seamless and immersive user experience. By enabling users to visualize and interact with virtual car customizations in their real environment, this project highlights expertise in AR development and demonstrates the practical applications of AR technology in enhancing user engagement and satisfaction.
