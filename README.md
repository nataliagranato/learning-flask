# Criar um ambiente virtual do Python
```
python3 -m venv venv
```
## Activate the environment
```
source ./venv/bin/activate
```
## Instalar o Flask e outras bibliotecas
Com nosso ambiente virtual criado e ativado, agora podemos instalar o Flask, a biblioteca que precisamos para o site. Instalaremos o Flask seguindo uma convenção comum, que é criar um arquivo requirements.txt. O arquivo requirements.txt não é especial por si só. É um arquivo de texto em que listamos as bibliotecas necessárias para o aplicativo. Mas é a convenção normalmente usada por desenvolvedores e facilita o gerenciamento de aplicativos em que várias bibliotecas são dependências.

Nomeie o arquivo requirements.txt e adicione o seguinte texto:
```
flask
python-dotenv
requests
```

Realize a instalação usando pip para executar o seguinte comando:
```
pip install -r requirements.txt
```

# Testar o aplicativo

1. Execute o comando a seguir a fim de definir o runtime do Flask para desenvolvimento, o que significa que o servidor será recarregado automaticamente em cada alteração:
```
export FLASK_ENV=development
```

2. Execute o aplicativo com o seguinte comando:
```
flask run
```
