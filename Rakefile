namespace :assets do
  task :precompile do
    require 'jekyll'
    options = Jekyll.configuration({'auto' => false, 'server' => false})
    puts "Building site: #{options['source']} -> #{options['destination']}"
    Jekyll::Site.new(options).process
  end
end
