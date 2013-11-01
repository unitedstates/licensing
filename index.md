---
layout: default
permalink: /
filename: index.md
---


## Open Government Data

### Best-Practices Language for Making Data “License-Free”

Public data generated or commissioned by government bodies is becoming an increasingly important part of the public sphere — from new forms of civic participation, journalism, transparency and accountability to new opportunities for innovation and growth.

As open data guidelines evolve to meet current practices, including new goals from the White House and the increasing role of government contractors in the production of public government data, we think it is essential that U.S. federal government agencies have the tools to preserve the United States's long legal tradition of ensuring that public information created by the federal government is exempt from U.S. copyright and remains free for everyone to use without restriction.

Leading open data standards and principles, such as the 2007 [8 Principles of Open Government Data][1], have established that the absence of restrictions on the reuse of government information is a core part of promoting good government and entrepreneurial innovation. When there are no restrictions on the reuse of government data, the data is said to be “license-free”. To the greatest extent possible, we strongly believe U.S. public government data should be “license-free”.

**This document provides language to affix to data publications so that they may meet, or to make it clear that they meet, the criteria of the “license-free” principle. The language is intended for U.S. federal government agencies.**

#### What You Need to Know

1. Data is “license-free” only if a) copyright, and similar laws do not apply or have been waived, and b) there are no restrictions on use or sharing of the data except as set forth in existing law.
2. Copyright applies to some government data but not others (and never to U.S. law). When it applies to public information, it should be waived so that the public can use it without restriction.
3. Government data should be dedicated to the public domain and not licensed. Licensing (including open licensing) builds on copyright and other related rights, and the use of licensing is contrary to the long tradition that federal government data is in the public domain.
4. Data is more valuable when it is clear that there is a green light enabling reuse.
5. [Foreign copyright may apply to any government data.][2] A waiver of foreign copyright protections is suggested, especially if foreign use of the data is important.
6. The [Creative Commons CC0 Public Domain Dedication][3] is a widely adopted legal tool allowing a creator to dedicate his/her work to the public domain worldwide. CC0 waives any and all domestic and foreign copyright protections and related rights over a work to whatever extent that they can be waived.

We provide below recommended language for five common situations. The language should be placed in the data package’s README or LICENSE file, at a minimum, and in data catalog listings when possible.

#### For U.S. Federal Government Works

Copyright protection is not available for works of the United States Government under 17 USC § 105 unless a specific exemption applies. We recommend the following language when the data is believed to not be copyrightable:

> As a work of the United States Government, this package is in the public domain within the United States. Additionally, [Agency Name] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/)).

*This language is in use by the Department of Health & Human Services's [ckanext-datajson project](https://github.com/HHS/ckanext-datajson) and the Consumer Financial Protection Bureau's [qu project](https://github.com/cfpb/qu), both on github.com.*

It is incumbent on the agency to attempt to determine the intellectual property status of any work it publishes as open data. If the status of a work is unclear, it should be clearly marked as such, such as with a notice that the work may not be a work of the United States Government.

When mixing government and non-government works, such as on an official government blog with public contributors, we recommend that the non-governmental contributors be required to waive copyright protection to their submissions in a similar manner as above. In some instances, such as contributions to a blog, licensing non-governmental contributions in a manner that meets the requirements of the [the Open Definition][4] may be appropriate, but bear in mind that such contributions would not be “license-free”, as per the discussion above. In that case, material which is openly licensed rather than license-free should be clearly marked as such in a machine-processable manner.

*The White House's [Project Open Data](http://project-open-data.github.io/) requires outside contributors to waive copyright using CC0. [WhiteHouse.gov](http://www.whitehouse.gov/) also uses a mixed approach at [http://www.whitehouse.gov/copyright](http://www.whitehouse.gov/copyright).*

If a statutory exemption to 17 USC § 105 is applicable, use:

> This is a work of the United States Government that is exempt from 17 USC § 105. However, [Agency Name] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/)).

#### For Government Works Produced by a Contractor

Works produced under a contract with the government are typically subject to copyright protection. If the contract provides that ownership of the work is transferred to the government, use:

> This work was created through a government contract which assigned copyright to [the United States Government or Agency name]. However, [Agency Name] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/)).

