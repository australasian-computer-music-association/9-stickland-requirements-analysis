---
title: 'Professional Views of Digital Audio Workstations and Collaborative Audio Mixing'
date: '2021-11-12'
anonymous: 'false'
author: 
    - name: Scott Stickland
      affiliation: School of Creative Industries, The University of Newcastle, Australia
    - name: Rukshan Athauda
      affiliation: School of Information and Physical Sciences, The University of Newcastle, Australia
    - name: Nathan Scott
      affiliation: School of Creative Industries, The University of Newcastle, Australia
author-header: S. Stickland, R. Athauda, and N. Scott
abstract: |
	Digital audio workstations (DAWs) play a critical role in audio mixing and post-production activities, facilitating audio engineers and clients to work collaboratively in a studio environment. The coronavirus pandemic brought into focus the need to carry out these activities in an effective manner with remote participants. This article explores the requirements for an optimal remote collaboration platform to facilitate post-production audio mixing through a qualitative study. We interviewed a group of Australian-based professional music/sound practitioners about their use of DAWs, work-case scenarios, use of remote control and collaboration features, and perspectives for an "ideal" remote collaborative music post-production environment. We derived several insights from the analysis of this data that can inform the design and development of a new collaboration platform. The evidence showed that the most common practice for remote mixing collaboration is an iterative process of sharing audio files/recordings with audio engineers who perform mixing/post-production work, which is shared back with clients for feedback asynchronously. Professional audio mixing practitioners do not typically engage in real-time remote collaboration outside of remote one-to-one sound source recording because synchronous post-production collaboration methods are unavailable. Our analysis derives a vision for such a platform: a "virtual" remote collaboration environment that emulates an in-studio experience.
bibliography: 'references'
papersize: a4
classoption: 12pt
reference-section-title: 'References'
---

# Introduction

Professional studio-based audio mixing of recorded material is an
innately collaborative process. Rarely is the audio engineer granted
carte blanche to produce a mix without some degree of oversight and
input from the various stakeholders, including the recording artist(s),
music producer(s), recording label representative(s) and, in the case of
music for film and television, the composer, music supervisor, editor,
producer(s) and director. Today, many modern music production studios
centrally integrate a Digital Audio Workstation (DAW) software
application in professional audio mixing. Although professional audio
mixing with all stakeholders physically in the well-equipped studio with
a DAW and audio engineer is ideal, remote collaboration modes and
practices for professional audio mixing are highly desirable, especially
in coronavirus-impacted times of self-isolation and travel restrictions.
This study's *raison d'être* was to understand the current practices and
identify the requirements for an ideal remote collaborative environment
for professional audio mixing and post-production. We conducted a series
of semi-structured interviews with professional audio mixing and music
production engineers to answer this central research question.

This article presents an interpretative phenomenological analysis (IPA) of
the responses from the semi-structured interviews. The IPA approach, as
defined by Smith (2004), is: ideographic, characterised by a detailed
sequential examination of each case in a small sample size; inductive,
"to allow unanticipated topics or themes to emerge during analysis" (p.
43); and interrogative, where discussion of the results of the analysis
concerns the research project's context. The interviews were voluntary
and aimed to ascertain several viewpoints, including:

-   The prevailing use of DAW platforms in audio mixing and music
    production workflows;

-   The range of specific DAW platforms used in the industry;

-   Typical professional work-case scenarios;

-   The current use of keyboard shortcuts and control surfaces in
    typical work-case scenarios;

-   Use of DAW-integrated online collaboration tools in professional
    studio work;

-   Typical existing practices when working with remote
    clients/colleagues;

-   Industry expectations of a real-time online audio mixing and music
    production environment; and

-   The perceived utility of multiparty audio mixing and music
    production online collaboration.

Six questions served as the interview guide and discussion starting
points and appear in the Appendix. As such, this article's structure
consists of six discrete sections that inductively analyse the responses
to the interview questions and any related follow-up questions, followed
by a Discussion section.

Table 1 summarises the research participant information.


+-------------+-------------+-------------+-------------+-------------+
|             | **Base of   | **Studio    | **Typical   | **Experience|
|             | Operations  | Owner/      | Work        | (Years)**   |
|             | (Australian | Operator /  | Scenarios** |             |
|             | State)**    | Freelance** |             |             |
+=============+=============+=============+=============+=============+
| Mixing      | Victoria    | Owner/      | Studio      | 10 +        |
| Engineer 1  |             | Operator    | Mixing /    |             |
|             |             |             | Recording   |             |
| (ME01)      |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Mixing      | Victoria    | Owner/      | Studio      | 15 +        |
| Engineer 2  |             | Operator    | Mixing /    |             |
|             |             |             | Recording   |             |
| (ME02)      |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Mixing      | New South   | Owner/      | Studio      | 25 +        |
| Engineer 3  | Wales       | Operator    | Mixing /    |             |
|             |             |             | Recording   |             |
| (ME03)      |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Mixing      | Victoria    | Freelance   | Live /      | 25 +        |
| Engineer 4  |             |             | Studio      |             |
|             |             |             | Mixing      |             |
| (ME04)      |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Mixing      | Victoria    | Owner/      | Studio      | 15 +        |
| Engineer 5  |             | Operator    | Mixing /    |             |
|             |             |             | Recording   |             |
| (ME05)      |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Mixing      | Western     | Owner/      | Studio      | 20 +        |
| Engineer 6  | Australia   | Operator    | Mixing /    |             |
|             |             |             | Recording   |             |
| (ME06)      |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Mixing      | Queensland  | Freelance   | Studio      | 20 +        |
| Engineer 7  |             |             | Mixing /    |             |
|             |             |             | Recording   |             |
| (ME07)      |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Mixing      | New South   | Owner/      | Studio      | 10 +        |
| Engineer 8  | Wales       | Operator    | Mixing      |             |
|             |             |             |             |             |
| (ME08)      |             | Freelance   |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Mixing      | Victoria    | Owner/      | Live /      | 30 +        |
| Engineer 9  |             | Operator    | Studio      |             |
|             |             |             | Mixing      |             |
| (ME09)      |             | Freelance   |             |             |
+-------------+-------------+-------------+-------------+-------------+
:The Recruited Audio Mixing Engineers -- Statistical Information


