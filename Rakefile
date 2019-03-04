ENV["PLAYLISTER_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

# Type `rake -T` on your command line to see the available rake tasks.

task :console do
  Pry.start
end

=begin
  hello = Song.create(name: "Hello")
  adele = Artist.create(name: "Adele")   not capitalised??? Adele
  hello.artist = adele   not "Adele"???
=end