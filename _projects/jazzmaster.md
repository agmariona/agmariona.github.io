---
layout: page
title: JazzMaster
description: An automatic accompaniment system for jazz music
# img: /assets/img/12.jpg
importance: 1
# category: work
---

My senior thesis from Harvard. Read the full thesis <a href="{{
"jazzmaster.pdf" | prepend: '/assets/pdf/' | relative_url}}">here</a>.

---

#### Abstract:
> Jazz is a musical genre which focuses heavily on improvisation in a group
setting. In order to practice and improve, musicians must frequently play a
wide variety of songs with others. Beginners or other musicians who do not have
access to a band or practice group need a system which provides a suitable
replacement experience. We design and implement a system which can accompany a
soloist playing an arbitrary melody in real-time. If the melody is recognized
to be that of a known jazz standard, the device will follow along to that
standard. If the melody is not recognized, or if the player deviates from a
known melody, the device will comp with a suitable, conventional chord
progression.
> 
> The project consists of three main tasks: identifying a melody, deter- mining
a suitable accompaniment, and playing the accompaniment. All of these tasks
present primarily signal processing challenges. Iden- tifying the melody
involves parsing a raw audio waveform into a programmatic representation. Such
a representation can then be used to produce an accompaniment by matching to a
database of known melodies and performing musical transformations to generate
an ap- propriate harmony. Finally, the device must actually play along with the
musician, following the musician’s tempo and phrasing well.
