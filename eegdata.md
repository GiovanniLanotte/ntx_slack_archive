######eegdata

2/8/2017 1:01 AM

 **andyh616** :

 >:clap: :metal:

2/8/2017 1:02 AM

 **yannick** :

 >:ntx2:

2/8/2017 7:03 PM

 **stephen** :

 ><http://www.openmhealth.org/documentation/#/overview/get-started>

2/8/2017 7:03 PM

 **stephen** :

 ><http://www.openmhealth.org/>

2/8/2017 7:04 PM

 **stephen** :

 >Anyone familiar with this mobile health data open source framework ?

2/8/2017 10:39 PM

 **jaymutzafi** :

 >You folks seen this? <https://medicalxpress.com/news/2017-02-advanced-eeg-analysis-reveals-complex.html>

> 
Can this be applied programmatically?

2/9/2017 4:41 AM

 **joeyo** :

 >lol. Multitaper methods aren't exactly new for field potential analysis. But perhaps they havent been used clinically yet?

2/9/2017 6:00 AM

 **pierre** :

 >Yeah multitaper isn't very new, but their results are pretty cool 

2/9/2017 6:01 AM

 **pierre** :

 >Haven't seen much EEG sleep multitapers but it looks really consistent 

2/21/2017 11:15 AM

 **firassafieddine** :

 >hello

> 


> 
I am currently trying to extract data from an epoc emotic 14 channel eeg headset , I am having some trouble being able to extract the data stream

> 
Any suggestions?!

2/21/2017 3:32 PM

 **ray_cassani** :

 >yes it is: <https://github.com/bcimontreal/bci_workshop>

2/21/2017 3:44 PM

 **firassafieddine** :

 >thanks alot

2/27/2017 7:55 PM

 **mpontais** :

 >Hey there! I'm trying to make electronic structures respond to data given by an Emotiv Epoc headset, and I'm facing some troubles.. I'm for now using MindyourOscs, through Processing, then sending the signals to Arduino. It works for facial recognition features, but does not respond when I call affective functions (Excitement/Meditation/Frustration/...) which are the ones I'm interested about! 

> 
Did someone know about this issue? And is there a "known" solution? Else I'm not really familiar with the Emotiv Epoc, so would there be a better/quicker/easier way to be able to program microcontrollers according to the EEG data other than the Processing/Arduino interface? 

> 
Thanks a lot!

2/28/2017 3:12 PM

 **natanel** :

 >hola!

> 
does anyone here has eeg readings of febromealgia vs healthy patients?

> 
can i get some of that? :slightly_smiling_face:

2/28/2017 3:45 PM

 **mpontais** :

 >Oh sorry I just realized I miss read your post as a question! Um I've never use Unity but I heard a lot about it for VR. Can you also control other electronic structures than a VR headset with it?

2/28/2017 4:03 PM

 **bhargava2566302** :

 >If u want u can pm

3/2/2017 10:21 PM

 **alexandre.barachant** :

 ><http://alexandre.barachant.org/blog/2017/03/02/Hands-on-OpenBCI-Ganglion.html>

3/3/2017 4:10 PM

 **alexandre.barachant** :

 >indeed. In terms of signal quality, the muse is good. with optimal electrode placement i have no doubt AUC would get better

3/3/2017 4:58 PM

 **melanie** :

 >can anyone point me in the direction of a tutorial for doing ICA on resting state EEG data? I can only seem to find things for erp paradigms.

3/3/2017 5:00 PM

 **melanie** :

 >(worth noting that I'm not even sure my question makes sense)

3/3/2017 5:53 PM

 **qbarthelemy** :

 >you can look at MNE

> 
<http://martinos.org/mne/dev/manual/preprocessing/ica.html>

3/3/2017 6:09 PM

 **melanie** :

 >qbarthelemy: thanks - can't seem to find anything on how to use their ICA package without having a stimulus file. Currently just using the sklearn ica package. It seems to be working (ish) :slightly_smiling_face:

3/3/2017 7:45 PM

 **yrenard** :

 >melanie also there exist different ways of doing ICA ; ICA is a family of methods and you should be neet picky as to which one suits your problem and its apriori parameters the best

3/3/2017 7:51 PM

 **qbarthelemy** :

 >I do agree. FastICA is not the best one...

3/3/2017 7:55 PM

 **yrenard** :

 >:wink:

3/3/2017 8:04 PM

 **hectordomorozco** :

 >yrenard can you point us to some resources as to fully understand this? :slightly_smiling_face:

3/3/2017 8:09 PM

 **yrenard** :

 >you should start with the wikipedia page I guess, this already mentions quite a few different techniques

3/3/2017 8:25 PM

 **qbarthelemy** :

 >Arnaud Delorme has an excellent paper on BSS methods

> 
<http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0030135>

3/3/2017 9:38 PM

 **hectordomorozco** :

 >Thanks

3/6/2017 7:56 PM

 **sydneyneurotechx** :

 >alexandre.barachant  Did you make your own EEG cap?

3/6/2017 7:56 PM

 **alexandre.barachant** :

 >yep

3/6/2017 7:57 PM

 **sydneyneurotechx** :

 >Do you have any tutorials on building one? :stuck_out_tongue:

3/6/2017 7:59 PM

 **alexandre.barachant** :

 >not really, i took some picture and planned to make a tutorial back when i built it (summer 2016) but it was not that usefull since the offset of the electrode was too big for the OpenBCI board.

> 
Now it is compatible with the ganglion so i might do it

3/6/2017 8:00 PM

 **alexandre.barachant** :

 >however, i'm not 100% satisfied with the electrodes, confortwise

3/6/2017 8:03 PM

 **alexandre.barachant** :

 >AJ made a video of assembling the electrodes : <https://www.youtube.com/watch?v=kgNdJGsjy-Q>

3/6/2017 8:04 PM

 **alexandre.barachant** :

 >the rest is just a swim cap and a hot glue gun :slightly_smiling_face:

3/6/2017 11:08 PM

 **sydneyneurotechx** :

 >Where did you get those electrodes?

3/7/2017 7:30 AM

 **physionikhil** :

 >can any one help me with the hardware part for making an eeg controlled electrical muscle stimulation device

3/7/2017 9:01 AM

 **alexandre.barachant** :

 >sydneyneurotechx  this is my own design. There a link with the video with instruction to oder components (PCB + pogo pins)

3/10/2017 11:10 AM

 **octonomy** :

 >hi everybody, long time no see. hope youre all doing well in your work as spring arrives.

> 
I have a sklearn question to ask. Has anyone tried to use the sklearn TimeSeriesSplit instead of the more common StratifiedKFold() or test_train_split() cross-eval methods?

> 


> 
<http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.TimeSeriesSplit.html>

3/10/2017 11:12 AM

 **octonomy** :

 >Im trying to understand, from high level, if this is going to be problematic for EEG epochs data? It is a weird concept: 

> 
"Note that unlike standard cross-validation methods, successive training sets are supersets of those that come before them.

> 


> 
Here is example of what happens with this split:

> 
```

> 
&gt;&gt;&gt; from sklearn.model_selection import TimeSeriesSplit

> 
&gt;&gt;&gt; X = np.array([[1, 2], [3, 4], [1, 2], [3, 4]])

> 
&gt;&gt;&gt; y = np.array([1, 2, 3, 4])

> 
&gt;&gt;&gt; tscv = TimeSeriesSplit(n_splits=3)

> 
&gt;&gt;&gt; print(tscv)  

> 
TimeSeriesSplit(n_splits=3)

> 
&gt;&gt;&gt; for train_index, test_index in tscv.split(X):

> 
...    print("TRAIN:", train_index, "TEST:", test_index)

> 
...    X_train, X_test = X[train_index], X[test_index]

> 
...    y_train, y_test = y[train_index], y[test_index]

> 
TRAIN: [0] TEST: [1]

> 
TRAIN: [0 1] TEST: [2]

> 
TRAIN: [0 1 2] TEST: [3]

> 
```

3/10/2017 11:12 AM

 **octonomy** :

 >so your train sets are gradually increasing. its like each test fold is trained with X cumulative up to the y.

3/10/2017 11:14 AM

 **alexandre.barachant** :

 >This is an interesting split that keep time structure. 

> 
I generally use K-Fold when i don't shuffle, but this one will make sure you don't train with data that will be recorded after your test set.

3/10/2017 11:15 AM

 **alexandre.barachant** :

 >this is a cool validator for benchmarking the number of trial to use in a realistic setup

3/10/2017 11:16 AM

 **octonomy** :

 >yes i never notice it before, but not sure its new to 0.18

3/10/2017 11:16 AM

 **alexandre.barachant** :

 >yes, it's new

3/10/2017 11:16 AM

 **alexandre.barachant** :

 >they rewrote the cross validation API

3/10/2017 11:16 AM

 **octonomy** :

 >yeah i saw that. with this model_selection package

3/10/2017 11:16 AM

 **octonomy** :

 >its good

3/10/2017 11:17 AM

 **alexandre.barachant** :

 >they have also GroupKFold or LeaveOneGroupOut that is very usefull for cross-subject, session

3/10/2017 11:20 AM

 **octonomy** :

 >yes ive been struggling with the kfolds. im able to keep my train and test separate just fine for final analysis, but within the gridsearch step in training, where one might further split into train/validation, i end up using CV, and am worried that train data is overfitting by being mixed with validation folds because they are close in time proximity.

3/10/2017 11:23 AM

 **octonomy** :

 >hm no, actually im cropping epochs, so its not like sampling randomly from a continuous time series. sorry, just thinking out loud.

3/10/2017 11:54 AM

 **octonomy** :

 >one problem with the TimeSeriesSplit I guess is that it is mixing times series information from different classes?  for example: in the example above, if X[0] and X[2] were class 1, and X[1] and X[3] were class 2, then:

> 
```

> 
[0] -&gt; class 1

> 
[0, 1] -&gt; class 2

> 
[0,1,2] -&gt; class 1

> 
[0,1,2,3] -&gt; class 2

> 
```

> 
this seems not good. must be some other use case where this split is useful, but maybe not already epoched EEG.  seems like this would be useful where cumulative past time series leads to current class label.

3/13/2017 11:18 PM

 **sydneyneurotechx** :

 >To view archived text from Slack please visit:

> 
<https://github.com/NeuroTechX/ntx_slack_archive/blob/master/eegdata.md>

3/15/2017 10:56 AM

 **omer** :

 >Yeaa probably, we use this kind of ful  night spectrals in our lab for years also in publications. I guess it just new for the clinic, you don't really need multitaper for that...

3/15/2017 10:57 AM

 **omer** :

 >you can build one yourself

3/16/2017 9:16 AM

 **dojeda** :

 >Hey, is anyone currently saving EEG data on a distributed database (i.e. opentsdb, hbase, etc)? I am wondering how performant (or not) this is.

> 
When you read about "time series analysis" around the web, where the time series are stored in some sort of database, examples are mostly with series whose Fs &gt;&gt; 1Hz, but in EEG we are generally interested in &gt;128Hz. OpenTSDB, for instance, has a warning on their frequently asked questions:

> 
&gt; Can I store sub-second precision timestamps in OpenTSDB? As of version 2.0 you can store data with millisecond timestamps. However we recommend you avoid storing a data point at each millisecond as this will slow down queries dramatically.

3/16/2017 10:16 AM

 **pierre** :

 >marion w have done this in cloudbrain

3/16/2017 7:06 PM

 **firassafieddine** :

 >hello everyone,

> 


> 
Im trying to figure out what each of the sensors of the emotiv epoc 14 channels sense:

> 


> 
AF3, AF4, F3, F4, FC5, FC6, F7, F8, T7, T8, P7, P8, O1, O2

> 


> 
anything about that ?

3/16/2017 7:09 PM

 **yrenard** :

 >firassafieddine ^^ <http://www.mariusthart.net/downloads/eeg_electrodes_10-20.svg>

3/16/2017 7:09 PM

 **yrenard** :

 >and <https://en.wikipedia.org/wiki/10-20_system_(EEG)>

3/16/2017 7:11 PM

 **firassafieddine** :

 >looks helpful! thanks yrenard  Im trying to find what each one of these sensors get

3/16/2017 7:31 PM

 **yannick** :

 >firassafieddine There is no "simple" answer to your question. Perhaps reading a little more on EEG (<https://en.wikipedia.org/wiki/Electroencephalography>) would help refine your question?

3/17/2017 4:32 AM

 **sydneyneurotechx** :

 >firassafieddine The best answer as to what each of the electrodes will get, is dependent on the type of task you are looking to measure. There are a variety of types of brain signals that you can acquire with an eeg(For example your emotiv). for example you can look at Neural Oscillations (more commonly known as brain waves) or Event Related Potentials, which is where you measure the brains response to some form external or internal stimulation. iMotions has a great pdf which explains the basic of eeg (If you find the wiki article overwhelming). I'd also looking at their pdf on experimental design as it's good idea to follow an experimental procedure when trying to acquire eeg signal

3/17/2017 5:31 AM

 **physionikhil** :

 >Does any one know about an affordable and portable Nirs device for measure cerebral oxygenation in stroke patients after physical therapy interventions including conditioning exercises

3/18/2017 9:19 AM

 **a.tech** :

 >physionikhil 

> 
You might like to look at

> 
<https://www.biopac.com/application/fnir-functional-near-infrared-optical-brain-imaging/>

3/18/2017 10:58 AM

 **physionikhil** :

 >a.tech hi thnx for the info for Biopac. Do u have an idea how much their system cost. I also searched about artinis oxymon Fnirs device. Yet to get a quote from them

3/18/2017 1:39 PM

 **sydneyneurotechx** :

 >The cheapest consumer NIRS I found was 2 thousand by Hitachi. Not sure if you can find cheaper or not

3/18/2017 2:16 PM

 **physionikhil** :

 >2000$? Their units go over 500k I think

3/18/2017 2:20 PM

 **physionikhil** :

 >Artinis have another by the name porta lite , not sure how reliable it is

3/18/2017 2:20 PM

 **yannick** :

 >Nan they do have a "consumer" version they presented last year

3/18/2017 2:21 PM

 **yannick** :

 ><http://www.hitachi-hightech.com/global/about/news/2016/nr20160224.html>

3/18/2017 2:21 PM

 **physionikhil** :

 >yannick thnx let me check

3/18/2017 2:23 PM

 **physionikhil** :

 >yannick any experience with artinis octamon or portalite for Nirs studies?

3/18/2017 2:34 PM

 **yannick** :

 >No, sorry :disappointed:

3/18/2017 2:40 PM

 **physionikhil** :

 >Ok

3/18/2017 4:11 PM

 **nedack** :

 >physionikhil I'm using Nirsport made by NIRX (<https://nirx.net/nirsport/>) and my supervisor told me it costs around 30k�. Also, I know Biopac sell a fNIRS system at 19000 � HT in France but i don't remember if it's the fNIR100 or other

3/19/2017 11:26 AM

 **physionikhil** :

 >nedack thank you, may I know what are your applications for fNIRS system

3/19/2017 2:20 PM

 **nedack** :

 >physionikhil Yeah, I'm working on the assessment of the mental workload in flight condition

3/19/2017 3:06 PM

 **physionikhil** :

 >nedack great

3/20/2017 3:18 PM

 **eferdinand** :

 >any recommendation for reading ECG from the forehead?

3/20/2017 4:48 PM

 **alexandre.barachant** :

 >you can read ECG everywhere as long as the reference electrode and the signal electrodes are far away.

> 
so if you can only place electrodes on the forehead that will be tricky

3/20/2017 6:15 PM

 **mkos** :

 >Hi, I am interested in buying Muse 2016 for my research project. I found some inconsistencies on Muse's website and I am wondering if the following are available for Muse 2016?

> 
a) MuseIO,

> 
b) MuseLab,

> 
c) MusePlayer.

3/20/2017 6:48 PM

 **amilenkovic** :

 >I believe Muse are still working on updating the SDK to support the Muse 2016 hardware, though I hope someone will correct me if that information is out of date

3/20/2017 6:49 PM

 **amilenkovic** :

 >if you are looking for a solution to access EEG data on a Muse 2016, there's an app called MuseMonitor on both Android / iOS that works quite well and lets you pair the muse to a phone or tablet, as well as get the full data in CSV / Zip / stream to an OSC server

3/20/2017 6:50 PM

 **amilenkovic** :

 >There are also some ways to get a muse 2016 working in Linux apparently, though I haven't tried them since I have a 2014

3/20/2017 8:46 PM

 **mkos** :

 >oh, very useful! thank you amilenkovic !

3/20/2017 8:46 PM

 **mkos** :

 >So for now, the safest bet would be to get the older hardware, correct?

3/20/2017 10:53 PM

 **sydneyneurotechx** :

 >Older hardware will work, but from my understanding the 2016 hardware should work just fine with those three applications  mkos . Correct me if I'm wrong graeme

3/20/2017 10:57 PM

 **graeme** :

 >That's right, and we're working on an update to the research tools for Windows, which will work with all the Muses (and be more awesome in general) 

3/21/2017 12:38 AM

 **mkos** :

 >graeme - nice but I want to ran a pilot next month :slightly_smiling_face:

3/21/2017 12:41 AM

 **graeme** :

 >you can easily stream eeg data from Muse Monitor right now (also via MuseLab) then forward it to wherever you want. That will only create challenges if you're looking for low-latency responses because of the network latency

3/21/2017 9:13 AM

 **alexandre.barachant** :

 >mkos On linux, you can use my code : <https://github.com/alexandrebarachant/muse-lsl>

> 
It can works on windows/mac but you need a special dongle and patching the pygatt python library

3/21/2017 1:47 PM

 **mkos** :

 >excellent - I like linux :slightly_smiling_face: thanks! alexandre.barachant

3/21/2017 1:53 PM

 **alexandre.barachant** :

 >mkos you can read more on my blog : <http://alexandre.barachant.org/blog/2017/01/27/reverse-engineering-muse-eeg-headband-bluetooth-protocol.html>

3/22/2017 3:44 AM

 **pierre** :

 >I'm not quite sure where to post this, but you can get attention through cross-brain correlations with the OpenBCI ganglion!

3/22/2017 3:44 AM

 **pierre** :

 >I led a lab on this today, and everyone got it to work and got interesting results

3/22/2017 3:44 AM

 **pierre** :

 >I feel it has a lot of promise

3/22/2017 3:45 AM

 **pierre** :

 >here's a reference: <https://github.com/NeurotechBerkeley/bci-course/tree/master/lab7>

3/22/2017 3:48 AM

 **pierre** :

 >we placed the electrodes in frontal and temporal, so it should be doable with muse, but I'm guessing you guys are already aware of this

3/22/2017 5:58 AM

 **lemiesz** :

 >Hi everyone, im new to this but it all sounds really interesting. 

> 
Anyone have any resources I could read, to help introduce me to Muse/EEGs/Neurofeedback

3/22/2017 7:01 AM

 **physionikhil** :

 >lemiesz u can check this out

3/22/2017 1:15 PM

 **sydneyneurotechx** :

 >lemiesz You can take a look at our awesome BCI page. It has a non-exhaustive list of resources to help you get started.

3/22/2017 1:15 PM

 **sydneyneurotechx** :

 >We are also working on NeurotechEDU and content should be ready soon for that.

3/22/2017 6:52 PM

 **dano** :

 >pierre that looks really cool! I'll see if we can get a replication with the Muse at one of our TO hacknights

3/22/2017 6:52 PM

 **pierre** :

 >dano that'd be awesome, let me know how it goes!

3/22/2017 7:00 PM

 **pierre** :

 >Feel free to message me if you have any questions or concerns

3/23/2017 1:02 AM

 **graeme** :

 >pierre that is really slick

3/23/2017 1:03 AM

 **bhargava2566302** :

 >graeme: hey i need a help with you guys

3/23/2017 1:03 AM

 **bhargava2566302** :

 >When i uploading an app that uses muse its asking for some id can you just how can i get it

3/23/2017 1:04 AM

 **graeme** :

 >send me an email at moffat at interaxon dot ca

3/23/2017 5:27 AM

 **lemiesz** :

 >Thanks guys

3/23/2017 5:27 AM

 **lemiesz** :

 >So the way I understand it, MuseIO does not work with the current headband right now

3/23/2017 6:25 AM

 **franko** :

 >Hello, any reviews on Emotiv Insight? Need something for brain work analysis during working hours. Is it accurate?

3/23/2017 12:12 PM

 **sydneyneurotechx** :

 >I don't see why it wouldn't. How did you come to that conclusion?

3/23/2017 8:27 PM

 **igweckay** :

 >Has anyone connected Emotiv with Processing.js ? 

3/24/2017 8:02 AM

 **rimsmb** :

 >Hi,

> 
try this application with your device (for Muse2016) to read and save the signals from Muse2016, it is the only solution until now <https://play.google.com/store/apps/details?id=com.myr.mymuse2017>

3/24/2017 8:29 PM

 **graeme** :

 >lemiesz you can use Muse Monitor as a substitute for MuseIO if you're using the 2016 headband. It can output an osc stream in the same way MuseIO does.

3/26/2017 10:30 PM

 **maxim** :

 >By the way, you can use official Muse test application as well. It will save all the data in the file in sdcard, that file can then be saved and analyzed (if there is no need for realt-time interaction)

3/27/2017 10:29 PM

 **danbaker** :

 >lemiesz I believe thats correct - I had purchased a 2016 band but it doesnt work with latest bluetooth LE or whatever it is, so I had to return it and use the 2015 model

3/28/2017 4:38 PM

 **d.adamos** :

 >Hi all,  an event synchronization tutorial between OpenSesame open-source experiment builder and Emotiv EEG Testbench is provided in our Groups web page: <http://neuroinformatics.gr/node/37>

4/2/2017 6:52 PM

 **dano** :

 >Anyone interested in recording data from a Muse headset can now use EEG 101 to do so! We skip the .muse format and go straight to simple, legible CSVs

> 
<https://play.google.com/store/apps/details?id=com.eeg_project&amp;hl=en>

4/2/2017 11:40 PM

 **sydneyneurotechx** :

 >dano  I'd suggest include a sample Muse dataset for the eeg 101 tutorial for people that don't have the Muse

4/2/2017 11:40 PM

 **sydneyneurotechx** :

 >It would also help for when I'm talking at events about your projects :stuck_out_tongue:

4/2/2017 11:43 PM

 **dano** :

 >But.. who's brain? What should they be doing? So many questions get raised everytime I ponder offline mode! :open_mouth:

4/3/2017 12:22 AM

 **sydneyneurotechx** :

 >Your brain!

4/3/2017 12:22 AM

 **sydneyneurotechx** :

 >My brain!

4/3/2017 12:23 AM

 **sydneyneurotechx** :

 >I volunteer my brain

4/5/2017 2:51 AM

 **octonomy** :

 >My dear Mr. alexandre.barachant , a small question for you. I have been using the pyRiemann lib (which is excellent,, thank you for this gift), and noticed it seems to frequently come back with the `ValueError: array must not contain infs or NaNs` error.

> 


> 
I try the `cov_data_train = np.nan_to_num(cov_data_train)` right before clf_mdm.fit(), but doesnt help. 

> 


> 
Is there any chance theres something in the code a bit deeper that might cause the dreaded Nan/Inf?

4/5/2017 5:58 AM

 **yrenard** :

 >octonomy: the number one reason is if your input signal, for any reason, has inf or nan numbers. You can check your epochs with `np.all(np.isfinite())` and validate that this input is always numeric

4/5/2017 5:59 AM

 **yrenard** :

 >the number two reason is that the rank of your matrices is not up to the number of channels (which means you lost a degree of freedom, e.g. by referencing all channels to the common average)

4/5/2017 6:00 AM

 **yrenard** :

 >in order to avoir that, you should ensure that the rank of your matrices is equal to the number of channels you have (use `np.linalg.rank` to get this), or reduce the matrices by dropping some channels that can be reconstructed as a linear combination of other channels

4/5/2017 6:01 AM

 **yrenard** :

 >if you referenced to common average, just drop any of your input channels before sending them to pyriemann

4/5/2017 11:49 AM

 **alexandre.barachant** :

 >octonomy: yrenard got it right. this error usually happens when you have rank deficient matrices. This is the case when applying an average reference, or when the number of time sample in your covariance window is lower than the number of channels. To fix that, disable average refrence (older version of MNE set it by default), increase your window size, or add regularization during the estimation.

4/5/2017 11:50 AM

 **alexandre.barachant** :

 >Note that i suggest you to work from the github version of the toolbox. I recently added some more explicit error message for this problem

4/5/2017 11:53 AM

 **alexandre.barachant** :

 >I plan to release a new version in the next couple of weeks

4/5/2017 12:30 PM

 **octonomy** :

 >thanks so much yrenard and alexandre.barachant for the clues. yrenard i did put in this check you mention `np.isfinite()` right before the call to `fit()` and the data is ok, so its something further down inside the fit() call that further transforms my input data to result with nan/inf

4/5/2017 12:31 PM

 **alexandre.barachant** :

 >yes, the problem is not input matrices contain nans, they are rank deficient

