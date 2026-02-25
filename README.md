# PCM Framework: The "Docker Killer"
**O ambiente de desenvolvimento local mais leve, rápido e elegante do planeta**
Cansado de ver o Docker consumir 4GB de RAM para um site simples? Farto de lutar com certificados SSL no Windows? A **PCM Framework** é um motor binário de 15MB escrito em Go que orquestra o teu ambiente PHP em segundos

---
## Porquê a PCM?
* **Performance Absurda:** Consumo médio de 15MB de RAM (contra os 2GB+ do Docker).
* **SSL Automático:** Gera certificados confiáveis e domínios `.pcm` com cadeado verde instantâneo
* **Zero Configuração:** Não instalas Apache ou Nginx. O motor Go trata do Proxy Reverso
* **Multi-PHP:** Escolhe a versão do PHP no teu `.env` e a PCM trata de tudo em background

---
## Iniciação Rápida (10 Segundos)

### 1. Download & Instalação
Descarrega o [último binário aqui](link) e dá duplo-clique no `pcm.exe`
*O instalador irá configurar as variáveis de sistema automaticamente*

### 2. Criar um Projeto
Abre o teu terminal (PowerShell ou CMD) e digita:
```bash
pcm new <nome_do_site>
cd <nome_do_site>
pcm up -o
```
Neste momento estás no teu browser e tens o ambiente completamente preparado para testes