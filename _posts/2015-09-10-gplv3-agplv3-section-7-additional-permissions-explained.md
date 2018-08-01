---
id: 417
title: 'GPLv3 / AGPLv3 &#8211; Section 7 (Additional Permissions) Explained'
date: 2015-09-10T02:59:58+00:00
author: Sam
layout: post
guid: http://www.samuelip.com/?p=417
permalink: /?p=417
header_choice_select:
  - ""
custom_header_img_id_value:
  - ""
categories:
  - Open Source Software
---
Section 7 of GPLv3 has caused a lot of confusion amongst software developers. Once explained, one can see how Section 7  enhances license compatibility and why it has been drafted the way it is. Here is Section 7 (in <span style="color: #0000ff;"><strong>blue</strong></span>) with annotated notes (in black):

#### **<span style="color: #0000ff;"><a style="color: #0000ff;" name="section7"></a>7. Additional Terms.</span>**

**<span style="color: #0000ff;">“Additional permissions” are terms that supplement the terms of this License by making exceptions from one or more of its conditions. Additional permissions that are applicable to the entire Program shall be treated as though they were included in this License, to the extent that they are valid under applicable law. If additional permissions apply only to part of the Program, that part may be used separately under those permissions, but the entire Program remains governed by this License without regard to the additional permissions</span>**.

<span style="color: #0000ff;"><strong>When you convey a copy of a covered work, you may at your option remove any additional permissions from that copy, or from any part of it. (Additional permissions may be written to require their own removal in certain cases when you modify the work.) You may place additional permissions on material, added by you to a covered work, for which you have or can give appropriate copyright permission.</strong></span>

Essentially, these two paragraphs introduces the concept of &#8220;Additional Permissions&#8221;, which are terms that make exceptions from one or more of GPLv3&#8217;s conditions. Generally, modifications to software licensed under GPLv3 must be released under the GPLv3.  However, Section 7 provides that if you are the copyright holder (or have permission from the copyright holder), you can add additional permissions for what the user can do with the licensed work.  However, these permissions &#8212; above and beyond what GPLv3 says &#8212; can be removed by downstream recipients.

<span style="color: #0000ff;"><strong>Notwithstanding any other provision of this License, for material you add to a covered work, you may (if authorized by the copyright holders of that material) supplement the terms of this License with terms:</strong></span>

  * <span style="color: #0000ff;"><strong>a) Disclaiming warranty or limiting liability differently from the terms of sections 15 and 16 of this License; or</strong></span>
  * <span style="color: #0000ff;"><strong>b) Requiring preservation of specified reasonable legal notices or author attributions in that material or in the Appropriate Legal Notices displayed by works containing it; or</strong></span>
  * <span style="color: #0000ff;"><strong>c) Prohibiting misrepresentation of the origin of that material, or requiring that modified versions of such material be marked in reasonable ways as different from the original version; or</strong></span>
  * <span style="color: #0000ff;"><strong>d) Limiting the use for publicity purposes of names of licensors or authors of the material; or</strong></span>
  * <span style="color: #0000ff;"><strong>e) Declining to grant rights under trademark law for use of some trade names, trademarks, or service marks; or</strong></span>
  * <span style="color: #0000ff;"><strong>f) Requiring indemnification of licensors and authors of that material by anyone who conveys the material (or modified versions of it) with contractual assumptions of liability to the recipient, for any liability that these contractual assumptions directly impose on those licensors and authors.</strong></span>

<span style="color: #0000ff;"><strong>All other non-permissive additional terms are considered “further restrictions” within the meaning of section 10. If the Program as you received it, or any part of it, contains a notice stating that it is governed by this License along with a term that is a further restriction, you may remove that term. If a license document contains a further restriction but permits relicensing or conveying under this License, you may add to a covered work material governed by the terms of that license document, provided that the further restriction does not survive such relicensing or conveying.</strong></span>

The above paragraph is about a limited list of additional restrictions that you may add to your modifications if you are the copyright holder (or if you have permission from the copyright holder), thus enhancing license compatibility. Without the above paragraph, combining GPLv3 code with another OSS license which introduces a relatively benign restriction that does not exist in GPLv3 would result in a license violation.

Unlike &#8220;additional permissions&#8221;, this list is understandably limited &#8212; if not, GPLv3 software may become so much restricted that it is no longer free.  Moreover, these additional restrictions may not be removed.  Lastly, Section 7 states that if you receive a GPLv3 licensed work with additional restrictions not found in the list in Section 7, you may remove it.

<span style="color: #0000ff;"><strong>If you add terms to a covered work in accord with this section, you must place, in the relevant source files, a statement of the additional terms that apply to those files, or a notice indicating where to find the applicable terms.</strong></span>

<span style="color: #0000ff;"><strong>Additional terms, permissive or non-permissive, may be stated in the form of a separately written license, or stated as exceptions; the above requirements apply either way.</strong></span>

The above paragraphs states the obvious &#8212; essentially, if you add additional permissive or non-permissive (aka further restrictions) terms, you need to direct the user to where they can be found.  I have often see these additional terms placed in the same file where the GPLv3 license is found under a separately identified paragraph.

For a more in-depth treatment on Section 2, see the Free Software Foundation&#8217;s article on Section 2: [here](http://gplv3.fsf.org/additional-terms-dd2.html).

&nbsp;

&nbsp;