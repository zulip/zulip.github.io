# Google Summer of Code 2017

Zulip participated in GSoC 2016 and mentored three students officially
(and 4 more who did their proposed projects unofficially). We do
intend to ask Google Summer of Code to allow us to mentor again in
2017, but we have no guarantees as to whether we'll be accepted or
rejected as an organization (although we have no particular reason to
believe we'll be rejected.) We'll know by 27 February 2017 whether
we'll be mentoring for GSoC 2017.

If you want to apply for GSoC 2017, a great way to get started is to
skim [the official GSoC
resources](https://developers.google.com/open-source/gsoc/resources/)
-- especially [the student
manual](https://developers.google.com/open-source/gsoc/resources/manual).

And keep your eye on [the GSoC
timeline](https://developers.google.com/open-source/gsoc/timeline). The
student application deadline is 3 April 2017.

## About us

[Zulip](https://www.zulip.org) is a powerful, open source group chat
application. The core web app is written in Python and uses the Django
framework. We also make a cross-platform mobile app, an Android app, a
cross-platform desktop app, and many service integrations, all open
source.

Zulip supports both private messaging and group chats via conversation
streams. Zulip also supports fast search, drag-and-drop file uploads,
image previews, group private messages, audible notifications,
missed-message emails, desktop apps, and [much
more](https://www.zulip.org/features.html).

Zulip has gained a considerable amount of traction [since we released
it as open source software in September
2015](https://blogs.dropbox.com/tech/2015/09/open-sourcing-zulip-a-dropbox-hack-week-project/),
and is gaining more users at a rapid pace -- every day, at least tens
of thousands of people use Zulip. Your work on Zulip will have impact
on the daily experiences of a huge number of people.

As an organization, we value high-quality mentorship and making sure our
product quality is extremely high -- you can expect to learn a lot from
disciplined code reviews by highly experienced engineers. Since Zulip is a
group chat product, your GSoC experience with the Zulip project will be
highly interactive, with a real focus on teaching you the concepts and
reasoning behind how Zulip is engineered and how to make it better.

As part of that commitment, Zulip has over 80,000 words of
[documentation for developers](zulip.readthedocs.io/en/latest/).

## Getting started

We have an easy-to-setup development environment, and a library of
tasks that are great for first-time contributors
([guide](https://github.com/zulip/zulip#ways-to-contribute)). Take
a look at [our architectural overview and key
concepts](https://zulip.readthedocs.io/en/latest/architecture-overview.html#usage-assumptions-and-concepts).

Then: use
[our first-time Zulip developer guide](https://zulip.readthedocs.io/en/latest/dev-env-first-time-contributors.html)
to get your Zulip development environment set up. If you have any
trouble, please speak up in
[#GSoC](https://chat.zulip.org/#narrow/stream/GSoC) on
[the Zulip development community server](http://zulip.readthedocs.io/en/latest/chat-zulip-org.html),
(use your name as the topic), or post to
[our GSoC mailing list](https://groups.google.com/forum/#!forum/zulip-gsoc),
and we'll help you out.

Once you've gotten set up, take a look at [our architectural overview
and key
concepts](https://zulip.readthedocs.io/en/latest/architecture-overview.html#usage-assumptions-and-concepts). Then
look through our library of tasks that are great for first-time
contributors
([guide](https://github.com/zulip/zulip#ways-to-contribute)), and
comment on an issue that appeals to you and say "I'm going to work on
this." Then start working on it! If you have any setbacks or you get
stuck, [tell us what you're trying to do and what you've already
tried](https://blogs.akamai.com/2013/10/you-must-try-and-then-you-must-ask.html),
and we'll help you out.

Contributors who are new to open source will likely benefit from
reading
[our Git guide](http://zulip.readthedocs.io/en/latest/git-guide.html),
which has a lot of advice about how to do things like rebase your code.

# Application tips, and how to be a strong candidate

You'll be following [GSoC's application process
instructions](https://developers.google.com/open-source/gsoc/). And
we'll be asking you to make at least one small initial pull request
before the application deadline (3 April 2017), to help us assess you
as a developer.

Getting started earlier is better, so you have more time to learn,
make contributions, and make a good proposal.

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
* A link to the small initial contribution(s) you did.

We expect applicants to either have experience with the technologies
relevant to their project or have strong programming experience.  We
also expect applicants to be excited about learning how to do
disciplined, professional software engineering, where they can
demonstrate through reasoning and automated tests that their code is
correct.

While only one contribution is required to be considered for the
program, we find that the strongest applicants make multiple
contributions throughout the application process, including after the
application deadline.

We are more interested in candidates if we see them submitting good
contributions to Zulip projects, helping other applicants on GitHub
and on our mailing lists and in
[chat.zulip.org](http://zulip.readthedocs.io/en/latest/chat-zulip-org.html),
learning from our suggestions,
[trying to solve their own obstacles and then asking well-formed questions](https://blogs.akamai.com/2013/10/you-must-try-and-then-you-must-ask.html),
and developing and sharing project ideas and project proposals that
are plausible and useful.

Also, you're going to find that people give you links to pages that
answer your questions. Here's how that often works:

1. you [try to solve your problem until you get stuck, including
looking through our code and our documentation, then start formulating
your request for
help](https://blogs.akamai.com/2013/10/you-must-try-and-then-you-must-ask.html)
1. you ask your question
1. someone directs you to a document
1. you go read that document, and try to use it to answer your question
1. you find you are confused about a new thing
1. you ask another question
1. now that you have demonstrated that you have the ability to read,
think, and learn new things, someone has a longer talk with you to
answer your new specific question
1. you and the other person collaborate to improve the document that you
read in step 3 :-)

This helps us make a balance between person-to-person discussion and
documentation that everyone can read, so we save time answering common
questions but also get everyone the personal help they need. This will
help you understand the rhythm of help we provide in the developers'
Zulip livechat -- including why we prefer to give you help in public
mailing lists and Zulip streams, instead of in one-on-one private
messages or email. We prefer to hear from you and respond to you in
public places so more people have a chance to answer the question, and
to see and benefit from the answer. [More about that in this blog
post.](https://www.harihareswara.net/sumana/2016/10/12/0)


## Project ideas

These are the seeds of ideas; it's also fine for you to come up with
your own project ideas.

### Full stack and web frontend focused projects

Code: [github.com/zulip/zulip -- Python, JavaScript, and
CSS](http://github.com/zulip/zulip/)

- Write cool new features for Zulip.  Play around with the software, browse
  [the feature suggestions that other users have
  contributed](https://github.com/zulip/zulip/labels/enhancement), and
  suggest something you’d like to build!

- Optimize performance.  Zulip already performs fairly well once
  the site has been loaded, but there are a bunch of ideas for how to
  make it substantially faster, especially improving the initial load
  time.  We’d like to try a lot of super-new modern technologies like
  using HTTP 2 to send all the assets in parallel with the main page
  HTML.

- Overhaul the Zulip website’s user experience to handle large teams
  well (e.g. currently, the buddy list always has every user in the
  organization, no matter how big!).  This project would likely
  consist of 2–3 individual sub-projects each taking a few weeks to
  implement.

- Build out the administration pages for Zulip to let admins set a
  retention policy for when old messages should be deleted, audit
  data, etc. ...  the sorts of things needed for Zulip to be used at
  more larger organizations.  We get constant requests for these kinds
  of features on the Zulip mailing list.

- Implement analytics so we can see how people use Zulip, see which
  features are valuable, systematically debug performance problems, etc.

 - Frontend analytics visualizations: we store a lot of interesting
   data about user activity, stream activity, etc. The projects will be
   around make fun/useful visualizations of the data for users and realm
   admins.

 - Backend analytics: There is a lot of data in our production tables and
   server logs that would be nice to aggregate (e.g. info about stream/user
   activity, or common server errors).

### Backend focused projects

Code: [github.com/zulip/zulip -- mostly
Python](http://github.com/zulip/zulip/)

- [Write bots and
  integrations](https://zulip.readthedocs.io/en/latest/integration-guide.html)
  -- e.g., a Jabber mirror
  or [Mailman integration](https://github.com/zulip/zulip/issues/959).

- [Make it easy to import data from Slack into
  Zulip](https://github.com/zulip/zulip/issues/908).

- Build meta-integration. Zulip has several dozen native integrations
  (https://chat.zulip.org/integrations/), but Slack has a ton more.  We
  should build a system to make all of Slack’s numerous third-party
  integrations work with Zulip as well, and make Zulip’s integration
  system a lot more slick.

- Improve our Python 3 support. And once that's done, support a much
  wider range of Linux platforms.

- Improve scalability and replication. Currently Zulip has reasonably
  good database scalability but has a few technical changes need to
  make it possible to run a Zulip installation as a scalable
  distributed system.  It should be possible to change this in a
  summer!

- Shrink and speed up our database. We have some plans for how to
  improve the Zulip message storage database schema to be
  substantially more compact with better performance.  Advanced
  postgresql experience desired!

- Build a federation system for users on different Zulip servers to
  exchange messages.

- Write more API client libraries in more languages, or improve the
  ones that already exist (in
  [JavaScript](https://github.com/zulip/zulip-js),
  [PHP](https://packagist.org/packages/mrferos/zulip-php),
  [Haskell](https://hackage.haskell.org/package/hzulip)...

### Mobile projects (mobile experience expected)

Code: [github.com/zulip/zulip-mobile (experimental, cross-platform
React Native mobile app)](https://github.com/zulip/zulip-mobile), and
[github.com/zulip/zulip-android (Android app -- a Gradle project
written in Java)](https://github.com/zulip/zulip-android)

- Improve performance.  Build a better caching system for the
  mobile apps to make the startup process substantially faster.

### Desktop projects

Code: [github.com/zulip/zulip-electron (work-in-progress cross-platform desktop client written in JavaScript on Electron)](https://github.com/zulip/zulip-electron), [github.com/zulip/zulip-desktop (cross-platform desktop client written in C++ with Qt)][https://github.com/zulip/zulip-desktop)

- Make the Zulip user experience great for individuals who are
  members of multiple Zulip teams.

- Improve our experimental [Electron-based desktop client
  application](https://github.com/zulip/zulip-electron) with better
  design, notifications, and cooler desktop integrations.



## Circulating proposals (February-April 2017)

If you're applying to GSoC, we'd like for you to publicly post a few
sections of your proposal -- the project summary, list of
deliverables, and timeline -- someplace public on the Web, such as on
your blog, sometime in February, March, or early April 2017. That way,
the whole developer community -- not just the mentors and
administrators -- have a chance to give you feedback and help you
improve your proposal. This makes it easier for the whole community to
give feedback and help you iterate. And it makes it easier for us to
know who's applying, how many people are applying, and what they're
interested in.

Where should you publish your draft? Google Docs, your blog, Etherpad,
Dropbox Paper, Medium, Dreamwidth, whatever -- any platform that
allows people to look at the text without having to log in or download
a particular app, and that lets you update the draft as you improve
your idea, would be fine. And then please start a new email thread (on
[the Zulip GSoC email
list](https://groups.google.com/forum/#!forum/zulip-gsoc)) with a link
to what you've written, and we'll start giving you feedback!

Rough is fine! A paragraph of project description and a small bulleted
list of deliverables is fine for the first draft of this sort of thing.


## Mentors

We don't yet know who specifically our mentors will be. But you can
reach us via [#GSoC](https://chat.zulip.org/#narrow/stream/GSoC) on
[the Zulip development community server](http://zulip.readthedocs.io/en/latest/chat-zulip-org.html),
(compose a new stream message to with your name as the topic), or
through
[our GSoC mailing list](https://groups.google.com/forum/#!forum/zulip-gsoc),
and we'll help you out.

Hope to hear from you! And thanks for being interested in Zulip. We're
always happy to help volunteers get started contributing to our open
source project, whether or not they go through GSoC.
