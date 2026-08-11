---
title: "No Vibes, Just Struggle: Notes From a Research Software Engineer"
date: 2026-05-14T17:11:53.478Z
draft: false

event_name: "Convivial Code: The Politics and Pedagogies of Vibe Coding"
event_url: ""

location: "University of Warwick, Coventry (UK)"
address:
  street: ""
  city: ""
  region: ""
  postcode: ""
  country: ""

summary: ""
abstract: |
  

event_start: 2026-05-14T10:00:00.478Z
event_end: 2026-05-14T17:30:30.478Z
event_all_day: false

# Speakers are matched to profiles in content/authors/
authors:
  - me

tags:
  - Research Talks
  - Community

featured: false

image:
  caption: "Event's logo. Credit: Michael Dieter"
  focal_point: Center

links:
  - icon: brands/github
    name: Demo or code
    url: ""
  - icon: brands/youtube
    name: Recording
    url: ""
  - icon: book-open
    name: Documentation
    url: ""

# Link to your Markdown slides (folder name in content/slides/)
slides: ""

# Associate related projects
projects: []
---

<!-- Add the talk outline, prerequisites, and how people can join. -->

I'm going to share a couple of struggles that I'm experiencing in my everyday work as a Senior Research Software Engineer at the Centre for Interdisciplinary Methodologies. But before doing so, I need to disclose my positionality in relation to AI and vive coding, particularly about its meaning and how I use it.

Coding is a very polisemic word, and people may assign different meanings depending on their background or context. As a Research Software Engineer, when I think about _coding_ I am mainly referring to the action of creating scripts or software that can be used in an academic setting. This setting is very important to me because it comes with a series of values and requirements that are different from other settings (e.g. hobbysts or industry), such as reproducibility, provenance, or correctly citing sources as an integral part of academic integrity.

I have never vive coded. I've seldom used vector-mediated coding: when I use it, I do it reluctantly or triggered by curiosity. Either case, I always feel it as a defeat. This is not because I'm so proud that I feel my ego threatened, or because I'm a good or fast coder that doesn't need such aids. I'm actually neither. Probably because of that, through commons-based peer production, I've learnt a series of techniques, good practices and cultural norms that helped me to overcome my individual limitations. Two paradigmatic examples are to use and adapt code and frameworks that other, smarter people, have created and decided to share it with others through open licenses; and to rely on processes and automations[^automations] to reduce errors, to understand when something doesn't work and to seek help when I can't find the answer, and to do so, to be able to explain to others what I want to do and what I've done.

Now, that my stance is clear, I'm in a better condition to share my struggles with AI in general and AI-assisted coding.

The first has to do with the fact that technology is never neutral, and AI has been built through extractive and exploitive practices that are assumed, validated and reproduced when using them. Examples of this can be seen in how LLMs have been trained by systematically stealing IP, or by employing humans to manually tag content in terrible working conditions and at the expense of their mental health.

And not to mention the large amount of resources this technology and the required infrastructure (i.e., datacentres) require for functioning, such as energy, water, oil but also hardware such as RAM or SSDs and Hard drives. Even though the tech and the companies behind ofuscate date to make it really difficult to quantify the environmental costs (and therefore, making it easier to be disregarded), we are already seeing their effects. This week alone news echoed how Maryland taxpayers would need to pay $2 billion dollars to upgrade the power grid to host data centers, or that important SSD and HDD manufacturers have sold all their production until 2029 exclusively to serve Data center needs, creating new forms of scarcity. 

But probably, the clearer example about the worldviews and political agenda that are encapsulated in this technology is how AI companies are directly or indirectly promoting surveillance, and even genocides, and how their CEOs feel empowered enough to publish supremacist manifestos in the name of their companies [^palantir-manifesto].

The combination of these factors makes me feel that **every time I use AI-tools I'm forced to disregard my values and the political and moral beliefs that I stand for, and makes me feel closer to a world and a society I wouldn't wannt anyone to live in. And this is not an easy pill to swallow**.

The second one has to do with AI assisted coding, or vector coding. It is easy to be flashed by the ability to produce something that works in a reduced amount of time and with few or little knowledge on coding. It is really impressing to see that what would take a lot of time is accomplished (at least in appearance) in a matter of minutes, and with little effort. I can see how many people (particularly those who do not know how to code or are in early stages) may see it as a way to overcome their limitations and how this seems like it's democratising coding. I really do, I would believe it myself it wasn't because it is the opposite. 

