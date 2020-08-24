## Kafka Demo Comandos

### Criar Tópicos
- kafka-topics --bootstrap-server localhost:9092 --topic <nome_topico> --create --partitions 3 --replication-factor 1
### Alterar Tópicos
- kafka-topics --alter --bootstrap-server localhost:9092 --topic <nome_topico> --partitions <qtd>
### Listar Tópicos
- kafka-topics --bootstrap-server localhost:9092 --list
### Detalhes do tópico
- kafka-topics --bootstrap-server localhost:9092 --topic <nome_topico> --describe


 
