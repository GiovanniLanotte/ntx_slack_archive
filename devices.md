######devices

2/11/2017 10:34 PM

 **pierre** :

 ><@U0B586TUL> no I haven't but let me know if you have it!

2/11/2017 10:34 PM

 **pierre** :

 >I'll probably end up having to figure it out over the next week anyway

2/11/2017 10:45 PM

 **aj** :

 >do you want programmatic setup or GUI setup?

2/12/2017 12:29 AM

 **pierre** :

 >I want to stream raw data through python

2/12/2017 12:29 AM

 **pierre** :

 >I guess programmatic setup?

2/12/2017 12:29 AM

 **pierre** :

 ><@U0B586TUL> ^

2/12/2017 12:59 AM

 **aj** :

 >Most brute force way is the example in interfacing with other tools in the node js ganglion repo

2/12/2017 1:00 AM

 **aj** :

 >If you want more sophisticated see the Python example in the Cyton aka `OpenBCI_NodeJS`

2/12/2017 2:57 AM

 **pierre** :

 >Ah okay great thanks, will look into it

2/12/2017 10:15 AM

 **alexandre.barachant** :

 ><@U073X4JRL> will LSL streaming works for you ? i adapted the LSL example of `OpenBCI_NodeJS` for the ganglion. i can send you the files

2/20/2017 4:12 PM

 **sydneyneurotechx** :

 >Only thing that is inaccurate in the article is that the material has been around for a while. It's just being used in a different use case.

2/22/2017 5:24 AM

 **pierre** :

 >Hey <@U0AJ51TKJ>, I tried your LSL code and it worked very well! Thanks!

2/22/2017 8:40 AM

 **alexandre.barachant** :

 >sweet

2/22/2017 5:36 PM

 **benjamindeleener** :

 ><!channel> has anyone had difficulties connecting the OpenBCI Gui to the Cython on Mac OS X Sierra? The software doesnt seem to detect the board. It is working on Mac OS X El Capitan, with the same installation (Driver and Gui)

2/22/2017 6:19 PM

 **benjamindeleener** :

 >Its working when I moved the OpenBCI_GUI application into the application folder. Some stuff seem to have changed in Sierra. Happy that it is working though!

2/28/2017 9:04 PM

 **stephen** :

 >List of all ECG devices one can wear: <https://forum.quantifiedself.com/t/reliable-wearable-ecg/2653>

3/3/2017 1:50 AM

 **jfrey** :

 ><@U073X4JRL>: if you still want give ganglion + python a try (...and if you are a linux-powered guy), it's getting easier: <http://openbci.com/forum/index.php?p=/discussion/1017/ganglion-board-now-working-with-python-on-linux>

3/3/2017 6:12 AM

 **pierre** :

 >I'm still on the lookout for pure Python solutions though

3/7/2017 3:00 PM

 **physionikhil** :

 >hi i am trying to develop an eeg controlled electrical stimulation device for stroke patients , can anyone advise me on the hardware and assembly

3/7/2017 3:26 PM

 **sydneyneurotechx** :

 >Hi physionikhil. Do you have an idea of where you want to place the electrodes and the type of stimulation you would like to do?

3/7/2017 4:30 PM

 **physionikhil** :

 >Yes , for the muscle stimulation I want to place the Electrodes on the extensor compartment of forearm and for the leg region I want to place on the front of the thigh and just below the knee outside the shin bone, usually a interrupted galvanic current is used with a 9V medically approved stimulator

3/7/2017 9:09 PM

 **aj** :

 >Hey I'm gonna have 2 Wifi Shields for OpenBCI Cyton. Anyone interested in one? It's plug and play with an over the air update to the OpenBCI 32bit Cyton board.

3/7/2017 9:35 PM

 **sydneyneurotechx** :

 >physionikhil: For the EEG component, how many electrodes will you be using?

3/8/2017 12:42 AM

 **physionikhil** :

 >For EEG 8 Electrode system

3/8/2017 2:50 AM

 **physionikhil** :

 >Anyone interested to sell cyton board?

> 


3/8/2017 2:56 PM

 **sydneyneurotechx** :

 >And the electrode montage will primarily be in the C location? Also, out of curiosity is there any ethical dilemmas in doing this project? Do you have University approval or is it not required?

3/12/2017 5:25 AM

 **physionikhil** :

 >Yes that can work as well but fronto parietal locations will be better suited for it in my opinion. I am a private clinician and we already have patients with stroke and movement dysfunction. We will be taking written consents from our therapy clients and even now we have their verbal consent. I don't think there should be any ethical dilemma in this kind of study. If we could develop a working prototype of it I will be able to get a University approval where I am teaching

3/13/2017 11:17 PM

 **sydneyneurotechx** :

 >To view archived text from Slack please visit:

> 
<https://github.com/NeuroTechX/ntx_slack_archive/blob/master/devices.md>

3/14/2017 3:35 AM

 **physionikhil** :

 >Cheap cranial stimulation device from China, not sure how authentic it is as it doesnt specify any technical info

> 


> 
<https://f2rq3.app.goo.gl/?link=https%3A%2F%2Fm.alibaba.com%2Fproduct%2F60315578379%2FHaobro-design-electric-brain-stimulate-device.html&amp;apn=com.alibaba.intl.android.apps.poseidon&amp;ibi=com.alibaba.sourcing&amp;isi=503451073&amp;amv=69>

3/17/2017 4:14 PM

 **octonomy** :

 >Has anyone experienced an issue with openBCI dropping every other sample? I have a 16 channel kit but running it in 8 channel mode. Wondering if it's a limitation of the board (like you have to take off daisy while running in 8 channel mode). Looking it up on openBCI forum now but thought I'd ask you all here too

3/17/2017 4:16 PM

 **yrenard** :

 >No you can ask the 8 channels of the OpenBCI without removing the daisy board

3/17/2017 4:16 PM

 **yrenard** :

 >It must be deactivated though

3/17/2017 4:16 PM

 **yrenard** :

 >and this has an impact on the sampling rate

3/17/2017 4:16 PM

 **yrenard** :

 >You would receive twice as much samples from the board than what you would receive if the daisy module was activated

3/17/2017 5:48 PM

 **octonomy** :

 >Do you know the procedure to deactivate it? Is it a command line option or a physical hardware switch?

3/17/2017 5:49 PM

 **octonomy** :

 >Right it is 250hz for 8channel and 125 for 16channel. I was hoping I could just switch between those by specifying correct device

3/17/2017 5:50 PM

 **yrenard** :

 >It is a command that you send through the BT protocol

3/17/2017 5:50 PM

 **octonomy** :

 >Ok I see 

3/17/2017 5:50 PM

 **yrenard** :

 >Let me check the OpenViBE driver

3/17/2017 5:50 PM

 **octonomy** :

 >I'll look that up. Thanks for confirming, it's kind of a hard thing to search for in openBCI forum

3/17/2017 5:53 PM

 **yrenard** :

 >So sending `c` should do the trick

3/17/2017 5:55 PM

 **yrenard** :

 >Btw, you should find it in the documentation - But I needed to read it once to understand how to search in it :wink:

3/17/2017 5:57 PM

 **yrenard** :

 >You need to look at this page specifically <http://docs.openbci.com/OpenBCI%20Software/04-OpenBCI_Cyton_SDK>

3/19/2017 12:02 AM

 **octonomy** :

 >Thank you!!

3/22/2017 1:54 AM

 **a.tech** :

 >Has anyone tried printing an UltraCortex using a flexible filament like (TPE or TPU) instead of ABS or PLA? 

> 


> 
Maybe it'll get better contact or be more comfortable if the helmet had some flex to it?

3/22/2017 1:55 AM

 **a.tech** :

 >Im ordering in some filament right now so I thought I'd ask haha

3/22/2017 3:44 AM

 **sydneyneurotechx** :

 >conor  Showed me some prototype with ninja flex I believe. Unsure of the results though

3/22/2017 3:52 AM

 **sydneyneurotechx** :

 >irene.viguix  May have an answer for you

3/22/2017 2:27 PM

 **yannick** :

 >hey jmhorschig do you have an idea of the price range for the OctaMon device?

> 
<http://www.artinis.com/octamon/>

> 
We were having a discussion about the price range of portable fNIRS devices recently.

3/22/2017 6:54 PM

 **aj** :

 >anyone know have experience with MQTT?

3/22/2017 6:55 PM

 **aj** :

 >i've seen and held one

3/23/2017 8:20 PM

 **harris** :

 >Is there any software to use with openBCI that is like emotiv's where you can do command recognition

3/23/2017 8:57 PM

 **sydneyneurotechx** :

 >Like Keyboard control?

3/23/2017 8:59 PM

 **sydneyneurotechx** :

 >If so, you could potentially with OpenVibe

3/23/2017 9:00 PM

 **sydneyneurotechx** :

 ><http://openbci.com/forum/index.php?p=/discussion/475/moving-the-cursor-via-openvibe-ongoing-tutorial-for-beginners>

3/23/2017 9:05 PM

 **harris** :

 >How much work needs to be done with OpenVIBE to achieve something similar to Emotiv's kit?

3/24/2017 7:52 AM

 **jmhorschig** :

 >yannick: sure I have, I am working here ;) the whole industry is hesitant with making their prices publicly available though (not sure why, we all know what prices of competitors are anyway), and it varies per country Think of something around 20k$.

3/24/2017 12:21 PM

 **yannick** :

 >jmhorschig yeah, we had a similar conversation few months ago about some EEG (research) devices not showing their prices but offering a "Get a Quote" button. (e.g. Cognionics)

3/24/2017 12:21 PM

 **yannick** :

 >Thanks for the price range!

3/24/2017 12:35 PM

 **jmhorschig** :

 >Generally with EEG research devices, it's about 500$ per channel up until 32ch, and then 250$ per additional channel up until 64ch, and from then on ~125$ per channel ( i.e. 8ch is 4k$, 32ch ~16k$, 64ch ~24k$, 128ch ~32k$, 256ch ~48k$). Just rough estimates though, differs a bit per company. It's a bit stupid that it's so secretive, but that's the market...

3/24/2017 3:42 PM

 **sydneyneurotechx** :

 >yrenard Any ideas?

3/24/2017 3:58 PM

 **yrenard** :

 >I would say reading the tutorials mainly, to understand the underlying of a BCI process (preprocess, feature extraction, modeling and feedback pipeline basically) - Everything is in the software to let you do pretty much the same as Emotiv's EmoKey

3/24/2017 3:58 PM

 **yrenard** :

 >Say 2 days of reading and messing around with the software and you should be good to build what you need

3/31/2017 6:13 AM

 **pierre** :

 >Anybody know the status of this and similar open TMS projects? 

> 
<http://open-rtms.sourceforge.net/>

3/31/2017 12:08 PM

 **yannick** :

 ><http://www.neuroelectrics.com/products/caps/headcap-cover-r>

> 
Adding a Faraday shielding over the EEG cap. Interesting...

3/31/2017 2:59 PM

 **aj** :

 >Lit

3/31/2017 3:12 PM

 **physionikhil** :

 >This is great

4/1/2017 12:13 PM

 **yannick** :

 >Looking forward to see the signal from:

> 
<https://www.youtube.com/watch?v=5CZtoYbfbHU>

4/2/2017 11:05 PM

 **harris** :

 >yannick are those glasses at the end the supposed product?

4/2/2017 11:06 PM

 **yannick** :

 >Yup, the new InteraXon's device. (you can kinda recognize the Muse behind the ear electrodes)

4/2/2017 11:06 PM

 **harris** :

 >'Lowdown Focus Mpowered by Muses frames includes brainwave-sensing EEG, EOG and EMG technology as well as other sensors, including a 3-axis accelerometer, a 3-axis gyro, a 3-axis magnetometer, a UV sensor (UVA and UVB), a temperature gauge and a pressure sensor, providing a rich upgrade path for applications via an open SDK.'

4/3/2017 3:08 AM

 **octonomy** :

 >what i want is to start an eeg modeling agency

4/3/2017 3:19 AM

 **sydneyneurotechx** :

 >Neat cap. What is  Spacer and silver fabric? Anyone have any ideas? Can't find much online.

4/4/2017 6:15 AM

 **sydneyneurotechx** :

 >For those interested. japesinator  created at TDCS Badge for Cyphercon (Hacker conference in Wisconsin). It is functional (tried it on myself). I did a simple optic nerve stimulation and it created beautiful phosphenes.

> 


> 
All hail Electric Cthulhu!

4/6/2017 4:19 PM

 **octonomy** :

 >hello, does anyone on here use an openbci with daisy module? wondering if i have the wires hooked up correctly

4/6/2017 4:20 PM

 **octonomy** :

 >im seeing weirdness, quite high voltage readings (range of ~2000uv) and every channel is identical, which im pretty sure is not supposed to happen

4/6/2017 4:23 PM

 **octonomy** :

 >My connections are like this:

> 
All electrodes on bottom row of both boards 

4/6/2017 4:25 PM

 **octonomy** :

 >Including the GND (connected bottom row on bottom board) and the SRB (connected bottom pins on both boards - to a y-connector)

4/6/2017 4:35 PM

 **sydneyneurotechx** :

 >Does it work correctly without the Daisy module? octonomy ?

4/6/2017 4:41 PM

 **octonomy** :

 >yes, without the daisy its great

4/6/2017 4:41 PM

 **octonomy** :

 >so i think its not the main board

4/6/2017 4:42 PM

 **octonomy** :

 >of course i had to solder the headers onto daisy myself, os i second guess myself, but the solder points do look clean

4/6/2017 4:42 PM

 **octonomy** :

 >i also question if i did a good enough job soldering the y connector wire to connect the SRB

4/6/2017 4:43 PM

 **octonomy** :

 >but before i go down that path, i just wanted to ask if anyone can validate that i just have the wires on daisy hooked up correctly. this is one thing is just cant find on Openbci forums or their how to.

4/6/2017 5:02 PM

 **octonomy** :

 >it seems to work most normally when i take off my right ear clip. this brings the signal within normal range of 0-200uV

4/6/2017 5:03 PM

 **octonomy** :

 >when i have both clips on, it exhibits weird behavior, where it will be normal for about 5 sec, then suddenly jump up to 10,000uV range for 5 sec, then back down again. it seems to just jump between orders of magnitude of voltage every 5sec or so

4/6/2017 5:38 PM

 **aj** :

 >that's the right setup

4/6/2017 5:38 PM

 **octonomy** :

 >excellent, thank you

4/6/2017 5:39 PM

 **octonomy** :

 >this frees me up to try other things.  ill try resoldering a different y-connector, maybe i jacked it up somehow

4/6/2017 5:39 PM

 **aj** :

 >you should send me your daisy board lol

4/6/2017 5:39 PM

 **aj** :

 >i would have already had it fixed and sent back

4/6/2017 5:39 PM

 **aj** :

 >ask teon

4/6/2017 5:40 PM

 **octonomy** :

 >i might just send it. i have to get the other one soldered up and running and i will do it. could be out in the post tomorrow :slightly_smiling_face:

4/6/2017 5:40 PM

 **octonomy** :

 >thnks

4/6/2017 5:40 PM

 **octonomy** :

 >btw aj your openbci node connector is the greatest thing since sliced bread

4/6/2017 5:42 PM

 **aj** :

 >good you should spend your time doing cool shit with the data not trying to get the data

4/6/2017 5:42 PM

 **aj** :

 >and thanks!

4/6/2017 5:43 PM

 **aj** :

 >when i use the openbci GUI, packets get dropped, but with my node connector inside thinker, packets never get dropped because it's on it's own process separate from analysis

4/6/2017 5:43 PM

 **aj** :

 >it's like the most important thing for this serial connection so the nod works great for that

4/6/2017 9:36 PM

 **octonomy** :

 >Yes exactly!

4/8/2017 11:25 PM

 **kshen** :

 >Does anyone know if brain sensing devices/headbands are being used in banks to monitor emotions of traders?

> 


> 
<https://www.bloomberg.com/news/articles/2016-09-01/wall-street-s-next-frontier-is-hacking-into-emotions-of-traders>

4/9/2017 12:57 PM

 **melanie** :

 >I've heard people considering it, but I haven't seen it implemented anywhere

4/9/2017 1:49 PM

 **kshen** :

 >melanie how accurate would EEG data even be

4/9/2017 6:34 PM

 **sydneyneurotechx** :

 >I would say that High Frequency Trading will make all/most Traders obsolete anyways

4/9/2017 10:37 PM

 **kshen** :

 >Interesting, why do you say that?

4/10/2017 2:17 PM

 **bciguy** :

 >another pair of headphones (powered by Onkyo) with EEG capabilities succesfully crowdfunded.. <https://www.indiegogo.com/projects/mindset-smart-headphones-that-improve-your-focus#/> This is the 2nd Ive seen with this type of montage (first is Kokoon).. Ive never seen anything like this come close to measuring real EEG .. and given my experiences (challenges) with skin-contact dry electrodes, Im not willing to believe any useful signal can be measured this way. Can someone change my mind about this?

4/10/2017 2:57 PM

 **alexandre.barachant** :

 >bciguy i have some good signal coming from this type of dry electrode. However, the headset must be tight to keep good contact.

> 
Looking just at the picture from the headset, i would say you better have short hair to get anything from it.

4/10/2017 3:12 PM

 **bciguy** :

 >alexandre.barachant do your electrodes protrude out of the case? Looking at this type of design it really seems like the best signal quality will be maybe comparable to earlier studies of EEG measured through the hair. I remember the signal attenuation being very high for those approaches, not to mention the uncontrollable factor of differing hair styles/thicknesses etc when targeting such an EEG device to consumer markets.

4/10/2017 3:15 PM

 **alexandre.barachant** :

 >my electrodes are note completely different but are made to go through hair. i posted some picture a while ago but they might have diseapered from the slack

4/10/2017 3:15 PM

 **alexandre.barachant** :

 >it's just some pins, bassicaly