# Participant Responses

## DAW Platforms and Their Typical Use

Question 1 firstly concentrated on the participants' choice of DAW
platform(s) to determine the technical sophistication and audio
processing capability required of a DAW engaged in professional audio
mixing. This question also sought to establish the participants' typical
work-case scenarios and the role their DAW platform(s) played in
performing such work to achieve industry-standard results.

### The Prevailing Use of DAW Platforms

In all nine instances, the engineers' choice of DAW platform was
integral to their daily work. This sample size determined that most
studio configurations appeared to be an amalgamation of digital and
analogue technologies, with the DAW application serving as a centralised
input and output interface. There also appeared to be a differentiation
in the studio equipment used between recording and post-recording mixing
activities. Two participants, in particular, discussed mixing
"in-the-box", indicating a predominant use of insert and send software
plug-ins to perform signal and effects processing, which, in essence,
utilises a purely digital environment:

> "Just about all of my work is done on Pro Tools, and just about all of
> it is done in-the-box." -ME05
>
> "But so much work is in-the-box these days, that you'd want to use
> plug-ins you're used to using." -ME06

Two participants also talked specifically about their use of external
hardware processing units, in particular, explaining that their DAW use
employs a hybrid digital/analogue signal-processing configuration.
Interestingly, ME05 stated that engaging such external hardware is done
during the recording, rather than post-production mixing, phase of music
production:

> "When it comes to recording, though, I do use some of the outboard
> gear I've got here in the studio, like the \[Empirical Labs\]
> Distressor \[compressor\] and... the \[Universal Audio\] 1176
> \[limiting amplifier\]. I always use a preamp on the vocal mics just
> to warm them up a bit and just print them straight to Pro Tools along
> with a clean dupe track." -ME05
>
> "I think doing freelance jobs; you need to be across which plug-ins
> will do the job if there's no hardware, but, um, also you need, um,
> need to be across at least the usual outboard gear, you know, like a
> \[Universal Audio\] 1176 \[limiting amplifier\] or a \[AMS Neve\] 1073
> \[preamp and EQ\]." -ME07

Several participants discussed employing their DAW for its sequencing or
programming capability, incorporating that aspect of automated music
production, and in particular, their use of virtual instrument plug-in
software:

> "Apple Loops \[utility in Logic Pro\] is amazing for quickly getting
> ideas down." -ME01
>
> "In terms of MIDI, if it's a band thing, I'm happy to use MIDI stuff
> as well. I personally here try to use real instruments where I can.
> Depending on budget... I might use \[inMusic Brands'\] BFD \[virtual
> drum software\] ... and trigger them in.... I try and get real strings
> in where I can, but ... I use one, \[IK Multimedia's\] SampleTank 3
> \[sample-based sound workstation\]." -ME02
>
> "For a long time, I used Cubase as a sequencer, on occasion
> supplementing the MIDI tracks with some audio tracks, then mixing down
> to a stereo master audio track. Today, I'd say predominantly my
> production activities are... a pretty even blend of MIDI, external
> instrument tracks, VST instrument tracks and live audio tracks in the
> one project." -ME06
>
> "Logic made more sense \[because\] a lot of what I do is
> sequencer-based." -ME08

### The Range of DAW Platforms 

All told, the participants mentioned a total of nine DAW platforms, with
six used in their typical audio engineering and mixing work:

1.  BandLab Technologies' *BandLab*\* (BandLab Technologies, 2021);

2.  Steinberg's *Cubase Pro* (Steinberg Media Technologies GmbH, 2021a);

3.  Mark of the Unicorn's (MOTU's) *Digital Performer* (Mark of the
    Unicorn Inc., 2021);

4.  Apple's *GarageBand*\* (Apple Inc., 2021a);

5.  Ableton's *Live*\* (Ableton AG, n.d.);

6.  Apple's *Logic Pro* (Apple Inc., 2021c)

7.  Avid's *Pro Tools* (Avid Technology Inc., 2021);

8.  Cockos' *REAPER* (Cockos Inc., 2021); and

9.  Waves' *Tracks Live* (Waves Audio Ltd., 2021).

\* DAWs mentioned but not used by the participants.

One of the DAW platforms mentioned but not used by two participants was
*BandLab* (BandLab Technologies, 2021), the only web browser-based DAW
application of the nine DAW platforms. Both participants recognised
*BandLab* as being a platform capable of facilitating online
collaboration; however, neither expressed an interest in using it for
collaborative purposes:

> "BandLab... I wouldn't want to even try making a professional mix with
> those online DAWs; it would drive me crazy. It needs to be... a proper
> industry DAW like Pro Tools." -ME07
>
> "There is an online DAW out there called BandLab, which... I wouldn't
> want to use it for the sake of working with someone online." -ME09

While the browser-based user environment and cloud storage are well-suited
to online collaboration, the responses suggest that browser-based DAWs
such as BandLab, Spotify's Soundtrap (Spotify USA / Spotify AB, 2021), 
AmpTrack Technologies' Amped Studio (AmpTrack Technologies AB, 2021) and
Audiotool (Audiotool.com, 2021), are yet to see mainstream acceptance in
professional mixing of recorded music. While not explicitly discussed in
the interviews, this eschewing of browser-based DAWs could be due to their
incompatibility with existing VST-, AU- and AAX-based plug-ins.
Furthermore, while developer efforts have resulted in progressive
improvements to input and output latencies (wac2017 qmul, 2017), the Web
Audio API, upon which these DAWs are constructed, cannot provide the same
low-latency response as that seen in the long-established Audio Stream
Input/Output (ASIO) (Steinberg Media Technologies GmbH, 2020) or Core Audio
(Apple Inc., 2017) protocols.

Interestingly, several engineers mentioned utilising at least two DAW
applications depending on the type of work:

> "So, I use two different systems; I use Logic Pro X for all my
> writing, production, and quite a bit of mixing as well. But, for any
> post-production stuff that I do, it's all Pro Tools because every time
> I try and mix a film project in Logic, \[there are\] problems." -ME01
>
> "Most often, the stuff that I would use, being live, ... I use Waves
> Tracks Live, or I use REAPER, ... just because the primary function
> that I'm looking for is rock-solid, reliable... recording of large
> files and long times... and large track count... if we're doing some
> mixdown stuff, it would either be... Digital Performer or... Logic and
> the occasional Pro Tools, but not as much." -ME03
>
> "I predominantly use Pro Tools... I also run Logic. Pro Tools is my
> main thing for the last 12 years... I mix in that; I produce in that;
> I record in that. Logic I've used probably the last six years. That is
> more a writing tool for me." -ME04
>
> "Just about all of my work is done on Pro Tools... occasionally, I'll
> use Logic if there's some programming needed... like... a synth pad or
> loop thing, but all of that ends up as tracks in Pro Tools anyway."
> -ME05

From the data, it appears that some audio engineers consider *Pro
Tools*, for instance, as a DAW platform valued for its audio recording
and mixing capability but prefer *Logic Pro* for sequenced content.
There also appears to be different performance requirements of a DAW
platform between studio and live environments. Both engineers who
perform live recordings favour a DAW platform known for its reliability
but is not necessarily as sophisticated as those employed in the studio
environment. ME03 stated that the choice of using *Tracks Live* or
*REAPER* for live work is because "*those platforms are arguably the
most stripped-down, featureless, boring set-ups around, but that's why I
use them*."

Nevertheless, *Pro Tools* was the most used and referred to DAW platform
in the sample, exclusively utilised by two participants and in
conjunction with another DAW platform by another three participants.
Notably, all nine participants mentioned *Pro Tools* at least once in
their interviews, suggesting it is considered the most prevalent DAW of
the music industry and the proverbial yardstick to measure the
performance and features of other DAW platforms. Intriguingly, however,
three of the five *Pro Tools* users also employ another DAW platform,
mainly to compensate for what appears to be an apparent weakness in
sequencing/programming capability and ease of use:

> "Mixing quickly when you've got to get stuff done, I find \[Logic\]
> much faster than Pro Tools." -ME01
>
> "So, I found Logic sometimes to be quicker to write in than Pro Tools,
> just because the virtual instruments are... all built into it." -ME04

Figure 1 presents the breakdown of the choice of DAWs across the nine
participants.

![The choice of DAW platform(s) per participant](./media/image1.png){width="5.709145888013999in"
height="3.4242760279965005in"}

However, analysing the data further and concentrating on which DAW
platform is exclusively, or predominantly, used for studio-based
post-production audio mixing, *Pro Tools* is the DAW of choice for five
participants, *Cubase Pro* for two and *Logic Pro* for one. ME03, who
stated that when "doing some mixdown stuff, it would either be...
*Digital Performer* or... *Logic* and the occasional *Pro Tools*, but
not as much", did not differentiate between *Digital Performer* and
*Logic Pro*. Therefore, they have been attributed to the
participant, but with a 50% weighting. Figure 2 shows this distribution
of DAW platforms for studio-based audio mixing.

![The distribution of chosen DAW platforms for studio-based
audio mixing](./media/image2.png){width="5.709145888013999in"
height="3.4242760279965005in"}

### Typical DAW Work-Case Scenarios

The participants discussed three discrete music production activities,
for which their chosen DAW platform(s) played an integral role:

1.  Studio-based audio recording;

2.  Studio-based post-production audio mixing; and

3.  Live multitrack audio recording.

The audio material requiring post-production mixing was sourced mainly
from either studio recording sessions conducted by the participant or
from clients with audio files recorded elsewhere. In addition to these
activities, ME01 discussed post-production audio mixing for film by
importing video and specific DAW export file formats into a *Pro Tools*
session:

> "They send me film, and they also send me an AAF \[Advanced Authoring
> Format file\] or an OMF \[Open Media Framework file\], which is out of
> their editing \[software\] ... It has volume, gain clip... sometimes
> it has panning... but the main thing is all the audio is locked in
> with the film, and it's very... frame-accurate." -ME01

However, mixing for this medium appears to be a specialised practice
considering only one of the nine participants mentioned this facet of
post-production audio mixing. Furthermore, the two live mixing engineers
discussed their DAW use for capturing live multitrack performances for
later post-production audio mixing:

> "If you can imagine a live show that I've multitracked, the idea is
> that those tracks be turned into something that will be commercially
> released as a record, or... B-Sides or DVD." -ME03
>
> "Anyway, that's what I do, studio recording and post mixes, and live
> front-of-house mixing..., desk recordings and post-production." -ME09

Though not expressly mentioned, the engineers presumably export their
multitrack recordings as audio stems for importing into the DAW platform
better suited for such work than the one employed to capture the
recordings.

Interestingly, some of the participants, who engage in post-production
audio mixing of source material recorded outside of the participants'
studios, expressed a reluctance or apprehension when approaching this
type of music production work:

> "Yeah, I... do a little bit of that, but most of the stuff I record
> here. I just want to hear \[the recorded material\] first because
> oftentimes I find people's expectations if they've recorded at home
> and it's... terribly recorded... they think that sending it to me it's
> going to sound like a Foo Fighters album or something, which is
> obviously not the case. -ME02
>
> "The bulk of my work is recording and post mixing. I have done just
> some post mixing of tracks produced elsewhere, but... I prefer not to
> work that way.... I don't mix a lot of other people's studio work...
> it's a challenge when I do, which I suppose is not that bad, but it
> takes more time that I don't always have or could be better spent
> doing other work." -ME05

Conversely, ME07, who works as a freelance audio mixing engineer,
specialises in mixing recordings produced by other audio engineers, and
ME08 expressed enjoyment in such mixing work:

> "As for the type of work I do, it's pretty much freelance
> post-production mixing." -ME07
>
> "I occasionally get some post-production work thrown my way, which I
> really enjoy actually." -ME08

Given such divergent responses, it appears that whether a mixing
engineer works with audio they did not record or not comes down to a
personal preference.

## Prevailing Use of Keyboard Shortcuts and Control Surfaces

This question queried the participants using two existing methods of
remotely operating a DAW application: keyboard shortcuts and control
surfaces. The reasoning for this particular line of inquiry was to
establish if using such methods was inherent in the participants'
established work routines.

All nine participants emphasised their use of keyboard shortcuts as
being integral to their workflow, attributing the expediency their usage
provides:

> "Keyboard shortcuts, for anyone who has been producing for a while,
> are like the "golden child" in every studio. Everyone has their own
> ones, and they save you so much time." -ME01
>
> "I use the shortcuts; if... there's something that I'm doing... in Pro
> Tools, I'm like, 'That could be a lot faster', then I'll look for a
> shortcut. Most of the things that I need I have shortcuts." -ME02
>
> "I use keyboard shortcuts all the time; in fact, I can't imagine how I
> worked before them. The more I don't have to touch the mouse, the more
> I don't have to take time finding some command in a menu, the better."
> -ME05
>
> "Keyboard shortcuts streamline my workflow and makes setting up a
> project so much quicker than using a mouse." -ME06

Six participants mentioned they had integrated a control surface
configuration into their extended DAW architecture. The reasons given
for why the participants included the use of a control surface into
their workflow were twofold: for the tactile operation when automating
DAW-specific events, and for the perceived superiority and ease compared
to using a mouse:

> "When you're automating something by \[a mouse\], it's a lot different
> to when you're moving it by feel, by your hands. So, I think \[there
> are\] definitely advantages to \[control surfaces\], and... when I'm
> mixing a song and doing something creative, I'll use faders." -ME01
>
> "Maybe it's just that I came up from the old-school of physical
> consoles: knobs, buttons, switches and faders. That is definitely my
> comfort level... the world of automation... roughing things in if you
> like.... I always prefer to have something that reflects \[my hands\]
> rather than a mouse." -ME03
>
> "Right now, I use the \[Avid\] S3, and I don't know how I got on
> without it... it has all the control I need right there, and I find
> myself looking less and less at the mixer on-screen.... I really like
> the feel of faders under my fingers. It makes me feel like I'm still
> keeping in touch with what mixing has always been about: ... things
> you can touch and move while you listen." -ME05
>
> "I've also been using a Mackie MCU and MCU Extender control surface
> set-up for the past 5 or 6 years.... I like the... tactile response I
> get from real faders and rotary encoders when I'm mixing." -ME06

Interestingly, at the time of the interviews, some of the participants
who did not employ a control surface expressed a desire to do so in the
future, suggesting that such devices, and their use in audio mixing
activities, are becoming *de rigueur*.

## Experience with Existing DAW-Integrated Collaboration Features

Of the nine participants interviewed, seven worked with DAW platforms
that feature integrated online collaboration features. *Pro Tools* users
can access the asynchronous file and project sharing feature, *Cloud
Collaboration*. In contrast, the *Cubase Pro* users have two
collaborative options, the synchronous remote performer recording
system, *VST Connect*, and the asynchronous file and project sharing
approach facilitated by *VST Transit*. Given that these seven
participants had a readily available means of online collaboration
provided by their DAW platform, it was helpful asking them about their
level of familiarity and practical experience with these two forms of
collaboration to determine their current degree of engagement in such
activities.

### Avid's Pro Tools: Cloud Collaboration

Of the five participants who used *Pro Tools* for their post-production
audio mixing work, four said they had not used *Cloud Collaboration*,
and even then, the one participant who had, ME04, had only tried it
once. Furthermore, ME07 was not particularly aware of its existence:

> "I haven't used it at all. It... vaguely sounds... familiar, you know,
> I may have read something or heard someone... I really can't imagine
> why I'd use it, to be honest." -ME07

As to why the four participants who were familiar with *Cloud
Collaboration* chose not to use it, their responses derived several
themes:

-   A reluctance to share the *Pro Tools* project file lest a
    collaborator makes unwanted and permanent changes. As an aside,
    *Cloud Collaboration* has track ownership and automatic version
    saving mechanisms that can potentially circumvent such issues,
    suggesting that despite the participant's awareness of *Cloud
    Collaboration*, there are aspects of its workflow that are not fully
    understood:

    -   *"It's definitely something I'm interested in, and I can see it
        being... a great thing in the future, but... the problem is it
        relies on everyone having the same set-up and no one screwing
        the files up, and they're two things I'm very precious about."
        -ME01*

-   *Cloud Collaboration's* practice of file sharing through cloud
    storage is a collaboration method already exploited by the
    practitioners through existing third-party cloud storage platforms:

    -   *"My other thing with it, you only get that 1 GB of storage
        unless you pay for more... I've already paid for enough
        subscriptions with Dropbox." -ME04*

    -   *"I haven't used it cause it's so similar to what I already do.
        Seriously, the only difference I could see from... what I
        usually do using Dropbox is saving a bit of time importing
        changes directly into Pro Tools." -ME05*

-   Despite employing lossless file compression to maximise cloud
    storage, users will typically require increased storage capacity the
    more projects they choose to share in this fashion. However, with
    increased storage comes increased cost, an imposition some of the
    participants were unwilling to bear, as seen in ME04's comment above
    for instance:

    -   *"If you want to pay for the Pro Tools subscription, you pay for
        that and... I don't want to pay more money... for something that
        works, but it only works for Pro Tools." -ME04*

    -   *"The more you use it, the more storage space you need, and
        they're asking for another \$300 US for the privilege. That
        difference isn't worth \$400 a year when I already pay a yearly
        Dropbox subscription that essentially does the same thing."
        -ME05*

-   ME02 provided a different perspective on the theme of an additional
    cost. Owing to the choice of hardware, also produced by Avid, that
    integrates with *Pro Tools*, the participant operates an earlier
    version of *Pro Tools*, as later versions are incompatible with the
    hardware without additional expense. However, the version the
    participant uses does not feature *Cloud Collaboration.* As ME02
    describes the dilemma:

    -   "\[With\] *my HD Native Thunderbolt* \[interface\]*, for me to
        upgrade to the latest version of Pro Tools... Avid wanted
        something like... around \$900 US or something in that vicinity
        for the driver. It's something I've already paid like \$8000
        for... I don't see why I should have to pay that much money."
        -ME02*

-   ME04 also discussed a prerequisite for this collaboration model with
    other colleagues: each person requires *Pro Tools*. However, as the
    participant pointed out, this prerequisite cannot be taken for
    granted:

    -   *"I work with a lot of artists, especially recently* \[who are\]
        *running Ableton or running Logic or running GarageBand for Mac.
        You can't tell them to go get Pro Tools just to do a*
        \[collaboration\] *session." -ME04*

### Steinberg's Cubase Pro: VST Connect and VST Transit

#### VST Connect

