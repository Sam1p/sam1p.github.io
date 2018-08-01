---
id: 317
title: APIs are Copyrightable For Now
date: 2014-10-16T06:47:19+00:00
author: Sam
layout: post
guid: http://www.samuelip.com/?p=317
permalink: /?p=317
header_choice_select:
  - ""
custom_header_img_id_value:
  - ""
categories:
  - Law
---
I&#8217;ve posted previously about my views on whether APIs ought to be copyrightable from an Engineer&#8217;s perspective.  The saga continues as Google, on Oct. 6th, petitioned with the US Supreme Court (SCOTUS) for a writ of certiorari to consider, not only whether Java APIs are copyrightable, but also the question of how far-reaching copyright protection extends in software.

To bring readers up to speed:

  * Application Programming Interfaces (APIs) are a set of specifications that define software component inputs, outputs, and operations, allowing software components to communicate. Google used the APIs of Java in their Android operating system, which Oracle asserts copyright to.
  * In August, 2014, Oracle sued Google for copyright infringement, both literal (i.e. copying verbatim of the original expression) and non-literal infringement (i.e. copying the structure, sequence of the Java API package).
  * On May 31, 2014, in a landmark decision,  Judge Alsup of the Northern District of California declared that [APIs are not copyrightable](https://www.eff.org/files/alsup_api_ruling.pdf). His decision could be summarized as follows: &#8220;The method specification [API] is the idea. The method implementation [API Implementation] is the expression. No one may monopolize the idea&#8221;.
  * On May 9, 2014, the Court of Appeals for the Federal Circuit (Circuit Judges: O&#8217;Malley, Plager, and Taranto)  [reversed Judge Alsup&#8217;s decision](http://cdn1.vox-cdn.com/assets/4431835/13-1021.Opinion.5-7-2014.1.pdf), stating that copyrightability presents a &#8220;low bar&#8221; that requires only that a work be original and expressive in the sense that  &#8220;the author had multiple ways to express the underlying idea&#8221;  And since, &#8220;[t]he evidence showed that Oracle had unlimited options as to the selection and arrangement of the 7000 lines Google copied&#8221;, both the API declarations <span style="text-decoration: underline;">and</span> the API package organization is copyrightable.  While a plain reading of 17 U.S.C. § 102(b) excludes &#8220;systems&#8221; and &#8220;methods of operations&#8221; from copyright protection, the CAFC clarified that such provisions of the Copyright Act, &#8220;does not extinguish the protection accorded a particular expression of an idea merely because the expression is embodied in a method of operation&#8221;, but rather, Section 102(b)  &#8220;serves to clarify the &#8216;idea/expression dichotomy&#8217; in that copyright extends only to the idea, not the expression&#8221;.
  * On October 6, 2014, Google filed a petition for a Writ of Certiorari to have the Supreme Court of the United States consider the question.

Google posed the following question to the Supreme Court of the United States:

> Whether copyright protection extends to all elements of an original work of computer software, including a system or method of operation, that an author could have written in more than one way.

The Supreme Court&#8217;s answer will have far reaching implications. For instance, systems and methods of operations are generally considered patentable inventions afforded 20 years of protection. If software systems and methods can be couched under copyright protection rather than under patent intention, such software systems and methods would be afforded protection far beyond 20 years (author&#8217;s life plus 70 years; or for works of corporate authorship, the earlier of (1) 120 years after creation or (2) 95 years after publication).  Obviously this would blur the line between patent and copyright law and cause much confusion.

Moreover, whether APIs are copyrightable has ramifications on innovation and there are a good policy arguments to be considered on both sides of the matter. On one hand, the ability to copyright APIs provides economic incentives for  authors of APIs to create and release better APIs. On the other hand, others argue that it is the inability to copyright APIs that reduce licensing costs and encourage broad adoption, thereby fostering innovation.

It will be interesting to follow this petition&#8217;s developments and to review Oracle&#8217;s response on November 7th.