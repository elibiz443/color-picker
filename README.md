# color-picker

Steps:

## Create Project
```
rails new color-picker -j esbuild -c tailwind -d postgresql -T && cd color-picker && subl .
```

## Create Scaffold:
```
rails g scaffold post title body:text font_color background_color
```

## Create & migrate DB:
```
rails db:create db:migrate
```

## Add index to routes:
```
root "posts#index"
```
 ## Run Server
```
bin/dev
```

## Run the following:
```
rails g stimulus color-picker

yarn add stimulus-color-picker
```

Update stimulus controller and form.
