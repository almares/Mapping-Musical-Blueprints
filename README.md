# Mapping Musical Blueprints and Psychophysiological States
Aaron Mares
April 22nd 2019
Professor Ahmed Helmy
CIS4930/6930  Mobile Networking


# Abstract
What speaks to your soul? The answer of course is nonlinear and can be discussed through such a wide variety of mediums and scopes that it could take years to process any one person’s response. Our group directs this question with a pressing emphasis on what would very likely be a common response to it: music. Music has for eons, both in the metaphorical sense and in the proven modern scientific world, struck chords within certain facets of an individual's makeup. Often described as a creative outlet, explosive force of expression, deeply emotional and moving pinnacle of human culture, or therapeutic enhancement, the potential of this art has only been scratched and the vast majority of its full applications could very well currently still be undiscovered.
We focus our energy on the last definition of music: therapeutic enhancement. The relatively new field of music therapy serves to aid in the human endeavors with the assistance of tonal harmony. We seek to provide a new layer to this innovative notion aimed at attaining higher individual aptitude. Through the monitoring of characteristics such as heart rate, cerebral flows, and blood pressure the introduction of music has shown to benefit specific sample spaces of groups in recovery, athletics, and stressful situations. We think the takeaways from these encounters can contribute to a resource that tailors to a broader audience while still offering a far more intimate reading and reflection of the individual self. 
Our study intends to monitor sample individuals throughout a variety of everyday tasks requiring different levels of focus, areas of the brain, and mental fortitude. Following the exposure to targeted genres of peak performance, the most effective selections for each subject will gradually steer playlists toward a closer person-specific medley of works that positively impact any given encounter. Essentially mapping out their tonal “blueprints,” our analysis will offer the prospect of a more applicable, evolving, and impactful musical therapist than ever experienced before.

# Motivation
Music therapy has long been an effective form of treating stress and anxiety and encouraging productivity and individual effort. This application intends to monitor the individual, determining the most effective music for them in a variety of scenarios. Our end goal intends to determine potentially effective music both by monitoring individual characteristics and, through proximity based networking, identifying the most intra-group specific qualities of the people you interact with the most and the locations you spend the most time in. Ultimately, we hope to provide a sort of music therapist and analyst of one’s own unique tonal blueprint, distinguishing the key factors that make an individual’s heart sing (and hopefully beat).

# Related Work
Many studies have been done to investigate the effectiveness of music on stress and anxiety. However, where all the studies fall short is in availability to the public. A study evaluating coronary heart disease patients [4] has quantitative data showing the effectiveness of music on the heart rates and blood pressure of patients. Other various sources have noted with importance the potential benefits of this field in such cases as in aiding recovering patients prone to anxiety, even to the same degree as prescribed preoperative sedatives [2] and reducing the risks and maladies of individuals with cardiovascular diseases [4]. Another particular study highlights the effect that music has on sports [3]. Investigating the effects of interjected songs in exercise, this unique application of music therapy claims that the use of music can be applied as both a stimulant or a sedative. The possibility of not only calming individuals but also enhancing them leads to the idea that proper music therapy can be applicable in a multitude of simulations (i.e sports, mental disorders, relaxation techniques, coronary problems).
Along with the effects of music therapy, work has been done in classifying music itself into subcategories. However, none of them appear to sort them by the effects on individuals, only by genre and interest. The three largest music listening services accomplish their own sorting in different ways. All tend to contain some combination of algorithms, comparisons to other music listeners, and expert created playlists. We believe that our application would implement the existing music recommendation algorithms in a way that would also take vital signs (and therefore their effects on the users) into account.

