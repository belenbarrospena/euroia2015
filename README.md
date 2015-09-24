# euroia2015

This is roughly what I said during the presentation: 

Good afternoon everybody. My name is Belén, I am the designer for something called the Yocto Project, which is a Linux Foundation initiative. 

Like all Linux Foundation initiatives, the Yocto Project is FOSS. What is this FOSS thing? Well, FOSS is an acronym. The acronym stands for Free and Open Source Software. 

I need to use this acronym because, in theory, free software and open source software are different things. Although, to be honest, for the purposes of this talk we are much more interested in what they have in common than in how they are different. And they have a lot in common. 

This is the definition of open source software: "software whose source code is available for modification or enhancement by anyone". 

And this is the definition of free software: software for which any user can study the source code, modify it and share it. 

As you can see, the story is quite similar: in both cases we are referring to software whose source code, which is the human-readable version of the computer code, is out there, available for anybody too look at. And not just to look at: but to change and to improve as they see fit and, within the conditions established by the software license, redistribute too. 

FOSS has another fundamental characteristic: it is peer reviewed. 

You see: free and open source software is not written by a tight, well-coordinated, smallish team of engineers from a certain company. It is written by a community of software developers who contribute small snippets of code called "patches". Why "patches" are called "patches" is an interesting story, but we don't really have time today to go into details. 

This is a patch: one of those snippets of code that together make a free or open source software application. Patches are published to a public forum, often a mailing list or a code review tool. Anybody subscribed to that public forum can check the patches out, they can ask questions, make comments and suggest improvements. So your peers review the computer code you write.  

Patches, once reviewed, are accepted and incorporated to the main body of code that constitutes the application: this is what's called "merging upstream". So when you contribute to free or open source software projects, you don't only commit to publish the code you write: you also commit to listen to the opinions and suggestions of others, take them into consideration, follow the recommendations from your peers and amend your code accordingly. 

And this is absolutely fundamental to the nature of free an open source software: it is at the core not only of its development process, but also of its philosophy and values. The humility, the humbleness, and the willingness to listen and learn from others. 

And now that I have told you what FOSS is, let me ask you a question. Who here uses FOSS? Please stand up so that we can see you. What you see here is a perfect representation of the perception that we designers have of FOSS: that it is a minority of the software in existence, used by a minority of people. 

And now let me ask you another question: who here uses the Internet? Please stand up so that we can see you... and don't lie to me because I know you were all on Twitter just a minute ago. 

And what you see here is a perfect representation of the reality of FOSS. Anybody who uses the Internet uses FOSS. And I am not talking about the standard protocols like TCP/IP or web technologies like HTML, CSS or JavaScript. No, no. The web browsers you use, are based on rendering engines that are FOSS. The websites you visit, are served by web servers running FOSS, located in data centers managed with FOSS, to which you connect via routers whose operating system is based on FOSS. What's more: every time you cross the street at the traffic lights, every time you use an elevator, every time you print a document, every time you pay in a parking lot, you are using FOSS, because a significant percentage of embedded computing is based on the Linux kernel which is of course ... FOSS. 

And this is one of the big FOSS problems: any similarities between the perception we have of it, and the reality of it, are pure coincidence. FOSS is surrounded by myths. And if you allow me, I will try to debunk some of them here today. Not all of them: just 5 of them, because that's all we have time for. 

Myth number one: FOSS does not use graphical user interfaces. There is this idea going around that all FOSS is software that never interacts directly with users: libraries, compilers, things like the kernel, stuff that constitutes the infrastructure of technology, the pipes, nuts and bolts of the computing world; stuff with which developers interact via command line interfaces. Maybe this was true at some point, but it is most definitely not true any more. Young developers (and the not so young ones) are used to graphical interfaces, and they expect and demand the same kind of interaction from their development tools. 

Pretty much anything you can think of, even the most technical things that we designers are blissfully unaware of, tend to present some kind of graphical interface. For example build systems, which are these fiendishly complicated tools that automate the compilation process and build our operating systems from source, have graphical interfaces. I know because my job is designing one. 

Not only that: the times of FOSS taking care of just the infrastructure of computing are coming to an end, and here is my favourite example of that. This is the list of the eight mobile operating systems currently in the market. Of those eight, five claim to be FOSS in one way or another. Between them, the OS that owes 80% of the market (Android), and the newest four: FirefoxOS, Sailfish, Tizen and Ubuntu Touch. Of course, all of them include a graphical user interface, and all of them interact directly with users. 

So the idea that FOSS does no use graphical user interfaces in simply not true: graphical interfaces are a fundamental component of, and play a very important role in, all software, including FOSS. 

Myth number two: all FOSS is ugly and unusable. As anthropologists would explain to you, myths often have some kind of connexion with reality. And that is the case with this second myth. There is a lot of ugliness in FOSS. More than ugliness, I like calling it "brutalism". "Brutalism" is a very common architectural style in the United Kingdom. Here in Madrid, not so much, but in the UK: brutalism everywhere. 

This is Preston's bus station: one of the most famous examples of brutalism. To me, FOSS UIs are to software what brutalism is to architecture. Because although you might or might not like the outside of the building, the reality is that the building is solid, practical and has good foundations. And this happens to FOSS as well: the UI might be ugly as hell, but the software behind it is solid, it's well designed from a technical perspective, and on top of that it tends to solve a very real problem and tends to be incredibly useful. Let me show you some examples of brutalism in FOSS. 

