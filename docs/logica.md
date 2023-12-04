# Visão Lógica
Nesta visão lógica da arquitetura do projeto, destacamos as partes essenciais do modelo de design, delineando a divisão em subsistemas e pacotes que compõem a estrutura do sistema.

#### Subsistema de Front-end
Este subsistema abrange a camada de apresentação do sistema, responsável por proporcionar a interface com o usuário. No contexto do projeto, a escolha predominante é a utilização de TypeScript e React. Dentro deste subsistema, identificamos pacotes específicos relacionados a diferentes componentes da interface de usuário.

**Autenticação (Component)**
- **Responsabilidades:** Gerenciar processos de autenticação e autorização do usuário.
- **Relacionamentos:** Comunica-se com o subsistema de Back-end para validar credenciais do usuário.

**Controle De Vídeos (Component):**
- **Responsabilidades:** Gerenciar a exibição e interação com vídeos.
- **Relacionamentos:** Envia solicitações ao Back-end para recuperar dados de vídeos específicos.

#### Subsistema de Back-end
O subsistema de Back-end lida com a lógica de negócios, processamento de dados e interação com o banco de dados. Aqui, TypeScript é a linguagem predominante.

**Gestão De Usuários (Módulo)**

- **Classes:** Usuário, AutenticaçãoService
- **Responsabilidades:** Gerenciar informações de usuários, autenticação e autorização.
- **Relacionamentos:** Conecta-se ao banco de dados para recuperar e armazenar dados de usuários.

**Conteúdo Multimídia (Módulo)**
- **Classes:** Vídeo, ComentárioService
- **Responsabilidades:** Gerenciar conteúdo multimídia, como vídeos e comentários associados.
Relacionamentos: Interage com o subsistema de Front-end para fornecer dados de vídeos e comentários.

#### Subsistema de Banco de Dados
Este subsistema armazena e gerencia os dados persistentes do sistema, utilizando um banco de dados adequado às necessidades do projeto.

**Modelos De Dados**
- **Entidades:** Usuário, Vídeo, Comentário
- **Responsabilidades:** Definir estruturas de dados e relacionamentos para persistência.
Esta visão lógica oferece uma compreensão clara da estrutura do sistema, destacando a organização em subsistemas, pacotes e classes, fornecendo uma base sólida para o desenvolvimento e manutenção do projeto.