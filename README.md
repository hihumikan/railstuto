# README

### Usage

```sh
host machine $ docker-compose build && docker-compose up -d
host machine $ docker-compose exec /bin/bash
web container $ bundle exec rake db:migrate RAILS_ENV=development
```

access [http://localhost:3000](http://localhost:3000)
