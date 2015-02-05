---
layout: post
title: "Muons flight path, Science Hack day Nairobi - 2012" 
--- 

__This article was originally published on [IT News Africa][0] and has been reposted here.__


``[Science Hack Day][1] (SHD) is an event that aims to bring together designers, developers and scientists with good ideas to collaborate together and come up with solutions within a timeframe of 48 hours. 


Scientists and scholars from Kenya recently enjoyed solving issues at the Science Hack Day. SHD aims to bridge existing gaps between science, current technology and design so as to ensure and encourage future collaboration, community building and awareness.

“Science should be disruptively accessible,” said [Ariel Waldman][2] founder of Science Hack Day, San Francisco.

“Science Hack Day empowers people from a variety of different backgrounds to explore, participate in, and build new ways of interacting with and contributing to science.”

In an interview with [Martin A. Chiteri][3], a Software Developer by profession and an organizer at the event, as well as [Dr. Matthew Bellis][4] of Siena College, I managed to get some insight as to what SHD entails.

*What were some of the ideas of the Nairobi SHD 2012?*

>*Martin:* According to me the major ideas of discussion as was reflected on by the founder of SHD San Francisco, Ariel Waldman and [Matt Biddulph][5] (BBC Uk, Dopplr, Nokia, Hackdiary.com – London) is that there is a lot of data out there from scientific experiments that need to be processed and better made sense of by the rest of us lay people.

>The other thing that came up is that there are many opportunities to gain from some of the challenges faced by scientists, like the automation of processes performed in research, experiments in science, etc. An example was the energy use optimization problems on programmable logic controllers present in power generators manufactured by Siemens’ industry.

*How do you come up with a hack? Is it dependent on an individual or is there a general discussion amongst the group as to what they should come up with?*

>*Martin:* At the beginning of the 48-hour hack-a-thon people are allowed to pitch (sell) ideas. We encourage this to come from the scientific community. They present some of the problems they face and the developers in the room can join them in an effort to come up a solution within the time-frame.

>Group sizes generally vary from 1 or 2 to about 4 – 8 maximum

*How can you explain the hack that your group came up with?*

>*Martin:* The hack my group came up with is [an animation of trajectories elementary particles][6] from a family known as lepton and bosons (or daughter particles) take immediately they decay from their parents (quarks), usually protons after an extremely high energy proton-proton collision inside the Large Hadron collider’s compact muon solenoid at the European centre for Nuclear research.

>We got a portion of the data from [one of the experiments][7] courtesy of Dr. Matt Bellis and used it to visualize the movements using [mapping tools][8] (Basemaps), [graphing and plotting libraries][9] (Matplotlib) plus libraries for [Scientific analysis][10]. We produced image frames of the estimated path between where the collision occurred [(France / Switzerland border)][11] and the coordinates of the place [where the particles were actually detected][12]. After that we created a motion picture of the journey by sequencing the image frames compressed using [a free multimedia encoding tool][13] known as ffmpeg.

>Our main inspiration was another work done by a group for [visualizing remote attacks][14] on a server they hosted for computer security research experiment. The other source of ideas was [an application][15] in the Android market place (Google Play) on the LHC.

*If the “hack” was to be put in a real world situation, of what importance will it be to the technology sector?*

>*Martin:* The hack was mainly an idea to have fun with, but it appears to be gaining popularity as [a possible teaching tool][16].

>*Dr. Matt Bellis:* with the animation we have, it was important to somehow show that the muons have different energies, but the higher energy ones don’t really travel noticeably faster than the lower energy one. This is initially counter-intuitive. We think of things that possess more energy as being able to go much, much faster. But these particles are moving close to, but always less than, the speed of light. They can never quite get there.

>So if you put 1000x more energy into one of these particles, you might only increase its speed by a fraction of a percent! We decided to represent the energy of one of these muons by the size of the dot, but still have the animation move them at about the same speed. Obviously, the animation is still slowing down the particles much slower than their actual speed.

