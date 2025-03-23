
# Fake Shop


######
Este projeto automatiza o processo de build e deploy de uma loja online Fake Shop usando GitHub Actions, Docker e Kubernetes.
O que é preciso para rodar

    Ter uma conta no Docker Hub.

    Ter uma conta no DigitalOcean ou outro serviço que tenha Kubernetes.

    Ter o GitHub Actions ativado no repositório.

    Instalar o kubectl (ferramenta do Kubernetes) e o docker na sua máquina.

Como configurar

    Crie sua conta no Docker Hub e no Kubernetes.

    No repositório do GitHub, adicione algumas variáveis para conectar o projeto:

        DOCKER_USERNAME: seu nome de usuário no Docker.

        DOCKER_PASSWORD: sua senha ou token do Docker.

        KUBE_CONFIG: arquivo de configuração do Kubernetes (se necessário).

Como funciona o processo

    Quando você fizer uma mudança no código, o GitHub Actions vai automaticamente rodar a pipeline.

    O processo vai:

        Criar a imagem Docker.

        Enviar a imagem para o Docker Hub.

        Fazer o deploy da aplicação no Kubernetes.

Como verificar se está funcionando

    Acesse o Docker Hub e veja se a imagem foi criada corretamente.

    No Kubernetes, use o comando kubectl get pods para ver se a aplicação foi implantada com sucesso.

Outras informações

Este projeto pode ser melhorado com mais testes automatizados e ferramentas de monitoramento.

### Variável de Ambiente ###
DB_HOST	=> Host do banco de dados PostgreSQL.

DB_USER => Nome do usuário do banco de dados PostgreSQL.

DB_PASSWORD	=> Senha do usuário do banco de dados PostgreSQL.

DB_NAME	=>	Nome do banco de dados PostgreSQL.

DB_PORT	=>	Porta de conexão com o banco de dados PostgreSQL.
