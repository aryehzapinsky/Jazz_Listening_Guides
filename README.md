# Advanced Jazz Listening Guides

The goal of this project is to create more interactive listening guides for some jazz pieces from a jazz history class in Columbia University.

Initially, I tried using a package called aubio and tapestrea to track the beat. These initial attempts were unsuccessful.

Then, I found a python package called Librosa and a website called Music Information Retrival. These two resources furthered the quest to track beats and plot the results. You can check the References page/file for more details.

To plot the results, I initially tried using Matplotlib but that resource does not allow for variable interval duration between images. So I save the images locally to a tmp file and then use FFMPEG to combine the plot images with variable intervals. Once again, more details follow in the References page/file.
