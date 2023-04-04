# encoding: UTF-8
source 'https://rubygems.org'

gem 'rake', '>= 12.3.3'
gem 'cocoapods', '>= 1.11.0'
gem 'xcode-install'
gem 'fastlane', '>= 2.127.2'
gem 'danger-gitlab', '>= 7.0.0'
gem 'danger-swiftlint'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
