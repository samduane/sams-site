+++
title = "Javascript: Bash for the Web"
author = ["Sam Duane"]
summary = """
  The world runs on the internet. From phones to servers, fridges to thermometers. The internet has invaded every
  part of our lives. The backbone of the world wide web that keeps everything running is... Javascript. One of - if not
  **the** - worst languages to be used in production systems. Why?
  """
lastmod = 2023-01-06T01:28:28-05:00
tags = ["programming", "web-dev"]
draft = true
+++

&emsp; I could start by trashing on JS. I could go on about all of its obvious mistakes, inexplicable oddities, and
outright asinine design decisions. I won't. There are as many blogs that cover all of that as there are frameworks that
attempt to fix those problems. Instead, I want to explain why I think things came to be this way, and how we should view
JS going forward.

&emsp; I'm no historian. I started coding about 5 years ago. To say I have some unique first hand experience with the growth of
the web would be a lie. That said, there are some basic facts we can use to piece together the digital crime scene we are
currently observing. Time to put on our fedoras, detective!


## In the beginning... {#in-the-beginning-dot-dot-dot}

&emsp; It's always best to start at the genesis of the event. When we look at what the web was back in the "good ol' days", it
was _quite different_. With no standards and a mess of technologies, the web was... _special_. I say this both in the
literal and sarcastic sense. It really was an amazing new technology. Yet, it was also a dumpster fire. Different
browsers had different standards. HTML was in its infancy. Java tried to enter with applets. PHP was actually **good** compared
to many of the alternatives. While this sounds terrible(and was), it wasn't nearly as bad as the situation we have
today. This is because of one major difference: in the beginning, web sites were just that - websites. Not apps with
thousands, even millions of users.

&emsp; Back in the day, a website was a document. You could put up stylized text on a screen. Wow! That was it. No fancy
buttons or animations. No full-stack systems to create your game-changing startup app that will _revolutionize_ the
industry. Just some pages. It was more like a PDF than a desktop app. And that was good! The web had a specific purpose,
and had HTML and CSS to do the job. Yay!


### More!!! {#more}

&emsp; As the web got more popular, it grew. As it grew, people did more with their sites. People began to hunger for more!
While HTML and CSS developers strived to please these bearded fanatics, they were limited in their functionality. This is where scripting languages
joined the conversation. With the ability to create personal functions that could extend their sites, these simple
languages were like drops of dew from heaven itself. People could do amazing things! Adding buttons and dynamic menus
with fun animations. It was fun! This is the birth of Javascript.

&emsp; As the story goes, JS was born in 10 days at a coding competition. A fun challenge to implement an easy to use scripting
language. While it was originally planned to be Scheme in the browser, a few requests and design decisions would result
in the seedling that would grow into the language that we know and ~~love~~ hate today!


## Identity crisis {#identity-crisis}

&emsp; It wasn't designed to create reusable code across platforms like Java. It wasn't designed to support thousands of
asynchronous calls that needed to be up 24/7 like Erlang. It wasn't designed to be the de-facto tool used by the most
successful operating system like C. It was a scripting language, designed for fun. It let people do quirky things with
their personal sites. For personal sites, it was good!


### For ~~better and~~ worse {#for-worse}

&emsp; However, things continued to change. The web continued to grow. Netscape died, and Internet Explorer reigned supreme.
Later, Chrome would rise from the ashes and conquer the demonic forces at Microsoft, to usher us in a new age of virtual
glory! Remember when Google _wasn't_ evil? Good times.

&emsp; Anyways, the web became more significant in the average Joe's life. It became an essential part of the everyday.
Companies started to realize that they could take advantage. Advertising, cookies, and more! Oh my! The internet
was no longer the home for personal blogs with stroke inducing rainbow animations. Now it was time for the
corporate world to take charge!

&emsp; With companies putting more effort into their digital presence, the purpose of websites changed. They were less
home pages and more web apps. More needed to be done, and Javascript was the quickest option to get up and running.
Things continued to grow, and now JS had to grow with it. Javascript was now married to the browser.

&emsp; Now in the current day, JS has grown from a goofy little scripting language into an absolute abomination of a
production system. Framework after framework promises to resolve the issues baked into the core of JS, all failing to
truly eradicate the inadequacies.


## Building on Bash {#building-on-bash}

&emsp; While it's easy to simply dismiss Javascript as a "bad language", I think the true issue is the view of the
developer. Having reflected on the origins of JS, it's clear that it was _never_ intended to be used for app
development. It was _never_ designed for large scale use. Like Bash, it was designed as a simple language for quick
scripts on a personal system. Both have their quirks. Both are good enough for what they were designed to do.

&emsp; However, there's a difference. Unlike Bash, which had C to rely on for serious development in the UNIX
world, JS has nobody. The browser landscape has no C. Rust is starting to enter the picture. WASM looks to
provide better support from more refined languages. Still, there is no definitive programming language for the internet.

&emsp; The post-apocalyptic wasteland of JS now makes sense. The problem is not that JS is used for the web. No, the
problem is that it's the **only** language for the web. We have built an ecosystem of apps on the web equivalent of Bash. Imagine
if our operating systems were designed without C? Everything built purely in shell scripts. That's what we've done with the
internet. Frankly, I'm impressed things aren't **worse**!


## Moving forward {#moving-forward}

&emsp; With a better understanding of the current predicament, it's clear that change is needed. WASM is a great step in
the right direction. Being able to develop professional applications with proven languages on the web is exciting to see
and brings hope for the future of the internet. Hopefully, we can see browsers better integrate with other languages,
and have a C for the web. Maybe that will be Rust, or Go, or Elixir. All purpose built for the demands of the web. Who knows!
Regardless, it seems best to begin transitioning to these systems for more intensive progams.

&emsp; As for Javascript, it will continue to be used. Hopefully, with time its prominence will begin to fade, and it
will be restored to its rightful place - quick and easy scripts for personal sites. Frameworks and hackjobs will be
used less and less. It will be championed by a new generation of bearded fanatics, a gateway drug into the world wide web.
