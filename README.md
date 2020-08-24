## Kafka Demo Comandos

### Criar Tópicos
- kafka-topics --bootstrap-server localhost:9092 --topic <nome_topico> --create --partitions 3 --replication-factor 1
### Alterar Tópicos
- kafka-topics --alter --bootstrap-server localhost:9092 --topic <nome_topico> --partitions <qtd>
### Listar Tópicos
- kafka-topics --bootstrap-server localhost:9092 --list
### Detalhes do tópico
- kafka-topics --bootstrap-server localhost:9092 --topic <nome_topico> --describe
### Enviar mensagem via linha de comando
- kafka-console-producer --bootstrap-server 127.0.0.1:9092 --topic <nome_topico>
### Enviar linhas de comandos com chave e valor
- kafka-console-producer --bootstrap-server 127.0.0.1:9092 --topic <nome_topico> --property parse.key=true --property key.separator=,
  Exemplo: chave,valor
   

 
