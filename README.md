# Sunset and Twilight using QT QML

## Project Description
This project is a Qt QML application titled "Sunset-Twilight" that simulates a dynamic sunset and twilight scene with various animated elements. Here's a brief description:


 - **Window Setup**:
The main window has a fixed size of 1400x700 pixels and displays the title "Sunset-Twilight."

 - **Background and Sky**:
A Rectangle named sky serves as the background, changing color in a continuous loop to simulate the transition from indigo to light blue and back.
 
 - **Mountain and Sea**:
An Image of mountains is placed at the bottom of the window.
A Rectangle with a gradient simulates the sea, with its colors animated to change gradually, creating a moving effect.

 - **Sun**:
A Rectangle represents the sun, which scales and changes color in a cyclical animation, while also moving up and down.

 - **Clouds**:
Multiple Cloud items are animated with different properties. They scale, rotate, and move in various patterns. One cloud (cloud2) changes its parent when clicked.
 
 - **Moon and Stars**:
An Image of the moon moves across the screen and triggers the creation and removal of star objects. The moon's movement is animated with a spring behavior, and stars are generated randomly when the moon reaches certain positions.
 
 - **Animations**:
Various animations are applied to elements, including color transitions, scaling effects, and movements. The animations use different easing types and durations to create a smooth and engaging visual experience.
The project aims to create a visually appealing and interactive representation of a sunset and twilight scene using QML's powerful animation capabilities. 

## Features


 > Perform an animation of the sunset and twilight using **`QT QML`**.

<p align="center">
  <img src="https://github.com/AdolfCarr/QML_sunset_twilight/blob/main/gifs/QML_sunset_twilight_3.gif" width="692" height="346" alt="Screen in QML Sunset-Twilight application">
</p>
<p align="center">

<p align="center">
  <em>Gif 1: Screen in QML Sunset-Twilight application</em>
</p>

## How to run the project
- **Open Qt Creator**: Launch Qt Creator on your computer.

- **Open Project**: Navigate to File -> Open File or Project... in the menu bar.

- **Select Project Directory:** In the dialog box, navigate to the directory containing your CMakeLists.txt file.

  - Select the folder that represents your project (it should contain your CMakeLists.txt file).
  - Click Open to load the project into Qt Creator.
- **Configure the Project**: Qt Creator will automatically detect the CMakeLists.txt file and configure the project. It may prompt 
you to select a build directory if it's the first time opening the project.

- **Build the Project**: After the project is loaded, you will see it in the Projects pane on the left side of Qt Creator.

  - If necessary, configure your build settings (like selecting a build kit or target).
  - Click on the hammer icon (Build Project) in the bottom left corner to build the project. This step compiles your code.

- **Run the Project**: Once the project is successfully built without errors, click on the green play button (or press Ctrl + R) to run the project.

- **View Output**: Qt Creator will show the application's output in the Application Output pane at the bottom of the screen. This pane displays any console output from your application.





