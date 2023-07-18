Motion Detection :

Description :

This is a motion detection program that uses a webcam or a video file as input to detect motion within the scene. The program utilizes computer vision techniques to compare frames from the input source and identifies regions where significant changes in pixel values occur, indicating motion. It provides a visual representation of the detected motion by drawing bounding boxes around the moving objects.

Table of Contents :

Installation
Usage
Configuration
Contributing
License

Installation

1. Clone the repository to your local machine:

git clone https://github.com/your-username/motion-detection.git

2. Change into the project directory:

cd motion-detection

3. Install any required dependencies (if any) by running:

pip install -r requirements.txt

Usage :

To start using the motion detection program, follow these steps:

1. Make sure you have Python installed on your machine.

2. Open a terminal or command prompt and navigate to the project directory.

3. Run the `motion_detection.py` script:

python motion_detection.py

4. The program will access your webcam or prompt you to provide a path to a video file for motion detection.

5. Press the `q` key to exit the program.

Configuration :

The motion detection program allows for some basic configuration options. These options can be modified in the `config.json` file. The available configurations are as follows:

- `min_area`: An integer representing the minimum area (in pixels) of a detected motion region to be considered significant. Smaller regions will be ignored as noise.
- `blur_kernel`: An odd integer indicating the size of the Gaussian blur kernel used to reduce noise in the frames.
- `dilate_iterations`: The number of iterations for the dilation operation, which expands the motion regions for better visualization.

Contributing :

Contributions to this project are welcome! If you find any bugs, have feature requests, or want to improve the code, feel free to open an issue or submit a pull request.

When contributing, please follow the existing coding style, and make sure to thoroughly test your changes.

License :

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as you see fit. See the [LICENSE](LICENSE) file for more details.

Credits :

The motion detection program was developed by SAHITH (https://github.com/SAHITHV). If you have any questions or need assistance, feel free to reach out to me. Happy detecting!