4/5/2017 12:31 PM

 **alexandre.barachant** :

 >if you estimates your cov mats with regularization =&gt; `Covariances(estimator='lwf').transform(EEG)` the the problem will go away

4/5/2017 12:32 PM

 **alexandre.barachant** :

 ><https://github.com/alexandrebarachant/pyRiemann/issues/40>

4/5/2017 12:35 PM

 **octonomy** :

 >ah ok, i was looking down the average reference suggestion, which i think  is set by `mne.io.set_eeg_reference`. i will try regularization, this was my next idea too. happy to see its just a param to the covariances() constructor so i dont have to do it from scratch

4/5/2017 12:39 PM

 **octonomy** :

 >in this way you showed just now, do you not pass in EEG as X to constructor, and instead pass it in into the transform call explicitly? I expected: `Covariances(X=EEG, estimator='lwf')` instead of `Covariances(estimator='lwf').transform(EEG)`?

4/5/2017 12:43 PM

 **alexandre.barachant** :

 >no, the data nevers goes into the constructor

4/5/2017 12:43 PM

 **alexandre.barachant** :

 >for mne, the average reference is generally applied during the epoching

4/5/2017 12:44 PM

 **alexandre.barachant** :

 ><http://martinos.org/mne/stable/generated/mne.Epochs.html>

4/5/2017 12:44 PM

 **alexandre.barachant** :

 >add_eeg_ref=False

4/5/2017 12:45 PM

 **alexandre.barachant** :

 >```

> 
add_eeg_ref : bool

> 
      If True, an EEG average reference will be added (unless one already exists). The default value of True in 0.13 will change to False in 0.14, and the parameter will be removed in 0.15. Use mne.set_eeg_reference() instead.

> 
```

4/5/2017 12:45 PM

 **octonomy** :

 >im working with pyRiemann 0.2.4.  the example here does pass in X to constructor of covariances:

> 
```

> 
# compute covariance matrices

> 
cov_data_train = covariances(epochs_data_train)```

> 
<http://pythonhosted.org/pyriemann/auto_examples/motor-imagery/plot_single.html>

4/5/2017 12:46 PM

 **alexandre.barachant** :

 >yes, because that's a function, not a class.

4/5/2017 12:47 PM

 **alexandre.barachant** :

 >i should change the example to use the `Covariances` class instead

4/5/2017 12:47 PM

 **octonomy** :

 >ah, ok. i see, you gave me example with capital C, so its class, not function. understood.

4/5/2017 12:48 PM

 **alexandre.barachant** :

 >haha, i already did it on the last code

4/5/2017 12:48 PM

 **alexandre.barachant** :

 ><https://github.com/alexandrebarachant/pyRiemann/blob/master/examples/motor-imagery/plot_single.py#L68>

4/5/2017 12:48 PM

 **alexandre.barachant** :

 >When i will release the new version, the doc will be updated

4/5/2017 12:50 PM

 **octonomy** :

 >ohhh. i see, so your master is ahead of distributed package used by pip

4/5/2017 12:51 PM

 **alexandre.barachant** :

 >yes, big time :slightly_smiling_face:

4/5/2017 12:52 PM

 **octonomy** :

 >so to work from latest master, i could just `pip uninstall pyriemann`, git clone master, and then do setup.py?

4/5/2017 12:53 PM

 **alexandre.barachant** :

 >yep, you can uninstall pyriemann, clone the master, and then do `python setup.py develop`

4/5/2017 12:53 PM

 **alexandre.barachant** :

 >this way when you update the repo, the package follows

4/5/2017 12:54 PM

 **octonomy** :

 >great. im curious about why MNE would *add* the average reference by default? wouldnt you want to subtract the average rather than add it, if you were to use it?

4/5/2017 12:55 PM

 **alexandre.barachant** :

 >that's not a 'add' in mathematical sense, you add the projector tha apply the average reference

4/5/2017 1:03 PM

 **octonomy** :

 >ok, thank you. im now using the latest master of pyRiemann, excited to be here on the edge.

4/5/2017 1:05 PM

 **octonomy** :

 >may i ask one more q? in your work with xgboost, alexandre.barachant were you using that algorithm with inputs of covariance (like with pyRiemann) or spatial filters (like with CSP), or something else entirely?

4/5/2017 1:07 PM

 **alexandre.barachant** :

 >i was using tangent space, which produce vectors from covariances matrices

4/5/2017 1:07 PM

 **alexandre.barachant** :

 >you can build a pipeline like that

4/5/2017 1:08 PM

 **octonomy** :

 >i see

4/5/2017 1:08 PM

 **alexandre.barachant** :

 >```

> 
clf = make_pipeline(Covariances(estimator='lwf'), TangentSpace(), XGBClassifier())

> 
clf.fit(EEG_data, labels)

> 
```

4/5/2017 1:16 PM

 **octonomy** :

 >understood. thanks for your help today

4/6/2017 3:40 PM

 **octonomy** :

 >alexandre.barachant if you use the pipeline as you showed above, when it comes to your test data, how do you apply the transform to it before score()?  in the example above, could I just use

> 
```

> 
clf.score(test_X, test_y)

> 
```

> 
Does this properly handle the transform on the new data before running score?

4/6/2017 3:42 PM

 **alexandre.barachant** :

 >yes.

> 
in a pipeline, when you fit, it call `fit_transform` to every steps, except the last one where it call `fit`.

> 
Then, when you predict (or score) it call `transform` on every step, then call `predict` on the last one

4/6/2017 3:44 PM

 **alexandre.barachant** :

 ><http://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html>

4/6/2017 3:53 PM

 **octonomy** :

 >thank you

4/6/2017 3:59 PM

 **alexandre.barachant** :

 >pipelines are super usefull :slightly_smiling_face:

4/6/2017 4:04 PM

 **octonomy** :

 >i love it. just getting the hang of it

4/6/2017 4:05 PM

 **octonomy** :

 >in your pyRiemann library, you offer a CSP transformer? how is it different from the MNE version?

4/6/2017 4:06 PM

 **octonomy** :

 >i guess i shoudl say estimator, since it is not just transform

4/6/2017 4:07 PM

 **alexandre.barachant** :

 >it works on covariances matrices instread of epochs data. MNE does the covariance estimation within the CSP function.

> 
This makes pyriemann CSP more flexible (can be piped as a covariance matrix dimentionality reduction, with the parameter `CSP(log=False)`) and you can also use different metric for mean covariance estimation

4/6/2017 4:07 PM

 **octonomy** :

 >i still dont quite understand the diff between estimator vs classifier. i thought estimator was just sklearns word for a classifier

4/6/2017 4:08 PM

 **alexandre.barachant** :

 >finally, CSP in pyRiemann is also implementing multiclass CSP, which i later added to the CSP of mne

4/6/2017 4:09 PM

 **alexandre.barachant** :

 >i actually fixed a small bug in the CSP implementation of MNE yesterday (<https://github.com/mne-tools/mne-python/pull/4144>). they are now strictly equivalent

4/6/2017 4:11 PM

 **alexandre.barachant** :

 >An estimator is the "base class" of sklearn

4/6/2017 4:11 PM

 **alexandre.barachant** :

 >CSP is a transformer

4/6/2017 4:11 PM

 **alexandre.barachant** :

 >tranformer have a fit and transform, but no predict

4/6/2017 4:12 PM

 **alexandre.barachant** :

 >the other base class have (Classifier, Regressor, Cluster) have a predict

4/6/2017 4:13 PM

 **octonomy** :

 >yes, CSP is a way to extract features only

4/6/2017 4:13 PM

 **alexandre.barachant** :

 >A transformer typically does data "preprocessing" i.e step before a classifier. Feature extraction in a general sense

4/6/2017 4:13 PM

 **octonomy** :

 >so, its like both a classifier and estimator can both be said to be subset of estimator

4/6/2017 4:13 PM

 **alexandre.barachant** :

 ><http://scikit-learn.org/stable/modules/classes.html#module-sklearn.base>

4/6/2017 4:15 PM

 **alexandre.barachant** :

 >a transformer is an estimator, a classifier is also an estimator. that is just the base name for a sklearn class

4/6/2017 4:19 PM

 **octonomy** :

 >yes, i see

4/6/2017 4:21 PM

 **alexandre.barachant** :

 >some estimator can be both classifier and transformer. like my MDM which has a transform method (and return the distance to each centroid). it can therefore be piped before another classifier to to 'manifold embedding'

4/7/2017 12:26 AM

 **pat** :

 >Has anyone had luck connecting Muse to openvibe? I'm trying to go through LSL, but after running muse-io --lsl_eeg I can't seem to connect (and muse-lsl.py fails as gatt can't connect to my device, though it's unclear why not)

4/7/2017 12:32 AM

 **dano** :

 >Have you tried this? Never used OpenVibe, but it worked for me

> 
<https://github.com/alexandrebarachant/muse-lsl>

4/7/2017 12:32 AM

 **pat** :

 >yep, that's muse-lsl.py

4/7/2017 12:33 AM

 **pat** :

 >unfortunately gatt can't connect after 5s, although muse-io has no problems.

4/7/2017 12:34 AM

 **dano** :

 >Of course. You might have a gatt BLE issue then. Can you test on another computer/OS?

4/7/2017 12:40 AM

 **pat** :

 >not easily :disappointed: no worries though, I'll look into why gatt is failing. thanks!

4/7/2017 12:55 AM

 **pat** :

 >ah, damn - I guess the original muse wasn't BLE, so won't be found by gatt?

4/7/2017 1:11 AM

 **pat** :

 >ok, ignore the above - it looks like I could get --lsl_eeg working! :slightly_smiling_face:

4/7/2017 1:31 AM

 **alexandre.barachant** :

 >pat do you have a muse 2014 headband ? my code is only compatible with muse 2016

4/7/2017 1:46 AM

 **pat** :

 >Indeed, that was the issue (e.g. not appearing in lescan)

4/7/2017 1:56 AM

 **pat** :

 >Do the 2016 devices not work with musi-io's --lsl_eeg, or was muse-lsl.py adding more functionality that I should be wary of missing with muse-io?

4/7/2017 9:21 PM

 **dano** :

 >pat: The official support for 2016 headbands hasn't been added to muse-io yet. Alexandres code is a good stop gap solution

4/7/2017 9:40 PM

 **pat** :

 >Thanks! Good to know it's safe for me to stick to muse-io then

4/8/2017 5:02 PM

 **octonomy** :

 >alexandre.barachant about the pipeline, pyriemann, xgb:

> 


> 
I was expecting the same results from either of these 2 operations. However, they give different scores.

> 


> 
```

> 
# split transformer and classifier

> 
transformer = make_pipeline(Covariances(estimator='lwf'), TangentSpace())

> 
clf = XGBClassifier()

> 
clf.fit(transformer.transform(train_X), train_y)

> 
print clf.score(transformer.transform(test_X),test_y)

> 
```

> 
```

> 
# unified pipeline

> 
clf2 = make_pipeline(Covariances(estimator='lwf'), TangentSpace(), XGBClassifier())

> 
clf2.fit(train_X, train_y)

> 
print clf2.score(test_X, test_y)

> 
```

> 
do you know why?

4/8/2017 5:05 PM

 **octonomy** :

 >the reason i want to split transformer and estimator is 

> 
1) decouple them to allow modular configuration of feature extraction method/classifier

> 
2) to be able to try some extra code in between the transform and fit step (optimization attempts) 

> 


> 
im now wondering if splitting them into two steps significantly alters the classification outcome.

4/8/2017 5:44 PM

 **maxim** :

 >maybe use fit_transform instead of transform on train_X?

4/8/2017 5:49 PM

 **octonomy** :

 >maxim thanks, do you mean in the first code block or second?

4/8/2017 5:50 PM

 **octonomy** :

 >ah yes, i see, that does it

4/8/2017 5:52 PM

 **octonomy** :

 >so i changed 

> 
`clf.fit(transformer.transform(train_X), train_y)` to:

> 
`clf.fit(transformer.fit_transform(train_X), train_y)`

> 
but the second call, to `test_X` remains only `transform()`

4/8/2017 5:53 PM

 **octonomy** :

 >i see, so the transform should be fit when using the train data. and then that information is persisted until you use it to transform the test data later. im familiar with this from CSP, where you have to calculate some spatial filters from the covariances.

4/8/2017 5:53 PM

 **octonomy** :

 >thanks for the help, it was obvious, but im still learning.

4/8/2017 6:05 PM

 **maxim** :

 >yeah, you are exactly right

4/8/2017 6:05 PM

 **maxim** :

 >Some transformers are stateless and you don't have to fit them, but a lot of them need to be fit first

4/8/2017 6:06 PM

 **maxim** :

 >As an alternative, you can call transformer.fit(train_X) first, and then have two transforms

4/8/2017 10:36 PM

 **aj** :

 >Had any one done wensockets? Arduino to node.js?

4/8/2017 10:37 PM

 **bhargava2566302** :

 >Yes tell

4/9/2017 1:00 AM

 **octonomy** :

 >Yes done websockets but not with arduino 

4/10/2017 3:13 AM

 **dano** :

 >Did a websocket project off a Raspberry Pi once. Websockets are awesome, especially when hooked up with RxJs and Redux Observables 

4/10/2017 5:02 AM

 **aj** :

 >yea trying to figure them out

4/10/2017 5:02 AM

 **aj** :

 >going with a standard tcp socket for now

4/10/2017 5:02 AM

 **aj** :

 >just working on how to pass along the port and ip address

4/10/2017 5:02 AM

 **aj** :

 >brainwaves coming to an internet near you shortly

4/13/2017 6:14 AM

 **w** :

 >Has anyone come across a Node module for LSL, at least publishing to LSL if not reading from

4/13/2017 7:37 AM

 **alexandre.barachant** :

 >w I don't think there exist one.

4/13/2017 1:40 PM

 **aj** :

 >w there is not a js wrapper for LSL 

4/13/2017 6:09 PM

 **w** :

 >Thanks

4/14/2017 4:00 PM

 **aj** :

 >w <https://github.com/sccn/labstreaminglayer/issues/168>

4/16/2017 7:11 AM

 **octonomy** :

 >hi everyone. possible discussion topic if anyone is interested. I could move this over to <#C09H26C83|literaturereview> channel if thats better. anyway& in my work trying to compare performance of different classification algorithms on a common set of session datasets, I was looking for the most accepted method for reporting statistical significance.

> 


> 
that is, many studies might attempt to show that classifier A &gt; B &gt; C with performance metric of mean accuracy, when applied to datasets 1, 2, 3, 4, 5, 6, 7, 8, etc.  however, its not enough to show just that a classifier has better accuracy than others, but also that this better performance is statistically significant.

> 


> 
in my search of how to do this (there are many ways), the best I found was this method. its a generalized 2 step process outlined by Bashashati and earlier Demsar.  First step is to use the Friedman test, then, if null hypothesis is rejected, you can go on to post-hoc Holm test.

> 


> 
so far form the literature I reviewed, this seems like the most sound method of comparing multiple classifiers across multiple datasets. Im just floating this out into the channel to a) see if anyone has better suggestions for evaluating statistical significance of classifier performance, and b) to share with the group in case this has not crossed your radar before.

> 


> 
Bashashatis paper is freely available here if anyone is interested: <http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0129435>

4/16/2017 9:28 PM

 **joeyo** :

 >The Friedman test looks reasonable and it doesn't seem to make too many assumptions. I personally prefer permutation tests in this situation, but I think it's mostly a matter if taste.

