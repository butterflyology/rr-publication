sharing, publishing, archiving
=====
author: Karen Cranston, Hilmar Lapp

URL to lesson:<br/>
https://github.com/Reproducible-Science-Curriculum/rr-publication

<br/>
<!-- public domain dedication copied from CC -->
<p style="font-size: small; text-align: center" xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <span rel="dct:publisher" resource="[_:publisher]">the person who associated CC0</span>
  with this work has waived all copyright and related or neighboring
  rights to this work.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="[_:publisher]">
  United States</span>.
</p>

Non synomymous
======

sharing, publishing, archiving
* _shared_ could mean I emailed it to you ;)
* _publish_ : citable artifact, discoverable
* _archive_ : long-term preservation

why, what, when, where, how, with whom to share & publish?
=====

* why publish?
* what materials do we need to publish?
* when do we make them available? 
* who are we sharing with?
* where do we publish various outputs?
* how do we prepare materials for publication?

For the remaining slides we are going to assume that we are at the point of publication.

why?
=====
incremental: true

* funding agency / journal requirement
* community expects it
* increased visibility / citation

increased visibility / citation
=====
left: 70%

[![Piwowar & Vision (2013) Data reuse and the open data citation advantage.](https://dfzljdn9uc3pi.cloudfront.net/2013/175/1/fig-1-full.png)](https://dx.doi.org/10.7717/peerj.175)

***

Piwowar & Vision (2013) "[Data reuse and the open data citation advantage.](https://dx.doi.org/10.7717/peerj.175)" PeerJ, e175

<small>Figure 1: Citation density for papers with and without publicly available microarray data, by year of study publication.</small>

why?
=====

* funding agency / journal requirement
* community expects it
* increased visibility / citation
* _better research_

better research
=====
left: 70%

[![Wicherts et al (2011) Willingness to Share Research Data Is Related to the Strength of the Evidence and the Quality of Reporting of Statistical Results.](http://journals.plos.org/plosone/article/figure/image?size=large&id=info:doi/10.1371/journal.pone.0026828.g001)](http://dx.doi.org/10.1371/journal.pone.0026828)

***

<small>Wicherts et al (2011) "[Willingness to Share Research Data Is Related to the Strength of the Evidence and the Quality of Reporting of Statistical Results.](http://dx.doi.org/10.1371/journal.pone.0026828)" PLoS ONE 6(11): e26828</small>

<p style="font-size: 75%">Figure 1. Distribution of reporting errors per paper for papers from which data were shared and from which no data were shared.</p>

why?
=====

* funding agency / journal requirement
* community expects it
* increased visibility / citation
* better research
* more efficient, less redundant science
    - by allowing others to build upon our work

Activity (in pairs)
=====
type: prompt

<br/><br/>
**Catalog the artifacts you produced this morning.**
* What needs to be published?
* What does not need to be published?
* Anything that cannot be published?

it depends
=====

share? _yes!_
* starting data set
* metadata
* data cleaning steps
* analysis scripts
* source code
* readme

***

share? _maybe?_
* raw data
* processed / cleaned data
* intermediate results

share? _no!_
* confidential (e.g., patient) data
* material already published
* pre-existing restrictive license
* passwords, private keys

where?
=====
type: prompt

* Domain-specific data repository (GenBank, PDB)
* Source code hosting service ([GitHub](http://github.com), [Bitbucket](http://bitbucket.com))
* Generic repository ([Dryad](http://datadryad.com), [Figshare](http://figshare.com), [Zenodo](http://zenodo.org))
* Institutional repository
* Sharing services ([RPubs](http://rpubs.com), [iPython Notebook Viewer](http://nbviewer.ipython.org/), Dropbox, Google Drive)

<br/>
**Discuss**: Contrast with journal supplementary materials.

many repositories
=====
title: false

[![Registry of Research data Repositories](http://www.re3data.org/wp-content/uploads/2013/09/cropped-re3data_Logo_RGB_header.png)](http://re3data.org)
[![Growth of re3data.org](http://www.re3data.org/wp-content/uploads/2014/11/growth-re3data.png)](http://www.re3data.org/2014/11/over-1000-research-data-repositories-indexed-in-re3data-org/)

how to choose?
=====

* is there a domain specific repository?
* what are the backup & replication policies?
* is there a plan for long-term preservation?
* can people find your materials?
* is it citable? (does it provide DOIs)
* is your purpose archival, sharing or publication?

university libraries try to help
=====
title: false

<!-- Replace with your university library's data management guide -->
<iframe width="100%" height="700px" src="http://guides.uflib.ufl.edu/datamanagement"></iframe>

what goes where when?
=====

**You will likely have different artifacts:**
* Rmarkdown
* source code
* other documentation
* raw data
* derived data

***

**Possible workflow:**
* develop data & code on GitHub
* upon publication
    - share markdown on RPubs
    - archive a snapshot of data in Dryad
    - code snapshot to Zenodo 

how to share, publish: file formats
=====

**Do's**
* non-proprietary file formats
* text file formats (.csv, .tsv, .txt)

***

**Don't's**
* proprietary file formats (.xls)
* data as PDFs or images
* data in Word documents

how to share, publish: checklist
=====

* top-level `README` that describes the data or software package
* list files and naming conventions
* describe abbreviations, column names, etc
* installation and usage instructions for software
    - create separate `INSTALL` if long
* citation instructions
    - consider creating a [`CITATION` file](http://blog.rtwilson.com/encouraging-citation-of-software-introducing-citation-files/)
* contribution instructions
    - Github will automatically link to `CONTRIBUTING` file for new issues and pull requests

Activity (in pairs)
=====
type: prompt

<br/><br/>
**Documenting your research:**
* collect all of the to-be-archived artifacts from the preceding lesson into a directory
* write a README file that describes the contents of the directory

put a license or waiver on it
=====
title: false

<br/>
<br/>
<p style="font-size: 300%; font-weight: bold; text-align: center">Put a license or waiver on it</p>

does copyright apply?
=====

**Copyright applies to creative works**
* source code
* text (manuscripts etc)
* images

***

**Typically not copyrightable:**
* data, results
* individual records in a database of facts

**Depends on jurisdiction and case:**
* _curated collections of data_?
* _databases_
* _medical images?_

Choose A License
=====

<iframe width="100%" height="700px" src="http://choosealicense.com/"></iframe>

software licensing guide
=====
left: 70%

[![Morin et al 2012, A Quick Guide to Software Licensing for the Scientist-Programmer](http://journals.plos.org/ploscompbiol/article/figure/image?size=large&id=info:doi/10.1371/journal.pcbi.1002598.g002)](10.1371/journal.pcbi.1002598.g002)

***

> Morin, Andrew, Jennifer Urban, and Piotr Sliz. 2012. “[A Quick Guide to Software Licensing for the Scientist-Programmer.](http://dx.doi.org/10.1371/journal.pcbi.1002598)” PLoS Computational Biology 8 (7): e1002598.

Creative Commons
=====
title:false

<iframe width="100%" height="700px" src="http://creativecommons.org/choose/"></iframe>

open is not open to interpretation
=====

[The Open Definition](http://opendefinition.org/) sets out principles that define “openness” in relation to data and content. It makes precise the meaning of “open” in the terms _open data_, _open content_, and _open source_:

> “Open means anyone can freely access, use, modify, and share for any purpose (subject, at most, to requirements that preserve provenance and openness).”

or more succinctly:

> “Open data and content can be freely used, modified, and shared by anyone for any purpose”

Waiving copyright
=====

<center>[![CC Zero](http://mirrors.creativecommons.org/presskit/buttons/88x31/png/cc-zero.png)](http://creativecommons.org/about/cc0)</center>

> CC0 enables scientists, educators, artists and other creators and owners of copyright- or database-protected content to waive those interests in their works and thereby place them as completely as possible in the public domain, so that others may freely build upon, enhance and reuse the works for any purposes without restriction under copyright or database law.

Dryad requires CC0
=====
> [Dryad’s use of CC0](http://datadryad.org/pages/faq#info-cc0) to make the terms of reuse explicit has some important advantages:
> * Interoperability: Since CC0 is both human and machine-readable, other people and indexing services will automatically be able to determine the terms of use.
> * Universality: CC0 is a single mechanism that is both global and universal, covering all data and all countries. It is also widely recognized.
> * Simplicity: There is no need for humans to make, or respond to, individual data requests, and no need for click-through agreements. This allows more scientists to spend their time doing science.

licenses versus community norms
=====

From the [Panton Principles](http://pantonprinciples.org/faq/#Q11_What_are_community_norms_and_why_are_they_important):
> [...] in the scholarly research community the act of citation is a commonly held community norm when reusing another community member’s work.
>
> Community norms can be a much more effective way of encouraging positive behaviour, such as citation, than applying licenses. A well functioning community supports its members in their application of norms, whereas licences can only be enforced through court action and thus invite people to ignore them when they are confident that this is unlikely.

licenses are legal instruments
=====

* Licenses, copyright, terms of use are complicated issues.
* There are legal implications to your choices.
* Citation is a professional norm in science.
    - We have good systems for ensuring proper citation.
    - Would you try to sue someone in court who fails to cite you properly?
* Keep it simple by putting the least-restrictive license possible

<br/>
_Let scientists do science without having to talk to lawyers._