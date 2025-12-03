# One One: AR Dog Application
One One is an augmented reality (AR) mobile application designed to support users’ mental and physical well-being through a virtual dog companion. Built as a team project at Ritsumeikan University, the app encourages light activity, relaxation, and digital companionship using AR features.
<br>

## Features
### AR Dog Companion
- Place a virtual dog on real-world surfaces using ground-plane detection.
- The dog performs multiple animations, including walking, running, eating, breathing, tail-wagging, and jumping.
- Dog sound effects are triggered when interacting with the dog.

### Interactive User Interface
- Includes Start, How to Play, and About Us screens.
- Page transitions handled through C# scripts.
- Custom-designed buttons and start screens created to match the app concept.
- Application icon and screen designs optimized for usability and visual appeal.

### Notification System
- Sends periodic reminders when users have not opened the application.
- Encourages users to relax, take breaks, or go for a walk.
- Notification frequency is adjustable.

### AR Experience
- Built using Unity and Vuforia.
- Detects surfaces or markers to place the dog accurately in the environment.
- Deployable on iOS devices through Xcode.
<br>

## Development Process
### 1. 3D Modeling and Animation (Blender)
- Designed the dog character from initial sketches.
- Created 3D models, adjusted skeletons, and animated movements.
- Exported models in FBX format for Unity integration.

### 2. Application Base (Unity and Vuforia)
- Implemented AR camera and ground-plane detection.
- Integrated the FBX dog model into Unity scenes.
- Used Unity’s Animator to control animation behavior.

### 3. Additional Features and UI
- Developed C# logic for page navigation and button interactions.
- Integrated dog sound effects.
- Designed multiple start screens and the final app icon.
- Experimented with object scanning for future interaction features.

<br>

## Results
The final application includes:
- A functioning AR dog with multiple animations.
- A simple and clean UI for navigation.
- Sound interaction connected to the dog’s actions.
- A working notification system.
- AR performance operating smoothly on iOS.
The application achieves the goal of promoting relaxation, mindfulness, and healthier daily habits.

<br>

## Challenges and Lessons Learned
Key difficulties during development included:
- Deformation of the dog model due to FBX export settings.
- Assigning actions to additional UI buttons due to limited Unity API knowledge.
- Implementing camera-following behavior for the dog.
- Time constraints that prevented completion of object-based interactions.
These challenges led to deeper learning in Unity development, AR systems, and collaborative teamwork.
<br>

## Future Improvements
Planned enhancements include:
- More reliable animation triggers.
- Camera-following behavior for the dog.
- Emotional system based on user interaction frequency.
- A virtual health system with pet hospitals using real map locations.
- Object recognition features that influence the dog’s actions.
- Interactions with real dogs or other users who are also using the app outdoors.

<br>
For more detailed explanations, diagrams, and development notes, please refer to the full project poster:
Poster PDF: [One One Project Poster (PDF)](https://github.com/yourusername/yourrepository/POSTER_LINK_HERE)


