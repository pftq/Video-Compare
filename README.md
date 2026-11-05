# Video-Compare
Compares 2 videos that should be the same (excluding slight compression differences).  Useful for identifying bad exports.  Also works on audio/music.

Download link: https://github.com/pftq/Video-Compare/releases/tag/20261102

You may also find these useful (one-click to download all [here](https://drive.google.com/drive/folders/1nvQFC5uwsZlf-82LuskCP-qut9xHw-lt?usp=sharing)):
- [Video Debanding](https://github.com/pftq/Video-Debanding) (fixes quality issues with repeat re-processing/compression)
- [MP4 Audio Delay Fix](https://github.com/pftq/MP4-Audio-Delay-Fix) (20ms delay at start of file)
- [Video Frame Sync](https://github.com/pftq/Video-Frame-Sync) (syncing 2 files that drift out of sync)
- [Video Color Match](https://github.com/pftq/VideoColorMatch) (correcting color grading drift)
- [Screencaps Generator](https://github.com/pftq/Screencaps-Generator) (smart screencaps selection + gallery grid sheet)

This is sensitive enough that it picks out the fact MP4s introduce a slight 20ms delay in the audio start (so re-exporting the same MP4 multiple times will cause the video/audio to be out of sync).

<img width="861" height="706" alt="image" src="https://github.com/user-attachments/assets/9d732361-b19a-446e-b88e-99991ae8fa4d" />

Also lets you drill down on exact differences between videos at a frame by frame timestamp level
<img width="862" height="702" alt="image" src="https://github.com/user-attachments/assets/2154b843-0635-41ff-b151-eebb9a493d6b" />

<img width="871" height="686" alt="image" src="https://github.com/user-attachments/assets/30704326-5d2d-4aa8-b485-979b4040850d" />

And comparing music files - it's able to detect the pops I fixed in mastering on a song.
<img width="860" height="703" alt="image" src="https://github.com/user-attachments/assets/f124a4ca-463f-4bc3-9831-30adf93d0276" />


Credits:
- [Python](https://www.python.org/) — application runtime
- [Tcl/Tk](https://www.tcl.tk/) via Tkinter — desktop interface
- [PyAV](https://github.com/PyAV-Org/PyAV) and
  [FFmpeg](https://ffmpeg.org/) — media decoding and encoding
- [OpenCV](https://opencv.org/) — image processing and optical flow
- [NumPy](https://numpy.org/) — numerical processing
- [Pillow](https://python-pillow.org/) — image previews
- [PyInstaller](https://pyinstaller.org/) — Windows application packaging