Bugzilla, a bug tracking system. Ugly as hell. Brought to you by Mozilla, yes the same Mozilla that makes the Firefox web browser, the same Mozilla we all love because they are all open and cuddly. 

Gerrit, a web interface for code review, sponsored by Google. Yes, the very same Google that makes your beautiful Android phone. 

And my favourite one lately: menuconfig, the tool to configure the Linux kernel. Kernel developers are saints. 

But inferring from these examples that ALL FOSS is ugly is quite an exaggeration. 

Firefox, the web browser made by Mozilla, not only is not ugly: it has pioneered many of the design patterns that we have come to expect from any web browser. 

Sparkleshare, an alternative to Dropbox. 

MailPile, a secure email client that incorporates easy to use encryption. 

OwnCloud, another alternative to Dropbox. This one web based, and that includes some very nifty features.

So, although there is brutalism in FOSS, it is most definitely not true that all FOSS is ugly or unusable. And to be fair, there is a healthy amount of brutalism in commercial software too. 

Myth number three: FOSS developers hate designers. If we agreed before that myths have some connection to reality, then this is not a myth: this is a lie. Developers involved in FOSS do NOT hate designers, and I want to make this very clear. And it is not just me saying this: academic research says this too. These good people from Oulu university ran an experiment with their students. They set them as their class work to run a usability study for an open source project of their choice. The experiment concluded the following: the community welcomed the designers as they welcome any other contributors, with open arms. And in fact, developers said that it would be great to get this type of contribution on a continuous basis: they wanted the usability people to become permanent contributors. 

In fact, you might find that FOSS developers can have a surprisingly sophisticated understanding of what design is about. This is a slide created by one of the core developers of the Yocto Project for a presentation he gave at a recent conference. Look at the second bullet point: design is not only applicable to software with GUIs. This shows a very nuanced perception of what design is actually about. And after making this statement, the developer proceed to explain to the audience how design research activities informed his decision making for a new command line tool he was working on. I am so proud of him! 

So, believe me: FOSS developers really don't hate designers. They have much more important things to do and worry about.

Myth number four: FOSS is all technical stuff, and I don't understand those things. Well, yes, nothing we can do about  it: a lot of FOSS projects are very technical in nature. But it kind of makes sense: a lot of FOSS initiatives are about improving software development tools and processes. I deal with things like this every day. And maybe you cannot see it very well on this image but, believe, it doesn't matter: it's incomprehensible gibberish. 

But not ALL FOSS projects are technical in nature or are tools for developers. Some of them are games; others are graphical interfaces for operating systems, like this one here: the Gnome shell for Linux; others are suites of office applications: word processing, spreadsheets, presentation tools, very important for those who cannot afford to pay the software licenses of commercial solutions; or CMSs, to democratise web content production and publishing, like Wordpress. Some of them are alternative mobile application markets, like F-Droid for Android, that only lists applications that are FOSS; or services that preserve the privacy and anonymity of your mobile communications, like the ones listed here, developed by the Guardian Project. Between the thousands and thousands of FOSS projects out there, there is something for everybody. 

And myth number five, which I've left for the very end because it is my favourite one: there are no designers in FOSS. 

To debunk this one, I myself ran a little experiment. In September last year, I submitted a proposal to FOSDEM, a very big conference that happens in Brussels every year during the fist weekend of February, which brings together loads of people contributing to FOSS projects. The proposal, which they accepted, suggested having a full day of talks about user-centered design in Free and Open Source Projects. With the help of other designers who are also involved in FOSS, we opened a call for sessions, we chose the best ones, we published them in the FOSDEM website, and we went off to Brussels. It was the very first time that FOSDEM would include a design track, so we had no idea what was going to happen, how it would be received.

Well, let me tell you what happened. The first early morning sessions saw healthy attendance. But as the day progressed, we got full to the brim. When all chairs were occupied, people just lined along the walls and sat down on the stairs. In the end, we had to stop people from coming into the room and stuck the 'full' notice to the door. 

I think none of us was expecting this. There are designers in FOSS! Of course, there are. What happens is that we don't normally hang out in the same places: they have their own publications and conferences, and the do not usually attend ours. 

But although there are designers in FOSS, it is true that there are simply not enough of them. One of the things that happened to me while I was at FOSDEM was that tons of people came to me to tell me: Belén, I am a developer, I contribute to this FOSS project that does xyz, and it does it really well. But the interface really sucks, so we need some people who know what they are doing to help us design it properly. The problem is, I can't find anybody. Where are the designers willing to contribute to FOSS? Where do you get together? Is there anywhere I can post an announcement, a request for help, a job offer ...

Back in February, when they asked me this, I had nowhere to send them. Luckily, things have changed since. A group of designers and developers have decided to do something about it, and now we have: a repository in GitHub, a website (a very humble one so far, but better than nothing) with a "jobs" section where people can post requests for help. We also have a Twitter account, an IRC channel and, most importantly, tons of energy and a firm determination to fill the gap designers have been leaving in the world of Free and Open Source Software.

If this resonates with you somehow, and you would like to join us in helping the Free and Open Source Community to solve some of the trickiest problems that exist in software today, like making encryption comprehensible and accessible to everybody; or keeping the content of our digital activity and communications private; or creating usable and attractive alternatives to commercial services... now you know where to find us. 

Thanks for listening.  