**Vive coding produces code, but it does not make _programmers_, it makes _prompters_.** This is not just a semantic difference. I contend that the former is empowering, whereas the latter is disempowering. Vive coding epitomises neoliberal worldviews by stating that only the outputs matter[^karpathy], disregarding decades of disciplinary and interdisciplinary knowledge built over decades. **Coding is not about just producing code, it is also a cultural and social practice, a method.** Equally as important than the output are issues related to:

- Correctly attributing everybody's work, and complying with licences. Using AI can easily lead to copyright infringements and flags questions about Intellecutal Property and accountability: Who is the author of the code? Can we make sure that we are complying with the licence terms of the code that the AI is reproducing?Can we be sure that we are not leaking any personal or sensitive  information (either in the code or the prompts)?.
- Writing understandable and explainable code, not just to make it easier for us to maintain and improve it over time and for others to contribute to or scrutinise (again, this is important in an academic setting). If we cannot explain what the code does, how can our research rely on it? Can we use it in research if we cannot write a basic methods section? 
- Considering and addressing failure. Any relatively complex piece of code will, inevitabily, fail. Far from approaching failuire from a nihilistic standpoint, software engineer need to actively address them by putting measures to minimise the errors (e.g. automated testing), or to be able to debug them when they ocurr so they are easily fixable. Or, as Cory Doctorov [wrote](https://pluralistic.net/2026/01/06/1000x-liability/#graceful-failure-modes): "Writing code" is about making code that *runs well*. "Software engineering" is about making code that *fails well*". How are we going to maintain the software in the medium and long term?  What will we do when it fails? (because inevitabily, all code fails) Shall we start over again? Is then efficient?
- Saving resources, both material and  human. Is it fair to ask others to read, understand, test, and improve code that can be generated at faster pace than any human can review? Many projects[^slop-free], such as drupal[^drupal] or some GNU/Linux distributions, are not accepting contributions if the authors cannot explain them, as it suposes a liability but also a waste of resources and time from a team that has already a lot on their plate.


But probably the most important flaw in this framing is how it shifts the paradigm away from _processes_. Because programing is a never-ending task, it requires constant iteration, improvement, learning... it is, above all, a process. And so it is the learning process that makes you be a (good) programmer.  Admittedly, coding is challenging, it requires a series of skills that take time to learn, and even more to master. But once learnt, they are ours, nobody can take that from us. This is what is really empowering. On the other hand, being a promter means relying on something external (AI) to generate code.  What will a _prompter_ do if they lose access to those tools? Considering the track history of enshitification and lack of human consideration of these companies, this is not a hypothetical question. 


[^automations]: Code linters, Continuous Integration, Automated testing... are examples of such automations that are not AI-powered and have been commonplace in software development.
[^karpathy]: Open-AI cofounder Andrej Karpathy coined the concept of vive coding as this ([source](https://x.com/karpathy/status/1886192184808149383)):
    > There's a new kind of coding I call "vibe coding", where you fully give in to the vibes, embrace exponentials, and forget that the code even exists. It's possible because the LLMs (e.g. Cursor Composer w Sonnet) are getting too good. Also I just talk to Composer with SuperWhisper so I barely even touch the keyboard. I ask for the dumbest things like "decrease the padding on the sidebar by half" because I'm too lazy to find it. I "Accept All" always, I don't read the diffs anymore. When I get error messages I just copy paste them in with no comment, usually that fixes it. The code grows beyond my usual comprehension, I'd have to really read through it for a while. Sometimes the LLMs can't fix a bug so I just work around it or ask for random changes until it goes away. It's not too bad for throwaway weekend projects, but still quite amusing. I'm building a project or webapp, but it's not really coding - I just see stuff, say stuff, run stuff, and copy paste stuff, and it mostly works.
[^palantir-manifesto]: See excerpts from Alexander C. Karp & Nicholas W. Zamiska's _The Technological Republic: Hard Power, Soft Belief, and the Future of the West_ at Palantir's X account:  <https://x.com/PalantirTech/status/2045574398573453312>
[^slop-free]: Refer to the [Slopfree Software Index](https://codeberg.org/brib/slopfree-software-index) for a complete list of software that are not accepting any form of AI, and an exhaustive rationale for not doing that.
[^drupal]: Drupal's founder's blog: "[Never submit code you don't understand](https://dri.es/never-submit-code-you-do-not-understand)"