4/10/2017 3:16 PM

 **alexandre.barachant** :

 >they might have made pin smaller for their pictures (not to scare people off) but the principle is the same

4/10/2017 3:17 PM

 **alexandre.barachant** :

 >if the pins are really like on the picture (i.e. 1-2 mm long), then they will defenetly not touch the scalp

4/10/2017 3:19 PM

 **alexandre.barachant** :

 >there is a huge tradeoff between comfort and signal quality with this kind of dry electrodes

4/10/2017 3:20 PM

 **alexandre.barachant** :

 >you generally want bigger pins so it can got through any length of hair.

4/10/2017 3:22 PM

 **alexandre.barachant** :

 >most dry electrode based on pins (g.tec, wearable sensing, and to some extend cognonics) have pins with length &gt; 7mm

4/10/2017 3:24 PM

 **bciguy** :

 >yep, that has been my experience too. Just watching the field it makes me nervous when I see crowdfunding projects like these, when it is so obvious that what they have prototyped couldnt possibly work..

4/10/2017 3:26 PM

 **alexandre.barachant** :

 >well, it seems you can remove the electrode from the headset, so at least you will get a nice pair of headset :slightly_smiling_face:

4/10/2017 3:32 PM

 **alexandre.barachant** :

 >It would be nice to have the founders join the slack for a Q/A session.

4/10/2017 4:19 PM

 **yannick** :

 >The founders of Mindset you mean alexandre.barachant ?

4/10/2017 4:19 PM

 **sydneyneurotechx** :

 >jacobflood  Comments? ^

4/10/2017 4:19 PM

 **yannick** :

 >or doyond

4/10/2017 4:22 PM

 **yannick** :

 >( jacobflood &amp; doyond are the founders of Mindset - the EEG headphones kickstarter )

4/10/2017 4:35 PM

 **jacobflood** :

 >Totally game! Ill be travelling for the next few weeks though as we head back to Shenzhen, maybe we can organize an AMA?

4/10/2017 10:30 PM

 **aj** :

 >Gonna give away 10 free for beta test, only a couple spots left

4/10/2017 10:30 PM

 **aj** :

 ><https://docs.google.com/forms/d/e/1FAIpQLSfjMzITl3Z_bMxCZlXaUVHxj0vVZ6oXyk3G05epOMYWBOiAFA/viewform>

4/12/2017 7:40 PM

 **sydneyneurotechx** :

 >credit goes to yannick  for the find. But this might be interesting for people: <https://hackaday.io/project/20618-freeeeg32-32-channels-electroencephalography>

4/12/2017 7:41 PM

 **sydneyneurotechx** :

 >Looks like an openbci inspired 32 channel eeg

4/12/2017 7:48 PM

 **benjamindeleener** :

 >Very nice! Do we have a rough idea of how much it would cost to produce it?

4/12/2017 7:51 PM

 **benjamindeleener** :

 >and I see it has a Wifi shield integrated. What would be the max acquisition frequency? :smile:

4/12/2017 7:52 PM

 **sydneyneurotechx** :

 >No Idea, but my assumption is that they are just x4 up on most compontents of the 8 channel openbci BOM.

4/12/2017 7:52 PM

 **sydneyneurotechx** :

 >At least that's what it looks like from the picture

4/12/2017 7:53 PM

 **benjamindeleener** :

 >seems like it indeed

4/12/2017 7:58 PM

 **marion** :

 >Interesting. Also aj, this wifi shield looks awesome. How can we get on the beta list? (I think i remember completing a beta tester form some time ago, but i'm not sure). And I second octonomy , your nodeJS connector is the best. So much more stable!!

4/12/2017 7:58 PM

 **alexandre.barachant** :

 >it's another ADC different from the openbci. I'm actually considering a similar one for the next iteration of my board

4/12/2017 8:10 PM

 **marion** :

 >I just saw the link you posted above. OK, I guess I filled the form 2 times :stuck_out_tongue:

4/12/2017 8:11 PM

 **marion** :

 >I just saw the link you posted above. OK, I guess I filled the form 2 times :stuck_out_tongue:

4/12/2017 8:52 PM

 **alexandre.barachant** :

 >Looking at the BOM, they have some expensive component, but its wont be that much

> 
You can upload the design on MacroFab or Circuithub and get a quote. 

> 
I might be totally wrong, but i would say around 200-300$ per unit for 10 units

4/13/2017 1:24 AM

 **aj** :

 >It's GPL :(

4/13/2017 1:24 AM

 **aj** :

 >So much for shoving it in a commercial product 

4/13/2017 1:30 AM

 **yrenard** :

 >you know you can still ship it in a commercial product aj

4/13/2017 1:31 AM

 **aj** :

 >But have to disclose all the changes you make

4/13/2017 1:31 AM

 **yrenard** :

 >true that

4/13/2017 1:41 AM

 **harris** :

 >As a student with little money, been doing some digging.

4/13/2017 1:42 AM

 **harris** :

 ><https://i.imgur.com/rKlMrLj.png>

4/13/2017 1:42 AM

 **harris** :

 ><https://i.imgur.com/rKlMrLj.png> <https://i.imgur.com/Wh7IZjU.png>

4/13/2017 1:44 AM

 **bhargava2566302** :

 >Thats gr8

4/13/2017 1:45 AM

 **yrenard** :

 >haha harris maybe the difference is on one site, they have it on stock whereas on the other one, they promise delivery within 60 (!) days (if it ever happens)

4/13/2017 1:45 AM

 **harris** :

 >I've bought quite a bit from aliexpress in the past, they do have buyer production.

4/13/2017 1:46 AM

 **harris** :

 >If you notice in the image they actually have 900+ in stock compared to 42

4/13/2017 1:46 AM

 **yrenard** :

 >oh I did not see the 900+ note aside

4/13/2017 1:46 AM

 **yrenard** :

 >I take my joke back :wink:

4/13/2017 1:59 AM

 **aj** :

 >Yea china has cloned the shit out of the pulse sensor

4/13/2017 2:14 AM

 **aj** :

 >sydneyneurotechx wahhh trying to peel apart this wifi code but so much better c code then I can read lol

4/13/2017 2:15 AM

 **harris** :

 >Found some others

4/13/2017 2:15 AM

 **harris** :

 ><http://i.imgur.com/MzWWLaz.png>

4/13/2017 2:15 AM

 **harris** :

 ><http://i.imgur.com/h85qKdp.png>

4/13/2017 2:16 AM

 **harris** :

 >Not the same mm but there are others that have the same

4/13/2017 3:59 AM

 **aj** :

 >you're good!

4/14/2017 1:36 PM

 **aj** :

 >and thanks for the kind words on the nodejs connector :slightly_smiling_face: it's come a long way that's for sure!

4/15/2017 8:45 PM

 **dmitryneuro** :

 >I have 4000 Hz maximum

4/15/2017 8:55 PM

 **dmitryneuro** :

 >from OpenBCI Cyton used only ESD protection TPD4E1B06

4/15/2017 8:55 PM

 **benjamindeleener** :

 >How nice! That is quite great.

4/15/2017 9:03 PM

 **dmitryneuro** :

 >for 4000 Hz it was test inside mcu. for output by uart-wifi-&gt;wifi-uart-usb was tested only 1000 Hz, because I have CP2102 uart-usb with only 1Mhz. soon will test CP2102N with 3 MHz

4/15/2017 9:14 PM

 **dmitryneuro** :

 >32 channels * 24 bits * 4000 Hz = 3072000 bits/second, so it is close to limit of CP2102N.

> 
STM32F427ZI have on its USART 5.625 MBits/s.

> 


> 
I used uart-wifi-&gt;wifi-uart-usb with TCP2UART

4/21/2017 1:13 PM

 **eferdinand** :

 ><!channel> Has anyone used dry elecrodes with an amplifier originally built for wet ones? 

> 
Is there a difference in voltage between both electrode typea in a way that dry elecrodes have low signal that the amplifier is not capable of detecting? 

> 
Does it make sense?

> 
Could the impedance be the issue?

> 
If anyone has more information about the subject i'd appreciate it, you can reply here or DM me.

> 


4/21/2017 1:18 PM

 **aj** :

 >eferdinand I've been wondering the same thing!

4/21/2017 1:19 PM

 **aj** :

 >Do we need to change the hardware filters based on the impedance of the electrode?

4/21/2017 1:20 PM

 **aj** :

 >Like the OpenBCI only works with dry Ag/AgCl and NOT Dry Gold, but it works with wet Ag/AgCl and wet Gold Cup

4/21/2017 1:21 PM

 **aj** :

 >How do we calculate what filters were need based on the impedance of the electrode

4/21/2017 1:32 PM

 **aj** :

 >alexandre.barachant said electrodes can have impedance, so long as all electrodes have the same impedance

4/21/2017 1:33 PM

 **eferdinand** :

 >Exactly and apparently it's a problematic now, is there any literature about the topic? 

> 
I just faced this problem and im gonna put some efforts researching it. If you have any leads let me know...

4/21/2017 1:33 PM

 **aj** :

 >Are you seeing saturation/railing?

4/21/2017 1:34 PM

 **eferdinand** :

 >what's he scale of acceptable impedance on dry elecrodes, it's enormously different from wet ones until now.

> 
is there a way to compare or to bring it to scale

4/21/2017 1:34 PM

 **aj** :

 >The amplifier data sheets do shed light on these issues, 

4/21/2017 1:35 PM

 **alexandre.barachant** :

 >about the impedance. it dependens on the input impedance of the amplifier. EEG amplifier made for wet electrode generally have lower input impedance

4/21/2017 1:36 PM

 **alexandre.barachant** :

 >so when you use dry electrodes, impedance difference between the reference electrode and your measurment electrodes starts to matters, and it degrades your common mode rejection ratio (more noise)

4/21/2017 1:37 PM

 **alexandre.barachant** :

 >the second issue is that dry electrode have a bigger offset voltage, which lead to saturation of the amp

4/21/2017 1:38 PM

 **aj** :

 >How do you deal with the second issue?

4/21/2017 1:40 PM

 **aj** :

 >Bigger low pass filter?

4/21/2017 1:42 PM

 **alexandre.barachant** :

 >larger input range of the amplifier (for example decrease the Gain of the amplification) or high pass the signal

4/21/2017 1:44 PM

 **alexandre.barachant** :

 >decreasing the gain is the easiest way, but depending on your ADC, that can increase the noise level beyond what is acceptable.

> 
High pass filtering use more board space, and can degrade CMRR if you don't match the components values. Also, it change the phase of the signal

4/21/2017 1:50 PM

 **aj** :

 >&gt; high pass filtering... Can degrade CMRR is you don't match the components values

> 


> 
What are components here, to be sure they are matched

4/21/2017 2:06 PM

 **eferdinand** :

 >?

4/21/2017 6:01 PM

 **alexandre.barachant** :

 >electronic components (Resistor / Capacitors) of the filters

4/21/2017 6:01 PM

 **ntremblay_neuroservo** :

 >The components that need to be matched are the components between body (electrodes) and input of chip amplifier for the CMRR.

4/21/2017 6:13 PM

 **ntremblay_neuroservo** :

 >Here is a simple explanation: when components are used on the line before amplifier, these components affect frequency and phase response. If this channel response differ from from the response of the next channel the CMRR is affected since the same signal (let say 60hz) will not anymore be in sync between the two inputs so it won't be well eliminated by a differential amplifier.

> 
hope it can help.

4/22/2017 6:57 PM

 **pskorupinski** :

 >Hello everyone! I was planning on ordering an *OpenBCI* Ganglion board to my city in *Europe* but the price of trustworthy shipping seems unreasonable (just because it ships every time from the US). What would you recommend me to do? Are there some similar devices that have distribution all over Europe? Thank you so much!

4/23/2017 1:04 AM

 **sydneyneurotechx** :

 >There are European Alternatives if the cost is too much for shipping. What's your price range and what do you want to do with the device?

4/28/2017 9:05 AM

 **nicomaque.jette** :

 >guys maybe my question seems a basic one but I noticed the last version of OpenBCI Windows Application sends current only to the 'P' pins when we activates Lead-Off Detection, while we had a choice of 'N' or 'P' pin in the previous version. Why would it be 'P' pins only and why would someone make a setup using all electrodes on 'P' pins instead of 'N' pins (I always use only 'N')? many thanks!

4/28/2017 9:10 AM

 **nicomaque.jette** :

 >maybe I'm wrong but I would assume switching all the channels and ref electrodes from 'N' pins to 'P' pins would only change the sign of the readings

4/28/2017 10:44 AM

 **nicomaque.jette** :

 >also how many OpenBCI we have with NeuroForce and is there 1 that is 'unused' that we could do without for maybe a month?

4/28/2017 10:44 AM

 **nicomaque.jette** :

 >(forget last message, wrong channel lol)

4/28/2017 12:55 PM

 **nicomaque.jette** :

 >(@channel plz tag me in the answers, thanks!)

4/28/2017 3:59 PM

 **aj** :

 >do you want to open an issue on github?

4/28/2017 4:06 PM

 **nicomaque.jette** :

 >aj indeed I think it'd be a good idea

4/28/2017 4:07 PM

 **nicomaque.jette** :

 >aj on your side do you sometimes use setup that only use 'P' pins?

4/28/2017 4:35 PM

 **aj** :

 >never

4/28/2017 8:18 PM

 **nicomaque.jette** :

 >yeah same for me

4/30/2017 11:13 AM

 **nicomaque.jette** :

 >another quick question guys, I understand the role of OpenBCI's SRB as a ground though the impact of using BIAS is still unclear, why do we actually also need BIAS and not use only SRB?

4/30/2017 11:13 AM

 **nicomaque.jette** :

 >"If you use the N inputs for your electrodes, you have the option to connect some or all of the P inputs together and use SRB2 as reference for those channels you select."

4/30/2017 11:17 AM

 **nicomaque.jette** :

 >I've seen we can disable it but I don't fully grasp the extend of effects in doing so, many thanks!

4/30/2017 4:01 PM

 **aj** :

 >N inputs are referenced against the SRB1 pin by default, that's for EEG. 

4/30/2017 4:02 PM

 **aj** :

 >Pretty sure the bias is used as driven right ground for removing the capacitance in the skin that is always around

4/30/2017 4:03 PM

 **aj** :

 >I know neither of them are System ground for the electronics

4/30/2017 6:47 PM

 **nicomaque.jette** :

 >thanks aj

4/30/2017 9:13 PM

 **pierre** :

 >Is anyone working on a node.js module for the Muse? Like openbci-ganglion but for the Muse?

5/1/2017 1:14 AM

 **dano** :

 >Nope, but that's a great idea!

5/1/2017 1:15 AM

 **dano** :

 >Wouldn't take more than a week or two to wrap Muse SDK in JS, I reckon

5/1/2017 11:26 AM

 **nicomaque.jette** :

 >pierre I'm pretty sure a colleague in Montreal did a similar project, I'll DM you his infos as I don't find his user on this Slack

5/1/2017 11:29 AM

 **nicomaque.jette** :

 >found him : sidksv

5/1/2017 5:06 PM

 **yannick** :

 >Indeed, he did a nice project with the Muse and JS. sidksv wanna talk about what you did and the language behind it.

5/1/2017 5:16 PM

 **sidksv** :

 >For my project MindPainter I use muse sdk along with nodejs <http://socket.io|socket.io> and es6 js connected to mongodb. For the visualization is canvas webgl.

5/1/2017 5:32 PM

 **w** :

 >Screenshot?

5/2/2017 8:44 PM

 **sidksv** :

 >w I had made a video. Please check on this link <https://youtu.be/Yd_1TMwuSOA>

5/6/2017 6:22 AM

 **nicomaque.jette** :

 >guys (and aj) , I've been trying to flash the OpenBCI's firmware a very good amount of times now and sometimes it works and other times it just stays with the previous version instead of the new even though the upload worked 100% on the Arduino GUI. Here's the procedure I use:

> 


> 
1) OpenBCI Dongle set to GPIO6.

> 
2) Power OFF the OpenBCI Board.

> 
3) Press down both RST and PROG buttons at the same time.

> 
4) Power ON the OpenBCI Board.

> 
5) Release the RST button while still holding down the PROG button.

> 
6) Release the PROG button.

> 
7) Compile and upload OpenBCI_32bit in Arduino IDE

> 
8) Power off OpenBCI

> 
9) OpenBCI Dongle set back to Reset.

> 


