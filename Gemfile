# encoding: UTF-8
source 'https://rubygems.org'

gem 'rake'
gem 'cocoapods'
gem 'xcode-install'
gem 'fastlane'
gem 'danger-gitlab', '>= 7.0.0'
gem 'danger-swiftlint'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
