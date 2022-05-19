# chat-socket
Aplicação de chat em C usando socket

Como executar (apenas em ambiente linux):


Para compilar: gcc -Wall -g3 -fsanitize=address -pthread server.c -o server

Para executar: ./server <port>
  
Para compilar: gcc -Wall -g3 -fsanitize=address -pthread client.c -o client

Para executar: ./server <port>
