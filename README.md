glugglug.github.io
==================
####Config
    _config.yml    # Main config (Jekyll's settings)
    Rakefile       # Configs for deployment
    config.rb      # Compass config
    config.ru      # Rack config


####Add Post
    rake new_post\['title'\]


####Commit Source
    git add .
    git ci -m "msg"
    git push origin source


####Actions
    rake generate  # Generate site in public/
    rake preview   # Watches and mounts webserver
    rake deploy    # Push public/ to github pages

