# demo-integration

# rabbitmq container 

docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management

# publishing & consuming a message 

Use rabbitmq management page for message publishing
http://localhost:15672/#/queues/%2F/orderQueue.OrderRequest

processOrderRequestFlow consumes the message

![image](https://github.com/user-attachments/assets/088cbea6-9a6a-4930-94c7-e7a7b172733c)

