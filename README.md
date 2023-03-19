# README

```
rails new airbnb-clone -T -d postgresql --css tailwind
bundle exec rails db:create
nvim config/
touch app/controllers/home_controller.rb
```

```
rspec install
bundle exec rails g controller home
rm app/helpers/home_helper.rb spec/helpers/home_helper_spec.rb
```

`#frozen_string_literal: true`
It improves application performance by not allocating new space for the same string, thereby also saving time for garbage collection chores. How? when you freeze a string literal(string object), you're telling Ruby to not let any of your programs modify the string literal (object).

write test
bundle exec rspec
'require_helper'
`rails generate rspec:install`
