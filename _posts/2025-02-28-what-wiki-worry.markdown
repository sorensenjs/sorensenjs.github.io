---
layout: post
title:  "What, Wiki Worry?"
date:   2025-02-28 17:14:00 +0000
categories: opinion
---

For the past year, after reading in the Wikipedia Signpost newsletter on
[multiple](https://en.wikipedia.org/wiki/Wikipedia:Wikipedia_Signpost/2024-05-16/Special_report)
[occasions](https://en.wikipedia.org/wiki/Wikipedia:Wikipedia_Signpost/2023-08-15/Special_report)
that the number of active Wikipedia Administrators
has been in relentless decline since 2008. I was hoping that the
[final report](https://upload.wikimedia.org/wikipedia/commons/5/5f/%28Final_Report%29_Administrator_recruitment%2C_retention%2C_%26_attrition_%28SDS1.2.2%29.pdf)
from the foundation research effort that began last summer would lay the
foundation for bold action. And, while the report does confirm that
several large Wikipedia projects (i.e. languages) have a problem
recruiting new admins, the recommendations are mostly confined to
areas for additional study.

My feedback will proceed as follows: identifying what I believe is
the most concerning problem from the report's own data, articulating the
potential risks to projects from administrator decline, discussion of
technical tools that could reduce the risks posed by inexperienced and
malicious admins, discussion of training frameworks that could improve
potential administrator supply and streamline the RfA process.

## Pipeline problems

<p align="center">
  <img src="/media/admins.png">
</p>

From the [quantitative analysis](https://gitlab.wikimedia.org/repos/research/admin-recruitment-retention-and-attrition/-/blob/main/admin_tenure.ipynb?ref_type=heads)
on Administrator tenure, it's clear that <em>most</em> of the current
active admins have been doing this job for more than 15 years. On a purely
demographic level, this should be setting off alarm bells. Without a steady
stream of new recruits, this pool of volunteers is almost certainly facing the
potential for a accelerating decline.

As with problems that economists are beginning to discuss regarding falling
fertility and, correspondingly populations, there is good reason to believe that
the decline in administrators could accelerate. One obvious cause would be the
rise in administrative workload required per admin.

The report does not acknowledge the degree that present administrators are
involved in the RfA process, and that, in the absence of a more formal
requirements specification, the set of administrators acts more as a club than a
professional practice.

## Project Capture - Why it Matters

Wikipedia, especially the large English Wikipedia, has a difficult to quantify
role in powering current technological productivity. With large language models
often using the comprehensive and readily shareable content as the factual
training material, it would not be unreasonable to suggest that trillions of
dollars of economic activity depends upon the project. The damage that could be
done by a rogue group of admins working in concert is substantial.

And, this is not a theoretical problem. The [2021 report on the compromise of the
Croatian
Wikipedia](https://en.wikipedia.org/wiki/File:Croatian_WP_Disinformation_Assessment_-_Final_Report_EN.pdf)
demonstrates that the risks are real and poorly quantified. Because there are
substantial economic benefits to Wikipedia manipulation, and the difficulty in
detecting COI edits, especially edits performed using generative models, it
seems important that the administrator pool have explicit targets based upon
expected workloads.

Many wikipedians consider the creation of commons goods to be a movement. And,
if so, the decline in administrators is a warning sign that the movement is faltering.
At a time when so many public institutions, some storied and long lived, are
finding themselves compromised by internal or external forces, it seems unwise
to expect worrisome trends to work themselves out. Just consider the damage done
to a 150 year old organization like the National Rifle Association by
corruption, or the collapse of the Green party in the United States. In both
cases the failures were caused, in part, by people who were ideologically aligned with
the goals of the organization.

In short, if the organization is a movement, and it is not growing then
it's probably
in trouble. Some have argued that, as the project matures and the need for new policy
creation declines, so perhaps the decline in active editors and administrators
is not a concern. This perception - that the project is basically done - is
perhaps even more damaging to recruitment. Being an administrator is a difficult
task, as is amply documented in the report. If there is a loss of enthusiasm for
the ongoing work of Wikipedia, why would people step forward to take this
responsibility. I think the foundation could do a lot more to encourage people
to become contributors - my own back of the envelope estimate is that the
English Wikipedia is 20% complete - but that is a topic that is beyond the scope
of the present discussion.

## Reducing Risks from Bad Admins

The primary reason that the RfA process is arduous and exhausting is because
admins have such powerful control over Wikipedia content and users. Broadly
speaking the administrative controls can be broken down into page actions and
user actions. While it is important that administrators be able to act quickly
to address vandalism or distributed attacks, the most important, and often
controversial actions involve reading complex arguments and resolving disputes.
These types of actions are already subject to the AARV process, and almost all
administrator actions are subject to easy reversal by other administrators.

The problem of distributed administration of large systems is hardly unique to
Wikipedia. There are a lot commercial organizations that administer even more
complex systems (or, sometimes, fail to) that could provide lessons. But I will
just list some relevant ideas:

 + finer grained admin ACLs that can allow people to progressively become admins
 + provisional admin status, subject to automatic review
 + multi-party authorization for admin tasks that are not time sensitive
 + improved monitoring for anomalous administrative activity

Overall, the important point here is that AfD would be less fraught if the power
granted to administrators was lessened. While the topic of improving automation
use to reduce the administrative workload, it more likely than not that cleaning
up the busy work would leave only the most exhausting task: dispute
resolution.

Building up governance infrastructure on the mediawiki platform has always been
a difficult process both socially and technologically. But I would have liked to
see the report on Administrator retention to spend more time on potential
engineering solutions, even if they are speculative.

## Formalizing and Mentoring

Administration on Wikipedia is a <em>job</em>, and the foundation would most
benefit from treating it as such. Jobs have requirements, and for Wikipedia
demonstrating familiarity with the project and foundation's policy framework is
an obvious requirement. At present, candidates have to prove their familiarity
with these policies by citing past on-platform instances where they had
interactions involving them.
This is not the only way to demonstrate knowledge, and developing educational
materials, distinct from the policy documents, to train people in dispute
resolution is entirely possible.

Having read through several RfAs, especially the withdrawn or failed RfAs, one
is struck by the unforgiving regard that admins have for people who have made
mistakes in their past interactions. The general tone is that the candidate is
perhaps not the "right kind of person" for Adminship. In this regard, Wikipedia
seems to be copying many of the biases and shortcomings of the corporate
recruiting system. For an organization founded on open principles, it's more
than a little disappointing that more isn't done to foster candidates through
mentoring.

I think there are lessons to be learned from the <em>readability</em> process
used at Google and documented in the [_Software Engineering at Google_](https://abseil.io/resources/swe-book) book.
This program is a formal mentoring process where new employees are required to
obtain additional code reviews from language domain experts until the
demonstrate mastery of the company's particular policies and practices.

Wikipedia has been slowly rolling out mentorship programs, including featuring
them on the relatively new homepage feature. And, while
[mentioned](https://en.wikipedia.org/wiki/Wikipedia:Mentorship#Voluntary_mentorship)
there does not appear to be a formal Administrator mentoring program.