# Proposal
Problem statement: 
The potential of music is well-recognized, but we believe this art can yield much larger benefits as well as conveying of information regarding apparent patterns and relationships in the seemingly arbitrary mass musical movement occurring all around us. Can the potentially therapeutic effects of music be applied in determined situations to elevate our performance in those activities? Are there indeed specific “tonal blueprints” of individuals that play determining factors in what music “sings” to them most effectively? What time of day, if any, do we stand to gain the most from music therapy? Can we identify certain distinguishable musical groups that listeners tend to classify under? And if so, is there anything aside from the shared preference in tunes that identify these niches such as location, trajectory, periods of highest musical activeness, etc?
Evaluation Metrics: 
Various algorithms have been employed by numerous top streaming companies and listening stations, with nearly all employing quite unique methods for narrowing down millions of songs into a tailored selection specifically for the user. Some put great emphasis towards user behavior and collaboration, some implement machine learning to gather intel from musical hubs, others generate entire radios around tagged popular songs that mark taste characteristics, and some utilize the playlists of recognized artists and expert tastemakers. For our study, we feel it would yield the most illuminating results to initially start with broad lists of widely defined and quite distinguishable sound. Then, gauging the responses and execution of the participants these lists will begin tweaking and responding to the human reaction. This process will also take part within predefined activities, the primary identified ones being exercise, studies, and relaxation. Changes in heart rate and comparisons to a lack of music or intentionally detractful noises will all be used to measure effectiveness within each scenario. The deconstruction of the songs to cross-reference effective treatments is based on Spotify’s song characteristics since it provides an open API to their recommendation algorithm but these metrics can be extended if more resources become available (i.e. access to the actual algorithms used by the top companies). The deconstructions begin by defining tagged genre(s) and then expanding upon some following specified song parameters: 
Danceability:  how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity.
Range: [0.0, 1.0] (least to most danceable)
Duration of the song:
Measured in milliseconds (ms)
Energy: represents a perceptual measure of intensity and activity. (Typically, energetic tracks feel fast, loud, and noisy)
Range: [0.0, 1.0] (least to most energetic)
Instrumentalness: measures whether a track contains no vocals
Range: [0.0, 1.0] (more instrumental to less instrumental). A value over 0.5 aims to represent an instrumental track
Liveness: Detects the presence of an audience in the recording
Range: [0.0, 1.0] (low to high probability of the track being performed live). A tracks with a value above 0.8 is likely to be live recorded
Speechiness: presence of spoken words in the song.
Range:  [0.0, 1.0]
[0.66, 1.0] : tracks made entirely of spoken words
[0.33, 0.66] : tracks containing  both music and speech
[0.0, 0.33] : non- speech-like tracks
Tempo: the speed or pace of a given piece and derives directly from the average beat duration.
Measured in beats per minute (BPMs)
Investigated Parameter/Sample Space: 
Quite a large bit of emphasis will be on a significant period of time being allocated for each of these scenarios. Not only do we want to gear the bodies and heart into their natural rhythm, but map out the changes in response to a myriad of new sounds that will come and go during the task. Within each scenario, a playlist consisting of a multitude of specified music classifications will be shuffled through in random order and subjects heart rates will be incrementally taken at the beginning and culmination of tracks. Much of this study, at least the initial stages, will rely on the monitored progress and responses of each scenario. The size of this network will (for now) encompass a sample of the five members of the Captain Jacks, serving as pseudo hallmarks to the proposed musical definitions.
For our exercise scenario, we will look at impacts of various playlists within a traditional sports setting. Our targeted measured performance will occur in conjunction with any motion and physically exerting related activity - ideally running, biking, going to the gym, etc. The learning section will monitor individuals taking selected assessments, memory tests, and logic-based queries or focus-intense studies of relevant coursework. The relaxation scenarios can range from lying on one’s bed to practicing yoga, but all tasks within this will emphasize a calm environment and limited mobility while enforcing calming behaviors and emphasizing a freeing of thoughts.

# Methodology: 
Our methodology will entail significant amounts of heart monitoring and potentially mobility tracking. 
The predominant tool used, specifically for the gathering of our initial general music subsets, was that of Spotify’s API algorithm for sectioning music recommendations. Another significant asset used were wearable devices (i.e smartphone applications, fitbits, cardiometers) used to measure individual vital signs. After receiving the input of the vital signs, this information will be processed using the Python data science library PANDAS in order to analyze the performance and the tracks affecting it as well as accessing the Spotify API to provide new songs improving upon the last “targeted playlist” created. 
Expected results: 
Obviously, we would love to use music as an aid to better our own performances and abilities. We would anticipate a direct increase in focus while studying, motivation while exercising, and calmness while relaxing all with the continual use of our evolving playlists.

# Contributions
Intellectual Contributions:
The underlying foundation of our project was that of linking music to heart rate. Individuals can incite so much bias through popular opinion and ease of access towards what music they find motivating, and we sought to question with just how much clarity and faithfulness (as well as ease) we could reach out to a person’s musical niche through pure heart diagnostics. An immediate challenge presented at the start, and even still now, was how we could amass a proper representation of all music listeners through this study. We settled on taking our five members as a modest initial sample space of our larger community.
Effort Contributions:
We would wager the most principal aspect of our study was determining the most appropriate procedure for developing a responsive and uniquely tailored listing of tracks that would, through scientific backing via monitored heart rates, provide an individual with an invaluable boost during specified activities. The discovery and consequential implementation of Spotify’s API recommendation algorithm was influential in pinpointing the route we ended up taking, offering all the toggleable parameters desired for deconstructing music (early set divisions) as well as seed inputting tracks (later personal distinctions). A myriad of processes exist to produce  stimulating playlists, but ours accomplished this by quite literally following one’s heart.