Both participants who chose to utilise Cubase Pro for their studio-based
audio mixing also employed *VST Connect* for its real-time remote
performer recording capability. ME06 and ME09 noted the importance of an
accessible high-speed Internet connection, something that, in Australia,
has only been available since the mid-2010s (Gregory, 2019):

> "The first time I did use \[VST Connect\] was to record a guitarist...
> \[in\] 2014 or 15... using VST Connect SE... and it didn't work all
> that well. There were just too many dropouts for any of it to be
> useful. I did revisit it, though, when I got... a 50 Mbps connection
> and... the Pro version of VST Connect.... This time I used it to
> record vocals, and it worked really well." -ME06
>
> "When Steinberg came out with Connect Pro... I was sceptical... It
> wasn't till I got \[high-speed broadband\] connected that I
> investigated it a little more, and I was... really surprised at the
> automatic configuration." -ME09

Both participants acknowledged that they still encounter sporadic jitter
and audio dropouts with the performer's streamed audio; however, the Pro
version of *VST Connect* provides post-session transmission of a
high-resolution audio recording of the performer, stored on the
performer's computer, which automatically replaces the streamed audio in
the *Cubase Pro* project. The participants pointed to this functionality
as a highly-valued feature:

> "I also got the Pro version of VST Connect, even though it cost me to
> do it, mainly because \[it\] could let you transfer a high-quality
> recording of the performer to replace the live-streamed version after
> the recording session." -ME06

The participants mentioned *VST Connect'*s video communication as a
positive way to interact with the remote performer, distinguishing it
from other similar collaboration platforms:

> "The video is great, too; I didn't have that with \[an alternative
> remote recording platform\]. Yeah, it's a really useful add-on to
> have." -ME09

#### VST Transit

In stark contrast to the participants' uptake of *VST Connect*, neither
of them chose to use the *VST Transit* method of collaboration,
mirroring the response received by those participants who utilise *Pro
Tools*. Again, the dominant reason behind their decision owes to the
similarity in functionality with the participants' existing remote
collaboration practices co-opting existing third-party cloud storage
solutions and the extra cost of additional storage capacity:

> "With VST Transit, I've also checked it out, but it's really similar
> to just using Dropbox to share your files.... I guess it's another way
> for people to connect, but it's not something I really need
> considering I'm already paying for a Dropbox subscription." -ME06
>
> "\[VST Transit is\] just another cloud storage and sharing thing that
> I do already using Dropbox or Google Drive. I don't really need to
> share my recordings with anyone; I just send a mix." -ME09

ME09 identified a similar issue with *Pro Tools* and *Cloud
Collaboration*, in that collaborating with *VST Transit* requires the
other collaborators also to have a recent version of *Cubase Pro* to
access the project and audio files:

> "From what I can tell, \[VST Transit is\] a way to share your Cubase
> projects, and I don't know too many other people also using Cubase,
> which, um, kind of makes it unnecessary, really." -ME09

However, *VST Transit Join* (Steinberg Media Technologies GmbH, 2021b)
is a more recent add-on to *VST Transit* that allows collaborators with
DAW platforms other than *Cubase Pro* to access and contribute to the
shared *Cubase Pro* project.

## Existing Remote Collaboration Practices

Aside from the two instances of remote recording collaboration, as
already alluded to in the previous section, those participants who
engage in collaboration practices with (mainly) clients outside of the
studio environment do so in an asynchronous, file sharing environment
employing third-party free or subscription cloud storage platforms.
*Dropbox* (Dropbox Inc., n.d.) was mentioned at least once by all but
one of the participants throughout the interview process. Overall, the
participants discussed the use of the following cloud storage platforms
for collaboration purposes:

-   *Dropbox*;

-   *Google Drive* (Google LLC, 2020);

-   *WeTransfer* (WeTransfer, 2021); and

-   *iCloud* (Apple Inc., 2021b).

Interestingly, cloud-based applications designed explicitly for DAW
project backup, version cataloguing and rollback and remote collaboration,
such as *Splice Studio* (Splice.com, 2022), were not mentioned. It could
well have been that the participants were unaware of such platforms or,
as seen with *Cloud Collaboration* and *VST Transit*, their similarity to
existing cloud storage platforms precluded their adoption.

Figure 3 shows the range and choice of cloud storage options across
eight of the nine participants. Note that ME03 did acknowledge the ease
of file sharing today but did not mention any particular platform.

In addition to cloud storage, some of the participants discussed a
secondary collaboration means of communicating with clients, for
instance, a third-party videoconferencing platform:

> "I've had situations where I've actually got advertising clients
> overseas via Skype, dialled in listening to the voice-over session
> live.... They just want to make sure that the voice-over is what they
> want... and I'm just a puppet here pressing buttons." -ME01
>
> "I would chat to them, have a Zoom chat, and then just do my mixing
> and send the mix back and go back-and-forth." -ME04

![The choice of cloud storage platform(s) per participant](./media/image3.png){width="5.709145888013999in"
height="3.4242760279965005in"}

Furthermore, some collaborators still prefer to use written instructions
and feedback through the exchange of emails, while others will speak to
the client directly over the phone:

> "If it's a band \[I am mixing\], I always say, 'You guys discuss it as
> a band, and then one person, I'll deal with one person only, you email
> me back and forth, and we can discuss whatever problems'." -ME02
>
> So, again, Dropbox is the way to go and either speak on the phone or
> email for any edits." -ME06
>
> "Really, it's just as simple as uploading the mix once I think it's
> ready and usually a phone call to the client to go over what I've done
> and work out if there's any changes needed." -ME09

However, irrespective of the chosen means, it is apparent that once an
audio mix is shared, the mixing engineer requires a reciprocal mode of
communication with the client(s) to develop the mix further and ensure
the final product meets expectations. File sharing via cloud storage is
only one part of the equation contributing to a collaborative mixing
effort.

One of the significant facets of the participants' asynchronous
collaborative approach is the iterative, back-and-forth nature of their
interactions, communications, and ultimately, the audio mix development.
Some acknowledged that this methodology is not ideal; however, given the
uniform approach to remote collaboration, it appears to be accepted as
an industry-standard way of working:

