# CPT205 3D Coursework

An interactive 3D graphics project for CPT205, built with C++, OpenGL and FreeGLUT.

## Project Files

- `cyber_travel.cpp` — application source code.
- `textures/` — all 20 BMP textures used by the project.
- `report.pdf` — coursework report.
- `test.exe` — original prebuilt Windows executable.

## Run the Included Executable

On Windows, open a terminal in the project root and run:

```powershell
cd textures
..\test.exe
```

The included executable uses the original texture filenames, so it needs
`textures/` as its working directory.

## Build from Source

Compile `cyber_travel.cpp` with a Windows C++ compiler and the OpenGL/FreeGLUT
headers and libraries configured. The updated source loads images from
`textures/`, so run a newly built executable with the **project root** as its
working directory. Keep the `textures/` folder when sharing the application.

The included `test.exe` has not been rebuilt from the updated source.
