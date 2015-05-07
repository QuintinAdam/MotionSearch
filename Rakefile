# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

require 'motion-config-vars'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'Access Search'
  app.frameworks += ['CoreLocation', 'MapKit', 'AddressBook']

end