4/16/2017 9:35 PM

 **joeyo** :

 >The second test also makes sense, but it seems like there should be a correction applied to account for the multiple comparisons (maybe there already is, I'm not very familiar with the Holm test).

4/18/2017 5:52 PM

 **wanfuse123** :

 >Hi! I have a few straight forward questions I would like to ask someone who knows something about capturing eeg data

4/18/2017 5:52 PM

 **wanfuse123** :

 >anyone have time?

4/18/2017 5:58 PM

 **yrenard** :

 >wanfuse123 don't ask to ask, just ask, a lot of people here obviously know about capturing eeg data, whoever has time and skills for your question will voice an answer

4/18/2017 6:04 PM

 **wanfuse123** :

 >ok sorry thanks

4/18/2017 6:08 PM

 **yrenard** :

 >Sure no pb

4/18/2017 6:08 PM

 **wanfuse123** :

 >my first question is: what kind of equipment (and expense) would it cost to use eeg to detect and verify that a human brain is present vs no brain at all? in other words not to discern individual patterns (like the person is saying something) but just verify the presence of a brain?

4/18/2017 6:10 PM

 **wanfuse123** :

 >the only other qualification on the question is an eeg not directly attached

4/18/2017 6:10 PM

 **yrenard** :

 >if you compare healthy brain to literally no brain, just looking at the signal spectrum will give you good information as the human EEG is quite standard

4/18/2017 6:11 PM

 **yrenard** :

 >if you want to investigate on healthy brain vs some unconscious brain, it is another question and there is a lot of research currently on this problem

4/18/2017 6:11 PM

 **yrenard** :

 >you want to do that with no EEG equipment ?

4/18/2017 6:12 PM

 **wanfuse123** :

 >right just detect a brain in the vicinity

4/18/2017 6:13 PM

 **wanfuse123** :

 >anywhere from a few inches to maybe 2 feet

4/18/2017 6:13 PM

 **yrenard** :

 >what would you do that ?

4/18/2017 6:14 PM

 **wanfuse123** :

 >for a project of mine

4/18/2017 6:14 PM

 **wanfuse123** :

 >house IoT devices

4/18/2017 6:14 PM

 **yrenard** :

 >well, then EEG is not the way to go as you obviously need a contact to do that

4/18/2017 6:15 PM

 **yrenard** :

 >I have no good answer to the problem, maybe others have

4/18/2017 6:16 PM

 **yrenard** :

 >You may be interested by the MIT work on hear rate measurement from videos, you could definitely detect that some heart is beating with no contact, and conclude that there might be a brain somewhere

4/18/2017 6:16 PM

 **yrenard** :

 >sorry, this is nearly as vague as the question :wink:

4/18/2017 6:16 PM

 **wanfuse123** :

 >hmm thats not a bad thought

4/18/2017 6:17 PM

 **yrenard** :

 ><http://people.csail.mit.edu/mrub/vidmag>

4/18/2017 6:17 PM

 **wanfuse123** :

 >so how close does eeg need to be to pick up a basic signal directly attached or up against ?

4/18/2017 6:18 PM

 **yrenard** :

 >I'm not sure what you are asking

4/18/2017 6:19 PM

 **wanfuse123** :

 >to pick up a basic signal do the leads have to be attached to the head or just up against the head like a hat?

4/18/2017 6:20 PM

 **yrenard** :

 >it needs ot be in contact with the skin - if it's not, then use gel to bridge the skin to electrode gap

4/18/2017 6:22 PM

 **wanfuse123** :

 >ok, thanks for the information , its appreciated

4/22/2017 2:54 AM

 **ch.yumin** :

 >Hello everyone! I'm starting a project that I want to control a robotic arm with the Ganglion Board (4 Channels EEG from OpenBCI). I already have the robotic arm, it needs 8 commands for full control (3 joints and 1 actuator) or at least 6 commands (2 joints and 1 actuator). Can anyone give some advices about the best techniques/algorithms to use and where should I place the electrodes? This would be my first project, I don't even know if it's possible to get good results with 4 channels EEG haha

4/22/2017 2:42 PM

 **eferdinand** :

 >ch.yumin you have to talk with nicomaque.jette i know he had similar project

4/23/2017 1:32 AM

 **ch.yumin** :

 >eferdinand Ok! thank you

4/25/2017 5:21 PM

 **mesca** :

 >My account request for the DEAP dataset (<http://www.eecs.qmul.ac.uk/mmv/datasets/deap/index.html>) has been denied because I am an autodidact individual and not an academic researcher. Same for the HCI dataset (<https://mahnob-db.eu/hci-tagging/>) because I dont own an institutional email address. Can anyone suggest open and interesting datasets on which I can try my Machine Learning / Deep Learning skills? Thanks!

4/25/2017 7:29 PM

 **pierre** :

 >mesca: Hello fellow Pierre, have you checked out the datasets listed in the awesome-bci repo? Here: <https://github.com/NeuroTechX/awesome-bci#brain-databases>

4/25/2017 7:37 PM

 **mesca** :

 >pierre Looking into it right now! Thanks :slightly_smiling_face:

4/25/2017 7:56 PM

 **yannick** :

 >That awesome awesome-bci list. :ntxblue:  :slightly_smiling_face:

5/1/2017 7:51 PM

 **sydneyneurotechx** :

 ><!channel>  I would to announce NeuroTechX's  new initiative, the "Mother of all BCI Benchmark" project. 

> 


> 
The Goal of this project is to build a comprehensive benchmark of popular BCI algorithms applied on an extensive list of freely available EEG dataset. The code will be made available on github, serving as a reference point for the future algorithmic developments. Algorithms can be ranked and promoted on a website, providing a clear picture of the different solutions available in the field.

> 


> 
Reproducible Research in BCI has a long way to go. While many BCI datasets are made freely available, researchers do not publish code, and reproducing results required to benchmark new algorithms turns out to be more tricky than it should be. Performances can be significantly impacted by parameters of the preprocessing steps, toolboxes used and implementation tricks that are almost never reported in the literature. As a results, there is no comprehensive benchmark of BCI algorithm, and newcomers are spending a tremendous amount of time browsing literature to find out what algorithm works best and on which dataset.

> 


> 


> 
alexandre.barachant will lead the initiative and I will provide logistic support to push it forward. This will be mostly a coding project (It will be open source, so anyone can contribute), however people with a design background are invited as well.

> 


> 
If you are interested in participating, please fill out the doodle below. We will arrange one or two calls based on everyones availability. 

> 


> 
<https://doodle.com/poll/4ngxy9h8qpcmkhpb>

> 


> 
More details on the project can be found here:

> 


> 
<https://docs.google.com/document/d/18nU07Qci_VDbzZCLveDQqPgqRODt7HCNBfKeNPVwMQY/edit#>

5/1/2017 7:52 PM

 **c00p3r** :

 >is this a product that you will be talking about/demostrating on at defcon?

5/1/2017 7:55 PM

 **sydneyneurotechx** :

 >Haha, if there is enough time, but likely not c00p3r  (We plan to start in June, probably won't be enough time)

5/1/2017 8:01 PM

 **aj** :

 >can we start working on this sooner? i already started thinking about this like three weeks ago

5/1/2017 8:11 PM

 **mhough** :

 >Yeah great/needed project

5/1/2017 8:11 PM

 **sydneyneurotechx** :

 >It's partially dictated by alexandre.barachant's schedule (Mine as well). Alexandre what do you think? What's the earliest you can do?

5/1/2017 8:16 PM

 **sydneyneurotechx** :

 >mhough Sign up if you are interested :slightly_smiling_face:

5/1/2017 8:22 PM

 **mhough** :

 >Oh definitely. Any interest in running the same stuff on open clinical EEG?

5/1/2017 8:25 PM

 **sydneyneurotechx** :

 >When you say open clinical EEG, what are you referring to? Open Databases?

5/1/2017 8:58 PM

 **aj** :

 >just send some prs my way

5/1/2017 8:58 PM

 **aj** :

 >whenever y'all are ready on your end

5/1/2017 10:17 PM

 **a.tech** :

 >What an awesome project! This is definitely going to help grow the field. Preprocessing algos is such a huge bottle for new ppl! 

5/2/2017 1:23 AM

 **mhough** :

 >Yeah sydneyneurotechx  it's continuous EEG done for whatever hospitals can bill for? I haven't looked at it closely for events etc. I'll get the link. Only heard about it from a stats guy a couple of months ago. All low channel count so not so interesting for much spatially. 

5/2/2017 1:25 AM

 **mhough** :

 >And yes it's an open database. Should have led with that:)

5/2/2017 3:15 AM

 **sydneyneurotechx** :

 >I

5/2/2017 4:53 AM

 **octonomy** :

 >very nice. ill try to join this meeting

5/2/2017 6:15 AM

 **mhough** :

 >Understood sydneyneurotechx. Sorry if this is a repeat (can I not search the archives?) but I think he was talking about the Temple University EEG dataset

5/2/2017 6:15 AM

 **mhough** :

 ><https://www.isip.piconepress.com/publications/presentations_misc/2017/temple_innovation/auto_eeg/04_poster_v00.pdf>

5/2/2017 9:10 AM

 **alexandre.barachant** :

 >mhough We will use any dataset where we can apply supervised machine learning. We will focus on BCI at first, because the problems are better defined  and the dataset are smaller (in size), but it won't be incompatible with some clinical EEG problem (sleep, seizure, etc, as long as the data have annotation)

5/2/2017 12:05 PM

 **yannick** :

 >alexandre.barachant, dan.rizzuto and his team opened their invasive recordings from DARPA RAM related studies on memory. Lots of high quality labeled data on which they do machine learning to classify if the memory will be encoded or not. That could also be an interesting dataset / paradigm. (just thinking out loud)

5/2/2017 12:06 PM

 **alexandre.barachant** :

 >yannick do you have a link ?

5/2/2017 5:15 PM

 **mhough** :

 >That's great alexandre.barachant. I was jumping ahead I know. That's cool yannick. Yeah love a link

5/2/2017 5:23 PM

 **yannick** :

 >Here is the full wiki: <http://memory.psych.upenn.edu/RAM>

5/2/2017 5:24 PM

 **yannick** :

 >You have a link at the bottom of the main page to Download the dataset. 

> 
(You request access and they will share the Box - kinda Dropbox folder - with you)

5/3/2017 12:37 PM

 **alexandre.barachant** :

 >yannick Thanks. There will be some work to do to list all these datasets :slightly_smiling_face: We need to be carefull with the licence and will avoid using datasets that are behind a wall like this.

5/3/2017 3:15 PM

 **yannick** :

 >And/Or to work with the people behind the wall to make a door in the wall :slightly_smiling_face:

5/3/2017 3:27 PM

 **alexandre.barachant** :

 >yep sure, if the dataset is really interesting, we can try to convince people to make it available in direct download.

5/3/2017 4:58 PM

 **mhough** :

 >What are you looking for in the license? 

5/3/2017 5:52 PM

 **pat** :

 >what's the best way to ask questions about moabb? currently the announcement was in a few channels, would it make sense to create a new one?

5/3/2017 8:38 PM

 **alexandre.barachant** :

 >pat Good idea. We will create a channel before the end of the week. sydneyneurotechx and I are still working on the details.

5/3/2017 8:43 PM

 **alexandre.barachant** :

 >mhough I want to avoid datasets that are 'freely available' with restrictions. The whole point of this is to make it easy to use and accessible to everyone, whether you are part of a research lab, a company or an individual.

5/3/2017 8:48 PM

 **mhough** :

 >Yeah no worries. I know exactly what you mean. I followed up a few people's complaints about data access and they could get the data but they were perhaps too literal with the download instructions. It would be good to talk about it a little later but like you said just ignore those for now

5/3/2017 8:53 PM

 **alexandre.barachant** :

 >yep sure. i think the first step is to list all dataset available, what they contains and how they can be accessed. Then we will see how we can do it.

> 
Also, i thinks it's better to have a lot of smaller dataset, rather than a few big one. it is important to have diversity in the benchmark, so results are more robust

5/3/2017 8:55 PM

 **alexandre.barachant** :

 >there will be some interesting questions about how we rank the different algorithm.

5/3/2017 9:03 PM

 **mhough** :

 >Ok. I can start a list. I am doing the same for ERPs studies anyway. Is there a wiki or something I should use?

5/3/2017 9:09 PM

 **mhough** :

 >Once all the free stuff is organized I wonder if it will be easier to ask labs if they could give subsets of their data that could give you more of those small batches you want. I'm sure you've thought about it already. 

5/3/2017 9:21 PM

 **mhough** :

 >alexandre.barachant I know this is an ERP study but do people ignore the old Begleiter data on the UCI machine learning repository because they don't have the raw data? I'll ask the Poldrack lab. Years ago I tried to contact the person who took over after he retired (died?) to try and get the continuous EEG but its was a different time back then and honestly they might not even have it backed up somewhere:)

5/3/2017 11:49 PM

 **octonomy** :

 >mhough alexandre.barachant there is an awesome list one sec

5/4/2017 12:51 AM

 **octonomy** :

 >One key dataset is the BCI competition IV. It's referenced by so many papers. It sits behind a free registration where you must give email to get access. This was from 2008, i wonder if the original people would be willing to release access. I think by regulations probably this would require consent of original subjects, wherever they are. Just because of paperwork that is signed for experiments.

5/4/2017 12:55 AM

 **octonomy** :

 >I'd be happy to work with SF neurotech x chapter to collect our own royalty-free dataset of MI data using OpenBCI 8-channel and 16-channel, to add some lower resolution data to the mix. If it's useable for this project. I can use a standard MI protocol and document it.

5/4/2017 12:56 AM

 **octonomy** :

 >sydneyneurotechx created the <#C588BQVH9|moabb> channel. It's on

5/4/2017 1:11 AM

 **sydneyneurotechx** :

 >yup <!channel>  for those who want to join, please check out <#C588BQVH9|moabb>

5/4/2017 3:03 AM

 **aj** :

 >octonomy i could donate motor imagery data from thinker

5/4/2017 3:03 AM

 **aj** :

 >we should just make a formal way to add it

5/4/2017 3:03 AM

 **aj** :

 >please god not edf

5/4/2017 3:04 AM

 **octonomy** :

 >come on down to <#C588BQVH9|moabb> dont be a slacker

5/4/2017 3:05 AM

 **octonomy** :

 >oh what? you dont like BDF? ha ha ha

5/5/2017 3:44 PM

 **octonomy** :

 >alexandre.barachant may i ask you a question?  among the riemannian methods, would you say that MDM and TS represent fundamentally different feature spaces?  im asking because im trying to decide if classifiers using either method are appropriate to compare in the same statistical significance test.

5/5/2017 3:44 PM

 **alexandre.barachant** :

 >they both work on same input (covariance matrices), so it's fine as long as you estimated them with the same method

5/5/2017 3:46 PM

 **octonomy** :

 >ive been working from the ideas for comparing multiple classifiers across multiple datasets by Bashashati. In that they segregate test based on Band Power (BP) features vs Morlet wavelet features.  They say: The reason we compared the performance of different classifiers when a single feature extraction methodology was used was that the nature of feature spaces was different for each setting and the results could thus be misleading. For example, when we use the BP features, the feature space is of low dimensions compared to the settings where the Morlet feature is used. Therefore, classification methodologies could only be compared when they are applied on the same feature space.

5/5/2017 3:50 PM

 **alexandre.barachant** :

 >this is true if you want to compare classifiers, i.e for example is it better to use LDA or SVM

5/5/2017 3:50 PM

 **octonomy** :

 >would you describe MDM and TS as projection into a comparable feature space? if the same estimation is used, as you say? im uncertain if the additional projection back to a euclidean plane by TS qualifies as a fundamentally different space than MDM. to the point where it doesnt make sense to compare the same classifier (LDA or LR) against MDM vs TS

5/5/2017 3:51 PM

 **octonomy** :

 >yes, my goal is to compare different classifiers.  im not sure if MDM and TS must be segregated, or if they can be in the same signficance test (Im using Friedman with posthoc Holm)

5/5/2017 3:52 PM

 **alexandre.barachant** :

 >i'm not sure the question can be framed that way

5/5/2017 3:53 PM

 **alexandre.barachant** :

 >basically, you can only compare thing that are comparable, i.e. that took the same inputs. so here you are not comparing LDA or SVM, but the pipeline TS + classifier versus MDM

5/5/2017 3:54 PM

 **alexandre.barachant** :

 >basically, you can benchmark TS+SVM versus TS+LDA versus MDM

5/5/2017 3:54 PM

 **octonomy** :

 >i see. so since the pipeline takes the same inputs (covariance matrices).

5/5/2017 3:55 PM

 **octonomy** :

 >in this way, could you also add then also the pipeline of CSP+LDA, since it also takes the same inputs (covariance matrices)?

5/5/2017 3:55 PM

 **alexandre.barachant** :

 >yes. the same way they could have compared BP and wavelets (they both take raw data as input), the difference is in the intepretation. it's the whole pipeline that is better, not just the classifier

5/5/2017 3:58 PM

 **octonomy** :

 >got it. thank you for this clarification.

5/5/2017 3:59 PM

 **octonomy** :

 >i get confused sometimes about where exactly is the distinction between feature extraction vs classification.

5/5/2017 4:00 PM

 **octonomy** :

 >like, for example, to what extent is a grid search considered a Feature extraction.  if it results in restricting the bandpass filter a certain way, it is changing the information which will be considered by the classifier. and yet, it is a part of the classifier as well, since it uses the classifier to decide which preprocess params are best.

5/5/2017 4:01 PM

 **alexandre.barachant** :

 >IMO comparing classifier is only relevant when you want to know which classifier is better for a given feature set. but that's just a part of the story.

5/5/2017 4:02 PM

 **alexandre.barachant** :

 >if you have a good classifier for a given feature set, that is not given that this classifier will be optimal for another feature set

5/5/2017 4:05 PM

 **alexandre.barachant** :

 >and yes, you can add CSP+LDA

5/5/2017 4:05 PM

 **alexandre.barachant** :

 >all of these algorithms will be benchmarked in the <#C588BQVH9|moabb>

5/5/2017 4:09 PM

 **octonomy** :

 >in my interpretation, i prefer to think of this idea of the entire pipeline as the classifier. thank you for the advice

5/6/2017 12:42 AM

 **jfrayshe** :

 >Long time reader first time poster, was wondering if anyone could point me to some datasets that would be useful for analyzing neural oscillations?

> 


5/6/2017 4:48 PM

 **yannick** :

 >jfrayshe did you check the awesome-bci list? There are some datasets listed there.

5/6/2017 8:11 PM

 **octonomy** :

 >yannick the awesome list is pretty small on datasets actually

5/8/2017 4:27 AM

 **sydneyneurotechx** :

 >octonomy  Add more if you find :slightly_smiling_face:

5/8/2017 5:24 AM

 **octonomy** :

 >fair enough!

5/10/2017 9:05 PM

 **jfrayshe** :

 >I have looked at it but struggled to pull the individual datasets using python, any suggestions?

5/10/2017 10:15 PM

 **jfrayshe** :

 >Noob questions: what do events refer to in the case of eegdata?

5/10/2017 10:21 PM

 **octonomy** :

 >jfrayshe try MNE library. Install it. There are tutorials on their site that explain (I think) how to download a sample dataset.  I have not used their prerecorded data sets so I'm not speaking from experience.

5/10/2017 10:22 PM

 **octonomy** :

 >Events are literally events. In an experiment, it almost always refers to some stimulus presented to the subject.

5/10/2017 10:24 PM

 **jfrayshe** :

 >Cheers l will look into thay

5/10/2017 10:24 PM

 **octonomy** :

 >So for example, if you're working with motor imagery, and classifying left hand vs right hand, you have two "classes" of event, left and right. Conventionally, these classes are represented by integer codes, like left=2, right=3. An event in this case means you show either class 2 or 3 to the subject

5/10/2017 10:25 PM

 **octonomy** :

 >Technically event could be used for anything. But most common use is to tag or label data for supervised learning. 

5/11/2017 6:38 PM

 **yannick** :

 >Hey jfrey I see you did commit on: <https://github.com/conphyture/LSL2Unity>

> 
but in the ToDos its also mention to look at: <https://github.com/xfleckx/LSL4Unity>

> 
Im looking for LSL in Unity, any idea what to use?

5/12/2017 12:46 AM

 **jfrayshe** :

 >Thanks octonomy that clarifies things and is quite applicable to the data I'm working on.

5/12/2017 12:48 AM

 **jfrayshe** :

 >Is it common practice to automatically preprocess eeg data to filter out electrode signals that occupy a space that should have no impact on what I'm measuring? For example if I was analyzing neural oscillations (alpha and beta) during motor control should I automatically preprocess out signals from electrodes that aren't close to that region of the brain?

5/12/2017 6:40 AM

 **jfrey** :

 >yannick: I started my version because I could not get LSL4Unity work, at least on linux. I have been using LSL2Unity on Linux and Windows, but not extensively. I would say that my library is simpler to grasp, but I think you would be better of using LSL4Unity, it seems they have more features, It's definitely more thoroughly tested and... it's maintained. Once you'll have played with it, I'd like to hear your feedback :wink:

5/12/2017 11:47 PM

 **octonomy** :

 >I think it's your call jfrayshe . I think it depends on your technique. Methods like CSP will apply weights to each electrode, so if those electrodes you want to exclude are truly useless they would end being given little weight anyway

5/12/2017 11:55 PM

 **octonomy** :

 >Another thing to consider is, the presence of non relevant electrodes (also called "channels") is that they actually might be relevant if they can help reduce weight of channels you think are relevant.  For example, if a "good" channel right over motor cortex shares information with a "bad" channel over forehead, the extent to which the good channel's signal is "similar" (in covariance) might actually help to eliminate that part of the "good" channel's signal to "correct" it. Just a high level speculation here to share 

5/12/2017 11:57 PM

 **octonomy** :

 >In my own work I've experimented with removing channels one by one, using a "leave one out" approach, and haven't seen it to be too much difference on outcome.  I suggest you try running experiments with and without the "bad" electrodes and see for yourself what pattern emerges.

5/14/2017 1:49 AM

 **jfrayshe** :

 >octonomy cheers, thank you for your input it is helpful. I think for my work I might apply CSP since the data I am working with is not my own and I don't have much time to experiment with it.

5/14/2017 1:50 AM

 **jfrayshe** :

 >Anyone care to weigh on the function within mne they use to convert time based eeg data to frequency?

5/14/2017 2:00 AM

 **octonomy** :

 >yes its a good standard.  the work being done with riemannian geometry is as good and better it is looking like more and more, you might consider it.  check out pyRiemann library. you can use it like a scikit  learn classifier

5/14/2017 2:00 AM

 **octonomy** :

 >there are at least 2 ways to go with this - FFT and DWT

5/14/2017 2:00 AM

 **octonomy** :

 >FFT = fast fourier transform, and DWT = discrete wavelet transform.

5/14/2017 2:01 AM

 **octonomy** :

 >FFT removes the time information.  so you chose some kind of binning strategy (i.e. what size epoch windows you want to look at) and then fourier transform yields a histogram of power at different frequency bands.

5/14/2017 2:02 AM

 **octonomy** :

 >DWT is similar, but it retains the time information

5/14/2017 2:03 AM

 **octonomy** :

 >if you care about that.  but DWT is more complex because it is producing a lot more features to deal with. it gives you band power over time, and can also be used to show the phase information as well.  DWT is typically shown as the rainbow colored map, where red or blue is high or low voltage, on a plot where y axis is frequency bands, and x axis is time.  so its really a 3d graph

5/14/2017 2:04 AM

 **octonomy** :

 >FFT usually shows power on the y axis, and frequency band on the x axis. shown as a bar chart histogram, or line graph

5/14/2017 2:05 AM

 **octonomy** :

 >are you working with labeled data?

5/14/2017 2:07 AM

 **octonomy** :

 >i have done some work with getting nonstandard EEG files into MNE form.  basically if you can get your data into numpy arrays, you can then load them up in to MNE objects.  basically you want to create a RawArray object, and then if you have class labels (i.e. events), you can use the RawArray to create an Events object.  once you have an events object, you can quickly and easily select epochs as needed.  

> 


> 
the parts you have to work out are just how to load up the objects properly, you have to tell the RawArray which channels are EEG and which are STIM (i.e. not electrodes, but channels providing data about events, or stimulation).

5/14/2017 2:22 AM

 **jfrayshe** :

 >Thanks octonomy for the response. I suppose I'm looking for a specific example using mne, do they have a tutorial worth looking at?

5/14/2017 3:01 AM

 **octonomy** :

 >yep

5/14/2017 3:02 AM

 **octonomy** :

 >they have quite a few. what general type of work are you doing? are you trying to classify motor imagery?

5/15/2017 12:09 PM

 **sc** :

 >Lovely explanation of the Fourier Transform <http://gizmodo.com/digital-music-couldnt-exist-without-the-fourier-transfo-1699155287>

5/15/2017 2:29 PM

 **dano** :

 >sc: Really accessible. Will keep this in mind for teaching

5/15/2017 3:40 PM

 **jfrayshe** :

 >octonomy essentially I am attempting to visualize neural oscillations in the alpha and beta range that occur during actual vs imagined motion from the eegbci dataset available in mne.datasets

5/15/2017 6:03 PM

 **octonomy** :

 >So you want to apply alpha and/or beta filter on epochs of event labeled data?

5/15/2017 6:05 PM

 **octonomy** :

 >Thereby making graphs of epochs labeled  "actual" side-by-side with epochs labeled "imagined".

5/15/2017 6:06 PM

 **octonomy** :

 >To be honest, it sounds more like you're in the realm of ERP type study

5/15/2017 6:08 PM

 **octonomy** :

 >In which you might take say, 100 "active" epochs and average them. And then 100 "passive" epochs and average them. Producing two side by side average visualizations. Which could be either the average actual signal filtered in the range you want, or histogram presenting statistics

5/15/2017 6:08 PM

 **octonomy** :

 >How much time do you have to do this?

5/15/2017 7:25 PM

 **jfrayshe** :

 >Hmmm about a week at this point. I've laid a foundation but I wasn't approaching it from an ERP perspective 

5/15/2017 7:47 PM

 **jfrayshe** :

 >I'm really attempting to use a eeg data to demonstrate neural oscillations as a feature extraction 

5/15/2017 7:48 PM

 **jfrayshe** :

 >I'm only focusing on alpha and beta since they are predominant during motor control.

5/16/2017 3:26 AM

 **octonomy** :

 >I understand. I work with motor imagery, and alpha and beta too. The alpha and beta we usually just filter in one pass, from 7-30. There's a bandpass  filter in MNE. 

5/16/2017 3:26 AM

 **octonomy** :

 >My question is about your visualization.

5/16/2017 3:26 AM

 **octonomy** :

 >You said you want to visualize active vs imagined.

5/16/2017 3:27 AM

 **octonomy** :

 >Now my question was about whether you're doing single trial or averaged across many trials

5/16/2017 3:27 AM

 **octonomy** :

 >Like, let's say you have a dataset with 200 labeled trials, each say 4sec long, and 100 are active, 100 are imagined.

5/16/2017 3:28 AM

 **octonomy** :

 >Are you looking to plot 200 individual graphs? Of all epochs filtered to alpha/beta?

5/16/2017 3:29 AM

 **octonomy** :

 >In ERP, you show two graphs. In one, the average waveform of the 100 active, and the average waveform of the 100 imagined. That's one way to go

5/16/2017 3:30 AM

 **octonomy** :

 >The other way to go is, sounds like what you're trying, FFT to produce histogram, or bar chart, showing power at different frequency bands.

5/16/2017 3:31 AM

 **octonomy** :

 >But in this case, you have the same question: are you going to plot 200 bar chart histograms? Or are you going to present averages of 100 and 100 into just 2 graphs.

5/16/2017 7:53 PM

 **fred-simard** :

 >technically, jpeg compression is the cosine transform, but close enough

5/16/2017 11:24 PM

 **jfrayshe** :

 >The latter is what I envisioned, an average of values between 2 different experimental runs 

5/16/2017 11:25 PM

 **octonomy** :

 >Good ok. So if you take that approach of average, if you choose to show waveforms it's the ERP approach

5/17/2017 10:43 PM

 **octonomy** :

 >Wondering if anyone has a rough estimate of what's the state of the art performance accuracy for motor imagery BCI these days? What's the best achieved with online use? Anyone have any idea?

> 


> 
For two class my guess is somewhere around 80%

5/17/2017 11:03 PM

 **yrenard** :

 >It depends how many channel you have available and where they are located, but assuming you have good amount of electrodes and good locations, and that your subjects are also well trained, I would more shoot for 90 % accuracy for a two class BCI ; check out alexandre.barachant 's <https://hal.archives-ouvertes.fr/hal-00693321/file/esannBCI.pdf>

5/17/2017 11:34 PM

 **octonomy** :

 >Thanks yrenard . I was asking for any number of channels, whatever is the highest mark so far. Thanks for the paper this helps. I know the Riemann methods seem to be the leading accuracy right now

5/18/2017 8:37 AM

 **alexandre.barachant** :

 >octonomy yrenard I have a current version of the <#C588BQVH9|moabb> for 2 classes motor imagery (9 different dataset, 227 subjects). You get this kind of performances

5/18/2017 8:38 AM

 **alexandre.barachant** :

 >basically, with Riemannian geometry, 80% of the subjects get and AUC &gt; 0.6, and 20% of them can achieve &gt; 0.9. The median is around 0.75 AUC

5/18/2017 8:39 AM

 **alexandre.barachant** :

 >a breakdown for each dataset

5/18/2017 8:44 AM

 **qbarthelemy** :

 >Alexandre, have you got the results with classical MDM?

5/18/2017 8:50 AM

 **alexandre.barachant** :

 >yes, it is around CSP

5/18/2017 8:51 AM

 **alexandre.barachant** :

 >with MDM :

5/18/2017 8:52 AM

 **alexandre.barachant** :

 >it depends on the dataset, because MDM does not performs well for high channel count (generally)

5/18/2017 8:53 AM

 **qbarthelemy** :

 >ok, thx!

5/18/2017 12:55 PM

 **aj** :

 >this is cool

5/18/2017 12:55 PM

 **aj** :

 >good work alexandre.barachant

5/18/2017 11:24 PM

 **octonomy** :

 >Thank you this is excellent I will study this more to understand these! Awesome.

5/18/2017 11:26 PM

 **octonomy** :

 >P.s. I successfully defended my thesis today and will be awarded my masters degree in computer science! Looking forward a summer of BCI coding now that I'm free

5/19/2017 12:31 AM

 **jfrayshe** :

 >Congrats!

5/19/2017 10:02 PM

 **okbalefthanded** :

 >octonomy congrats! what was it about ?

5/20/2017 5:28 PM

 **octonomy** :

 >okbalefthanded brain computer interface development software. I worked on open source Python package and also a low cost headset for it which uses OpenBCI. Additionally, I used my equipment and software to do a statistical significance test of many classifiers against many datasets. Open source software to be released later this summer, with the goal of making EEG data collection and ML analysis simple for researchers

5/20/2017 5:34 PM

 **yannick** :

 >octonomy so I guess youll be involved in the Mother of All BCI Benchmark :stuck_out_tongue: (<#C588BQVH9|moabb> )

5/21/2017 5:12 PM

 **octonomy** :

 >Yep I'm going to try and make myself useful

5/30/2017 2:55 PM

 **andyh616** :

 >let me know if you are interested! here is the project website: <https://github.com/ContextLab/hypertools>

5/30/2017 2:56 PM

 **andyh616** :

 >we are participating in the mozilla code sprint this thurs and fri: <https://mozilla.github.io/global-sprint/> it would be awesome if anybody was interested in helping to implement the real-time plotting feature

5/30/2017 3:06 PM

 **yannick** :

 >Nice work andyh616! It sounds like something naoto &amp; sidksv would be interested in ^

5/30/2017 3:06 PM

 **andyh616** :

 >thanks!

5/30/2017 3:07 PM

 **andyh616** :

 >naoto sidksv DM me if you might be interested :slightly_smiling_face:

5/30/2017 3:24 PM

 **aj** :

 >andyh616 hey!

5/30/2017 3:25 PM

 **andyh616** :

 >hey man! hows it hangin?

5/30/2017 3:45 PM

 **bciguy** :

 >Hey <!channel> has anyone here applied DEEP LEARNING to RAW EEG? As far as Im aware most groups are still doing feature extraction by hand, so I thought this would be the best group to ask.

5/30/2017 3:46 PM

 **salazarparis** :

 >We do it <http://www.synapbox.com|www.synapbox.com> EEG and Facial recognition/Eye-tracking

5/30/2017 3:46 PM

 **alexandre.barachant** :

 >bciguy  <https://arxiv.org/pdf/1703.05051.pdf>

5/30/2017 3:46 PM

 **bciguy** :

 >salazarparis: you are applying deep learning directly to raw EEG?

5/30/2017 3:46 PM

 **hassan** :

 >salazarparis  and does it work?

5/30/2017 3:47 PM

 **salazarparis** :

 >Yes actually we are using Emotiv and Neurosky (Attention only)

5/30/2017 3:47 PM

 **bciguy** :

 >what kind of network are you using?

5/30/2017 3:47 PM

 **salazarparis** :

 >we work with Emotiv and Neurosky

5/30/2017 3:47 PM

 **bciguy** :

 >how do you overcome overfitting?

5/30/2017 3:48 PM

 **salazarparis** :

 >but we prefered to play with raw data from facial recognition and eyetracking

5/30/2017 3:49 PM

 **salazarparis** :

 >we can talk it somewhere else, we are trying to manage our know-how internally with specific people

5/30/2017 3:49 PM

 **salazarparis** :

 >not yet open to all

5/30/2017 3:49 PM

 **alexandre.barachant** :

 >there was a special session at the 2016 BCI meeting. Long story short, no one made it works better than hand crafted feature + LDA

5/30/2017 3:50 PM

 **alexandre.barachant** :

 >(that's not completely true, but that was the feeling)

5/30/2017 3:50 PM

 **yannick** :

 >Because everybody were using their own datasets, or people were leveraging the all the datasets available online as a general training, and then retraining for the task at hand? (kinda transfer learning from general EEG to specific EEG)

5/30/2017 3:50 PM

 **bciguy** :

 >alexandre.barachant: very interesting, I would love to see that presentation.. Do you know why it didnt work? Due to overfitting?

5/30/2017 3:51 PM

 **hassan** :

 >I saw once that US army (or a related agency) released  about 100 GB of raw EEG data. Cannot find the link. However, do we really consider this as an enough data to model a complex signal like EEG via deep learning?

5/30/2017 3:52 PM

 **alexandre.barachant** :

 >hassan, yep, those guy where the only one to present kind of good results at the conference

5/30/2017 3:53 PM

 **salazarparis** :

 >would you like to check an opportunity @synapbox ?

5/30/2017 3:53 PM

 **yannick** :

 >You obviously cant do deep learning with your own data within a lab experiment. Youll train on noise and overfit big time. You need a massive amount that will kinda learn what general EEG is, then learn the specificity of the task at hand.

5/30/2017 3:54 PM

 **alexandre.barachant** :

 >IMO, reason why it is not that efficient right now is :

> 
- Dataset are too small.

> 
- Most problem are binary classification problem, where current feature extraction are quasi-optimal.

> 
- DL don't like noisy data. DL like complex and structured data with a good SNR (like image, text, etc)

5/30/2017 3:55 PM

 **bciguy** :

 >salazarparis not sure I understand your answer - is this^ a solicitation for a job or future customer?

5/30/2017 3:56 PM

 **alexandre.barachant** :

 >the paper i pointed out here, they took a interesting approach, which is to build an architecture that reproduce current feature extraction pipeline. That's a way to let the network learn parameters that makes sense and can be interpreted

5/30/2017 3:56 PM

 **alexandre.barachant** :

 >the paper i pointed out here, they took a interesting approach, which is to build an architecture that reproduce current feature extraction pipeline. That's a way to let the network learn parameters that makes sense and can be interpreted

5/30/2017 3:57 PM

 **alexandre.barachant** :

 >it's basically like injecting a little bit of domain knowledge to help convergence

5/30/2017 3:57 PM

 **bciguy** :

 >alexandre.barachant: I get your reasoning here, but isnt the whole theory behind DL that the autoencoders create features in the hidden layers, and wouldnt that deal with the noise issue? Again, all theoretical and a very interesting discussion :smile:

5/30/2017 3:58 PM

 **bciguy** :

 >alexandre.barachant: yep, but the network does it on its own with data

5/30/2017 3:58 PM

 **salazarparis** :

 >I see you are in this

5/30/2017 3:58 PM

 **salazarparis** :

 >nice

5/30/2017 3:58 PM

 **bciguy** :

 >alexandre.barachant: yes this was my thought exactly, thanks again

5/30/2017 3:58 PM

 **salazarparis** :

 ><https://sleepwithaurora.com/>

5/30/2017 3:58 PM

 **salazarparis** :

 >let me know if you want

5/30/2017 3:58 PM

 **alexandre.barachant** :

 >the network learn the parameter, not the architecture.

5/30/2017 3:59 PM

 **bciguy** :

 >salazarparis I would be happy to speak with your team

5/30/2017 3:59 PM

 **bciguy** :

 >email me at <mailto:daniel@iwinks.org|daniel@iwinks.org>

5/30/2017 3:59 PM

 **alexandre.barachant** :

 >yes, but when feature are buried in noise, the auto-encoder has a lot of trouble to converge to a good solution

5/30/2017 4:00 PM

 **bciguy** :

 >I see what you are saying, I forgot to note the utility of BSS as a preprocessing step (PCA/ICA / Hilbert etc)

5/30/2017 4:02 PM

 **bciguy** :

 >semantics& the knowledge is in the neurons :wink:

5/30/2017 4:02 PM

 **salazarparis** :

 >ok, I will reach you tomorrow for sure

5/30/2017 4:02 PM

 **salazarparis** :

 >have a great day

5/30/2017 4:02 PM

 **alexandre.barachant** :

 >by architecture, i mean the amount and type of layer you pile up

5/30/2017 4:03 PM

 **ray_cassani** :

 >can't be possible the preprocessing is also a layer in the DL model? so the it learned rather than imposed?

5/30/2017 4:03 PM

 **hassan** :

 >alexandre.barachant: Do you have a link to their publications about that (if any)?

5/30/2017 4:03 PM

 **bciguy** :

 >yannick: why do you say this? Standard image recognition samples are within the same range as EEG 1s single trial / single channel (dim reduced) samples.

5/30/2017 4:04 PM

 **alexandre.barachant** :

 >for example, 1D conv layer are like temporal filter. by adding this layer you tell the network 'learn me the optimal temporal filter'.

> 


> 
The network by itself is not trying to figure out what kind of layer it should use (yet)

5/30/2017 4:05 PM

 **alexandre.barachant** :

 >yes, that was basically what they did in the paper i shared here

5/30/2017 4:10 PM

 **mrkrause** :

 >These end-to-end pipelines are all the rage right now--Ive seen a few kicking around for speech recognition too. 

> 


> 
Technically, its really impressive and I can see how (e.g.) not having to choose the filter settings is nice. On the other hand, I worry that they provide new and exciting ways to shoot oneself in the foot (what if the 60 Hz noise varies between conditions or subjects?) and it seems like you would have to completely retrain the model even after trivial changes (e.g., sampling rate)

5/30/2017 4:37 PM

 **yannick** :

 >Standard samples for image recognition problem can be within the same data size range. Not sure exactly what you mean here?

5/30/2017 4:39 PM

 **bciguy** :

 >Im saying that one sample (image) in the computer vision problem can be similar in size to a single trial single channel EEG sample

5/30/2017 4:40 PM

 **bciguy** :

 >Im calling you out on You obviously cant do deep learning with your own data within a lab experiment

5/30/2017 4:49 PM

 **yannick** :

 >Yes, and if you try to classify X and Os you need little samples because the data is highly structured with fairly low variance. The more complex the image and the more variance (e.g. races of dogs) the more data you will need. But a real-life image remains a highly structured piece of data.

5/30/2017 4:51 PM

 **yannick** :

 >EEG and time series such as stock market are not  necessarily as structured. Which makes Deep Learning harder.

5/30/2017 5:20 PM

 **dano** :

 >using matplotlib 2.0.2

5/30/2017 5:20 PM

 **dano** :

 >using matplotlib 2.0.2

5/30/2017 5:23 PM

 **alexandre.barachant** :

 >dano not sure it will wokrs , but try the parameter `interpolation='bilinear'`

5/30/2017 5:25 PM

 **dano** :

 >thanks!

5/30/2017 7:29 PM

 **dano** :

 >the interpolation parameter isn't in the matplotlib docs for specgram, I'll write a note to the devs

5/30/2017 7:30 PM

 **alexandre.barachant** :

 >it's in **kargs

5/30/2017 7:31 PM

 **alexandre.barachant** :

 >it's in the parameters for imshow or something like this

5/30/2017 7:31 PM

 **alexandre.barachant** :

 >it's in the parameters for imshow or something like this

5/30/2017 7:31 PM

 **dano** :

 >yea, it's there for imshow

5/30/2017 7:31 PM

 **alexandre.barachant** :

 >**kwargs :

> 


> 
Additional kwargs are passed on to imshow which makes the specgram image

5/30/2017 7:31 PM

 **dano** :

 >ahh, I see, imshow's like the general purpose plotting funciton

5/30/2017 7:32 PM

 **alexandre.barachant** :

 >(from the doc)

5/30/2017 7:32 PM

 **alexandre.barachant** :

 >yep, when I don't find the right param for this kind of thing, i often look at the **kargs param from the doc to know which base function it is using

5/30/2017 7:33 PM

 **alexandre.barachant** :

 >that's a bit annoying, but it usually works

5/30/2017 8:36 PM

 **bciguy** :

 >yannick when you say structured do you mean that latent variables have relatively lower variance?

5/30/2017 8:37 PM

 **bciguy** :

 >Yes EEG is noisy, everyone here knows that. I dont expect DL to work out of the box for EEG/BCI, and weve already talked about a few of the reasons why. However I suspect that it is going to be a very powerful tool in the next decade of EEG/BCI research, since it has made such a significant impact in *virtually all other domains of machine learning*, but not yet in EEG/BCIs.

5/30/2017 8:48 PM

 **bciguy** :

 >I dont expect DL to work out of the box for all EEG/BCI applications, and weve already talked about a few of the challenges for attempting to do so in this channel. However there must be an EEG correlate to Eigenimages or the like appearing in computer vision, and its difficult to even imagine what deep learning might be able to tell us about our datasets without just doing it (my excuse is lack of time!) I just wanted to have this discussion since I dont see it going on anywhere else.

5/30/2017 9:02 PM

 **yannick** :

 >Im using the X and O example because its a popular one in Deep Learning, simpler than MNIST. (just finished Yoshua Bengio Deep Learnings Class at University Montreal so I might be a little too much into it haha.)

> 
There is no doubt that Deep Learning will have a significant impact in the coming years, but like any other fields deep learning impacted, data is key. We need efforts that can leverage large(r) amount of data. The performance we see today in deep learning is also possible because of the amount of images of a cat or text or speech available online. All the large corpus of organized data now available online made a huge difference in the field, now moving so fast. MNIST, MSCOCO, LSUN, Flickr, Cornell Movie Dialogue, Stanford Twitter Sentiment, etc.

> 
What will help Deep Learning for EEG/BCI, is a similar grouping of data and benchmark to test algorithms to iterate quickly on approaches. Deep Learning right now is a lot of Try, Try, Try, Try& No one can tell what hyper parameter to use and such. So its all about iterating quickly. Which the EEG/BCI field need to get better at.

5/30/2017 9:06 PM

 **yannick** :

 >The field is moving so fast that the class itself (Deep Learning) is about What happened in the last 2-3 years. And the final project description says To our knowledge, this is a novel task and has never been done before, so a successful project would in fact be a valuable research contribution.  However we also designed the project so that a very simple solution will still be able to achieve reasonable results.  (quite intimidating, hahahaha)

5/30/2017 9:07 PM

 **yannick** :

 ><https://ift6266h17.wordpress.com/project-description/>

> 
(the final project for the class)

5/31/2017 2:20 PM

 **naoto** :

 >andyh616: I'm not available this week so I can't help you but it seems quite relevant to what I'm doing. I use t-SNE on training/calibration data and mapping real-time data by finding the smallest Euclidean distance <http://naotohieda.com/muse/>

5/31/2017 2:25 PM

 **andyh616** :

 >thats awesome! the package we are developing currently plots multivariate data using PCA, but we are extending it to support, t-SNE, MDS, and a whole bunch more.  Hopefully, we'll support streaming data soon.  I'd love to chat about your project sometime :slightly_smiling_face:

5/31/2017 8:25 PM

 **bciguy** :

 >yannick luckily my company is about to release a device that will create a massive database of single channel forehead (FP1-FP2) EEG  during sleep (or any other activity) from thousands of users around the world. What would you like to see  us do with this database that could be impactful for NeuroTechX and the field in general?

6/1/2017 1:35 PM

 **andyh616** :

 >if anyone is interested, we're hacking on eeg data visualization using hypertools: <http://hypertools.readthedocs.io/en/latest/> today and tommorow in the mozilla sprint. the goal is to get streaming eeg data from openbci in a realtime plot as a line in 3D using dimensionality reduction. if you are interested in getting involved, let me know!

6/1/2017 2:12 PM

 **bryan_j** :

 >andyh616: dano

6/1/2017 4:39 PM

 **vjayaram** :

 >What sort of dimensionality reduction?

6/1/2017 4:57 PM

 **dano** :

 >Awesome! I might not be able to help much since I'm also working on a mozilla sprint project: <https://github.com/NeuroTechX/eeg-101>

> 
However, I'd love to take a look at the library. Showing some cool data visualization might be fun for this upcoming outreach event we're holding

6/1/2017 8:50 PM

 **andyh616** :

 >vjayaram - currently, PCA. but we're going to support ICA, t-SNE, MDS, Isomap and a few more

6/1/2017 8:51 PM

 **andyh616** :

 >dano no worries! eeg-101 looks great! i've almost got a streaming version working, but it will be a little while til its generally usable i think

6/15/2017 4:34 PM

 **davidevaleriani** :

 >Hi everyone, I have started working with the OpenBCI 8bit after a few months and the board does not connect to the dongle anymore, although the LEDs are on. I have changed the battery with a new one, but nothing. Do you have any suggestions on what to try?

6/21/2017 4:53 PM

 **davidevaleriani** :

 >Hi all, I am trying to use the MNE library to extract CSP features from a 4-class MI dataset, however I get the following error:

> 
TypeError: 'float' object cannot be interpreted as an integer

> 
The 2-class version works perfectly. Do you have any example code for 4-class CSP? Am I missing something?

7/4/2017 1:56 PM

 **jk** :

 >Hi peeps. Where can I find various sets of eeg data online?

7/4/2017 2:09 PM

 **alexandre.barachant** :

 >jk 

> 
<http://bnci-horizon-2020.eu/database/data-sets>

> 
<https://zenodo.org/search?page=1&amp;size=20&amp;q=EEG&amp;type=dataset&amp;access_right=open&amp;sort=mostrecent>

7/4/2017 2:11 PM

 **alexandre.barachant** :

 >jk what kind of EEG are you interested in ?

7/4/2017 6:56 PM

 **pat** :

 >Has anyone here looked at Muse's raw_fft channels? I'm trying to recreate the /eeg -&gt; /alpha_absolute processing using the notes at <http://developer.choosemuse.com/research-tools/available-data#Raw_FFTs_for_Each_Channel>, but neither the /eeg -&gt; /raw_fft0 nor /raw_fft0 -&gt; /alpha_absolute appear to be working

7/4/2017 6:58 PM

 **pat** :

 >/raw_fft0 -&gt; /alpha_absolute feels like it should be the simplest, but calculating alpha power from each /raw_fft0 doesn't match the /alpha_absolute emitted just after:

7/4/2017 7:13 PM

 **pat** :

 >is there usually averaging added to alphas to smooth them out over time?

7/5/2017 8:22 PM

 **benjamindeleener** :

 >fred-simard nice work! I was wondering if you would like to share the code so we can try to reproduce? It would be awesome to try get the same results as you

7/5/2017 8:55 PM

 **dano** :

 >pat good detective work!

7/5/2017 8:56 PM

 **dano** :

 >Any ideas, hubertjb?

7/6/2017 12:43 PM

 **qbarthelemy** :

 >&gt; 1. SSVEP is detected using CCA (cross-canonical Analysis) 

> 
Yes. But CCA is not able to treat a resting-state class, contrary to Riemannian geometry. See <https://hal-uvsq.archives-ouvertes.fr/hal-01351623/document>

7/6/2017 1:26 PM

 **fred-simard** :

 >okbalefthanded qbarthelemy Thanks guys, really nice of you, I didn't expected to get answers. To be fair, I already had the answers for myself, although I haven't wrote the report. Since you were nice enough to share your methods with me, I'll do the same:

> 
1. I got some pretty good results using Bayesian classifier over the native statistics of the SSVEP, that is the f-test. The parametric formulation in the Bayesian framework leads to an intuitive formulation of the problem that allowed me to build a weakly-supervised detector that performed at 75% without any training (biased toward idle, so I had less than 2% of false positive).

7/6/2017 10:27 PM

 **samuelbg13** :

 >Hi guys! I am interested in BMIs and neurorobotics. I wanted to ask about the "mental commands" of the cognitive suite of the Emotiv Epoc, the famous virtual cube. Has anybody worked with that?  I am just wondering how does it really work, since as they brand it could seem it performs better than the standard paradigms of motor imagery decoded from SMRs.  How do they manage to get rid of all the perturbations? And assuming that the perturbations are somehow useful as part of the signal (i.e. muscle signals from the face), do you think it would work with locked-in and completely locked-in patients?  Any literature on the matter would be much appreciated :slightly_smiling_face:.

7/7/2017 1:40 PM

 **jk** :

 >alexandre.barachant I found these interesting - music (<http://doc.ml.tu-berlin.de/bbci/BNCIHorizon2020-MusicBCI/BNCI_MusicBCI.pdf>) and emergency brake (<https://lampx.tugraz.at/~bci/database/002-2016/description.txt>)

7/7/2017 1:43 PM

 **jk** :

 >alexandre.barachant I'm trying to get openvibe to run on my mac. Did you ever get chance to write that script for mac port?

7/7/2017 2:26 PM

 **alexandre.barachant** :

 >jk no, I gave up Mac and came back to my good old Linux laptop.

7/9/2017 5:22 AM

 **rashi** :

 >I've tried it out but I am no neuroscientist so I don't know what your words mean.  Perhaps you could ask questions and I'll tell you what I recall from trying it out

7/9/2017 9:09 PM

 **theengramproject** :

 >Hi guys, I am am a artist who has been working with the Emotiv insight to make music for a upcoming album I have been stumped for a while any suggestions?

7/10/2017 5:16 AM

 **rashi** :

 >theengramproject Wha

7/10/2017 5:16 AM

 **rashi** :

 >What's your questi

7/10/2017 5:16 AM

 **rashi** :

 >on?

7/10/2017 12:34 PM

 **samuelbg13** :

 >Hi rashi!  Many thanks. Have you worked with the mental commands suite? I was just wondering what is the machine learning paradigm behind it... Could you tell me how well has it worked for you? Is it robust and trustable? Does it work well with new people when they try it for the first time? 

7/10/2017 11:20 PM

 **yannick** :

 >Hey theengramproject, like rashi pointed out, your question isnt very clear&

7/11/2017 2:27 AM

 **theengramproject** :

 >How do I convert the eeg raw data into midi?

7/11/2017 7:31 PM

 **naoto** :

 >theengramproject do you have SDK for raw EEG? I know there's a reverse engineered script for Epoc (so you don't need the expensive SDK) but it seems they don't support Insight <http://github.com/openyou/emokit>

7/12/2017 3:42 PM

 **fred-simard** :

 >jmhorschig You are right. I am indeed reporting the t-test p-value, but erroneously multiplied by 100, I fixed it on my end and added the trial length (15 seconds). 

> 


> 
I do see the alpha wave on screen (raw-eeg past values, when I open my eyes). The high p-value is likely due to the outliers seen in the histogram and small number of samples (N=14), which limits the robustness of the mean statistic. This is why I complemented with a test on the median. Thanks for the feedback.

7/18/2017 12:59 PM

 **mesca** :

 >Hey everyone, what is the state of the art in zero-shot (binary) classification of ERP components?

7/18/2017 12:59 PM

 **mesca** :

 >In other words, how to classify ERP from unknown subjects?

7/18/2017 12:59 PM

 **mesca** :

 >Any paper or method you can recommend?

7/18/2017 1:00 PM

 **mesca** :

 >My intuition would be to ensemble many weak models in order to increase robustness, but I am wondering if there is a better/cleaner/simpler way to achieve this.

7/18/2017 1:10 PM

 **alexandre.barachant** :

 >it's actually an active area of research.

> 
I would say, there is 3 school for this problem :

> 
- learn a more generalizable model (by training on a very large number of subject and hope to learn invariance). This is generally the deep-learning road.

> 
- semi-supervised / unsupervised adaptation and transfert learning ( <https://arxiv.org/pdf/1409.0107.pdf>, <http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0102504>) 

> 
- Ensembling and meta learning (<https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5032911/pdf/fnins-10-00430.pdf>)

7/18/2017 1:18 PM

 **alexandre.barachant** :

 >For ERP, i'm leaning toward the solution 1 at the moment, because i think we have a real shot for that as soon as we have enough data.

7/18/2017 1:20 PM

 **alexandre.barachant** :

 >for neural oscillation/motor imagery, it might be harder because there is much more variability between individual. But for ERP, i found the patterns remarkably similar between subjects

7/18/2017 2:39 PM

 **mesca** :

 >Thanks alexandre.barachant

7/18/2017 2:40 PM

 **mesca** :

 >I trained a LSTM on 10 subjects (8000+ trials) and could not do better than regulated LDA.

7/18/2017 2:40 PM

 **alexandre.barachant** :

 >does not surprise me

7/18/2017 2:41 PM

 **mesca** :

 >I will review the other papers this week.

7/19/2017 8:56 AM

 **dojeda** :

 >Hello, does any know where I can find the specification of EGI file formats? I am using mne-python to read some raw data of that format and it is digitizing the signal incorrectly.

7/19/2017 3:34 PM

 **thoth** :

 >Hi, How many electrodes are necessary for build an experiment of BCI.

7/19/2017 3:37 PM

 **alexandre.barachant** :

 >thoth as many as you can unless you already have data or unless you know what type of brain activity you are aiming at detecting, in this case you can go down to 8 channel if they are well positioned

7/19/2017 4:15 PM

 **thoth** :

 >alexandre.barachant  thanks you. What would happen if it is taking data only for Fp2, What would be it serve this raw.

7/19/2017 4:19 PM

 **alexandre.barachant** :

 >thoth i can not really answer this. with FP2, you will get artifact related to eye movement and blinks, and some brain activity from the frontal lobe

7/19/2017 4:23 PM

 **thoth** :

 >What are the activities of the frontal lobe?

7/19/2017 10:48 PM

 **okbalefthanded** :

 >On this study: <http://www.sciencedirect.com/science/article/pii/S0165027016302680>

> 


> 
the authors used Compressed Sensing with an RBM to classify motion onset VEP (early ERPs), their approach had better accuracy on subject with low performance

7/20/2017 3:36 PM

 **mesca** :

 >Thanks okbalefthanded

7/21/2017 2:14 AM

 **andyh616** :

 >alexandre.barachant - and anybody who might be interested - if you could place 8 EEG channels anywhere, do you think there is an generalized optimal electrode configuration that is task-independent?

7/21/2017 2:16 AM

 **andyh616** :

 >to maximize information / minimize redundancy

7/21/2017 2:21 AM

 **andyh616** :

 >im thinking that you could take a resting state dataset with many electrodes (maybe 128+),  select 8 randomly, and then move around that space optimizing for most variance explained with 8 electrodes our of N electrodes using gradient descent or something more sophisticated

7/21/2017 2:24 AM

 **andyh616** :

 >even if this worked in a task-dependent way, you could potentially figure out what the best configuration is and use that montage for whatever you are trying to clsassify

7/21/2017 9:35 PM

 **fred-simard** :

 >andyh616 The 10/20 standard is a good place to start. 

7/21/2017 9:41 PM

 **andyh616** :

 >fred-simard, sure, but even within that montage their are many degrees of freedom if you have only 8 electrodes

7/21/2017 9:42 PM

 **andyh616** :

 >the question is about getting the most out of your data in a generalizable way given a fixed number of recording locations

7/22/2017 12:53 AM

 **fred-simard** :

 >andyh616 generally speaking, I bet on the set {F3, F4, C3, Cz, C4, P3, Pz, P4}, all referenced at the mid-point between Cz and Pz or linked ear-lobes. It gives you a good coverage of the cortex and both hemisphere are potentially separable. For what I know, this is the most common 8 electrodes setup that you will find in the literature as well

7/22/2017 1:24 AM

 **andyh616** :

 >:thumbsup: fred-simard you are probably right, but it would be neat to test empirically. some reasons that could be suboptimal: minimal coverage of visual cortex, redundant information along the midline, midline referencing subtracts out midline activity,  cortical folds distort direction of the signal, differences in redundancy of signal by region..

7/22/2017 1:26 AM

 **andyh616** :

 >also, info coming from subcortical structures is likely not distributed uniformly

7/22/2017 8:23 AM

 **alexandre.barachant** :

 >andyh616 i would have proposed a very similar montage, with Oz instead of Pz

7/22/2017 1:14 PM

 **mhough** :

 >andyh616 alexandre.barachant just seeing this. Reminds me of Mark Pfliegers work when he was at neuroscan pre-95 maybe? Using information criteria to determine signal loss from low-density density systems. In his case structured decimation <tel:(256-128-64-32|(256-128-64-32>) but it would be even better to differentiate some of the dominate structured circuit sources for a more nuanced report of a devices sensitivity. I think that was just a poster that neuroscan had on it's website many moons ago. I'll try and find it as it relates to the use of InfoGAN.

7/22/2017 3:36 PM

 **mhough** :

 >He's got something in 2000 on this but I can't find the original poster. Here's a great bunch of people together though:) <https://www.ncbi.nlm.nih.gov/pubmed/24478692>

7/22/2017 9:32 PM

 **andyh616** :

 >Awesome, thanks for the reference mhough !

7/23/2017 4:50 AM

 **andreacoravos** :

 >Has anyone used the DREEM eeg device? Is it any good. Thought this talk was interesting: <https://www.youtube.com/watch?v=dResAPv_o6U&amp;feature=youtu.be>

7/23/2017 3:12 PM

 **yannick** :

 >They did raise $22M for it.

7/24/2017 7:01 AM

 **omer** :

 >dojeda: Are you using NS5?

7/25/2017 5:35 PM

 **mhough** :

 >dojeda sorry did you get an answer on the EGI question. I missed that earlier. I know Jeff Eriksen had some issues previously but it's certainly fixable and I need to do that too:) Where's the EGI reader code from in mne I wonder?

7/25/2017 5:39 PM

 **dojeda** :

 >Well, my problem is just that I don't understand how the values are digitized. It seems that everything is loaded correctly and then multiplied by some values named "cals" that come from the EGI header entry named "value_range". In my case, the EGI header does not have such information, so the mne-tools uses the default, `1e-6`. I just wonder where that comes from and is it reasonable to multiply it by such value.

> 


> 
The code for the EGI reader is here <https://github.com/mne-tools/mne-python/blob/master/mne/io/egi/egi.py>

7/25/2017 5:42 PM

 **dojeda** :

 >omer asked me in a private message if I tried the NS5 software to read it but I don't have it (sorry Omer that I forgot to respond to your question)

7/25/2017 7:07 PM

 **mhough** :

 >dojeda ok. Thanks. So do you have the original recordings? If not, what was the processing chain applied that got you the file you have. Cals can be important but you can write a couple of different outputs into the same format with EGI raw files. Do you know the units of what's in there currently? Could some other tool have output the EGI file format with that missing field? Things to rule out. 

7/25/2017 7:36 PM

 **nedack** :

 >Is someone using timeseries database in ordre to stock EEG data ?

7/26/2017 7:45 AM

 **dojeda** :

 >&gt; Where's the EGI reader code from in mne I wonder?

> 


> 
Oh, I've just realized that you are asking the same question as I am... I do not know where that comes from but it seems that the mne-python developers were in contact with EGI. I am currently trying my luck with them as well. The git blame shows one developer that I know personally so I will try to ask him as well.

> 


> 
Concerning the recordings, I did not acquire these files myself, they were shared to me as-is, and I believe they are the raw files without any preprocessing. I can't be 100% sure, though. I do not have information concerning the units.

> 


> 
On the other hand, I have found EGI example files used in mne-python (see issue <https://github.com/mne-tools/mne-python/issues/1687> ) have that have the same value_range (zero)... perhaps this is normal.

7/26/2017 3:57 PM

 **mhough** :

 >If it's a recording session file then it should have gains and zeros with it and those could be separate files with a raw export. If it's an ERP written out then it should be microvolts and you don't need any cal values. 

7/28/2017 5:35 PM

 **fred-simard** :

 >nedack I built a python API to a mongodb database to store trial-based timeseries and related information. It works fairly well, but it lacks a few features and I'm spending my time on another project right now. Still, it provides a starting point if you want to adapt it for your own needs. Otherwise I suggest you use CSV files, that's the quick and dirty way.

7/28/2017 5:41 PM

 **fred-simard** :

 >andreacoravos I'd be curious to know if this is scientifically proven. I talked with a PI specialized in sleep and EEG about two months ago and although he was aware of the concept, he didn't seemed convinced that using sounds to modulate sleep rythms would actually work. I'm sure you can elicit rythms in auditory areas (and see the effect in EEG), but it's a stretch to claim that you can have a direct effect on the sleep process. For science, all they provide is a white paper, but its not written at a scientific level and the results are quite evasive.

7/29/2017 2:43 AM

 **yannick** :

 >They do have a patent on it (doesnt mean it works, but might interest some of you). They do cite other patents referring to Binaural Beats in their patent.

> 
<https://www.google.com/patents/WO2017021662A1>

7/29/2017 2:59 AM

 **nedack** :

 >Being a Msc student and using different devices (Biopac,Biosemi and Brain Products) on plural projects, I'm thinking about my research workflow : how can i store the data and how can access to it easily and quickly with Matlab, Python or others. 

> 
I want to be able to work with this data in 1,2,X years without too many problems and find all the informations : sampling rate, experimental design etc...

> 


> 
My supervisor keeps all the data in csv, as you propose, but I don't like it ! If I am not mistaken, you are working on intelliPi, have you implemented MongoDB on it ? And Why MongoDB ? I also find Mobbed (10.3389/fninf.2013.00020) based on PostgreSQL but it's only on Matlab and I'm trying to favor Python.

7/29/2017 3:11 PM

 **fred-simard** :

 >yannick andreacoravos Most of the claims are in the form, we stimulate with sounds and we measure an EEG response similar to that of deep sleep. This is a fair statement, I'm not challenging it. But so far, I haven't found the link between the EEG response they measure and the effect on deep sleep (I would expect some kind of psychometrics to support their claim), nor even a proof of the co-localisation of the effect they induce and sleep EEG pattern generators (source localisation study, using EEG and/or fMRI and/or MEG($$$)). I need to specify that I haven't reviewed the literature on the topic, only the few pieces of evidence thrown at me, so it might be out there. I honestly wish that it works, I think it's a great idea and works toward the general promise of EEG-based therapy to reduce reliance on drugs. Let's hope they did their science homework correctly.

7/29/2017 3:19 PM

 **fred-simard** :

 >It's a similar line of thought that lead me to look into DBMS. 

> 


> 
Funny you bring IntelliPi, I backed it up yesterday, I'm canning the project. Great idea, bad design, bad business model. I actually rebuilt the whole IntelliPi pipeline in Python over the last month, much better.

> 


> 
CSV will always be supported, simple format, but the power of a DBMS cannot be neglected. In fact, the tool my mongoDB is missing is a CSV import/export function, that will allow for easier data management. I'm not a big data expert, but the reason I chose mongoDB is because it combines the power of SQL, while providing flexible schemas. In my opinion, the metadata around EEG can be standardized to a great extent, but there will always be a need to add fields on-the-fly for X or Y reasons and scientists don't want to always bother about restrictive schemas. MongoDB allows for that.

> 


> 
I'm on vacation for 2 weeks, but right after, I want to start a git related to my work with EEG, I'll post my mongodb framework. It's incomplete, but it will give you an idea of what I had in mind.

7/30/2017 4:18 PM

 **sc** :

 >Ive worked extensively with Emotivs Cognitiv mental commands suite, and the answer to your question is going to be simple but unfortunately unsatisfying - their algorithm is completely proprietary, so no one outside of the company can tell you exactly what is going on, and anyone inside the company is prevented from doing so by NDA. All of that said, yes it will generally work well with first time users, but only for steering in a single direction, once you try to train it for more than on (ergo left versus right) it tends to have trouble distinguishing. There are several examples on their website and social media of the EPOC being used successfully with certain individuals with special needs, but no I dont think it would be a suitable replacement for motor imagery for someone who is locked in.

7/30/2017 5:09 PM

 **samuelbg13** :

 >Thanks a lot sc!  Why don't you think it could work that well with locked in subjects?

7/30/2017 5:34 PM

 **sc** :

 >I think a direct caregiver might be able to answer more precisely, but when it comes to ALS, the window between which single-finger joystick interactions has closed, and a gaze tracker is no longer useful (where they are truly fully locked in) and the statistical average end of life is so narrow that I think you

7/30/2017 5:40 PM

 **sc** :

 >The main benefit in that instance might be the cost savings between an Insight/EPOC and a medical/research-grade EEG, but honestly with all of the other costs related to someone with the needs of late-stage ALS, I think the difference is not as great as it may initially sound. I might suspect that a higher-end system might be covered under healthcare anyway.

7/30/2017 6:51 PM

 **samuelbg13** :

 >That information is very valuable! :) 

> 
The problem is that sometimes patients cannot elicit MI responses (BCI illiteracy). Forgive me for asking: when you said that MI is more "reliable, reproducible" than Emotiv mental commands, did you mean that it would not be possible to always get a clean (even binary "yes/no") signal in locked in patients? I must admit that I am not a very big fan of evoked potentials such as P300. 

7/30/2017 7:25 PM

 **sc** :

 >Well put it this way, if you have a patient with whom you want to work directly, then by all means it would be worth experimenting with an Emotiv headset. But you should try one out directly yourself first and evaluate how well youre able to control the single direction (yes) versus neutral (no) at will. My guess is youll end up training something like concentration versus no concentration, which is considerably harder to modulate at will versus (say) squeezing a tennis ball with your right hand versus squeezing a tennis ball with your left. What happens when someone asks a question and you need to concentrate to answer? What if the system isnt working for you and youre concentrating on getting it to work, only to keep producing yes responses? Lets say you get around that. Now take off the headset and come back in six hours. Put it back on. Did you get the fit exactly the same? Is the angle a little bit forward or backward? Without an EEG cap and measuring tape how will you align to the same position each time? Say you cant. Now you end up needed to re-train your data each time you put the headset on. But your patient is completely locked in. How easy is it going to be to *reproduce* those same responses each time? Want to check how well it is work? Its a proprietary algorithm, you dont have access to the data to see. And so on.

8/1/2017 9:54 PM

 **tahiltonjr** :

 >I could use assistance from anyone to help me read and interpret a 3 chart comparison of brainwaves from the muse headset and uploaded the data to produce graphs from within Excel.....

8/1/2017 10:04 PM

 **yannick** :

 >Can you share the chart here?

8/1/2017 10:25 PM

 **tahiltonjr** :

 >Yes.... and I also just uploaded a pdf showing all three in a new channel... <#C6GTL3W9K|eeg_via_hypnosis>

8/3/2017 11:37 AM

 **timopheym** :

 >Hey, is anyone has OpenVibe ready dataset for P300 (training and evalution purpose) (they have an example there with Cz, O1 and O2). I wanna test they LDA algorithm and only EEG device i have access to is broken now(

8/4/2017 4:39 PM

 **psoulos** :

 >Is there an open-source reimplementation of the 'concentration' and 'mellow' data that the Muse SDK used to support? The processing they used was from _My Virtual Dream_ <http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0130129>

8/4/2017 4:39 PM

 **psoulos** :

 >It would have been nice if they deprecated support instead of removing it entirely

8/4/2017 11:51 PM

 **pat** :

 >I was trying, but was unable to reimplement even the raw_fft values where the algorithm is described, so stopped there

8/7/2017 5:52 PM

 **sydneyneurotechx** :

 >There is the MOABB Project that alexandre.barachant  is working on. The goal is to create BCI benchmarks and concentration/mellow could eventually be included. What do you think alexandre.barachant ?

8/7/2017 5:53 PM

 **sydneyneurotechx** :

 ><https://github.com/NeuroTechX/moabb>

8/8/2017 6:48 PM

 **agustnr64** :

 >Hi channel. My name is agustin and i am a  biomedical engineering student.

> 
I am starting with my thesis which is related with BCI.

> 
I want built a classifier algorithm using EEG feature in order to move a robotic arm or other divice.

> 
At the moment i focus in find a good low cost adquisition system that allow me processing EEG in real time(online analysis).

> 
I saw systems as OpenBci or Emotive but i do not which is better.

> 
Could you advise on the devices for the acquisition of eeg with which you can do an online processing?

8/8/2017 8:38 PM

 **sydneyneurotechx** :

 >hey agustnr64. The answer will depend on your financial situation, coding experience, as well as the eeg paradigm you want to use. The advantages of the OpenBCI is that it allows for you to flexibly build your system and try different areas of the brain. The Emotiv has a rigid form factor which allows for easier data acquisition, and they provide some algorithms as well. Emotiv though is more expensive per session as you have to pay to access the raw data. Therefore when prototyping, it's usually not worth it. There will be a higher learning curve with OpenBCI, but at the advantage of being more flexible.

8/8/2017 8:39 PM

 **sydneyneurotechx** :

 >So to Summarize:

> 


> 
If you are short on time and have about 2000 to spend (including the money needed for session access, the Emotiv is for you)

> 


> 
If you have more time and short on Money, get the OpenBCI.

> 


> 
If you want to maximize your learning on how to build BCI's. Get the OpenBCI. All the code and schematics are open source, so you can always check them out

8/8/2017 8:39 PM

 **sydneyneurotechx** :

 >Also Check out this reference: hey agustnr64. The answer will depend on your financial situation, coding experience, as well as the eeg paradigm you want to you.

8/8/2017 10:16 PM

 **agustnr64** :

 >hi sydneyneurotechx. That you for your replay. it was so fast and useful.

8/8/2017 10:18 PM

 **agustnr64** :

 >I see the difference between both systems and i think i will get the OpenBci.  It seems to me that it has more advantage and also i account with time

8/8/2017 11:02 PM

 **aj** :

 >agustnr64 great idea! The OpenBCI system is getting really good

8/10/2017 7:55 PM

 **psoulos** :

 >That looks interesting. alexandre.barachant do you have plans to include concentration and mellow? I could reimplement the algorithm in 'My Virtual Dream' which uses relative alpha and gamma waves to detect changes in calmness and concentration. 

8/17/2017 2:06 AM

 **fred-simard** :

 >psoulos I believe they use Beta and Alpha Rythm

8/17/2017 6:16 PM

 **graeme** :

 >psoulos the basic recipe is posted below. It's important to note that this was an experimental algorithm that accidentally snuck out the door in our SDK, but we never intended it to. There are some very important caveats, notably: While Muse produces reliable gamma for post-hoc analysis, real-time gamma in any system is very hard to do because of the influence of EMG overlapping the gamma range. It's especially hard to do real-time gamma with Muse, because the Muse reference is close to the frontalis muscle. What we found was that people were using the concentration metric to produce BCIs that worked primarily on EMG and not EEG, and consequently making bad applications.

8/17/2017 6:17 PM

 **graeme** :

 >The mellow metric is much more robust because it runs on alpha. You could use beta more reliably than gamma for cognitive workload, but you'd still want to really validate this before you start using and sharing it.

8/17/2017 6:17 PM

 **graeme** :

 >In any case, here's the recipe: 

> 


> 
Mellow 

> 
Mellow is based on the relative spectral power of alpha (7.5 - 13 Hz) called RSPa. RSPa uses Relative Band Powers from the Muse SDK called alpha_relative whose values range between 0 and 1. These values are sent out every 100 ms so we recommend taking a moving average of the last 20 values.

> 


> 
Concentrate

> 
Concentrate is based on the relative spectral power of gamma(30 - 44 Hz) called RSPb. RSPb uses Relative Band Powers from the Muse SDK called gamma_relative whose values range between 0 and 1. These values are sent out every 100 ms so we recommend taking a moving average of the last 20 values. Note that the My Virtual Dream paper mentioned above used the beta band instead of the gamma band.

8/17/2017 6:19 PM

 **graeme** :

 >You can make this more robust with some basic machine learning, by creating a band power distribution for the individual user over 30s or so and then scoring relative to that distribution, linearly or non-linearly as you prefer.

8/18/2017 12:34 PM

 **andyh616** :

 >anybody know where I can get an open EEG/MEG dataset of multiple subjects watching the same movie?

8/18/2017 12:40 PM

 **andyh616** :

 >looking to run a quick analysis for a grant :flushed:

8/18/2017 12:41 PM

 **alexandre.barachant** :

 >trying to do some alignement ?*

8/18/2017 12:43 PM

 **alexandre.barachant** :

 >I don't have a dataset in mind. it's possible that they did that in the HCP

8/18/2017 1:50 PM

 **andyh616** :

 >trying to show intersubject functional connectivity varies over time using movie stimuli, ill check HCP, thanks!

8/18/2017 2:00 PM

 **andyh616** :

 >*intersubject correlation -&gt; timeseries of average pairwise (across-subject) correlation of raw electrode values using a sliding window

8/19/2017 12:51 PM

 **andyh616** :

 >found a phenomenal open EEG dataset, check it out: <http://fcon_1000.projects.nitrc.org/indi/cmi_eeg/index.html>

8/19/2017 12:53 PM

 **yannick** :

 >You should add it to the Awesome BCI List :slightly_smiling_face:

8/19/2017 1:00 PM

 **andyh616** :

 >good call! will do

8/19/2017 1:02 PM

 **yannick** :

 >Phenomenal stuff is good enough to make the cut for the Awesome list :stuck_out_tongue:

8/19/2017 1:03 PM

 **andyh616** :

 >:slightly_smiling_face: id have to agree

8/19/2017 1:04 PM

 **andyh616** :

 >turns out its already on there! :flushed:

8/22/2017 6:06 AM

 **sydneyneurotechx** :

 >Apparently this company that just went through YC can predict Alzheimer's 15 years before symptoms

8/22/2017 6:06 AM

 **sydneyneurotechx** :

 ><https://www.darmiyan.com/>

8/22/2017 10:51 PM

 **aj** :

 >Wow

8/22/2017 11:04 PM

 **sydneyneurotechx** :

 >Any ideas of how they do their analysis?

8/23/2017 12:59 AM

 **benjamindeleener** :

 >sydneyneurotechx seems like they applied this theory on diffusion MRI: <https://www.ncbi.nlm.nih.gov/pubmed/27739821?otool=nynyumlib&amp;myncbishare=nynyumlib>

8/23/2017 1:00 AM

 **benjamindeleener** :

 >Not an expert in Alzheimers disease so I cannot say if it promising or even real

8/23/2017 3:38 AM

 **mhough** :

 >andyh616 yes, it is isn't it:)

8/23/2017 3:40 AM

 **mhough** :

 >Holy schnitzel! Damn benjamindeleener that is an interesting article. Thanks

8/23/2017 5:16 PM

 **nuno** :

 >Hi everyone, is there any P300 open-source code you recommend?

8/23/2017 5:16 PM

 **nuno** :

 >I'd like to play around a bit for an application we are preparing but would be great if I could jump some of the steps of setting up the paradigm.

8/23/2017 5:17 PM

 **nuno** :

 >If you know of any python code that would be even better :slightly_smiling_face:

8/23/2017 5:17 PM

 **nuno** :

 >thanks

8/23/2017 5:19 PM

 **nuno** :

 >alexandre.barachant do you have any suggestions? :wink:

8/23/2017 5:20 PM

 **yrenard** :

 >have you looked at OpenViBE ?

8/23/2017 5:21 PM

 **yrenard** :

 >btw, P300 covers a wide range of requirements from acquisition synchronisation to actual modeling of the signal, be sure to not look only at code but also understand the background

8/23/2017 5:22 PM

 **nuno** :

 >thanks! I'll have a look at OpenVibe and what they already have implemented

8/23/2017 5:22 PM

 **yrenard** :

 >sure, probably not the latest way of doing it, but definitely decent :wink:

8/23/2017 5:26 PM

 **dano** :

 >alexandre.barachant's muse-lsl repo has python scripts for doing P300 experiments <https://github.com/alexandrebarachant/muse-lsl>

8/23/2017 5:53 PM

 **nuno** :

 >Thanks dano!

8/23/2017 6:01 PM

 **yrenard** :

 >dano isn't this essentially for data collection ? it does no detection, right ?

8/23/2017 6:04 PM

 **dano** :

 >Yea, mostly. He has a notebook with his P300 analysis code in it though

8/23/2017 6:05 PM

 **yrenard** :

 >ah gotcha

8/23/2017 6:05 PM

 **graeme** :

 >It does the analysis too, and builds a classifier. And hubertjb

8/23/2017 6:31 PM

 **alexandre.barachant** :

 >my P300 experiment is more about an oddball paradigm than an P300 BCI.

> 
@numo, if you are looking for a P300 BCI, openvibe is your best guess. If you are more interested in reproducing a classical neuroscience experiement, then mine is simpler

8/24/2017 12:46 AM

 **sc** :

 >Hey all, looking to dive into ML a bit, thinking about a TensorFlow Lite application, training attention versus neutral in the cloud, then being able to execute the trained set on Android in realtime, even when offline. Just looking to keep it simple at first, to get my feet wet with ML and TF. Thought I might use a NeuroSky and compare my results to their eSense attention algorithm. Any pointer on background material to read up, or algoirthms/toolkits to apply once in TF land? (And yes, similar to <#C4LSDAE95|neurodoro> type stuff)

8/26/2017 5:02 AM

 **psoulos** :

 >Hey sc, you should take a look at My Virtual Dream. It was an art project that used the Muse headset to detect "calm" and "concentrated"

8/26/2017 5:04 AM

 **psoulos** :

 >The values used to be included directly as an experimental value in the Muse SDK but were removed

8/26/2017 3:48 PM

 **sc** :

 >Very nice psoulos! I used those values at the Exploratorium exhibit for the Blooms with the rest of the crew (who eventually led into co-forming NeuroTechX with the Montreal  and NY folks). Looks like some good background info here. Ill have to chase up the referenced articles too.

8/26/2017 4:52 PM

 **aj** :

 >hope over to <#C08T2SENQ|devices> for specs and discussion of specs of a new 1 inch 8 chan eeg for arduino and raspberry pi <http://g.recordit.co/Q0xsLgfqvI.gif>

8/27/2017 2:33 AM

 **travjav** :

 >Hey Community! Has anyone successfully applied machine learning to their data recently with the Ganglion ? What tech stack did you use? Hardware, Language, libraries etc.  I just created a pretty cool application with a React.js front end displaying the array of objects ( microvolts) by having the server running on my local machine and was using sockets to push the data to the front. I would like to make the site live connect the local backend with the server and display live data on the net!

8/27/2017 6:07 PM

 **gabe.ibagon** :

 >heya - I do a lot of work with TF and EEG data. Some good papers to look at:<https://arxiv.org/abs/1703.05051>

8/27/2017 6:16 PM

 **gabe.ibagon** :

 >heya - I've done some work with TF and EEG data. Some good papers to start with:

> 


> 
<https://arxiv.org/abs/1703.05051>

> 
<https://arxiv.org/abs/1611.08024>

> 
<https://arxiv.org/abs/1511.06448>

> 
<https://arxiv.org/pdf/1511.04306>

> 


> 
All of these papers aren't too tricky to implement in TF or Keras (I recommend to use Keras until you need to construct more complex architectures, at which point you can use both Keras and pure TF). Feel free to message if you have any q's.

8/27/2017 11:43 PM

 **dano** :

 >Thanks Gabe!

8/28/2017 7:41 AM

 **omer** :

 >Hey all, Do anyone has experience with reliable dry EEG electrodes that are not wireless or part of product such as Muse, best if they work with openBCI, but wer'e open to anything... Thanks!

8/28/2017 11:15 AM

 **aj** :

 >Fri just made bigger electrodes!!!

8/28/2017 11:15 AM

 **aj** :

 >They are sooooo much better

8/28/2017 11:16 AM

 **aj** :

 >going through hair 

8/28/2017 11:17 AM

 **aj** :

 ><https://fri-fl-shop.com/product/new-longer-5mm-spike-disposable-reusable-dry-eeg-electrode-tde-210/>

8/28/2017 11:18 AM

 **aj** :

 >Joel was setting up a headset to test these on Friday but I didn't verify the data, if you want to wait, I can ask Joel to email me the data he collects and post here

8/28/2017 11:45 AM

 **omer** :

 >Thanks aj , that''s very helpful, If you can ask him that would be great, did you connect to to open BCI?

8/28/2017 11:50 AM

 **aj** :

 >Cool I'll post here soon! Yea I've written large portions of the Cyton firmware, Cyton and ganglion nodejs drivers and GUI code. Plus made the new wifi shield launching next month. If you ever have questions DM me. 

8/29/2017 3:42 AM

 **sydneyneurotechx** :

 >I've been doing a bit of a dive into Neurofeedback (NF) for ADHD as an alternative to a phamaceutical treatment. Based on my research, it seems that is that for the most part EEG NF is not an effective method of treatment or at best, provides a minor improvement. I was wondering if anyone has done their own research on the matter. 

> 


> 
Some readings: 

> 


> 
<http://www.sciencedirect.com/science/article/pii/S0890856716300958>

> 
<https://link.springer.com/article/10.1007/s00787-016-0902-x>

> 
<http://journals.sagepub.com/doi/abs/10.1177/1087054717693371>

> 
<https://lirias.kuleuven.be/bitstream/123456789/580196/1/The+European+ADHD+Guidelines+Group+replies.pdf>

> 
<http://www.ipeg-society.org/userfiles/files/IPEG%202016-.pdf#page=55>

8/29/2017 6:54 AM

 **jmhorschig** :

 >also check out her research (former colleague of mine): <https://www.researchgate.net/profile/Madelon_Vollebregt/publications>

> 
see especially the 2013 and 2014 publications

8/29/2017 4:09 PM

 **graeme** :

 >Some people I've talked to think that the theta-beta ratio effect that's targeted by most ADHD NFB protocols is actually an artifact of age-related changes at the cusp of theta and alpha that result in the alpha peak, and that there's not much to target there.

8/29/2017 4:10 PM

 **graeme** :

 >But in general I'd say the mixed results from the literature suggest that there might be something there for some people. We know that neurofeedback does work to change spectral power if you train it long enough - it's just a question of whether it's universally effective in all cases of ADHD. (Probably not.)

8/29/2017 4:11 PM

 **graeme** :

 >Important to remember that any improvement without psychotropic medicines is a pretty big deal.

8/31/2017 8:34 AM

 **mikhail.sintsov** :

 >Guys, have you ever seen online data repos for ECOG recordings? I have been working with intracranial LFP and scalp EEG recordings and I want to assess the ECOG abilities. ECOG have really good advantages.

8/31/2017 8:57 AM

 **alexandre.barachant** :

 >mikhail.sintsov : here <https://purl.stanford.edu/xd109qh3109> . it's recording for a classical face versus house ERP paradigm

8/31/2017 8:58 AM

 **alexandre.barachant** :

 >here i have some code to analyse the data : <https://github.com/alexandrebarachant/decoding-brain-challenge-2016>

8/31/2017 8:59 AM

 **mikhail.sintsov** :

 >great, thanks a lot!

8/31/2017 9:00 AM

 **alexandre.barachant** :

 >there is plenty of ECOG data online, but it's not really easy to find them. they are usually released with paper and hosted on obsure university website

8/31/2017 9:00 AM

 **alexandre.barachant** :

 >do you have a more specific paradigm in mind

8/31/2017 9:01 AM

 **alexandre.barachant** :

 >I think it existe a few very popular ECOG dataset where you can partially decode speech

8/31/2017 9:04 AM

 **mikhail.sintsov** :

 >I'm willing to assess its possibilities. I had seen a competition on epilepsy prediction, however, there were no task specific recordings. In terms of spatial and temporal resolution, could you, please, give your personal optinion what place ECOG takes between scalp EEG and intracranial LFP?

8/31/2017 9:05 AM

 **alexandre.barachant** :

 >it's closer to LFP than EEG.

8/31/2017 9:06 AM

 **alexandre.barachant** :

 >well, in terms of signal it looks like EEG, but the main difference is access to higher frequency

8/31/2017 9:07 AM

 **alexandre.barachant** :

 >and that makes a lot of difference, because there is a lot more information caried in the high gamma band

8/31/2017 9:07 AM

 **mikhail.sintsov** :

 >Yes, I heard, that it is basically up to 500 Hz, but it is not enough for spikes

8/31/2017 9:07 AM

 **mikhail.sintsov** :

 >There were a possible spike registration from L1-2 at max, but not L4 which is more crucial

8/31/2017 9:08 AM

 **alexandre.barachant** :

 >yep, it is still recording the combined activity of a neuron population, but the spatial resolution is way better than EEG

8/31/2017 9:11 AM

 **alexandre.barachant** :

 >ECoG has a much higher information content than EEG. However, it's invasive and therefore you rarely have a large coverage of the brain. Still, it has a way better coverage than the spikes recording that a re limited to a few mm of cortex at best.

8/31/2017 9:13 AM

 **mikhail.sintsov** :

 >Good, thank you for the council :smiley:

8/31/2017 9:15 AM

 **alexandre.barachant** :

 >i don't know how to answer your question properly. For me they serve different purpose. If you know exactly where your region of interest is, then use spike recording. if you want to record brain activity on a larger spatial scale or don't know where it is, ECoG is your best guess

8/31/2017 9:24 AM

 **mikhail.sintsov** :

 >ok, to be short. imagine a developing brain, which matures and grows in size. there is no convinient way to chronically record the neuronal activity with intracortical electrodes as it impairs natural development. an idea was to use ecog like here in rats (<https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5193146/>). but the question was, if its resolution is suitable for our purposes. therefore I wanted to have a glance on its data before moving there.

8/31/2017 9:31 AM

 **alexandre.barachant** :

 >I see, i'm not entirely sure ecog will not impact the devellopment of the brain, but thats another question :slightly_smiling_face: it could be quite interesting in rat since you will get whole brain recording. you can look at connectivity and this kind of thing. but its very different than spikes recording, and the data analysis is much more involving

8/31/2017 5:35 PM

 **joeyo** :

 >For what it's worth, Buzs�ki has a paper claiming to record spikes from uECoG

8/31/2017 5:35 PM

 **joeyo** :

 ><https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4308485/>

8/31/2017 5:49 PM

 **alexandre.barachant** :

 >yep, if you get a high enough temporal resolution (sampling frequency), then it's a deconvolution issues

9/2/2017 1:38 AM

 **travjav** :

 >Thats great stuff thanks Gabe!

9/2/2017 3:20 AM

 **aj** :

 >check out the amazing feature list on the new v3.0.0 firmware for OpenBCI <https://github.com/OpenBCI/OpenBCI_32bit_Library/releases/tag/v3.0.0>

9/2/2017 3:22 AM

 **aj** :

 >hello wifi, variable sample rates (research speeds 1kHz+) and you can read directly from the external serial port with a simple function call allowing you to get up to 1000Hz over hard wired serial.

9/2/2017 3:22 AM

 **aj** :

 >also can read from analog or digital ports on the top of the board with a simple command now

9/2/2017 3:22 AM

 **aj** :

 >so no longer do you have to change the firmware just to read from a button

9/5/2017 2:34 AM

 **fred-simard** :

 >Hello everyone, I dare asking: as anybody successfully measured the Beta wave, using a self-made electrode placement? This is a very common signal, leveraged by many consumer grade systems: Muse, Neurosky, Axio Headband, Neuroservo headcap and more. The standard setup is simple, ref in the middle of forehead and the signal is bilateral at Fp1, Fp2. I was able to measure it once, using ref at linked-earlobes and Fp1, Fp2, but I'm having a hard time measuring it reliably. Experimentally, I compare mind wandering vs. backward count by step of 3. Does anyone has any general suggestions to make, I'm a bit puzzled, because this is such a standard paradigm...

9/5/2017 2:35 AM

 **fred-simard** :

 >I only tried with myself by the way. I will be trying with someone shortly to at least rule this factor out.

9/6/2017 7:40 PM

 **aj** :

 >The openbci wifi shield is now on sale! <https://shop.openbci.com/collections/frontpage/products/wifi-shield?variant=44534009550>

9/6/2017 7:41 PM

 **aj** :

 >I really set out to make getting data from the openbci dead simple. Finally you can get 500hz json data with nano volts and timestamps! No more serial port!!

9/6/2017 9:52 PM

 **aj** :

 >and you can control it with http commands :slightly_smiling_face: <https://app.swaggerhub.com/apis/pushtheworld/openbci-wifi-server/1.3.0>

9/10/2017 2:09 PM

 **aj** :

 >Hey! I want to make an example for Open BCI wifi capabilities and make a mobile EMT/Ambulance prototype. Hook up one channel to EKG, Hook up another for EMG for chest respiratory compressions, and 4 channels for EEG, wet electrode to temples with reference with wet electrode too. Could bundle a tiny pack together for so cheap and boom!

9/10/2017 2:09 PM

 **aj** :

 >Any advice for settings the ADS1299 Shouod have to pull this off?

9/10/2017 2:09 PM

 **aj** :

 >Can also put a pulse sensor on too!

9/12/2017 12:07 AM

 **fred-simard** :

 >aj I recommend you plan to use differential lines (you can still short together all the EEG negative together externally for unipolar configuration) and you might want to set a different gain for each channel, depending on what they are used for.

9/12/2017 10:14 AM

 **aj** :

 >Ah good idea okay thanks Fred!

9/13/2017 8:10 PM

 **aj** :

 >Native Python driver for OpenBCI Wifi Shield written in 5 hours with new http commands and using the wifi shield to convert raw data to json. Check it out, would love feedback and contributions! <https://github.com/OpenBCI/OpenBCI_Python/pull/54>

9/14/2017 3:04 AM

 **sweetrabh** :

 >has anyone worked on or know about good results using eeg to track eye movement?

9/15/2017 5:33 AM

 **grandmasterspock** :

 >Does anyone know what the most detailed library of EEG data is?

9/15/2017 1:21 PM

 **yannick** :

 >By library you mean dataset and/or list of datasets? 

> 
(as opposed to a code library offering functions such as signal processing and machine learning)

9/15/2017 10:59 PM

 **grandmasterspock** :

 >yannick Yeah I mean dataset.. thanks for clearing that up

9/16/2017 1:14 AM

 **yannick** :

 >Check our the Awesome BCI List on our github

9/21/2017 4:38 PM

 **hectordomorozco** :

 >Friends, Ive a question for you: I recently decided to migrated all my analysis pipeline from MATLAB to Python. I was told that MNE is quite good, so Im giving it a try. Do you know of any other EEG resources in Python that I can use? Specially in terms of more advanced analysis (graph theory, information theory analysis, connectivity, forward modeling&). Thanks :slightly_smiling_face:

9/21/2017 6:34 PM

 **yannick** :

 >+1

> 
Im also interested in the answer!

9/21/2017 8:25 PM

 **psychopomp** :

 >hectordomorozco I've heard of pyeeg but I've never used it before

9/21/2017 8:50 PM

 **hectordomorozco** :

 >psychopomp I checked out the GitHub page and they  havent updated it on a year& Thats not usually a good sign, but Ill check it out. Thanks!

9/21/2017 9:10 PM

 **rohit** :

 >MNE seems most popular among(pyeeg, neurokit) that I have heard of. There are some general biosignal processing python libs biosig, biosignal, bioSPpy etc. 

9/21/2017 10:59 PM

 **hectordomorozco** :

 >Thanks man, Ill check those out, too. Honestly, MNE seems quite nice so far. It has a lot more capabilities than I originally thought it would have

9/22/2017 10:03 AM

 **aj** :

 >anyone have a SPDNet in python

9/22/2017 11:56 AM

 **mikhail.sintsov** :

 >I would also recommend looking at Phy <https://github.com/kwikteam/phy>.

9/28/2017 9:22 AM

 **alexandre.barachant** :

 >Thanks to a contribution of hubertjb, the muse-lsl (<https://github.com/alexandrebarachant/muse-lsl>) repository now have a bunch of new experiemental paradigm:

> 
- Auditory P300

> 
- Face versus House for observing N170

> 
- Visual SSEP

> 
- Auditory SSEP

> 
you can check the notebook folder for data analysis : <https://github.com/alexandrebarachant/muse-lsl/tree/master/notebooks>

9/28/2017 9:23 AM

 **alexandre.barachant** :

 >this is super cool. I would like to continue improving the repo by adding more classical neuroscience experiments. any suggestion ?

9/28/2017 9:32 AM

 **rohit** :

 >Awesome work hubertjb

9/28/2017 9:35 AM

 **alexandre.barachant** :

 ><https://en.wikipedia.org/wiki/P600_(neuroscience)>

9/28/2017 9:35 AM

 **alexandre.barachant** :

 >we could try this one

9/28/2017 9:40 AM

 **alexandre.barachant** :

 >also, did anyone tried motor imagery with a muse ?

9/28/2017 10:31 AM

 **alexandre.barachant** :

 ><https://github.com/skjerns/AutoSleepScorer>

9/28/2017 10:46 AM

 **danielao** :

 >This is brilliant. Just got my 2016 Muse a couple of weeks ago and have been looking for stuff like this. The code still requires being on Python 2.7 correct?

9/28/2017 10:51 AM

 **alexandre.barachant** :

 >unfortunatly, yes :disappointed: we use psychopy to display stimulus, and they onlu support 2.7

9/28/2017 11:00 AM

 **alexandre.barachant** :

 >actually, the version 1.85 seems to add support for python 3

9/28/2017 11:03 AM

 **alexandre.barachant** :

 >but its not released yet

9/28/2017 11:18 AM

 **danielao** :

 >Thanks for the reply. I guess I'll at least look for the dongle described to start and keep a look out for that update. Related question, but what is the efficacy on using Muse for ERPs or visual data? I'm slightly skeptical but I haven't dealt with commercial EEG data that extensively.

9/28/2017 11:21 AM

 **alexandre.barachant** :

 >it works, the signal with muse is good. The issue is more about the electrode positions. you can pick signal from the visual cortex because it diffuse on the scalp, but it's wont be as good as if you had electrodes positioned over the visual cortex.

> 
muse has an auxiliary channel where you can add another electrode. this way you can place one in Oz and get very good ERP

9/28/2017 11:24 AM

 **alexandre.barachant** :

 >this is what hubert did here : <https://github.com/alexandrebarachant/muse-lsl/blob/master/notebooks/SSVEP%20with%20Muse.ipynb> 

> 
he added an electrode on POz

9/28/2017 1:06 PM

 **hubertjb** :

 >thanks to benbrain, who initially developed and tested all these paradigms for the Muse at Interaxon!

9/28/2017 3:07 PM

 **danielao** :

 >Thanks for responding to my messages. This has actually been really helpful in understanding this side of the field. Yeah the positioning was more why I was wondering how Muse would pick up signal that originates from the other side of the head effectively. That makes a lot more sense and I'll definitely want to try that. 

> 
Honestly, it seems like that should be a product in itself, Muse with a couple more centrally located electrodes but at least they've been clear that with a bit of tinkering you can do it yourself. hubertjb any suggestions on adding this extra electrode (i.e. what you used, option of dry electrode, option of multiple)?

9/28/2017 4:08 PM

 **dano** :

 >What's the word on XDF vs EDF+ EEG file formats? After some searching I haven't been able figure out how much they differ, which one is advisable to use, and whether you can record from LSL to EDF+ or convert from XDF to EDF+

9/28/2017 4:25 PM

 **hubertjb** :

 >danielao there's a forum post about auxiliary electrodes for Muse here: <http://forum.choosemuse.com/t/auxilliary-electrodes/839/3> For the SSVEP experiment I used a dry hairpin electrode. As for multiple electrodes, you can connect only one aux electrode on Muse 2016 (up to 2 with Muse 2014).

9/28/2017 4:48 PM

 **danielao** :

 >Hi hubertjb. Thanks for replying. I did see that thread but it didn't really come to a conclusion (especially for newbies to homemade electrodes like myself). It was still unclear whether I could actually buy a dry electrode that connects to micro-USB. Enigma44 had the clearest answer so I'll look into that and your suggestion of a dry hairpin electrode.

9/28/2017 5:02 PM

 **mesca** :

 >Ive been experimenting with LSTM for cross-subject ERP classification: <https://github.com/mesca/turnkey-bci>

9/28/2017 5:18 PM

 **dano** :

 >Can you give a quick blurb about why LSTM might be helpful for that? IMU it's helpful for introducing temporal info (e.g. video) into classification

9/28/2017 5:26 PM

 **mesca** :

 >Well, ERPs are temporal data by nature :wink: There are many ways to use LSTM networks, here I use one to solve a sequence classification problem.

9/28/2017 5:32 PM

 **bciguy** :

 >alexandre.barachant interesting do you know the author? Aurora already has this functionality embedded onboard the device, with an open SDK and API endpoints

9/28/2017 5:48 PM

 **alexandre.barachant** :

 >no, i just came across this. no idea if it works well

9/29/2017 8:50 AM

 **jmhorschig** :

 >maybe a bit late of a reply, but most important is not the change in spectral power but the effect on behaviour, see my thoughts on <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4072086/>

9/29/2017 12:59 PM

 **dano** :

 >Amazing blog post about denoising audio with RNNs. Wonder if it would work with EEG

9/29/2017 12:59 PM

 **dano** :

 ><https://people.xiph.org/~jm/demo/rnnoise/>

9/29/2017 1:04 PM

 **alexandre.barachant** :

 >dano it could works, the problem is to get the data. Here it's artificially generated data (because you need labeled data i.e the same data clean and with added noise). the problem with EEG is that noise is hard to define

9/29/2017 1:07 PM

 **alexandre.barachant** :

 >it could works for ERP, because you know how the signal looks like (i.e. it is the average ERP), so you might actually be able have an estimation of the clean signal and the signal + noise

9/29/2017 1:08 PM

 **dano** :

 >I was just thinking that! Domain specific definitions of noise and signal might help

9/29/2017 9:46 PM

 **psoulos** :

 >Would it be possible to collect data from both ecog and eeg simultaneously and use that to train the neural network? EEG would be considered the noisy data, and ecog would be the "clean" data

9/29/2017 9:48 PM

 **alexandre.barachant** :

 >this is an interesting idea. Some kind of supervised source separation ... 

> 
IMO the results will be very subject specific

9/29/2017 11:50 PM

 **psoulos** :

 >and device specific too

9/30/2017 3:54 AM

 **joeyo** :

 >Reminds me of the "super-resolution" image enhancement demonstrations that have been achieved with nnets lately

9/30/2017 3:50 PM

 **alexandre.barachant** :

 >i've improved the LSL-viewer in muse-lsl. it is now using vispy

9/30/2017 3:50 PM

 **alexandre.barachant** :

 ><https://youtu.be/i1g55fKKcBU>

10/2/2017 12:15 AM

 **harris** :

 >As a computer science major, I haven't learned much yet about signal processing, and I was wondering what you all would recommend to learn it

10/2/2017 9:12 AM

 **okbalefthanded** :

 >The NeuroTechX awesome-BCI holds a section for Signal processing material: 

> 
<https://github.com/NeuroTechX/awesome-bci> 

> 
for a gentle introduction you start with the Mike X Cohen lecturelets

10/6/2017 4:45 PM

 **dano** :

 >This looks like an interesting one 

> 
<http://ieeexplore.ieee.org/abstract/document/6824740/?reload=true>

10/6/2017 6:58 PM

 **aj** :

 >Hi anyone know if there is high frequency eeg bio marker for motor movement or imagined motor movement? Looking for +60Hx

10/6/2017 6:59 PM

 **aj** :

 >I know we normally do 7-30Hz

10/6/2017 7:27 PM

 **pat** :

 >I'm not sure the best channel for this, but here seems close enough: I've been working on a few projects visualizing Muse EEG data on Android devices, so ended up splitting of a reusable library of data and visualization tools that make the whole process eaiser. If anyone's doing likewise and is interested, the code (library + sample app) are all available at: <https://github.com/padster/Muse-EEG-Toolkit>

10/6/2017 10:43 PM

 **dano** :

 >Good lord. Let's collaborate. Have you seen EEG 101? <https://github.com/neurotechx/eeg-101>

10/6/2017 10:48 PM

 **dano** :

 >I've implemented a whole bunch of the same stuff in Java for EEG 101. Not using Data Binding, though. Haven't actually come across that before

10/6/2017 10:51 PM

 **dano** :

 >The next thing I, and other collaborators like hubertjb and psoulos, will be working on is implementing ERPs in the app. We would definitely love to talk about that, as it seems your MergedSeries is similar to the kind of thing we might be trying to implement

10/6/2017 10:56 PM

 **dano** :

 >I've also been thinking of refactoring our EEG 101 code to be more remixable. For example, our EEG graph right now is just an Android view that does everything (receiving data, filtering, plotting) inside itself.

10/7/2017 7:31 PM

 **pat** :

 >dano nice - React makes sense, especially for multi-platform stuff. The Android data binding stuff is their fairly good attempt at an inbuilt equivalent, I find it a good way to quickly get live rendering working although might look at switching to React Native if that's what everyone is using and combining the two is hard work.

10/7/2017 7:35 PM

 **pat** :

 >MergedSeries I used for processing multiple frequency time series at the same time. For ERP you'll want something more like the Epoch collector that I just added; although I'll probably be changing the API a bit, currently you take the snapshot at the end of what you want (i.e. after the event), whereas probably it's better to make the call at the actual time of the event, and customize before + after delay.

10/11/2017 2:06 AM

 **educubecanada** :

 >Graeme Kilshaw performs EEG Experiment with 22bit visual binary code and EEG hookups:   <https://youtu.be/LtNwZ76Z8SE>

10/12/2017 3:06 PM

 **dano** :

 >Anyone have thoughts on this? Smooshing EEG data into colored images so that CNNs can be trained to detect seizures -- seems to work at least as well as the state-of-the-art.

> 
<https://arxiv.org/abs/1608.00220>

10/12/2017 4:28 PM

 **mrkrause** :

 >The time-frequency decomposition part makes perfect sense (were people not doing this already?) but actually making it into a jpeg or whatever seems a little silly

10/12/2017 4:31 PM

 **mrkrause** :

 >Also the interpretation of the convolutions in the t-f plane is potentially interesting: it suggests that abrupt changes in power are more predictive than the absolute amount of power, which seems pretty sensible to me.

10/12/2017 4:36 PM

 **alexandre.barachant** :

 >time-frequency decomposition "rectify" the signal and therefore you loose some interesting spatial correlation between EEG. for this reason, people like to apply first an ICA or some supervised source separation before going to the TF space. There is a potential huge gain to apply DL directly on raw data, but by converting them to image it's easier to leverage existing architecture

10/12/2017 4:55 PM

 **mrkrause** :

 >Sure. On the other hand, the color representation is a little weird because it makes it harder to extract absolute magnitudes. I'd think switching to greyscale would be an easy win.

10/12/2017 4:59 PM

 **alexandre.barachant** :

 >my experience in Seizure detection is that absolute value is rarelly interesting, and it's more the ratio between frequency that is interesting. It has also the advantage of normalizing the power of EEG, wich makes it less sensible to variation across time (eeg in seizure can be recorded over the course of several weeks)

10/12/2017 6:37 PM

 **mrkrause** :

 >alexandre.barachant, make sense, but I'd think that ratios would be more obvious with scalars than when going color -&gt; value. Still, it's neat that it works at all!

10/12/2017 7:11 PM

 **alexandre.barachant** :

 >Yes. You are right. It Makes more sense to use a scalar

10/13/2017 12:06 AM

 **pat** :

 >It seems a popular approach, at least with ML people who have a lot of tools / knowledge in image classification and much less in timeseries classification

10/13/2017 12:10 AM

 **pat** :

 >IIUC, they're interpreting it as color purely because they are using 3 frequency bands; to the CNN running, it's just a 3x16x16 tensor

10/13/2017 12:19 AM

 **pat** :

 >this is the first time I've seen EEG-&gt;image done via spatial map, rather than spectrogram, which seems neat. 

> 
I wonder why they didn't keep it 3D though, and end up with 3x16x16x16 or whatever

10/15/2017 6:57 PM

 **jorge.alemangonzalez** :

 >Hi all ! Here Jorge , i just join the comunity. I'm looking for EEG data with 6 labels or more about imagination. Not only motor imagery , but all kinds of imagination. Thanks !

10/17/2017 12:02 PM

 **samuelbg13** :

 >Hey guys. I am intrigued about the Riemannian Geometry approach to motor imagery classification. I have read it works well with not-to-many channels... but do you think it works well with a low-channel setup (around 6-8), for example with an OpenBCI?

10/17/2017 6:18 PM

 **fred-simard** :

 >I used py-Riemman on a low-count channel (4), on a different paradigm and it worked very well. If anything, it will probably score higher than most of the algorithms out there. Ask alexandre.barachant I'm sure he tried it.

10/17/2017 6:55 PM

 **alexandre.barachant** :

 >samuelbg13: yes, it works perfectly fine with low channel count

10/17/2017 7:35 PM

 **samuelbg13** :

 >Thanks guys :+1: fred-simard, alexandre.barachant. I will try it out.

10/17/2017 7:36 PM

 **elsehow** :

 >alexandre.barachant any idea how the pyRiemann method works on single-channel data?

10/17/2017 8:11 PM

 **alexandre.barachant** :

 >elsehow the principle is to exploit covariance between channels, so you need multiple channel.

10/17/2017 8:11 PM

 **elsehow** :

 >I see.

10/17/2017 8:11 PM

 **alexandre.barachant** :

 >if you have single channel data, you can transform it into multichannel data by aggrating time-delayed version of the signal.

10/17/2017 8:12 PM

 **elsehow** :

 >ah to exploit autocorrelations?

10/17/2017 8:12 PM

 **elsehow** :

 >thats a cool idea

10/17/2017 8:12 PM

 **alexandre.barachant** :

 >this way you can exploit auto-correlation

10/17/2017 8:12 PM

 **elsehow** :

 >but how do we know how long to delay it for?

10/17/2017 8:12 PM

 **alexandre.barachant** :

 >you don't, you have to find out

10/17/2017 8:12 PM

 **elsehow** :

 >:wink: another hyperparameter

10/17/2017 8:12 PM

 **elsehow** :

 >pinging psoulos

10/17/2017 8:13 PM

 **alexandre.barachant** :

 >BTW, its also used in the algorithm CSSP

10/17/2017 8:13 PM

 **alexandre.barachant** :

 >(<https://pdfs.semanticscholar.org/6831/ae1024cdbb86a728dc865dc9b6d0a94a41fd.pdf>)

10/17/2017 8:14 PM

 **alexandre.barachant** :

 >in pyriemann, you can use the class `HankelCovariance`

10/17/2017 8:14 PM

 **elsehow** :

 >awesome, thanks

10/17/2017 8:14 PM

 **elsehow** :

 >btw, I spent a few minutes today trying to get your `muse-lsl` package working with the lowdown focus. the BLE dongle I got didnt seem to be working with `pygatt`. since my macbook does seem to support BLE, ill see if i can find a python package thatll work sans-dongle. Ill keep you posted

10/17/2017 8:15 PM

 **alexandre.barachant** :

 >on mac, you can only use a BLED112 dongle with pygatt

10/17/2017 8:16 PM

 **alexandre.barachant** :

 >`muse-lsl` work with the lowdown focus

10/17/2017 8:16 PM

 **elsehow** :

 >so I thoguht my dongle was BLED112

10/17/2017 8:16 PM

 **elsehow** :

 >but it is a cheap china knockoff thing

10/17/2017 8:16 PM

 **elsehow** :

 >so im going to try with another

10/17/2017 8:17 PM

 **elsehow** :

 >however, unless im missing something, all one needs is bluetooth 4.0 hw. whats missing is `pygaff` support for this hw

10/17/2017 8:17 PM

 **elsehow** :

 >on the macbook

10/17/2017 8:17 PM

 **elsehow** :

 >is that correct? or am i missing something?

10/17/2017 8:17 PM

 **elsehow** :

 >btw, which dongle did you use, out of curiosity

10/17/2017 8:17 PM

 **alexandre.barachant** :

 >if it's a knockoff, it might not be detected by the auto-dectection of pygatt (different usb id), but you can give the serial port adress and it mlight works

10/17/2017 8:19 PM

 **elsehow** :

 >cool, i can find the serial port. will try

10/17/2017 8:20 PM

 **alexandre.barachant** :

 >As i understand, windows and mac does not provide an unified BLE stack for external software to use, and what does the BLED112 is to embedd the BLE stack on hardware and expose it through a serial port

10/17/2017 8:20 PM

 **alexandre.barachant** :

 >but it's more a pygatt issue.

10/17/2017 8:20 PM

 **elsehow** :

 >I got it

10/17/2017 8:21 PM

 **elsehow** :

 >Ill try specifying the port on a minimal example with pygatt next time im around my hw

10/17/2017 8:23 PM

 **elsehow** :

 >thanks for the consult

10/17/2017 8:24 PM

 **alexandre.barachant** :

 >with muse-lsl, you have and argument `--interface`

10/17/2017 8:24 PM

 **alexandre.barachant** :

 >so it should be something like 'python muse-lsl --interface /dev/ttyACM0 --address YOUR_MAC_ADRESS`

10/17/2017 8:26 PM

 **elsehow** :

 >thanks, yeah, I just read the `muse-lsl.py` script

10/17/2017 8:26 PM

 **elsehow** :

 >this project is really nicely organized

10/17/2017 8:27 PM

 **elsehow** :

 >good docstrings

10/17/2017 10:18 PM

 **yrenard** :

 >alexandre.barachant wouldn't time-delayed channel highly share variance with original channel ? that looks to me like a very ill conditionned covariance matrix until you have delay that is significant with regard to the epoch size you extract the cov matrix on

10/18/2017 12:35 AM

 **fred-simard** :

 >yrenard not necessarily, think of the covariance between a white noise signal and it's delayed version. Now the pertinence of computing the covariance between a signal and it's delayed version depends on what you what you are looking into, in terms of physiological phenomenon or else. It's analogous to auto-correlation.

10/18/2017 12:57 AM

 **elsehow** :

 >fred-simard so there should be no autocorrelation in the white noise signal right

10/18/2017 12:57 AM

 **elsehow** :

 >meanwhile we expect autocorrelation in the eeg signal

10/18/2017 12:57 AM

 **elsehow** :

 >the question for me is why this helps pyreimann

10/18/2017 1:03 AM

 **fred-simard** :

 >elsehow My argument is to show that depending on the nature of the signal you can have a lot of covariance between a signal and it's delayed version or not a all. For it means, it depends on what is studied.

> 


> 
What alexandre.barachant suggested is that if you want to use pyRiemann with only one channel, one way to go about it is to use the signal and one or more delayed version. This will allow you to build the covariance matrix, which can then be mapped into the Reimannian space onto the consequent manifold and processed using LDA. Will it perform well/better than other algorithms under such circumstances? this is up to you to find out, but mechanistically, that's a way to make it work.

10/18/2017 1:04 AM

 **elsehow** :

 >i see, so the question is really whether there is relevant info (wrt the classification/regression problem) in the autocorrelation

10/18/2017 1:05 AM

 **fred-simard** :

 >I said autocorrelation to help understand the process, but otherwise, yes, this is it.

10/18/2017 1:05 AM

 **elsehow** :

 >i see

10/18/2017 1:06 AM

 **fred-simard** :

 >no problem :wink:

10/18/2017 8:58 AM

 **alexandre.barachant** :

 >yrenard yest, two delayed version have the same variance, so the diagonal of this covariance is just the same value. the off diagonal is carrying the auto-correlation. You also want to be smart when you space your delay, if you do [0, 2, 4] sample, then you have 3 channels, but there is the same delays between ch1 and ch2 as between ch2 and ch3. if you use [0,1,3] you have 3 channels and 4 different delays

10/18/2017 8:59 AM

 **alexandre.barachant** :

 >I used the autocorrelation matrices in the seizure 2016 kaggle challenge. it wasn't a very good feature, but it made it into the ensemble : <https://github.com/alexandrebarachant/kaggle-seizure-prediction-challenge-2016>

10/18/2017 4:11 PM

 **yrenard** :

 >got it, so chosing the delays wisely avoids lower ranked covariance matrices, sounds interesting - have you tried that with multiple channels as well ?

10/18/2017 4:17 PM

 **alexandre.barachant** :

 >yep, it's the base for the CSSP algorithm

10/18/2017 4:19 PM

 **alexandre.barachant** :

 >i've used multichannel time delayed covariance (i call that Hankel Covariance ) in at least 2 challenge

10/18/2017 4:51 PM

 **yrenard** :

 >nice !

10/18/2017 7:40 PM

 **elsehow** :

 >alexandre.barachant how did you find the MAC address for your lowdown focus?

10/24/2017 1:22 AM

 **soroosh** :

 >Hello everyone,

> 
Can anyone introduce me some motor imagery datasets which contain more than two classes of tasks?

> 
I have already worked with the datasets from BCI competition, but I am looking to investigate other datasets, also.

10/24/2017 1:22 AM

 **yannick** :

 >Have you checked on the NTX awesome BCI list for other datasets?

10/24/2017 1:58 AM

 **soroosh** :

 >Unfortunately no. 

> 
Would you please provide more information?

10/24/2017 2:15 AM

 **jnaulty** :

 >soroosh 

> 
here you go: <https://github.com/NeuroTechX/awesome-bci>

10/24/2017 2:17 AM

 **soroosh** :

 >This is absolutely awesome. 

> 
Thank you very much jnaulty yannick

10/24/2017 2:18 AM

 **aj** :

 >They wouldnt call it awesome if it wasnt!!

10/24/2017 2:24 AM

 **jnaulty** :

 >:stuck_out_tongue:

10/25/2017 1:41 PM

 **aj** :

 >Hey all Im trying to make a circuit for marking eeg data when I flash a stimulus on screen, I want to put the diode on a little square and send a 1 when white and 0 when black to an arduino. Does any one have advice? (copied from <#C08T2SENQ|devices> because this channel is 10x bigger)

10/25/2017 1:52 PM

 **alexandre.barachant** :

 >you can use a photodiode, and a OPAmp used as a comparator. on one side you have the photodiode and on the other you can use a potentiometer to set the threshold of the comparatir

10/25/2017 1:52 PM

 **alexandre.barachant** :

 >you can google photodiode + comparator and you will fine plenty of example

10/25/2017 4:37 PM

 **aj** :

 >thanks Alex!

10/26/2017 2:20 PM

 **agustnr64** :

 >Hi everyone,

> 
I am trying to build a hand orthosis controlled by a non-invasive BCI for patients with hemiplegia for a student project. I have just started with the signal processing and feature extraction. Although I have read some papers, it is not quite clear to me what kind of features do I need extract. Is there someone who knows what kind of method could I have to perform?

10/26/2017 2:21 PM

 **agustnr64** :

 >Hi everyone,

> 
I am trying to build a hand orthosis controlled by a non-invasive BCI for patients with hemiplegia for a student project. I have just started with the signal processing and feature extraction. Although I have read some papers, it is not quite clear to me what kind of features do I need extract. Is here someone who knows what kind of method could I have to perform?

> 
Thank you so much for your time!

10/26/2017 5:57 PM

 **nicolas** :

 >aj Maybe this blog post will be useful to you (uses audio triggers, but the idea is the same):

> 
<https://bakerdh.wordpress.com/2013/10/22/arduino-sound-to-ttl-trigger-for-eeg/>

> 


> 
We used to have a very similar setup in our lab (photodiode and audio)

> 


> 
FWIW I don't use this anymore though as I've purchased a Labjack to send triggers (<https://labjack.com/products/u3>), which is a bit more flexible to send variable trigger values from code (matlab/python) and performs very well latency-wise (&lt;1ms latency)

10/26/2017 6:16 PM

 **andyh616** :

 >aj i wrote up a post a couple years ago to do this an openbci board - <http://openbci.com/community/measuring-stimulus-timing-with-a-photoresistor/>

10/26/2017 9:09 PM

 **aj** :

 >Hey all thanks yall

10/27/2017 5:21 PM

 **alexandre.barachant** :

 >today we greatly improved the display on the angular-muse : <https://muse-eeg-app.firebaseapp.com/>

10/27/2017 5:21 PM

 **alexandre.barachant** :

 >so now you can just go to this URL and get your EEG stream in a minute

10/27/2017 5:22 PM

 **alexandre.barachant** :

 >it even works on android out of the box

10/27/2017 5:22 PM

 **alexandre.barachant** :

 >thanks urish :slightly_smiling_face:

10/27/2017 5:40 PM

 **andyh616** :

 >awesome

10/27/2017 6:09 PM

 **graeme** :

 >This is awesome work, guys!

10/27/2017 6:14 PM

 **graeme** :

 >Holy cow this is an awesome app

10/27/2017 6:45 PM

 **alexandre.barachant** :

 >graeme yep. I had the same reaction :grinning:

10/27/2017 7:25 PM

 **yannick** :

 >Do I need something specific to make it work? (aside from a Muse :p)

> 
I tried on both my MacBook and Android Phone. Both devices can see and pair with the Muse from Bluetooth settings, but on both devices the app get stuck in the pairing dialogue never finding the Muse& (its a Muse 2014)

10/27/2017 7:31 PM

 **alexandre.barachant** :

 >yannick muse 2016 only

10/27/2017 7:33 PM

 **yannick** :

 >I used to be cool. Now Im deprecated& I need to update my toys. :confused:

10/27/2017 7:34 PM

 **alexandre.barachant** :

 >You had a muse before it was cool :grinning:

10/27/2017 7:39 PM

 **alexandre.barachant** :

 >Muse 2014 is Bluetooth. Muse 2016 is BLE. Having support for both of them require a different set of tools...

10/27/2017 8:08 PM

 **bciguy** :

 >& and BLE is not great for real-time EEG communication

10/27/2017 9:30 PM

 **graeme** :

 >Seems to work with the Smith Lowdown glasses too

10/27/2017 9:48 PM

 **alexandre.barachant** :

 >Backward compatibility :sunglasses:

10/30/2017 9:13 PM

 **pat** :

 >alexandre.barachant is the code for that available somewhere?

10/31/2017 9:18 AM

 **alexandre.barachant** :

 >pat: <https://github.com/NeuroJS/angular-muse>

10/31/2017 5:39 PM

 **gautamkumar** :

 >adastra

10/31/2017 9:53 PM

 **graeme** :

 >The eternal tradeoff - data rate, channels, battery life, wireless bandwidth...

10/31/2017 10:11 PM

 **alexandre.barachant** :

 >bciguy can you explain more in detail ? with the push / subscribes, it seems adapted to me.

10/31/2017 10:12 PM

 **sydneyneurotechx** :

 >Has anyone looked into memory consolidation and Theta training? Seems like an interesting use case of neurofeedback. <http://www.sciencedirect.com/science/article/pii/S0301051113002214>

10/31/2017 10:18 PM

 **bciguy** :

 >alexandre.barachant yes we use BLE on Aurora. It is ideal for in/frequent *status updates*, like location, state, etc. but not ideal for raw-data throughput.

10/31/2017 10:20 PM

 **bciguy** :

 >alexandre.barachant google the average bandwidth for the BLE protocol, it is much lower than the older Bluetooth 2.0 protocol. There are however some new BT technologies on the horizon ..

10/31/2017 10:21 PM

 **alexandre.barachant** :

 >yep, i see what you mean. it's not made for data streaming. saying that, for a low channel count, the choice looks okay to me.

10/31/2017 10:23 PM

 **alexandre.barachant** :

 >and Bluetooth 5 should be good enough for headset with decent channel count

10/31/2017 10:33 PM

 **bciguy** :

 >how many channels? Even for one channel it cuts it close

10/31/2017 10:35 PM

 **alexandre.barachant** :

 >muse seems fine with 5 channels (12 bits/sample) @ 256Hz. Ganglion goes 4 channels @ 200Hz, but its 24 bits so it's way harder

11/2/2017 10:45 AM

 **agustnr64** :

 >Hi! everyone

> 
is there anyone who knows where can I find EEG recordings from Patients who suffered a stroke.

> 
Thank for you time

11/2/2017 11:35 AM

 **alexandre.barachant** :

 >did anyone tryed this : <https://brainbase.io> looks interesting

11/2/2017 1:54 PM

 **fred-simard** :

 >yannick online database

11/2/2017 2:24 PM

 **mesca** :

 >Ive been on the waiting list for two months...

11/2/2017 3:13 PM

 **graeme** :

 ><https://makingscience.withgoogle.com/science-journal?lang=en>

11/2/2017 3:13 PM

 **graeme** :

 >Has anybody played around with Google Science Journal? We've been using it at Interaxon to collect environmental sensor data alongside EEG, and it's one of my favourite apps.

11/2/2017 3:14 PM

 **graeme** :

 >They have an external sensor API that it may be possible to plug Muse or other EEG systems into: <https://github.com/google/science-journal/blob/master/api/ScienceJournalApi/README-api.md>

11/2/2017 3:36 PM

 **dano** :

 >Putting myself on the email address. Good to hear something from Sapien Labs. This could be really cool.

11/2/2017 3:59 PM

 **yannick** :

 >tara ^ would you mind giving us an update on Sapien Labs database? :slightly_smiling_face:

11/2/2017 6:28 PM

 **yannick** :

 >Hey alexandre.barachant is the muse app supposed to work on iPhone ?

11/2/2017 6:29 PM

 **alexandre.barachant** :

 >no idea. urish is the original author, i just contributed to improve the EEG viz

11/2/2017 6:30 PM

 **alexandre.barachant** :

 >works on android for sure, but i dont know anyone with an iphone

11/2/2017 6:30 PM

 **urish** :

 >It uses Web Bluetooth, which is not available for iOS yet

11/2/2017 6:30 PM

 **urish** :

 >However! There's a polyfill available

11/2/2017 6:30 PM

 **alexandre.barachant** :

 >chrome only right ? i never tried on firefox

11/2/2017 6:31 PM

 **bhargava2566302** :

 >but webluetooth depends on browser not on OS

11/2/2017 6:31 PM

 **bhargava2566302** :

 >it might not work in safari

11/2/2017 6:32 PM

 **urish** :

 >Chrome, Opera, Samsung Internet and Mozilla Servo all support Web Bluetooth

11/2/2017 6:33 PM

 **urish** :

 >Apple however does not allow browsers to add new Web APIs, so no browsers have it on iOS

11/2/2017 6:33 PM

 **urish** :

 >There is this polyfill however;

11/2/2017 6:33 PM

 **urish** :

 ><https://itunes.apple.com/us/app/webble/id1193531073>

11/2/2017 6:34 PM

 **alexandre.barachant** :

 >do you know if it will becomes a standard in the future ?

11/2/2017 6:34 PM

 **urish** :

 >I haven't tested it with the Muse though, so I can't comment whether it works

11/2/2017 6:36 PM

 **urish** :

 >I believe it will, I know several people who work hard to make sure it will. I hope that by the end of 2018 it'll be supported by Edge (there's a polyfill as well) and Firefox

11/2/2017 7:57 PM

 **yannick** :

 >The app worked like a charm on Android for the Smith Lowdown Focus (Muse) Glasses.

> 
I took the glasses in my hand for the first time, and 3 clicks later I had my EEG signal. Impressive. 

> 
(1 click on the link. 1 click on connect. 1 click to select the [only] device)

11/2/2017 7:58 PM

 **yannick** :

 >Congratz urish &amp; alexandre.barachant.

11/2/2017 8:03 PM

 **yannick** :

 >I dont have a Muse 2016 to test, but on the glasses the head movement is:

> 
yaw: not working :disappointed:  (cant turn my head left/right)

> 
pitch: reverse (when I go up it goes down.

> 
roll: mirror (when I look at the face its going in opposite direction, but the right one)

11/2/2017 9:25 PM

 **aj** :

 >i just got the ganglion working with web bluetooth in the browser

11/2/2017 9:26 PM

 **aj** :

 >yesss

11/2/2017 9:26 PM

 **aj** :

 >web bluetooth!

11/2/2017 9:26 PM

 **aj** :

 >i had to overhaul the nodejs driver to work in the browser too

11/2/2017 9:26 PM

 **aj** :

 >yesss

11/2/2017 10:14 PM

 **urish** :

 >awesome AJ!

11/2/2017 10:15 PM

 **urish** :

 >Yes, yaw doesn't work because the current code only uses the accelerometer for estimating head position:

11/2/2017 10:16 PM

 **urish** :

 ><https://github.com/urish/angular-muse/blob/master/src/app/head-view/head-view.component.ts#L63>

11/2/2017 10:17 PM

 **urish** :

 >feel free to send a pull request with improvements to that

11/2/2017 10:53 PM

 **yannick** :

 >For those trying the app in your browser, *dont forget to enable the Experimental Web Features flag*. :slightly_smiling_face: And it should work like a charm.

> 
I tested: Smith Lowdown Focus (aka Muse Glasses) via muse-eeg-app on MacOS Sierra + Chrome (62.0.3202.75). You can see on the screen Eye Blinks &amp; Eye Movements Left/Right.

11/3/2017 6:29 PM

 **tara** :

 >We're getting close - for anyone who has signed up on brainbase we will be sending out invitations soon - don't want to put an exact date on it in case we find some new bugs but I hope we will be ready by the end of next week.

11/3/2017 6:57 PM

 **tara** :

 >For those who signed up a while ago - thanks for your patience!

11/4/2017 1:55 AM

 **hassan** :

 >What is the range that based on it you would consider if a spike in the neural data is usual or not. Also, if you found such a spike, would you exclude the whole channel or would you try  to "cut off" this piece of spike?

11/4/2017 1:49 PM

 **andyh616** :

 >By spike do you mean an artifact i.e. Noise in the data, or spike as in a neuron spike. Assuming you mean the former, there is no real "standard" for artifact rejection, but you could use something like a change in activity from one moment to the next that exceeds some threshold like 3 standard deviations from the mean. You can likely salvage the channel assuming it's not flooded w artifact

11/5/2017 11:38 PM

 **pierre** :

 >Seems like there's a couple papers on EOG, ECG, and line noise artifact removal from EEG data using similar techniques, but I'm most interested in filtering out movement artifacts

11/6/2017 9:45 PM

 **elsehow** :

 >yannick thank you for the tip on getting lowdown working with the muse app!! one thing: the head orientation appears to be flipped on the vertical access (when i tilt my head down, the avatar is tilted up).

11/7/2017 4:53 PM

 **hectordomorozco** :

 >Friends, have you checked out the ieee hackathon in Boston?

11/8/2017 6:26 PM

 **psoulos** :

 >In the following research, they take the same photo with a DSLR and a few camera phones. Then they use machine learning to map from the phone's lower quality image to the DSLR's high quality image. Is there any literature on a similar technique with EEG and ECog. Collect eeg and ecog data and create a mapping from eeg signal to ecog signal. alexandre.barachant elsehow 

> 


> 
<http://people.ee.ethz.ch/~ihnatova/>

11/8/2017 8:06 PM

 **andyh616** :

 >psoulos we are doing something similar to this with ECog to fMRI levels of resolution - check it out here:<https://www.biorxiv.org/content/early/2017/03/27/121020>

11/8/2017 8:07 PM

 **andyh616** :

 >its based on gaussian process regression, but could be extended to use deep learning methods

11/8/2017 8:13 PM

 **psoulos** :

 >Thanks for sharing this!

11/8/2017 10:33 PM

 **andyh616** :

 >one problem i see with mapping between EEG/iEEG that there is not a lot of training data (i.e. simultaneous EEG/iEEG) to train any sort of model, and whatever model is produced would probably be dependent on the task.  another issue that would make this not feasible is that there are likely many brain states that contribute to the same EEG topography, so there's a degrees of freedom mismatch there

11/8/2017 10:38 PM

 **alexandre.barachant** :

 >The main issues of these methods is that they are just "filling the blanks" and are not actually increasing the information content of your image. If you apply that to EEG to map to EEG, you will not gain the spectral resolution of the Ecog, and you merely will get similar resultat to what you can get with source separation

11/8/2017 10:40 PM

 **andyh616** :

 >:thumbsup: right, definitely agree

11/8/2017 10:47 PM

 **alexandre.barachant** :

 >or saying it differently, what you get with the DSLR is not an image with intrinsically DSLR quality, but something that is has the same property of a DSLR picture. It is the same for the GAN that improve resolution in image. you interpolate nicely and smartly so that the higher res image does not look pixelated, but you dont actually see what "between" pixels of the original image

11/8/2017 10:48 PM

 **psoulos** :

 >well you're inferring what's in between probabilistically

11/8/2017 10:48 PM

 **psoulos** :

 >so there's a chance that it's wrong, but with the right training data it can approach the ground truth

11/8/2017 10:49 PM

 **psoulos** :

 >I agree that the model would be dependent on the task/individual subject/specific recording devices

11/8/2017 10:50 PM

 **alexandre.barachant** :

 >you mean like this ? <https://www.youtube.com/watch?v=I_8ZH1Ggjk0>

11/8/2017 10:51 PM

 **elsehow** :

 >alexandre.barachant lol ^

11/8/2017 10:51 PM

 **elsehow** :

 >yes, like waifu2x

11/8/2017 10:51 PM

 **elsehow** :

 >it effectively uses a corpus to guess whats beteween the pixels

11/8/2017 10:51 PM

 **elsehow** :

 >using these imagined pixels for analysis (like blowing up a license plate) is as silly as what that paper seems to be proposing, no?

11/8/2017 10:53 PM

 **psoulos** :

 >well in the space of ecog readings, a lot may be improbable

11/8/2017 10:53 PM

 **psoulos** :

 >so the eeg-&gt;ecog would learn to map from eeg to more likely ecog states

11/8/2017 10:54 PM

 **elsehow** :

 >sure, but its just inheriting any incidental correlations in the original corpus

11/8/2017 10:55 PM

 **psoulos** :

 >why do you say incidental?

11/8/2017 10:55 PM

 **elsehow** :

 >because the correlations that the learner learns between EEG and ECOG may be spurious

11/8/2017 10:55 PM

 **elsehow** :

 >we have no way of knowing that ther eis some pure function mapping EEG to ECOG

11/8/2017 10:56 PM

 **alexandre.barachant** :

 >it's actually the same idea as source reconstruction used intensively in MEG and EEG.

> 
what you get is that you split the signal in smaller pieces and its can be easier to interpret. but you don't actually improve the information content of the original signal

11/8/2017 10:56 PM

 **elsehow** :

 >i think thats the larger concern

11/8/2017 10:56 PM

 **elsehow** :

 >the claim is that the output signal is of arbitrary resolution

11/8/2017 10:56 PM

 **elsehow** :

 >sure

11/8/2017 11:03 PM

 **andyh616** :

 >doesn't give a mapping between iEEG and EEG, but it could potentially help to do better source estimation with fewer electrodes

11/8/2017 11:05 PM

 **alexandre.barachant** :

 >no, you don't add any new information in your dataset, you just leak information from other subject into one subject. the information content of the whole dataset remain the same

11/8/2017 11:06 PM

 **andyh616** :

 >right, that's why i said new information at the subject level

11/8/2017 11:06 PM

 **andyh616** :

 >not in the dataset

11/8/2017 11:07 PM

 **alexandre.barachant** :

 >yes, but i mean what you get is not the data you would have recorded if you had an electrode at this position in the brain for this particular subject.

> 
still, it's a cool idea :slightly_smiling_face:

11/8/2017 11:09 PM

 **andyh616** :

 >sure, but its a potentially good guess!

11/8/2017 11:09 PM

 **alexandre.barachant** :

 >but this is made clear in the discussion

11/8/2017 11:09 PM

 **andyh616** :

 >yea

11/8/2017 11:09 PM

 **alexandre.barachant** :

 >&gt; Taken to the logical extreme, we could not hope to accurately recover activity patterns from brain areas where no recordings existed from any patient.

11/8/2017 11:11 PM

 **andyh616** :

 >i think that is referring to a scenario where electrode N is missing from all subjects

11/8/2017 11:11 PM

 **alexandre.barachant** :

 >yes, this is what i mean

11/8/2017 11:13 PM

 **andyh616** :

 >i'm on board with that, i guess the point im trying to make is that the full elec-by-elec covariance matrix in your dataset can be leveraged to infer activity in an individual subject, and this in turn could be leveraged to improve source reconstruction for that subject

11/8/2017 11:13 PM

 **alexandre.barachant** :

 >ho yep for sure, i'm on board too

11/8/2017 11:15 PM

 **psoulos** :

 >:upside_down_face: this conversation quickly went beyond me

11/8/2017 11:16 PM

 **andyh616** :

 >in any case, we are releasing a toolbox to do this soon!

11/8/2017 11:15 PM

 **andyh616** :

 >cool - i think we are in agreeement :slightly_smiling_face: :party_parrot:

11/8/2017 11:16 PM

 **psoulos** :

 >what is the consensus?

11/8/2017 11:16 PM

 **andyh616** :

 >with the low-res-&gt;high-res GAN, it is probably not possible to go EEG-&gt;iEEG

11/8/2017 11:17 PM

 **andyh616** :

 >right alexandre.barachant?

11/8/2017 11:20 PM

 **alexandre.barachant** :

 >or at least if you map it, you will just get something similar with source reconstruction

11/8/2017 11:21 PM

 **alexandre.barachant** :

 >andyh616 isn't your method mainly "estimating" the mixing model of the brain from the data ?

11/8/2017 11:23 PM

 **andyh616** :

 >mmm, i think you could say that. how every piece of brain talks to every other piece of brain..assuming linearity and stationarity (which we know is probably not quite right)

11/8/2017 11:24 PM

 **alexandre.barachant** :

 >okay, i'm reading the paper so i will stop making guess :slightly_smiling_face:

11/8/2017 11:24 PM

 **andyh616** :

 >but the trick is that each subject contributes a unique set of electrodes to the model

11/8/2017 11:29 PM

 **alexandre.barachant** :

 >okay, i read the method, and i better understand

11/8/2017 11:30 PM

 **alexandre.barachant** :

 >you use the average brain correlation matrix to infer signal in one position from an existing set of signal

11/8/2017 11:32 PM

 **andyh616** :

 >yep! eq 10 is the inference bit

11/8/2017 11:32 PM

 **andyh616** :

 >its basically gaussian process regression over space

11/8/2017 11:33 PM

 **alexandre.barachant** :

 >okay, so again there is no increase on information content of the signal.

11/8/2017 11:34 PM

 **andyh616** :

 >well, the correlation matrix is created from all subjects

11/8/2017 11:34 PM

 **andyh616** :

 >the inference is done per subject

11/8/2017 11:34 PM

 **alexandre.barachant** :

 >yes, but the corelation matrix is just used to estimates the weight of the projection from the current signal

11/8/2017 11:35 PM

 **andyh616** :

 >mm, yes that is true..

11/8/2017 11:35 PM

 **alexandre.barachant** :

 >let say you only have one electrode for a single subject, then the reconstruction at any position is just proportional to this single electrode

11/8/2017 11:36 PM

 **andyh616** :

 >yep, totally - i see where you are going :the_horns:

11/8/2017 11:38 PM

 **andyh616** :

 >so, each 'new' location is just a linear weighted combination of the subjects elctrodes, where the weights are derived from the full correlation matrix

11/8/2017 11:38 PM

 **alexandre.barachant** :

 >it's actually a very good idea. and i think we can use that to find common representation of EEG signal (for transfert between dataset, or interpolation, etc)

11/8/2017 11:38 PM

 **andyh616** :

 >hence, no 'new' information

11/8/2017 11:38 PM

 **alexandre.barachant** :

 >exactly

11/8/2017 11:40 PM

 **alexandre.barachant** :

 >so let say you build a classifier for P300 data, and you have a very nice classifier but all your data are from a single electrode montage.

> 
And the you get a new montage, so you are f**ck. your only solution is to get the minimal common denominator.

> 
with your method, you can estimate the weights that goes from one montage to another one, and then apply your old classifier on the new data

11/8/2017 11:41 PM

 **andyh616** :

 >ah! thats a neat idea!

11/8/2017 11:41 PM

 **alexandre.barachant** :

 >of course, it's assuming you roughly have the same coverage (at least on the part of the brain that matters)

11/8/2017 11:42 PM

 **alexandre.barachant** :

 >(BTW, you shoud use a log-euclidean metric for averaging your correlation matrix)

11/8/2017 11:42 PM

 **andyh616** :

 >is it just euclidean now?

11/8/2017 11:43 PM

 **andyh616** :

 >i think we average is z-world

11/8/2017 11:43 PM

 **alexandre.barachant** :

 >i mean this one :

11/8/2017 11:43 PM

 **alexandre.barachant** :

 >it's more robust than the euclidean mean

11/8/2017 11:43 PM

 **andyh616** :

 >ah roger that, i will pass it on :slightly_smiling_face:

11/8/2017 11:43 PM

 **alexandre.barachant** :

 >(but you might have trouble because you need SPD matrix, so you need regularisation)

11/8/2017 11:45 PM

 **andyh616** :

 >thanks for the ref, ill give lucy (first author) the link :slightly_smiling_face:

11/8/2017 11:47 PM

 **andyh616** :

 >i like this idea of using superEEG to transfer classifiers across datasets

11/8/2017 11:47 PM

 **andyh616** :

 >seems like it could be really promising

11/8/2017 11:47 PM

 **alexandre.barachant** :

 >you can build a webservice where you upload a EEG dataset, and select a new montage, and it will just generate the projection matrix

11/8/2017 11:48 PM

 **andyh616** :

 >could also build a huge database of EEG data in the same space, which could be very useful

11/8/2017 11:48 PM

 **alexandre.barachant** :

 >yes,

11/8/2017 11:51 PM

 **alexandre.barachant** :

 >i like this idea very much

11/8/2017 11:51 PM

 **alexandre.barachant** :

 >pinp me when the code is available

11/8/2017 11:52 PM

 **andyh616** :

 >will do, should be up soon after SFN (late Nov-ish)

11/9/2017 12:06 AM

 **alexandre.barachant** :

 >But i think the paper would deserve a more clear statement about what does this method. 

> 
it's a linear interpolation, and your predicted signal is just a linear combination of your electrode signal. 

> 
It should defenetly be linked to source reconstruction methods, and i'm even wondering if we can see it as a special case of beamforming

11/9/2017 12:08 AM

 **alexandre.barachant** :

 >some cool extension would be to actually do that in the FFT space, using cosprectrum matrices instead of correlation

11/9/2017 12:17 AM

 **andyh616** :

 >hmm, ill have to think more about it as 'a special case of beamforming'.  thanks for the feedback alexandre.barachant!

11/9/2017 12:17 AM

 **andyh616** :

 >agree about doing this in FFT space, its in the list

11/9/2017 12:25 AM

 **andyh616** :

 >some other comments:

11/9/2017 12:25 AM

 **andyh616** :

 >"But i think the paper would deserve a more clear statement about what does this method. 

> 
it's a linear interpolation, and your predicted signal is just a linear combination of your original signal. 

> 
It should defenetly be linked to source reconstruction methods, and i'm even wondering if we can see it as a special case of beamforming (edited)

> 
some cool extension would be to actually do that in the FFT space, using cosprectrum matrices instead of correlation"

11/9/2017 12:27 AM

 **andyh616** :

 >we also had a discussion about repurposing the algorithm as a tool to define a common space for EEG datasets with various numbers of electrodes, electrode placements etc

11/9/2017 1:39 PM

 **andyh616** :

 >hey alexandre.barachant, is the rationale for using log-euclidean mean that it is more robust to numerical rounding errors? or is there another reason?  Currently, we are computing correlation matrices, fisher's z scoring them and averaging, then inverting the fisher's transform to bring it back to correlation

11/9/2017 1:45 PM

 **alexandre.barachant** :

 >the rational for log-euclidean mean is that correlation matrices are SPD matrices (usually) so they belong to the manifold of SPD matrices. the proper way to average them is to use the log-euclidean metric (or even better, the riemannian metric, but it can be very computational)

11/9/2017 1:45 PM

 **andyh616** :

 >aaahh, i see

11/9/2017 1:46 PM

 **alexandre.barachant** :

 >for some application it actually improve a lot the performance. for some other it does not matter that much

11/9/2017 1:46 PM

 **alexandre.barachant** :

 >but in essence, the log-euclidean mean is more robust because the log will downplay the effect on artifacts

11/9/2017 1:47 PM

 **andyh616** :

 >interesting! i'll check it out to see if it improves our reconstruction accuracy.  also, i'll expose the distance function as an argument in the software so the user can use euclidean, log-euclidean, riemannian..

11/9/2017 1:48 PM

 **alexandre.barachant** :

 >well, i would say try first, no need to expose an extra parameter if it is not useful

11/9/2017 1:49 PM

 **andyh616** :

 >:thumbsup:

11/9/2017 1:50 PM

 **alexandre.barachant** :

 >i trend to think its not a good idea to add extra parameter just because we can :slightly_smiling_face:

11/9/2017 1:50 PM

 **andyh616** :

 >yup! i agree :slightly_smiling_face:

11/9/2017 1:50 PM

 **andyh616** :

 >thanks

11/13/2017 1:22 PM

 **rahman.shama** :

 >Hello! Is anyone here doing any ML on whole brain continuous EEG? (rather than ERP)

11/13/2017 1:39 PM

 **ruudkalis** :

 >There have been some competitions on Kaggle involving continuous EEG :

11/13/2017 1:40 PM

 **ruudkalis** :

 ><https://www.kaggle.com/c/seizure-prediction>

11/13/2017 1:41 PM

 **rahman.shama** :

 >Hey Ruud! Thanks! I was thinking more on scalp non-invasive EEG

11/13/2017 1:41 PM

 **ruudkalis** :

 >You can try to apply similar ML methods

11/13/2017 1:42 PM

 **ruudkalis** :

 >What exactly would you like to detect or predict?

11/13/2017 1:43 PM

 **alexandre.barachant** :

 >the nuclear option =&gt; <https://github.com/alexandrebarachant/Grasp-and-lift-EEG-challenge>

11/13/2017 1:46 PM

 **alexandre.barachant** :

 >there is a model for many type of feature (raw data, bandpower, covariance) and even some CNN and RNN

11/13/2017 3:05 PM

 **dano** :

 >Another <#C4LSDAE95|neurodoro>

11/13/2017 3:19 PM

 **alexandre.barachant** :

 >awesome. can you share the architecture ?

11/13/2017 3:21 PM

 **dano** :

 >Here's our code: <https://github.com/NeuroTechX/neurodoro/blob/5e38b0286d8424765db9186e13d2747212f6b5d8/classifier/neural_nets/juniper/eeg_rnn.py>

11/13/2017 6:47 PM

 **andyh616** :

 >super cool MEG decoding poster at SFN - <http://lauragwilliams.github.io/d/posters/Gwilliams_SNL_2017.pdf>

11/14/2017 12:56 AM

 **d.adamos** :

 >Hi rahman.shama, our latest work focuses on passive music listening + continuous EEG recording.  <https://qz.com/812498/eeg-brain-scans-can-tell-if-you-like-a-song-better-than-any-music-streaming-service-algorithm/>

11/14/2017 1:02 AM

 **sydneyneurotechx** :

 >Any potential opportunities with Hinton's capsule networks and eeg data? <https://medium.com/@pechyonkin/understanding-hintons-capsule-networks-part-i-intuition-b4b559d1159b>

11/14/2017 2:15 PM

 **alexandre.barachant** :

 >sydneyneurotechx I believe so. the idea of the capsule learning rotation invariance can be applied to dealing with transfer across session / subject (for many activity, i believe there is a lot of similarity between subject, but often the 'point of view' in EEG signal is different because of the variation in cortical organization and shape). The connection between capusle is also interesting, because a specific brain pattern is often composed of many "independant" patterns distributed across the brain (fox exemple, synchronization and desynchronization in the contra an ipsilateral motor cortex for decoding imagined movement)

11/14/2017 2:16 PM

 **alexandre.barachant** :

 >saying that, the capsule net seems to be tailored for image recognition, so it might be a little tricky to adapt

11/15/2017 12:37 AM

 **fred-simard** :

 >sydneyneurotechx One of the goal aimed by Geoff, when he presents the capsule network, is to reduce the number of data samples required for the network to learn advanced invariant representation. Any steps toward speeding up the training of the powerful deep nets is bound to be ground breaking. In consumer EEG, that means better and more individualized data analytics, shorter after device unboxing.

11/15/2017 3:38 AM

 **mhough** :

 >sydneyneurotechx fred-simard alexandre.barachant love the conversation on this and was certainly researching around his paper. Partly because of previous comments about his own direction post-backprop and lots of things in this particular paper, there is lots to like for vision scientists:) I was introduced to geometric algebra by physicists trying to understand what the visual system was managing to accomplish and even if we aren't on best track forward, its certainly a rich source of ideas to draw from. Karl Pribram always thought so:) Following that particular approach, there are reasons to move to a conformal geometry for the new invariants that you can then estimate. The kind of problems they are trying to solve in robotics is perhaps a better context for seeing the need for this. I liked the fact that his paper is using a more complex MNIST no matter what. Sorry this isn't very put together but I think its great direction and yes I think its even good for EEG.

11/15/2017 5:46 AM

 **mhough** :

 >Hey @andy616 thanks for sharing the super EEG paper. The paper and the brief discussion of it with psoulos and alexandre.barachant was very thought provoking. I'd be very interested in playing with the toolbox when its available. Is that MATLAB or python? Michele used GPy for his re-implementation of Haak et al. paper from this Summer so GPs are something that I have been looking at recently. Did you see the paper from Google Brain recently on DNNs as GPs?

11/15/2017 7:24 PM

 **andyh616** :

 >Hey mhough, no problem! It's a python toolbox and it will be available in the next month or so. I will announce it on here. I have not seen the google brain paper but will check it out. Thanks for the ref!

11/15/2017 8:03 PM

 **mhough** :

 >Perfect. Thanks

11/17/2017 11:22 PM

 **graeme** :

 >sydneyneurotechx

11/17/2017 11:25 PM

 **graeme** :

 >sydneyneurotechx alexandre.barachant andyh616 fred-simard hubertjb because of where we're located, we can pitch Geoff's lab at Vector on a capsule network EEG project supported by some of the Ontario/Canada funding agencies, in partnership with Muse. Is there interest in doing this?

11/18/2017 3:56 AM

 **sydneyneurotechx** :

 >Sounds like an interesting proposal on my side

11/18/2017 3:56 AM

 **sydneyneurotechx** :

 >What does  everyone else think?

11/19/2017 3:13 PM

 **andyh616** :

 >Sounds interesting but I've got too many thing going on at the moment to contribute anything meaningful :flushed:

11/19/2017 5:03 PM

 **dano** :

 >I was just thinking about this last night. Count me in

11/19/2017 7:46 PM

 **graeme** :

 >dano we could bring Avertus into this project too. 

11/20/2017 2:46 PM

 **r** :

 >alexandre.barachant When working with a time series dataset (EEG) how does the cross validation affect the results when the extracted features are from the frequency domain? I have a dataset of EEG recordings: 8 hours for 38 subjects. It was used to classify subjects according to their EEG. The extracted features are in the frequency domain: Fourier has been used.

> 
The cross validation technique used is: Stratified Shuffle Split.

> 
Some people say that with times series data, you cannot just mix the samples because you will end up using the future to predict the past (I have used stratified shuffled split). But in this case the features are in the frequency domain. Have I leaked information?

11/20/2017 3:03 PM

 **qbarthelemy** :

 >you should use time-frequency features on sliding windows, rather than frequency features (due to the stationary hypothesis of Fourier transform)

11/20/2017 3:23 PM

 **fred-simard** :

 >I'm working on a deep net project with Yannick, but would this be an open source initiative or would the IP belong to Muse?

11/20/2017 6:14 PM

 **yannick** :

 >Whats the idea Graeme? Anything you can disclose? Or you want to start a private chat with interested people?

11/20/2017 6:16 PM

 **alexandre.barachant** :

 >if you speak french : <https://www.facebook.com/LeHuffPost/videos/1558975550818688/>

11/20/2017 6:19 PM

 **alexandre.barachant** :

 >you can see me starting from 9'

11/20/2017 7:57 PM

 **yannick** :

 >My take away from the video: your laptop need a NeuroTechX sticker& hahaha :stuck_out_tongue:

> 
Awesome video.

11/21/2017 3:40 AM

 **aj** :

 ><http://ehtrust.org/wp-content/uploads/2015/12/Schools-and-Wireless-Briefing-October-2015.pdf>

11/21/2017 8:23 AM

 **alexandre.barachant** :

 >:slightly_smiling_face:

11/21/2017 8:23 AM

 **alexandre.barachant** :

 >where can i get one ?

11/21/2017 1:07 PM

 **r** :

 >qbarthelemy for example? 

> 


11/21/2017 1:18 PM

 **alexandre.barachant** :

 >r you don't have leaked information with your setup, but using stratified shuffle split would not lead to a realistic performance.

> 
two consecutive time window are very likely to be similar (in the frequency space) so you will get inflated performance.

11/21/2017 1:20 PM

 **alexandre.barachant** :

 >what you want to avoid is to have training and test data being recorded during the same time period

11/21/2017 1:21 PM

 **alexandre.barachant** :

 >you can use time series split : <http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.TimeSeriesSplit.html#sklearn.model_selection.TimeSeriesSplit>

11/21/2017 1:22 PM

 **alexandre.barachant** :

 >but if you want to do subject identification from EEG, best would be to have different sessions in training and test

11/21/2017 1:23 PM

 **alexandre.barachant** :

 >in this case, you can use <http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GroupShuffleSplit.html#sklearn.model_selection.GroupShuffleSplit>

11/21/2017 4:31 PM

 **r** :

 >alexandre.barachant thank you for your answer. But what about the hold-out set? Even despite using it, the performance is still inflated?

11/21/2017 4:31 PM

 **r** :

 >The hold-out was kept aside since the beginning.

11/21/2017 4:32 PM

 **alexandre.barachant** :

 >how was selected your hold out set ?

11/21/2017 4:32 PM

 **r** :

 >Randomly. I used a stratified random sampling. Basically I removed randomly the same amount of samples from each subject.

11/21/2017 4:34 PM

 **alexandre.barachant** :

 >then, you have the same problem

11/21/2017 4:36 PM

 **r** :

 >Hmm, then how should I have done the sampling? At the beginning I thought of removing the last samples (it is 8 hours recording: then the last 1 hour). To avoid the "using the future to predict the past".

11/21/2017 4:37 PM

 **alexandre.barachant** :

 >your problem is subject identification from EEG right ?

11/21/2017 4:37 PM

 **r** :

 >Yes, it is for biometrics.

11/21/2017 4:40 PM

 **alexandre.barachant** :

 >the ideal way to proceed is to record data from the same subject on another day. this way you are sure you have a realistic setup.

> 
it's not a problem of using the future to predict the past, but more that EEG (especially on low frequency) is very similar between consecutive time window

11/21/2017 4:41 PM

 **alexandre.barachant** :

 >if you don't have another session, then you could have used the first 5 for training, from 5h30 to 6h30 for test, and keep from 7 to 8 for hold out

11/21/2017 4:43 PM

 **alexandre.barachant** :

 >but it's not ideal, because your model will not take into account the inter-session variability, so you can expect a drop in performance when you want to identify the subject on another day

11/21/2017 4:44 PM

 **alexandre.barachant** :

 >whats the size of your window / epochs ?

11/21/2017 4:44 PM

 **r** :

 >30 seconds

11/21/2017 4:45 PM

 **r** :

 >Even with a leave-one-out cross validation? (leave 1 subject out).

11/21/2017 4:46 PM

 **alexandre.barachant** :

 >well, i'm not sure you can apply leave one subject out for subject identification

11/21/2017 4:47 PM

 **alexandre.barachant** :

 >or saying it differently, you can not identify a subject that does not exist in your training set

11/21/2017 4:47 PM

 **r** :

 >haha. yes, now I understand.

11/21/2017 4:49 PM

 **r** :

 >You know in any type of biometrics, there is an enrollment phase (a new user who wants to get access to a system). for me these are the epochs for the training of the system.

11/21/2017 4:51 PM

 **r** :

 >But if EEG is very similar, then the user would have access to the system the next day?

11/21/2017 4:51 PM

 **alexandre.barachant** :

 >is it what you want ?

11/21/2017 4:52 PM

 **alexandre.barachant** :

 >when i say very similar, its between 2 consecutive sample, in your case, 2 consecutive 30s window

11/21/2017 4:52 PM

 **r** :

 >Okey.

11/21/2017 4:54 PM

 **r** :

 >Well my research was focused on using COTS eeg headset to authenticate. So I enroll at 8H and I want access at 8h00m31s. Like with the fingerprint in the ipad.

11/21/2017 4:55 PM

 **r** :

 >Anyway. I will test the type of cross validation that you have suggested. Thank you.

11/21/2017 4:56 PM

 **r** :

 >And what if I have used time domain features? The consecutive windows are still similar?

11/21/2017 4:59 PM

 **alexandre.barachant** :

 >so you do the 8h enrollment every day ?

11/21/2017 5:00 PM

 **r** :

 >No, what I mean it is 8 o'clock, and I want to be enrolled at 8h with 30s. Because no one will be waiting a lot to have access to a system.

11/21/2017 5:01 PM

 **r** :

 >Ideally in biometrics, the enrollment and authentication have to be very fast. Because it is better for the user. For example no one waits 30 seconds to have access to their laptop after typing the password or using the fingerprint.

11/21/2017 5:03 PM

 **r** :

 >So, from the 8 hours dataset, I removed randomly 120 seconds form each subject for the hold-out. But also I removed samples to reduce the enrollment. At the end I use 1080 seconds for the enrollment and 30 seconds for the authentication.

11/21/2017 5:03 PM

 **r** :

 >haha. I messed up all the dataset.

11/21/2017 5:07 PM

 **r** :

 >Do you think that with the Riemannian geometry and my procedure; things would have been alright?

11/21/2017 5:45 PM

 **yrenard** :

 >r I believe everyone using microsoft platform waits way more then 30 seconds after inputing their password :slightly_smiling_face:

11/21/2017 5:54 PM

 **fortin.pasc** :

 >I will be honest with you. If I have to put on an EEG headset, tune the placement of the electrodes, boot my machine, wait 30s for it to authenticate and then start doing things, I would be throwing that system out the window.  But that's what research is about, keep up the good work... Once the system is working for 30s you can shrink down that period gradually.

11/21/2017 5:57 PM

 **r** :

 >haha. Well , ye sthe ides

11/21/2017 5:58 PM

 **r** :

 >the idea is to reduce time for enrollment and authentication. Also to use only 1 electrode.

11/21/2017 5:59 PM

 **fortin.pasc** :

 >yes, I understand the idea and encourage you to pursue it.

11/21/2017 6:00 PM

 **r** :

 >Thank you :grinning:

11/21/2017 6:10 PM

 **alexandre.barachant** :

 >r okay my point is that you don't really need 8h of training data, but if you want a realistic estimate of the performance, you want to have multiple session (just 1 min per session) so that you can estimate if your system is robust.

> 
if you use the same session, it correspond to the usecase that the user log just after making the enrollment, which is not realistic

11/21/2017 6:12 PM

 **r** :

 >And the session, ideally, has to be in different days, right?

11/21/2017 6:12 PM

 **r** :

 >I will look for a free dataset online.

11/21/2017 6:13 PM

 **alexandre.barachant** :

 >different day is the best. but just removing and putting back the headset can do a part of the job

11/21/2017 6:14 PM

 **alexandre.barachant** :

 >different day is better because you will be in a different cognitive state

11/21/2017 6:15 PM

 **alexandre.barachant** :

 >you don't want your system working only in the morning because you made the enrolment when you had larger alpha :slightly_smiling_face:

11/21/2017 6:17 PM

 **r** :

 >Yes! you know... my dataset is of sleeping subjects (that was the only dataset I could get). So I did the authentication for Awake, S1, S2, SWS, the combination of all sleep stages and the combination of sleep and awake. The best one was Rem. Also I trained in Awake and tested in the combination of all sleep stages (here the accuracy was very bad).

11/21/2017 6:20 PM

 **alexandre.barachant** :

 >yep, this is difficult to find a good dataset for that.

11/21/2017 6:25 PM

 **alexandre.barachant** :

 >this one might be usefull : <https://exhibits.stanford.edu/data/catalog/mz950kf4667>

11/21/2017 6:27 PM

 **r** :

 >Thank you very much. I will run the results and I will let you know. :grinning:

11/21/2017 6:39 PM

 **graeme** :

 >We could start a private chat, sure - this is just brainstorming but hubertjb has had a long standing interest in developing deep learning tools for EEG, as many of us have

11/21/2017 6:40 PM

 **graeme** :

 >But Geoff's in Toronto, and there's NSERC and OCE funding and Mitacs that could support a grad student or postdoc project on working with Geoff, if he's amenable - the hardest part would be convincing him to accept a collaborator.

11/21/2017 6:41 PM

 **graeme** :

 >If this is something we want to work on, we could organize it through NeuroTechX, lend support for funding through Interaxon and Avertus (alexdni dano) try to get Geoff Hinton/Chris Olah/Richard Zemel/etc. on board.

11/21/2017 7:29 PM

 **dano** :

 >Very cool. I think we've clearly got a Vector Institute full of students looking for interesting problems to work on, plenty of neurotech companies interested in applying deep learning to the data they're collecting, and a goverment interested in promoting this cutting-edge marriage between research and industry. Let's see what we can do to connect some of those interests.

11/22/2017 7:55 PM

 **nmp256** :

 >Hey there, not sure if this is the best channel for this question so please let me know if there's a better place for it. I'm a long time meditator interested in how self-compassion can be used to help people with eating disorders. There's already a lot of good research I've found on it, but not much I've found yet that covers how to detect compassion through biometrics (best I can get is looking at calm through heart rate changes). Does anyone here know if EEG can be used to detect anything like compassion and/or acceptance of yourself? Thanks so much!

