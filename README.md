# Lab Portfolio

| [Week 1](https://sjt4825.github.io/MCA-2022/#week-1) / [Week 2](https://sjt4825.github.io/MCA-2022/#week-2) / [Week 3](https://sjt4825.github.io/MCA-2022/#week-3) / [Week 4](https://sjt4825.github.io/MCA-2022/#week-4) / [Week 5](https://sjt4825.github.io/MCA-2022/#week-5) / [Week 7](https://sjt4825.github.io/MCA-2022/#week-7) / [Week 8](https://sjt4825.github.io/MCA-2022/#week-8) / [Week 9](https://sjt4825.github.io/MCA-2022/#week-9) / [Week 10](https://sjt4825.github.io/MCA-2022/#week-10) |

# Week 1

For the theme of my dataset I have chosen the English rock band Muse. The band consists of Matthew Bellamy (vocals & guitar), Chris Wolstenholme (bass guitar) and Dominic Howard (drums). In August 2022, they released their ninth studio album entitled "Will of the People".

Acoustic data for my theme can be found through every major music streaming platform such as Spotify or Apple Music as well as video platforms like YouTube. The acoustic data can be in the form of the official studio recordings as well as live performances or fan made covers. The band’s official website contains 30 second previews of all their songs facilitated through an embedded Spotify link. Acoustic data can be also be found on physical copies of their music such as CDs. The acoustic data is usually sorted into which album it is a part of.

Descriptive data can be found on the band's Spotify page. This includes things like the band members, the date the band formed, monthly listeners/followers, albums sold. It also has links to all their social medias as well as their Wikipedia page which includes more metadata about the band. On Spotify, the popularity of each song is analysed and is put into a top 5 popular songs area on the bands page.

In terms of notated data, there any many scores available on musescore.com but they are not free. Musescore allows you to sort these scores by things like the upload date and the relevance. Some analysis of the scores is needed to allow this sorting capability. Muse sheet music and guitar tablature is also available in the shop section of the band's website but it is also a paid product.

One challenge to working with music data is how a lot of the time sheet music is not in the public domain and therefore can't be accessed without making a payment. There are certain copyright laws that needs to be paid attention to before using any music or sheet music from the band in any of your own work. I have ran into a similar issue before when dealing with the use of music in things like YouTube videos. Some songs are blocked in certain countries, blocked altogether, or simply don't allow the video to be monetised.

Another challenge is that to find all this data you need to search through multiple differences sources, it isn't all found in 1 source.

# Week 2
[Back to top of page](https://sjt4825.github.io/MCA-2022/#lab-portfolio)

For week 2 our task was to find a piece of music relating to our theme to download and convert to Musescore files using Optical Music Recognition (OMR). We then had to edit the score to fix the parts where the OMR failed to accurately transcribe the piece.

I had difficulty finding a free score relating to my theme so I instead downloaded an image of a score preview on Google and converted it to a PDF using Microsoft Word.

The transcription managed to mostly detect the correct notes but it also missed out some notes and added random dynamic markings that were not in the original score. The transcription did not manage to include any of the metadata such as the title and composer. The transcription also combined all 20 bars into only 4 bars. This occurred as the software detected each 4 bars as a separate piano part and joined it all onto 1 system.  I was unsure of how to rectify this so I created new bars then pasted sections of the transcription onto them. I then edited it to correct the rest of the transcription.

## OMR Transcription
![OMR transcription](data/Week%202/OMR_transcription.png)

## Corrected Score

![Corrected score](data/Week%202/corrected_starlight_image.png)

# Week 3
[Back to top of page](https://sjt4825.github.io/MCA-2022/#lab-portfolio)

The first task for week 3 was to export the week 2 score to MusicXML and MEI. We then had to use Verovio to render the MEI file and experiment with changing the MEI code to see how it changes the score.

[Music XML file](data/Week%203/Starlight.musicxml)

[MEI file](data/Week%203/Starlight.mei)

The next task was to compare 3 different elements of the MusicXML and MEI files. The write-up for this task can be found [here](https://sjt4825.github.io/MCA-2022/verovio.html) 
# Week 4
[Back to top of page](https://sjt4825.github.io/MCA-2022/#lab-portfolio)

The task for week 4 was to make a jSymbolic analysis of my piece to extract relevant features of my piece and then use Python Notebook to create a piano roll, scatter plot of pitches and a pitch histogram of the piece. A pitch histogram displays how many times each pitch is used in a piece, this can allow us to make a good guess on what key the piece is in.

Here is the [jSymbolic analysis csv](data/Week%204/jsymbolic%20analysis.csv)

## Piano Roll
 
![Piano roll](data/Week%204/Piano%20roll.png)

## Scatter Plot of Pitches
 
![Scatter plot](data/Week%204/Scatter%20plot.png)


## Pitch Histogram

![Pitch histogram](data/Week%204/Pitch%20Histogram.png)

# Week 5
[Back to top of page](https://sjt4825.github.io/MCA-2022/#lab-portfolio)

For week 5 we were tasked to create a metadata schema of at least 5 elements that we can apply to our theme. The elements I chose to include are the title, composer, lyricist, band members (castList tag), album and encoder. We then had to add this metadata to our MEI file.

The updated MEI file can be found [here](data/Week%205/Starlight%20week%205.mei)

# Week 7
[Back to top of page](https://sjt4825.github.io/MCA-2022/#lab-portfolio)

The task for week 7 was to update our week 5 MEI file with genre and licencing information and display it on an HTML page.

The revised MEI data with the score can be found [here](data/Week%207/Starlight%20week%207.mei).

The revised MEI data with the score can be found [here](week7meta.html). 

I was not able to finish the formatting section of the task so the text is not in good shape. The score does not seem to appear on the webpage when the auth.uri attribute is included in the MEI file.

# Week 8
[Back to top of page](https://sjt4825.github.io/MCA-2022/#lab-portfolio)

For week 8 we had to pick 3 tracks relating to our theme. For each track, we had to make a table of metadata then create a spectrogram using Sonic Visualiser.

## Track Metadata Table

Title | Artist | Composer | Copyright Info | Genre | Source | File Format | No. of Channels | Sample Rate | Bit Rate | Duration
----- | ------ | -------- | -------------- | ----- | ------ | ----------- | --------------- | ----------- | -------- | --------
Psycho | Muse | Matthew Bellamy | All Rights Reserved WMG |Hard Rock | [YouTube](https://www.youtube.com/watch?v=UqLRqzTp6Rk&ab_channel=Muse) | .mp3 | 2 | 48KHz | 128kb/s | 5:50
Something Human (Acoustic) | Muse | Matthew Bellamy | All Rights Reserved WMG | Alternative Rock | [YouTube](https://www.youtube.com/watch?v=t9hYxA_OiVI&ab_channel=Muse) | .mp3 | 2 | 48KHz | 128kb/s | 3:46
Starlight (live) | Muse | Matthew Bellamy | All Rights Reserved WMG | Alternative rock | [YouTube](https://www.youtube.com/watch?v=R6f_7G71p_w&ab_channel=Muse) | .mp3 | 2 | 48KHz | 128kb/s | 4:18

## Waveform and Spectrogram for Psycho

![Psycho Waveform](data/Week%208/Psycho%20waveform.png)
![Psycho Spectrogram](data/Week%208/Psycho%20spectrogram.png)

## Waveform and Spectrogram for Something Human

![Something human Waveform](data/Week%208/Something%20Human%20waveform.png)
![Something human Spectrogram](data/Week%208/Something%20Human%20spectrogram.png)

## Waveform and Spectrogram for Starlight

![Starlight Waveform](data/Week%208/Starlight%20waveform.png)
![Starlight Spectrogram](data/Week%208/Starlight%20spectrogram.png)

With time-frequency analysis we are able to see a representation of the frequencies present in the recording as well as how often they appear. Whereas with waveform based analysis, it is a lot harder to pick out frequencies. Waveform analysis mostly shows us the amplitude of the sound as a whole but time-frequency analysis shows us the amplitude over the whole spectrum of frequencies.

At just before the 2 minute mark on the "Starlight" waveform, we can see that the amplitude of the sound has decreased. If however we look at the spectrogram for this same time period, we can see a lot of the lower frequencies have decreased but that the frequencies around 500-700Hz have stayed relatively the same amplitude as before. If we listen to the song at his section we can hear that the bass guitar has dropped out of the mix but there is still an electric guitar playing a melody in the upper range. This is represented by the spectrogram but not the waveform.

# Week 9
[Back to top of page](https://sjt4825.github.io/MCA-2022/#lab-portfolio)

For week 9 we had to choose 3 tracks then create a spectrogram, Mel Frequency Cepstral Coefficients (MFCC), and a chromagram for each track using Sonic Visualiser. We then had to use Python Notebook to create histograms for each of these.

For my 3 chosen tracks I chose a studio recording, a live concert recording and then an acoustic version of a song. This was for variety to hopefully be able to identify differences easier. 

## Psycho Histograms

### MFCC
![mfcc histogram](data/Week%209/psycho_mfcc_histogram.png)

### Chromagram
![chromagram histogram](data/Week%209/psycho_chromagram_histogram.png)

## Something Human Histograms

### MFCC
![mfcc histogram](data/Week%209/something_human_mfcc_histogram.png)

### Chromagram
![chromagram histogram](data/Week%209/something_human_chromagram_histogram.png)

## Starlight Histograms

### MFCC
![mfcc histogram](data/Week%209/starlight_mfcc_histogram.png)

### Chromagram
![chromagram histogram](data/Week%209/starlight_chromagram_histogram.png)

I decided to compare the MFCC histograms as an MFCC shows the timbre of the audio which to me is more interesting than the chromagram which looks at the pitch classes.  For the most part, the three recordings use the same or very similar instruments (electric guitar, bass and drums) and all have the same vocalist as they are from the same band. "Something Human" uses an acoustic guitar rather an electric guitar and does not have drums. "Starlight" includes a synth/keyboard which the other 2 tracks do not. "Starlight" also has crowd noises in the recording since it is from a live performance. If we look at the histograms for feature 2,3 and 4 we see that for "Starlight" the histograms has a 2nd hump or peak to the left of the main peak. This is not present for the others 2 tracks. This could perhaps be due to the extra synth texture and crowd noises. We can also see that the shape of the histogram for "Psycho" is not quite as tall as the other 2 tracks for feature 2, 3 and 4. For "Psycho" the shape of the histograms tend to be thinner than for the other 2 tracks. Overall the histograms for "Something Human" and "Starlight" seem to be the most similar. I wouldn't expect this from listening to the tracks especially consider "Something Human" is the only one to not use an electric guitar and not involve bass and drums. For all 3 tracks the shape of the histograms seem to be very similar. 

# Week 10
[Back to top of page](https://sjt4825.github.io/MCA-2022/#lab-portfolio)

For the first task we had to create a similarity matrix using python notebook for 3 tracks relating to our theme.

## Similarity matrix

![Similarity Matrix](data/Week%2010/week%2010%20similarity%20matrix.png)

The X and Y axes represent the track numbers and the colour represents the similarity between the tracks. 0 (dark blue) is the maximum similarity and around 2.5 (yellow) is the minimum similarity. As we can see in the similarity matrix, tracks 0-3 display high similarity with each other, this is expected as they are all classified as classical music. Tracks 4-6 are classified as rock music and as we can expect from this they are very similar to each other. Tracks 7-9 are tracks from my theme. These tracks are also in the broad rock genre and we can see that these tracks are quite similar to each other but also to the other rock tracks. Tracks 4-9 are not very similar to the classical tracks 0-3. 

After this, a polyphonic transcription was applied to the Musescore file from week 2. Overall the 2 scores are very different visually as well as for the musical content. The original file has been transcribed into both the wrong key and time signature. The transcription is in 3 / 4 which throws off the bar numbers significantly, making it harder to compare the 2 scores. The first 6 bars (first 4 in original piece) are almost unrecognisable, it has a similar rhythm but it doesn’t really have any similarities apart from that. 

After these first 6 bars, the transcription improves as it vaguely follows the original piece. However, there are many incorrect notes as well as added and missing notes. In the original piece there are only 2 notes being played at one time, however, in the transcription, there are up to 5 notes being played at the same time. The rhythm in many parts is also incorrect. There are also multiple clefs in the middle of the bars. It also misses out the dynamics and pedal markings. The repeat lines from the original score are not preserved. Despite all this, the tempo is correct.

## Original Score
![Original score](data/Week%2010/original%20score%20image.png)

## Sonic Visualiser Transcription
![Transcription](data/Week%2010/week%2010%20transcription%20image-1-1.png)
![Transcription](data/Week%2010/week%2010%20transcription%20image-1-2.png)
