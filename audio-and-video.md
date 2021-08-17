## AUDIO
We can add audio and Video to our web page to improve user engagement.
According to available statistics , users are not engaging more with video contents that mere texts or graphics.
Videos are viewed 10 times more than an image is viewed.

Images are good for conveying information but their stale nature is one disadvantage in their use.
An audio can help to convey spoken words that could be hard to express in writing while a video carries in it the sound and image to convey a point.
HTML5 provides the audio, and video element for achieving this.
To add an audio to a web page, use the general format as given below:
<audio src=” audio-location” loop autoplay controls>
 <!--Custom Message for unsupported devices--> 
 <p> This browser does not support the playing of audio </p>
</audio>
Let us look at the attributes available to an audio tag:
src: The value for the source attribute is the path to where the audio file is located.
The address could be relative or absolute.
If the audio could not be loaded, “This browser does not support the playing of audio ” will be displayed.
The content of the custom message is at your disposal. Choose what will resonate with your end users.
loop: To make an audio repeat whenever it gets to the end, you will use the loop attribute.
It can be written without any value or provided as loop=” true” 
autoplay: This attribute is an attribute with a boolean value and it instructs the browser to automatically start playing the audio file as soon as the page is rendered even without the user interacting with the file .
This should not be used as it could be annoying to users.
Users should interact with the document before playing the audio
controls: Controls are buttons that are used to influence the behaviour of the audio file like volume, playback, pause, and play
An example program will help to buttress our point the more. See the file below:
 

## VIDEO
To add a video to a web page, use the general format as given below:
<video loop autoplay controls>
    <source src=”video-location” type=”video format1”>
    <source src=”video-location” type=”video format2”>
    <p>Custom Message for unsupported devices </p>
</video>

Let us look at the attributes available to an audio tag:
src: The value for the source attribute is the location of the video file. This can be omitted in the video tab and the used in the source element.
The address could be relative or absolute.
If the video could not be loaded, “custom message for unsupported devices” will be displayed.
The paragraph inside the video element with  custom message is known as a fallback content . The fallback content will be displayed if the browser accessing the page doesn't support the <video> element , allowing us to provide a fallback for older browsers (MDN documentation) .
We use the <source> tag to provide different file formats that we intent to serve for differnet web browsers as browsers support differnt file format.
Loop, control, and autoplay act same way as with audio element.
An example program will help to buttress our point the more. See the file below:

