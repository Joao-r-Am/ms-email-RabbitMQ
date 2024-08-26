# Microsserviço Email e RabbitMQ

---

### Neste microsserviço é realizado o envio da mensagem para o email do usuário cadastrado

Quando a mensagem chega ao RabbitMQ enviado pelo [microsserviço de usuário](https://github.com/Joao-r-Am/ms-user-RabbitMQ), o serviço de email escuta a mensagem na fila, trata a mensagem, converte e envia para o email do usuário.
