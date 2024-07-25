# Local-First News
Local-First News was created as an open-contribution newsletter that makes it easy to stay on top the rapidly changing local-first software landscape.

## Contributing
Anyone can contribute to the latest issue of Local-First News by creating a pull request with suggested edits to the markdown file for that week's issue.

### Guidelines
- Newsletters are sent out on Thursdays at 12:00pm Eastern Time
  - Pull requests with contributions for that week's issue can be made up to 10:00am Eastern Time on that Thursday.
- Newsletter content will generally be limited to items released or published in the 7 days prior to that Thursday.
- All contributions should be written in [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

There are three sections in each issue:
1. News and discussions <!-- TODO update with in-page links once published -->
2. Tools and resources
3. Apps

#### 📰 News and discussions section
This section is to surface: 
- Local-first focussed events that happened in the last week, or will happen in the following week.
- Articles addressing some aspect of local-first development, that came out in the last week.
- Discussions on public forums about interesting local-first issues, that took place in the last week.

Contributions should use the following format:

```
## Title
Story or discussion summary.
[Link description](https://www.link.com)
```

- Titles should descriptive and to the point.
- Story or discussion summaries should provide additional detail that would help readers decide if they want to read more.
  - E.g. why the item is newsworthy.
- Links should be to a publically accesible original source.

**Examples:**

News item:
```
## Local-First Conf held in Berlin
The first-ever developer conference dedicated to local-first app development took place in Berlin on May 30th with a tech expo day held on May 31st.
[Local-First Conf website](https://www.localfirstconf.com/)
```

Article:
```
## Linear engineer shares how they scaled their sync engine
Tuomas Artman provides a technical explanation of how Linear's realtime sync engine works with their application today.
[Linear Blog](https://linear.app/blog/scaling-the-linear-sync-engine))
```

Discussion:
```
## The opportunity for local-frist of B2B SaaS
Discussion started by @emerywells on how apps with faster UI could dominate B2B markets.
[Twitter thread](https://x.com/emerywells/status/1813265037454451039)
```

#### 🛠️ Tools and resources section
This section is to surface:
- New tools related to local-first development released in the last week.
- Significant updates to existing tools released in the last week.
- Useful resources made available in the last week.

Contributions should use the following format:

```
## Tool name [optional: version number] or Resource title
Tool or resource summary.
[Link Description](https://www.link.com)
```

- Tool names should be used as is. Include a version number if the item refers to an update of an existing tool.
- Tool summaries should be descriptive and to the point.
- Links should be to the tool's website or GitHub page or to the webpage where the resource is available.

**Examples:**

Tool:
```
## TinyBase v5.1
TinyBase, a "reactive data store for local-first apps", adds server sync capabilities in this release.
[TinyBase release notes](https://tinybase.org/guides/releases/#v5-1)
```

Resource:
```
## Architectures for Central Server Collaboration
Matthew Weidner models architectural techiques that can be used to create real-time collaborative apps using a central server.
[Blog post](https://mattweidner.com/2024/06/04/server-architectures.html)
```

#### 👾 App section
This section is to surface apps built using local-first architectures. A wider discretion is applied regarding the app's release date being in the prior week. Apps are likely to be includeed if they:
- were released relatively recently
- are not well-known
- haven't been featured in the newsletter before

Contributions should use the following format:

```
## App name
App summary.
[optional: technology used]
[Link description](https://www.link.com)
```

- App names should be used as is.
- App summaries should be descriptive.
- Optionally include technology used, with a focus on the local-first parts of their stack.
- Links should be to the app's website or GitHub page.

Example:
```
## Fig
Wealth planning tool for freelancers.
Using PowerSync as sync engine.
[figwealth.io](https://figwealth.io/)
```

## Editorial Discretion
Our objective is to accept the vast majority of submissions as-is. However, editorial discretion will be applied to ensure submissions follow the above guidelines and for length. Guidelines may be applied more stringently in weeks with a high number of submissions. Editorial reasoning will be shared on pull requests.

@phillvdm and @cahofmeyr currently comprise the editorial team.


## Community
New to local-first? The [Local-First Software community](https://localfirstweb.dev/) is a great place to learn.