Or if copyright remains with the contractor, use:

> This work was produced by [Contractor Name] in the performance of a contract with [Agency Name] (contract number [contract number]). [Contractor Name] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/)).

Note that not all data is copyrightable. For instance, in the United States facts cannot be copyrighted. You should avoid implying copyright exists on works that are not within the domain of copyright law. However, use of the CC0 waiver is appropriate when there is any ambiguity.

#### For Primary Legal Materials

The courts have ruled that the law — i.e. edicts of government — is not protected by copyright (see Banks v. Manchester, 128 U.S. 244, 253 (1888) and other cases). This has also been [the position of the U.S. Copyright Office][5].

For federal government primary legal materials, the language for federal government works listed above will typically suffice. For other aspects of law that do not fall into one of the categories above, such as standards incorporated by reference, we recommend the following:

> This work contains laws, which are not subject to U.S. copyright protection. Additionally, [Body] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at [http://creativecommons.org/publicdomain/zero/1.0/](http://creativecommons.org/publicdomain/zero/1.0/)).

When publishing laws along side annotations in which copyright protections are asserted, we strongly recommend publishing an un-annotated copy of the law with the statement above.

*The Council of the District of Columbia uses CC0 to waive copyright on the DC Code at [http://dccouncil.us/UnofficialDCCode](http://dccouncil.us/UnofficialDCCode).*

#### Additional Notes

Click-through end user agreements and other terms of use statements that bind the user after he/she has acquired the data are always incompatible with the license-free principle. Terms of use may be used to protect the integrity of the government computer systems the data is being downloaded from but cannot restrict use of open government data or bind the end user once the data has been acquired.

The same principles outlined here for data also apply to software. In software licensing, two unique concerns arise. First, can the CC0 Public Domain Dedication be used for software? According to Creative Commons, [CC0 may be used for software](http://wiki.creativecommons.org/CC0_FAQ) and CC0 is compatible with many open source software licenses. (This differs from the Creative Commons licenses, like CC-BY, which are not compatible with open source licenses, but recall that CC0 is a waiver and not a license.) Second, does CC0 disclaim warranties as software licenses typically do? Yes, CC0 includes a disclaimer of warranties very similar to typical software licenses. Unfortunately the Open Source Initiative has [not specifically approved](http://opensource.org/faq#cc-zero) CC0 as open source. However, our goal is this document is not to advocate for open source but to address a higher standard held for government works. For these reasons we believe the recommended language we present for data above can and should be used for software created by government as well.

The Open Data Commons Public Domain Dedication and License (PDDL) is very similar to the Creative Commons CC0. It may be used in place of CC0.

"Open licensing" presumes copyright protection. Note that the CC0 Public Domain Dedication is, mostly, not a license but rather a waiver. Be careful not to call use of CC0 "open licensing." Where the waiver within CC0 is ineffective for any reason, CC0 contains a fallback public license that permits worldwide reuse.

[1]: http://opengovdata.org "Open Government Working Group 2007"
[2]: http://www.copyright.gov/history/law/clrev_94-1476.pdf "House Report 94-1476, page 59."
[3]: http://creativecommons.org/publicdomain/zero/1.0/legalcode
[4]: http://opendefinition.org/
[5]: http://ipmall.info/hosted_resources/copyrightcompendium.asp "Compendium II: Copyright Office Practices. 1998. Section 206.01."
[6]: http://creativecommons.org/publicdomain/mark/1.0/

#### Contributors and Supporters

Joshua Tauberer<br/>
*[GovTrack.us](http://www.govtrack.us)*

Eric Mill<br/>
*[Sunlight Foundation](http://sunlightfoundation.com)*

Jonathan Gray<br/>
*[Open Knowledge Foundation](http://okfn.org)* *

Ellen Miller<br/>
*[Sunlight Foundation](http://sunlightfoundation.com)*

Joseph Lorenzo Hall<br/>
*[Center for Democracy and Technology](https://www.cdt.org/)*

\* Affiliation is for identification purposes only.

We also thank Timothy Vollmer, Puneet Kishor, and other reviewers for their discussion and ideas, many of which we have borrowed here. Our gratitude does not imply their endorsement.
