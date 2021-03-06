
# Links to AI / NLP / NLU courses (youtube)

Stanford AI CS221
https://www.youtube.com/playlist?list=PLoROMvodv4rO1NB9TD4iUZ3qghGEGtqNX

Stanford ML CS229
https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU

Stanford NLP CS224N
https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z

Stanford NLU CS224U
https://www.youtube.com/playlist?list=PLoROMvodv4rObpMCir6rNNUlFAn56Js20

Stanford CS 330 NLP and general concepts
https://www.youtube.com/playlist?list=PLoROMvodv4rMC6zfYmnD7UG3LVvwaITY5

Stanford 2012 NLP
https://www.youtube.com/playlist?list=PLoROMvodv4rOFZnDyrlW3-nI7tMLtmiJZ

Cornell CS4780 (much more math)
https://www.youtube.com/channel/UC7p_I0qxYZP94vhesuLAWNA/playlists

MIT 6.S191 (DL)
https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI

------------------------------------------------------

Mostly test and training sets that can be obtained easily in a few clicks. Other sources can be realy difficult to extract or require payment or downloading and running software to form the data (ie. CoNLL 2003...)

# Reuters dataset (from 1996) : 

https://archive.ics.uci.edu/ml/machine-learning-databases/reuters21578-mld/

* Example of content :

\<DATE> 24-MAR-1987 16:07:44.11\</DATE>
\<PLACES><D>usa</D>\</PLACES>
\<TITLE>FEUD PERSISTS AT U.S. HOUSE BUDGET COMMITTTEE\</TITLE>
\<DATELINE>    WASHINGTON, March 24 - \</DATELINE>
\<BODY>A feud among Democrats and
Republicans persisted at the House Budget Committee, stalling
the writing of a fiscal 1988 U.S. budget plan.
Republicans failed to appear at a drafting session called by Democratic committee chairman William Gray as a make-up
meeting to end bickering that has delayed budget activity  for
a week and threatens the ability of Congress meeting an April
15 deadline for completing the deficit-cutting budget.
\</BODY>

# WordNet-3.0

https://wordnet.princeton.edu/download/current-version

C sources for a tool to use the data files (in the directory "/dict")
 
* Example of content :

* adjective file ( 21500 lines )

ineradicable a 1 3 ! & ^ 1 0 00898289  
inerrable a 1 1 & 1 0 00965359  
inerrant a 1 2 & + 1 0 00965359  
inert a 3 3 & + ; 3 2 01565038 01930004 00034322  


* noun file ( 82144 lines )

00963057 04 n 01 counterrevolution 0 003 @ 00962722 n 0000 + 02845871 a 0101 + 09969869 n 0101 | a revolution whose aim is to reverse the changes introduced by a previous revolution  
00963241 04 n 02 insurgency 0 insurgence 0 002 @ 00962129 n 0000 + 00963283 a 0101 | an organized rebellion aimed at overthrowing a constituted government through the use of subversion and armed conflict  
00963447 04 n 02 intifada 0 intifadah 0 001 @ 00962129 n 0000 | an uprising by Palestinian Arabs (in both the Gaza Strip and the West Bank) against Israel in the late 1980s and again in 2000; "the first intifada ended when Israel granted limited autonomy to the Palestine National Authority in 1993"  

* other files also


# Microsoft MIND dataset 

https://msnews.github.io/index.html

Anonymized behavior logs of Microsoft News website (news, clicks and navigation of users). Mostly for user behaivour studies (preferences) and for increasing clicks


#  IMDB movie reviews

https://www.kaggle.com/c/word2vec-nlp-tutorial/data

* Example of content :

"8196_8"	1	"I dont know why people think this is such a bad movie. Its got a pretty good plot, some good action, and the change of location for Harry does not hurt either. Sure some of its offensive and gratuitous but this is not the only movie like that. Eastwood is in good form as Dirty Harry, and I liked Pat Hingle in this movie as the small town cop. If you liked DIRTY HARRY, then you should see this one, its a lot better than THE DEAD POOL. 4/5"

"7166_2"	0	"This movie could have been very good, but comes up way short. Cheesy special effects and so-so acting. I could have looked past that if the story wasn't so lousy. If there was more of a background story, it would have been better. The plot centers around an evil Druid witch who is linked to this woman who gets migraines. The movie drags on and on and never clearly explains anything, it just keeps plodding on. Christopher Walken has a part, but it is completely senseless, as is most of the movie. This movie had potential, but it looks like some really bad made for TV movie. I would avoid this movie."

"10633_1"	0	"I watched this video at a friend's house. I'm glad I did not waste money buying this one. The video cover has a scene from the 1975 movie Capricorn One. The movie starts out with several clips of rocket blow-ups, most not related to manned flight. Sibrel's smoking gun is a short video clip of the astronauts preparing a video broadcast. He edits in his own voice-over instead of letting us listen to what the crew had to say. The video curiously ends with a showing of the Zapruder film. His claims about radiation, shielding, star photography, and others lead me to believe is he extremely ignorant or has some sort of ax to grind against NASA, the astronauts, or American in general. His science is bad, and so is this video."

# Europarl corpus

http://statmt.org

European Parliament session transcripts
Contains more than 2M sentences in different languages for SMT (translations)

* Example of content :

EN
Resumption of the session
I declare resumed the session of the European Parliament adjourned on Friday 17 December 1999

FR
Reprise de la session
Je déclare reprise la session du Parlement européen qui avait été interrompue le vendredi 17 décembre dernier

And in many other languages

# NLU : MCTest data 

Question answering : a set of stories and questions that AI / NLP should answer

https://github.com/vcvpaiva/MCTest-corpus

List of verbs and links to WordNet

https://github.com/vcvpaiva/IBM-vm-Verbs

Other related: 

https://github.com/kkalouli/SICK-processing

# NLU SQuAD

Questions and answers (Stanford)

https://rajpurkar.github.io/SQuAD-explorer/

# NLU RELATION EXTRACTION

Freebase from Google: concepts and all web pages that link to the same page on Wikipedia (this means that the concept is the same for the differnet links that point to the Wikipedia page, ie. New York and Big Apple)

https://developers.google.com/freebase

or

https://freebase-easy.cs.uni-freiburg.de/dump/

# NLU Question answering

https://github.com/brmson/dataset-factoid-curated

# Open Data on AWS (many data sets on different subjects and domains)
https://aws.amazon.com/opendata/?wwps-cards.sort-by=item.additionalFields.sortDate&wwps-cards.sort-order=desc


----------------

Other ressources that may be interesting for AI / NLP

# MTurk (tasks and jobs for the masses)
https://www.mturk.com/get-started





