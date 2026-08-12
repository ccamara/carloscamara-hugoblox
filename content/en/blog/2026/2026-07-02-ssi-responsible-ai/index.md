---
title: "Responsible AI in RSE - a living register to support practitioners, leaders and policymakers"
summary: ""
date: 2026-07-14
draft: false

# Featured image for cards/social
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''

# Authors are matched to profiles in content/authors/
authors:
  - Joseph Shingleton
  - me
  - Oscar Seip
  - Stephan Druskat
  - Sam Harrison
  - Arielle Bennett

tags:
  - AI
  - SSI

content_meta:
  trending: false
---

> [!NOTE]
> This collaborative post was originally published at the [Software Sustainability Blog](https://www.software.ac.uk/news/responsible-ai-rse-living-register-support-practitioners-leaders-and-policymakers) and was authored by some of the Responsible AI Study Group members: Joseph Shingleton, Carlos Cámara-Menoyo, Oscar Seip, Stephan Druskat, Sam Harrison, Arielle Bennett and B. Almarzouq.

The research software community is nothing if not diverse. It brings together practitioners loosely connected by their relationship with the broad and sometimes nebulous idea of 'research software'. The day-to-day experience of, say, an engineer developing and maintaining computational fluid dynamics simulations is very different from that of a data architect supporting clinical data pipelines. It is unsurprising, then, that this diversity of experience gives rise to a wide range of hopes, concerns, and uncertainties - particularly within the context of Generative Artificial Intelligence (GenAI).

Research software’s rich diversity of experience is explicitly recognised in the Alliance for Data Science and AI’s (ADSA) and US-RSE’s recent community [position statement on GenAI](https://github.com/Academic-Data-Science-Alliance/rse-ai-position-statement/blob/main/RSE-AI-Final_Statement.md) in the RSE workplace:

*“The conversation around software engineering in the age of GenAI has […] left relatively little space for nuanced discussions of […] the complexities of developing research software in a future where GenAI is widely available.”*

The nuance and complexity identified by ADSA make the development of GenAI guidance and policy particularly challenging. In the context of a highly diverse, reactive, and evolving discipline like research software engineering, there is no “one-size-fits-all” approach to GenAI governance. Rather, we must develop systems that capture the nuanced and shifting concerns of practitioners, leaders, funders and other stakeholders; systems that can also act as an evolving reference for best practice. The [Responsible AI Risk Register for RSE](https://jshng-glasgow.github.io/SSI-Responsible-AI-Risk-Register/) (RAIRR) is intended as one such system.

RAIRR is a living register designed to support open discussion of how GenAI adoption is affecting research software practice. It allows contributors to document risks identified in their day-to-day work, alongside possible mitigations, examples, and shared responsibility for responding to them. We expect the register to become a useful resource to inform the development of AI policies that are grounded in the actual experience of RSE practitioners, rather than hype, promises, expectations or unfounded fears. RAIRR is open for anyone to use and contribute to, being particularly relevant to practitioners, leaders and policymakers.

## Pilot and technical implementation

We introduced RAIRR at the [Collaboration’s Workshop 2026](https://www.software.ac.uk/workshop/collaborations-workshop-2026-cw26) as an opportunity to test the idea in practice. Working in small groups, attendees were asked to identify the ways in which GenAI adoption might lead to harm, failure, or undesirable outcomes in their professional work. Crucially, they were also asked to consider valid approaches to mitigation of these risks, and suggest examples of best practices they have seen, either in institutional guidance or individual practice. This provides a pragmatic and actionable account of practitioners' perception of AI risk in research software.

An example of one such risk is shown below ([contributed by Paddy McCann’s group](https://github.com/jshng-glasgow/SSI-Responsible-AI-Risk-Register/issues/178)), which highlights the potential for the accidental reuse of licensed code in software with incompatible licenses (e.g. the use of copyleft-licensed code within more permissively licensed software). Given the provenance of AI-generated code is not visible to developers using GenAI (i.e. there is no way of knowing whether the generated code is mostly or entirely based on code with a restrictive license), there is a real risk that such code will be unintentionally reused in violation of licenses.

![](https://www.software.ac.uk/sites/default/files/2026-06/RAIDD.png)

Risks can be added to and updated in the register through issue templates provided in the repository. As well as adding new risks or updating existing ones, the templates also allow users to add relevant or interesting resources. Since each risk is directly associated with a GitHub issue, users wishing to discuss a risk further can easily do so by adding a comment to the issue. This facilitates open discussion and allows users to add additional context or framing to existing risks. Of course, some users may wish to submit more sensitive risks – in such cases, an alternate route for anonymous contributions via an online form is also available.

## What's next?

The register is open to new contributions describing risks around AI adoption within research software practices. We also welcome discussion of existing risks via their associated GitHub Issues, and encourage people to add examples of how risks can be mitigated, and to point to examples of best practice. We will be running a further workshop at RSECon26 in Sheffield, so please keep an eye out for opportunities for collaborative contribution sessions.

## Contributing to RAIRR

You can view the full register and contribute to it [here](https://jshng-glasgow.github.io/SSI-Responsible-AI-Risk-Register/). Please make sure to read the [README.md](https://github.com/jshng-glasgow/SSI-Responsible-AI-Risk-Register/blob/main/README.md) and [CONTRIBUTING.md](http://contributing.md/) for more information about what makes a good contribution to the register.

The register is maintained by the SSI Responsible AI Study Group – a recently established group interested in understanding ways in which AI may be adopted safely, fairly, and constructively within research software practices. The group is open to new members from both within the SSI and externally – if you’re interested in joining, then please contact joseph.shingleton[at]glasgow.ac.uk or oscar.seip[at]manchester.ac.uk.
