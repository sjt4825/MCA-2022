# Lab Portfolio

# Week 1


## Dataset Theme
For the theme of my dataset I have chosen the English rock band Muse. 

# Week 2
For week 2 our task was to find a piece of music relating to our theme to download and convert to musescore files using Optical Music Recognition (OMR). We then had to edit the score to fix the parts where the OMR failed to accurately transcibe the piece.

I had diffculty finding a free score relating to my theme so I instead downloaded an image of a score preview on Google and converted it to a PDF using Microsoft Word.

The transcription managed to mostly detect the correct notes but it also missed out some notes and added random dynamic markings that were not in the original score. The transcription did not manage to include any of the metadata such as the title and composer. The transcription also combined all 20 bars into only 4 bars. This occured as the software detected each 4 bars as a seperate piano part and joined it all onto 1 system.  I was unsure of how to rectify this so I created new bars then pasted sections of the transcription onto them. I then edited it to correct the rest of the transcription



# Week 4

The task for week 4 was to make a jsymbolic analysis of my piece and then use Python Notebook to create a piano roll and pitch histogram of the piece. A pitch histogram displays how many times each pitch is used in a piece, this can allow us to make a good guess on what key the piece is in.

Here is the [jsymbolic analysis csv](https://github.com/sjt4825/MCA-2022/blob/master/data/Week%204/jsymbolic%20analysis.csv)

### Piano Roll

![Piano roll](data/Week%204/Piano%20roll.png)

### Pitch Histogram

![Pitch histogram](data/Week%204/Pitch%20Histogram.png)

# Week 8

For week 8 we had to pick 3 tracks relating to our theme. For each track, we had to make a table of metadata then create a spectrogram.

With time frequency analysis it allows us to see a representation of how often each frequency is present in the recording, this can suggest which key the piece is in. Whereas with waveform based analysis it is a lot harder to pick out frequencies and they are not represented in a clear way, there is also no measure of how often each frequency occurs. We can see a representation of how prevalent each frequency and therefore note is.

Time frequency depicts frequency a lot more clearly than wavefrom analysis. It also shows us a lot more useful information than a waveform does


# Week 9

For my 3 chosen tracks I chose a studio recording, a live concert recording and then an acoustic version of a song. The live concert recording has a lot of extra crowd noise which the studio recording of the first track does not have. The acoustic version has a lot less going on in it as it is only an electric guitar and a voice for the most part. COnsidering all this i would expect the histograms to be quite different to each other.

### Track 1 Histogram
![Track 1 histogram](data/Week%204/Pitch%20Histogram.png)

### Track 2 Histogram
![Track 2 histogram](data/Week%204/Pitch%20Histogram.png)

### Track 3 Histogram
![Track 3 histogram](data/Week%204/Pitch%20Histogram.png)

The psycho and starlight histograms for the chromagram generally have a higher amplitude which is expected as they are electric instruments with the use of drums whereas the something human track si acoustic so does not have as wide of a range of frequencies and is not of great of an amplitude

# Week 10
For the first task we had to create a similarity matrix using python notebook for 3 tracks relating to our theme.

### Similarity matrix

![Similarity Matrix](data/Week%2010/week%2010%20similarity%20matrix.png)

After this, a polyphonic transcription was applied to the musescore file from week 2. Overall the 2 scores are very different visually as well as for the musical content.
The original file has been transcribed into both the wrong key and time signature. The transcription is in 3 / 4 which throws off the bar numbers significantly, making it harder to compare the 2 scores. The first 6 bars (first 4 in original piece) are almost unrecognisable, it has a similar rhythm but it doesn’t really have any similarities apart from that. 

After these first 6 bars, the transcription improves as it vaguely follows the original piece. However, there are many incorrect notes as well as added and missing notes. In the original piece there are only 2 notes being played at one time, however, in the transcription, there are up to 5 notes being played at the same time. The rhythm in many parts is also incorrect. There are also multiple clefs in the middle of the bars. It also misses out the dynamics and pedal markings. The repeat lines from the original score are not preserved. Despite all this, the tempo is correct.

### Original Score
![Original score](data/Week%2010/original%20score%20image.png)

### Sonic Visualiser Transcription
![Transcription](data/Week%2010/week%2010%20transcription%20image-1-1.png)
![Transcription](data/Week%2010/week%2010%20transcription%20image-1-2.png)
