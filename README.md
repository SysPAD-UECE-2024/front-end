# Data Protection System based on Encryptation and Anonymization Techniques 

Este projeto tem como objetivo estudar técnicas e metodologias para propor um sistema de proteção de dados baseado em computação em nuvem, permitindo processamento de alta capacidade sem sobrecarregar os recursos computacionais de dispositivos e servidores locais de empresas e instituições governamentais. Assim, o objetivo é desenvolver um sistema para receber dados através de uma API de comunicação, configurar anonimização adequada, proteger dados por meio de criptografia e retornar dados anonimizados aos usuários do sistema. Por fim, o protótipo foi implantado em ambiente de nuvem para realizar uma análise experimental robusta.

A aplicação web está sendo construída para fornecer uma forma fácil de o usuário final utilizar a proteção de dados oferecida por este projeto.

# Estrutura do readme.md

Este documento está organizado nas seguintes seções principais:

1. **Selo Considerados**  
   Certificações de qualidade aplicadas ao projeto

2. **Informações Básicas**  
   Detalhes de acesso e arquitetura do sistema

3. **Dependências**  
   Especificação técnica de tecnologias e requisitos

4. **Instalação**  
   Guia completo para configuração do ambiente

5. **Estrutura do Repositório**  
   Diagrama da organização de arquivos e componentes

6. **Preocupações com Segurança**  
   Diretrizes para operação segura do sistema

7. **Testes e Experimentos**  
   Procedimentos para validação das funcionalidades

8. **Licença**  
   Direitos de uso e modificação do código
   
# Selos Considerados

Os selos considerados são: **Disponíveis**, **Funcionais**, **Sustentáveis** e **Reprodutíveis**.

# Informações básicas

A versão atual do sistema está hospedada na Huawei Cloud e pode ser acessada através [deste link](http://110.238.69.32/)

Este repositório contém apenas o front-end da aplicação web do projeto. Você pode acessar:
- Agente cliente: [Repositório do Agent](https://github.com/FRIDA-LACNIC-UECE/agent)
- Back-end da aplicação: [Repositório do Back-end](https://github.com/FRIDA-LACNIC-UECE/back-end)

# Dependências

## Tecnologias Utilizadas
- [Git](https://git-scm.com/) - Sistema de controle de versão distribuído
- [Node.js](https://nodejs.org/en) v12.22.1 - Ambiente de execução JavaScript
- [Npm](https://www.npmjs.com/) v6.13.4 ou [Yarn](https://yarnpkg.com/) v1.21.1
- [Quasar](https://quasar.dev/) v2.12.0 - Framework baseado em Vue.js
- [Vue.js](https://vuejs.org/) v3.0.0 - Framework para interfaces web
- [Vue-router](https://router.vuejs.org/) v4.0.0 - Gerenciamento de rotas para Vue.js
- [Vuex](https://vuex.vuejs.org/) - Gerenciamento de estado para Vue.js
- [Axios](https://axios-http.com/) v0.27.2 - Cliente HTTP para APIs

# Instalação

Para executar a aplicação, você precisará de:
- Git
- Node.js
- Npm ou Yarn
- [Vue CLI Plugin](https://quasar.dev/start/vue-cli-plugin)
- [Quasar CLI](https://quasar.dev/start/quick-start)

```bash
# Clonar repositório com a branch atualizada
git clone https://github.com/FRIDA-LACNIC-UECE/front-end

# Acessar diretório
cd front-end

# Instalar dependências
npm install # ou yarn install

# Executar aplicação
quasar dev

# A aplicação estará disponível em: http://localhost:8080
