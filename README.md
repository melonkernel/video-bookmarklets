# Video bookmarklets for productivity and fun

### Step 1
Create a folder in your bookmarks bar, called "v"

### Step 2
Create a bookmark with the name `3x` and give it this url `javascript:document.querySelector('video').playbackRate=3`
or drag one of these links to the folder [1x](javascript:document.querySelector('video').playbackRate=1) [1.5x](javascript:document.querySelector('video').playbackRate=1.5) [2x](javascript:document.querySelector('video').playbackRate=2) [2.25x](javascript:document.querySelector('video').playbackRate=2.25) [2.5x](javascript:document.querySelector('video').playbackRate=2.5) [2.75x](javascript:document.querySelector('video').playbackRate=2.75) [3x](javascript:document.querySelector('video').playbackRate=3) [3.25x](javascript:document.querySelector('video').playbackRate=3.25) [3.5x](javascript:document.querySelector('video').playbackRate=3.5)

### Step 3
Create a bookmark called `pip` with this url `javascript:(function()%7B%5Bdocument%2C...%5B...document.querySelectorAll(%22iframe%22)%5D.map(iframe%20%3D%3E%20iframe.contentDocument).filter(iframe%20%3D%3E%20!!iframe)%5D.some(d%20%3D%3E%5B...d.querySelectorAll(%22video%22)%5D.filter(video%20%3D%3E%20video.paused%20%3D%3D%20false%20%26%26%20video.ended%20%3D%3D%20false).some(video%20%3D%3E%20!!video.requestPictureInPicture().catch(err%20%3D%3E%20console.log(err))))%7D)()`
or drag this link [pip](javascript:(function()%7B%5Bdocument%2C...%5B...document.querySelectorAll(%22iframe%22)%5D.map(iframe%20%3D%3E%20iframe.contentDocument).filter(iframe%20%3D%3E%20!!iframe)%5D.some(d%20%3D%3E%5B...d.querySelectorAll(%22video%22)%5D.filter(video%20%3D%3E%20video.paused%20%3D%3D%20false%20%26%26%20video.ended%20%3D%3D%20false).some(video%20%3D%3E%20!!video.requestPictureInPicture().catch(err%20%3D%3E%20console.log(err))))%7D)())
