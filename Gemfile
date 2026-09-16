source "https://rubygems.org"

# Pins Jekyll and plugins to exactly what GitHub Pages runs,
# so the local preview matches the deployed site.
gem "github-pages", group: :jekyll_plugins

# Needed on Windows for `jekyll serve` file watching and timezone data
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", ">= 0.1.0"
end
