# Start Local Service

```bash
bash

# install deps
bundle install
yarn install

# init db
RAILS_ENV=development bundle exec rails db:setup

# start service
pg_ctl -D /usr/local/var/postgres start
brew services redis-server starts

# start server
foreman start
```
