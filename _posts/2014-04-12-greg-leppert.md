---
layout: interview
slug: greg.leppert
title: Greg Leppert - Reading.am
summary: Founder of Reading.am. Co-founder of Svpply. Reads a lot.
categories: [reading, community]
---

#### Who are you and what do you do?

My name is [Greg Leppert](http://twitter.com/leppert) and I build [Reading.am](http://reading.am), along with a handful of other projects.

#### Can you describe Reading really quick?

Reading is push-button link sharing. When you sign up, Reading hands you two standard issue items - a bookmarklet for posting the current page youre visiting and a social feed for following what your friends are posting. The goal is to make it as easy as possible for you to get a feel for, and feed into, the zeitgeist of your community. Can I use the term zeitgeist with a straight face? Probably not. Assume that I winced there when I typed it.

A better phrasing might be that Reading lets you show other people what youre thinking about without forcing you to have an opinion about it beforehand. I find freeform text boxes somewhat intimidating in that regard.

#### You've said before that Reading encourages you to post before you start reading a page. How do you think Reading's design encourages that behavior?

Most of what makes Reading compelling shows itself after youve posted a page to your profile. Clicking the Reading bookmarklet not only serves to post the page, it also shows you who else has already read that page (or is reading it currently) and any of the comments that have been left there for you to find.

But I think theres an implicit question therewhy encourage posting before youve even read the thing? Because, at least my hope is, itll prevent posting a link from becoming an endorsement for the content at the other end of that link. Theres a natural tendency to curate what we associate with our online profiles and I think thats, in large part, because weve spent a lot of time equating a users profile page with a users identity and, consequently, their beliefs. But I consume a wealth of content that I dont necessarily agree with, and that helps to inform me, to shape my opinions, as much as the content that I agree with wholeheartedly.

Its not all about ideologies and beliefs, though. Much of it is about posting the innocuous things that facilitate work and friendship. If I see you post a series of Stack Overflow links to your Reading profile, orbiting around a specific topic, I have a new understanding of the problem youve been trying to solve that day and I might even step in and offer to help. Where else on the web could an exchange like that happen so casually?

#### Reading's development was really closely tied to how you personally used it in HipChat early on, so the realtime flow of links was really important. Is that still the case for you?

The HipChat integration was focused on helping a small team of people have that casual exchange of knowledge and, hopefully, bring them closer together in the process. The way I consume Reading really changes from day to day. When I find myself with a checklist of disparate tasks that need to be completed that day, Ill keep my Reading feed open, along with the Reading Twitter account, and dip in and of the stream. Its a nice way to break up my day and stay involved with the community. But when I have a single, engrossing job to do - when Im researching a new idea or banging on a development problem - Ill typically peck at the Reading Digest (a daily email with links you might find interesting) during my morning coffee and scroll through my feed at the end of the day.

#### What do you think is gained by getting a link to a page when someone is still on it?

I think presence is powerful. Content that is largely static, that was previously constructed, suddenly becomes living, even though its not the author who is breathing life into it. In that regard, the web is much like architectureits pages are simply buildings that ask us to inhabit them. But much of the web wasnt constructed with that in mind, so weve been building tools to layer it on top.

Thats all a fancy way of saying its nice not to be alone when youre experiencing new things, however mundane they might be.

#### What's the coolest use of Reading you've seen from someone? Have you seen any surprising workflows?

Im tickled every time I see a new "isreading" Twitter account pop up, the first of which was [Max Fenton](http://twitter.com/maxfenton)'s [@maxisreading](http://twitter.com/maxisreading). "isreading" accounts are Twitter accounts that mirror a users Reading posts to a dedicated Twitter handle (@caseyisreading, @joelisreading, etc). Its something Max invented and which caught on organically with other users.

The thought of someone generating, and spreading, new ideas that use one of my creations as their foundation just blows my mindits the ultimate compliment. I call these sorts of things cultural artifacts. Theyre a sign that youve developed something compelling enough, and flexible enough, for a unique culture to develop and for that culture to produce new things. If a digital archeologist were to dig up the remains of Reading a millennium from now, I hope theyd find hundreds of cultural artifacts developed by our community.

#### Do you find yourself clicking the extension to see who's on the page? Sometimes I try to see if I can predict when friends will be there when I do mark it.

All the time! I love seeing the people I dont know as much as the people I do. Sometimes its easy to trace how we all arrived there (via MetaFilter, for instance) but other times it feels like serendipity. When I see someone Ive never met on a page Im reading, I find myself thinking about the trillions of pages on the web and how we both ended up at the same place at the same time for no other reason than we find the same things compelling. Thats the foundation for a friendship, if Ive ever seen one, and a perfect reason to say hello.

#### Was that type of interaction something you tried to take into account when you were expanding reading from a HipChat plugin for your office to something for a wider audience? Like, people starting to get a sense of one another from these reading lists. Piecing together an image of someone from all these tiny pieces of ambient information?

Thats exactly it, and ambient information is a wonderful term for the output. Expanding Reading to a user base beyond our HipChat room was a deliberately slow process. I knew how the Reading bookmarklet had changed our dialog at the office and I wanted to use that as a waypoint for opening it up to others, scaling an existing positive experience rather than trying to reimagine it for a broad audience. Reading has always been a labor of love for me, and most of the development has happened in fits and starts on nights and weekends, so theres been plenty of time to interact with the community and get a feel for what to work on next. If you peeled back Readings git log and plotted the various commits, youd have a deeply personal picture of my spare time. And because of that, I havent felt pressured to make everything obvious or map interactions to established conventions. Whats yep and nope? I think I have a better idea now that the community has taken hold of it, but when I released it I did so out of curiosity.

#### Reading has some pretty interesting social and privacy features in that everyone who has read a page, and all of the comments they make, are visible to the entire community. Annoyances seem practically nonexistent though, since users only get notifications when they are mentioned specifically. People seem to mention one or two friends and have their own separate threads in the open.

#### I was wondering if you had any theories you were trying to test out for finding a balance between intimate and global sharing, and what you think separates a Reading comments section from the default comments section taking place on the same page.

This really stemmed from Reading being a somewhat small community and the web being a rather large place. Theres a line of code thats been commented out in the Reading codebase with a note that says uncomment when needed. That line would filter the list of readers and comments, limiting them to the people you follow. My hope, and why it was unfiltered by default, is that Reading will gather people around distinct ideas and interests rather than broad topics.

Ive often wondered if the breadth of the premise that brings people together correlates to the potential for conflict and noise. With Reading, youre seeing specific people and specific comments because youre all reading a specific piece of content. The next page you post to Reading might have an entirely new set of folks. Contrast this with a community where youre bound together by topics as broad as videos or sports where users will have a much greater challenge finding common ground.

#### I should probably at least nod towards the origin of this site. Do you have a collection of domains? What's the best thing you've ever registered.

I do have a collection. My goal with Reading has always been to expand the scope, to encourage the sharing of all media, and for the most part the community has already gravitated in that direction. Im the proud owner of listening.am and watching.am, along with a few others, but my favorite at the moment is probably elephantsho.es. Id actually forgotten about that one until it renewed a few weeks back. Theres something about buying a domain name that commits you to an idea in a cursory sense, almost like planting a flag. I suppose elephantsho.es idea would be to make the world a more friendly place, one domain name at a time.