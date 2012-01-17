# QuietAssets

Rails 3.* logs assets in the output from rails server. These messages are pretty verbose.
Adding this gem to your project's Gemfile will suppress those messages.

``` ruby

group :development do
  gem 'quiet_assets', git: 'git@github.com:AgilionApps/quiet_assets.git'
end

```

## Credits

Lifted from: http://stackoverflow.com/questions/6312448/how-to-disable-logging-of-asset-pipeline-sprockets-messages-in-rails-3-1/7508407#7508407
