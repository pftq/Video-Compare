# Video-Compare
Compares 2 videos that should be the same (excluding slight compression differences).  Useful for identifying bad exports.  Also works on audio/music.

This is sensitive enough that it picks out the fact MP4s introduce a slight 20ms delay in the audio start (so re-exporting the same MP4 multiple times will cause the video/audio to be out of sync).

<img width="861" height="706" alt="image" src="https://github.com/user-attachments/assets/9d732361-b19a-446e-b88e-99991ae8fa4d" />

Credits:
- [Python](https://www.python.org/) — application runtime
- [Tcl/Tk](https://www.tcl.tk/) via Tkinter — desktop interface
- [PyAV](https://github.com/PyAV-Org/PyAV) and
  [FFmpeg](https://ffmpeg.org/) — media decoding and encoding
- [OpenCV](https://opencv.org/) — image processing and optical flow
- [NumPy](https://numpy.org/) — numerical processing
- [Pillow](https://python-pillow.org/) — image previews
- [PyInstaller](https://pyinstaller.org/) — Windows application packaging
