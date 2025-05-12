# script-monitoramento_sistema - Script Bash

Este repositório contém um script Bash para realizar o monitoramento básico de um sistema Linux. Ele coleta e registra informações sobre:

- **Logs do sistema e de autenticação**
- **Conectividade de rede**
- **Uso de disco**
- **Desempenho de hardware (CPU, memória, I/O)**

Todos os dados são salvos automaticamente em arquivos de log dentro do diretório `monitoramento_sistema/`.

---

## 📂 Estrutura dos Logs

| Arquivo                         | Conteúdo                                             |
|--------------------------------|------------------------------------------------------|
| `monitoramento_logs_sistema.txt` | Erros e falhas encontrados no `/var/log/syslog`      |
| `monitoramento_logs_auth.txt`   | Erros e falhas no `/var/log/auth.log`                |
| `monitoramento_rede.txt`        | Testes de conectividade com a internet e site alvo   |
| `monitoramento_disco.txt`       | Espaço em disco e uso de diretório `/home/david`     |
| `monitoramento_hardware.txt`    | Uso de RAM, CPU e estatísticas de I/O                |

---

## ⚙️ Como usar

1- Dê permissão de execução ao script:
   ```bash
   chmod +x monitoramento-sistemas.sh
2- Execute com :
./monitoramento-sistemas.sh
Na pasta em que o script esta.


