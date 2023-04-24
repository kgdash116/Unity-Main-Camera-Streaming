
# TP Unity Main Camera Streaming

## Requirements
- Unity editor version > 2021.3.0
- PyCharm IDE
- Python interpreter 3.9

<br>

## Steps for loading the scripts for camera streaming in Unity

- Open up a project in **Unity** (premade/new project).
- Drag and drop the `CameraStreamer.cs` file into the Assets portion of the opened project.

![image](https://user-images.githubusercontent.com/101527504/234135225-74f93c83-f974-4c3d-919c-ea377dad05c6.png)

- Select the main camera component from the Hierarchy section.

<p align="center">
  <img width="176" height="400" src="https://github.com/kgdash116/Unity-Main-Camera-Streaming/blob/main/images/hieracrchy.png?raw=true">
</p>


- In the Inspector's section of the main camera component, click the Add component menu.

<p align="center">
  <img width="286" height="400" src="https://github.com/kgdash116/Unity-Main-Camera-Streaming/blob/main/images/add%20component.png?raw=true">
</p>




- Next, select scripts from the menu.

<p align="center">
  <img  src="https://github.com/kgdash116/Unity-Main-Camera-Streaming/blob/main/images/scripts.png?raw=true">
</p>



- A list of available scripts in the environment's Assets section will be displayed.
- Select the `CameraStreamer.cs` script from the available options.


<p align="center">
  <img  src="https://github.com/kgdash116/Unity-Main-Camera-Streaming/blob/main/images/camera%20streamer.png?raw=true">
</p>



- The script will be added to the main camera component.

![image](https://user-images.githubusercontent.com/101527504/234135615-e874523e-578a-4e68-b73b-b986a92e8abf.png)


<br> 

## Steps for streaming the feed of the Unity's main camera.

- Open `tp_python_api` as a project in PyCharm or any other IDE.
- Select Python 3.9 as the Python Interpreter.

![image](https://user-images.githubusercontent.com/101527504/234138232-aba0c1fb-6d83-4754-b284-f95ea807b25c.png)

- From the Project menu on the left, where all the files and folders are displayed navigate to the test folder, inside the test    folder, navigate to the server folder and run `run_server.py` to start the server.

![image](https://user-images.githubusercontent.com/101527504/234135821-28854470-04b5-44ed-8bbb-e8c41a7335d8.png)

- A message of a successful server running would be displayed on the console.
- Now, run the  Unity environment in play mode.

![image](https://user-images.githubusercontent.com/101527504/234135911-d18c4118-289a-4451-98b7-1b50cdc7d6a5.png)

- Next, under the test folder navigate to the client folder and from there open and run the `cam_test.py` file.

![image](https://user-images.githubusercontent.com/101527504/234135968-7d25296d-9fa2-4c07-851c-39a41c31fa43.png)

- If the conncection is valid, a 200 status repsonse code will be generated in the python console.

![image](https://user-images.githubusercontent.com/101527504/234136060-a8d2469d-fc53-469a-ab44-bc2de3f21223.png)

- The stream from the Unity's main camera should start playing in a new OpenCV window.

![image](https://user-images.githubusercontent.com/101527504/234136088-d7c5ce30-a034-4f14-bad9-9bc087786045.png)
