---
title: "Reflections on My FOSDEM 2026 Presentation"
date: 2026-02-10
draft: false
tags:
  - FOSDEM
  - Public Speaking
  - Linux Kernel
  - Conferences
---

Hi everybody,

The video of my presentation is now available on its permanent page:

- **Reproducing Linux Kernel Bugs in 5 Minutes with virtme-ng**  
  https://fosdem.org/2026/schedule/event/99ULYW-repro-linux-kernel-bug-5-min-virtme-ng/

I would like to share a more detailed reflection on the presentation itself. I believe we should be our own toughest critics, and I hope the lessons I learned will be useful both for me and for others preparing for future conferences.

There is a saying:

> *“In a stressful situation, you will not rise to the level of your expectations, but fall to the level of your preparation.”*

This is exactly what happened to me.

---

## Preparation vs Improvisation

I prepared the presentation plan and refined it in several iterations. However, I made the assumption that sticking closely to prepared text would feel like *reading from paper* and therefore boring. I decided to rely mostly on improvisation. This turned out to be a mistake.

Under stress, my English — which is far from ideal even in calm situations — degraded significantly. I started speaking more monotonically, with simpler phrasing and noticeable pauses.

The conclusion is clear:

- I need to improve my spoken English so that I can speak confidently for longer periods.

That said, I do not believe that reading a fully prepared text is the right solution either. That approach is indeed boring.

The best solution seems to be a golden mean:

- preparing a strong structure consisting of key sentences that must be delivered on each slide  
- improvising around them while preserving cohesion

---

## Timing and Rehearsal

Another issue I nearly lost control of was timing. Despite providing each slide with a short description during preparation, I almost ran out of time.

From my perspective, it felt like I had just started when I suddenly saw:

- “10 minutes left”
- then a few slides later “5 minutes left”

The conclusion here is that preparation must include:

- at least **two full rehearsal runs with a timer**

---

## Audience Engagement

One of the most important aspects of presenting is establishing contact with the audience.

I followed the basic recommendations from the FOSDEM staff:

- look at people  
- scan the room  
- do not stare at the screen  

However, despite doing this, I did not feel fully *on the spot*, and I felt that the audience was not as engaged as it could have been.

This raised an important question for me:

- How do you engage people beyond simply providing good content?

One effective technique I noticed in great presentations is active communication with the audience. Simple questions like:

- “How many of you use tool A?”
- “How many use tool A together with framework B?”

may seem pointless at first — the presentation does not change based on the answers.

However, I now realize that this kind of warm-up helps people focus and establishes the presenter’s presence in the room.

---

## Technical Setup Matters

Technical setup is another crucial factor.

One thing that distracted me from maintaining eye contact was my slide viewer configuration. I did not switch the PDF viewer into presentation mode, so advancing slides required using specific keys.

As a result, I repeatedly had to look down at the keyboard to find “PgUp” and “PgDown” on my ThinkPad, breaking visual contact with the audience on every slide.

---

## Speaking Style and Cohesion

Speaking style also matters greatly.

A monotonic voice quickly loses attention. Speech should be expressive, supported by gestures and body language.

Cohesion is essential, and forward references should be avoided or clearly announced to prevent confusion.

---

## Handling Questions Gracefully

Handling unexpected situations gracefully is another important skill.

During the Q&A session, I was asked a question I did not initially understand. Instead of immediately asking for clarification, I tried to guess the meaning. This was a mistake.

Simple phrases like:

- “Could you please rephrase?”
- “Let me clarify if I understood correctly”

are essential tools and should always be used.

---

## Learning Public Speaking

All the skills described above fall under what is commonly called *public speaking*.

I am actually glad that I have not formally trained in this before, because making my own mistakes means that future learning will be much easier to internalize.

If you have recommendations for good materials on public speaking, I would be very grateful.

Public speaking techniques should not be rigid rules that limit expression. They should act as amplifiers, helping each person express themselves in the best possible way, adapted to their individual style — including appearance, body language, and personal traits.

---

## A good part
I also want to briefly highlight what went well.  
The live demo worked perfectly and stayed within the time limit — but I had a solid backup plan in place.

I had pre-recorded the bug reproduction and patch application using **asciinema**, and I kept local copies in my presentation folder. If anything had gone wrong during the live demo, I could have immediately switched to another tmux tab and replayed it using `asciinema play`.

As an additional fallback, I also had a Firefox tab open with the recordings uploaded to asciinema and ready to play.

Having two levels of backup removed a lot of stress and helped me feel much more confident during the demo.

---

## Conclusion

To conclude, none of the above matters without the main goal:

- sharing technical knowledge in a way that people genuinely appreciate

I would greatly appreciate your feedback. If you have one, please share it on LinkedIn as I have no comments in this blog:

https://www.linkedin.com/posts/roman-st_fosdem-2026-reproducing-a-syzbot-bug-in-activity-7427057682928418816-WuAe


Thank you.
