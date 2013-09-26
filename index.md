---
layout: default
permalink: /
filename: index.md
---


### Open Government Data: Best-Practices Language for Making Data "License-Free"

Public government data is becoming an increasingly important part of the modern free press, industries from weather forecasting to business intelligence, and the repertoire of tools that can increase the efficiency of government services and support civic participation.

Open government data has been defined in many ways. [One definition][1] uses eight core principles. As a definition, it does not attempt to say what should be open but rather articulates the consensus understanding of what it means to be open. One principle, in its simplest form, states that open government data is "license-free," or in other words that the data has no restrictions on use except as set forth in law.

**This document provides language to affix to data publications so that they may meet, or to make it clear that they meet, the criteria of the “license-free” principle. The language is intended for U.S. federal government agencies.**

#### What You Need to Know

1. Data is “license-free” only if a) copyright, and similar laws do not apply or have been waived, and b) there are no restrictions on use or sharing of the data except as set forth in existing law.
2. Copyright applies to some government data but not others (and never to U.S. law). When it applies, it must be waived by the agency (or owner if not the agency) for the data to meet the "license-free" principle. In this case, data is dedicated to the public domain, not licensed.
3. An "open license" is different. "Open licenses" are designed for other definitions of open (such as open source, open content, and open knowledge), but these exploit copyright protections to enforce their terms. A fear of copyright infringement may hinder innovation and accountability.
4. Data is more valuable when its copyright status is clear through an explicit statement.
5. [Foreign copyright may apply to any government data.][2] A waiver of foreign copyright protections is suggested, especially if foreign use of the data is important.
6. The [Creative Commons CC0 Public Domain Dedication][3] is a widely adopted legal tool allowing a creator to dedicate his/her work to the public domain worldwide. CC0 waives any and all domestic and foreign copyright protections and related rights over a work to whatever extent that they can be waived.

We provide below recommended language for five common situations. The language should be placed in the data package’s README or LICENSE file, at a minimum, and in data catalog listings when possible.

#### For U.S. Federal Government Works

Copyright protection is not available for works of the United States Government under 17 USC § 105 unless a specific exemption applies. We recommend the following language when the data is believed to not be copyrightable:

> As a work of the United States Government, this package is in the public domain within the United States. Additionally, [Agency Name] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at http://creativecommons.org/publicdomain/zero/1.0/).

*This language is in use by the Department of Health & Human Services's [ckanext-datajson project](https://github.com/HHS/ckanext-datajson) and the Consumer Financial Protection Bureau's [qu project](https://github.com/cfpb/qu), both on github.com.*

When mixing government and non-government works, such as on an official government blog with public contributors, we recommend that the non-governmental contributors be required to waive copyright protection to their submissions in a similar manner as above. In some instances, such as contributions to a blog, licensing non-governmental contributions in a manner that meets the requirements of the [the Open Definition][4] may be appropriate, but bear in mind that such contributions would not be “license-free” and thus might not be considered open.

*WhiteHouse.gov uses this mixed approach at http://www.whitehouse.gov/copyright.*

If a statutory exemption to 17 USC § 105 is applicable:

> This is a work of the United States Government that is exempt from 17 USC § 105. However, [Agency Name] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at http://creativecommons.org/publicdomain/zero/1.0/).

#### For Government Works Produced by a Contractor

Works produced under a contract with the government are typically subject to copyright protection. If the contract provides that ownership of the work is transferred to the government, use:

> This work was created through a government contract which assigned copyright to [the United States Government or Agency name]. However, [Agency Name] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at http://creativecommons.org/publicdomain/zero/1.0/).

Or if copyright remains with the contractor, use:

> This work was produced by [Contractor Name] in the performance of a contract with [Agency Name] (contract number [contract number]). [Contractor Name] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at http://creativecommons.org/publicdomain/zero/1.0/).

#### For Primary Legal Materials

The courts have ruled that the law — i.e. edicts of government — is not protected by copyright (see Banks v. Manchester, 128 U.S. 244, 253 (1888) and other cases). This has also been [the position of the U.S. Copyright Office][5].

For federal government primary legal materials, the language for federal government works listed above will typically suffice. For other aspects of law that do not fall into one of the categories above, such as standards incorporated by reference, we recommend the following:

> This work contains laws, which are not subject to U.S. copyright protection. Additionally, [Body] waives copyright and related rights in the work worldwide through the CC0 1.0 Universal Public Domain Dedication (which can be found at http://creativecommons.org/publicdomain/zero/1.0/).

When publishing laws along side annotations in which copyright protections are asserted, we strongly recommend publishing an un-annotated copy of the law with the statement above.

*The Council of the District of Columbia uses CC0 to waive copyright on the DC Code at http://dccouncil.us/UnofficialDCCode.*

#### Additional Notes

Click-through end user agreements and other terms of use statements that bind the user after he/she has acquired the data are always incompatible with the license-free principle. Terms of use may be used to protect the integrity of the government computer systems the data is being downloaded from but cannot restrict use of open government data or bind the end user once the data has been acquired.

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
