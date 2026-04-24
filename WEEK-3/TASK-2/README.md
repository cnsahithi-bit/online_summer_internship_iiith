## TASK-2
# What we did
1.We created a combined video by stacking three different videos:
-->Raw video (original images)
-->Object detection video
-->Object segmentation video
All three were placed one above the other in a single output video so we can easily compare the results.
We also removed the original audio and added a new background music.

# tools used
1.vstack → Stacks multiple videos vertically (one above another)
2.hstack → Places videos side-by-side (horizontally)
3.scale → Resizes videos to the same resolution
4.-filter_complex → Applies multiple video/audio operations together
5.-an → Removes audio completely
6.-i → Adds an input file (video/audio)
7.-map → Selects which video/audio streams to include
8.-shortest → Ends output when the shortest input finishes
9.volume → Adjusts audio loudness
10.fps → Controls frame rate of the video

# output video
[output video](https://drive.google.com/file/d/1CLSHEmaRVdB51QtAssmPJjnIjYvOCzBy/view?usp=drive_link)
