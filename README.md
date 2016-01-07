
# Email Banner Creator

This Email banner tool is adapted from Vox Media's Meme.

Meme is a generator that Vox Media uses to create social sharing images. See working version at [http://www.sbnation.com/a/meme](http://www.sbnation.com/a/meme).

## Install

* `git clone https://github.com/voxmedia/meme.git`
* `bundle install`
* `bundle exec middleman`

This will start a local web server running at: `http://localhost:4567/`

## Customization

### Configuration

Settings and controls are configured through `source/javascripts/settings.js.erb`. The [settings file](https://github.com/voxmedia/meme/blob/master/source/javascripts/settings.js.erb) has ample comments to document configuration.

### Fonts

Include your own fonts in `stylesheets/_fonts.scss`, then add your font options into the [settings file](https://github.com/voxmedia/meme/blob/master/source/javascripts/settings.js.erb#L12).

### Editor theme

Set the [theme-color variable](https://github.com/voxmedia/meme/blob/master/source/stylesheets/_vars.scss#L3) in `source/stylesheets/_vars.scss`. That one color will be tinted across all editor controls.

