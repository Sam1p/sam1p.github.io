---
id: 413
title: GNU Affero General Public License 3.0 (AGPL)
date: 2015-09-10T00:30:26+00:00
author: Sam
layout: post
guid: http://www.samuelip.com/?p=413
permalink: /?p=413
header_choice_select:
  - ""
custom_header_img_id_value:
  - ""
categories:
  - Uncategorized
---
Not to be confused with another license called the Affero General Public License published by the now-defunct Affero organization, the GNU Affero Public License (AGPLv3) was designed to close a loophole in GPL where one could use GPL licensed software available without ever disclosing source code to their modifications by deploying their software as a service and thus, avoiding a technical &#8220;distribution&#8221;.

The AGPLv3 is identical to GPLv3, with the exception that source code for modifications must be disclosed if AGPLv3 licensed software is used in a software-as-a-service model. Section 13 of AGPLv3 states:

> Notwithstanding any other provision of this License, if you modify the Program, your modified version must prominently offer all users interacting with it remotely through a computer network (if your version supports such interaction) an opportunity to receive the Corresponding Source of your version by providing access to the Corresponding Source form a network server at no charge, through some standard or customary means

The Free Software Foundation has clarified in their FAQ that, &#8220;[i]f the program is expressly designed to accept user requests and send responses over a network, then it meets the criteria&#8221;, of, &#8220;interacting with [the software] remotely through a computer network&#8221;.  Examples include web and mail servers, interactive web-based applications, and servers for games played online.  It is interesting to note that the &#8220;user&#8221; in this case, could very well be a computer program.

Along a very reasonable line of thought, the Free Software Foundation further clarifies that, &#8220;[if] a program is not expressly designed to interact with a user through a network, but is being run in an environment where it happens to do so, then it does not fall into this category. For example, an application is not required to provide source merely because the user is running it over SSH, or a remote X session.&#8221;

What about client-server architectures where the client is licensed under AGPLv3?  The Free Software Foundation clarifies that Section 13 of AGPLv3 would not be triggered, as it would not be reasonable to argue that the &#8220;server operation is a &#8216;user&#8217; interacting with the client in any meaningful sense&#8230;the server can make absolutely no assumptions about what the client will do &#8212; so there&#8217;s no meaningful way for the server operator to be considered a user of that software.&#8221;

In the marketplace, there have been [articles](http://www.theregister.co.uk/2011/03/31/google_on_open_source_licenses/) stating that Google bans use of software licensed under AGPLv3.  As an offeror of cloud solutions, this policy seems to make good business sense.  Misuse of open source software could trigger disclosure obligations of otherwise proprietary code.

On the other end of the spectrum, some companies have embraced AGPLv3 as part of a dual-licensing strategy.  For instance, a company might desire to release their source code as AGPLv3 to the public.  Users that want to make modifications, but do not want to disclose their proprietary source code, would then be required to pay for a commercial license to the software.

While AGPLv3 is ranked at 16 of the Top 20 Open Source Licenses used in open source projects by [Black Duck Software](https://www.blackducksoftware.com/resources/data/top-20-open-source-licenses), use of AGPLv3 is expected to grow steadily.