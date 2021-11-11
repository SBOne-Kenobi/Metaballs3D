# Metaballs3D
3D visualisation of Metaballs (OpenGL)

## How to execute
1. Install Cmake (minimum version 3.12)
    - `apt install cmake`
2. Install GLEW
    - `apt install glew`
3. Install SDL2 (for example version 2.0.16)
    -  `apt install sdl2`
4. Clone repository
    - `git clone https://github.com/SBOne-Kenobi/Metaballs3D.git`
5. Build project with cmake
    - Create build-directory
    - Configure: `cmake ..`
    - On Windows:
       - Configure build with `-DGLEW_ROOT="<PATH TO GLEW>" -DSDL2_ROOT="<PATH TO SDL2>"`
       - Copy glew32.dll SDL2.dll libs to build-directory of project
       - Also need to build with Visual Studio toolchain on Windows (and install libs also for this toolchain)
    - Build: `cmake build .`
6. Run
    - `./Metaballs3D`

## Control
- Arrows to rotate scene
- WS to move forward and backward
- Space to pause graph
- Left ctrl and left alt to switch polygon mode
- 1 and 2 to turn on/off grid and isolines
- Whell on mouse to change detalisation of grid
- Wheel + left shift to change number of isolines
- Mouse left click creates metaball
- Mouse right click delete metaball

## Example
- [Video](https://disk.yandex.ru/i/uCrR7eI9gcMzlw) and screenshot

![image](https://user-images.githubusercontent.com/54807972/141285793-aacab208-2f2f-4c20-b5b0-f1b38829086d.png)

