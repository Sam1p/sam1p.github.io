---
id: 408
title: Software-as-a-Service and Open Source Software Licenses
date: 2015-09-04T01:16:53+00:00
author: Sam
layout: post
guid: http://www.samuelip.com/?p=408
permalink: /?p=408
header_choice_select:
  - ""
custom_header_img_id_value:
  - ""
categories:
  - Uncategorized
---
​Generally, it is the _distribution_ of open source software (or derivative works thereto) that triggers the source code disclosure requirements found in many open source software licenses such as the GNU Public License (**“GPL****”**). However, with the prevalence of Software-as-a-Service (**“SaaS”**), many believe that because their product offerings are based on a SaaS model, there is no _distribution_, and hence, the source code disclosure requirements in certain open source software licenses are not triggered. Unfortunately, this belief can result in the use of open source software that exposes the client&#8217;s proprietary source code for the following reasons:

**1.** **Third Party Application Hosting May Result in A &#8220;Distribution&#8221;**

<div>
  Unless a client is hosting its own product offering, having a third party (e.g., Amazon) host the application may well be considered a <i>distribution</i> under open source software licenses such as GPLv2.0. Other licenses such as GPLv3.0 exempt hosting providers who provide facilities for running open source software (or modifications thereto) licensed under GPL version 3.0, but only if such service providers, “do so exclusively on your behalf, under your direction and control, on terms that prohibit them from making any copies of your copyrighted material outside their relationship with you” (s. 2, GPLv3). Therefore, if these conditions are not met, a hosting relationship may well be considered a <i>distribution</i> and subject a client’s to source code disclosure requirements.
</div>

<div>
</div>

<div>
  <strong><em><span style="color: #525252;">Note: </span></em></strong>Interestingly, while Google uses much open source software, they also host their own web applications and can readily comply with this open source licensing obligation.
</div>

<div>
</div>

<div>
</div>

<div>
  <strong>2. </strong><strong>JavaScript Components of a SaaS Offering May Result In A &#8220;Distribution&#8221;</strong>
</div>

<div>
  In a SaaS model, applications are hosted and made available to customers over the internet. However, JavaScript (small pieces of code) related to the SaaS application is often sent to a customer’s computer and executed on the client’s browser and would likely amount to a <i>distribution</i>.  If the JavaScript is licensed under a strong copyleft license such as the GPL, two issues arise.
</div>

<div>
</div>

<div>
  First, JavaScript is often sent to a client’s computer in obfuscated form to protect the original source code. This original, un-obfuscated, source code which would have to be disclosed. Second, such <i>distribution</i> could trigger the requirement to disclose proprietary source code that is considered derivative works of the JavaScript. Depending on how the JavaScript is used, there is a possibility that a large portion of the proprietary source code powering the SaaS offering would be subject to disclosure requirements.
</div>

<div>
</div>

<div>
</div>

<div>
  <strong>3 Use of Software Licensed Under the </strong><strong>GNU Affero Public License</strong>
</div>

<div>
</div>

<div>
  Lastly, clients should be especially wary of using open source software licensed under the GNU Affero Public License (<b>“AGPL”</b>). The AGL was designed to close a loophole in the GPL that permitted many software developers to use open source software licensed under the GPL without disclosing source code to their modifications by using a SaaS model (thus making available the software without technically <em>distributing</em> it). Under the AGPL, if a client permits customers to interact with open source software through a computer network, the source code disclosure obligations are triggered (s. 13, AGPL).
</div>

<div>
  For the above reasons, clients should be cautious not to gloss over their open source software licensing obligations when working with open source software in a SaaS model.
</div>