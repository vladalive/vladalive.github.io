source 'https://rubygems.org'

ruby '>= 4.0'

# GitHub Pages builds the live site with its own pinned toolchain (the
# github-pages gem). That gem cannot be installed on Ruby 4: every release
# that runs here is blocked (liquid 4.0.3 needs String#tainted?, commonmarker
# < 1.0 needs Ruby < 4.0). This Gemfile therefore reproduces the pieces the
# site uses, for local builds only; Pages ignores it.
gem 'jekyll', '~> 3.10.0'
gem 'jekyll-theme-tactile', '0.2.0'
gem 'kramdown-parser-gfm' # Pages default markdown setup

group :jekyll_plugins do
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
end

# No longer default gems on current Ruby; required by Jekyll 3.x.
gem 'base64'
gem 'bigdecimal'
gem 'csv'
gem 'logger'
gem 'webrick'
