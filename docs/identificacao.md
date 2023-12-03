# Identificação do Projeto

|Projeto | Requisitante | Gerente de Projetos|
| -------| ------------ | -------------------|
| CodeCast |              |                    |

# Brainstorming 
<details>
  <summary style="font-size: 1em; font-weight: bold">Resumo do Brainstorming 01</summary>
    <br>
    <p><strong>Data da Reunião:</strong> 23 de Agosto de 2023</p>
    <p><strong>Horário:</strong> 18:00 - 20:00</p>
    <p><strong>Local:</strong> IFPI Campus Pedro II</p>

    <h2>Equipe:</h2>
    <ol>
        <li>Luis Alberto Brito de Matos - Arquiteto de Software (Mod. IV)</li>
        <li>João Vitor Pereira da Silva - Desenvolvedor Sênior (Mod. IV)</li>
        <li>Lucas Eduardo Soares de Oliveira - Analista de Requisitos (Mod. IV)</li>
        <li>Alan Manoel Fernandes da Silva - Gerente de Qualidade (Mod. IV)</li>
    </ol>

    <h2>Agenda:</h2>
    <ol>
        <li>Nome do grupo</li>
        <li>Nome do projeto</li>
        <li>Ideias de nomes do grupo e do projeto</li>
        <li>Ideias para o tipo de Streaming</li>
    </ol>

    <h2>Ideias e Discussões:</h2>

    <h3>Nome do Grupo:</h3>
    <ul>
        <li>"DevGhosts"</li>
        <li>"InventoryCode"</li>
        <li>"ArchiGhost"</li>
        <li>"ArchiLegends"</li>
        <li>"SoftCraft"</li>
    </ul>

    <p><strong>Decisão:</strong> Por votação, o nome escolhido foi "ArchiGhost" por representar a combinação de "architecture" e "Ghost", indicando uma arquitetura abstrata.</p>

    <h3>Nome do Projeto:</h3>
    <p>Discussão sobre o escopo da plataforma de streaming de música/vídeo.</p>

    <p><strong>Decisão:</strong> Streaming único de música ou filmes. Sugestão do Desenvolvedor Sênior para duas ideias adicionais: "Mood" (streaming de música com playlists baseadas no humor do usuário) e "CodeCast" (plataforma de streaming de podcasts/livecode).</p>

    <p><strong>Votação:</strong> "CodeCast" vence com três votos contra um.</p>

    <h2>Próximos Passos:</h2>
    <ol>
        <li>Criação da logo do projeto</li>
        <li>Escolha da paleta de cores</li>
        <li>Criação da logo para o grupo (ainda indefinido)</li>
    </ol>

    <h2>Observações:</h2>
    <ul>
        <li>Nomes humorísticos relacionados ao Arquiteto de Software foram descartados.</li>
        <li>Limitação do escopo para streaming de música ou filmes.</li>
        <li>Participação ativa de todos os membros na discussão e votação.</li>
    </ul>

    <h2>Imagens (exemplo):</h2>
    <ol>
        <li>Imagem da sala de reunião</li>
    </ol>
</details>

<details>
  <summary style="font-size: 1em; font-weight: bold">Resumo do Brainstorming 02</summary>
  <br>

  <p><strong>Data da Reunião:</strong> 16 de Setembro de 2023</p>
  <p><strong>Horário:</strong> 8:00 - 10:00</p>
  <p><strong>Local:</strong> Meet</p>

  <h2>Equipe:</h2>
    <ol>
        <li>Luis Alberto Brito de Matos - Arquiteto de Software (Mod. IV)</li>
        <li>João Vitor Pereira da Silva - Desenvolvedor Sênior (Mod. IV)</li>
        <li>Lucas Eduardo Soares de Oliveira - Analista de Requisitos (Mod. IV)</li>
        <li>Alan Manoel Fernandes da Silva - Gerente de Qualidade (Mod. IV)</li>
    </ol>

  <h2>Introdução:</h2>
  <p>O objetivo desta reunião é debater pontos levantados na reunião com o cliente para definir requisitos funcionais e não funcionais do sistema, bem como a criação do documento de requisitos.</p>

  <h2>Agenda:</h2>
  <ol>
    <li>Requisitos Funcionais</li>
    <li>Requisitos Não Funcionais</li>
    <li>Diagrama de Casos de Uso</li>
  </ol>

  <h2>Ideias e Discussões:</h2>
  <p>A criação dos requisitos do sistema ocorreu após a divisão da gravação da reunião autorizada pelo cliente. Cada membro da equipe ficou responsável por criar os requisitos para o seu intervalo de tempo. Posteriormente, houve uma reunião remota para a integração dos requisitos e discussão para determinar suas prioridades.</p>

  <h2>Próximos Passos:</h2>
    <ol>
        <li>Desenolvimento do protótipo</li>
    </ol>
    <h2>Imagens:</h2>
    <img src="../img/fotoReuniao01.jpg" style="height: 400px">
    <img src="../img/fotoReuniao02.jpg" style="height: 400px">
