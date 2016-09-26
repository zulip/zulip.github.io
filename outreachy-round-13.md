Zulip is a proud participant in [Outreachy](http://outreachy.org/) and
is currently recruiting Outreachy interns for the upcoming Round
13. We'll teach you and pay you to improve Zulip, full-time, between
December 6, 2016 and March 6, 2017.

If you're [in a group underrepresented in open source
communities](https://wiki.gnome.org/Outreachy#Eligibility) and you're
interested in contributing to Zulip during a paid apprenticeship,
please apply by October 17th!

# About us

Zulip is a powerful, open source group chat application. Written in Python
and using the Django framework, Zulip supports both private messaging and
group chats via conversation streams.

Zulip also supports fast search, drag-and-drop file uploads, image
previews, group private messages, audible notifications, missed-message
emails, desktop apps, and [much more](https://www.zulip.org).

Zulip has gained a considerable amount of traction [since we released
it as open source software in September
2015](https://blogs.dropbox.com/tech/2015/09/open-sourcing-zulip-a-dropbox-hack-week-project/),
and is gaining more users at a rapid pace -- every day, at least tens
of thousands of people use Zulip. Your work on Zulip will have impact
on the daily experiences of a huge number of people.

As an organization, we value high-quality mentorship and making sure our
product quality is extremely high -- you can expect to learn a lot from
disciplined code reviews by highly experienced engineers. Since Zulip is a
group chat product, your Outreachy experience with the Zulip project will be
highly interactive, with a real focus on teaching you the concepts and
reasoning behind how Zulip is engineered and how to make it better.

# Get to know us

We have an easy-to-setup development environment, and a library of
tasks that are great for first-time contributors
([guide](https://github.com/zulip/zulip#contributing-to-zulip)). Take
a look at [our architectural overview and key
concepts](https://zulip.readthedocs.io/en/latest/architecture-overview.html#usage-assumptions-and-concepts).

We'd love for you to drop by [our open Zulip livechat at
zulip.tabbott.net](https://zulip.tabbott.net/#narrow/stream/Outreachy.202016-2017/topic/Welcome)
(we use Zulip instead of IRC) or our [Outreachy round 13 mailing
list](https://groups.google.com/forum/#!forum/zulip-outreachy-round-13). Please
talk with us about [our
roadmap](https://zulip.readthedocs.io/en/latest/roadmap.html) or your
questions, and consider applying for an Outreachy internship with us!

# Application tips

Our Outreachy application process opens September 12 and closes
October 17. [You'll follow the instructions
here.](https://wiki.gnome.org/Outreachy#Application_Process) Applying
earlier is better so we have time to give you suggestions for
revision.

Your application should include the following:

* Details on any experience you have related to the technologies that
  Zulip has, or related to our product approach.
* Links to materials to help us evaluate your level of experience and
  how you work, such as personal projects of yours, including any
  existing open source or open culture contributions you've made and
  any bug reports you've submitted to open source projects.
* Some notes on what you are hoping to get out of your twelve-week project.
* A description of the project you'd like to do, and why you're excited about it.
* Some notes on why you're excited about working on Zulip.
* A link to the small initial contribution you did.

If you're applying for a coding internship: We expect applicants to
either have experience with the technologies relevant to their project
or have strong programming experience.  We also expect applicants to
be excited about learning how to do disciplined, professional software
engineering, where they can demonstrate through reasoning and
automated tests that their code is correct.

If you're applying for a writing internship: We expect applicants to
be skilled in writing in English for a non-academic audience, and to
be interested in getting feedback that will help them write accurately
and accessibly about technology.

We'll be asking for you to publicly post a few sections of your
proposal -- the project summary, list of deliverables, and timeline --
someplace public on the Web, such as on your blog, or in a public
document on a platform like
[EtherPad](https://public.etherpad-mozilla.org/) or
[Hackpad](https://hackpad.com) or [Dropbox
Paper](https://www.dropbox.com)). That way, the whole developer
community -- not just the mentors and administrators -- have a chance
to give you feedback and help you improve your proposal.

# Project ideas

We're interested in a variety of coding and writing projects you could
do with our web app's back end and front end, our mobile or desktop
apps, or other code that integrates with Zulip.

* [Writing bots and
  integrations](https://zulip.readthedocs.io/en/latest/integration-guide.html)
  -- e.g., [a better IRC
  mirror](https://github.com/zulip/zulip/issues/249) or Jabber mirror
  or [Mailman integration](https://github.com/zulip/zulip/issues/959).

* [Making it easy to import data from Slack into
  Zulip](https://github.com/zulip/zulip/issues/908).

* Working on engineering for our
  [React Native mobile app](https://github.com/zulip/zulip-mobile) for
  iOS. This is a pressing need for us, since our current iOS app is
  very out of date.  A lot of the UX ideas for Android below also
  apply to the React Native iOS app, in addition to just getting the
  app to feature parity.

* Improving the user experience and design of our [Java Android
  app](https://github.com/zulip/zulip-android), which [we've been
  steadily
  improving](https://groups.google.com/forum/#!topic/zulip-announce/xZ9i9PeDhJ8)
  and which is much further along than the iOS app.  Here's some more concrete ideas:

 - Setting up repeatable Android builds for CI and production releases, that reliably run both Espresso and Unit tests

 - Adding photo uploads and cropping

 - Adding file attachment uploads

 - Implementing a "share to Zulip" functionality to share content from other apps to Zulip

 - Fancier in app notifications

 - Fancy up the homescreen widget

* Improving and redesigning Zulip's UI/UX. These will include:
  - [zulip.org](https://zulip.org/)
  - Zulip's web app

* Merging some of our Django extensions into upstream -- Zulip has
  several cool extensions and/or monkey-patchings we do to improve the
  Django web framework for our users, and several of these would make
  sense to attempt to contribute to upstream Django (or at least make
  into reusable Django extension(s)). These include:

 - Zulip's cool request parsing library (`zerver/lib/request.py`)
 - `JsonableError` exception middleware
 - Time-tracking of database and memcached profiling data and
   including in logs, and adding support for doing the same with time
   spent rendering templates (may be worth looking at
   https://github.com/dropbox/stopwatch as a potential replacement)
 - Zulip’s caching extensions (`zerver/lib/cache*.py`)

* [Writing more development
  tutorials](https://github.com/zulip/zulip/pull/676), and especially
  testing/documenting/expanding the [Zulip
  API](https://zulipchat.com/api/) bindings -- we'd probably want to
  go for an approach that involves auto-generated documentation
  (etc.).

* Implementing analytics so we can see: how are messages distributed
  across users? what happens when you analyze the social graph of who
  talks to and mentions whom, and how interconnected are people and
  groups across streams?

 - Frontend analytics visualizations: we store a lot of interesting
   data about user activity, stream activity, etc. The task would be
   to make fun/useful visualizations of the data for users and realm
   admins.

 - Backend analytics: There is a lot of data in our production tables
   and server logs that would be nice to aggregate (e.g. common errors
   that give out response code 500).

* Improving our experimental [Electron-based desktop client
  application](https://github.com/zulip/zulip-electron) with better
  design, notifications, and cooler desktop integrations.


# Initial contribution ideas

Check out our [bite-sized
bugs](https://github.com/zulip/zulip/labels/bite%20size). If none of
those work for you, drop in on our [open
livechat](https://zulip.tabbott.net/#narrow/stream/Outreachy.202016-2017/topic/Welcome)
in the `Welcome` topic within the `Outreachy 2016-2017` stream, and
talk with us about what your skills are -- we'll find something for
you.

As you work towards an initial contribution, it might help you to
check out [these tips for new open source
contributors](https://zulip.tabbott.net/#narrow/stream/Outreachy.202016-2017/topic/Tips.20for.20new.20open.20source.20contributors),
on how to learn faster and communicate respectfully in open source
communities.

# Mentors

Our mentors will include Tim Abbott and Rishi Gupta, both of whom work
on maintaining Zulip, and both of whom read the [mailing
list](https://groups.google.com/forum/#!forum/zulip-outreachy-round-13)
and whom you can ping in [our Zulip
livechat](https://zulip.tabbott.net/#narrow/stream/Outreachy.202016-2017/topic/Welcome).

Hope to hear from you!
