## Pre-requisites
You need to include **javascripts/twitter.js** in your page in order for the follow buttons to work.

## Installing the plugin
Add **twitter_tag.rb** (or its containing directory, **octopress_twitter_tag**) in the **plugins** directory.

### Installing the plugin as a git submodule
1. Go to the toplevel of your working tree.
2. Add the repo as a git submodule:
    git submodule add git@github.com:abraao/octopress_twitter_tag plugins/octopress_twitter_tag

## Using the plugin
To use the plugin, simply use one of the options below (the @ symbol is optional for the twitter name).
    {% twitter abelourenco %}
    {% twitter @abelourenco %}

## TODO
1. Don't assume twitter.js is already available on the page.
2. Refactor markup from the Twitter aside.
3. Add tests. Do octopress plugins follow a common pattern for this?
4. Make the following optional: follow button, follower count.

## Credits
Based on [Brandon Mathis's](http://github.com/imathis) [image tag plugin](https://github.com/imathis/octopress/blob/master/plugins/image_tag.rb). The HTML markup was taken from his twitter aside.

## Contact
abraao@alourenco.com
