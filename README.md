from pydub import AudioSegment

# Load the audio file
audio = AudioSegment.from_file("path/to/your/file.aac")

# Export as WAV
audio.export("converted_file.wav", format="wav")

