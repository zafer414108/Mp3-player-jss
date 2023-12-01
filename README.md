# Mp3-player-jss
This code is a JavaScript script that controls an audio player UI. Here's how it works:

It selects various HTML elements using the getElementById method and assigns them to variables.

It defines an array called songsList , which contains objects representing songs with properties such as name , link , artist , and image .

There are several functions defined to handle different functionalities of the audio player, such as playing, pausing, changing songs, and updating
progress.

The timeFormatter function is defined to format the time in minutes and seconds.

The setSong function takes an array index as a parameter and sets the audio source and other song details based on the selected song from the songsList array.

The playAudio and pauseAudio functions control the playback of the audio.

The nextSong and previousSong functions handle changing to the next and previous songs respectively.

The audio.onended event listener is set to automatically play the next song when the current song ends.

The progressBar.addEventListener event listener handles updating the progress bar and the current time of the audio when the user clicks on the progress bar.

The shuffleButton.addEventListener event listener toggles the shuffle mode of the player.

The repeatButton.addEventListener event listener toggles the repeat mode of the player.

The initializePlayList function populates the playlist songs dynamically based on the songsList array.

Various event listeners are set for UI elements such as play, pause, next, previous, and playlist buttons.

The setInterval function is used to update the current time and progress of the audio every second.

The audio.addEventListener event listener updates the current time of the audio.

The window.onload event listener is set to initialize the audio player when the page is loaded.

Let me know if you need any further assistance!
# MP3 GİF
![radio](https://github.com/zafer414108/Mp3-player-jss/assets/147662873/ec0cd971-5eb7-491f-ade4-b1d215563283)
