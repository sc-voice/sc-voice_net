---
title: Linking to sc-voice.net
description: How to link to a sutta or segment
img: nick-fewings-psV7OMIL-iw-unsplash.png
img-alt: image of signpost
link: https://unsplash.com/photos/psV7OMIL-iw
order: 4
---

If you need a link to content hosted on sc-voice.net, you have several choices

* card links
* sutta links
* segment quotes
* site-independent links

### Card Links
The URL for the current card is shown in your browser address field.

* [https://www.sc-voice.net/#/search/mn44/en](https://www.sc-voice.net/#/search/mn44/en)
* [https://www.sc-voice.net/#/sutta/mn44:1.3/en/sujato](https://www.sc-voice.net/#/sutta/mn44:1.3/en/sujato)
* [https://www.sc-voice.net/#/graph/mn44/en/sujato](https://www.sc-voice.net/#/graph/mn44/en/sujato)
* [https://www.sc-voice.net/#/wiki/study/tips](https://www.sc-voice.net/#/wiki/study/tips)

### Sutta Links
Sutta links are show in sutta cards, which recognizes several url formats:

* Segment link (default) [https://www.sc-voice.net/#/sutta/mn44:1.3/en/sujato](https://www.sc-voice.net/#/sutta/mn44:1.3/en/sujato)
* Sutta link [https://www.sc-voice.net/#/sutta/mn44/en/sujato](https://www.sc-voice.net/#/sutta/mn44/en/sujato)
* Language independent link [https://www.sc-voice.net/#/sutta/mn44](https://www.sc-voice.net/#/sutta/mn44)
* Author independent link [https://www.sc-voice.net/#/sutta/mn44/de](https://www.sc-voice.net/#/sutta/mn44/de)

### Segment Quotes
We often want to share a link to specific segment along with its quote:

> [mn44:1.1](https://www.sc-voice.net/#/sutta/mn44:1.1/en/sujato) <i>Evaṁ me sutaṁ—</i>  
> [mn44:1.1](https://www.sc-voice.net/#/sutta/mn44:1.1/en/sujato) So I have heard. 

Te get a segment quote, just click on the segment you want and a Markdown quote with a segment link will be copied to your clipboard.

###  Site-independent links
The sc-voice.net website is actually one of several "EBT-Sites" dedicated to specific languages. 
For example, the DE EBT-Site is dhammmaregen.net. 
Site-independent links are used by SuttaCentral.net to redirect users to the correct site for their language.

#### Site-independent sutta link

* ```https://www.api.sc-voice.net/scv/ebt-site/:sutta_uid/:lang/:author``` 

Example (DE):
[https://www.api.sc-voice.net/scv/ebt-site/thig1.1/de/sabbamitta](https://www.api.sc-voice.net/scv/ebt-site/thig1.1/de/sabbamitta)

#### Site-independent segment link
* ```https://www.api.sc-voice.net/scv/ebt-site/:seg_id/:lang/:author```

Example (DE):
[https://www.api.sc-voice.net/scv/ebt-site/thig1.1:1.3/de/sabbamitta](https://www.api.sc-voice.net/scv/ebt-site/thig1.1:1.3/de/sabbamitta)

#### Site-independent home  link
* ```https://www.api.sc-voice.net/scv/ebt-site/site/:lang```

Example (DE):
[https://www.api.sc-voice.net/scv/ebt-site/site/de](https://www.api.sc-voice.net/scv/ebt-site/site/de)

Example (EN):
[https://www.api.sc-voice.net/scv/ebt-site/site/en](https://www.api.sc-voice.net/scv/ebt-site/site/en)

