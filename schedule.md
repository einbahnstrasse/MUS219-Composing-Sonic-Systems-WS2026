---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: archive
layout: single   
title: Schedule   
lang: en   
ref: sched   
permalink: /schedule/   
# sidebar:
#   nav: "schedule-toc"   
toc: true  
toc_label: "Schedule" # default: Content
toc_icon: "bell"  # corr esponding Font Awesome icon name without the "fa" prefix
toc_sticky: true   # enables sticky toc 
read_time: true  
date: 2025-08-25  
last_modified_at: 2026-01-21   

---

_Our precise order of topics and their accompanying materials will periodically change and/or be updated, at the discretion of the instructor, based on class pacing and other factors. Schedule and materials will be regularly updated on this website and announced in class. Changes to, or additions of, recordings, readings, or videos may be appended to this current schedule below. Additional materials will be distributed on this website or in class. Our schedule follows the [Current Bates Academic Calendar]({{ site.Bates-calendar }}){:target="_blank"}. Check frequently for updates!_  

## Calendar of Deadlines    

_Subscribe to our class Google calendar to see our upcoming deadlines. Daily schedule of events, tutorials, topics, terms, listening, guests, and other relevant information follows._ 

<iframe src="https://calendar.google.com/calendar/embed?height=500&wkst=1&ctz=America%2FNew_York&showPrint=0&src=Y18wODY5Yzg3NmU1Y2I5MDBlZWUyNjA5NzIxYjJhZTI3ODA2NWYxMTBkN2E4ZjgwMzdjZGZmMjUzYjkxZjFjZDg4QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%238e24aa" style="border:solid 1px #777" width="650" height="500" frameborder="0" scrolling="no"></iframe>

* * *   

## Week 1: {{ site.week-01 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-01-topic }}</span>

#### Wednesday 1/14 — Orientation & Setup (No patching)
##### In Class
- Course overview and expectations
- What “sonic systems” means in this course
- Semester arc and concert requirements
- Website walkthrough + access check
- GitHub accounts and workflow overview
- Max installation check

