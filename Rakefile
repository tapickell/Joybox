$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'
require 'bundler'
Bundler.require


Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'Joybox'
  app.identifier = 'com.rubymotion.joybox'
  app.version = "0.0.1"

  p app.build_mode
end