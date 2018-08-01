---
id: 423
title: Software Licensing and the LGPL
date: 2015-11-09T22:59:38+00:00
author: Sam
layout: post
guid: http://www.samuelip.com/?p=423
permalink: /?p=423
header_choice_select:
  - ""
custom_header_img_id_value:
  - ""
categories:
  - Uncategorized
---
Provisions that prohibit reverse engineering are commonly found in commercial licenses (e.g., EULAs, Terms of Use, Software License Agreements, etc.). While these provisions serve to protect the software developer&#8217;s intellectual property, software developers who include such clauses in their software licenses must ascertain there no software components are used that are licensed under the GNU Lesser General Public License (LGPL) (called a Library by LGPL). As the use of Open Source Software (OSS) during the development process is prevalent in many organizations, this issue is often overlooked.

LGPL states that if one combines or links a &#8220;work that uses the Library&#8221; with the Library, and subsequently distributes the combined or linked work, then one cannot include reverse engineering provisions in the license agreement.  Specifically, Section 6 of LGPL 2.1 states:

> As an exception to the Sections above, you may also combine or link a &#8220;work that uses the Library&#8221; with the Library to produce a work containing portions of the Library, and distribute that work under terms of your choice, provided that the terms permit modification of the work for the customer&#8217;s own use and reverse engineering for debugging such modifications.

Putting aside the controversial issue of whether Section 6 only applies to statically linked works, a plain reading of Section 6 suggests that LGPL places a _positive obligation_ on the software developer to include within their software license certain terms that _permit_ reverse engineering for debugging modifications of the combined work as a whole, _not just the Library._

This is consistent with the principles of &#8220;free&#8221; software advanced by the Free Software Foundation. Anyone should be able to modify LGPL licensed &#8212; that is, after all, one of the four essential freedoms of &#8220;free&#8221; software. However, after making modifications to the Library, a software developer may need to reverse engineer the rest of your proprietary object code / executable to make the modified version of the Library work with the proprietary object code / executable. Section 6 of LGPL ensures the freedom to do so.

Some in the OSS community (e.g., Software Freedom Law Centre)  hold the view that software license terms do not need to _permit_ reverse engineering.  Rather, software license terms must only refrain from &#8220;_prohibit[ing]_ user modification and reverse engineering for debugging of modifications to the LGPL&#8217;d code included in the combination&#8221;.  While this is the view of one well respected organization in the OSS community, this view may not be upheld in the courts of every jurisdiction.

Similar to LGPL 2.1, Section 4 of LGPL 3.0 states:

> You may convey a Combined Work under the terms of your choice that, taken together, effectively do not restrict modification of the portions of the Library contained in the Combined Work and reverse engineering for debugging such modifications&#8230;

LGPL 3.0 differs from 2.1 in that the _positive obligation_ to permit reverse engineering is replaced with a prohibition on software developers from restricting reverse engineering. This is aligned with the Software Freedom Law Centre&#8217;s views regarding the interpretation of Section 6 of LGPL 2.1.  While it isn&#8217;t entirely clear whether &#8220;reverse engineering&#8221; applies to just the Library or the Combined Work as a whole, there is still a strong argument that if reverse engineering of the Combined Work as a whole is required for debugging modifications to the Library, then that a software developer cannot restrict such activity.

Ultimately, whether a software developer is using software licensed under LGPL 2.1 or LGPL 3.0, they should be cautious when drafting their license agreements and should tailor the terms of such license agreement accordingly.

&nbsp;

&nbsp;

&nbsp;

&nbsp;