##### Tutorials
* [Introduction to MaxMSP Slides 1—18: What is MaxMSP?](https://einbahnstrasse.github.io/MHL-intro-to-MaxMSP/){:target="_blank"}
* [Introduction to MaxMSP (video, 33 minutes)](https://youtu.be/DpKIQzjOh_U?si=ozCElT5NQmD-m9D0){:target="_blank"}

{% include video id="DpKIQzjOh_U?si=ozCElT5NQmD-m9D0" provider="youtube" %}

* [Introduction to Git and GitHub (video, 28 minutes)](https://youtu.be/Lw2OgM6tQd8?si=EvIraJMlgGHUdPet){:target="_blank"}

{% include video id="Lw2OgM6tQd8?si=EvIraJMlgGHUdPet" provider="youtube" %}

##### Assignments  
* Setup your GitHub account   
* Be sure to complete the [Intro Survey](https://forms.gle/aoBKQDuqnK1aoGH9A){:target="_blank"}   
* Install + authorize Max (if using a personal license), or book time in the computer labs   
* Watch the Max and GitHub intro videos above, rebuild tutorial patches, and commit them to your GitHub account by our weekly deadline: Saturdays, 11:59 PM.        
* Make these starter patches (from the video):

##### Patches    
  - `starter.patch.v01.maxpat`    
  - `starter.patch.v02.maxpat`      

##### Terms, Concepts, Objects, Shortcuts
_Use this list as a reference. Leave comments in your patches to remind yourself what these are and how they work._
- realtime vs. offline electronics
- computer music
- patch / subpatch `<p>` / abstraction
- object box `command + n`
- lock/unlock patch `command + e`
- message box `<m>` / comment box `<c>`
- control rate (Max) vs. signal rate (MSP)
- resize boxes `command + j`
- duplicate an object `command + D`
- open help file: `option + click` on any object

* * *

## Week 2: {{ site.week-02 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-02-topic }}</span>

#### Monday 1/19     
_MLK Jr. Day — No class._    

#### Wednesdsay 1/21 — Signal Flow & Debugging

##### In Class
- signal vs control
- gain staging and safe monitoring

##### Tutorials
* [MaxMSP Keyboard Shortcuts (MacOS and Windows)](https://docs.cycling74.com/max8/vignettes/shortcuts){:target="_blank"}
* [Introduction to MaxMSP Slides 19—35: History through New Terms](https://einbahnstrasse.github.io/MHL-intro-to-MaxMSP/#/19){:target="_blank"}
* [MaxMSP Beginner's Cheatsheet (includes Data Classes)](https://cycling74-web-uploads.s3.amazonaws.com/5462c2a9bdbb99652da7a00a/2017-05-11T08:53:04Z/cheatsheet.pdf){:target="_blank"}

##### Patches    
  - `_scaffold.v01.maxpat`
  - `working.patch.v01.maxpat`
  - `lg.sound.in.v01.maxpat`
  - `lg.sound.out.v01.maxpat`
  <!-- - `00.getting.started.maxpat` -->

* * *

## Week 3: {{ site.week-03 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-02-topic }}</span>

#### Monday 1/26 — Oscillators & Envelopes
##### In Class
- waveform families
- oscillator objects
- ADSR and envelope-as-time-system

##### Tutorials
* [Learn About Waveforms (The Pudding)](https://pudding.cool/2018/02/waveforms/){:target="_blank"}

#### Video Tutorials    
_In lieu of class during inclement weather, follow the video tutorial and complete patches before Wednesday._      
* [Week 3 Day 1 Patching](https://youtu.be/xrp77TXfdgY?si=a-e2qBi_Nl0IQNJD){:target="_blank"}      

{% include video id="xrp77TXfdgY?si=a-e2qBi_Nl0IQNJD" provider="youtube" %}     
   
#### Listening
* [Max Mathews, _Bicycle Built for Two_ (1961)](https://youtu.be/ZFUVR-clo8g?si=xdj3dzQyMBw-g1Ui){:target="_blank"}

{% include video id="ZFUVR-clo8g?si=xdj3dzQyMBw-g1Ui" provider="youtube" %}

##### Patches    
<!-- - `_scaffold.v01.maxpat` -->
- `01.basic.waveforms.maxpat`
- `02.ADSR.maxpat`

##### Assignments
* Finish:
  - `01.basic.waveforms.maxpat`
  - `02.ADSR.maxpat`
<!-- * Read: shortcuts + cheatsheet (use help files constantly) -->

##### Terms, Concepts, Objects, Shortcuts
- oscillator
- sine `<cycle~>` / saw `<phasor~>` / triangle `<tri~>` / square `<rect~>`
- ADSR / envelope
- duty cycle
- **help files**: `option + click`

#### Wednesday 1/28 — Monosynth and MIDI Input     

##### Patches    
- `03.monosynth.variable.note.length.maxpat`
- `04.additive.synth.with.randomization.maxpat`
- MIDI subpatcher inside of `_scaffold.v01.maxpat`

##### Terms, Concepts, Objects, Shortcuts
- synthesis engine  
- MIDI (Music Instrument Digital Interface)   
- monosynthesizer     
- additive synthesis    

* * *  

## Week 4: {{ site.week-04 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-04-topic }}</span>

#### Monday 2/2 — Class Canceled; Illness    

#### Wednesday 2/4 — Polyphony and Voice Allocation       

#### Boiler (Downloads)     
* [Bach Polyphony Tutorial Patches](https://github.com/einbahnstrasse/bach-poly-boiler-patches){:target="_blank"}    

##### Patches    
- `bach.poly.05.polyphony.maxpat`
- `simple.voice.polyCore.v01.maxpat`
<!-- - MIDI subpatcher inside of `_scaffold.v01.maxpat` -->

##### Terms, Concepts, Objects, Shortcuts
- synthesis engine  
- MIDI (Music Instrument Digital Interface)   
- monosynthesizer     
- additive synthesis       

* * *     

## Week 5: {{ site.week-05 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-05-topic }}</span>

#### Monday 2/9 — Euclidean Rhythms in Bach         

#### Boiler (Downloads)     
* [Interacting With Bach Tutorial Patches](https://github.com/einbahnstrasse/interacting-with-bach-W2026){:target="_blank"}    

#### Optional Reading   
* [Toussaint Paper on Euclidean Rhythms](https://cgm.cs.mcgill.ca/~godfried/publications/banff.pdf){:target="_blank"}    

##### Patches    
- `bach.interaction.t07.euclidean.idea.maxpat`
- ~~`bach.interaction.t08.melodic.profile.maxpat`~~     

#### Wednesday 2/11 — Modulation Synthesis          

#### Boiler (Downloads)       
* [Test Sounds Media Folder](https://github.com/einbahnstrasse/synth-tech-media){:target="_blank"}    

#### Listening
* [Tristan Murail, _Atlantys_ (1985) for two Yamaha DX7 Synthesizers](https://youtu.be/rnwoUFhxQLo?si=MH6MS0kg92ae8DNQ){:target="_blank"}    

{% include video id="rnwoUFhxQLo?si=MH6MS0kg92ae8DNQ" provider="youtube" %}

[View the score](https://drive.google.com/file/d/1B5Yp6BBWGEFgFEMMCqfEIhWCdFJfF459/view?usp=sharing){:target="_blank"} for more information, if interested.   

##### Patches    
- `RM.AM.FM.v01.onWaveforms.maxpat`     
- ~~`RM.AM.FM.v02.onSignals.maxpat`~~     

##### Assignment    
* [Connecting Modulation to bach.roll + poly~](/MUS219-Composing-Sonic-Systems-WS2026/assignments/modulation-bach-integration/){:target="_blank"}    
  
* * *     

## Week 6: {{ site.week-06 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-06-topic }}</span>

#### Monday 2/23 — Phi         

#### Tutorials        
* Look at a solution to the assignment   
* Consider random-note generation (_briefly_ — more on this later)   

#### Boiler (Downloads)       
* [Phi Boiler](https://github.com/einbahnstrasse/phi-boiler){:target="_blank"}    

#### Listening
* [John Chowning, _Stria_ (1977)](https://youtu.be/988jPjs1gao?si=T054gKWSL2d1nzdx){:target="_blank"}    

{% include video id="988jPjs1gao?si=T054gKWSL2d1nzdx" provider="youtube" %}   

##### Patches    
- `RM.AM.FM.v02.onSignals.maxpat`     
- `_phi.v01.maxpat`     

##### Terms, Concepts, Objects, Shortcuts
- ring modulation     
- golden ratio ("golden section")       
- self-similarity            

#### Wednedsay 2/25 — Phi, Continued    

##### Patches    
- `_phi.v02.maxpat`     
- `phi.polyCore.v02.maxpat`     

* * *     

## Week 7: {{ site.week-07 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-07-topic }}</span>

#### Monday 3/2 — Using Randomness + Reservoirs             

#### Boiler (Downloads)       
* [Randomness + Reservoirs Boiler](https://github.com/einbahnstrasse/week.5.boiler.patches){:target="_blank"}    

##### Patches    
- `03.two.voices.maxpat`     
- `04.using.distributions.maxpat`     

#### Wednesday 3/4 — Randomness, Cont.                    

##### Tutorials
* [Debugging in Max](https://einbahnstrasse.github.io/Debugging-in-Max/){:target="_blank"}     
   
##### Patches    
- `04.using.distributions.maxpat`       

* * *     

## Week 8: {{ site.week-08 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-08-topic }}</span>

#### Monday 3/9 — Wavetable Synthesis             

#### Boiler (Downloads)       
* [Wavetable Synthesis Boiler](https://github.com/einbahnstrasse/wavetable.boiler){:target="_blank"}    

##### Patches    
- `03.wavetable.synthesis.maxpat`   
- `03a.buffer.interpolation.maxpat`            
- ~~`04.waveshaping.maxpat`~~        

##### Assignment     
* **For Wednesday**: Connect your fancy new wavetable synthesizer to the `<bach.roll>` in `04.using.distributions.maxpat` and drive the synthesizer using the correct pitches and note information originating from playback in your `<bach.roll>` sequence.   

#### Wednesday 3/11 — Distortion Synthesis                 

##### Patches   
- ~~`05.wavetable.distortion.bands.maxpat`~~     
- ~~`06.wavefolder.maxpat`~~  

* * *    

## Week 9: {{ site.week-09 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-09-topic }}</span>

#### Monday 3/23 — Wavetable Synthesis, Continued              

##### Upcoming Quiz   
_Expect a short, in-class, written pop-quiz over the Debugging in Max slides sometime in the next 1-3 class sessions. Review the slides for preparation._  

##### Patches   
- `04.waveshaping.maxpat` 
- `05.wavetable.distortion.bands.maxpat`     
- `06.wavefolder.maxpat`  

* * *    

## Week 10: {{ site.week-10 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-10-topic }}</span>

#### Monday 3/39 — No Class                  

#### Wednesday 4/1 — Guest Presentation (In Person)     
_Jason Thorpe Buchannan, guest composer_        

* * *    

## Week 11: {{ site.week-11 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-11-topic }}</span>

#### Monday 4/5 — Filter as Process           

##### Patches   
- `lowpass.filter.generation.maxpat`   

##### Assignment     
* **For Saturday (normal submission schedule)**: Consider one of the wavetable patches we made during our wavetable unit in class EXCLUDING the one you already used for the assignment in Week 8 (e.g., in Weeks 8-10 we considered all sorts of wavetables, waveshaping, wavefolders, distortion, etc.). Take another one of these (or potenitally find a way to use both in the same polysnthesizer), build a `poly~` with it, and drive your synth using _your own_ generative process: combine what we've learned about distributions, including randomizing paramaters such as pitch and onset, to create something more pesonally nuanced. However, don't simply _copy_ and use default values given in class. It's your turn to create something of your own using the principles we've developed. You may also borrow from today's lowpass filter example, but again, the empahsis should be on developing your own control process and not simply using the patch you already made.  

#### Wednesday 4/1 — No Class    

* * *    

## Week 12: {{ site.week-12 }}
### <span style="color: #fc3a52; font-size: 120%; ">{{ site.week-12-topic }}</span>     

#### Monday 4/13 — Presentation on Concert Patches             


* * *    

_More coming soon — check back frequently!_   

* * *  


