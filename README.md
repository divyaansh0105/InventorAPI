# Inventor API

The ExtrudeCommand application is a simple program that makes a part document,does a sketch and extrudes it.

## Prerequisites

Make sure you have the following prerequisites installed before running the application:

- Autodesk Inventor must be installed on your machine.
- Visual Studio to run the soultion.

## Getting Started

1. Build the ExtrudeCommand application using Visual Studio or any preferred C# IDE.

2. Run the application.

3. Click the "Establish Connection" button to establish a connection to the running instance of Autodesk Inventor. A message will indicate whether the connection was successful or if Inventor is not running.

4. Click the "Extrude" button to create a new part document, sketch a rectangle, and perform an extrusion.

## Functionality

The application performs the following tasks:

- Connects to an active instance of Autodesk Inventor.
- Creates a new part document.
- Sketches a rectangle on the default work plane.
- Extrudes the sketched profile to create a 3D object.

## Notes

- The extrusion distance and sketch dimensions are set in the code and can be modified according to your requirements.



