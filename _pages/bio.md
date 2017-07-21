---
layout: single
author_profile: true
permalink: /bio/
read_time: false
title: About Me
---

{%capture balrog %}<span style="font-variant:small-caps;">Balrog</span>{% endcapture %}

First and foremost, I think of myself as a scientist -- not only because of my professional history, but based on my outlook on life.
I try to think along scientific lines, based on evidence, with conclusions drawn based on logical analysis.
No doubt, science has been so important bringing us to where we are today and will continue to shape our future.
Research drives us. Quoth Steven Weinberg:
> Men and women are not content to comfort themselves with tales
> of gods and giants, or to confine their thoughts to the daily affairs of life; they also build
> telescopes and satellites and accelerators, and sit at their desks for endless hours working
> out the meaning of the data they gather. The effort to understand the universe is one of the
> very few things that lifts human life a little above the level of farce, and gives it some of the
> grace of tragedy.

<div style="max-width:475px; width:100%; margin:auto; float:right; margin-left:20px; margin-bottom:20px">
	<div id="wslider" style="">
		<img src="/assets/images/busyweek2.png" style="" alt="My research group hard at work. 'Busy weeks' pushed us to author the first DES science paper." style="">
		<img data-src="/assets/images/luckbros2.jpg" style="" alt="Pretty much the story of my life during those dissertation writing months..." style="">
		<img data-src="/assets/images/desmeeting2.jpg" style="" alt="DES Collaboration Meeting, 2015 -- Ann Arbor. Naturally, I'm the one wearing the Ohio State jersey." style="height:100%">
	</div>
	<script>
		var wslider = new IdealImageSlider.Slider({
			selector: '#wslider',
			effect: 'fade',
			height: 'auto',
			transitionDuration: 500,
			interval: 7001
		});
		wslider.addCaptions();
		wslider.start();
	</script>
