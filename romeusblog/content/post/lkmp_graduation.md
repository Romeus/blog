+++
title = 'Linux Kernel Mentorship program graduation'
date = 2024-08-07T19:36:48+02:00
tags = ["learnings", "certifications"]
+++

It was a long journey. I heard about Linux Kernel Mentorship Program in the mid of the January, went through the application process and was selected as a mentee. Despite I wasn't a newbie kernel developer, I learnt a lot during my mentorship period. And now, this journey is over and I am graduated.  
I want to thank my wonderful and patient Linux Foundation mentors and experienced kernel developers and maintainers - 
[Shuah Khan](https://www.linkedin.com/in/shuah-khan/), [Javier Carrasco Cruz](https://www.linkedin.com/in/javiercarrascocruz/) and [Julia Lawall](https://www.linkedin.com/in/julia-lawall-5781356/) from the bottom of my heart for their support, wise and passion.

[![Graduation letter](/lkmp/Linux_kernel_bug_fix_spring24.jpg)](/lkmp/Linux_kernel_bug_fix_spring24.pdf)

Below, I would like to share a few useful pieces of advice for the upcoming mentees of the program and newbie kernel developers:  

- Choose 1, maximum 2 subsystems to work on. Linux Kernel is complex, and it is
  is impossible to dive deep to many subsystems simultaneously

- Always prefer subsystem you know well if possible. Ramping up on a particular
  subsystem is time-consuming and it is better to avoid this during mentorship
  period

- Never avoid "non-essential" job like updating documentation, tests, user-space
  tools. There are several reasons:
  1) It is not non-essential job. Typically it is easier to do such task than
  updating drivers or core code, but it is part of the kernel, and the quality
  is always matter. Besides, it is a good to warm up with such tasks
  2) Open bugs are always present. On the other hands there are always several
  experience developers fixing those bugs with the speed of light. A new developer
  cannot expect outperform these. Highly likely the bugs will be fixed in hours.
  So, probably newbie will have no choice, but start with fixing low-priority bugs

- Don't start fixing hardware-related bug if you don't have access to this hardware.
  It is hard to impossible to check if a bug was really fixed.

- Always test carefully. Never put equal sign between code has been compiled and
  a bug has been fixed. The bare minimum of the testing procedure - building and
  running. The better option is make the branch take your codepath(s)

- Work at several patches at once. Do not wait for feedback immediately. Maintainers
  are busy enough to response the same day. Typically waiting period could be 1-2 weeks.
  So, after sending a patch, immediately switch to another one.

- Use advanced tools. A good example is b4 - tool that allows you to work on a patch,
  support automatic versioning, and track it status on lore.kernel.org

- Key principle - bring value to the community and Linux kernel, not only to yourself.
  For example, if you decide to create patches that rename variables, or simply add/remove
  indentation then highly likely they will be rejected as creating noise without any value.
  A patch shall improve existing code, fix bug, or add a new feature.

- Handle feedback properly. Never suppose that maintainers reject your patches because
  of their bad mood or by similar reasons. They are experienced developers and if they
  reject some patches then they have reasons. Typically they explain those reasons.

P.S: You could find me in the Graduted mentees subsection at the bottom of the page here:  
[Graduated mentees](https://mentorship.lfx.linuxfoundation.org/project/df065cf2-c9d2-453f-8624-7d84654d6352)
