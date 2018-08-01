---
id: 210
title: Should APIs be copyrightable?
date: 2013-11-10T08:33:48+00:00
author: Sam
layout: post
guid: http://www.samuelip.com/?p=210
permalink: /?p=210
header_choice_select:
  - ""
custom_header_img_id_value:
  - ""
categories:
  - Law
---
This summer, I had been following the [Oracle v. Google](http://www.groklaw.net/pdf3/OraGoogle-1202.pdf) case since last year where Oracle sued Google for infringing on its copyright of over 37 Java APIs (Application Programming Interfaces).  While an American case,  Justice Alsup ruled that the Java APIs were <span style="text-decoration: underline;">not</span> copyrightable.  Justice Alsup stated:

> So long as the specific code used to implement a method is different, anyone is free under the Copyright Act to write his or her own code to carry out exactly the same function or specification of any methods used in the Java API. It does not matter that the declaration or method header lines are identical. Under the rules of Java, they _must be identical_ to declare a method specifying the _same_ functionality — even when the implementation is different. When there is only one way to express an idea or function, then everyone is free to do so and no one can monopolize that expression. And, while the Android method and class names could have been different from the names of their counterparts in Java and still have worked, copyright protection never extends to names or short phrases as a matter of law.

As a former engineer at BlackBerry, this decision sits uneasy with me &#8212; not from a policy perspective, but from an application of law perspective. I&#8217;ll explain why.  The essential aspects of copyright law in this case as follows: (1) Copyright exists at the moment of creation; (2) one can only copyright an expression of idea, but not the idea itself; (3) an exception (&#8220;Merger Doctrine&#8221;) may exist if there is only one way to express an idea, in such a scenario, the creative work is not copyrightable.

Since the Java APIs are undoubtedly an original creative endeavour and an expression of a programmer&#8217;s idea, Justice Alsup is relying on the merger doctrine, and the fact that copyright APIs are too short. But something isn&#8217;t right. Google did not have to rely on the Java APIs to express their idea &#8212; that is, to develop Java platform/applications. They could have used the C language APIs, the C++ Language APIs, Python Language APIs, or any number of other language APIs to do so.

Then, with respect to Justice Alsup&#8217;s remark that copyright protection never extends to short phrases, APIs are a collection of short phrases that work in harmony. There must be consistency of design in order for the APIs to be used intuitively by any software developer. Taken as a whole, the Java API as a collective is not short by any stretch.

Alas, this spring, the Electronic Frontier Foundation submitted an amicus brief to the courts, expressing concern that APIs could be copyrightable. Understandably this will impede innovation. I buy the policy argument; it has merit. But I still maintain the decision was an erroneous application of the law.  To this end, this won&#8217;t be the last post on the matter.