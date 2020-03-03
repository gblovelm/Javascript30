Custom HTML5 video player with various custom controls.
CSS already done

Uses <video>..</video> tags in HTML then various DIVs for each of the controls.
Split the code into 3 sections:

1. Get the elements - e.g. 
```
const video = player.querySelector('.viewer');
```

2. Build out functions. e.g.
```
function togglePlay() {
  const method = video.paused ? 'play' : 'pause';
  video[method]();
}
```

3. Hook up the event listeners, e.g.
```
video.addEventListener('click', togglePlay);
```

skip buttons - anything that has a dataset.skip
Need to update volume and playback rate.

Use flex-basis 0% - 100% for horizontal progress bar.
Listen for timeupdate event then run handleProgress() function to update the flexBasis percent value.

scrub() function is used to update the video to where you click the mouse on the progress bar.
the mousedown flag is used so the the scrub function is not run if the mousedown flag = false.

Future enhancement idea:
 - add button to right side to make the video go full screen when clicked on. 
 Design uses CSS flexbox so can easily add one on the end of the current row.

