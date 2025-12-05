# Relatório Diário de Compras

Este projeto contém uma **procedure em MySQL** que gera um relatório diário da quantidade de produtos comprados por dia.  
Além disso, um **event scheduler** é configurado para executar a procedure automaticamente todos os dias.

## 🚀 Como usar

1. Ative o Event Scheduler no MySQL:
   ```sql
   SET GLOBAL event_scheduler = ON;
