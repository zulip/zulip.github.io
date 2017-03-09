# Google Summer of Code 2017

Zulip [is a mentoring organization in GSoC 2017](https://summerofcode.withgoogle.com/organizations/6508216277008384/).

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
[documentation for developers](https://zulip.readthedocs.io/en/latest/).

Zulip participated in GSoC 2016 and mentored three students officially
(and 4 more who did their proposed projects unofficially). We've also
mentored three Outreachy interns and dozens of Google Code-In participants.

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
comment on an issue that appeals to you with a comment like "I'm going to work on
this." Then start working on it! If you have any setbacks or you get
stuck, [tell us what you're trying to do and what you've already
tried](https://blogs.akamai.com/2013/10/you-must-try-and-then-you-must-ask.html),
and we'll help you out.

Contributors who are new to open source will likely benefit from
reading
[the Zulip guide to Git](http://zulip.readthedocs.io/en/latest/git-guide.html),
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

## Mentors

We have more than a dozen Zulip contributors who are interested in
mentoring projects.  We usually decide which contributors are
mentoring which projects based in part on who is a good fit for the
needs of each student as well as technical expertise.  You can reach
us via [#GSoC](https://chat.zulip.org/#narrow/stream/GSoC) on
[the Zulip development community server](http://zulip.readthedocs.io/en/latest/chat-zulip-org.html),
(compose a new stream message with your name as the topic), or
through
[our GSoC mailing list](https://groups.google.com/forum/#!forum/zulip-gsoc),
and we'll help you out.

Zulip operates under group mentorship.  That means you can contact
anyone, not just the person assigned to you, for assistance.  Our
preferred approach is to just post in a public stream on
chat.zulip.org and someone will help you.  We list the Zulip
contributors who are experts for various projects by name below; they
will likely be able to provide you with the best feedback on your
proposal.

However, the first and most important thing to do for building a
strong application is to show your skills by contributing to a large
open source project like Zulip, to show that you can work effectively
in a large codebase (it doesn't matter what part of Zulip, and we're
happy to consider work in other open source projects).  The quality of
your best work is more important to us than the quantity; so be sure
to test your work before submitting it for review and follow our
coding guidelines (and don't worry if you make mistakes in your first
few contributions!  Everyone makes mistakes getting started).

Once you have several PRs merged (or at least one significant PR
merged), you should start discussing with the Zulip development
community the project you'd like to do, and developing a specific
project plan.  We recommend discussing what you're thinking in public
streams on chat.zulip.org, so it's easy to get quick feedback from
whoever is online.

## Project ideas

These are the seeds of ideas; you will need to do research on the
Zulip codebase, read issues on GitHub, and talk with developers to put
together a complete project proposal.  It's also fine for you to come
up with your own project ideas.  As you'll see below, you can put
together a great project around one of the
[area labels](https://github.com/zulip/zulip/labels) on GitHub; each
has a cluster of problems in one part of the Zulip project that we'd
love to improve.

We don't believe in labeling projects by difficulty (e.g. a project
that involves writing a lot of documentation will be hard for some
great programmers, and a UI design project might be hard for a great
backend programmer, while a great writer might have trouble doing
performance work).  To help you find a great project, we list the
skills needed, and try to emphasize where strong skills with
particular tools are likely to be important for a given project.

For all of our projects, an important skill to develop is a good command
of Git; read
[our Git Guide](https://zulip.readthedocs.io/en/latest/git-guide.html) to
learn how to use it well.

### Full stack and web frontend focused projects

Code: [github.com/zulip/zulip -- Python, Django, JavaScript, and
CSS](http://github.com/zulip/zulip/).

- Make Zulip integrations easier for nontechnical users to
  setup.  This includes adding a backend permissions system for
  managing bot permissions (and actually implementing the enforcement
  logic), adding an Oauth system for presenting those controls to
  users, as well as making the /integrations page UI have buttons to
  create a bot, rather than sending users to the administration page.
  **Skills recommended**: Strong Python/Django; JavaScript, CSS, and
  design sense helpful.  Understanding of implementing Oauth
  providers, e.g. having built a prototype with
  [the Django Oauth toolkit](https://django-oauth-toolkit.readthedocs.io/en/latest/)
  would be great to demonstrate as part of an application.  The
  [Zulip integration writing guide](http://zulip.readthedocs.io/en/latest/integration-guide.html)
  and
  [integration documentation](https://chat.zulip.org/integrations/)
  are useful materials for learning about how things currently work,
  and
  [the integrations label on GitHub](https://chat.zulip.org/integrations/)
  has a bunch of good starter issues to demonstrate your skills if
  you're interested in this area.  Expert: Tomasz Kolek.

- Build a meta-integration that converts the Slack incoming webhook
  API to post messages into Zulip. Zulip has several dozen native
  integrations (https://chat.zulip.org/integrations/), but Slack has a
  ton more.  We should build an interface to make all of Slack’s
  numerous third-party integrations work with Zulip as well, by
  basically building a Zulip incoming webhook interface that accepts
  the Slack API (if you just put in a Zulip server URL as your "Slack
  server").  **Skills required**: Strong Python experience; experience
  with the Slack API a plus.  Work should include documenting the
  system and advertising it.  Expert: Tomasz Kolek.

- Visual design work on Zulip's logged-out pages, including /help,
  /apps, /integrations, /api, /login, /register, the zulip.org
  website, etc.  We'd love to make these look nicer both through
  polish and potentially through adding fun illustrations to make the product
  more friendly.  A project could include work on Zulip's logged-in UI
  as well.  **Skills required**: Design, HTML and CSS skills;
  JavaScript and illustration experience are helpful.  A great
  application would come with mockups for specific changes, and/or a
  set of PRs making small improvements to the logged-out UI.  Expert:
  Brock Whittaker.

* Make Zulip's user-facing documentation more awesome.  Zulip now has
  a [lot of documentation](https://chat.zulip.org/help/) for users
  (largely written by Google Code-In students!) on how to use the
  various product features, and what features exist, but it could use
  a lot of work on organization, polish, and otherwise making it feel
  nice.  The largest part of this, though, would be writing guides for
  new users on how to setup Zulip effectively.  One could start with the
  [open user documentation issues](https://github.com/zulip/zulip/labels/area%3A%20documentation%20%28user%29).
  **Skills required**: Strong English writing skills, empathy for
  users, appreciation for the Zulip user experience.  Minimal coding
  experience required.  Expert: Cynthia Lin.

- Build support for outgoing webhooks and slash commands into Zulip to
  improve its chat-ops capabilities.  There's an existing
  [pull request](https://github.com/zulip/zulip/pull/1393) with a lot
  of work on the outgoing webhooks piece of this feature that would
  need to be cleaned up and finished, and then we need to build support for slash
  commands, some example integrations, and a full set of
  documentation and tests.  Recommended reading includes Slack's
  documentation for these features, the Zulip message sending code
  path, and the linked pull request. **Skills required**: Strong
  Python/Django skills.  Expert: Tim Abbott

- Build a system for managing Zulip bots entirely on the web.
  Right now, there's a somewhat cumbersome process where you download
  the API bindings, create a bot with an API key, put it in
  configuration files, etc.  We'd like to move to a model where a bot
  could easily progress from being a quick prototype to being a third-party extension to
  being built into Zulip.  And then for built-in bots, one should be able to click a few
  buttons of configuration on the web to set them up and include them in
  your organization.  We've developed a number of example bots
  at `contrib_bots/` in the main Zulip repository that can be used for
  testing; the design document for the deployment part of this vision
  (likely part 1) is
  [here](http://zulip.readthedocs.io/en/latest/custom-apps.html).
  **Skills recommended**: Python and JavaScript/CSS, plus devops
  skills (Linux deployment, Docker, puppet etc.) are all useful here.
  Experience writing tools using various popular APIs is helpful for
  being able to make good choices.  Experts: Steve Howell, Alicja
  Raszkowska.

- Redesign the Zulip settings and administration pages to be more
  consistent, performant, and prettier, with nice reusable UI
  components.  Right now, each widget has its own look and feel,
  there's too many colorful buttons, and some widgets (like the list
  of all users) can cause loading the admin UI to hang for a few
  seconds in a realm with thousands of users.  You can get a great
  sense of what needs to be done by just browsing the administration
  site in a development environment.  You can get experience working
  on the subsystem by working on some of
  [our open settings/admin issues](https://github.com/zulip/zulip/labels/area%3A%20admin).
  **Skills recommended**: JavaScript, HTML, CSS, and an eye for visual
  design.  Experience using the Timeline tab in the Chrome developer
  tools is useful if you want to focus on the performance side of
  things.  The performance issues are primarily on the frontend, so
  Python/Django experience is less important, but still useful.
  Expert: Brock Whittaker.

- Optimize frontend performance.  Zulip already performs fairly well
  once the site has been loaded, but there are a bunch of ideas for
  how to make it substantially faster.  This is likely a particularly
  challenging project to do well, since there are a lot of subtle
  interactions to understand.  **Skill recommeded**: Strong debugging,
  communication, and code reading skills are most important here.
  JavaScript experience; some Python/Django experience, some skill
  with CSS, ideally experience using the Chrome Timeline profiling
  tools (but you can pick this up as you go).  Expert: Brock
  Whittaker.

- Build out the administration pages for Zulip to let admins set a
  retention policy for when old messages should be deleted, audit
  data, etc. ...  the sorts of things needed for Zulip to be used at
  larger organizations.  We get constant requests for these kinds
  of features from Zulip users.  The Zulip bug tracker has
  [almost 50 open issues](https://github.com/zulip/zulip/labels/area%3A%20settings%20%28admin%2Forg%29)
  in the space of improving the Zulip administrative UI.  Many are
  little bite-size fixes in those pages, which are great for getting a
  feel for things, but a solid project here would be implementing 5-10
  of the major missing features.  The first part of this project will
  be refactoring the admin UI interfaces to require writing less
  semi-duplicate code for each feature. **Skills recommended**: A
  good mix of Python/Django and HTML/CSS/JavaScript skill is ideal.
  The system for adding new features is
  [well documented](http://zulip.readthedocs.io/en/latest/new-feature-tutorial.html).
  Expert: Tim Abbott.

- Rebuild the Zulip web UI using a modern reactive layer like vue.js.
Strategically, we'd start with self-contained, messy pieces (like the
presence layer), then move on to more complex pieces (like the
subscriptions page), and finally attach the main UI.  Definitely worth
reading the vue.js documentation and reading
[how Zulip's real-time sync works](http://zulip.readthedocs.io/en/latest/events-system.html).
**Skills recommended**: Strong JavaScript experience, good
communication skills and an eye for detail.  We think this would be an
awesome project, but rewrite projects often introduce lots of bugs, so
we're interested in particularly careful candidates who have the
discipline to redo a small component at a time and carefully test for
regressions.  Good ways to demonstrate qualification for this are
finding and reporting bugs using
[Zulip's manual UI testing guide](http://zulip.readthedocs.io/en/latest/manual-testing.html)
and doing
[refactoring projects](https://github.com/zulip/zulip/labels/area%3A%20refactoring).
Expert: Tommy Ip, Brock Whittaker, Tim Abbott.

- Making Zulip's emoji experience amazing.  The most important piece
  here is making Zulip's emoji and emoji reactions pickers really nice
  and easy to use, like Slack's or Facebook's; we'd also like to build
  a system for doing smart autocomplete, and sort the emoji that an
  individual and their organization use the most at the top.  There are
  about
  [15 open issues](https://github.com/zulip/zulip/labels/area%3A%20emoji)
  that you can use to fill out a project.  Emoji is one of those
  things that is heavy on the details; so this is a project that
  is about polishing something really well. It may still be on the
  small side; you may want to look at other
  [compose improvements](https://github.com/zulip/zulip/labels/area%3A%20compose)
  as well.  Our
  [emoji docs](http://zulip.readthedocs.io/en/latest/emoji.html) are
  essential reading.  **Skills required**: A balance of Python,
  JavaScript and CSS.  Expert: Rishi Gupta.

- Work on making [Snipe](https://github.com/kcr/snipe), written in
  Python 3, or [Barnowl](https://github.com/barnowl/barnowl), written
  in Perl (on top of C), a really good terminal-based client for
  Zulip.  In both cases there is a basic working implementation, and
  the goal of this project would be to build that implementation out
  to be full-featured, well-documented, and something people are
  excited to use.  **Skills required**: Python 3 (asyncio) or Perl
  development skills, good communication and project management
  skills, good at reading code.  Experts: Karl Ramm (Snipe) or Alex
  Dehnert (Barnowl), but chat with Tim Abbott first if you're
  interested in this project.

- Improvements to Zulip's markdown processor.  Ideas include LaTeX
  support,
  [fixing open issues](https://github.com/zulip/zulip/labels/area%3A%20markdown),
  and adding other useful extensions.  The compose issues are also
  useful; read
  [our markdown docs](http://zulip.readthedocs.io/en/latest/markdown.html)
  to learn how this works.  Expert: Tim Abbott.

- Overhaul the Zulip website’s user experience to handle large
  organizations well (e.g. currently, the buddy list always has every
  user in the organization, no matter how big!).  While Zulip performs
  similarly to Slack on this front, with a good summer's work, it
  should be possible to make Zulip clearly the world's best group chat
  software for large teams.  This project would likely consist of
  several individual sub-projects each taking a few weeks to
  implement, starting with the buddy list, and proceeding with work on
  presence, autocomplete/typeahead optimization, and the "subscribers"
  lists in the stream management UI.  **Skills recommended**:
  JavaScript, Python.  Experts: Tim Abbott, Brock Whittaker.

- Implement analytics so we can see how people use Zulip, see which
  features are valuable, systematically debug performance problems,
  etc.  Check out https://chat.zulip.org/stats to see what we've
  implemented so far, and read
  [our analytics doc](http://zulip.readthedocs.io/en/latest/analytics.html)
  to understand how the system works.  **Skills required**: Good
  Django experience, some JavaScript/CSS experience.  Expert: Rishi
  Gupta.

 - Frontend analytics visualizations: we store a lot of interesting
   data about user activity, stream activity, etc. The projects will be
   around make fun/useful visualizations of the data for users, realm
   admins, and sys admins.

 - Backend analytics: There is a lot of data in our production tables and
   server logs that needs to be aggregated (e.g. info about stream/user
   activity, performance data for how fast narrowing is, etc.).

- [Make it easy to import data from Slack into Zulip](https://github.com/zulip/zulip/issues/908).
  There's a few layers to this; importing channels and users, making
  it easy for an administrator to bulk-invite users from an old Slack
  instance, and then importing the message content.  Zulip has a
  well-designed import/export tool (`./manage.py export`; `./manage.py
  import`) so the Zulip-side infrastructure is already present.  A
  full solution would involve building a full web experience, where
  one can entirely over the web create a new Zulip organization
  populated with the data from a Slack instance.  A good project would
  have a full import working partway through the summer so that
  there's plenty of time to fix issues.  **Skills required**: Strong
  Python skills; JavaScript/CSS helpful.  Experts: Tomasz Kolek, Steve
  Howell, Tim Abbott (depending on piece).

- Write cool new features for Zulip.  Play around with the software, browse
  [the feature suggestions that other users have
  contributed](https://github.com/zulip/zulip/labels/enhancement), and
  suggest something you’d like to build!  A great project can combine
  3-5 significant features.  Experts: Lots, depending on feature!

- Work on Zulip's development and testing infrastructure.  Zulip is a
  project that takes great pride in building great tools for
  development, but there's always more to do to make the experience
  delightful.  Significantly, a full 10% of Zulip's open issues are ideas
  for how to improve the project, and are
  [in](https://github.com/zulip/zulip/labels/area%3A%20tooling])
  [these](https://github.com/zulip/zulip/labels/area%3A%20testing-coverage)
  [four](https://github.com/zulip/zulip/labels/area%3A%20testing-infrastructure)
  [labels](https://github.com/zulip/zulip/labels/area%3A%20provision)
  for tooling improvements.

  This is a somewhat unusual project, in that it would likely consist
  of dozens of small improvements to the overall codebase, but this
  sort of work has a huge impact on the experience of other Zulip
  developers and thus the community as a whole (project leader Tim
  Abbott spends more time on the development experience than probably
  anything else).

  A possible specific larger project in this space is working on
  adding [mypy](http://zulip.readthedocs.io/en/latest/mypy.html) stubs
  for Django in mypy to make our type checking more powerful.  Read
  [our mypy blog post](http://blog.zulip.org/2016/10/13/static-types-in-python-oh-mypy/)
  for details on how mypy works and is integrated into zulip.  This
  specific project is ideal for a strong contributor interested in
  type systems.

  **Skills required**: Python, some DevOps, and a passion for checking
  your work carefully.  A strong applicant for this will have
  completed several projects in these areas.

  Experts: Tim Abbott (provision, testing), Steve Howell (tooling, testing).

- Finish Zulip's Python 3 migration.  This would have huge impact, as
  currently we can't really take advantage of Python 3 features.  The
  first month or so of the project would be carefully testing Zulip's
  Python 3 support in production and adjusting our production
  installer to ensure Python 3 is installed; the rest would be doing
  refactoring on the codebase to take advantage of Python 3.  **Skills
  required**: Strong Python skills.  Expert: Umair Waheed Khan.

- Improve scalability and replication support to make Zulip more of a
  distributed system. Currently Zulip has reasonably good database
  scalability but has a few technical changes needed to make it possible
  to run a Zulip installation with ultra-high availability.  It should
  be possible to change this in a summer!  There's lots of great
  reading in the
  [Zulip production](http://zulip.readthedocs.io/en/latest/prod-maintain-secure-upgrade.html)
  documentation,
  [architecture overview](http://zulip.readthedocs.io/en/latest/architecture-overview.html)
  and pages linked to from there.  **Skills required**: Python and
  strong DevOps/infrastructure experience; puppet skills are helpful.
  Expert: Tim Abbott.

- Add good support and documentation for using Zulip in Docker, both
  for development and in production, so that we can recommend it as a
  preferred way to use Zulip.  You should review all the materials linked
  [here](http://zulip.readthedocs.io/en/latest/dev-setup-non-vagrant.html#using-docker-experimental).
  Or relatedly, create tooling to
  maintain a "one-click" installer for Zulip (e.g. AWS or Digital Ocean
  image) to make it super easy to get started with Zulip.  **Skills
  required**: Docker and/or experience running and administering Linux
  servers.  Knowing Puppet is very helpful; some Python and shell is
  useful too.  The references in the last section are all useful; also
  check out the existing Docker development environment and pull
  request for Docker in production.  Experts: Tim Abbott.

- Build a federation system for users on different Zulip servers to
  exchange messages.  See
  [the issue on matrix.org integration](https://github.com/zulip/zulip/issues/356)
  for a lot of details on what's involved; the project would likely be
  jointly mentored with matrix.org.  Expert: Tim Abbott

- Write more API client libraries in more languages, or improve the
  ones that already exist (in python in `api/` in the Zulip server
  repo, as well as [JavaScript](https://github.com/zulip/zulip-js),
  [PHP](https://packagist.org/packages/mrferos/zulip-php), and
  [Haskell](https://hackage.haskell.org/package/hzulip)).  To make this
  a successful project, it would likely also include overhauling
  Zulip's API documentation to have a nice markdown syntax for
  writing docs and fully documenting all the endpoints.  **Skills
  required**: Experience with the target language and API design.
  Expert: Depends on language :).

- Develop [**@zulipbot**](https://github.com/zulip/zulipbot), the GitHub
workflow bot for the Zulip organization and its repositories. By utilizing the
[GitHub API](https://developer.github.com/v3/),
[**@zulipbot**](https://github.com/zulipbot) improves the experience of Zulip
contributors by managing the issues and pull requests in the Zulip repositories,
such as assigning issues to contributors and appropriately labeling issues with
their current status to help contributors gain a better understanding of which
issues are being worked on. Since the project is in its early stages of
development, there are a variety of possible tasks that can be done, including
adding new features, writing unit tests and creating a testing framework, and
writing documentation. **Skills required**: Node.js, ECMAScript 6, and API
experience. Expert: Cynthia Lin, Joshua Pan.

### React Native iOS app

Code:
[React Native mobile app](https://github.com/zulip/zulip-mobile).
Experts: Neeraj Wahi, Boris Yankov.

The highest priority for the Zulip project overall is improving the
Zulip React Native mobile app.

- Work on issues and polish for the app.  You can see the open issues
  [here](https://github.com/zulip/zulip-mobile/issues), grouped into
  milestones by how pressing they are.  There are several dozen open
  issues across the project, and likely many more problems that nobody
  has found yet; in the short term, it needs polish, bug
  finding/squashing, and debugging.  So browse the open issues, play
  with the app, and get involved!  This is still a relatively
  early-stage project, so in a lot of ways a project is "help build
  the Zulip React Native app".  Goals include parity with the webapp
  (in terms of what you can do), parity with Slack (in terms of the
  visuals), world-class scrolling and narrowing performance, and a
  great codebase.
- A key part of the vision for the app is building a really nice way
  to skim unread conversations, decide which to read, and be able to
  exit (and mark as unread again) ones that you want to process on
  the desktop really quickly.  Building and polishing this experience
  would probably be only half a project on its own, but one could add to it.
- Make the React Native app work well and look like it has a native UI
  experience on Android.  Since React Native is designed for
  cross-platform apps, this would be less writing a ton of code and
  more polishing to make the Android-specific stuff work well (push
  notifications, back button support, etc.).

A good project proposal here will bundle together a few focus
areas that you want to make really great (e.g. the message composing,
editing, and reacting experience), that you can work on over the summer.

**Skills required**: Strong JavaScript experience, specifically React
  experience is awesome for this.  iOS or Android development/design
  experience is useful as well.  Experience with React Native
  development required, but you're unlikely to know it in advance; you
  can learn it if you're motivated!  There's tons of good online
  tutorials, courses, etc.

We don't have a lot of specific projects listed here, since we aren't
expecting to have many strong applicants
who can program React Native.  We'd love to have multiple students
working on this area if possible; we will extend this list if there is
significant interest (and see the Android list for a bunch of possible
features).

You don't need an iOS device to work on this, since one can do React
Native development using the Android development environment.

### Android projects

Code:
[Android app written in Java](https://github.com/zulip/zulip-android).  Experts: Lisa Neigut, Kunal Gupta, Saumya Bhatnagar.


- Good multi-account support; see the Electron app description for
  details on what this means, since it's basically the same idea for
  Android.  This is probably the most complex project idea, since it
  will likely require a lot of changes to how the database works, but
  it'd have a big impact on how nice Zulip is for larger organizations.
- Giving the app a really nice onboarding experience.  Right now, we
  don't teach users how to use the app, logging in can involve typing
  your password on a phone in the absence of Google auth for the
  Zulip server, and we don't have any cute illustrations to make the
  app feel especially friendly.
- Adding features to give the app parity with the webapp in terms of
  what you can do, e.g. settings management, subscriptions management,
  pinning streams, emoji reactions, etc.
- Building an advanced search UI to make it easy to construct complex
  searches on a phone using all the Zulip search operators.
- Combining together a bunch of polish issues in the Zulip Android app
  project; there's a lot that could be a little bit nicer (typeaheads,
  etc.).
- Optimize the loading messages performance. The Zulip android app
  already performs fairly well once the messages has been loaded, but
  it takes a bit of time to load the messages on app startup. Improve
  the performance so that for loading messages, it doesn't take much
  time; this would require both profiling (for Java perf issues) and
  adjusting the strategy for how messages are loaded from the server.
- Display messages even when the app is in offline mode. The Zulip
  android app do not display the old stored messages when the
  application is started in offline mode. Caching old messages would
  be to use a long-lived event queue with the server, which could
  allow to cache thousands of messages of history (and maintain it
  over time through other users editing messages).

A good project will likely combine several of these feature ideas.

**Skills required**: Experience with Android development.


### Electron Desktop projects

Code:
[cross-platform desktop app written in JavaScript on Electron](https://github.com/zulip/zulip-electron).
Expert: Akash Nimare

- Make the Zulip user experience great for individuals who are members
of multiple Zulip teams.  Currently, the Zulip desktop apps are a
great experience if you are using just one Zulip server, but many
users, especially those in the Zulip development community, use
multiple Zulip servers.  We need to build a nice set of options for
how users can manage being logged into multiple Zulip organizations.
There are 2 models: multiple running copies of the app (with different
icons in alt-tab for each organization), and a single window that
shows unread counts for multiple Zulip organizations.  We recommend
first learning Electron, if you don't know it yet, and then
contributing to a few minor issues.  The Electron desktop app is only
about 2000 lines of JavaScript code, so reading the entire codebase to
understand how it works is doable.

- Improve our experimental
  [Electron-based desktop client application](https://github.com/zulip/zulip-electron)
  with better design, notifications, and cooler desktop integrations.
  There's a few dozen open issues across the project, and likely many
  more problems that nobody has found yet; mostly it needs polish and
  cross-platform issue debugging.  So browse the open issues and get
  involved!  This is still a relatively early-stage project, so in a
  lot of ways the project is really "help build the Zulip Electron
  app".  Goals include parity with the old QT app and Slack's app.

**Skills required**: JavaScript experience, Electron experience.  You
  can learn electron as part of your application!

Good preparation for either project is to (1) try out the app and see
if you can find bugs or polish problems lacking open issues and report
them and (2) fix some polish issues in either the Electron app
or the Zulip web frontend (which is used by the electron app).

## Circulating proposals (February-April 2017)

If you're applying to GSoC, we'd like for you to publicly post a few
sections of your proposal -- the project summary, list of
deliverables, and timeline -- some place public on the Web,
sometime in February, March, or early April 2017. That way,
the whole developer community -- not just the mentors and
administrators -- have a chance to give you feedback and help you
improve your proposal.

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


We hope to hear from you! And thanks for being interested in
Zulip. We're always happy to help volunteers get started contributing
to our open source project, whether or not they go through GSoC.
