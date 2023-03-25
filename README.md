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

install devise

```
gem devise
rails generate devise:install
bundle exec rails g devise user
bundle exec rails db:migrate db:test:prepare
```

`localhost:3000/users/sign_in` appears user form sign_in, sign_up, forgot your password

1. Make sign in form
   `$ rails generate devise:views`

2. add navbar
   `https://tailwindui.com/components/application-ui/navigation/navbars`

`bin/dev` css and js rebuild

`touch app/views/layouts/_header.html.erb `

create stylesheet file
change css - scss
install sassc

colors to root
update navbar style

update manifest
