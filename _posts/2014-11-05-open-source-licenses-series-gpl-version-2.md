---
id: 336
title: 'Open Source Licenses Series: GPL version 2'
date: 2014-11-05T08:07:14+00:00
author: Sam
layout: post
guid: http://www.samuelip.com/?p=336
permalink: /?p=336
header_choice_select:
  - ""
custom_header_img_id_value:
  - ""
categories:
  - Law
  - Open Source Software
---
As a former programmer, I&#8217;ve always struggled to untangle the various Open Source Software licenses.  I&#8217;m hoping this series will explain, in simple terms, the basics behind such licenses. According to [Black Duck Software](https://www.blackducksoftware.com/resources/data/top-20-open-source-licenses), the GNU Public License version 2.0 is still the most popular open source software license on the internet and as such, we&#8217;ll begin with an introduction to the GPL version 2.0.

<span style="text-decoration: underline;"><strong>GNU Public License (GPL) version 2.0</strong></span>

**Link to GPLv2.0 license:** [here](http://www.gnu.org/licenses/gpl-2.0.html)

**Background: ** The first version of GPL was written by Richard Stallman to address two issues: (1) to ensure software is distributed in source code form; and (2) to ensure subsequent licenses are placed on software that further restricted an individual&#8217;s freedom to share and change it. The GPLv2.0 builds on this and adds what Stallman calls the &#8220;liberty or death&#8221; clause (section 7), explained further below.

**Key Provisions in GPLv2.0:**

  1. You can copy, modify, distribute GPLv2.0 software if you: 
      * accompany it with the source-code;
      * provide a written offer (valid for 3 years) to provide the source code at cost; or
      * for non-commercial distribution, if you pass along the written offer you received if you obtained the object code or executable form.
  2. However, if you modify and subsequently copy and distribute such modifications if you adhere to the following requirements: 
      * cause any work you distribute/publish that contains or is derived from the GPLv2.0 program to be licensed as a whole at no charge under GPLv2.0 (aka &#8220;copyleft&#8221;);
      * cause modified files to carry notices stating you changed the file and the date of any change; and
      * adhere to the requirements in point #1 above.Note: There are special notification requirements for command-line software found in Section 2 of the GPLv2.0
  3. You can only charge a fee for the act of transferring a copy  or offering a warranty protection, but not for the license itself.  In other words, you can sell copies of GPLv2.0 software (or your modifications to it), but those whom you have sold copies to can copy and give away the source code to your software.
  4. If for whatever reason, you are faced with conditions (e.g. court order, patent infringement, etc.) that restrict you from complying with all the requirements of the GPLv2.0, then you must not distribute the GPLv2.0 program (or the modifications).  So for example, if a patent license requires you to pay royalties for each distribution of a certain GPLv2.0 program then you are not permitted to distribute the  program at all.

**Interesting Implications:**

  1. As a software developer, you can take open source software and modify/copy it for internal use.  You are not obligated to release the source code externally. Only when you start releasing it to other companies or contractors working off-site do you need to adhere to the GPLv2.0 requirements.
  2. Creating modules that statically <span style="text-decoration: underline;">or</span> dynamically link to GPL as a whole will subject the module to GPLv2.0.  (If your desire is to keep modules clear of GPLv2.0 requirements, consider using the Lesser GPL license that we will discuss at a later date)