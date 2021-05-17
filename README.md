## Repositorio de configuração para projeto https://github.com/wallanpsantos/ecossistemas

### As configurações são chamadas através da aplicação hr-config-server

Repositorio: https://github.com/wallanpsantos/ecossistemas/tree/develop/hr-config-server

### Arquivo properties que faz a chamada das configurações:

#### Configuracoes do repositorio properties
spring.cloud.config.server.git.default-label=main
spring.cloud.config.server.git.uri=https://github.com/wallanpsantos/ecossistemas/tree/develop/hr-config-server-properties
spring.cloud.config.server.git.clone-on-start=true
spring.cloud.config.server.git.search-paths={application}

##### Acesso ao repositorio Github do properties
spring.cloud.config.server.git.username=${GITHUB_USER}
spring.cloud.config.server.git.password=${GITHUB_PASSWORD}

### Variaveis de sistema Windows/Linux do usuario

GITHUB_USER

GITHUB_PASSWORD
