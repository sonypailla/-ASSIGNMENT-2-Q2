Convolution Operations with Different Stride and Padding

Student Information

Name: SONY PAILLA

Student ID: 700765443

Course: CS5720 - Neural Networks and Deep Learning

University: University of Central Missouri

Objective

The objective of this assignment is to perform 2D convolution on a 5×5 input matrix using a 3×3 kernel with different stride and padding configurations using TensorFlow.

Approach

Define Input and Kernel:

A 5×5 matrix is used as the input.

A 3×3 kernel (Laplacian filter) is used for edge detection.

Reshape Matrices:

Convert input and kernel into 4D tensors for TensorFlow.

Perform Convolution:

Apply tf.nn.conv2d() with varying stride and padding values:

Stride = 1, Padding = 'VALID'

Stride = 1, Padding = 'SAME'

Stride = 2, Padding = 'VALID'

Stride = 2, Padding = 'SAME'

Print Feature Maps:

The output feature maps for each case are displayed.

Results

The program successfully computes the convolved feature maps for all four configurations. The output varies based on stride and padding, affecting the dimensions of the resulting matrices.

Execution Instructions

1. Ensure you have Python 3.x installed.

2. Install required dependencies:

pip install numpy tensorflow

3. Run the Python script:
python convolution_operations.py

4. The output will display the feature maps for all configurations.