</details>

<br>

# Técnicas de Elicatação de Requisitos
A elicitação de requisitos é uma etapa crucial no processo de desenvolvimento, pois é nesse momento que as necessidades docliente são identificadas e compreendidas. A principal técnica utilizada foi a entrevista semi-aberta com cliente, onde foi possivel identificar os requisitos mais importantes, além de um questionário aplicado com o mesmo, sendo possivel identificar alguns requisitos que passaram despercebidos.

# Requisitos Funcionais 
|Código |Identificação |Classificação |Ator |Objetivo|
|--------|--------------|--------------|--------|--------|
|[RF01] |Cadastro de usuários |Essencial |Usuário| O sistema deve permitir o cadastro de usuários por meio de nome, endereço de email e senha.|
|[RF02] |Realizar Login |Essencial |Usuário|O sistema deve permitir aos usuários efetuarem login em suas contas. |
|[RF03] |Catálogo de vídeos |Importante |Sistema| O sistema deve ser organizado por catálogos de vídeos como (linguagem de programação, tendências, tutoriais, entre outras).|
|[RF04] |Transmissão ao vivo |Essencial |Criador de conteúdo| O sistema deve permitir a transmissão ao vivo de podcasts e outros eventos.|
|[RF05] |Perguntas anônimas |Desejavél |Usuário| O sistema deve permitir que os usuários possam fazer perguntas anônimas. |
|[RF06] |Sugestões de vídeos |Importante |Sistema|O sistema deve permitir aos usuários fazerem perguntas aos criadores de conteúdo sem serem expostos.|
|[RF07] |Notificação de lançamento de vídeos |Importante |Sistema|O sistema deve ser capaz de notificar os inscritos do canal quando um novo vídeo for lançado ou uma nova live começar . Essas notificações devem ser entregues de forma imediata e eficaz, seja por meio de notificações push, emails ou qualquer outro método de comunicação apropriado.|
|[RF08] |Personalização de perfil e feed |Essencial |Usuário|Os usuários devem ter a capacidade de personalizar seu perfil, incluindo a adição de uma foto de perfil e a personalização do feed de conteúdo, permitindo que eles adaptem a experiência de acordo com suas preferências individuais.|
|[RF09] |Interação com vídeos |Essencial |Usuário|Os usuários devem poder interagir com os vídeos, incluindo a capacidade de curtir os vídeos que eles gostam. Além disso, devem ser fornecidas opções para compartilhar vídeos e adicionar comentários.|
|[RF10] |Monetização por anúncios e visualizações |Essencial |Sistema|O sistema deve incluir um sistema de monetização que permita a exibição de anúncios antes, durante ou após os vídeos, bem como a geração de receita com base nas visualizações dos vídeos.|
|[RF11] |Modelo de assinatura |Desejável |Sistema|Deve ser implementado um modelo de assinatura que permita aos usuários pagar uma quantia específica para ter acesso a conteúdos exclusivos e à comunidade de um canal. Os usuários que pagam devem receber destaque e benefícios adicionais.|
|[RF12] |Controle de qualidade de vídeo |Essencial |Sistema|O sistema deve ser capaz de ajustar a qualidade dos vídeos de acordo com a velocidade da internet do usuário, garantindo uma experiência de visualização suave mesmo para aqueles com conexões de internet mais lentas. Isso pode incluir a entrega de diferentes resoluções de vídeo.|
|[RF13] |Legendas automáticas |Desejável |Sistema|É desejável que o sistema seja capaz de gerar legendas automáticas para os vídeos, tornando o conteúdo acessível a um público mais amplo, incluindo pessoas com deficiência auditiva.|
|[RF14] |Interpretação de código |Desejável |Sistema|A plataforma deve possuir um intérprete aos vídeos.|
|[RF15] |Suporte a vários idiomas |Importante |Sistema|A plataforma deve suportar múltiplos idiomas para a interface do usuário e para a descrição dos vídeos.|
|[RF16] |Tutoriais para os criadores de conteúdo |Importante |Sistema|Deve haver tutoriais para ajudar os criadores de conteúdo a produzirem vídeos conforme a plataforma e de alta qualidade.|
|[RF17] |Relatórios e análises |Importante  |Sistema|Os criadores de conteúdo devem ter acesso a informações detalhadas sobre o desempenho de seus canais, como visualizações, comentários e métricas de engajamento e inscritos.|
|[RF18] |Tela adicional para criadores de conteúdo |Essencial |Criador de conteúdo|O sistema deve ter uma interface adicional para criadores de conteúdo.Deve haver uma distinção clara entre os usuários que criam conteúdo e os que apenas o consomem.|
|[RF19] |Usuário que só consome conteúdo pode se tornar criador |Essencial |Sistema|Deve ser possível para os usuários que inicialmente apenas consomem conteúdo se tornarem criadores de conteúdo sem criar uma nova conta.|
|[RF20] |Downloads de vídeos |Importante |Usuário|O sistema pode permitir que os usuários baixem os vídeos.|
|[RF21] |Restrição de download |Importante |Sistema|O sistema deve permitir ao criador deixar o vídeo disponível para o usuário fazer o download.|
|[RF22] |Salvamento de lives |Importante  |Sistema|O sistema deve permitir ao criador salvar ou não as lives.|
|[RF23] |Conteúdos exclusivos |Importante |Sistema|O sistema deve permitir ao criador de conteúdo fazer conteúdos exclusivos para assinantes|
|[RF24] |Agendamento de vídeos|Importante  |Sistema|O sistema deve permitir aos criadores agendarem os vídeos.|
|[RF25] |Filtro de conteúdo|Importante |Sistema|O sistema deve permitir aos usuários pesquisarem por conteúdos que desejam.|
|[RF26] |Canais inscritos|Importante |Sistema|O sistema deve permitir que os usuários vejam os canais que estão inscritos.|
|[RF27] |Histórico|Importante |Sistema|O sistema deve permitir aos usuários visualizarem o histórico de vídeos assistidos|
|[RF28] |Penalizações por violações de diretrizes|Essencial |Sistema|O sistema deve ter penalizações para usuários que não sigam as diretrizes.|
|[RF29] |Ausência de anúncios para assinantes|Essencial |Sistema|O sistema deve bloquear anúncios para os assinantes. |

