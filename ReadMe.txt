Download RabbitMq Lastest version from https://www.rabbitmq.com/download.html

Download latest Erlang OTP version from https://www.erlang.org/downloads

Install ErLang

Install RabbitMq

Open http://localhost:15672/

If not Visible then open Rabbit Mq command Prompt by run as admin and type command rabbitmq-plugins enable rabbitmq_management there

Now again try to open http://localhost:15672/, Default Username:- guest and Password: guest



Basic Commands for RabbitMq

To Start App:- rabbitmqctl start_app

To Stop App:- rabbitmqctl stop_app

For Reset Command:

Stop the App:-  rabbitmqctl stop_app

Reset the App:-  rabbitmqctl reset

Start the App:-  rabbitmqctl start_app

To add a new user

rabbitmqctl add_user test test

Set Tag for the user

set_user_tags username tagname

set_user_tags test administrator

