# Welcome to Lesson 1

- [Don't get scared, get started](#getting-started)
- [GitHub Accounts, Organizations and Teams](#organization)
- [Content types](#content)
- [Markdown](#markdown)
- [Issue tracker](#issues)
- [Tutorial tasks](#tasks)

### Getting started

GitHub itself isn't much more than a social network like Facebook or Instagram. You build a profile, upload projects to share and connect with other users by "following" their accounts. And while many users store programs and code projects, there's nothing preventing you from keeping text documents or other file types in your project folders to show off. It is capable of storing any file type from text, to structured data, to software. And more features are being added by the day. The real power of Git, however, is less about individuals publishing content (many places can do that, including google docs etc). It is more about that content being easily shared, built upon, and credited in a way that is robust to the realities of distributed collaboration. While the power of GitHub is daunting, you don't actually have to be a blackbelt to gain a lot of benefit from using it. You don't even have to know how to code or use the commandline.

### Organization

Git supports the following types of primary entities:

- **Individual:** A person who contributes to GitHub
- **Repository:** A collection of versioned files (of any type)
- **Organization:** An entity that may correspond to an actual organization (such as a university) or to a meaningful grouping of repositories. Organizations are like individuals except that they can establish teams.
- **Teams**: A group of individuals assembled by the administrators of an organization. An individual may participate in many teams and organizations, however a team is always bound to a single organization.

The relationships between any combination of these entities is many-to-many, with the nuanced exception of repositories.
For our purposes today we will oversimplify by saying that a repositoy belongs *either* to a single organization or to a single *individual*.

![](../howto/images/github-organizations-teams-repos.png)

### Markdown

| Raw markup syntax | As rendered |
|-------------|------------|
|`Emphasis, aka italics, with *asterisks* or _underscores_.`|Emphasis, aka italics, with *asterisks* or _underscores_.|
|`Strong emphasis, aka bold, with **asterisks** or __underscores__.`|Strong emphasis, aka bold, with **asterisks** or __underscores__.
|`Combined emphasis with **asterisks and _underscores_**.`|Combined emphasis with **asterisks and _underscores_**.|
|`Strikethrough uses two tildes. ~~Scratch this.~~` | Strikethrough uses two tildes. ~~Scratch this.~~ |

### Content

GitHub can store any kind of content, provided it isn't too big. (And now [even this is possible](https://git-lfs.github.com/)).
However, it is more capable for some filetypes than it is for others. Certain filetypes can be viewed 'natively' within the GitHub interface. These are:

- Images: png, jpg, svg
- GEOJSON
- CSV, TSV (note that files named type '.tab' will not render properly in the UI.
- Markdown
- Software code (eg. including json, HTML, xml etc)
- Any of these can also be set up outside of a repository but within your use

### Issues

The GitHub issue tracker is easy to use, fairly lightweight and capable for a lot of the basic project management one would want to do.
This guide is a nice overview: https://guides.github.com/features/issues/

Other more nuanced queries are also possible, but here we will stick to the basics.

Features of an effective ticket:
 - meaningful title
 - context in which the issue was encountered
 - indication of whether you're reporting a bug, feature request, or improvement
 - description of what you would like to see instead 
 - breakdown into specific tasks
 - acknowledgement of dependencies
 - mentions of specific people
 - use of meaningful tags


### Tasks
- Customize your avatar
- Create a gist
- Create an issue
- Comment on an issue

### [Back to Home](../index)
