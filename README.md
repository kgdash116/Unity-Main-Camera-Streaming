
# TP Unity Main Camera Streaming

## Requirements
- Unity
- PyCharm IDE

<br>

## Steps for loading the scripts for camera streaming in Unity

- Open up a project in **Unity** (premade/new project).
- Drag and drop the `CameraStreamer.cs` file into the Assets portion of the opened project.
- Select the main camera component from the Hierarchy section.
- In the Inspector's section of the main camera component, click the Add component menu and select scripts.
- A list of available scripts in the environment's Assets section will be displayed.
- Select the `CameraStreamer.cs` script from the available options.

<br> 
## Steps for streaming the feed of the Unity's main camera.

- Open `tp_python_api` as a project in PyCharm or any other IDE.
- Select Python 3.9 as the Python Interpreter.
- From the Project menu on the left, where all the files and folders are displayed navigate to the test folder, inside the test    folder, navigate to the server folder and run `run_server.py` to start the server.
- A message of a successful server running would be displayed on the console.
- Now, run the  Unity environment in play mode.
- Next, under the test folder navigate to the client folder and from there open and run the `cam_test.py` file.
- The stream from the Unity's main camera should start playing in a new OpenCV window.