# Results and Analysis
Parameters & Metrics Used: 
After considering the evaluation metrics for the songs explained in previous sections, the biological data must be analyzed to obtain results. 
The data properties evaluated in the different playlists vary according to the nature of the different scenarios.In all of the scenarios the mean value of the heart rate is used as reference, but we focused on different properties of the heart rate fluctuation.
Exercise: the maximum heart rate value recorded during the test is studied along with the mean value. 
In this case since the tests performed vary in various manners from one user to another (type of activity, duration, path, etc) therefore we compare the global maximum (the peak performance instant) achieved and then compare it to the mean value of the session to be able to fairly evaluate the results of the music. It would not be productive to compare a 10 minutes bike session with a 45 minutes run.
Relaxation: the minimum heart rate value recorded during the test is studied along with the mean value. 
Contrary to the previous case, in this scenario the test is constant for each user so we can study the changes in heart rate not only in the scope of an individual playlist but also the evolution of it along the different playlist iterations.
Studying:  the minimum heart rate value recorded during the test is studied along with the standard deviation.
A major change in a person’s heart rate might lead to lack of focus either due to excitement or due loss of energy, therefore in this case we value those playlists that keep a rather constant heart rate. The Standard Deviation is a measure used to quantify the amount of variation of a set of data values. The lower our standard deviation is the closer the values of the population are to the mean, therefore the heart rate has been kept constant. 
The song metrics are present throughout the tests as well. Each scenario was tested following applying an iterative music selection process. The initial iteration is based purely on the  song attributes which the Spotify API considers during the music recommendation process (as mentioned before). The initial teraton presents a global playlist containing three songs per studied genre, and two genres per scenario were considered, therefore the playlist contains 18 songs. This playlist was common for all the users, it helps to reduce the users bias since they will not know which are the songs that are supposed to affect their tests.
Now the iterative process begins: after each individual performing the corresponding tests, the two best performing songs in each genre of each scenario are drawn from the playlist. By now each user has the top performing song of each genre proposed at the beginning of the experiment thanks to the feedback received during the test.
In order to craft the next playlist, the top songs are grouped by scenario and run through the Spotify API. Thus, the top songs of each scenario are used as seeds in the algorithm parameters. This seeds are added to the parameters used in the initial iteration in order to get two new songs per genre resulting in  a total of 6 songs per scenario (one old and two new songs per  genre). This new playlist after the first iteration is still composed of 18 songs. It is a global playlist again meaning that it targets all three scenarios but this time it is not common to all users, since each one has different top songs. The global personal playlist is applied to the users again and the corresponding measurements take place.
The second iteration (the last one for us at least) results at last in three local playlists with music targeting exclusively the intended scenario. The process starts by selecting again the top two best performing songs for each scenario. Then both are used as seeds in the algorithm together with the song parameters targeting the first genre of the scenario (i.e. for exercise the two songs will be input seeds and then the parameters corresponding to hip-hop are input as well) in order to get 8 new songs. Then the same is applied to the second genre of the scenario (i.e. work-out instead of hip-hop this time). In the end we have 8 + 8 = 16 new songs and 2 old songs making a personal and local playlist of 18 songs for each targeted scenario.

# Data:
Exercise

Billy
(Mean, Max)
Original Playlist
149
162
First Iteration
132
159
Second Iteration
127
170


Frank
(Mean, Max)
Original Playlist
155
162
First Iteration
109
122
Second Iteration
116
131


Reflections
As explained in last section the exercise scenario is special since not all the tests carried out in the iterations presented the same characteristics, but by looking at the final iteration we see the common heart rate distribution of a sports session, the heart rate tends to increase over time as  the user exerts himself more and more.

The  main conclusion that we can extract out of the process graphs is that the difference between the mean and the maximum heart rate is wider when the specific playlist is applied which might not imply that the overall performance increases but certainly shows us the user being affected positively by the music at certain points.

Relaxation/Meditation

Billy
(Mean, Min)
Original Playlist
67
63
First Iteration
93
70
Second Iteration
54
50

Frank
(Mean, Min)
Original Playlist
134
126
First Iteration
86
83
Second Iteration
76
71

Freddie
(Mean, Min)
Original Playlist
87
84
First Iteration
86
81
Second Iteration
76
69


Reflections
We can observe consistently across the process graphs that as soon as the users start the relaxing test no matter which playlist is playing their heart rates lower. As in the exercise case this might occur due to the test’s own nature setting the trend that the users will follow (exercise will raise it while meditation will lower it). 

