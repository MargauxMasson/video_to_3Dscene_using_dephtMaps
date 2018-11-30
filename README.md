# video_to_3Dscene_using_dephtMaps
Purpose of this project is to produce a system that creates 3D videos using normal camera footage.
This is achieved by using certain camera tricks and giving the illusion of having stereo camera setup by exploiting the parallax effect. 

Implementation's steps (3 sprints): 
First Sprint:
- Take in two images that are some distance apart and create a depth map of the scene
- Recognize which direction the camera is moving based on a video
- Take a video and convert it to a depth map video

Second Sprint:
- Use tools to take the depthmap stream and the full video stream and create a 3D video
- Move the program to the AI embedded platform and test the performance
- Collect all of the functions into one executable file 
- Create an user UI in the Terminal in order to use the system

Third Sprint:
- Using CNN to extract a depth map from an image
- Integrate the depth map generation using CNN
- Update the user UI in the Terminal so the user can use to use the CNN depth map creator or not

The Integration folder contains all the modules integrated together: 
- Camera's direction detection 
- Image 2D to Depth Map
- OpenGL 3D scene creation
- Video to Depth map video
- Tests

## How to run this code

Open a terminal and run `python cli.py` (better to use python3 because of the Pytorch module).

And then follow the instructions in the terminal.

## Result examples

You can find some result examples in the folder 'results'. 
If you want to try out the examples, run: 
`python cli.py`, then choose 1) Save depthmap video; and write this path: `results/videos_examples/1.mp4`

## Tests

To run tests please use the following command:
`PYTHONPATH=. pytest -v`



Team members: Behnam Saeedi, Margaux Masson, Kamilla Aslami, Nghi Duong, Dhruv Jawalkar
Course CS561 Project: Software Engineering Methods