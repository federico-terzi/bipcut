[App](./app)

# bipcut
### What is bitcut?

**bitcut** is a small utility made using *Python*, *Scipy* and *FFmpeg*, that makes possible to extract video/audio clips using soundwaves. It uses a *Fast Fourier Transform* to detect when a specific soundwave is played in the video and, based on the tone frequency, cut or skip the clip.

Note: This is completely lossless using `ffmpeg copy` :)

##### Demo video

( Click on it to see it )

[![Demo Video](https://img.youtube.com/vi/Xq_35cm3jvI/0.jpg)](https://www.youtube.com/watch?v=Xq_35cm3jvI)

### Installation

Make sure to have Python 3 with *scipy* and *more_itertools* installed.

`pip3 install scipy more_itertools`

You will also need to install *FFmpeg* on your system, and add it to the PATH environment variable.

You can find the bipcut Android App here: https://github.com/federico-terzi/bipcut-remote

### Using bitcut

Using **bitcut** is pretty straightforward, just invoke it like this:

`python3 bipcut.py <INPUT_FILE> <OUTPUT_DIRECTORY> <OUTPUT_FORMAT>`

For example: 

`python3 bipcut.py /path/to/the/video.mp4 /output/directory mp4`

### License

```
MIT License

Copyright (c) 2018 Federico Terzi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
