# encoding: UTF-8
source 'https://rubygems.org'

gem 'rake'
gem 'cocoapods'
gem 'xcode-install', '>= 2.3.1'
gem 'fastlane', '>= 2.66.2'
gem 'danger-gitlab', '>= 6.0.0'
gem 'danger-swiftlint', '>= 0.11.0'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