>We should point out that the muons never actually leave CERN, because the experiment is deep underground and these particles are stopped in the rock. However, by making animations like this, maybe we are secretly educating people? Someone may see it and wonder why some of the colours are the way they are? Or what does the size of circles mean?

*For those who did not attend, what is the most interesting part that they missed?*

>The [15 year old Leah Atieno][17] doing [a demo with the robot][18] she programmed.

>We also had a Kinect provided for by Microsoft [to let the attendees unwind][19].

*As an organizer, were there any challenges that you experienced and how did you manage to overcome them?*

>*Martin:* Sourcing funds was a major headache. We used our networks to counter this, even though they are small as of now.

>Coordinating tasks that led to and during the event was also not easy. It was a very good experience all the same.

*What was your experience of SHD 2012, and how has SHD being appreciated here in Kenya?*

>*Martin:* The reception is really good, especially after the event came to completion. We continue to receive very enthusiastic responses from sponsors, facilitators and participants alike

>*Dr. Matt Bellis:* SHD allowed me to interact with non-scientists in an environment through which [I can better explain what I do][20].

>For example, I can learn what people do- or do not know about particle physics. Or what misconceptions do they have about how science works. Then I can try to explain these scientific concepts…but I don’t always do a good job!

>So at an SHD [I get to learn how better to explain these topics][21]. Do I need animation? Do I need sound? Should I use different words or language to better explain these topics?

>In addition, I get to work with people like Martin A. Chiteri and [Morris][22] who help me find a better way to explain these concepts, whether through a video like the ‘Muons Flight Path’ or some other hack.

__~Michelle Tongo__
"

[0]: http://www.itnewsafrica.com/2012/04/hacking-into-the-science-of-solutions/ "Hacking into the Science of solutions"
[1]: http://sciencehackday.org/ "Science Hack Day, San Francisco"
[2]: http://arielwaldman.com/ "Ariel Waldman"
[3]: https://twitter.com/chiteri "Follow Martin on Twitter"
[4]: http://mattbellis.com/ "Prof. Matthew Bellis, website"
[5]: http://www.hackdiary.com/ "Matt Biddulph's, Blog"
[6]: http://youtu.be/ag7w0vgZj5g "Muons flight path, Youtube"
[7]: http://cms.web.cern.ch/news/cms-public-data-activity-scoops-prize-nairobi "C.M.S news item, SHD Nairobi - 2012"
[8]: http://matplotlib.org/basemap/ "Basemaps"
[9]: http://matplotlib.org/ "Matplotlib"
[10]: http://www.scipy.org/ "SciPy"
[11]: http://home.web.cern.ch/about "European Centre for Nuclear Research, CERN"
[12]: http://cms.web.cern.ch/news/what-cms "Compact Muon Solenoid experiment"
[13]: https://www.ffmpeg.org/about.html "FFMPEG, multimedia compression tool"
[14]: http://www.wallix.org/2012/02/29/pylogsparser-visualizing-ssh-attacks-in-video/ "Visualizing SSH attacks in video"
[15]: https://play.google.com/store/apps/details?id=com.lhsee "LHSee on Google play store"
[16]: https://plus.google.com/u/0/+MatthewBellis/posts/YGB2pmZGin7 "Matt Bellis' post on G+"
[17]: http://www.humanipo.com/news/210/15-year-old-girl-scoops-top-prize-at-science-hack-day-nairobi/ ""Science Hack Day, Nairobi - 2012 on Human IPO""
[18]: http://www.flickr.com/photos/mbiddulph/7079490375/in/set-72157629442124858 "Leah Atieno Ligare"
[19]: http://www.flickr.com/photos/mbiddulph/7079249191/in/set-72157629442124858/ "Science Hack Day Nairobi attendees with Kinect"
[20]: http://www.mattbellis.com/outreach/ "Outreach, Prof. Matthew Bellis"
[21]: http://sciencehackday.org/matt-bellis/ "Science Hack Day: a spa weekend to recharge my batteries"
[22]: http://nerd.co.ke/morris "Morris Mwanga, blog"
