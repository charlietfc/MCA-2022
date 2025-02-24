# Charlie Curtis MCA Project

[__WEEK 1__](https://charlietfc.github.io/MCA-2022/#week-1-write-up) | [__WEEK 2__](https://charlietfc.github.io/MCA-2022/#week-2-write-up) | [__WEEK 3__](https://charlietfc.github.io/MCA-2022/#week-3-write-up) | [__WEEK 4__](https://charlietfc.github.io/MCA-2022/#week-4-write-up) | [__WEEK 5__](https://charlietfc.github.io/MCA-2022/#week-5-write-up) | [__WEEK 7__](https://charlietfc.github.io/MCA-2022/#week-7-write-up) | [__WEEK 8__](https://charlietfc.github.io/MCA-2022/#week-8-write-up) | [__WEEK 9__](https://charlietfc.github.io/MCA-2022/#week-9-write-up) | [__WEEK 10__](https://charlietfc.github.io/MCA-2022/#week-10-write-up)

![image](French-composer-Claude-Debussy.webp)

## Week 1 

In my experience the challenges of working with music and music related data are situated in the finding of accurate and legitimate notated data. In terms of distribution both too much and too little can be a problem. Too much distribution can inevitably lead to studying or taking data off of a score that is inaccurate. Too little distribution can make it hard to find the data in the first place. This relates to my selected theme, the orchestral work of Debussy, as many different versions of his work exist online. Amongst this there are also various transcriptions and arrangements of his work too. Finding a clear and accurate score amongst the illegitimate ones can be difficult. In addition, as he is a very popular composer there are many different recordings and versions of acoustic data available. Too much choice and too many variations can make it hard to find a precise version. 

Debussy’s work is well documented and recorded. All of his scores are available in the public domain and are on imslp. Many recordings made of his work are on spotify. IMSLP also contains metadata on Debussy’s work.

P.S. In Week 2 I changed my focus from Debussy's orchestral work to his solo piano music. All of the above regarding distribution difficulties still apply. 

## Week 2

I started by thinking I would try to transcribe a Debussy Orchestral work, but on discussion with Josh I realized this would be hard to pursue later down the line due to transposing instruments. I then went for a debussy piece for cello and piano, The Cello Sonata prologue. But when I imported it into Musescore the score was almost unrecognisable, parts had been stretched out and voice parts had been added randomly. I thought it best to choose a simpler piece.

I ended up choosing Debussy's L51. The pdf imported well enough aside from the fact that it was in 2/4 whereas the original score is in 3/4. When I tried to convert it to 3/4 Musescore crashed. So I started switching the score to 3/4 in small chunks, working backwards. Josh then told me I could just do 20 bars which I easily converted. There were then not many changes to make to the score apart from the odd duration issue, missing note or missing articulations and dynamics. Later on I went back to change it to just 10 bars, I had to edit these myself but the basis was from the Musescore Transcription 

### 10 Bars of Debussy's Valse Romantique
![image](Debussy_Valsefr-1.png)

## Week 3 

[Verovio MEI Score and Write Up](https://charlietfc.github.io/MCA-2022/verovio.html)

## Week 4 

### jSymbolic Analysis of Valse Romantique 

![image](valsefeaturegraph.PNG)

![image](valsepitchclassgraph.PNG)


### Piano Roll and Histogram for Debussy's Valse Romantique, L. 71

![image](debussyvalsePR.png)

![image](debussyvalseHISTO.png)


## Week 5

Choosing a metadata schema: the choices of metadata I opted for was decided based on a combination of what I thought was necessary and the information I had available to me for the specific work I chose - Debussy's Valse Romantique 
these were the options I went for:

styleName - within 'title', indicates genre

respStmt - to give my name as having encoded the file 

persName - to give the composer's name 

distributor - within 'pubStmt' - gives describition of English distributor of French publishing

date - the date the piece was released 

publisher - gave French publisher

address - address of French publisher

notesStmt - to give information on licensing data 

## Week 7 

[Verovio Website With Metadata](https://charlietfc.github.io/MCA-2022/CCCss.html)

Here is my Verovio Website with the updated and formatted Metadata. As is visible I couldn't quite line everything up but the basic ideas are there. I did have to go back to edit the MEI file as it sometimes wasn't clear, such as with the publisher and the distributor, what the metadata was actually referring to. Therefore I had to add descriptive names in the MEI code.

## Week 8 

### Comparison Table

   | Content | Track 1 | Track 2 | Track 3 |
   | :------: | :------: | :------: | :------: |
   | **Title** | Valse Romantique, L. 71 | Images I, L110: III. Mouvement | Danse Bohémienne, L. 9 |
   | **Link To Recordings** | (https://www.youtube.com/watch?v=DGYGRtnYX0c) | (https://www.youtube.com/watch?v=W3GU4doYGAo) | (https://www.youtube.com/watch?v=NBNt3EkH8y8) |
   | **Artist** | Zoltan Kocsis | Jean-Bernard Pommier | Jean-Efflam Bavouzet |
   | **Composer** | Claude Debussy | Claude Debussy | Claude Debussy |
   | **Copyright Info** | Public Domain | Public Domain | Public Domain |
   | **Genre** | Impressionist Piano Music | Impressionist Piano Music | Impressionist Piano Music |
   | **Source** | Youtube | Youtube | Youtube |
   | **File/Audio Format** | MP3 | MP3 | MP3|
   | **Number of Channels** | 2 | 2 | 2 |
   | **Sample Rate** | 48kHz | 48kHz | 48kHz |
   | **Bits per second** | 128kb/s | 128kb/s | 128kb/s |
   | **Duration** | 3:05 minutes | 3:43 minutes | 1:58 minutes |

### Waveform, Spectrogram and MFCC for Valse Romantique, L. 71
 
 ![image](valse_waveform.png)
 
 
 ![image](valse_spectrogram.png)
 
### Waveform, Spectrogram and MFCC for Images I, L110: III. Mouvement 
 
 ![image](mouvement_waveform.png)
 
 ![image](mouvement_spectrogram.png)
 
### Waveform, Spectrogram and MFCC for Danse Bohémienne, L. 9
 
 ![image](bohemienne_waveform.png)
 
 ![image](bohemienne_spectrogram.png)
 
 An advantage of time frequency analysis over waveform analysis is that you can notice specifically 'musical' occurences within the piece through just a quick glance at the time frequency spectrogram. 'Musical' is obviously a broad term and in this context I mean something that would relate to the actual notes being played within the piece of music. For example in the time frequency spectrogram of Images I, L110: III. Mouvement it is easy to spot, near the end of the piece, an ascending phrase as a diagonal red line is showed on the graph. This would be very difficult to decode through the waveform. Another advantage is that the time frequency spectrogram shows the formants within the piece of music, these are noticeable in all of the graphs. As each of these pieces contain solo piano there is not huge variation in the formants shown, yet they are still interesting to observe as opposed to the waveforms which don't show them at all.
 
## Week 9 

### Spectrograms for the first 3 Debussy Preludes L. 117

#### Prelude 1. Danseuses de Delphes

![image](prelude1_spectro.png)

#### Prelude 2. Voiles

![image](prelude2_spectro.png)

#### Prelude 3. Le Vent Dans le Plaine

![image](prelude3_spectro.png)


### Chromagrams for the first 3 Debussy Preludes L. 117

#### Prelude 1. Danseuses de Delphes

![image](prelude1_chroma.png)

#### Prelude 2. Voiles

![image](prelude2_chroma.png)

#### Prelude 3. Le Vent Dans le Plaine

![image](prelude3_chroma.png)


### MFCCs for the first 3 Debussy Preludes L. 117

#### Prelude 1. Danseuses de Delphes

![image](prelude1_mfcc.png)

#### Prelude 2. Voiles

![image](prelude2_mfcc.png)

#### Prelude 3. Le Vent Dans le Plaine

![image](prelude3_mfcc.png)


### 20 MFCC Histograms and 12 Chromagram Histograms for Prelude 1. Danseuses de Delphes. L. 117

 ![image](Prelude_1_histograms.png)

 ![image](Prelude_1_12chromagrams.png)
 
 ### Prelude 2. Voiles. L. 117
 
 ![image](Prelude_2_histograms.png)

 ![image](Prelude_2_12chromagrams.png)
 
 ### Prelude 3. Le Vent Dans le Plaine. L. 117
 
 ![image](Prelude_3_histograms.png)

 ![image](Prelude_3_12chromagrams.png)
 
 
 
## Week 10 

### Debussy Preludes Similarity Graphs

![image](debussysimilaritymatrix.png)

### Debussy Valse Romantique Transcription Comparison 


#### Original Transcription 
![image](Debussy_L71_MEI-1.png)


#### Sonic Visualiser Transcription 
![image](Debussy_L71_midi-1.png)

There are several differences between the original Debussy Valse Romantique score and the sonic visualiser transciption. The sonic visualiser transcription is in 4/4 whereas the original piece is in 3/4. It also contains to lines of bass clef instead of a one bass clef and one treble clef. There is later constant switching between bass and treble clef in the sonic visulaiser transcription. Throughout the entire trancription there are countless melodic and rhythmic inaccuracies and the whole piece is ultimatly unrecognisable from the original score. Overall, it is a inaccurate transcription that has lost most of the original information form the score it is based off of. 

 
 
 
 
