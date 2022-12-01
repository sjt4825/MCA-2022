# Lab Portfolio

# Week 1
For the theme of my dataset I have chosen the English rock band Muse. The band consists of Matthew Bellamy (vocals & guitar), Chris Wolstenholme (bass guitar) and Dominic Howard (drums). In August 2022, they released their ninth studio album entitled "Will of the People".

Acoustic data for my theme can be found through every major music streaming platform including Spotufy, apple music, tidal, deezer. Studio albums aswell as live performance albums Aswell as video platforms like youtube. The acoustic data can be in the form of the official songs on the bands channel as well as fan made remixes or covers or live performances from concerts. The band’s official website contains 30 second preview of all their songs facilitated through an embedded spotify link. The band includes link to music videos. 

The meta data found on the Spotify include things like the band members, the date the band formed, monthly listeners/followers, albums sold. It also has links to all their social medias aswell as their Wikipedia page which includes more metadata about the band.

In terms of notated data, there any many muse scores available on musescore.com but they are not free. Muse sheet music aswell as guitar tabs are available in the shop section of their website but it is also a paid product.

One challenge to working with music data is how a lot of the time sheet music is not in the public domain and therefore cant be accessed without making a payment. There are certain copyright laws that needs to be paid attention to before using any music or sheet music from the band in any of your own work. I have ran into a similar issue before when dealing with the use of music in things like YouTube videos. Some songs are blocked in certain countries, blocked altogether, or simply don't allow the video to be monetised.

Another challenge is that all the data you're looking for most likely isnt all from the same source so you would need to visit a lot of different places to collect all the data you want.

# Week 2
For week 2 our task was to find a piece of music relating to our theme to download and convert to musescore files using Optical Music Recognition (OMR). We then had to edit the score to fix the parts where the OMR failed to accurately transcibe the piece.

I had diffculty finding a free score relating to my theme so I instead downloaded an image of a score preview on Google and converted it to a PDF using Microsoft Word.

The transcription managed to mostly detect the correct notes but it also missed out some notes and added random dynamic markings that were not in the original score. The transcription did not manage to include any of the metadata such as the title and composer. The transcription also combined all 20 bars into only 4 bars. This occured as the software detected each 4 bars as a seperate piano part and joined it all onto 1 system.  I was unsure of how to rectify this so I created new bars then pasted sections of the transcription onto them. I then edited it to correct the rest of the transcription

### OMR Transcription DEpedia.org
![OMR transcription](data/Week%202/OMR_transcription.png)

### Corrected Score

![Corrected score](data/Week%202/Corrected_week_2_score.png)

# Week 3

The first task for week 3 was to export the week 2 score to MusicXML and MEI. We then had to use Verovio to render the MEI file and experiment with changing the MEI code to see how it changes the score.

[Music XML file](https://github.com/sjt4825/MCA-2022/blob/master/data/Week%203/Starlight.musicxml)

[MEI file](https://github.com/sjt4825/MCA-2022/blob/master/data/Week%203/Starlight.mei)

The next task was to compare 3 different elements of the MusicXML and MEI files. The writeup for this task can be found [here](https://github.com/sjt4825/MCA-2022/blob/master/verovio.html) try just typing verovio.html

# Week 4

The task for week 4 was to make a jSymbolic analysis of my piece and then use Python Notebook to create a piano roll and pitch histogram of the piece. A pitch histogram displays how many times each pitch is used in a piece, this can allow us to make a good guess on what key the piece is in.

Here is the [jSymbolic analysis csv](https://github.com/sjt4825/MCA-2022/blob/master/data/Week%204/jsymbolic%20analysis.csv)

### Piano Roll

add scatter plot 
![Piano roll](data/Week%204/Piano%20roll.png)

### Pitch Histogram

![Pitch histogram](data/Week%204/Pitch%20Histogram.png)

# Week 5

For week 5 we were tasked to create a metadata schema of at least 5 elements that we can apply to our theme. The elements I chose to include are the title, composer, lyricist, band members (castList tag), album (seriesStmt tag) and encoder.


# Week 8

For week 8 we had to pick 3 tracks relating to our theme. For each track, we had to make a table of metadata then create a spectrogram.

### Waveform and Spectrogram for Psycho

![Psycho Waveform](data/Week%208/Psycho%20waveform.png)
![Psycho Spectrogram](data/Week%208/Psycho%20spectrogram.png)

### Waveform and Spectrogram for Something Human

![Something human Waveform](data/Week%208/Something%20Human%20waveform.png)
![Something human Spectrogram](data/Week%208/Something%20Human%20spectrogram.png)

### Waveform and Spectrogram for Starlight

![Starlight Waveform](data/Week%208/Starlight%20waveform.png)
![Starlight Spectrogram](data/Week%208/Starlight%20spectrogram.png)

With time frequency analysis it allows us to see a representation of how often each frequency is present in the recording, this can suggest which key the piece is in. Whereas with waveform based analysis it is a lot harder to pick out frequencies and they are not represented in a clear way, there is also no measure of how often each frequency occurs. We can see a representation of how prevalent each frequency and therefore note is.

Time frequency depicts frequency a lot more clearly than wavefrom analysis. It also shows us a lot more useful information than a waveform does


# Week 9
For week 9 we had to choose 3 tracks then create a spectrogram, Mel Frequency Cepstral Coefficients (MFCC), and a chromagram for each track. We then had to use Python Notebook to cretate histograms for each of these.

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