> 
(I noticed the firmware don't get updated if the OpenBCI Dongle stays on GPIO6 after an upload)

> 


> 
Is there any crucial step that I'm missing? Or any way to force the OpenBCI to set itself with the latest uploaded firmware? Many thanks!

5/6/2017 9:47 AM

 **aj** :

 >That's the wrong firmware

5/6/2017 9:49 AM

 **aj** :

 >Well what version are you trying to flash?

5/6/2017 9:49 AM

 **aj** :

 >If it's V1 then that method should work although there was a bug that could lead to failures while uploading

5/6/2017 9:49 AM

 **aj** :

 ><https://github.com/OpenBCI/OpenBCI_32bit_Library/blob/master/examples/DefaultBoard/DefaultBoard.ino>

5/6/2017 9:50 AM

 **aj** :

 >Is the v2 firmware, and soon to be v3 firmware that supports wifi

5/6/2017 9:51 AM

 **aj** :

 >You'll want to upload the radios if you are upgrading from v1 to v2, please follow the upgrade guide if that's the case <https://github.com/OpenBCI/OpenBCI_32bit_Library/blob/master/UPGRADE_GUIDE.md>

5/6/2017 9:52 AM

 **aj** :

 >Hit me in the DM and id be more then happy to hop on a chat and get you back to hacking! 

5/6/2017 10:26 AM

 **nicomaque.jette** :

 >thanks aj ! I've found a way to validate the upload (turning the LED to HIGH/LOW each time in the Arduino sketch) and doing so somehow it worked each time and my script in CPP files all worked as supposed

5/6/2017 11:55 AM

 **aj** :

 >Yea ive been using that little light for debugging too hahaha

5/6/2017 11:55 AM

 **aj** :

 >Are you using v2.0.1?

5/6/2017 1:45 PM

 **nicomaque.jette** :

 >aj that LED makes me recall my first "hello world" with Arduino lol

5/6/2017 1:45 PM

 **nicomaque.jette** :

 >still with v1 so far

5/6/2017 1:58 PM

 **aj** :

 >cool yea there is a variable called `pollTime` (pretty sure that's what it's called there) that needs to be raised on most machines to prevent the over the air programming from failing. Helps to keep the arduino ide window open, or call the build upload from a terminal window if possible and leave that front and center.

5/6/2017 9:28 PM

 **nicomaque.jette** :

 >thanks for the info!

5/7/2017 11:21 PM

 **aj** :

 >Anyone done analytics on Intel Edison yet?

5/10/2017 8:50 PM

 **aj** :

 >essentially a tiny breakout board for ADS1299

5/10/2017 11:26 PM

 **a.tech** :

 >How cute 

5/11/2017 12:53 AM

 **nicomaque.jette** :

 >nice! 'P' inputs would be on the other side?

5/11/2017 2:32 AM

 **aj** :

 >I never use P so I figured I'd save some space 

5/11/2017 3:08 AM

 **nicomaque.jette** :

 >indeed :stuck_out_tongue:

5/11/2017 3:14 AM

 **nicomaque.jette** :

 >I understood that impedance test used voltage difference of a channel between 'P' and 'N' while having Lead-Off current on 'P', I'm not sure how I'd go about with this tiny board

5/12/2017 12:41 AM

 **stephen** :

 >Does anyone know people who could make a scalable, cheap wireless RFID tag system? 

> 
Interested in putting sensors on livestock. 

> 
Thanks.

5/12/2017 6:23 PM

 **sydneyneurotechx** :

 >at what cost?

5/12/2017 6:23 PM

 **sydneyneurotechx** :

 >stephen? What's the PPU you're looking for

5/12/2017 6:23 PM

 **sydneyneurotechx** :

 >I'm connected with Dangerous Things. They do RFID Implants for Humans

5/13/2017 2:20 AM

 **yannick** :

 >Anyone whos played with Analog/Digital inputs with the OpenBCI Ganglion board?

5/13/2017 3:22 PM

 **aj** :

 >Hi everyone! I want to integrate fNIRS/EROS or functional ultrasound (fUS) sensors into my headset on monday. The headset is a bose noise canceling headphones. what company do I buy fNIRS, EROS, fUS sensors from? I specifically want to integrate them through SPI or I2C interfaces. My speciality is system design, electronic design (pcbs), firmware, drivers, wireless comms, applied open source neural decoding algorithms (note i don't make the algs, just find and apply). Thank you sooo much y'all :slightly_smiling_face:

5/13/2017 3:24 PM

 **aj** :

 >there is no wrong answer, not testing intellect or anything, just want to see if anyone has any insight

5/13/2017 11:27 PM

 **mhough** :

 >I'll know more when I meet with the Fus people in Virginia. The tyler lab at va Tech lists some make/model in their papers on fus but I haven't used that. The openfnirs bom is complete I believe.but I don't know if you want a companies support/features. Too many modalities use EROS as an acronym. You talking optical or EIT or something else? Thanks. Sounds great. Do you have a multi physics model? How many sensors do you want to try and fit?

5/14/2017 10:46 AM

 **aj** :

 >I saw the bom for openfnir was pretty complete. I reached out to the fUS people too, gonna try and call them tomorrow. I was talking optical EROS, but yea still hair is a problem with that modality

5/14/2017 10:02 PM

 **mhough** :

 >Sure. I don't know what people want to hear on the hair thing. Sick people don't care about their hair and if you want to "see through walls" then use MEG. Do you mean Gratton's EROS? Are they still doing that? It never made it into a paper but I think. An aside. We got a good confirmation of Gratton's space fortress -subcortical volume result from Arul and Omar's data at GazzLab. EROS if I remember correctly is based on the same physiological mechanism as Bayford and Holders-EIT in that water changes are what's driving your imaging contrast.

5/14/2017 10:03 PM

 **mhough** :

 > You need FEM for this 

5/14/2017 11:17 PM

 **aj** :

 >what is FEM?

5/14/2017 11:18 PM

 **aj** :

 >would be sweet if we could use MEG but the whole super cooling thing inside a faraday cage

5/15/2017 12:26 AM

 **aj** :

 >sooo <http://www.sciencedirect.com/science/article/pii/S1053811917300411>

5/15/2017 1:22 AM

 **mhough** :

 >Yeah that's real and right on Matthew for the last author credit on that! I didn't know he was interested in that part too. And yeah your not going to have a wearable version of that anytime soon. 

5/15/2017 1:25 AM

 **mhough** :

 >Finite element modeling/models. It's a means of computing realistic physics solutions when you have complex structure like the head as opposed to 3 or 4 concentric spheres 

5/15/2017 2:14 AM

 **aj** :

 >i like magnets as a solution to the hair problem

5/19/2017 9:26 PM

 **aj** :

 >New ganglion firmware adds wifi shield plug and play features that give uncompressed streaming data of 200/400/800/1600/3200/6400/12800/25600Hz - beta test ongoing.. stay tuned!

5/19/2017 9:27 PM

 **aj** :

 >Same deal with cyton but variable sample rates up to 16000hz for 8 chan or 8000hz for 16 chan

5/19/2017 9:27 PM

 **aj** :

 >It's a little http sever running on your head 

5/19/2017 9:28 PM

 **aj** :

 >Head over to the learning section of <http://OpenBCI.com|OpenBCI.com> to see all the new wifi overviews and tutorials

5/19/2017 9:29 PM

 **yannick** :

 >Then ARM will acquire your shield and it will be a little http server running in our head :slightly_smiling_face:

> 
What can possibly go wrong?

5/19/2017 10:34 PM

 **aj** :

 >So many things

5/19/2017 10:34 PM

 **aj** :

 >We gotta lock it down

5/19/2017 10:34 PM

 **aj** :

 >But hey, that's why I open source this stuff!

5/21/2017 7:33 AM

 **niouby** :

 >Hi everybody, my name is Morgane and I am a french student. For a project with my school, I have got a MUSE and I tried the EEG101 application and it's very interesting! I have some questions about how the code works with react native

5/21/2017 5:15 PM

 **octonomy** :

 >Hi niouby just to let you know most people here might not have that much experience with web related concepts like react native or even react at all. More common here is use of scientific programming libraries. Most here use Python and/or matlab. So in regard to your question about muse, what about the code do you need to connect to react native? Is it safe to assume you're looking for a way to get a stream of json data to flow from muse sdk to your react native app?

5/21/2017 5:41 PM

 **niouby** :

 >Hi octonomy, thanks for your reply. My problem is the following: I want to use the EEG 101 app for my project. I need to modify it so I started to do something simple: modify the text shown when you open the app. However, if I recompile and run the app after changing the JavaScript file where the text is written, my modification are ignored.

5/21/2017 5:49 PM

 **octonomy** :

 >for this, i cant help, i have not worked with Muse much, and have not used the EEG 101 app. Perhaps someone else can help. If oyure making mods and it doesnt show up, there could be a few different things going on, maybe youre in the wrong file, maybe the compilation needs to be set to development in order for your changes to be picked up (like in python), or maybe something else. hope someone on here who has worked with the Muse might be able to help.  Otherwise, is there any place on the muse site where they walk you through making changes to the app?

5/21/2017 5:55 PM

 **niouby** :

 >Someone advised me to talk to Dano (I'm looking for his answer). I haven't found yet. I'm going to try some IRC channels. Thank again :slightly_smiling_face:!

5/22/2017 5:39 AM

 **pierre** :

 >niouby the relevant channel is <#C0K883P71|interactive-tutorial> , if you're still looking, I noticed you haven't posted there 

5/23/2017 8:28 AM

 **jmhorschig** :

 >aj, the only 'customer priced' fnirs device available is from <http://foc.us|foc.us> - the openbci documentation looks legit. Otherwise, there is nothing out there (apart from individual academic groups working on fNIRS). A word of advice: skip the EROS tale...

5/23/2017 10:53 AM

 **yannick** :

 ><http://foc.us|foc.us> doesnt do fNIRS. Do they? They do tDCS (tCS) and recently added EEG, but fNIRS thatd be new information for me.

5/23/2017 10:55 AM

 **benjamindeleener** :

 >yannick seems like the focus EEG Dev Kit has fNIRS capabilities, as they sell fNIRS sensors along with the kit: <https://world.foc.us/eeg>

5/23/2017 10:58 AM

 **yannick** :

 >Yeah you are right! I had forgotten about it. Has anyone seen any post / project / paper using the <http://foc.us|foc.us> fNIRS ?

5/23/2017 12:50 PM

 **dano** :

 >That sounds awesome. Would love to get one to play with

5/23/2017 1:52 PM

 **jmhorschig** :

 >yannick: no, it's quite new and we're astonished by the low price - we do not have any more info. If anyone has experience or data, I'd be happy to be invited to chat.

5/23/2017 2:01 PM

 **jmhorschig** :

 >aj: finite element model - it's a physical model that can be used to describe properties of different tissues, e.g. optical scattering and absorption. You can think of it as a 3D model of vertices, where each vertex has additional properties that can later be used by some algorithm to e.g. compute photon migration.

5/31/2017 9:15 AM

 **stephen** :

 >Does anyone know why TMS machines are so expensive? 

> 


> 
This article suggests

5/31/2017 11:25 AM

 **jmhorschig** :

 >stephen <http://open-rtms.sourceforge.net/about.html> 

> 
it's expensive, because machines are expensive, because it's complicated to make these, and especially make usage safe.

5/31/2017 11:25 AM

 **jmhorschig** :

 >and of course because people like to make money

5/31/2017 11:26 AM

 **alexandre.barachant** :

 >also, it is expensive because the market is small, so you can't save cost by sacling manufacturing

5/31/2017 11:28 AM

 **alexandre.barachant** :

 >and also medical market is a bit weird in terms price self-regulation

5/31/2017 11:33 AM

 **stephen** :

 >Thanks jmhorschig and alexandre.barachant!

5/31/2017 11:36 AM

 **alexandre.barachant** :

 >especially in the US, where there is not that much regulation or incentive to put a fair price on the intervention or drug. Company basically try to extract as much as they can from the insurance.

5/31/2017 11:38 AM

 **alexandre.barachant** :

 >what i'm saying is that even if the price of the machine was 100$, the daily session might still be 200 to 300$

5/31/2017 7:50 PM

 **sydneyneurotechx** :

 >Another example of another technology that is expensive versus the cost of the BOM would be ultrasound. alexandre.barachant mentioned the reason, but it's interesting that there are a lot of technologies out there that can hypothetically be disrupted.  <https://maori.geek.nz/why-are-ultrasound-machines-so-expensive-623ce91d8402>

6/1/2017 1:28 PM

 **ntremblay_neuroservo** :

 >Hello NeuroTechX community,

> 
 

> 
As a NeuroTechX member myself, I would like to offer to the NeuroTechX community a dedicated member discount applicable to NeuroServo Product.

> 
 

> 
NeuroServo has developed a baseball cap with proprietary EEG device integrated. This device output raw data at 2048Hz when connected with the NeuroServo Development Kit. With this development kit, you can easily build your own tools for study groups, neuromarketing, classroom activities, games, cognitive studies and more! NeuroServo driver is already integrated in the latest version of OpenVibe software and C#/C++ sample code for communication is available upon request.

> 
 

> 
By using the PROMO code NTXJUNE2017, NeuroTechX members will obtain exclusively the development module for free when they buy the NeuroServo device (offer valid for June 2017 only).

> 
 

> 
<https://www.neuroservo.com/en/product/dev>

> 
 

> 
Cheers!

> 
Nicolas.

6/2/2017 3:47 PM

 **tonyb** :

 >Hey folks! I'm Tony Balbin of <http://warrior.do|warrior.do>. I'm in the process of creating a VR meditation app, and have a Muse headband to do research on users of the app. Does anyone have recommendations for a non-programmer to record and visualize EEG data? Any pointers would be greatly appreciated!  :slightly_smiling_face:

6/2/2017 6:10 PM

 **dano** :

 >You've come to the right place!

6/2/2017 6:12 PM

 **dano** :

 >There's a few different ways to record and work with Muse data. One is the official Muse research tools, but those won't work well unless you have an old model Muse (no power symbol on power button) <http://developer.choosemuse.com/research-tools>

6/2/2017 6:13 PM

 **dano** :

 >If you have a Muse 2016 and want to work with live Muse data on your computer with Python, I'd suggest checking out alexandre.barachant's custom streaming code: <https://github.com/alexandrebarachant/muse-lsl>

6/2/2017 6:16 PM

 **dano** :

 >If you're interested in making an app and want to work with Android, I'd point you to one of our flagship NeuroTechX apps, EEG 101. It will allow you to record data from your headband to .csv files for prototyping analysis, and is open source so you could modify the app to suit your own purposes. We handle the tricky parts of connecting to the device and visualizing the data for you <https://github.com/alexandrebarachant/muse-lsl>

6/2/2017 6:22 PM

 **dano** :

 >VR is a bit of an unblazed trail, but lots of us here are interested in it. Muse has an SDK for Unity, the most popular VR engine, but there aren't many *good*open source examples of it in action. If it's something you're really interested in, you could definitely find a lot of support here for developing your own Unity app.

6/3/2017 1:28 AM

 **tonyb** :

 >Wow dano thanks so much for the information! Really helpful, I'll check it all out.  bhargava2566302 will definitely let you know.

6/4/2017 11:14 PM

 **chrisabbott** :

 >tonyb You could save yourself some time by purchasing this and using it with muse-lsl: <http://www.silabs.com/products/wireless/bluetooth/bluetooth-low-energy-modules/ble121lr-bluetooth-smart-long-range-module1>

6/5/2017 4:28 AM

 **tonyb** :

 >chrisabbott thanks for the recommendation. Unfortunately i have the older Muse model so it looks like the muse-lsl code won't work with it. But plus side is it's compatible with the Muse research tools, so will probably go that route.

6/5/2017 4:30 AM

 **tonyb** :

 >The app I'm developing is going to be geared towards the google cardboard platform and smartphones. I've been able to get away with using snap-in VR headsets alongside the Muse

6/5/2017 4:42 AM

 **chrisabbott** :

 >tonyb: Ah okay, that makes a lot more sense. You might run into some issues with those front electrodes though. There's way more support for the 2014 model than the 2016, so you're at an advantage in that regard

6/5/2017 8:16 AM

 **mhough** :

 >There is going to be a workshop on dry electrodes at the end of the summer for those interested and able to make it

6/5/2017 8:16 AM

 **mhough** :

 ><https://goo.gl/H1GDaL>

6/5/2017 7:47 PM

 **naoto** :

 >I just bought an OpenBCI Ganglion and trying to connect to Surface Pro 4. SP4 seems to support Bluetooth 4.0, but the OpenBCI GUI tool (specifically GanglionHub.exe) says "Uncaught Exception: Error: No compatible USB Bluetooth 4.0 device found!" Am I missing a setup procedure or do I need to purchase a USB dongle?

6/5/2017 9:12 PM

 **andrewjsauer** :

 >naoto i think you are good on the USB dongle. i purchased a ganglion as well and didn't have issues connecting to my Samsung S6

6/5/2017 9:12 PM

 **andrewjsauer** :

 >naoto i think you are good on the USB dongle. i purchased a ganglion as well and didn't have issues connecting to my Samsung S6

6/5/2017 9:12 PM

 **andrewjsauer** :

 >my guess is surface pro 4 does not support bluetooth 4.0

6/5/2017 9:12 PM

 **andrewjsauer** :

 >:shrug:

6/5/2017 9:13 PM

 **naoto** :

 >what is the app you used with the samsung phone?

6/5/2017 9:17 PM

 **naoto** :

 >andrewjsauer SP4 supports 4.0 according to microsoft, but not sure about BLE. Anyways, Windows with Bluetooth is always a pain to setup so maybe I should use other os

6/5/2017 9:33 PM

 **andrewjsauer** :

 >i've been working on an android app and my first goal was to get the two to connect and it worked

6/5/2017 9:33 PM

 **andrewjsauer** :

 >but that's strange...

6/5/2017 9:34 PM

 **andrewjsauer** :

 >yeah, let me know what your results are with another OS

6/6/2017 6:14 PM

 **naoto** :

 >andrewjsauer I got it working on my Raspberry Pi 3 with OpenBCI_Python. I will forget about windows and BLE...

6/6/2017 10:01 PM

 **andrewjsauer** :

 >sweet, :+1:

6/6/2017 10:01 PM

 **andrewjsauer** :

 >naoto what are you building? or you just messing around?

6/7/2017 4:17 AM

 **naoto** :

 >andrewjsauer I'm working on projects like this <http://naotohieda.com/muse/> <http://naotohieda.com/eegexp/>

6/7/2017 1:28 PM

 **lubo** :

 >What do you guys think of Neuroon Open: <http://kickstarter.neuroon.com/sleep-hackers>

6/8/2017 7:08 AM

 **mhough** :

 >naoto thats awesome. what you using for the OS on the raspi3? I am hoping a fedora or ubuntu mate?

6/8/2017 7:13 AM

 **mhough** :

 >tonyb yes something with google cardboard would be good for the experimental control system I always thought. Anyone tried to run psychopy on Android? Definitely want to do SSVEPs to one eye and the phone connects to the raspi3 running the DAQ. Its mounted on top of the ganglion board for instance

6/8/2017 3:16 PM

 **naoto** :

 >mhough: mine is raspbian 8

6/8/2017 4:01 PM

 **mhough** :

 >Thanks naoto. It would be great to see those interested in an ARM branch of neurodebian use ubuntu 16.04/mate as its pretty responsive as a desktop. Any of the neurodebian supported OS versions would do though. I know dmitryneuro is interested and Anderson Winkler at FMRIB has some posts on getting neurodebian packages running on ARM. Its probably outdated and maybe they are already doing this but I would like to help an effort to get this officially supported on at least a couple of reference boards including Qualcomm's one.

6/9/2017 12:04 PM

 **francescacoo** :

 >Muse: hi guys, few months ago my Muse broke while under warranty. They sent me a new one and it is a Muse 2016. Since then I never tried the research tools SDK anymore, but I discovered yesterday that it is not supported on Muse 2016 :open_mouth: any workaround?

6/9/2017 12:11 PM

 **alexandre.barachant** :

 >francescacoo : <https://github.com/alexandrebarachant/muse-lsl>

6/9/2017 12:11 PM

 **francescacoo** :

 >alexandre.barachant: wohooo that's great alexandre! Thanks a lot!

6/9/2017 12:11 PM

 **alexandre.barachant** :

 >francescacoo : <https://github.com/urish/muse-js>

6/9/2017 12:12 PM

 **alexandre.barachant** :

 >my code is in python, and if you don't use linux (windows or MacOS), you will have to buy a BLED112 dongle

6/9/2017 12:13 PM

 **francescacoo** :

 >I am on Linux

6/9/2017 12:13 PM

 **alexandre.barachant** :

 >i did not tried muse-js, but it might have a better os support

6/12/2017 2:50 PM

 **ben.cuthbert** :

 >mhough: this link is broken- is the workshop still happening? Where is it?

6/14/2017 5:04 PM

 **aj** :

 >Just ordered the first batch of production OpenBCI Wifi Shields! Should be on sale within a month or so. Adding features to the firmware for the next two weeks, if you have any requests (i.e. features that will ship with the default firmware) (e.g. marion and I are making a direct to cloudbrain feature that has a login page and everything on the default firmware)

6/14/2017 5:06 PM

 **aj** :

 >Pretty sure they will cost $119.99 per board

6/15/2017 11:37 AM

 **mesca** :

 >aj Where can I buy it? I cant find any link on the OpenBCI or PTW websites.

6/15/2017 11:37 AM

 **mesca** :

 >Also: is it compatible with the 16-channel setup (Cyton + Daisy)?

6/15/2017 11:38 AM

 **aj** :

 >The boards are being made right now !

6/15/2017 11:38 AM

 **aj** :

 >Available in about a month

6/15/2017 11:39 AM

 **aj** :

 >And yes fully compatible with ganglion, cyton, cyton+Daisy

6/15/2017 11:40 AM

 **mesca** :

 >Great! Cant wait :wink:

6/15/2017 10:21 PM

 **aj** :

 >Just found myself defending muse for the first time when they were called a marketing company. I was like hold the fuck up they mastered conductive rubber electrodes and made a EEG headset people can put on. Plus they have cool neuroscientists working for them contributing to open source where possible

6/16/2017 12:41 AM

 **maxim** :

 >aj, any links to those open source things? Are those unofficial Muse BLE connection libs on github actually by people connected with Muse?

6/16/2017 1:42 AM

 **aj** :

 >Mine has some commits

6/16/2017 11:46 AM

 **yannick** :

 >Some of you might be interested by this Low Cost BCI paper <http://ieeexplore.ieee.org/document/7851005/>

6/16/2017 1:56 PM

 **sc** :

 >Ha yes, very close to the original in-place laplacian I was going for (c:

6/17/2017 6:16 PM

 **mhough** :

 >Damn yannick that's cool. sc are you doing multimodal?

6/18/2017 1:18 AM

 **aj** :

 >that is really cool

6/18/2017 1:18 AM

 **aj** :

 >i thought nir didnt work through hair

6/21/2017 1:08 PM

 **javi_neuralcubes** :

 >We're trying give a push to the <#C1G552DD4|smartphone-bci> project, now known as icibici (pronounced as easy-bisi) for that we're going to order some pcbs of the project in bulk. We are wondering if anyone would be interested in getting some for organising hackathons for their chapters, or just to play around a bit. Also we're trying to get some funding to give the project a bit of push, anyone knows any good opportunities or interested bodies yannick sydneyneurotechx?

> 
Thanks a million!

6/21/2017 1:09 PM

 **javi_neuralcubes** :

 >also we're planning on using pcbGOGO, some knows any other good service that we can use?

6/21/2017 1:10 PM

 **javi_neuralcubes** :

 >Depending on the amount we order the price of each device will be in the range of $14-$16

6/21/2017 1:13 PM

 **alexandre.barachant** :

 >for PCB, oshpark is great

6/21/2017 1:14 PM

 **alexandre.barachant** :

 >i had good results with seeedstudio too

6/21/2017 4:45 PM

 **aj** :

 >i have had perfect success with <http://pcb-pool.com|pcb-pool.com>

6/21/2017 5:54 PM

 **sydneyneurotechx** :

 >hey javi_neuralcubes we can do a call about it and see what we can uggest

6/21/2017 6:58 PM

 **japesinator** :

 >3pcb and dirtypcbs can both do good work for super cheap

6/23/2017 12:15 AM

 **naoto** :

 >I don't know if it's packet loss but I had some bad issues with packet loss on Linux <https://github.com/OpenBCI/OpenBCI_Python>

6/23/2017 12:21 AM

 **yrenard** :

 >could also be reference electrode popping

6/23/2017 1:56 AM

 **dano** :

 >naoto: I am on Linux

6/23/2017 1:56 AM

 **dano** :

 >yrenard: The references are the ear clips, right? Any way to improve their connection? I did notice high impedence for them

6/23/2017 2:24 AM

 **yrenard** :

 >yes, I guess this is the earclips - I think some people are adding some saline solution or gel on them, and you can also clean the ear lobe with alcohol prior to applying the electrode, but electrode pop is not exactly similar to impedance issues, it might more be that the electrode is moving a little bit or that the conductive surface loses connection with the skin from time to time

6/24/2017 12:25 AM

 **eferdinand** :

 ><http://kickstarter.neuroon.com/sleep-hackers>

6/24/2017 12:27 AM

 **eferdinand** :

 >Anyone has updates about this, it's been planned for a while now

6/24/2017 5:45 AM

 **aj** :

 >dano that's super strange you should reach out to OpenBCI!

6/24/2017 5:46 AM

 **aj** :

 >That high ref impedance is troubking

6/24/2017 5:46 AM

 **aj** :

 >What does the data look like with no electrodes? This would not be a firmware issue

6/24/2017 5:46 AM

 **aj** :

 >The newer firmware has no compression differences

6/24/2017 12:35 PM

 **javi_neuralcubes** :

 >sydneyneurotechx how's your availability this week?

6/24/2017 12:35 PM

 **javi_neuralcubes** :

 >It'd be great to have a chat

6/24/2017 3:03 PM

 **aj** :

 >javi_neuralcubes you should sell them on the OpenBCI online store!

6/24/2017 3:03 PM

 **aj** :

 >Would be the only single channel device

6/24/2017 3:10 PM

 **yannick** :

 >javi_neuralcubes I hope well sell them on the NTX store :wink:  

> 
(new feature of NTX website 2.0 soon to be released)

6/25/2017 2:44 PM

 **aj** :

 >Hi all! I would love feedback on the OpenBCI wifi shield http rest server protocol!! <https://app.swaggerhub.com/apis/pushtheworld/openbci-wifi-server/1.1.0> 

6/25/2017 2:45 PM

 **aj** :

 >I'm finalizing the 1.0.0 firmware June 30th!

6/26/2017 2:38 PM

 **javi_neuralcubes** :

 >yannick that's a great idea!

> 
aj what kind of process should we follow to sell it at the openbci store

> 
also, this is a kind of super dyi thing, we haven't  gone through any kind of quality testing/regulation stuff... how does the liability works with you guys :smile:

6/26/2017 2:39 PM

 **javi_neuralcubes** :

 >andt thanks alexandre.barachant

6/26/2017 4:37 PM

 **dano** :

 >I'll try and use the same ganglion with a PC and see if I get the same error

6/26/2017 5:23 PM

 **bhargava2566302** :

 >does muse has a warranty because mine was broken which about like 3 months old

6/26/2017 7:31 PM

 **aj** :

 > dano yes please try and use another PC!

6/27/2017 9:43 PM

 **sydneyneurotechx** :

 >Neuroon Open has launched an open source eeg for sleeping. <https://www.kickstarter.com/projects/intelclinic/neuroon-open-smartest-sleep-dreams-and-meditation>

6/27/2017 9:44 PM

 **sydneyneurotechx** :

 ><!channel>  anyone in NeuroTechX associated with them??

7/4/2017 12:40 PM

 **sydneyneurotechx** :

 >Any details on this MRI machine? How does it compare to other models? <http://www.bbc.com/news/health-40488545>

7/4/2017 12:50 PM

 **benjamindeleener** :

 >sydneyneurotechx it is simple a 7T MRI machine. Still for research and coming slowly into clinics. What they used is state-of-the-art fiber tractography on high-resolution diffusion MRI.

7/4/2017 12:50 PM

 **benjamindeleener** :

 >The high magnetic field allows higher resolution and contrast while reducing the scanning time.

7/4/2017 12:51 PM

 **benjamindeleener** :

 >I believe McGill will receive its own 7T MRI scanner pretty soon :slightly_smiling_face:

7/4/2017 12:52 PM

 **benjamindeleener** :

 >I would be happy to discuss more MRI stuff if there are interested people

7/4/2017 12:55 PM

 **sydneyneurotechx** :

 >benjamindeleener: Neat! Was reading up wikipedia and there was mention that up to 9.4 T has been used on humans. <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4406343/>

> 


> 
What does higher Tesla values provide? More resolution?

7/4/2017 1:01 PM

 **benjamindeleener** :

 >sydneyneurotechx Yes, basically higher resolution because it increase the signal-to-noise ratio (so you can go in higher res with the same SNR). These machines usually also comes with better gradients, which improves many things, such as sensitivity in diffusion MRI.

7/4/2017 1:01 PM

 **benjamindeleener** :

 >However, increasing the magnetic field also increase the risks for the patients (mainly heat risks)

7/4/2017 1:02 PM

 **benjamindeleener** :

 >And the usual rule of 1M$ per Tesla still applies

7/5/2017 5:34 PM

 **bciguy** :

 >sydneyneurotechx: Im in touch with them, however we already have a device that provides this open framework. Happy to discuss further.

7/6/2017 9:35 AM

 **timfiori** :

 >Has anyone used the <http://foc.us|foc.us> fNIRS sensors yet? Looks like it was discussed in the group in May last, I'm wondering if anyone has had any experience with them yet. I'm looking into fNIRS devices and <http://foc.us|foc.us> is the only one that fits the budget!

7/6/2017 9:22 PM

 **mhough** :

 >timfiori yeah I was hoping to but haven't yet. Is there anything special you need from them?

7/6/2017 9:25 PM

 **mhough** :

 >sydneyneurotechx benjamindeleener 7t doesn't improve everything yet. Diffusion is one of those things that works well. T1s not so much:) I wonder which package they used for tracking.

7/7/2017 8:42 AM

 **jmhorschig** :

 >timfiori I know no one with that device and haven't read anything here thus far. If you buy it, please share your experience. But, to ease your mind, it is actually the only device on the market that cheap - the only other cheap option is to make it yourself (<http://opennirs.org/>). I am also not aware of any development from any other company to make a consumer fnirs product in near future (we definitely don't).

7/7/2017 4:26 PM

 **timfiori** :

 >mhough I don't need anything specific at this stage apart from affordability! It's more for experimentation. I've had bad experiences with <http://foc.us|foc.us> hardware breaking but I'll likely order a set and will let everyone know how it goes

> 


> 
jmhorschig opennirs looks promising from the documentation, have you had experience with it?

7/7/2017 4:31 PM

 **yrenard** :

 >timfiori I know about NIRx in Germany, they have good reputation, I haven't used their device though and have no idea of the price

7/7/2017 9:42 PM

 **a.tech** :

 >timfiori Biopac also has an affordable fnir device <https://www.biopac.com/knowledge-base/fnir-faq/>

7/9/2017 10:04 AM

 **alexandre.barachant** :

 >hey all, I have to find a name for my open hardware EEG project, but i'm not very inspired. Any idea ?

7/9/2017 5:25 PM

 **urish** :

 >Hi Alex! Is this a open hardware EEG headset?

7/9/2017 5:46 PM

 **alexandre.barachant** :

 >urish soon to be open. I procrastinated the source release (one reason being i can't find a nice name for the project)

7/9/2017 5:47 PM

 **alexandre.barachant** :

 >its mainly an amplifier, but I also want to propose plan for a cap and electrodes

7/9/2017 8:22 PM

 **urish** :

 >What kind of name are you looking for? fun name? something with more professional sound?

7/9/2017 10:56 PM

 **dano** :

 >timfiori: Super curious about this as well. We should really put together a pitch and ask <http://foc.us|foc.us> for a free device to hack on

7/9/2017 10:58 PM

 **dano** :

 >:brain: storming

7/9/2017 10:59 PM

 **dano** :

 >Is this the AlexEEG?

7/10/2017 6:50 AM

 **jmhorschig** :

 >timfiori NIRx, not good, better check out <http://www.artinis.com|www.artinis.com> ;) that's where I am working at (Dutch company). NIRx is actually a US company with a German office in Berlin. I'd say their devices are okay, but obviously ours are better. Pricewise they are much too expensive for a consumer product though, with their cheapest device around 40k$. Our cheapest (single channel) is around 12k$, multichannel 20k$. This is really cheap for a research-grade device, but definitely not suited for regular consumers.

7/10/2017 6:53 AM

 **jmhorschig** :

 >a.tech similar prices there as far as we know, something around 30k$? Plus, the Biotech devices have a really low sample rate (1Hz), so I cannot recommend their devices. SNR seems good though, and it's roughly portable at least - but not as good and portable as our products ofc' ;) Just adding to that disclaimer, I am happy about anyone using NIRS, no matter what device.

7/10/2017 6:55 AM

 **jmhorschig** :

 >timfiori no, never tried, but seems legit. Was part of a guys Master's thesis who is working with really knowledgable researchers in Berlin on his PhD (EEG+fNIRS) now. I never met him, but talked to his supervisors. Seems to me though that he's the kind of guy that you can walk up to and ask for a bit of help.

7/10/2017 8:19 AM

 **alexandre.barachant** :

 >dano yes, the amplifier and cap developed in this project is the "AlexEEG" from my blog. 

> 
urish i'm looking for any name really. uninspired name with Open* and Free*  are already taken.

7/10/2017 8:47 AM

 **urish** :

 >alexandre.barachant here are a few ideas: BrainLogger, LibreEEG, EEGenius, HomeEEG, EEG4All, PersonalEEG, WaveWare, ThoughtMaster

7/10/2017 9:21 AM

 **alexandre.barachant** :

 >nice, thanks !

7/10/2017 9:32 AM

 **jmhorschig** :

 >chantEEG?

7/10/2017 2:40 PM

 **dano** :

 >WaveWare is nice!

7/10/2017 11:22 PM

 **yannick** :

 >abEEG. A Better EEG :wink:

7/11/2017 5:53 AM

 **timfiori** :

 >jmhorschig: thanks for all the advice! We're not quite ready to commit to the price of a higher quality device so will likely pick up the <http://foc.us|foc.us> fNIRS system. Very interested in having a go at the opennirs device in the future

7/11/2017 7:09 AM

 **jmhorschig** :

 >I see, prices are really very crazy on the research market - but then againt it's a small niche and all the R&amp;D costs need to be covered to maintain a sustainable business. At least there are no bullshit companies out there, which flood the market with cheap and nonworking devices. Not sure about the focus though ;) Would you mind sending me a snippet of data once you got some? I am really curious about the data quality.

7/11/2017 11:41 PM

 **marion** :

 >Shout-out to <http://autodidactes.io|autodidactes.io> for their awesome Bcibox. I just got mine and I'm loving it. <http://www.autodidacts.io/bcibox-open-source-openbci-enclosure/>

7/14/2017 1:36 AM

 **timfiori** :

 >Sure, will definitely make some data available. I find it's hard to know what you're getting with focus products since there isn't a lot of documentation or many reviews out there

7/16/2017 12:05 AM

 **bhargava2566302** :

 >Does anyone had an 3d printed small or medium size

7/16/2017 12:05 AM

 **bhargava2566302** :

 >Openbci headset

7/16/2017 7:56 AM

 **aj** :

 ><http://g.recordit.co/kbmf9UpU2x.gif>

7/16/2017 7:56 AM

 **aj** :

 >250Hz 16 channels over wifi

7/16/2017 7:57 AM

 **aj** :

 >should i try 1000Hz??

7/16/2017 8:41 AM

 **mhough** :

 >aj yes, yes you should:)

7/16/2017 4:41 PM

 **aj** :

 >mhough totally works

7/16/2017 4:41 PM

 **aj** :

 >epiccc

7/16/2017 4:43 PM

 **mhough** :

 >Nice!

7/16/2017 7:05 PM

 **aj** :

 >Ganglion following in at 1600Hz

7/17/2017 8:05 PM

 **andrewjsauer** :

 ><!here|@here> Has anyone looked into / built a non-research EEG device for dogs? (minus the No More Woof spat) Looking into making one but with all the challenges to overcome I'm not sure if it's even feasible, curious if anyone here has an opinion on the matter.

7/17/2017 8:09 PM

 **dano** :

 >Haha, maybe dog EEG should remain a cautionary tale

7/17/2017 8:11 PM

 **andrewjsauer** :

 >Haha, fair. I mean, it would be interesting done right

7/17/2017 8:15 PM

 **sydneyneurotechx** :

 >andrewjsauer  if you are able to access this publication, I'd love to know the results of this study :smile: <http://onlinelibrary.wiley.com/doi/10.1111/j.1748-5827.1962.tb04189.x/full>

7/17/2017 8:47 PM

 **andrewjsauer** :

 >accessed. the procedure indicates they inserted the electrode under the skin using a needle. not sure if the market is ready to be inserting electrodes into their pets, yet..  :sunglasses:

7/18/2017 12:38 AM

 **mhough** :

 >andrewjsauer actually the market is:) meaning that for vets yes. Owners too in the sense that once you've seen your pet seize multiple times that doesn't seem so bad. It's how you do research EEG on non-human primates etc. Not sure what problems you are facing though. Does it need to have high-density? Does it need to be long-term? You can shave sites for recordings if you want to stay transdermal but the electrodes will still be pretty irritating. Dogs are going to try and take it off if not restrained. How did this thread get so weird;)

7/18/2017 12:39 AM

 **mhough** :

 >Dog fmri is awesome so canine EEG needs to catch up. Cool thing is that it's easy to get CTs of them

7/18/2017 4:27 AM

 **yannick** :

 >I hope that you are not just teasing us with exciting EEG board images... But that you are gonna tell us more about it! :slightly_smiling_face:

7/18/2017 7:11 AM

 **dmitryneuro** :

 >It was assembled and now work as planned and even better. After some hacks needed to start it up, because some components was not tested completly in that configuration. Hacks was: USB connector pin 4 to 5, UART isolation power source from 5V to WIFI 3V3, WIFI RESET pin to EN pin, WIFI GPIO15 pin to GND. Changes will be commited in FreeEEG32 beta.

7/18/2017 8:48 AM

 **alexandre.barachant** :

 >dmitryneuro very nice !

7/18/2017 2:23 PM

 **sydneyneurotechx** :

 >aj  Check it out ^

7/18/2017 2:23 PM

 **sydneyneurotechx** :

 >great job dmitryneuro

7/18/2017 7:15 PM

 **andrewjsauer** :

 >mhough oh good point! yeah, looking at transdermal long-term use as i think that'd be really interesting data. shaving a site for recordings is definitely an option, i'm wondering if it's possible without though :thinking_face:

7/19/2017 6:41 AM

 **mhough** :

 >andrewjsauer it's certainly possible. If the coats pretty amenable, youve got a custom "cap" which is easy and some spiky electrodes. It's a common design choice for handling hair. Dry or wet. You would need a cone to protect them or a lot of pretraining to get them used to the equipment. 

7/19/2017 6:42 AM

 **mhough** :

 >Great work dmitryneuro 

7/19/2017 5:58 PM

 **graeme** :

 >alexandre.barachant the worst name in history, just as a warning, is the one from Lyon group: OpenElectrophy

7/20/2017 2:21 AM

 **a.tech** :

 >super cool dmitryneuro

7/20/2017 2:39 AM

 **andrewjsauer** :

 >Agreed, interesting / fun challenges indeed!

7/20/2017 6:28 AM

 **aj** :

 >Where are you sourcing them from?? I can't find a good source. Tried getting a bunch off eBay (we had gotten 10 prior and all worked) and 4/4 random samples failed to boot.

7/20/2017 6:31 AM

 **aj** :

 >The esp8266

7/20/2017 7:49 AM

 **dmitryneuro** :

 >on aliexpress.

> 


> 
have made broken parts by myself.

> 
as i remember,

> 
1) placing in reset mode on NodeNCU to get cp2102 work as only usb-uart for MCU&lt;-&gt;PC data transfer needs, make 3 esp8266 modules go to overheat and stop responding to anything. so now made reset and enable pins together, so as i learn from that 3, reset alone for a long time without enable pin switched with reset is the way to kill esp8266.

