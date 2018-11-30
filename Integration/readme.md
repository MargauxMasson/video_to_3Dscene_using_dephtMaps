# video_to_3Dscene_using_dephtMaps

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
