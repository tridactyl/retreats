Tridactyl retreat dev diary
===========================

Day -1
------

-   Azk arrives; cmcaine, bovine3dom, azk go for a curry, have an accidental pilgrimage to Stephenson's Rocket, and trek to the Peak District.

Day 0
-----

-   cmcaine & bovine3dom went for a walk. Azk did some work. glacambre arrived. Hugh Jackman visits Piccadilly Gardens the day after us, proving once again our trend-setting abilities.

Day 1
-----

-   We all looked at the most-thumbed-up issues to help organise our priorities and thumbed our noses at them; our main aim for the retreat is to reduce jank and have a more consistent UX
-   cmcaine worked on a functional version of Tridactyl's state considering immutable.js, meoisis, and immer.js [link](https://github.com/cmcaine/tridactyl-2-experiments)
-   azk discovered that hiding our iframe in a shadow DOM doesn't solve the page-refresh-loop bug. azk then ran some experiments with MithrilJS and began reimplementing the commandline
-   bovine3dom started looking through the backlog of issues, closing a few, updating others
-   We moved the keyboard API to the Tridactyl organisation; bovine3dom started rewriting it to comply with the current WebExtension experiment requirements
-   The plan is to first make a Firefox Developer Edition only Tridactyl build that comes with the keyboard API to prevent us getting bored of waiting for Mozilla (and vice versa)
-   But the WebExtension Experiment API has changed enough that we're currently in build-tool hell with the keyboard-api
-   glacambre fixed a bunch of issues with scrolling and focusing events, thanks glacambre!

Day 2
-----

-   azk and cmcaine continued work on the commandline and state redesign based off saulrh's earlier work. The current focus is on getting the CLI up and running, making the statusbar work and defining the states and the RPC communication between them.
-   bovine3dom went over old issues, fixing some, closing others, and accepting a few PRs. He also bashed his head against WebExtension Experiments for the keyboard API but didn't make any progress.
-   glacambre fixed some issues from the backlog and started work on turning hintmode into a real mode with user-configurable binds.

Day 3
-----

-   azk, cmcaine and saulrh continued work on the commandline/state redesign. cmcaine wrote some RPC stuff he was happy with. saulrh got Mithril working with iframes.
-   bovine3dom closed/fixed some more issues and made it harder to add undocumented config settings.
-   glacambre finished hint mode and got it merged; he also fixed our find mode up a little bit.
- so thanks!

Day 4
-----

-   azk and cmcaine got an input box working in an iframe under Mithril. They're confident that they'll be able to get a little bit of Tridactyl working with it soon.
-   bovine3dom kept working through the backlog, closing duplicate issues and fixing easy ones. Particularly, error messages will no longer steal focus from the page.
-   bovine3dom and cmcaine looked at the keyboard API again; we've changed a few things and now we get different error messages.
-   In total, we closed 27 issues today.
-   glacambre worked on find mode to the point where it's quite useable now; he's also been experimenting with new ways of doing ex-commands such that they can be created at runtime.

Day 5
-----

-   azk, cmcaine kept working on the iframe / commandline
-   bovine3dom kept working through the backlog, closing duplicate issues and fixing easy ones. He also added `keyfeed` and user-definable modes.
-   glacambre fixed smooth scrolling a bit, and made find mode a little better.
-   In total, we closed 4 issues today (but they were harder :()
-   nmx nqqrq ebg13 naq grkg.ebg13
-   bound to `g?` by default; text mode version is not bound.
-   glacambre, cmcaine and bovine3dom went for a walk up Higger Tor.

Day 6
-----

-   glacambre made some progress towards allowing us to remove our python macro script, replacing it with the TypeScript compiler
-   glacambre fixed the find mode up a little more; it now focuses elements you select with it amongst other things
- untested on Windows, so please poke us if it seems to be broken
-   cmcaine fixed and broke numeric prefixes an odd number of times
-   cmcaine swapped npm out for yarn as we were all fed up of npm making random changes to package-lock.json
-   antonva looked at the keyboard-api and WebExtension experiments and got nowhere (like the rest of us :( )
- again subsidised by donors, so thanks!

Day 7
-----

-   glacambre left :(
-   antonva fixed up and finished `mktridactylrc`
-   bovine3dom investigated `keyup` binds and TreeStyleTab integration and opened draft PRs for both
-   cmcaine played with iframes and the shadow DOM some more

Day 8 - the final day
---------------------

-   antonva left :(
-   antonva fixed `set findcase smart` after leaving
-   bovine3dom merged `:mktridactylrc`
-   bovine3dom started to make a Sankey diagram accounting the funding and costs of the retreat for funsies
