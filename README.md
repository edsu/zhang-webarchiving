A Brief Look at Web Archiving
=============================

Notes for Jane Zhang's Digital Curation class at Catholic University.
March 5, 2014.

Hi
--

* How many people use social media, have a website, run a webserver?
* Why do we love the Web? Why do we hate the Web?
* The Web needs to be cared for, and it needs the collective attention of 
  archivists, to create archives of web content and to help build a Web 
  that can be. 
* [What is the archive, to archive, an archive?](http://blogs.loc.gov/digitalpreservation/2014/02/what-do-you-mean-by-archive-genres-of-usage-for-digital-preservers/)
* Archivvy: select, appraise, arrange, describe, preserve, make available
* My background
* NDF Talk: [Web as a Preservation Medium](http://inkdroid.org/journal/2013/11/26/the-web-as-a-preservation-medium/)

Why Does the Web Archive Matter?
--------------------------------

* [Supreme Court Opionions Clicks That Lead Nowhere](http://www.nytimes.com/2013/09/24/us/politics/in-supreme-court-opinions-clicks-that-lead-nowhere.html)
* [UK Conservative Party deletes links](http://www.theguardian.com/politics/2013/nov/13/conservative-party-archive-speeches-internet)
* lots of work to do

How much of the Web is archived?
--------------------------------

* Not a solved problem.
* IA: 366 billion
* IIPC: 75 billion
* Google: 1T URLs 
* generous guesstimate: 44%

Despair?
--------

* Verne Harris - [The Archival Sliver](http://www.nyu.edu/classes/bkg/methods/harris.pdf)

    Even if archivists in a particular country were to preserve every record generated throughout the land, they would still have only a sliver of a window into that country’s experience. But of course in practice, this record universum is substantially reduced through deliberate and inadvertent destruction by records creators and managers, leaving a sliver of a sliver from which archivists select what they will preserve. And they do not preserve much.

    The archival record is best understood as a sliver of a sliver of a sliver of a window into process. It is a fragile thing, an enchanted thing, defined not by its connection to “reality”, but by its open-ended layerings of construction and reconstruction.

* [Losing My Revolution](http://arxiv.org/abs/1209.3026)
* [Wikileaks](http://www.wikileaks.org)
* [NSA Files](http://www.theguardian.com/world/the-nsa-files+content/document)
* [Manning Transcripts](https://pressfreedomfoundation.org/bradley-manning-transcripts)

Library of Congress
-------------------

* team of 6 + InternetArchive
* [selection](http://lcweb2.loc.gov/diglib/lcwa/html/lcwa-home.html)
* [notification](http://www.loc.gov/webarchiving/notice_to_webmasters.html)
* seed lists, scoping
* quality control 
* embargo period
* access!

The Wider Web
-------------

* [Internet Archive](http://archive.org)
* [IIPC](http://netpreserve.org)
* [perma.cc](http://perma.cc)
* [ArchiveIt](http://archiveit.org)
  * [Columbia University Human Rights Watch Archive](http://library.columbia.edu/locations/chrdr/hrwa.html)
  * [2014 Winter Olympics](https://archive-it.org/collections/4200)
* [Hanzo](http://www.hanzoarchives.com/)
* [ArchiveTeam](http://archiveteam.org/)
* [ArchiveSocial](http://archivesocial.com/)
* [CommonCrawl](http://commoncrawl.org/)
* [Social Feed Manager](https://github.com/gwu-libraries/social-feed-manager)

Nuts & Bolts
------------

* [1/10 Americans think HTML is an STD](http://www.latimes.com/business/technology/la-fi-tn-1-10-americans-html-std-study-finds-20140304,0,1188415.story)
* 25 years old: HTTP, HTML, URL 
* robots.txt
* [OpenWayback](https://github.com/iipc/openwayback)
* [Heretrix](https://github.com/iipc/heritrix3)
* [wget](https://www.gnu.org/software/wget/)
* [pywb](https://github.com/ikreymer/pywb)
* [WARC](http://www.iso.org/iso/catalogue_detail.htm?csnumber=44717): ISO 28500:2009 ; wget -H -Dwww.cua.edu -r -l 2 --warc-file=cua --convert-links="on" http://lis.cua.edu/courses/index.cfm
* [Memento](http://tools.ietf.org/html/rfc7089) RFC 7089
* [UNT Nomination Tool](http://digital2.library.unt.edu/nomination/)

Interlude: Web Packages
-----------------------

* Demo Facebook and Twitter "archive" packages.
* [Packaging on the Web](https://github.com/w3ctag/packaging-on-the-web)
* [ResourceSync](http://www.niso.org/workrooms/resourcesync/)

Challenges
----------

* scoping (backlinks)
* streaming video / audio
* dynamic content / ghost
* funding (sustainable)
* copyright
* storage space
* format migration
* digital preservation significant characteristics?
* collection development: seedlists, inventory
* single point of failure (IA)

What can you do?
----------------

* Big data is great, but start with [small data](https://www.ideals.illinois.edu/handle/2142/39750):
  * your organizations web presence
  * local blogs
  * local government
  * local arts scene / businesses
* Website owners:
  * Permalinks/Cool URIs
  * robots.txt
  * sitemaps
* [Personal Digital Archiving](http://visions.indstate.edu/pda2014/)
  * outreach with your community
  * best practices / guidance
* Keep an open mind.
* Have a whole class about web archiving!

Learn More
----------

* [ArchiveIt](https://archive-it.org/) webinars for libraries, archives, classes.
* [More Podcast Less Process](http://keepingcollections.org/more-podcast-less-process/) - Episode #7 on Web Archiving - Alex Thurman (Columbia) and Lily Pregill (New York Art Resources Consortium)
* [Web Curators Mailing List](http://netpreserve.org/web-curators-mailing-list)
