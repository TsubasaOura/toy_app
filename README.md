# Rails Tutorial Log

## 0章

```bash
$ sudo docker-compose build
$ sudo docker-compose run --rm web bundle install
$ sudo docker-compose run --rm web rails db:create
$ docker-compose up
```

## 第一章

## 第二章

## 第三章

ユーザー設計

```bash
$ sudo docker-compose run --rm web rails generate scaffold User name:string email:string
$ sudo docker-compose run --rm web rails db:migrate
```



表示ができなかったが以下のコードを削除すれば直った。

`/app/views/layouts/application.html.erb`

```html
<%= javascript_pack_tag 'application', 'data-turbolinks-track': 'reload' %>
```



