# Local-first resources

For a developer-oriented spiel on owning your own data independent of the cloud, see [this classic article by Ink and Switch](https://www.inkandswitch.com/local-first.html).

I have been moving more and more of my personal infrastructure offline because:
- I don't like being reliant on network connectivity to do what ought to be local work.
- I don't like being reliant on cloud-based platforms that will not always be around, and that frequently change their featureset / pricing models.
- It makes my general existence easier, less distracting, and more freeing. I like being able to do things on the train or at a park without getting frustrated about network connectivity.
- Local-first is the easiest and least expensive way to guarantee 100% uptime. This appeals to me both as a consumer and as a software engineer / computer scientist.

## Personal knowledge system / braintrust / notes

[Obsidian.md](https://obsidian.md/)
- In my opinion, the gold standard of local-first personal knowledge systems.
- While the core software itself is not FOSS, it *is* extensible, and has a thriving community of open-source plugins.
- It is the only personal knowledge system tested for general distribution I am aware of that is local-first, cross-platform, built on a non-proprietary human-readable encoding format (Markdown), *and* supports graph-linking, tagging, and backlink identification. (If you're not too familiar with the space, these are all features that increase your ownership of your data -- keeping it accessible and human-readable even if Obsidian unexpectedly blows up or disappears one day -- and more mentally accessible.)
- As a bonus, it is also genuinely free for personal use, not "freemium". They monetize through commercial licenses and optional web-based add-on services (that you could build yourself or use a third-party solution for if you wanted, since everything is stored in Markdown).

### Other common options that IMHO are less ideal
- The Archive (Zettelkasten): similar to Obsidian but with fewer features and a simpler workflow, non-extensible, costs $20 for lifetime license after a generous free trial period. I liked this almost as much as Obsidian. Since both of them use Markdown for storage, you can switch between them without much effort. However, limited to macOS.
- Roam Research: similar graph-linking features to Obsidian, but extremely expensive, cloud-only, proprietary data storage
- Evernote: local-first with syncing, but uses a hierarchical organization scheme
- Notion: great featureset and very intuitive interface; however: hierarchical organization scheme, no tagging, no offline support, proprietary data format
- Google Docs: probably the gold standard for real-time collaboration and sharing; however: not local-first (but does partially support offline use), hierarchical organization scheme, no tagging

## Offline information access

[Dash by Kapeli](https://kapeli.com/dash) is a $30 offline database of 200+ API documentation sets. It also supports generating your own docsets or downloading third-party docsets. Unfortunately, only available for macOS.

[Internet In A Box](http://internet-in-a-box.org/) is a piece of FOSS software that makes it easy to self-host downloaded websites on a Raspberry Pi. It is often used to increase information equitability in places where it's prohibitively expensive to get Internet access, or as an emergency backup at hospitals.

[Hundred Rabbits](https://100r.co/site/off_the_grid.html), a web dev studio that operates entirely out of a roaming sailboat, has a [fantastic compilation of off-grid resources](https://100r.co/site/off_the_grid.html) for working internet nomads.
