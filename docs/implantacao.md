# Visão de Implantação

Apresentamos as configurações da rede física onde o software será implantado e executado. A estrutura física reflete o Modelo de Implantação do projeto, identificando os nós físicos, como computadores e CPUs, que executarão o software, bem como suas interconexões.

#### Configuração de Implantação Padrão
**Nós Físicos**

- **Servidor Principal:**
  - **Especificações:** CPU de alto desempenho, armazenamento de grande capacidade.
  - **Funções:** Hospeda o subsistema de Back-end e o banco de dados.

- **Servidor Front-end**
  - **Especificações:** CPU de múltiplos núcleos.
  - **Funções:** Responsável por executar o subsistema de Front-end e interagir com os clientes.

- **Servidor de Banco de Dados:**
  - **Especificações:** CPU otimizada para consultas intensivas, armazenamento em disco de alta capacidade.
  - **Funções:** Executa o sistema de gerenciamento de banco de dados, armazenando e recuperando dados.

**Interconexões**

- A comunicação entre o Servidor Front-end e o Servidor Principal ocorre por meio de uma rede local rápida para garantir uma resposta eficiente às solicitações do usuário.
- O Servidor Principal se conecta ao Servidor de Banco de Dados por meio de uma conexão dedicada de alta velocidade para otimizar as operações de leitura e gravação.

**Mapeamento de Processos:**
- **Subsistema de Front-end:**
  - O processo do Servidor Front-end executa as lógicas do Front-end, interagindo com os clientes e encaminhando solicitações ao Subsistema de Back-end.
- **Subsistema de Back-end:**
  - O Servidor Principal aloca processos para gerenciar autenticação, autorização, processamento de vídeo e interações com o banco de dados.
- **Banco de Dados:**
  - O Servidor de Banco de Dados executa processos relacionados ao armazenamento, recuperação e manipulação eficiente de dados persistidos.