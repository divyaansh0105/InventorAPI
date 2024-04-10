# Inventor API

The ExtrudeCommand application is a simple program that demonstrates how to create a part document, sketch a rectangle, and perform an extrusion using the Autodesk Inventor API.

## Prerequisites

Make sure you have the following prerequisites installed before running the application:

- Autodesk Inventor must be installed on your machine.

## Getting Started

1. Build the ExtrudeCommand application using Visual Studio or any preferred C# IDE.

2. Run the application.

3. Click the "Connect to Inventor" button to establish a connection to the running instance of Autodesk Inventor. A message will indicate whether the connection was successful or if Inventor is not running.

4. Click the "Create Extruded Part" button to create a new part document, sketch a rectangle, and perform an extrusion.

## Functionality

The application performs the following tasks:

- Connects to an active instance of Autodesk Inventor.
- Creates a new part document.
- Sketches a rectangle on the default work plane.
- Extrudes the sketched profile to create a 3D object.

## Notes

- The extrusion distance and sketch dimensions are set in the code and can be modified according to your requirements.