After comparing the changes in heart rate in each individual iteration we find that the rate of change is not consistent enough to draw conclusions. Although it certainly worked positively for Freddie the improvement is not significant with respect to the playlist of the first iteration on the rest of users. This might occur due to the close relation between relax and study songs (both of them are calm activities while exercise songs lie on the opposite side of the spectrum) therefore the initial global playlist already presents a decent percentage of songs with calming properties (66.66%. One third are calming songs and the other third are study songs). With a larger set of data and more time the differences between studying and relaxing music could be more closely studied but for the scope of this project the results are positive but inconclusive. 

Studying

Billy
(Mean, Std. Deviation)
Original Playlist
63
3.52
First Iteration
61
3.75
Second Iteration
69
5.21

Frank
(Mean, Std. Deviation)
Original Playlist
81
3.14
First Iteration
87
2.95
Second Iteration
86
5.50

Freddie
(Mean, Std. Deviation)
Original Playlist
82
2.76
First Iteration
80
3.49
Second Iteration
79
3.12


Reflections
Just by looking at the graphs there is not a significant improvement in the heart rate stability, in fact the results are slightly more negative. Again this most likely supports the fact that the study and relaxation songs have a similar effect and therefore the first playlists are already well suited for this task. Besides the heart rate results, regarding the performance of the study test, the users felt more focused and less tired after the specific playlist test than after the first two playlists.  The conclusion drawn after looking at the whole picture is that new metrics must be used to properly test the performance in studies, with a wider set of data and an evaluation system on the tests the results might change. 



# Comparisons
Our findings within the atmosphere of athletics mirrored the conclusions of other similar research focusing on the effects of music towards exercise [4]. These studies found positive correlations between perceived exertion and performance and the use of music. In our study within exercising, the disparity between the mean heart rate of participants during their entire workout and the maximum heart rate attained became more pronounced with the application of the customized playlists. This indicated that the presence of  person-centered resounding music led to a higher peak of physical exertion during exercise, regardless of the average intensity throughout the day’s cardio. Additional results clearly demonstrating an overall lowering and sedative effect of calming music on heart rates undoubtedly support therapeutic studies on cardiovascular health and coronary heart patients [2], [4].
An unexpected remark of our experiment were the fluctuations in our progressive data collections. While some scenarios’ heart rate BPMs better reflected an affected change brought on by the integration playlists, others seemed almost uncertain of themselves, either exhibiting miniscule overall changes or significant spikes followed by sharp drops. This is hindsight could very well be a factor associated with such a musically evolving methodology that requires both a mix of beneficial and lackluster trials with an individual to begin garnering a true sense of their auditory wiring.

# References/Relevant Links
[1] Listening to Music Affects Diurnal Variation in Muscle Power Output by H. Chtourou, A. Chaouachi, O. Hammouda, K. Chamari, N. Souissi 
https://www.thieme-connect.com/products/ejournals/html/10.1055/s-0031-1284398#N68741
[2] The effects of music on the cardiovascular system and cardiovascular health by Hans-Joachim Trappe 
https://heart.bmj.com/content/heartjnl/96/23/1868.full.pdf
[3] Psychophysical effects of Music in Exercise by Dr. Radhika Gujjala , Dr. G. Madhavi Latha, Dr. S. Usha Devi
https://pdfs.semanticscholar.org/0f98/5edbc3eef50a08913ef52a2b05c3f630e2d9.pdf
[4] Music for stress and anxiety reduction in coronary heart disease patients by J. Bradt, C. Dileo, N. Potvin
https://www.cochranelibrary.com/cdsr/doi/10.1002/14651858.CD006577.pub3/abstract
[5] Removement of the Three Minutes Irritating Music Produced No Incremental Relaxation by Wei-Ta Hsiao, Chung-Hung Hong, Hui-Min Wang
https://www.computer.org/csdl/proceedings/ibica/2011/4606/00/4606a057.pdf
[6] EEG monitored mind de-stressing smart phone application using Yoga and Music Therapy by Gautham Raj Vijayaragavan, R.L Raghav, K.P Phani, Vivek Vaidyanathan 
https://www.computer.org/csdl/proceedings/icgciot/2015/7910/00/07380498-abs.html
[7] The Influence of Music on Driver Stress by David L. Wiesenthal  Dwight A. Hennessy  Brad Totten https://doi.org/10.1111/j.1559-1816.2000.tb02463.x 
[8] Music Personalization at Spotify by Kurt Jacobson, Vidhya Murali, Edward Newett, Brian Whitman, and Romain Yon https://dl.acm.org/citation.cfm?id=2959120
Spotify Recommendation open-source API: https://developer.spotify.com/documentation/web-api/reference/browse/get-recommendations/

