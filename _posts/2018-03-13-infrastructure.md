---
layout: post
title: Bug Reporting
---

# Litreview - Software Infrastructure

I've recently read the first few pages of a book written by Nadia Eghbal. "Roads and Bridges: The Unseen Labor Behind our Digital Infrastructure" 
(https://github.com/ritjoe/hfoss/blob/master/assets/roads-and-bridges-the-unseen-labor-behind-our-digital-infrastructure.pdf) goes over the hidden
challenges to maintaining an open source software project. Eghbal discuses the cost probelm that many open source projects face, with primary 
contributors unable to support themselves with their work. The actual phyiscal cost that comes with running servers and storing data are also 
discussed. Users of free software can increase the need for physical resources, without providing any form of revenue for the maintaining organization.
There has been an increase in awareness for donations to open source  projects, as well as corporations begininning to get involved. While this is
helpful, there is still a lot to go. Concerns about the implications of private interests in free projects also exist. This also holds true in the
case of Government involvement. There is public Government funding for physical infrastructure and it seems obvious that software would receive 
similar attention. There are risks, however, with introducing Government interest in free projects. The request for back doors is just one of these.
There are a number of questions and concerns about how to increase support for open source projects, which so desperately need it, and Eghbal does
a great job of discussing these. 

After reading this book, users will have a new found appreciation for the maintainers of their favorite open source project. They'll understand
the costs that exsit, as well as the contribution they make to that price. Hopefully readers will have a desire to to improve their habits when
interacting with the free software community. 

There were a few particular things I enjoyed reading about in this book. The first of these being the discussion on security implications for
open source software. When I was still young and naive andfirst becomming a programmer, I incorrectly believed that open source software would
be naturally less secure than proprietary software. I felt that a price tag meant "better" and if something was free, it's because it wasn't good
enough to be sold. As I've grown and developed as a developer I no longer feel this way and have actually completley flipped on this regard. I 
now feel that open source software is naturally more secure than code that is hidden. The code reviews and availability to public scrutiny lead
to a much more inspected code base. Eghbal briefly discuses this in the book, but a great example is also the Linux file system bug that was 
introduced into an NPM package (https://github.com/npm/npm/issues/19883). This was a severe bug that was able to slip through the testing phase
but was quickly caught by a user and submitted as a well detailed bug to the project team for consideration on how to fix.

While on the topic of security, something I didn't like in this book is the discussion on backdoors being implemented into software. This isn't
an issue with Eghbal's writing, just my feelings on the content discussed within the book. Eghbal makes a point to talk about the potential
for private and government entities to request "backdoor" access into software that would invade the privacy rights of the softwares users. I 
am against such requests by any organization, and was glad to see that Eghbal brought this point up within the book. 

I also enjoyed the discussion about users that don't contribute to any projects they use, but are a drain on those projects resources. I've never
been much of a contributing develoepr myself and Eghbal does a great job of making me refelct on my daily habits as a programmer, as well as ways
that I can improve them. Things as small as submitting bug reports for the devlopment team are a great place to start. Although contributing code
to projects used more frequently would be even better. 

Eghbal also has a brief discussion about the implications of introducing money into free software. This can lead to outside interests influincing 
what should be a neutral project. While a reason for concern, this fear shouldn't stop the progress being made to fund open source projects. There
has been an increase in foundations that exist to support popular projects as well as private companies contributing and funding software that
they use. I'm of the belief that money always brings corruption, and would advocate for transparency in any support to the open source community. 
The inherin neutrality of open source is one of its greatest assets and it would do well to protect that. 

This brings me to a question that I had while reading this book. Eghbal discussing a man named Jeff Atwood giving a $5,000 to an open source
project called ScrewTurn. Atwood had inquired about the teams use of the money he gave them, and was sad to learn that they had not yet made
a decission on how to spend it. Eghbal never tells us what they decided on, if such a choice was ever made. I would have liked to hear the 
outcome of that. It was interesting to learn that the decenteralized nature of open source projects made things like budget decisions hard to
reach. After reading this section, however, it seems a no-brainer. 

Roads and Bridges: The Unseen Labor Behind our Digital Infrastructure" by Nadia Eghbal provides a great read. I personally know that I gained
a lot of insight into the behavior I have as a programmer. I've had an increased awareness to the costs I induce on the software community, and
have learned ways to alleviate that cost. I have a better understanding as to what goes into supporting software, and the steps being taken by
different entities to keeping popular projects up and running. While a bit of a long read, this is definitely on of value for developers new or old. 



