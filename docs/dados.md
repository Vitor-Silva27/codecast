# Gerenciamento de Dados

# Estratégia de armazenamento de dados
A estratégia de armazenamento de dados para o sistema de streaming de vídeos é fundamental para lidar com o grande volume de informações geradas, frequentemente acessadas e garantir baixa latência. Optou-se por utilizar o banco de dados NoSQL MongoDB devido às suas características específicas que atendem aos requisitos do projeto.

O MongoDB oferece flexibilidade no modelo de dados, sendo capaz de lidar com documentos complexos, como informações de vídeos, usuários e interações. Sua capacidade de escalabilidade horizontal é crucial para garantir o gerenciamento eficiente de grandes volumes de dados e cargas de tráfego intenso, características intrínsecas a plataformas de streaming.

Além disso, a natureza distribuída do MongoDB é vital para assegurar que os dados não estejam centralizados em um único local, proporcionando redundância e evitando perda de dados em casos de falhas ou danos ao banco de dados.
 

# Gerenciamento de bancos de dados
O gerenciamento segue um modelo distribuído e escalável para lidar com grandes volumes de dados e tráfego simultâneo de usuários. Aqui estão alguns aspectos relacionados ao modelo de dados deste sistema:

#### Armazenamento Distribuído
- **Banco de Dados NoSQL:** Será utilizado banco de dados NoSQL, como o MongoDB, para permitir uma escalabilidade horizontal eficiente. Isso é crucial para lidar com a alta demanda de leitura e gravação.
- **Divisão de Dados por Geografia:** Para otimizar o desempenho e reduzir a latência, os dados podem ser distribuídos geograficamente em centros de dados ao redor do mundo, permitindo uma entrega rápida de conteúdo aos usuários.

#### Gerenciamento de Metadados
- **Indexação Eficiente:** Sistemas de streaming precisam de um mecanismo eficiente para indexar e recuperar metadados relacionados a vídeos, como título, descrição, tags e informações do criador.
- **Sistema de Filas para Processamento Assíncrono:** O uso de sistemas de filas, como o Apache Kafka, pode ser adotado para processar assincronamente operações relacionadas a metadados, como atualizações de visualizações, likes e recomendações.

#### Gerenciamento de Conteúdo Multimídia
- **Transcodificação Dinâmica:** Os sistemas realizam transcodificação dinâmica para oferecer suporte a diferentes resoluções e formatos de vídeo, garantindo uma experiência de visualização otimizada para dispositivos variados.

#### Sistemas de Cache
- **Cache de Conteúdo Dinâmico:** O uso de sistemas de cache, como o Redis, para armazenar temporariamente informações frequentemente acessadas, como informações de perfil do usuário, listas de reprodução e configurações pessoais.

#### Processamento de Streams ao Vivo
- **Tecnologias de Streaming:** Utilização de protocolos de streaming, como o HTTP Live Streaming (HLS) ou o Dynamic Adaptive Streaming over HTTP (DASH), para entregar conteúdo ao vivo de maneira eficiente e adaptável à largura de banda do usuário.

#### Análise de Dados em Tempo Real
- **Ferramentas de Análise de Big Data:** O processamento de eventos em tempo real e a análise de big data são usados para entender padrões de comportamento do usuário, melhorar recomendações e personalizar a experiência do usuário.

#### Backup e segurança
- **Soluções de Backup e Recuperação:** Para garantir a integridade e a disponibilidade contínua dos dados, implementaremos estratégias de backup regulares, utilizando soluções confiáveis como AWS Backup. Isso assegura a rápida recuperação em caso de falhas ou perda de dados.
- **Políticas de Retenção e Gerenciamento de Dados:** Estabeleceremos políticas claras de retenção de dados, gerenciando adequadamente o ciclo de vida das informações armazenadas. Dados desnecessários serão arquivados ou excluídos regularmente, otimizando o uso de recursos de armazenamento.
- **Segurança Avançada dos Dados:** Implementaremos medidas de segurança avançadas, como criptografia de dados em repouso e em trânsito, para proteger as informações sensíveis. O controle de acesso será rigorosamente aplicado para garantir que apenas usuários autorizados possam acessar e modificar dados.
