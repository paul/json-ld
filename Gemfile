source "https://rubygems.org"

gemspec
gem 'rdf',              github: "ruby-rdf/rdf",             branch: "develop"
gem 'rdf-spec',         github: "ruby-rdf/rdf-spec",        branch: "develop"
gem 'jsonlint',         github: "dougbarth/jsonlint",       platforms: [:rbx, :mri]

group :development do
  gem 'ebnf',           github: "gkellogg/ebnf",            branch: "develop"
  gem 'sxp',            github: "gkellogg/sxp-ruby",        branch: "develop"
  gem 'rdf-isomorphic', github: "ruby-rdf/rdf-isomorphic",  branch: "develop"
  gem 'rdf-turtle',     github: "ruby-rdf/rdf-turtle",      branch: "develop"
  gem 'rdf-trig',       github: "ruby-rdf/rdf-trig",        branch: "develop"
  gem 'rdf-vocab',      github: "ruby-rdf/rdf-vocab",       branch: "develop"
  gem 'rdf-xsd',        github: "ruby-rdf/rdf-xsd",         branch: "develop"
  gem 'fasterer'
end

group :development, :test do
  gem 'simplecov',  require: false, platform: :mri
  gem 'coveralls',  require: false, platform: :mri
  gem 'psych',      platforms: [:mri, :rbx]
end

group :debug do
  gem "wirble"
  gem "byebug", platforms: :mri
end

platforms :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'rubinius', '~> 2.0'
end
