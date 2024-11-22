# CS-330-Comp-Visualizations

Motivation
This project explores the power of OpenGL for rendering stunning 3D graphics and managing scenes. It was created as part of a learning journey to delve into the fundamentals of computer graphics and their real-world applications, such as game development, virtual simulations, and 3D modeling.

The project demonstrates key OpenGL functionalities, including scene rendering, managing 3D objects, and leveraging various graphics tools to bring visuals to life. This milestone-driven initiative is a testament to mastering C++ programming in tandem with graphics libraries.

Getting Started
Prerequisites
Before diving into this project, ensure you have the following installed on your system:

C++ Compiler: GCC, MSVC, or Clang
OpenGL: Minimum version 3.3
GLFW: For handling windows and user input
GLAD: OpenGL loader
Visual Studio IDE (optional, for structured development)

Clone the Repository:

bash
Copy code
   "git clone <repository-url>"
   "cd <project-directory>"
   
Install Dependencies:
Ensure that all required libraries (GLFW, GLAD) are installed and linked to your project.

Build the Project:
If using Visual Studio:

Open the solution file provided in the repository.
Set the build configuration to Release or Debug.
Press Ctrl + F5 to build and run.
For manual builds:
bash
Copy code
 "g++ -o OpenGLProject MainCode.cpp SceneManager.cpp ViewManager.cpp -lglfw -lGL -ldl
 ./OpenGLProject"
 
Usage
Running the Application:
Launch the project executable to view the rendered scenes. Experiment with object transformations, view manipulation, and lighting effects.

Key Features:

Render and interact with custom 3D shapes.
Modify scenes using the SceneManager.
Experiment with camera perspectives via the ViewManager.
Files Overview:

MainCode.cpp: Entrypoint for the application.
SceneManager.h/.cpp: Handles the creation and management of scenes.
ViewManager.h/.cpp: Controls camera and viewport.
3D Shapes: Stores custom 3D object definitions.

Tools
This project was developed using the following tools:

Visual Studio IDE: For C++ development and debugging.
OpenGL: Rendering API for high-performance graphics.
GLFW: For window management and input handling.
GLAD: OpenGL loader for function handling.
Microsoft Visual C++ Compiler: For efficient code compilation.
Blender/3D Modeling Software (optional): To create and export 3D assets for the project.

![image](https://github.com/user-attachments/assets/74a2fbb0-7fb3-4225-be65-300a37b0e74d)

![Screenshot 2024-08-24 225547](https://github.com/user-attachments/assets/ecc07636-78d8-438a-9632-cb44c626b6ea)

![Screenshot 2024-08-20 122002](https://github.com/user-attachments/assets/2ecdd497-97af-4bcf-abce-41b562d5c417)
