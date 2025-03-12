## Robo Cambista Maluco

Esse é um projeto pessoal onde testarei conceitos e ferramentas. Os conceitos que estão sendo aplicados no robô são reais, porém os resultados de suas operações não são confiáveis.

### Requisitos
- As operações serão realizadas pela **Binance**, portanto, é necessário criar uma conta e instalar o app desktop (escolher a versão em inglês e configurar a conta em inglês).
- Ter o **Docker** e **Docker Compose** instalados.

### Como executar o projeto
Para iniciar o ambiente Docker, utilize os comandos abaixo:

```bash
docker-compose up -d

docker exec -it trading_env bash
``` 

Isso irá iniciar o contêiner e permitir acesso ao ambiente interativo do robô.

### Tecnologias Utilizadas
- **Python**
- **Anaconda**
- **CCXT** (para integração com corretoras)
- **pandas_ta**, **ta** (para análise técnica)
- **Multiprocessing** (para execução concorrente)
- **Docker** (para conteinerização do ambiente)

### Observação
Este projeto é experimental e **não deve ser utilizado para operações reais** sem a devida validação e compreensão dos riscos envolvidos.