# Requisitos Não Funcionais 
|Código  |Identificação |Classificação |Ator |Objetivo|
|--------|--------------|--------------|--------|--------|
|[RNF01] |Usabilidade |Essencial |Designer|O sistema deve ser projetado com foco na usabilidade, proporcionando uma experiência de usuário intuitiva e agradável. Deve ser fácil de navegar e de entender, com interfaces de usuário amigáveis, eficientes e responsivas|
|[RNF02] |Escalabilidade e arquitetura |Essencial |Arquiteto|O sistema deve ser projetado com escalabilidade em mente, garantindo que possa lidar com um aumento no número de usuários e conteúdos sem comprometer o desempenho. A arquitetura do sistema deve ser robusta e flexível|
|[RNF03] |Segurança da informação|Essencial |Desenvolvedor|O sistema deve implementar medidas de segurança eficazes para proteger as informações dos usuários, incluindo dados pessoais e de pagamento. Isso inclui criptografia de dados, autenticação segura e proteção contra ameaças cibernéticas|
|[RNF04] |Backup |Essencial |Desenvolvedor|Os vídeos e dados dos criadores de conteúdo devem ser periodicamente e automaticamente copiados e armazenados em backups para evitar perda de vídeos ou dados|
|[RNF05] |Suporte|Essencial |Equipe de Suporte|A plataforma deve oferecer suporte técnico aos usuários para solucionar problemas e responder a perguntas.|
|[RNF06] |Atualizações contínuas |Essencial |Desenvolvedor|A plataforma deve ser atualizada regularmente.|
|[RNF07] |Conformidades com a legislação local|Essencial |Desenvolvedor|O sistema deve seguir a legislação do país em que se encontra |
|[RNF08] |Restrição ao uso de terceiros|Essencial |Desenvolvedor|O sistema não pode permitir o uso de conteúdo de outros criadores |
|[RNF09] |Disponibilidade |Essencial |Desenvolvedor|O sistema deve estar disponível 24h por dia |
|[RNF10] |Manutenibilidade |Importante |Desenvolvedor|O sistema deve ser de fácil manutenibilidade para facilitar a correção de bugs.|
|[RNF11] |Desempenho |Importante |Desenvolvedor| O sistema deve ser rápido para garantir que os usuários não fiquem esperando muito tempo para carregar as páginas.|
|[RNF12] |Compatibilidade |Essencial |Desenvolvedor|O sistema deve ser compatível com diversos dispositivos. |
|[RNF13] |Opções de pagamento de assinatura |Essencial |Desenvolvedor|O sistema deve oferecer diversas maneiras de pagamento para os assinantes |