> 
2) in first design of FreeEEG32 board was no esp8266, so uart isolation with 5v power worked fine. but when i added esp8266, not made test, and appeared that esp8266 tx and rx not 5v tolerant, so now this esp8266 3 modules only load firmware but firmware failing somewhere, and leave light diode turn on on esp-12f after flashing

7/20/2017 7:39 PM

 **aj** :

 >Get esp8266 from Mouser! The adafruit 12s it's working so well!

7/20/2017 7:40 PM

 **aj** :

 >But it's individually packaged :(

7/21/2017 1:43 PM

 **alexandre.barachant** :

 >just received my test board assembly. 8 channel

7/21/2017 5:31 PM

 **aj** :

 >Sick!!

7/22/2017 1:01 PM

 **mhough** :

 >Nice!

7/24/2017 8:33 AM

 **urish** :

 >alexandre.barachant is that ESP32 you are using there?

7/24/2017 8:34 AM

 **alexandre.barachant** :

 >yep.

7/24/2017 8:34 AM

 **alexandre.barachant** :

 >i tried the board for the first time yesterday. Got some nice EEG :slightly_smiling_face:

7/24/2017 3:22 PM

 **alexandre.barachant** :

 >some fresh EEG (alpha wave)

7/24/2017 9:52 PM

 **urish** :

 >awesome!

