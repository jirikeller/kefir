# kefir
KEller's Functional MRI Interaction Routines

Author: Jiří Keller, M.D., Ph.D. <keller.public+git-kefir@gmail.com>

# Introduction

There are several commercial fMRI packages such as E-prime, Presentation etc and few non-commercial such asi Expyriment, Psychopy etc. We were trying to use several of those, but were not completly satisfied. So, this is another software bult by user for user.
Kefir routines are written in Python and you can use just very simplistic approach (such as traffic-light block paradign even without MRI synchdonization) or very complex one, with parallel threads, logging, visual and auditory outputs, response pad and scanner TTL inputs etc. And what is the best - you can run all  this on open-source platform, e.g. Raspberry pi with Raspbian (setup we actually use). Kefir is fast enough even on this hardware !

# What Kefir can do for you ?
At the time of writing this "advert", Kefir can:
- project a cross for resting-state fMRI paradigm on the screen for patient
- run simple block paradigm (rest/activation) either synchronized by time (known TR duration) or synced with MR scanner
- present text stimuli
- present pictures
- play sound
- or any combination of above three stimuli (nearly) simultaneously
- log your events, if you with (or not to log them by default to make your life easier and not to mess the drive with logs)

# Why should I use Kefir and not other software ?
- Raspberry Pi is OK as a HW platform. No expensive Windows-based computers
- python-based - no Matlab licence is needed any more
- not a signle synchronization pulse missed on Raspberry Pi

# Licence
At this timepoint, no code is shared on github as at this development stage software is *Authorware* - if you are interested in using Kefir for your own projects, I would be happy to implement desired features and helping you to set up the stuff, but I would like to be a co-author of your paper arising from this study. Please send me an e-mail.
