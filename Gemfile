# encoding: UTF-8
source 'https://rubygems.org'

gem 'rake'
gem 'cocoapods'
gem 'xcode-install', '>= 2.4.0'
gem 'fastlane', '>= 2.183.0'
gem 'danger-gitlab', '>= 8.0.0'
gem 'danger-swiftlint', '>= 0.11.1'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