> "So, I'll prepare the session once we've got a file that's okay...
> I'll just send them a bounce of the... song, give them the \[tempo\]
> so they can load it into whatever \[DAW\] they're using, they record
> the parts from zero, and then they send those back." -ME01
>
> "The collaboration of sending files back and forth constantly, it's a
> lot easier these days than it used to be. There used to be a time when
> we would literally 'Fed-Ex' hard drives over to them, over 'the pond'
> because it was easier than trying to do it online." -ME03
>
> "I would chat to them, have a Zoom chat, and then just do my mixing
> and send the mix back and go back-and-forth." -ME04
>
> "So... Dropbox works, but it's a slow and a repetitious way of
> working, especially when I can make... remote recordings in the
> studio." -ME06

## Professional Expectations of a Real-Time Remote Collaboration Environment

When asking the participants to provide a wish-list of capabilities,
features and environmental conditions of an idealised and hypothetical
real-time remote audio mixing or music production collaborative milieu,
some needed clarification to conceptualise the environment readily:

> "Okay, so, like, I'm working in here on Pro Tools, and I'm connecting
> to someone else at the same time? Is that what you mean? Sorry, this
> is a real curveball \[because\] it's something I've never thought
> about... and correct me if I'm wrong, it's something we've never been
> able to do, right?" -ME05
>
> "Right, so, just to be clear, you're talking about working online with
> a client, not a client working with you in the studio.... This is not
> like \[VST\] Performer? You're not talking about remote recording?"
> -ME09

Despite the hesitant start for some, the participants' responses
revealed some common themes. Chief among them was the need for clear and
effective communication. Indeed, several participants articulated a
desire for an audio/visual communication link, preferring the spoken
word over a text-based chat feature:

> "They have to be able to hear me the whole time. I'd love to be able
> to see what's going on... a good talkback system, real-time, and
> vision of what's going on." -ME01
>
> "I would want to have a video link, so... they can see me, and I can
> see them. I'd want to have a separate audio track that's... just a
> link that I can talk to-and-fro to the client." -ME02
>
> "I want to know what the other person is doing, so I'd definitely want
> to be able to see and speak to the person as we work... I'd want to
> see what the other person is doing and talk through what's
> happening... like what would happen if I had that person working with
> me." -ME05
>
> "I think we'd both need to talk to each other as we go about working.
> If we're developing a post-production mix, let's say, then it's
> important that we can talk through what's needed and how to execute
> those moves." -ME09

Similarly, some of the participants nominated a high-quality audio
monitoring capability as a critical aspect of the collaborative
environment, linking their ability to mix at an industry-standard level
of expertise with their ability to hear the mixing project in as high a
resolution as they would in a studio environment:

> "I want to hear what's going on, be able to give them directions, so
> it has to be very clear. So, \[a\] very clear monitoring path." -ME01
>
> "I continue to monitor the mix in the studio the same way, not some
> glitchy audio streamed from the other person. I want to hear the mix
> the way it sounds coming straight from the DAW." -ME05
>
> "I'd want it to run like we're both there at the mixer console hearing
> the same thing as we mix.... But you'd want to hear what the other
> person is doing as though you're both in the same listening
> environment and working with the highest audio resolution... as you
> would in your own studio." -ME06
>
> "Okay, well, first up, I need to hear the mix in optimal conditions."
> -ME07

Several participants not only expressed their vision of the
collaboration involving the use of a DAW platform, but they also
articulated a desire to maintain their usual degree of localised control
over that DAW's operation. Some of the participants appeared to harbour
concern over losing creative control of the mixing project and wanted to
ensure that they could preserve a professional mixing standard:

> "I'd want to keep using Pro Tools exactly the same way I use it now.
> I'd want to be able to control what happens and not have someone else
> make changes that I don't know about until the session's updated."
> -ME05
>
> "The most obvious thing would be that I continue to use Cubase the way
> I currently have it configured. I wouldn't... like having to import
> the stems into another type of DAW just to do the collaboration. I'd
> want to make sure I've got control over the DAW.... I'd like to know I
> still have the same level of control over the project." -ME09

Suppose there is a theme that eloquently encapsulates the broad vision
of the participants as a cohesive group of professional practitioners.
In that case, it is the hope for the collaborative environment and
functionality to closely resemble the experience of being in the one
studio space together:

> "It's got to be like I was sitting there in the studio... Basically,
> everything that I would get by sitting there in the studio, I would
> want that." -ME01
>
> "Like what would happen if I had that person working with me... in
> here, in the studio." -ME05
>
> "I'd want it to run like we're both there at the mixer console hearing
> the same thing as we mix." -ME06
>
> "You'd really want it to be like you're in the studio together." -ME07
>
> "If I could have an environment that's as close to the experience of
> two people working in the studio together, I think that's the best you
> could wish for." -ME09

## Demand for Multiparty Remote Collaboration 

The participants were not as unified in response to being asked to
provide an opinion on the apparent worth of conducting a remote
collaboration session with multiple parties as they responded to the
previous question. Two participants did recognise the value in
collaborating within a multiparty environment:

> "What... often happened with me was, just purely by fact of geography,
> the bands I was working with are US-based, and I was Australia-based,
> so I was only over there during tours, typically. I wouldn't be able
> to be in the studio if they're grabbing multitracks and potentially
> doing some overdubs.... There were often situations where another
> engineer would take over locally because they could be in the room
> with the band working one-on-one. They would be listening to what I
> put down cause it's live, and they would be asking questions about how
> I got that, how I treated the audience mics for the stems that I've
> sent and how I've got certain sounds, how I cleaned up certain
> things.... It was difficult because it always had to be done verbally;
> there was no easy way that I could demonstrate it. Doing something
> remotely where I can... input directly into what they're listening to
> would have been huge." -ME03
>
> "Actually, thinking about it, I can see maybe in TV or film post that
> would work... a professional team who know what they're doing: the
> editor, foley, sound designer. That would be good." -ME05

Nevertheless, the general impressions gleaned from the remaining
participants' responses were that they either could not conceive of a
situation in their current practice when such a collaboration would be
necessary or believed a multiparty collaboration would be unworkable:

> "I'm not really sure why you'd want to \[collaborate with multiple
> parties\] ... it could get messy the more people you have moving
> faders and so on." -ME06
>
> "I've done plenty of mixing with the band in the control room with me,
> but they're not sitting at the console moving faders with me.... I
> could handle working one-on-one with someone who knows what they're
> doing, but I don't think working in a group would be all that
> productive, really." -ME07
>
> "I really don't think that kind of thing would be necessary. I can see
> the value of working with a client because that's the kind of work I
> do, but I really don't think I'd use any kind of group collaboration."
> -ME08
>
> "You'd want to make sure everyone knows what they're doing; otherwise,
> it could get really messy, really quick. I suppose there could be a
> time and place for such a thing, but I think that might be stretching
> the boundary a bit." -ME09

#  Discussion

There are several crucial findings evident in the totality of responses
from the nine participating audio engineers:

**The DAW Platform**

While, undoubtedly, Avid's *Pro Tools* appeared to be the most popular
platform of choice, it was by no means the only one that studios and
engineers adopted for their audio mixing activities. Indeed, when
concentrating specifically on the DAW platforms utilised in professional
audio mixing practices, the data showed that, in addition to *Pro
Tools*, Steinberg's *Cubase Pro*, Apple's *Logic Pro* and MOTU's
*Digital Performer* appeared to serve the engineers' required purposes
equally as well.

An industry-based inquiry, conducted in 2017 by Ask.Audio, a website
resource for "digital music makers" (Sethi, 2018), reflected this
pattern of DAW use. 30, 611 survey responses determined the top-12
primary-use DAW platforms, according to the musicians and producers who
participated. The fact that a top-12 illustrates the breadth of the
global DAW market; nevertheless, the four applications with the highest
userbase were: *Ableton Live*, *Logic Pro*, *Pro Tools* and *Cubase*
(see Figure 4). This result aligned with the interview data and pointed
to a degree of commonality in utility and capability across the most
universally used DAW platforms.

![The results of Ask.Audio's survey on the respondents' choice
of DAW platform (Adapted from (Sethi, 2018))](./media/image4.png){width="5.709145888013999in"
height="3.4242760279965005in"}


**The Prevailing Use of Keyboard Shortcuts and Control Surfaces**

The prevalence and intrinsic use of keyboard shortcuts, evidenced in the
participants' responses, spoke to the importance of time-efficient and
expedient audio mixing processes. Similarly, the participants' responses
pointed to a current or intended addition of a control surface to their
typical DAW operation and mixing practices, again iterating the
advantages of their use.

**The Uptake of DAW-Specific Remote Collaboration Features**

Taking an overarching view of the interview responses, the most
prominent finding was, of those participants whose chosen DAW platform
included a specific asynchronous file and project sharing capability by
way of specialised cloud storage, not one utilised this DAW-integrated
collaboration feature. However, it would be misleading to conclude that
the participants eschewed this mode of collaboration. Indeed, in most
cases, this lack of uptake is owed to the participants having already
adopted a form of asynchronous collaboration with clients that co-opts
third-party, commercial cloud storage platforms.

Consequently, the interview responses offered an impression that
professional studios and engineers are already engaged in remote
collaboration practices; however, the model implemented is asynchronous,
iterative and has the potential to be time-consuming and inefficient.
While some participants admitted that this practice was not an ideal use
of their time, and others remarked on the simplicity of the approach for
working with clients outside of the studio environment, only one, ME01,
described a synchronous means of remote collaboration, in this instance,
running a concurrent videoconferencing application while conducting an
in-studio voice-over session.

**Industry Expectations of Real-Time Remote Music Mixing and Production
Collaboration** Asking participants to enumerate the prominent features
and capabilities a hypothetical "ideal" real-time remote collaborative
environment provided the following shortlist of features:

1.  A clear, practical and synchronous audio/visual means of
    communication, available to all collaborators throughout the
    session;

2.  The ability to monitor the collaboration's mixing and production
    activities in the highest fidelity possible, preferably, the exact
    resolution as that typically monitored in-studio;

3.  DAW-based mixing and production operations, providing control over
    the changes and edits made to the DAW project; and

4.  A collaborative environment and mode of operation that closely
    aligns with the experience of working in person in the studio.

**The Perceived Utility of Remote Multiparty Music Mixing and Production
Collaboration**

Most of the participants' responses did not support the need for a
multiparty capability. However, ME03 favoured a collaborative
environment inclusive of multiple parties, providing a post-live
recording scenario that would benefit from remote multiparty
collaboration. Such an instance can be considered a specialised facet of
live mix engineering, not typical of local studio-based work; therefore,
it was not necessarily surprising that some participants could not
conceive of a situation where multiparty collaboration would be
required. Indeed, some participants supposed that such collaboration
would be chaotic and not especially conducive to a cohesive workflow.

# Conclusion

This article presented a qualitative research study that
phenomenologically analyses the current use of DAWs, their role in audio
mixing and post-production, features used for remote collaboration and
current professional practices. After conducting semi-structured
interviews with nine Australian-based professional audio mixing
engineers, the study involved collecting, interpreting, and presenting
the data. Accordingly, the study resulted in the identification of
several significant inductive insights.

DAWs play an integral role in professional audio engineers work and
practice, with Pro Tools being the most popular platform. Typical DAW
use includes activities, such as studio-based audio recording,
studio-based post-production audio mixing and live multitrack audio
recording. Although audio mixing is a collaborative process, and some
DAW platforms provide native collaborative features, practitioners tend
not to use these features in typical day-to-day work. Several reasons,
including costs, such as license fees, force the participants to use a
single DAW platform by all collaborators. The availability of alternate
cost-effective cloud storage solutions (such as Dropbox) that can provide
facilities for audio file-sharing make such features redundant. Audio
mixing with remote clients by professionals typically entails sharing
audio files/recordings by an audio engineer, who mixes and provides audio
files for review and feedback. This method can be an iterative process.
Professional audio engineers did not envision a need for multi-party
remote collaboration. Instead, several participants perceived this
approach as chaotic, leading to the audio engineer losing control of the
project. When queried for an “ideal” remote collaborative environment for
audio mixing, a unique insight was that audio engineers envision it to be
an experience similar in “look and feel” to the participants working in
the “same” studio. That is, all collaborators communicate synchronously,
comparable to an in-studio experience. The audio mixing actions of any
collaborator are viewed in “real-time” by all and played in high-resolution
using the studio’s equipment. The “virtual studio” experience in remote
collaboration is similar to an in-studio experience. Given the trend the
participating engineers suggest, any future endeavours for a remote
collaborative environment could consider achieving this goal.

