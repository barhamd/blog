load 'deploy'
# Uncomment if you are using Rails' asset pipeline
load 'deploy/assets'
# I added the following line. I got it from the railscast on deploying a server. It might not be necessary though since this is a new version of capistrano. Not sure right now.
Dir['vendor/gems/*/recipes/*.rb','vendor/plugins/*/recipes/*.rb'].each { |plugin| load(plugin) }
load 'config/deploy' # remove this line to skip loading any of the default tasks
