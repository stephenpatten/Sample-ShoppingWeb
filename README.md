# Sample-ShoppingWeb
A web site with a simulated cart, using a saga to track cart expiration via Quartz

https://github.com/phatboyg
http://blog.phatboyg.com/general/2015/09/12/sagas-state-machines-and-abandoned-carts.html

https://github.com/maldworth
https://www.maldworth.com/2015/09/

Note: remember to setup a Virtual Host in RabbitMQ

λ docker run -d --hostname my-rabbit --name some-rabbit -p 5672:5672 -p 15672:15672 rabbitmq:3-management

λ docker stop some-rabbit

λ docker start some-rabbit
