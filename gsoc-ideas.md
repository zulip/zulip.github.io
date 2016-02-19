Zulip GSOC ideas

Full stack and web frontend focused projects

- Cool new features for Zulip.  Play around with the software, browse the feature suggestions that other users have contributed: https://github.com/zulip/zulip/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement, and suggest something you’d like to build!
- Performance optimization.  Zulip already performs fairly well once the site has been loaded, but there are a bunch of ideas for how to make it substantially faster, especially improving the initial load time.  We’d like to try a lot of super-new modern technologies like using HTTP 2 to send all the assets in parallel with the main page HTML.
- Overhauling the Zulip website’s user experience to handle large teams well (e.g. currently, the buddy list always has every user in the organization, no matter how big!).  This project would likely consist of 2–3 individual sub-projects each taking a few weeks to implement.
- Building out the administration pages for Zulip to let admins set a retention policy for when old messages should be deleted, see analytics on how their teams are using Zulip, audit data, etc. — the sorts of things needed for Zulip to be used at more larger organizations.  We get constant requests for these kinds of features on the Zulip mailing list.

Python backend focused projects:

- Zulip has been experimenting with the exciting new http://mypy-lang.org/ optional static typing system for Python based on PEP-484; we’d love to see a project to fully annotate Zulip’s core backend system with every function having static type declarations.  Advanced experience with Python and understanding of type theory preferred.
- Zulip has several dozen native integrations (https://zulip.com/integrations/), but Slack has a ton more.  We should build a system to make all of Slack’s numerous third-party integrations work with Zulip as well, and make Zulip’s integration system a lot more slick.
- Migrating Zulip to support Python 3 and once done, a much wider range of Linux platforms (currently, we only support Python 2.7 on Ubuntu Trusty, which substantially limits how widely it can be deployed)
- Scalability and replication: Currently Zulip has reasonably good database scalability but has a few technical changes need to make it possible to run a Zulip installation as a scalable distributed system.  It should be possible to change this in a summer!
- We have some plans for how to improve the Zulip message storage database schema to be substantially more compact with better performance.  Advanced postgresql experience desired!
- Build a federation system for users on different Zulip servers to exchange messages.


Mobile projects (mobile experience expected):

- Rebuild the iOS app using modern iOS development techniques (either React Native and/or Swift)
- Performance improvements.  Build a better caching system for the mobile apps to make the startup process substantially faster.

Desktop projects:

- Build a better desktop app for Zulip based on Electron to replace the existing qt/Webkit based app with more modern technologies.
- Making the Zulip user experience great for individuals who are members of multiple Zulip teams.












