## Open Source Checklist

### Code

- [Choose](http://choosealicense.com/) a license
    - Without a license, people won't or can't use your code
- [Create repository](https://github.com/new)
    - If the new project contains Python or JS code, add the relevant portion(s) of the [pre-commit](https://github.com/cbmi/oss/blob/master/pre-commit) file to the cloned repo at `.git/hooks/` and set the permissions to `755` using `chmod 755 .git/hooks/pre-commit`. NOTE: You will need to update the [first line](https://github.com/cbmi/oss/blob/master/pre-commit#L1) of the pre-commit file to be the path to your local Python instance.
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
- Dedicate a site or series of pages to **cookbook-style** code recipes
    - Recipes should follow the tried and true O'Reilly [problem/solution/discussion format](http://oreillynet.com/images/cookbooks/spread.gif)
    - This acts as a _code examples FAQ_ which lowers the barrier for people to learn the APIs
    - Create an editable wiki page or thread on Google Groups to encourage user-submitted recipes. If these are the dedicated pages, ensure the recipes are reviewed and attribute is provided when they are moved.
        - Send an email thanking the user who submitted with a link to the new location of the recipe
- Have a section for "Prior Work"
    - This is thought about implicitly when starting a project, but this pre-development reasoning is helpful for others to understand why the project exists to begin with. Note, this does not preclude having an "About" section/page which has a more direct vision for the project.
    - Start writing this section _immediately_ during a project's inception. If nothing else doing this helps justify why the project is worth doing.


### Community

- Create tickets that are simple to implement/fix to encourage people to contribute (even if it takes longer to write up the ticket than to implement)
    - This lowers the barrier to get someone _in the code_. They will become comfortable navigating the code which increases their likelihood to contribute.
- [Create](https://groups.google.com/forum/#!creategroup) a Google Group or something
    - For general discussion, questions, support, etc.
    - Provides a low barrier for getting people aware of what's happening in the project without needing to have a GitHub account
- _(optional)_ [Create](https://plus.google.com/communities) a Google+ community
    - More of a friendly and social format for the project as suppose to a mailing list
- _(optional)_ [Create](https://twitter.com/signup) a Twitter account
    - Short notifications such as new releases, community events, hackathons, etc.
