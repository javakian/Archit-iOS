# encoding: UTF-8
source 'https://rubygems.org'

gem 'rake'
gem 'cocoapods', '>= 1.11.0'
gem 'xcode-install', '>= 2.4.0'
gem 'fastlane', '>= 2.67.0'
gem 'danger-gitlab', '>= 7.0.0'
gem 'danger-swiftlint', '>= 0.11.1'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
