source 'https://rubygems.org'
ruby '2.0.0'
gem 'rails', '4.0.0'
gem 'ruby-oci8'
gem 'activerecord-oracle_enhanced-adapter', git: 'https://github.com/yahonda/oracle-enhanced.git', branch: 'rails4'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'bootstrap-sass'
gem 'devise'
gem 'rails_email_validator'
gem 'simple_form', '>= 3.0.0.rc'
gem 'simple_form_class', git: 'https://github.com/bbozo/simple_form_class'
gem 'paper_trail', :git => "https://github.com/airblade/paper_trail.git", :branch => "rails4"
group :assets do
  gem 'therubyracer', :platform=>:ruby
end
group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :rbx]
  gem 'quiet_assets'
end
group :development, :test do
  gem 'factory_girl_rails'
  gem 'pry-rails' # enter dragon
end
group :production do
  gem 'thin'
  gem 'pry-rails'
end
group :test do
  gem 'capybara'
  gem 'minitest-spec-rails'
  gem 'minitest-wscolor'
end
