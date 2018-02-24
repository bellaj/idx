Demonstration 

to install rails https://gorails.com/setup/ubuntu/16.04

# installation : #

gem install bundler

bundle update

bundle install


Optional : sudo apt install ruby-railties

if pg error : sudo apt-get install libpq-dev

# run Application#
rails server
and visit 127.0.0.1:3000

** Notice : **

if you have a newer Ruby downgrad or install older version 2.3.4:

add a .ruby-version file to your application's directory containing the following line:

2.3.4


this Demo works without problem with the following releases :

  ruby -v
ruby 2.3.4p301 (2017-03-30 revision 58214) [x86_64-linux]
  rails -v
Rails 3.2.13

