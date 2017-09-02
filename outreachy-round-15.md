Zulip is a proud participant in [Outreachy](https://www.gnome.org/outreachy/) and
is currently helping new open source contributors apply to be
Outreachy interns for the upcoming December 2017 round. We'll teach you and pay
you to improve Zulip, full-time, between December 5, 2017 and March 5,
2018.

If you're [in a group underrepresented in open source
communities](https://wiki.gnome.org/Outreachy#Eligibility) and you're
interested in contributing to Zulip during a paid apprenticeship,
please apply by the October deadline!

# About us

Zulip is a powerful, open source group chat application. Zulip's key feature
is topic-based threading, which allows for long running, high quality chat
conversations, and makes it possible for distributed teams to communicate
effectively over chat. Zulip is the leading open source competitor to Slack,
by community size and by commit velocity.

As an organization, we value high-quality mentorship and
high-quality product -- you can expect to learn a lot from
disciplined code reviews by highly experienced engineers. Since Zulip is a
group chat product, your Outreachy experience with the Zulip project will be
highly interactive, with a focus on teaching you the concepts and
reasoning behind how Zulip is engineered and how to make it better. All three
of our Outreachy interns from the 2016 cycle are now core contributors to the
Zulip project.

Zulip is written in Python, and uses the Django framework. The web frontend
is mostly in jQuery, the mobile app is written in React Native, and our
desktop apps use Electron.

# Get to know us

We have an [easy-to-setup development environment](http://zulip.readthedocs.io/en/latest/dev-overview.html),
and a [library of tasks](https://github.com/zulip/zulip/issues?q=is%3Aopen+is%3Aissue+label%3A%22bite+size%22)
that are great for first-time contributors.
Also take a look at [our architectural overview and key concepts](https://zulip.readthedocs.io/en/latest/architecture-overview.html#usage-assumptions-and-concepts).

We'd love for you to drop by [our open Zulip livechat at
chat.zulip.org](https://chat.zulip.org/#narrow/stream/Outreachy.202017-2018)
(we use Zulip instead of IRC), and introduce yourself; compose a new
stream message to the 'Outreachy 2017-2018' stream, with your name as
the topic, and a few sentences about your background and interests.

# Application tips, and how to be a strong candidate

Our Outreachy application process opens mid-September and closes
mid-October. [You'll follow the instructions
here](https://wiki.gnome.org/Outreachy#Application_Process).

Your application should include the following:

* Details on any experience you have related to the technologies that
  Zulip has, or related to our product approach.
* Links to materials to help us evaluate your level of experience and
  how you work, such as personal projects of yours, including any
  existing open source or open culture contributions you've made and
  any bug reports you've submitted to open source projects.
* Some notes on what you are hoping to get out of your twelve-week project.
* A short description of the area you'd like to work on, and why you're
  interested in it.
* A link to the initial contribution(s) you did.

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

As the [application process
guide](https://wiki.gnome.org/Outreachy#Application_Process) says:

"While only one contribution is required to be considered for the
program, we find that the strongest applicants make multiple
contributions throughout the application process, including after the
application deadline."

We are more interested in candidates if we see them submitting good
contributions to Zulip projects, helping other applicants on GitHub
and on
[chat.zulip.org](https://chat.zulip.org/#narrow/stream/Outreachy.202017-2018/subject/Welcome),
learning from our suggestions, [trying to solve their own obstacles
and then asking well-formed
questions](https://blogs.akamai.com/2013/10/you-must-try-and-then-you-must-ask.html),
and making good observations about how the product can be improved.

Also, you're going to find that people give you links to pages that
answer your questions. Here's how that often works:

1) you [try to solve your problem until you get stuck, including
looking through our code and our documentation, then start formulating
your request for
help](https://blogs.akamai.com/2013/10/you-must-try-and-then-you-must-ask.html)
2) you ask your question
3) someone directs you to a document
4) you go read that document, and try to use it to answer your question
5) you find you are confused about a new thing
6) you ask another question
7) now that you have demonstrated that you have the ability to read,
think, and learn new things, someone has a longer talk with you to
answer your new specific question
8) you and the other person collaborate to improve the document that you
read in step 3 :-)

This helps us make a balance between person-to-person discussion and
documentation that everyone can read, so we save time answering common
questions but also get everyone the personal help they need. This will
help you understand the rhythm of help we provide in the developers'
Zulip livechat -- including why we prefer to give you help in public
mailing lists and Zulip streams, instead of in one-on-one private
messages or email. We prefer to hear from you and respond to you in
public places so more people have a chance to answer the question, and
to see and benefit from the answer.


# Project ideas

We're interested in a variety of coding and writing projects you could
do with our web app's back end and front end, our mobile or desktop
apps, or other code that integrates with Zulip.

* [Writing bots and
  integrations](https://zulip.readthedocs.io/en/latest/integration-guide.html)
  -- e.g., [a better IRC
  mirror](https://github.com/zulip/zulip/issues/249) or Jabber mirror
  or [Mailman integration](https://github.com/zulip/zulip/issues/959).

* Making it easier to import data from Slack into Zulip.

* Working on engineering for our
  [React Native mobile app](https://github.com/zulip/zulip-mobile) for
  iOS. This is a pressing need for us, since our current iOS app is
  very out of date.

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

* Improving our [Electron-based desktop client
  application](https://github.com/zulip/zulip-electron) with better
  design, notifications, and cooler desktop integrations.

* Writing more development tutorials, and especially
  testing/documenting/expanding the [Zulip API](https://zulipchat.com/api/)
  bindings -- we'd probably want to
  go for an approach that involves auto-generated documentation.

* Writing technical blog posts for the Zulip blog, like [this
  one](http://blog.zulip.org/2016/10/13/static-types-in-python-oh-mypy/).


# Initial contribution ideas

Check out our [bite-sized
bugs](https://github.com/zulip/zulip/labels/bite%20size). If none of
those work for you, drop in on our [open
livechat](https://chat.zulip.org/#narrow/stream/Outreachy.202017-2018)
and compose a new stream message to the 'Outreachy 2017-2018' stream
with your name as the topic, and talk with us about your current
experience -- we'll find something for you.


# Mentors

Our mentors will include Tim Abbott and Rishi Gupta, both of whom work
on maintaining Zulip full time, and both of whom you can ping in [our Zulip
livechat](https://chat.zulip.org/#narrow/stream/Outreachy.202017-2018).

Hope to hear from you!