</div>
<div style="position:relative; width:200px; content:''; display:table;"></div>
Academically, my background is in Physics, earning my Bachelors, Masters, and PhD from **_The_** Ohio State University.
In graduate school, I carved out my niche in cosmology, working with an amazing group of people in [CCAPP][ccapp] (Center for Cosmology and Astroparticle Physics).
I think anyone who's been there will agree that CCAPP is top-notch, and I am privileged to have been a student there.
Klaus Honscheid was a phenomenal PhD advisor, and I'll always miss interactions with him and his group.
In my research, I did a lot of technical software work, developing a (perhaps excessive) love for Python.
It was all contributing to efforts of the [Dark Energy Survey][des] (DES) -- an astronomy project involving hundreds
of scientist that is designed to help us better understand the properties of the Universe's expansion.
The telescope is in Chile (I've used it), and the project contributors are all over the globe.
I owe much gratitude to many DES collaborators, but especially my {{balrog}} team.

I don't want to get into too many technical details here, but roughly speaking, my [dissertation research][dissertation] progressed along three fronts.
First, I developed control software for [DECam][decam], DES' multi-million dollar survey camera. (It was the largest-ever digital camera at the time it was built.)
Second, I was a lead contributor to an [early DES science project][clusters] that verified DES was capable of sensitively measuring how galaxies' shapes are aligned,
which is very important for the survey. Specifically, I was responsible for carefully processing the data to systematically remove image defects and reduce the relative noise level.
Third, I designed [{{balrog}}][balrog], software to realistically simulate DES (or other astronomical survey) data, then used the simulations
to remove nefarious contamination from high-noise data and effectively double the sample size available for precision measurements
(equivalent to doubling the survey area for such measurements, without requiring more observation time).

<div style="max-width:300px; width:100%; margin:auto; float:left; margin-right:20px; margin-bottom:20px">
	<div id="cslider" style="">
		<img src="/assets/images/treefieldmud2.jpg" style="" alt="My friends and I following an epic Treefield mud game">
		<img data-src="/assets/images/brass2.jpg" style="" alt="On the ice at Nationwide Arena with then Blue Jacket Derick Brassard">
		<img data-src="/assets/images/michigan2.jpg" style="" alt="Block O in the 'Shoe before beating Michingan">
		<img data-src="/assets/images/home2.jpg" style="" alt="Tifo before U.S. vs. Mexico -- scoreline, dos a cero">
	</div>
	<script>
		var cslider = new IdealImageSlider.Slider({
			selector: '#cslider',
			effect: 'fade',
			height: 'auto',
			transitionDuration: 500,
			interval: 6001
		});
		cslider.addCaptions();
		cslider.start();
	</script>
</div>
<div style="position:relative; width:200px; content:''; display:table;"></div>
Although work is very important to me, it's not the only thing, and Columbus became such a personal home to me over the years I was there.
The sports list goes on and on: Ohio State football and soccer galore, CBJ season tickets, Crew supporters section,
_dos a cero_ with USMNT, among others. As undergrads, we played plenty of pick up football on our beloved _Treefield_.
My graduate years are when I embraced the cure-all wonder-drug known as espresso. (Useless trivia,
a huge portion of PhD dissertation was written inside [Luck Brothers Coffee][luckbros] instead of my office.)
I also developed my insatiable need for crossword puzzles. (When I retire, maybe I'll go back to school for the elusive enigmatology degree.)
Nine years later, the day did eventually come that I had to move away from Columbus, and the next chapter of my life would be written from Philadelphia, Pennsylvania.
But needless to say, I'll always fondly remember my time in the heart of Buckeye Country.


Following graduate school, I took a postdoc job at the University of Pennsylvania, continuing on with DES,
this time working in Gary Bernstein's research group. My work was similar to what I did in graduate school -- 
more analyses using {{balrog}}, more data quality curating, more weak lensing (if you know what that is), and of course, more publications.
Though my time in the City of Brotherly Love was much shorter than my time in Columbus, it also came with its memories.
Perhaps most unforgettable was [_Snowmageddon 2016_][blizzard], a blizzard that covered the city with two feet of snow (apparently the fourth most in city history),
shutting down absolutely everything. Though I'm all for public transportation, the lowlight of my time in Philly was probably my SEPTA commute;
I commiserate with all those who endure the seemingly never on time Chestnut Hill West trains.


<div style="max-width:400px; width:100%; margin:auto; float:right; margin-left:20px; margin-bottom:20px">
	<div id="oslider" style="">
		<img src="/assets/images/titan.JPG" style="" alt="Meet Titan -- the largest supercomputer in the U.S., located at ORNL">
		<img src="/assets/images/office.jpg" style="" alt="My office, which includes a motivational sock monkey">
		<img data-src="/assets/images/chkm_finish.JPG" style="" alt="Crossing the finish line at the Knoxville (Half) Marathon">
	</div>
	<script>
		var oslider = new IdealImageSlider.Slider({
			selector: '#oslider',
			effect: 'fade',
			height: 'auto',
			transitionDuration: 500,
			interval: 6001
		});
		oslider.addCaptions();
		oslider.start();
	</script>
</div>
<div style="position:relative; width:200px; content:''; display:table;"></div>
Although I actively continue to coauthor papers with DES, I have a new day-to-day focus.
In June 2016, I began my ongoing career at Oak Ridge National Lab (ORNL), joining the [Scientific Data Group][sdg].
For the first time in decade, I was no longer in a physics department, making the jump to the Computer Science and Mathematics Division at ORNL.
Our group focuses on techniques for managing, visualizing, and analyzing large-scale scientific data,
partnering with the science teams to innovate solutions to computer science problems that impede scientific insight.
On one project, I've been working with two teams of energy scientists who simulate fusion reactors, helping them to build a framework that couples two separate code bases,
because the physics modeled in each alone is not enough to fully model next-generation devices.
On another project, I am exploring new ways to manage scientific data such that users can interact with multiple 'views' of large datasets, 
which present not only original full-quality data, but also error-understood reduced-quality versions with faster turnaround.

While I still thoroughly enjoy supporting my favorite sports teams, drinking coffee, and solving crossword puzzles, my time living in the Knoxville area
has seen a rise of interest in my personal fitness. Most days, working out is my favorite part of the day. 
I find that physical activity is the perfect complement to exercising my mind at work.
My personality is such that I try to challenge myself, both in the office and in the gym.
Some of my favorite activities include: trail running, lifting, rowing, and kickboxing. (I don't fight other people though, just training bags/pads.)


### Notes about nothing: ###
* My last name is pronounced Sue-hit-uh. (The 'c' is silent.)
* As far as I am aware, my first/last name combo is unique, part or present.
* I minored in French Literature as an undergrad at Ohio State.
* I've been to Chile, Spain, England, and Germany, but somehow not Canada.
* My second choice for graduate school, had I not chosen Ohio State, would have been Indiana University.
* I once sold knives as a summer job -- kitchen knives, that is.
* My kickboxing fighter name is Pollo Loco.
* I wear contact lenses, but only in my left eye.
* I've needed a backup chute while skydiving.


[ccapp]: http://ccapp.osu.edu/
[des]: http://www.darkenergysurvey.org/
[dissertation]: https://drive.google.com/open?id=0B4AAwvZlUdfeUmZuU0tPeU5IWWs
[decam]: http://www.darkenergysurvey.org/the-des-project/instrument/
[clusters]: http://www.darkenergysurvey.org/darchive/mass-and-galaxy-distributions-of-four-massive-galaxy-clusters-from-dark-energy-survey-science-verification-data/
[luckbros]: http://luckbroscoffeehouse.com/
[balrog]: https://arxiv.org/abs/1507.08336
[blizzard]: https://www.accuweather.com/en/weather-news/recap-blizzard-2016-washington-dc-new-york-city-philadelphia-baltimore-northeast/54977271
[sdg]: http://www.csm.ornl.gov/newsite/data_group.html
