audio-string-audio
==================

Converting mp3 audio to and from base64 string

Here's a MP3 Base64 Encoder / Decoder widget. 
It outputs a Base64-encoded string representation of your sound file.
After the string is processed it decodes the Base64 into a Uint8Array typed array and stores it in arrayBuffer.
Once this is done the stored audio data is decoded using Web Audio decodeAudioData() function. 
We can now test the audio by clicking play/stop buttons.
