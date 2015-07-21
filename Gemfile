# ~/Gemfile
#
# To slim on needed gems, just comment out unused ones

source "http://rubygems.org"

group :development do

  # Sass, Compass and extensions.
  gem 'sass'                    # Sass.
  gem 'sass-globbing'           # Import Sass files based on globbing pattern.
  gem 'breakpoint'              # Manages CSS media queries.
  gem 'compass'                 # Framework built on Sass.
  gem 'compass-validator'       # So you can `compass validate`.
  gem 'susy'                    # Susy grid framework.
  gem 'oily_png'                # Faster Compass sprite generation.
  gem 'css_parser'              # Helps `compass stats` output statistics.
  gem 'compass-rgbapng'         # Turns rgba() into .png's for backwards compatibility.
  gem 'singularitygs'           # Alternative to the Susy grid framework.
  gem 'zen-grids'               # John Albin Zen grid framework.
  gem 'toolkit'                 # Compass utility from the fabulous Snugug. https://github.com/at-import/toolkit
  gem 'chroma-sass'             # John Albin color scheme helper. https://github.com/JohnAlbin/chroma
  gem 'scss_lint'               # Check your SCSS

  # Guard
  gem 'guard'                   # Guard event handler.
  gem 'guard-sass'              # Compile just plain Sass
  gem 'guard-compass'           # Compile on sass/scss change.
  gem 'guard-shell'             # Run shell commands.
  gem 'guard-livereload'        # Browser reload.
  gem 'yajl-ruby'               # Faster JSON with LiveReload in the browser.

  # Dependency to prevent polling. Setup for multiple OS environments.
  # Optionally remove the lines not specific to your OS.
  # https://github.com/guard/guard#efficient-filesystem-handling
  gem 'rb-inotify', '~> 0.9', :require => false      # Linux
  gem 'rb-fsevent', :require => false                # Mac OSX
  gem 'rb-fchange', :require => false                # Windows

end
