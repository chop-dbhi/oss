## Open Source Checklist

### Code

- [Choose](http://choosealicense.com/) a license
    - Without a license, people won't or can't use your code
- [Create repository](https://github.com/new)
- Include CONTRIBUTORS.md in repository
    - Encourages people to contribute and acts as a guideline for contribution
- Include README.md with general information about the repository
    - Even if a website exists for the codebase, a quick summary prevents the user from needing to click another link
- Include or reference a [style guide](https://github.com/cbmi/style-guides)
    - This should be mentioned in the CONTRIBUTORS.md and optionally in the README.md
- Define a set of consistent [issue labels](https://github.com/cbmi/style-guides/blob/master/git.md#issue-labels)
    - This promotes clarity and consistency when triaging issues
- Integrate with [Travis-CI](http://about.travis-ci.org/docs/user/getting-started/) for continuous integration/testing of your code base
- Integrate with [Coveralls.io](https://coveralls.io/docs) (which integrates with Travis-CI) for code coverage stats


### Documentation

- [Github Pages](http://pages.github.com/) for user and technical docs
    - To make using Jekyll a tad easier for documentation, check out [jekyll-docs-template](http://bruth.github.io/jekyll-docs-template/)
    - There are alternatives for hosting auto-generated technical docs such as [Read The Docs](https://readthedocs.org)
- _(optional)_ [GitHub Wiki](https://github.com/blog/774-git-powered-wikis-improved) for community supplied information or extensions
    - See [Backbone's wiki](https://github.com/jashkenas/backbone/wiki) for example pages
    - Here is [wiki template](https://github.com/bruth/oss-community-wiki/wiki) which includes most of the needed pages for building a community

### Community

- [Create](https://groups.google.com/forum/#!creategroup) a Google Group or something
    - For general discussion, questions, support, etc.
    - Provides a low barrier for getting people aware of what's happening in the project without needing to have a GitHub account
- _(optional)_ [Create](https://plus.google.com/communities) a Google+ community
    - More of a friendly and social format for the project as suppose to a mailing list
- _(optional)_ [Create](https://twitter.com/signup) a Twitter account
    - Short notifications such as new releases, community events, hackathons, etc.