# References

Ableton AG (n.d.). Live (Version 11) \[Computer Program\]: Ableton AG. 
Retrieved 1 August 2021, from https://www.ableton.com/en/live/

AmpTrack Technologies AB. (2021). Make music online - Amped Studio online sequencer. 
Retrieved 1 August 2021, from https://ampedstudio.com/

Apple Inc. (2017). What is Core Audio? 
Retrieved 16 June 2020, from 
https://developer.apple.com/library/archive/documentation/MusicAudio/Conceptual/CoreAudioOverview/WhatisCoreAudio/WhatisCoreAudio.html

Apple Inc. (2021a). GarageBand for Mac (Version 10.4.3) \[Computer Program\]: Apple Inc. 
Retrieved 1 August 2021, from https://www.apple.com/au/mac/garageband/

Apple Inc. (2021b). iCloud. 
Retrieved 1 August 2021, from https://www.icloud.com/

Apple Inc. (2021c). Logic Pro (Version 10.6) \[Computer Program\] Cupertino, United States of America: Apple Inc. 
Retrieved 28 July 2021, from https://www.apple.com/au/logic-pro/

Audiotool.com. (2021). Audiotool - Free Music Software - Make Music Online In Your Browser. 
Retrieved 1 August 2021, from https://www.audiotool.com/

Avid Technology Inc. (2021). Pro Tools (Version 2021.6) \[Computer Program\] Burlington, United States of America: Avid Technology Inc. 
Retrieved 28 July 2021, from https://www.avid.com/pro-tools

BandLab Technologies. (2021). BandLab: Make Music Online. 
Retrieved 1 August 2021, from https://www.bandlab.com/

Cockos Inc. (2021). REAPER (Version 6.33) \[Computer Program\] New York, United States: Cockos Inc. 
Retrieved 18 December 2020, from https://www.reaper.fm/download.php?from_reaper=1

Dropbox Inc. (n.d.). Manage Your Work More Efficiently - Dropbox Professional. 
Retrieved 1 August 2021, from https://www.dropbox.com/pro

Google LLC. (2020). Google Drive: Free Cloud Storage for Personal Use. 
Retrieved 7 March 2020, from https://www.google.com/drive/

Gregory, Mark A. (2019). How to Transition the National Broadband Network to Fibre To The Premises. 
*Journal of Telecommunications and the Digital Economy, 7*(1), 57-67. 
DOI: https://doi.org/https://www.doi.org/10.18080/jtde.v7n1.182

Mark of the Unicorn Inc. (2021). Digital Performer (Version 11) \[Computer Program\]: Mark of the Unicorn Inc. 
Retrieved 1 August 2021, from https://motu.com/en-us/products/software/dp/

Sethi, Rounik. (2018). Top 12 Most Popular DAWs (You Voted For). *Ask.Audio*. 
Retrieved 2 August 2021, from https://ask.audio/articles/top-12-most-popular-daws-you-voted-for

Smith, Jonathan A. (2004). Reflecting on the development of interpretative phenomenological analysis and its contribution to qualitative research in psychology. *Qualitative Research in Psychology, 1*(1), 39-54. DOI: https://doi.org/https://doi.org/10.1191/1478088704qp004oa

Splice.com. (2022). Collaborate with Splice Studio \| Splice. 
Retrieved 4 February 2022, from https://splice.com/features/studio

Spotify USA / Spotify AB. (2021). Soundtrap - Make music online. 
Retrieved 1 August 2021, from https://www.soundtrap.com/

Steinberg Media Technologies GmbH. (2020). Technologies \| Steinberg. 
Retrieved 17 June 2020, from https://www.steinberg.net/en/company/technologies.html

Steinberg Media Technologies GmbH (2021a). Cubase Pro (Version 11.0.3) \[Computer Program\] Hamburg, Germany: Steinberg Media Technologies GmbH. 
Retrieved 11 November 2020, from https://new.steinberg.net/cubase/new-features/

Steinberg Media Technologies GmbH. (2021b). VST Transit: Music cloud collaboration \| Steinberg. 
Retrieved 1 August 2021, from https://new.steinberg.net/vst-transit/?et_cid=15&et_lid=22&et_sub=VST%2520Transit

wac2017 qmul. (2017). *Web Audio Conference 2017 (WAC2017 QMUL) Day 1 - Afternoon* \[Video File\] 
Retrieved 2 June 2020, from https://www.youtube.com/watch?v=OpUeyRRPpCo&feature=youtu.be&t=957

Waves Audio Ltd. (2021). Tracks Live - Multitrack Recording Software \| Waves. 
Retrieved 1 August 2021, from https://www.waves.com/mixers-racks/tracks-live#presenting-tracks-live

WeTransfer. (2021). Products \| WeTransfer. 
Retrieved 1 August 2021, from https://about.wetransfer.com/en/products/

# Appendix: Interview Guide Questions

## Question One:  {#question-one .list-paragraph}

What DAW platform do you use for your typical music production
activities, and what do those activities involve?

## Question Two: {#question-two .list-paragraph}

How integral are keyboard shortcuts and/or the use of a control surface
to your workflow, and why?

## Question Three: {#question-three .list-paragraph}

If the chosen DAW platform is either Pro Tools or Cubase Pro, have you
had any experience using their integrated collaboration features (i.e.
Cloud Collaboration, VST Connect Pro/VST Connect Performer, and VST
Transit/VST Transit Join)? If so, how did you use the feature, and what
are your impressions?

## Question Four: {#question-four .list-paragraph}

Have you had any experience collaborating on a music production project
with a remote studio or participant? If so, how was that achieved, and
what are your impressions?

## Question Five: {#question-five .list-paragraph}

If you wanted to collaborate on a music production project with a remote
engineer/producer in real-time, what would be your wish-list in terms of
functionality and workflow? (For example, access to the DAW project,
communication means, creation and quality of audio files, or editing
capabilities).

## Question Six: {#question-six .list-paragraph}

If not already mentioned, how useful would it be to extend this
collaboration functionality and workflow to multiple remote
engineers/producers in real-time? If so, in what way?