7/24/2017 9:52 PM

 **urish** :

 >which code are you running inside?

7/24/2017 10:25 PM

 **alexandre.barachant** :

 >Arduino core. The esp takes care of configuring the ADC, data collection and transfer.

7/24/2017 10:27 PM

 **alexandre.barachant** :

 >I'm using WiFi only so far. But the esp32 also do BLE.

7/25/2017 8:56 PM

 **aj** :

 >I just wrote my first medium article

7/25/2017 8:56 PM

 **aj** :

 ><https://medium.com/@pushtheworld_aj/how-i-write-stable-arduino-code-actual-exmaples-and-rational-63dd5def2db8>

7/27/2017 1:46 PM

 **alexandre.barachant** :

 >what are the cool features you want to see on a EEG amplifier ?

7/27/2017 4:45 PM

 **aj** :

 >One that does not rail

7/27/2017 4:45 PM

 **alexandre.barachant** :

 >:slightly_smiling_face: i mean, beside being able to record EEG

7/27/2017 4:46 PM

 **aj** :

 >But it's an EEG amplifier lol why else would I get it? Do you mean emg? Or like is setting gain important?

7/27/2017 4:46 PM

 **alexandre.barachant** :

 >oh, i mean if it rail, then you can't record EEG

7/27/2017 4:48 PM

 **alexandre.barachant** :

 >i'm more interesting in knowing what kind of extra feature is important.

7/27/2017 4:48 PM

 **alexandre.barachant** :

 >like SD card, trigger channels, wired connection in addition to wifi, etc

7/27/2017 4:49 PM

 **alexandre.barachant** :

 >on board lipo charger

7/27/2017 4:54 PM

 **aj** :

 >I real time clock

7/27/2017 4:54 PM

 **aj** :

 >Next EEG I build will have one

7/27/2017 4:55 PM

 **alexandre.barachant** :

 >a rtc ?

7/27/2017 4:55 PM

 **alexandre.barachant** :

 >there is one in the esp32 i think

7/27/2017 4:56 PM

 **aj** :

 >Yea an rtc

7/27/2017 4:57 PM

 **aj** :

 >I think that could be the key to time syncing

7/27/2017 4:57 PM

 **aj** :

 >Also I way for the EEG board to take a photo resistor and hook it up to the screen to verify time sync with stims

7/27/2017 4:58 PM

 **alexandre.barachant** :

 >so that's a hardware trigger

7/27/2017 4:58 PM

 **alexandre.barachant** :

 >you dont need RTC to sync, you just need a counter

7/27/2017 4:59 PM

 **alexandre.barachant** :

 >but there is one RTC on the ESP32. it think there is even NTP sync

7/27/2017 5:02 PM

 **alexandre.barachant** :

 >so aj say hardware triggers and RTC. anyone else ?

7/27/2017 5:02 PM

 **aj** :

 >The drift with an rtc is much slower

7/27/2017 5:02 PM

 **aj** :

 >That's all

7/27/2017 5:02 PM

 **aj** :

 >That's the benefit

7/27/2017 5:07 PM

 **alexandre.barachant** :

 >hum, i'm not sure about that. the drift is slower if the ocillator is good

7/28/2017 12:35 AM

 **yrenard** :

 >I second alexandre.barachant on that one :wink:

7/30/2017 3:23 PM

 **sc** :

 >alexandre.barachant heres a riff on Yannicks name suggestion: abcdEEG & it kinda rolls off the tongue to native English speakers. Could stand for nothing (just mean to be simple as ABCs) or an acronym like A Better C Device .. or Alexandre Barachats C Device etc. & not sure what the C stands for & Connect? Computer? Cu-ality? (c:

7/30/2017 3:24 PM

 **alexandre.barachant** :

 >sc thanks :slightly_smiling_face:

7/30/2017 3:25 PM

 **sc** :

 >Alex Bs Cool Device!

7/31/2017 5:19 AM

 **aj** :

 ><https://medium.com/neurable/announcing-the-worlds-first-brain-computer-interface-for-virtual-reality-a3110db62607>

7/31/2017 5:19 AM

 **aj** :

 >Sickkkk

7/31/2017 5:20 AM

 **aj** :

 >Props to neurable for making it happen!

7/31/2017 5:21 AM

 **alexandre.barachant** :

 >The headset is nice ! Built by wearable sensing i guess

7/31/2017 5:23 AM

 **alexandre.barachant** :

 >but the article is overselling the tech way too much :astonished:

7/31/2017 5:29 AM

 **yannick** :

 >Great design guys (adamm_neurable, pharo et al.)

7/31/2017 3:20 PM

 **benjamindeleener** :

 >Announcing the worlds first brain-computer interface for virtual reality

> 
<https://medium.com/neurable/announcing-the-worlds-first-brain-computer-interface-for-virtual-reality-a3110db62607>

7/31/2017 4:20 PM

 **dano** :

 >Oooo

7/31/2017 4:45 PM

 **dano** :

 >alexandre.barachant, I think you're right. They say the Awakenings game that they released operates entirely without handheld controllers. With state-of-the-art active or reactive BCIs, I can't imagine that being anything but *frustrating*

7/31/2017 7:29 PM

 **bciguy** :

 >Its been a few years since I reviewed the lit but I believe the P300 is still the BCI modality with highest ITR (info transfer rate)

7/31/2017 7:29 PM

 **bciguy** :

 >hence its widespread adoption as the Go-To BCI modality

7/31/2017 8:31 PM

 **alexandre.barachant** :

 >Don't get me wrong here, I think P300 is great. For locked in and patients, it's one of the best modality.

> 


> 
But for healthy user, P300 is just a BCI gimmick. It's a glorified eye tracker without the accuracy. It does not provide any sense of "brain control". It allow you to select the item you are focusing your attention on.

> 


> 
I did my fair share of work about P300, (a post doc of almost 2 years) developing the algorithms of Brain invaders, one of the first P300 BCI video game.

> 
For a first time user, what is fun is the novelty, but after 10 minutes there is just no interest left.

> 


> 
So P300 is generally a gateway BCI, but the real $$$ are not on stimulation based BCI. For me it's a bit surprising that the neurable headset is only covering the visual cortex. i would have expected more coverage in order to be able to move on and extend they offers as soon as they get traction (and being able to deliver what they claim)

> 


> 
The design of this headset is great, and i'm sure they will end up with a great P300 BCI.

7/31/2017 8:41 PM

 **aj** :

 >The articles coming from demos are "damn it worked well" and "was shocked how well it worked"

7/31/2017 8:44 PM

 **alexandre.barachant** :

 ><https://www.youtube.com/watch?v=47WHqDNckI8>

7/31/2017 9:03 PM

 **alexandre.barachant** :

 >aj for sure it works :slightly_smiling_face: my point is not here, and I don't want to sound negative at all, this is a great piece of works. 

> 
What i'm saying is that there is a "wow, you can guess what i'm thinking" effect, but if you play it for the 10th time you quickly end up with "give me the mouse, it's faster to select what i want". 

> 
It's a cool gimmick, but i'm still a little bit puzzled about the long term vision

8/1/2017 4:55 PM

 **eferdinand** :

 >I heared about those guys when they first started, anyone is connected to them?

> 
<http://Smartcaptech.com|Smartcaptech.com>

8/2/2017 1:57 AM

 **jk** :

 >True. None of so-called bci demos has impressed me. I have yet to see one that is self-evident.

8/2/2017 3:47 AM

 **fred-simard** :

 >I did some business thinking about the idea of a hand-free BCI button selector and tried the HTC Vive. I concluded that the "laser" pointer and conventional controllers are well suited in many situations. I wish them the best thought, and yes it is a P300 speller.

8/2/2017 7:40 PM

 **bciguy** :

 >alexandre.barachant agreed, and I piloted numerous P300 studies during my doctoral studies. One specific study integrated more than one modality: for example we used SSVEP in addition to the p300 speller to improve accuracy, though only trivially  ( i think i still have the matlab  + psychophys. toolbox code if anyones interested..). The challenge with all of these modalities is still a low ITR compared to conventional control methods. I dont think anyone disagrees with you that current BCIs for healthy subjects dont offer better control - in any measure - beyond whats available via conventional HCI methods.

8/2/2017 7:43 PM

 **aj** :

 >They have some hold release functionality that is more interactive then P300

8/6/2017 2:01 PM

 **alexandre.barachant** :

 >a new board, 16 channels. more compact, and cheaper

8/6/2017 2:03 PM

 **alexandre.barachant** :

 >i made a small design error, so the noise is a little bit higer than expected, but i should fix it on the next iteration

8/6/2017 9:23 PM

 **perrotta** :

 >I want to record eeg data on myself during the day for several days. Has anyone ever worn an eeg device out and about all day? Any thoughts on devices that wont fall off my head and also hopefully dont become too uncomfortable?

8/6/2017 10:32 PM

 **ntremblay** :

 >Hello perrotta, take a look at <http://www.neuroservo.com|www.neuroservo.com>, this may be interesting for you.. 

8/7/2017 4:09 AM

 **perrotta** :

 >Thanks ntremblay! Ill check it out. Any others?

8/7/2017 4:30 AM

 **yrenard** :

 >Emotiv Epoc could be fine for 8h recording. Does not have SD so will need a bit of hacking to dump data on a mobile device

8/7/2017 4:33 PM

 **perrotta** :

 >thanks yrenard. Ive worn one before but never for an extended amount of time. Anyone have thoughts on the Emotiv Insight?

8/7/2017 5:10 PM

 **yrenard** :

 >less sensors, so depends what you are looking at and what you expect to capture. If sensors are well located given what you search, that might be a very good be

8/9/2017 8:16 PM

 **timopheym** :

 >alexandre.barachant looks cool, what rate? Is it open design?

8/9/2017 8:19 PM

 **alexandre.barachant** :

 >timopheym this design is running at 1000Hz, 16 channels, over wifi. The design will be open, but is not yet

8/9/2017 8:21 PM

 **timopheym** :

 >And what's the expected net price?

8/9/2017 8:36 PM

 **alexandre.barachant** :

 >I don't know, this is too early to tell, i'm still thinking about adding different feature that might increase the BOM

8/16/2017 8:46 AM

 **alexandre.barachant** :

 >harris how many channels are you thinking of ?

> 
there is 8 channels per ADC, and you can daisy-chain them.

> 
I'm thinking it should be possible to extend them to 32 channels without changing the design. After that you might need to rethink a few things.

8/16/2017 8:47 AM

 **alexandre.barachant** :

 >more specifically, use multiple SPI interface, buffer the ocilllator output, add another regulator, switch to a wired data interface

8/16/2017 9:47 AM

 **aj** :

 >I think we can get 32 over wifi

8/16/2017 9:48 AM

 **aj** :

 >I'm testing 24 soon and I'm not nervous about it, 16 streams fine

8/16/2017 9:48 AM

 **aj** :

 >Actually I could sim 32 and see if there are issues

8/16/2017 9:49 AM

 **aj** :

 >I think the connector needs to change after 16

8/16/2017 9:50 AM

 **aj** :

 >Using a 2.54 mm pitch header with differential input quickly turns into 66+ pins with after ref and bias and such

8/16/2017 9:50 AM

 **aj** :

 >That's a lot of area

8/16/2017 10:03 AM

 **alexandre.barachant** :

 >i'm not really worried about the wifi. 32 channels at 1kHz should works, it's more that if you want more, and want reliability, wired is better

8/16/2017 11:10 AM

 **aj** :

 >Yea but electrical shock is a thing and electrodes on brains

8/16/2017 11:10 AM

 **aj** :

 >So I worry about that

8/16/2017 11:12 AM

 **alexandre.barachant** :

 >you can isolate the connexion

8/16/2017 3:05 PM

 **sydneyneurotechx** :

 >Anyone have any experience with this device? They are going for a headphone design (dry electrodes) and doing neurofeedback. Based on the pricing probably targeting a more professional market (military etc). <https://getversus.com/>

8/16/2017 3:18 PM

 **aj** :

 >5 channel over Bluetooth is niceee

8/17/2017 1:03 AM

 **fred-simard** :

 >alexandre.barachant: Unless I'm mistaken, WiFi offers and throughput 2 or 3 order of magnitudes above what is required by 32x1k EEG... And if you use TCP, you don't need to worry about reliabilty. Witg WiFi you are good to go for a while. How about battery consumption?

8/17/2017 1:05 AM

 **fred-simard** :

 >aj: Unless you refer to BLE, Smarting does 24 chan at 500hz over bluetooth classic. I don't know if they compress the data, but they stream over RFCOMM

8/17/2017 2:05 AM

 **aj** :

 >I didn't know that!

8/17/2017 2:05 AM

 **aj** :

 >And that goes to iphone and Android?

8/17/2017 2:08 AM

 **fred-simard** :

 >aj: Good question. I think so, given that they ship their device with an android phone. I don't remember reading any restrictions in the manual.

8/17/2017 2:09 AM

 **aj** :

 >Hmm that's amazing why I'd OpenBCI not doing that I wonder

8/17/2017 2:09 AM

 **aj** :

 >They used an RFDuino which uses a Nordic gazell stack that doesn't go to iPhones and such

8/17/2017 2:09 AM

 **aj** :

 >And can only get 16chan at 125hz

8/17/2017 2:14 AM

 **fred-simard** :

 >I always wondered why they made that choice. Maybe they thought they would consume less power, but even BLE consumes its fair share of power when streaming a full data rate. BLE is mostly built for passive advertisement (ibeacon). Maybe to save on the cost?

8/17/2017 2:14 AM

 **fred-simard** :

 >Rfduino is on top of BLE

8/17/2017 2:20 AM

 **fred-simard** :

 >alexandre.barachant: Did you use the ADS1299, I thought your design was based on the MCP analog front-end?

8/17/2017 4:33 AM

 **alexandre.barachant** :

 >you are not mistaken, wifi has the theoretical bandwith to let much more than that. But on a microcontroller, there are other bottleneck than just the wifi bandwidth. Just a quick example, but if you have a single core uC, when it's busy with TCP stuff, it can not do anything else and may miss some samples comming from the ADC.

8/17/2017 4:37 AM

 **alexandre.barachant** :

 >there is a lot of EEG device that use classic bluetooth for eeg :

> 
- Wearable sensing : 24 channels x 300Hz

> 
- Neuroelectrics : 32 channels x 500 Hz

> 
- Cognonics : 20 channels x 500 Hz

8/17/2017 4:38 AM

 **alexandre.barachant** :

 >BLE is much harder, but muse managed 5 channels at 256Hz

8/17/2017 4:38 AM

 **alexandre.barachant** :

 >it all depends on the number of bits you encode your data. muse is 12 bits ...

8/17/2017 4:51 AM

 **aj** :

 >Joel days the spec was not around when he made the first boards

8/17/2017 4:52 AM

 **aj** :

 >I'm trying to get two full channels and that's even pushing ble 

8/17/2017 4:14 PM

 **fred-simard** :

 >Are you compressing your data? I implemented the &lt;2016 Muse decompression algo: <https://github.com/AtlantsEmbedded/atlants-DATA_interface/blob/master/data-daemon/src/supported_hardware/muse_pack_parser.c>

> 


> 
I think several others did, and I think the Ganglion use a similar encoding scheme.

> 


> 
I never measured the rate of compression, but it seemed like a smart way to go about the problem. The rate of compression increase with the number of channels, so I don't know how you score with 2.

8/17/2017 4:15 PM

 **fred-simard** :

 >I was able to stream a reasonable amount of data using HID-over-Gatt

8/17/2017 5:15 PM

 **aj** :

 >I didn't try to compress yet, some EEG applications don't need the compression but yes if we implemented a simple delta compression like on ganglion we can get four although that can for sure be lossy 

8/17/2017 6:38 PM

 **graeme** :

 >We have two of the Versus in our office. There's no stock software app for raw data, so you'd have to try a alexandre.barachant style bluetooth sniffing hack. I'm not sure if they're encrypted. Nonetheless, the big downside we found was that you have to use Ten20 gel - the polymer electrodes don't really work without that, and it comes with little tubes of Ten20 (called 'electrode conditioner' in their marketing) that they were selling on their website.

8/17/2017 6:39 PM

 **graeme** :

 >Also, it was not a comfortable headset in any way.

8/18/2017 4:45 PM

 **graeme** :

 ><http://brain-duino.com/>

8/18/2017 5:56 PM

 **graeme** :

 >Are those guys still around?

8/20/2017 6:11 PM

 **aj** :

 >Is anyone interested in a thumb sized 8chan EEG that hooks up to Arduinos/raspberry pi and is powered by 3v3 and can be Daisy chained together?

8/20/2017 6:13 PM

 **aj** :

 >Trying to see if I should put this into production

8/20/2017 6:13 PM

 **aj** :

 >Price would be &lt; $200 for sure

8/21/2017 12:21 AM

 **benjamindeleener** :

 >I am sure many people will be interested. Not speaking for all but I bet many student clubs would find that very useful

8/21/2017 3:22 AM

 **fred-simard** :

 >aj: I'm using the ads1299eeg-fe for that purpose, but it's big. I would buy your stick.

8/21/2017 11:49 AM

 **aj** :

 >Sweet!

8/21/2017 7:50 PM

 **aj** :

 >Cool! I'll launch a beta in the coming months

8/21/2017 9:02 PM

 **a.tech** :

 >Likewise 

8/23/2017 2:26 AM

 **aj** :

 >People are using the new OpenBCI cyton firmware with opto isolated UART to usb to get 500Hz steady at 460800 buad over wired connection 

8/23/2017 2:28 AM

 **aj** :

 ><https://github.com/OpenBCI/OpenBCI_32bit_Library/releases/tag/v3.0.0-rc5>

8/23/2017 2:30 AM

 **aj** :

 >All you have to do is hook up tx (d11) and rx (d12) and ground and then instead of calling `board.begin()` like normal in setup function you call `board.beginDebug(460800)`

8/23/2017 2:30 AM

 **aj** :

 >Sooo easy a cave person could do it!

8/26/2017 4:33 PM

 **aj** :

 >Hey <#C08T2SENQ|devices> question! Joel (openbci joel) and i were talking about the mini eeg and he says it should be battery powered so people can't have the opportunity to hook an arduino/raspberry pi up to the wall, be hooked up to the device, and an electrical surge hit and electrocute their heads. it's why the openbci is battery powered. should this stick be battery powered?

8/26/2017 4:34 PM

 **aj** :

 >Here is a sweet gif of the mini board as of today, it's powered by a 3V3 input pin <http://g.recordit.co/Q0xsLgfqvI.gif>

8/26/2017 4:35 PM

 **aj** :

 >i'm also looking for different connectors if anyone has suggestions1

8/26/2017 4:47 PM

 **aj** :

 >fred-simard a.tech that's huge!!! this device is 1.11" by 1.29"

8/26/2017 4:48 PM

 **aj** :

 >if i get smaller connectors i can go smaller

8/26/2017 4:48 PM

 **aj** :

 >what connectors do you want?

8/26/2017 6:04 PM

 **fred-simard** :

 >aj: aj huge indeed. Personnally, I like stackable similar to raspberry pi/arduino, one or two rows. I'm making use of the bias_drv, and the ads1299eeg-fe has an unpopulated active shielding circuit pads I would really like to try this out. I'll write a short document that explains my ideal ads1299 configuration tomorrow and i'll send it to you.

8/26/2017 6:06 PM

 **aj** :

 >That's so great! Thank you so much!

8/26/2017 6:06 PM

 **fred-simard** :

 >you'll be free to select the features you want to include

8/26/2017 6:07 PM

 **fred-simard** :

 >the openbci ganglion has a pretty slick design as well and slightly cheaper, just saying.

8/26/2017 6:07 PM

 **fred-simard** :

 >it would be a matter of scaling up to 8 electrodes

8/26/2017 6:31 PM

 **a.tech** :

 >On board battery would make it easier to use but I can imagine it would increase the size of the overall design as well if you use AA or AAA batteries...

> 


> 
Maybe a tiny rechargable Li polymer with microusb or one of those tiny disposable watch batteries could keep design compact? 

> 


> 
Cool chip so far man!!

8/26/2017 7:59 PM

 **aj** :

 >I've made a hulk ganglion (8 channel) and it's like 4"x2" for all the parts! Plus the SNR is worse.

8/26/2017 8:03 PM

 **aj** :

 >i also the EMI is worse on the ganglion then the ADS1299

8/26/2017 11:55 PM

 **fred-simard** :

 >My MCU is already battery operated, but if it comes with a battery connector, i'll simply remove and hook my own wires.

8/27/2017 12:06 AM

 **fred-simard** :

 >you might want to expose the ads1299 gpios (through hole). I don't use them, but some might want it and it doesn't cost much to do it

8/27/2017 12:13 AM

 **fred-simard** :

 >correct me if i'm wrong, but apparently you are only exposing the (+) electrodes. While the unipolar configuration is the most popular, I would lime to have the possibility to use as multi-polar.

8/27/2017 12:14 AM

 **fred-simard** :

 >*like

8/27/2017 12:15 AM

 **fred-simard** :

 >and from your gift, I don't see the START pin on the connector, is there a reason for that?

8/27/2017 9:00 AM

 **aj** :

 >I only exposed the negative side, I wanted to make the headers small, if you want all the pins for differential and what not, then just get the OpenBCI, but if you want a tiny embeddable EEG... If I could get a better connector on it then maybe I could for it all

8/27/2017 1:08 PM

 **ntremblay** :

 >hello aj, a lot of headers are available. If its only matter of finding the right one, I could help you if you need. 1.27mm pitch with dual rows may fit well for your project I think and you can find them right angle also. let me know if you need!

> 
Nicolas.

8/27/2017 6:18 PM

 **fred-simard** :

 >aj, I was only suggesting, I'm using unipolar so multi-polar option is only to keep the door open to experiment with it. OpenBCI cython is a good system, but I was aiming at saving on the costs and size, by dropping the RFduino. Thanks for considering my opinion.

8/27/2017 6:43 PM

 **aj** :

 >fred-simard I think you are right and I'm updating with both rows. Thanks!!

8/28/2017 5:50 PM

 **jamoonie94** :

 >Hey everyone, could someone give a concise comparison of various consumer eeg devices? 

8/28/2017 6:08 PM

 **yannick** :

 >sydneyneurotechx didnt you guys put something together on this?

8/28/2017 6:35 PM

 **sydneyneurotechx** :

 >yup! jamoonie94, check out this link. <http://learn.neurotechedu.com/headsets/>

8/28/2017 6:35 PM

 **sydneyneurotechx** :

 >If you have a question that isn't there, I don't mind answering it :slightly_smiling_face:

8/28/2017 6:41 PM

 **jamoonie94** :

 >Awesome. Thank you!

8/29/2017 5:10 PM

 **fred-simard** :

 >The ADS1299 is expensive, but it's a SoC, you pay for what you get. The Ganglion is a good alternative design, great work from the guys, but whereas you save $ you loose quality (and you need to support more parts)

9/1/2017 7:34 PM

 **jamoonie94** :

 >Hey, has anyone heard of IMotions before?

> 
<https://imotions.com/eeg/>

> 
<https://imotions.com/portfolio-items/abm-b-alert-x24-eeg/>

9/1/2017 7:39 PM

 **yannick** :

 >Yes, there small eBooks on many subjects (EEG, Eye Tracking, etc.) are pretty nice.

9/5/2017 3:49 PM

 **hailey** :

 >jamoonie94 Yes I use iMotions on a daily basis. What are you looking to use it for?

9/5/2017 4:18 PM

 **jamoonie94** :

 >I want to use it for my Masters project and also a BCI+VR gaming project. For the former I essentially just need auditory P300s and for the latter I want to implement some more complex functions for the game beyond just using alpha/etc waves

9/5/2017 4:42 PM

 **hailey** :

 >iMotions is a great tool, but cost is still very high (~$20k). Ive used it mainly to display stimuli with integrated eye tracking &amp; ECG, so I cant speak to how well it would work for your needs. Their support staff are fairly helpful if youre looking for more answers/guidancde

9/5/2017 4:43 PM

 **yannick** :

 >In what context did you use it hailey? User Experience? Neuromarketing? else?

9/5/2017 4:44 PM

 **hailey** :

 >Testing efficacy &amp; safety of a neuro-tech product

9/5/2017 4:45 PM

 **jamoonie94** :

 >20k for what exactly? 

9/5/2017 9:18 PM

 **aj** :

 >jamoonie94 how many channels do you want?

9/5/2017 9:37 PM

 **jamoonie94** :

 >Im not exactly sure at this point. Depends on the project I suppose. Although there is another side project I want to pursue which is to decode covert speech& Id probably want relatively more channels

9/6/2017 1:52 PM

 **hailey** :

 >It was $20k for the cost of the software, but this also including the Tobii eye tracker, so I suppose the software alone is slightly cheaper.

9/6/2017 2:39 PM

 **jee** :

 >Hi all, I'm setting up OpenBCI 8-channel Cyton board with Mark IV headframe, following tutorials and OpenBCI's forum discussions and had no luck. I seem to be getting noises whenever I touch the batteries or other wires on the headset. I expected signals from a single channel if I touched a specific spiky electrode on the headset but it would show signals on other channel/s or sometimes nothing at all. Then another time most channels were showing 'Railed' label. 

> 


> 
I plugged electrodes from the headset to 1-8 channels (N1P-N8P) on the bottom pins of Cyton board, and two ear clips on SRB top pin and BIAS top pin. Bottom pin meaning closer to the board, and top pin away from the board. 

> 


> 
Has anyone had a similr problem ramping up?

9/6/2017 3:33 PM

 **aj** :

 >touching wires while recording should produce noise, i try to keep my cables as still as possible to limit noise. I also think your SRB pin should be on the bottom row for the default setup with OpenBCI.

9/6/2017 4:42 PM

 **jee** :

 >aj Is it reasonable to expect spikes when the applicable electrode is touched with finger?

9/6/2017 7:38 PM

 **aj** :

 >That looks like good EEG!

9/6/2017 7:39 PM

 **aj** :

 >Yea the jump is fine

9/7/2017 3:52 PM

 **jee** :

 >Awesome, thanks aj! I'm going to remove the unused electrodes to simplify things..

9/7/2017 4:39 PM

 **aj** :

 >jee i think that's a good idea, but an alternative idea is to leave the electrodes on the headset and power down the channels that are not in use by clicking the colored number on the left hand side for each channel on the _Time Series_ widget you wish to turn off.

9/7/2017 9:33 PM

 **yacine.mahdid** :

 >Hi there, I have an open BCI cap with the ultracortex MARKIV / 8 channels cyton board and I had a question concerning the ear clips. I think I've wired them properly by putting them on the SRB and BIAS pin, but I wasn't sure if I had to have both of then clipped on when recording EEG. The signal is radically different wether I have one or the other or both of them on!

9/7/2017 9:39 PM

 **aj** :

 >Have both on for sure!

9/7/2017 9:39 PM

 **aj** :

 >yacine.mahdid 

9/7/2017 9:40 PM

 **yacine.mahdid** :

 >Allright thanks aj!

9/8/2017 1:45 PM

 **jee** :

 >aj Ohh thanks for the tip! Awesome!

9/8/2017 1:46 PM

 **aj** :

 >i'm gonna make some tutorial videos soon, will be sure to cover these!

9/8/2017 5:19 PM

 **yacine.mahdid** :

 >Hi aj, 

> 
We are planning on recording with open BCI soon to test the signal quality. I heard from one of our collaborator that the quality of the signal is way better when recording on the sd cars. I was wondering if there is a particular card that you would recommend? (thanks for all the help by the way!)

9/8/2017 5:31 PM

 **aj** :

 >You need a class 10. I also think saving to an sd has the benefit of not dropping packets. 

9/8/2017 5:31 PM

 **aj** :

 >Same data but with Bluetooth some packets cab get dropped 

9/8/2017 5:33 PM

 **aj** :

 >^ yacine.mahdid does that make sense?

9/8/2017 5:34 PM

 **aj** :

 >The wifi shield that just got released solves the dropped packet issue for real time processing <https://shop.openbci.com/collections/frontpage/products/wifi-shield?variant=44534009550>

9/8/2017 5:40 PM

 **yacine.mahdid** :

 >Yes make perfect sense, thanks aj!

9/8/2017 11:51 PM

 **jee** :

 >I am also shooting tutorial videos! Once I finish learning the details of setting up!

9/11/2017 11:05 PM

 **sydneyneurotechx** :

 >Oh look. Another Neurofeedback device coming to Kickstarter. <https://producthype.co/neuroplus/>

9/11/2017 11:06 PM

 **sydneyneurotechx** :

 >Looks like the cogniotics electrode with the Neurosky ear clip

9/11/2017 11:21 PM

 **yannick** :

 >But at least the guy behind it is not a new comer to the field trying to make few quick bucks.

> 
He started working with Emotiv years ago, then Muse, now apparently making his own device.

> 
(I cant speak about the science or the quality. Im just saying that hes not a new comer to the field)

9/12/2017 2:10 AM

 **dano** :

 >Hmmmm, so from the lit I think we can safely say brain training games = no work. Brain training games + EEG = ? :neutral_face:

9/12/2017 4:28 AM

 **yrenard** :

 >Does Cz-only training fall in the bucket of Brain Training games + EEG anyway ? If the electrode had been mobile enough so that every other day, one could have train the left-artistic brain, and every other other day, train the right more rational brain, that would have been in that bucket for sure... but one electrode... i'm not sure :stuck_out_tongue:

9/12/2017 4:45 PM

 **yannick** :

 >Well, even with one electrodes, if you could find something meaningful to influence the brain game or cognitive training, it would qualify as such, but the question is what and how are you using the Cz signal.

9/12/2017 5:23 PM

 **yannick** :

 >To comment on your point dano, it is not fair to say brain training games = no work. It would be like saying tDCS doesnt work and/or neurofeedback doesnt work. In these 3 fields positive results have been published, but have been quite hard to reproduce. I dont think we can say it doesnt work, but we cant say we fully master it. Many studies have been published comparing gamers vs non-gamers for different cognitive functions such as reaction time, contrast sensibility, attention (different types of attention), etc. and in some areas (mainly visual/visuomotor), gamers have indeed shown greater skills. Intuitively, doing a task for thousands of hours would indeed have an impact on related cognitive function (given what we now know on brain plasticity), but we havent necessarily yet figured out how to master the mechanics to optimize such brain training to avoid playing for 4 years to notice that indeed you gained few ms in reaction time.

> 
I think that it is fair to say that there is something there, but we dont master it. Also, I think that when it comes to the brain, given our current understanding and resolutions, one-size-fits-all approaches dont always work (e.g. tDCS with same montage on 2 different people wont stimulate the exact same cortical regions / neurons / networks). 

> 
Im looking forward for the Clinical Trials from l (with Akili) to see if they will get their FDA approval for therapeutic usage. (Yes, that would mean prescribing a specific video game for ADHD)

> 
My 2 cents&

9/13/2017 10:17 AM

 **mikhail.sintsov** :

 >Hi, could you please give me some links and keywords to the State of the Art systems for human scalp EEG recordings?

9/13/2017 10:19 AM

 **mikhail.sintsov** :

 >My lab is going to build or buy an eeg device.

9/13/2017 3:27 PM

 **yannick** :

 >I feel like its a rather broad question. Would you be more interested in the application side of things (i.e. what are people doing with EEG) or the hardware side of things (i.e. what kind of EEG system do people buy/build)?

9/13/2017 3:27 PM

 **yannick** :

 >I feel like its a rather broad question. Would you be more interested in the application side of things (i.e. what are people doing with EEG) or the hardware side of things (i.e. what kind of EEG system do people buy/build)?

9/13/2017 9:08 PM

 **bciguy** :

 >looks like cognionics electrodes

9/14/2017 9:20 AM

 **mikhail.sintsov** :

 >I meant, the hardware. In sense of spatial resolution and SNR.

9/14/2017 4:45 PM

 **danielao** :

 >Does anyone have experience with Thync? Just heard of it today and I don't really dabble in neuromodulation at the moment.

9/14/2017 6:40 PM

 **hailey** :

 >Ive had some experience with them. Any questions you have in particular?

9/14/2017 9:37 PM

 **danielao** :

 >Hi hailey, I don't have a specific questions but just wondering what your context and experience was with it.

9/15/2017 2:57 AM

 **sweetrabh** :

 >sorry to jump on an old thread but Im curious alexandre.barachant, for but the real $$$ are not on stimulation based BCI, which signals do you think can be reliably taken advantage of?

9/15/2017 8:05 AM

 **alexandre.barachant** :

 >sweetrabh to date, stimulation based BCI are the most reliable type of signal you can exploit, but that's not the issue here. For controling things, user expect self paced BCI because its the natural way to interact with our environment.

9/15/2017 2:33 PM

 **bhargava2566302** :

 >Awesome aj whats the shield

9/15/2017 2:34 PM

 **aj** :

 >A tiny little eeg 

9/15/2017 2:34 PM

 **aj** :

 >For Arduino and raspberry pi

9/15/2017 2:37 PM

 **bhargava2566302** :

 >Oh is it in market

9/15/2017 4:22 PM

 **sweetrabh** :

 >Ah ok I see, thanks. By self paced BCI, do you mean passive BCI or like a continuous EEG measurement?

9/15/2017 4:36 PM

 **alexandre.barachant** :

 >sweetrabh Self paced is when the user decide when to send command. you can see it as a sub-class of continuous. (your keyboard is self-paced, it does not output keystrokes all the time,  just when the user want it)

9/17/2017 4:00 AM

 **yannick** :

 >Cool!

9/18/2017 11:11 AM

 **mikhail.sintsov** :

 >ray_cassani That is interesting. But what are advantages of stripping epoc down to bones? Did it improve snr?

9/18/2017 2:07 PM

 **mikhail.sintsov** :

 >Guys, I need an advice. I'm willing to make a custom ECoG electrode for my rats. However, in labs nearby it is barely possible. The SOTA solution requires PEDOT:PSS, but for our purposes any microelectronics litrography would work. There are solution from Neuronexus, but their price is too high for us, like $800 for a single probe, and it becomes even higher after crossing the board. Could you suggest any manufacturers or labs, where it is 

> 
feasible to get custom probes cheaper? Maybe in Europe or China (considering I'm located in Russia)?

9/18/2017 6:19 PM

 **joeyo** :

 >Cortera makes uECoG arrays, not sure about cost: 

9/18/2017 6:19 PM

 **joeyo** :

 ><http://corteraneuro.com/products/neuroscience>

9/22/2017 4:43 PM

 **alexandre.barachant** :

 >Recently, i've been working on 3D printed EEG electrode. I think i start to get very positive results.

> 
I'm using conductive PLA + silver paint on the tip of the electrodes.

> 
here is some pictures :

9/22/2017 4:45 PM

 **alexandre.barachant** :

 >anyone has tried similar things ?

9/22/2017 7:20 PM

 **yannick** :

 >You made the electrodes yourself? (the one similar to the Cognionics ones

9/22/2017 9:06 PM

 **sydneyneurotechx** :

 >Nice. Canadian quarter for scale.  :stuck_out_tongue:

9/22/2017 9:07 PM

 **sydneyneurotechx** :

 >Have you tried with ERP's yet alexandre.barachant?

9/22/2017 9:20 PM

 **alexandre.barachant** :

 >sydneyneurotechx ^

9/22/2017 9:23 PM

 **sydneyneurotechx** :

 >holy moly, that's amazing

9/22/2017 9:27 PM

 **alexandre.barachant** :

 >yannick yes, its homemade. Similar to cognonics, but not flexible. i have trouble to 3D print conductive flexible filament

9/23/2017 12:19 AM

 **fred-simard** :

 >I think Connor at OpenBCI has done some work on printed electrodes, but that goes back a few years.

9/23/2017 5:02 AM

 **yrenard** :

 >congratulations alexandre.barachant that looks great

9/23/2017 12:04 PM

 **aj** :

 >how do I determine the amount of RAM i need for a project?

9/23/2017 1:03 PM

 **ntremblay** :

 >Hello Aj, a big part of ram consumption came from variables and array that you declare... I think you should firstly verify this and also take in account the data type of your arrays. A byte array is x time smaller than a float array...

9/23/2017 1:32 PM

 **aj** :

 >yea i guess i need to run my system and see it's memory consumption

9/23/2017 1:33 PM

 **aj** :

 >i wonder if there is a trace tool to monitor memory

9/25/2017 12:12 AM

 **fred-simard** :

 >aj there's plenty. Visual Studio integrates a profiler if you're using Windows. Under Linux, this should get you started: <https://baptiste-wicht.com/posts/2011/07/profile-applications-linux-perf-tools.html>. Google it, this is a common need for performance optimization and embedded system development.

9/25/2017 12:25 AM

 **fred-simard** :

 >alexandre.barachant Even thought I think your work toward designing a 3d printed electrode is amazing, I would like to play the devil's advocate, here. I noticed that you plotted the average traces for the EEG responses, but you didn't provided the following key information: 1) what is the number of trials, 2) what does the shaded region shows? 

> 


> 
I noticed several articles (blogs) that compared recording platforms and made dubious claims on the ability to measure the ERP. The simple trick is to record many trials and plot the standard error on the mean as the shaded region. The standard error is greatly reduced as the number of trials increases and is not related to information content. While such a trace confirms that the ERP can be measured using the said device, it hides that the variability of the response is much higher than other devices, greatly impacting single trial performance. A better metric is the standard deviation (usually 95% interval), which does provide an estimate for the entropy in the system.

> 


> 
The problem with dry electrode is not so much that they can't measure EEG signals, it is that they pick up a lot of noise, by turning the electrode wire into some kind of antenna. With enough trials or long recording period, you can still find whatever EEG signature you are hunting for, but it takes more trials/time to filter out the noise.

> 


> 
Again, I think your work is amazing and I'm looking forward to see your progress, I'm only playing the role of the skeptic who needs to challenges your work. I hope you'll prove me wrong.

9/25/2017 8:24 AM

 **alexandre.barachant** :

 >fred-simard I'm agreeing with you 100%. i would have made the same remark if it was not me that posted the results.

> 
Obeserving ERP difference is a very bad way to compare systems, because ERP hide noise thanks to averaging.

> 
This is why i develloped a complete procedure to benchmark the electrodes. In addition to ERP, this procedure generate induce oscillation in gamma frequency in the visual cortex.

> 
I then use single trial classification as a metric for signal quality, since more noise would lead to lower classification performances.

9/25/2017 8:25 AM

 **alexandre.barachant** :

 >These resuslts are just for teasing, but i'm currently setting up the benchmark and recording data on several subjects

9/25/2017 8:25 AM

 **alexandre.barachant** :

 >to aswers your question, there is 80 trial per class, and the shaded region is the convidence interval estimated with bootstraping.

9/26/2017 12:23 AM

 **fred-simard** :

 >Great job thanks for the details. Keep it up. After reading your message, I looked it up and identified a conductive epoxy and conductive flexible TPU plastic. Not cheap thought. I'm a bit busy right now, but might give it a try later on. Side note, I tried you pyRiemann on some data I had. Good stuff!

9/26/2017 6:59 AM

 **alexandre.barachant** :

 >I have some conductive TPU too. its quite hard to print correctly, but it works.

9/28/2017 4:26 PM

 **yacine.mahdid** :

 >Hi guys, does anyone have experience with recording eeg with the dry electrodes headset from OpenBCI? <#C08T2SENQ|devices> 

9/28/2017 5:16 PM

 **dano** :

 >The UltraCortex? We used it for some cool demo projects in Toronto, didn't have any problems

9/28/2017 8:21 PM

 **aj** :

 >I have some experience with UltraCortex

9/29/2017 11:15 AM

 **alexdni** :

 >we've tried this earlier on this year in our lab as well and found it hard to print with conductive flexible filament. instead, we printed with regular filament and coated it with silver paint. the issue we found for doing that is the coating wears off after usage and messes with signal quality. 

> 


> 
currently we use silver-impregnated fabric electrodes for the forehead, and spring-loaded retractable electrodes for haired-areas.

9/29/2017 4:21 PM

 **ben.cuthbert** :

 >Hey everyone, we're trying to connect to our Muse using MuELS, following the instructions from (<https://github.com/NeuroTechX/bci-workshop>). We've followed all of the setup instructions on Windows 10, but when we try to start acquisition we get the following error:

> 
Error 2 occurred at System <http://Exec.vi|Exec.vi>. Command was "muse-io.exe --preset 14 --device  Muse-52C3 --osc <osc.tcp://localhost:5000>"

9/29/2017 4:21 PM

 **ben.cuthbert** :

 >Can anyone shed some light on this issue?

9/29/2017 4:31 PM

 **ben.cuthbert** :

 >Update: MuseIO isn't compatible with the 2016 Headset... looking into muse-lsl

9/29/2017 4:40 PM

 **ben.cuthbert** :

 >The readme for muse-lsl says that on Mac and PC we must have the BLED112 dongle.. is this absolutely necessary to interface with the 2016 Muse? We want to be sure before ordering

9/29/2017 4:57 PM

 **alexandre.barachant** :

 >ben.cuthbert yes. this is because the python library pygatt i'm using only works with a BLED112 dongle on Mac and window.

> 
in the meantime, you can try to boot on a live-USB with ubuntu (and switch to linux because Mac and windows sucks)

9/29/2017 4:58 PM

 **alexandre.barachant** :

 >this is anoying, but I did not find another way to do BLE with python

9/29/2017 5:01 PM

 **ben.cuthbert** :

 >alexandre.barachant thanks for getting back to me so quickly! The dongle looks pretty cheap so I'll probably order 1 or 2, and switch to Linux eventually

9/29/2017 5:01 PM

 **ben.cuthbert** :

 >Thanks so much for this repo by the way- it's amazing!

9/29/2017 5:01 PM

 **alexandre.barachant** :

 >:slightly_smiling_face:

9/29/2017 7:49 PM

 **dano** :

 >You could also use dongle-less BlueMuse for Windows projects <https://github.com/kowalej/BlueMuse>

9/29/2017 7:52 PM

 **alexandre.barachant** :

 >nice. if someone can confirm it works with the experimental paradigm provided with muse-lsl, i will add a link into my readme

9/29/2017 7:52 PM

 **dano** :

 >yayy kowalej

9/30/2017 4:22 PM

 **yacine.mahdid** :

 >aj  ans dano , cool! I'm trying to record with it, but its very very uncomfortable and the signal quality is really poor. It must be the way I set it up. Did you have any issue with it?

9/30/2017 4:23 PM

 **dano** :

 >OUr biggest problem was the software -- on every platform but Mac we had data dropping issues

9/30/2017 5:31 PM

 **aj** :

 >@yacine get electrodes from fri

9/30/2017 5:31 PM

 **aj** :

 >They have new long ones for hair

9/30/2017 5:31 PM

 **aj** :

 >They fit right in!

9/30/2017 5:32 PM

 **aj** :

 >And their other smaller spikes are less spoke then openbci

9/30/2017 5:35 PM

 **aj** :

 >Make sure wires are not long and bunched

9/30/2017 5:36 PM

 **aj** :

 >@dano did that happen on Windows?

9/30/2017 5:36 PM

 **aj** :

 >And it was ganglion right

9/30/2017 5:37 PM

 **aj** :

 >I think the data rate is too high for BLE

9/30/2017 5:37 PM

 **aj** :

 >With that size compression

9/30/2017 5:38 PM

 **aj** :

 >Should reduce the compression to 16 bits and not send as many data packets per second

9/30/2017 5:38 PM

 **aj** :

 >I drop packets like crazy on Mac it sucks

9/30/2017 5:38 PM

 **aj** :

 >With cyton I'm good

9/30/2017 5:39 PM

 **aj** :

 >But ganglion over ble does not work with my Mac. I may plan to write some code to test this bug.

9/30/2017 5:45 PM

 **aj** :

 >I want to write some test code for simblee to duplicate the issue with my Mac, then see exactly what sample rate starts dropping packets on my hardware. If we can get say 50Hz but not 100Hz, maybe we can do more compression or lower resolution for these platforms that are having problems. 

9/30/2017 5:46 PM

 **aj** :

 >Then I could add in board modes changing that drops sample rate or goes into this mode, and you at least get continuous data

9/30/2017 5:47 PM

 **aj** :

 >The packets literally never get to the software layer of Bluetooth it's mind boggling 

10/1/2017 3:02 PM

 **dano** :

 >Yea, it was Ganglion. I mostly remember it on Linux, but I think it might have happened on windows too

10/1/2017 3:03 PM

 **dano** :

 >That sounds like a great approach, though

10/1/2017 6:25 PM

 **yacine.mahdid** :

 >Thanks guys! Will check out the electrode!

10/2/2017 9:04 PM

 **jamoonie94** :

 >Alright Im a noob when it comes to EEG hardware, but I just won a scholarship in my department :blush: and I want to invest in something that can be used to take on a variety of projects. For instance, I may want a project where I focus on P300s or etc. At this point in time, what EEG/BCI gear would you say is the best?

10/2/2017 9:14 PM

 **jamoonie94** :

 >anyone heard of : <http://www.bri.com.tw/product.html>

10/2/2017 9:23 PM

 **alexandre.barachant** :

 >I don't know much about the signal quality, but I once asked a quote for the 32 channel system. It's 12k$

10/2/2017 9:25 PM

 **alexandre.barachant** :

 >If you want something good for multiple project, you can either have a headset with good coverage (24 - 32) elecs or a reconfigurable system with lower channel count

10/2/2017 9:27 PM

 **alexandre.barachant** :

 >What's your budget ?

10/2/2017 9:27 PM

 **jamoonie94** :

 >It was ~1500-2000, but after hearing that I feel that I may want to increase that.

10/2/2017 9:28 PM

 **alexandre.barachant** :

 >For 2k, openbci might be your best guess.

10/2/2017 9:28 PM

 **jamoonie94** :

 >have you used that before?

10/2/2017 9:30 PM

 **alexandre.barachant** :

 >Multiply this by 10, an you can go for a cognonics or a wearable sensing dsi24

10/2/2017 9:31 PM

 **alexandre.barachant** :

 >G.tech had some good hardware but I don't like their dry electrode. Not comfortable at all.

10/2/2017 9:32 PM

 **jamoonie94** :

 >yeah Im looking for something that can be easily used (somewhat)

10/2/2017 9:32 PM

 **jamoonie94** :

 >open BCI does sound like the best bet

10/2/2017 9:33 PM

 **alexandre.barachant** :

 >It's good. But is less "plug and play"

10/2/2017 9:34 PM

 **alexandre.barachant** :

 >Also. I dont like the 3d printed headset. I prefer a cap. 

10/2/2017 9:36 PM

 **jamoonie94** :

 >Im gonna go for the pro assembled Ultracortex MarkVI

10/2/2017 9:36 PM

 **jamoonie94** :

 >Im looking for something more toward research

10/2/2017 9:39 PM

 **alexandre.barachant** :

 >With a little practice and tweaks, openbci is definitely up to the standard. You might want to add  the wifi shield, it has a more reliable connection.

10/2/2017 9:42 PM

 **jamoonie94** :

 >what parts are essential and what would you recommend

10/2/2017 9:43 PM

 **jamoonie94** :

 >sorry to be shotgunning you with so many questions

10/2/2017 9:43 PM

 **jamoonie94** :

 >I guess Im confused about what it all includes

10/2/2017 9:52 PM

 **alexandre.barachant** :

 >You need an amplifier to record the EEG. You have the ganglion (4 ch), the cython (8ch) or the Daisy (16 channel).

10/2/2017 9:53 PM

 **alexandre.barachant** :

 >You can add the wifi shield to get better data streaming.

10/2/2017 9:53 PM

 **jamoonie94** :

 >cool I have the daisy on my shopping list

10/2/2017 9:53 PM

 **jamoonie94** :

 >does the data streaming have to go to Azure etc?

10/2/2017 9:53 PM

 **jamoonie94** :

 >can it not just stream right to my comp?

10/2/2017 9:53 PM

 **jamoonie94** :

 >also what about EEG, gel

10/2/2017 9:54 PM

 **jamoonie94** :

 >?

10/2/2017 9:54 PM

 **jamoonie94** :

 >seriously sorry for all the questions

10/2/2017 9:54 PM

 **alexandre.barachant** :

 >And finally, you need some electrode. For that you can either buy some spare électrodes and build a cap yourself, or buy the 3d printed headset

10/2/2017 9:56 PM

 **alexandre.barachant** :

 >With wifi board you can stream on your comp. Without it too, but some people report trouble with higher sampling rate

10/2/2017 9:56 PM

 **alexandre.barachant** :

 >No need for gel if you go for dry electrode (ultracortex)

10/2/2017 9:58 PM

 **jamoonie94** :

 >okay sounds good.

10/2/2017 9:58 PM

 **jamoonie94** :

 >Thanks alot Alexandre!

10/2/2017 11:21 PM

 **aj** :

 >It can go to azure

10/2/2017 11:21 PM

 **aj** :

 >I'm working on hitting it this week

10/2/2017 11:22 PM

 **aj** :

 >And if it requires a software patch I'll update it

10/2/2017 11:22 PM

 **aj** :

 >But this is exactly why I built the wifi shield! Direct to cloud!!!

10/2/2017 11:23 PM

 **aj** :

 >Bi directional http control from browser it's great so you can completely control the board from web browser.

10/21/2017 11:55 PM

 **aj** :

 >Awesome contributions to OpenBCI make me so happy! WiFi shield working makes me happy to. Im putting in long hours to make the WiFi shield reliable, fast, and easy to use. Check out this feature proposal from new user! <https://github.com/OpenBCI/OpenBCI_GUI/issues/264#issuecomment-338438330> 

10/22/2017 1:19 PM

 **bryan** :

 >Hi all, my lab is going to submit a tech fee proposal to our university for next year and I want to pick out the best gear for a complete BCI system for research. I was thinking dry electrodes, wireless and some stimulation component (TMS or tDCS). Large proposals have been funded in the past- $40k+. What would you all consider to be the best system and best components?

10/22/2017 1:28 PM

 **alexandre.barachant** :

 >bryan for wireless t*CS + EEG, i think you have neuroelectrics

10/22/2017 1:30 PM

 **alexandre.barachant** :

 >saying that, you can only record with a dry electrode, for both recording and stim, you need wet electrode

10/24/2017 1:21 PM

 **bryan** :

 >Thanks alexandre.barachant So, if I wanted a complete system I would have wet electrodes for the stim (still needed for TMS?) and dry for recording. Is neuroelectrics still the choice for all components? I was wondering if Cognionics would be best for dry and to try to fit them into a system made up of parts from different mfg's. Also need a stimulator- who is best for TMS/t*CS?

10/24/2017 1:23 PM

 **alexandre.barachant** :

 >okay, i'm still not sure what you want to achieve. i recommanded neuroelectrics because it can stimulate and record at the same time (i think) or at lease with the same electrodes

10/24/2017 1:23 PM

 **alexandre.barachant** :

 >Adding TMS on top of that is tricky

10/24/2017 1:24 PM

 **alexandre.barachant** :

 >TMS send large magnetic pulse, so you want to have a system that is TMS compatible. i doubt active electrodes from cognonics will like it

10/24/2017 1:25 PM

 **alexandre.barachant** :

 >i'm not sure TMS / TDCS is part of the standard BCI lab, but for sure :slightly_smiling_face:

10/24/2017 1:26 PM

 **bryan** :

 >That's why I wanted to see what people here thought. I know some colleagues use it in their experiments

10/24/2017 1:26 PM

 **alexandre.barachant** :

 >for what it worth, I did EEG + TDCS + TMS in the past. We had a regular 32 wet channel EEG (neuroprax), soterix for HD-tDCS, and i can't remember the name of the TMS machine (+ brainvision, for realtime localization of TMS)

10/24/2017 1:27 PM

 **alexandre.barachant** :

 >but you are looking way past the 40k of your budget

10/24/2017 1:27 PM

 **bryan** :

 >Only drawback with Neuroelectrics is 32 channel limit. I think Cognionics had a 64 cap

10/24/2017 1:27 PM

 **bryan** :

 >Thanks that's helpful. Yeah, I don't have a hard line of the number for the budget

10/24/2017 1:28 PM

 **bryan** :

 >I can break it up amongst some PIs also

10/24/2017 1:28 PM

 **alexandre.barachant** :

 >do you want to do all simulataneous EEG + tDCS + TMS ?

10/24/2017 1:28 PM

 **bryan** :

 >not necessarily, either TMS or tDCS to start should be fine

10/24/2017 1:29 PM

 **alexandre.barachant** :

 >no i mean, stimulation + EEG recording at the same time ?

10/24/2017 1:29 PM

 **bryan** :

 >for certain experiments, yes that would be good

10/24/2017 1:29 PM

 **alexandre.barachant** :

 >that create a large constraints on what kind of hardware you use

10/24/2017 1:30 PM

 **alexandre.barachant** :

 >also, by experience, it's hard to put tDCS on high density EEG

10/24/2017 1:30 PM

 **alexandre.barachant** :

 >even more with  Dry EEG,

10/24/2017 1:30 PM

 **alexandre.barachant** :

 >higer than 32

10/24/2017 1:31 PM

 **alexandre.barachant** :

 >then you have problem with the tDCS gel creating bridge between electrodes

10/24/2017 1:32 PM

 **bryan** :

 >Yeah, that can happen in normal recordings anyway. But I guess with stimulation it's even more of a concern?

10/24/2017 1:33 PM

 **alexandre.barachant** :

 >no bridge with dry electrode :slightly_smiling_face:

10/24/2017 1:34 PM

 **bryan** :

 >Yes, I meant with wet recording. That's one of the many reasons I want to go dry! :slightly_smiling_face: 

> 
It sounds like I would use my dry electrodes for recording and wet for stimulation. Could still use same amplifier, eye tracking, response devices

10/24/2017 1:34 PM

 **alexandre.barachant** :

 >okay, what i would recomend is to check compatibility with the manufacturer. i really doubt cognonics is TMS friendly

10/24/2017 1:35 PM

 **alexandre.barachant** :

 >some manufacturer offers complete solution for EEG + TMS (or tDCS). but their system are less sexy than the cognonics

10/24/2017 1:37 PM

 **alexandre.barachant** :

 >like this

10/24/2017 1:37 PM

 **bryan** :

 >For just dry recording, would you say Cognionics is the leader? ie, this system: <http://www.cognionics.com/index.php/products/hd-eeg-systems/72-channel-system>

10/24/2017 1:37 PM

 **alexandre.barachant** :

 >they are quite good

10/24/2017 1:39 PM

 **alexandre.barachant** :

 >i heard good thing about ant-neuro electrodes : <http://www.ant-neuro.com/products/waveguard_touch>

10/24/2017 1:40 PM

 **alexandre.barachant** :

 >but if you want the absolute best, you will have to wait i release my open source hardware EEG headset :slightly_smiling_face:

10/24/2017 1:41 PM

 **bryan** :

 >haha nice!

10/24/2017 1:41 PM

 **bryan** :

 >you will have a tough one to beat in OpenBCI

10/24/2017 1:42 PM

 **alexandre.barachant** :

 >:slightly_smiling_face: i think it will be complementary with OpenBCI. mine is more research oriented

10/24/2017 1:43 PM

 **bryan** :

 >Well I will look forward to learning more! Thanks for your help, I will review these options with my PI

10/24/2017 1:47 PM

 **alexandre.barachant** :

 >okay. to summarize my recommendation :

> 
- Neuroelectrics if you want to stimulate + record with the same electrodes

> 
- Cognonics for dry wireless system. ant-neuro for a more classical non-wireless dry

10/24/2017 1:48 PM

 **alexandre.barachant** :

 >- for TMS stim, you really have to check, because none of this systems are likely to handle the magnetic pulse

10/24/2017 2:02 PM

 **bryan** :

 >Awesome, thank you!

10/25/2017 1:16 PM

 **aj** :

 >Hey all Im trying to make a circuit for marking eeg data when I flash a stimulus on screen, I want to put the diode on a little square and send a 1 when white and 0 when black to an arduino. Does any one have advice?

10/25/2017 1:56 PM

 **rohit** :

 >I not sure about what you mean by 'diode on a little square' but you can use a photodiode(cheapest solution), it will detect when the light shines on it and communicate to Arduino. You can easily Google the simple circuits for that. 

> 


> 
Secondly, why do you need arduino and external circuit, can't you just know when the screen is flashing white/black if you have programmed it to do so. 

10/25/2017 2:03 PM

 **alexandre.barachant** :

 >rohit your screen does not display things instantaneously, and there is several frame of delay between the time you ask to display something and what happens in real life. 

> 
Depending on how low level your programming is, there is also a frame or two of jitter that is very difficult to fix. this greatly decrease the accuracy of evoked potential detection

10/25/2017 2:04 PM

 **alexandre.barachant** :

 >in many neuroscience experiment, hardware tagging is used to physically get the timing of the stimulus as seen by the user

10/25/2017 2:12 PM

 **alexandre.barachant** :

 >Some EEG amplifier also does not stream timestamps, so you don't actually know precisely the computer time corresponding to a given EEG sample. And then you have drift in the EEG amplifier clock. For all these reason, if very precise timing is required, you have hardware trigger input in most EEG hardware. it's generally a TTL input that is sampled simultaneously with the EEG and used to tag your stimulus within the EEG stream

10/25/2017 3:37 PM

 **ray_cassani** :

 >If the EEG devices has not input for triggers, a channel could sacrificed to be used as trigger channel, however I'm no familiar on how much it'll effect the EEG signal quality, and I guess it'll depend on the EEG device that is being used. Any knowledge in this topic?

10/25/2017 3:39 PM

 **alexandre.barachant** :

 >yep, you could sacrifice a channel. but it depend on the device. if you have a DRL (or active grounding), the signal from the channel will be re-injected in the patient as part of the common mode cancelation

10/25/2017 3:40 PM

 **alexandre.barachant** :

 >so i would not necessarily recommand this with openBCI for example

10/25/2017 3:42 PM

 **alexandre.barachant** :

 >also, if your amplifier has some cross-talk between channel, it can leak into adjacent channels.

10/25/2017 4:34 PM

 **aj** :

 >side convo here but it's hella easy to remove a channel from the bias

10/25/2017 4:35 PM

 **aj** :

 >&gt; TTL input that is sampled simultaneously with the EEG and used to tag your stimulus within the EEG stream

10/25/2017 8:06 PM

 **aj** :

 >I still have not found a good circuit to duplicate :confused:

10/25/2017 8:08 PM

 **aj** :

 >when use a phototransistor?

10/25/2017 8:10 PM

 **aj** :

 >wait i think i did find one

10/25/2017 9:01 PM

 **aj** :

 >can anyone recommend a phototransistor they have used before? Mine is non sensitive enough

10/26/2017 4:56 AM

 **rohit** :

 >I have used opt101(sensitivity was really good) ic, and photo resisters in past they worked just fine.

> 


> 
You try to use high biasing resister to increase sensitivity in case of phototransistor.

> 


> 
<https://www.intorobotics.com/common-budgeted-arduino-light-sensors/> found this, you could refer if looking for alternates

> 


10/26/2017 6:49 AM

 **harris** :

 >I might be receiving a small grant for around two thousand USD and I would like to build up an EEG system from scratch that has the spatial resolution for mental command applications. I am hoping for it to use dry electrodes, and wireless. Would OpenBCI be the best route for this?

10/27/2017 7:26 AM

 **jmhorschig** :

 >sorry to chime in rather late. The ANT-Neuro works nice, for sure, but the best impression for dry electrodes I got so far is from <http://wearablesensing.com/>  - check them out. Nice guys as well. 

> 
For a standard BCI lab, brain stimulation is actually not usual., but when going for Neuroelectrics you might want to think about adding fNIRS (<http://www.artinis.com/starstim-fnirs/> - but disclaimer, I'm an Artinis employee) . If I were you, I'd go for that, because for BCI a second modality is a much bigger plus than brain stimulation. And if you want to start up with brain stimulation and have no prior experience, maybe do not go with TMS. It's way too challenging to get a clean signal - you make life easier by starting txCS (it's also cheaper).

10/27/2017 12:51 PM

 **bryan** :

 >interesting, thank you for chiming in! I will include the fNIRS/EEG/txCS in my options. The limit of 8 channels is a drawback, however, but I understand why, with so many parts integrating.

> 
This fNIRS/EEG package is also interesting: <http://www.artinis.com/nirs-eeg-package/>

> 
Looks like you can get good coverage with this setup and there's a wireless/mobile option? I would be interested in learning more about that.

10/27/2017 10:18 PM

 **sydneyneurotechx** :

 >So something like motor imagery?

10/31/2017 11:33 AM

 **aj** :

 >How does the muse have a ble characteristic for everything? There is a characteristic for each eeg channel, accel, Control data, its crazy how many there are.

10/31/2017 11:34 AM

 **aj** :

 >What ble chip allows that? Did they register with the Bluetooth team?

10/31/2017 9:21 PM

 **harris** :

 >Does anyone have any stable way of connecting with the Muse 2014?

10/31/2017 9:22 PM

 **harris** :

 >I tried almost everything at a recent hackathon but I failed to get any data back from it

11/1/2017 2:24 AM

 **sydneyneurotechx** :

 >What's your OS? Mac or Windows? There are a variety of reasons why your connection might not be stable. Did your eeg have good contact on your head?

11/1/2017 5:35 PM

 **yannick** :

 >You mean the bluetooth connection was bad or the electrodes signal was bad?

11/1/2017 5:39 PM

 **harris** :

 >yannick I tried windows 10 and ubuntu but couldn't seem to get any application to connect to the stream properly

11/1/2017 6:02 PM

 **graeme** :

 >Try the MuseDirect beta on windows, or Muse-io on mac. Both should work, and we would really appreciate hearing if they don't work (plus any bugs).

11/1/2017 8:46 PM

 **fred-simard** :

 >harris Hey, I build a C framework that does exactly that. It's a bit old and I haven't touched it in a while, but last time I checked it works well. Try to follow these steps: <https://github.com/AtlantsEmbedded/IntelliPi/wiki/Compiling-and-running-IntelliPi-on-Linux-x86-x64-(and-Raspbian)>

11/1/2017 8:47 PM

 **sydneyneurotechx** :

 >Might I suggest taking some screen caps so that we can see what errors you are getting? If you run muse-io via  a TCP connection, does it connect to the device?

11/5/2017 11:40 PM

 **mhough** :

 >Hey fred-simard I just saw your message and GitHub. Nice! You are here in Montreal? I would be interested in meeting up and chatting about some extensions to what you have for a super small system prototype.

11/6/2017 12:41 AM

 **aj** :

 ><http://openbci.com/community/cyton-ble-code-now-in-alpha/>

11/6/2017 12:41 AM

 **aj** :

 >just release new firmware and drivers for openbci cyton over ble

11/6/2017 8:46 AM

 **jmhorschig** :

 >Hi Bryan,

> 
The 8-channel limit is with this specific setup, we have a couple of other mobile-devices in production right now that will allow 24-channel NIRS. So, yes, there are wireless options. Best would be to take this outside slack (mail me <mailto:jorn@artinis.com|jorn@artinis.com>).

11/9/2017 11:51 PM

 **adamm_neurable** :

 >Does anyone know of any commercial "in-ear" EEG devices? Ear-buds/plugs? I know of the cEEGrid and the failed United Science "Aware" Kickstarter plus a handful of researchers who have hacked Muses and Neurosky's strip for ear-buds....but does anyone know of any other organization who is actively working on or selling EEG/Ear devices?

11/10/2017 3:28 PM

 **dano** :

 >Looks like the Mandic lab in the UK is doing the most focused work on in ear EEG devices. However, it doesn't look like they've started to commercialize yet.

> 


> 
<https://www.nature.com/articles/s41598-017-06925-2>

11/10/2017 6:47 PM

 **yannick** :

 >fred-simard ^

11/14/2017 11:15 PM

 **ben.cuthbert** :

 >MUSE 2016: Has anybody had any luck decoding bluetooth packets containing accelerometer/gyroscope data? I've used alexandre.barachants post as a guide (<http://alexandre.barachant.org/blog/2017/01/27/reverse-engineering-muse-eeg-headband-bluetooth-protocol.html>) and messed around with the awesome muse-lsl repo, but I can't make sense of the data I get from non-eeg handles. Thanks in advance!

11/14/2017 11:47 PM

 **alexandre.barachant** :

 >ben.cuthbert I think urish did decide accelerometer data for his muse-js package

11/15/2017 12:21 AM

 **ray_cassani** :

 >hey yannick, do we have a Muse 2016 at NT Montreal?  I'd like to give a try with those packages in the <#C073X2ZQW|hacknights>

11/15/2017 12:22 AM

 **sydneyneurotechx** :

 >We do ray_cassani

11/15/2017 6:38 AM

 **mhough** :

 >Hey aj will you be going to hacknight tomorrow in SF?

11/15/2017 6:48 AM

 **aj** :

 >mhough 100%

11/15/2017 7:08 AM

 **mhough** :

 >Cool man. Didn't think I would be in town but thank you for the silver lining:)

11/15/2017 9:43 AM

 **urish** :

 >Indeed

11/15/2017 3:38 PM

 **ben.cuthbert** :

 >Great! I'm checking it out now. Looks like you got battery &amp; temperature info too- that's wicked!

11/16/2017 9:42 AM

 **urish** :

 >You are welcome :slightly_smiling_face: What are you building?

11/16/2017 11:39 AM

 **alexandre.barachant** :

 >albertle what is MMG ?

11/16/2017 1:18 PM

 **albertle** :

 >alexandre.barachant sorry, I should have been clear that that picture is not ours. I'm not sure what MMG is; just the EMG plots are relevant to what we were seeing. 

11/16/2017 5:30 PM

 **joeyo** :

 >Most likely mechanomyogram

11/16/2017 7:06 PM

 **ben.cuthbert** :

 >We've got a couple of ideas.. for now we're just trying to get a solid handle on interfacing with the muse

11/17/2017 12:26 PM

 **urish** :

 >Which ideas?

11/18/2017 3:57 AM

 **sydneyneurotechx** :

 >Anyone with any thoughts around gtec's new system?

11/18/2017 3:58 AM

 **sydneyneurotechx** :

 >Apparently to help with communication of Locked in patients

11/18/2017 3:58 AM

 **sydneyneurotechx** :

 >Anything unique in their approach?

11/18/2017 8:40 AM

 **aj** :

 >wifi direct working hells yea with openbci wifi streaming 2000Hz with no dropped packets.

11/18/2017 8:16 PM

 **urish** :

 >my project for today:

> 
<https://twitter.com/UriShaked/status/931889030479908864>

