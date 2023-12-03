# Segurança
A segurança é uma prioridade fundamental, visando proteger dados sensíveis, garantir a integridade do sistema e proporcionar uma experiência segura aos usuários. Para atingir esses objetivos, são implementadas estratégias robustas, controles de acesso rigorosos e métodos avançados de autenticação.

#### Estratégias de Segurança
- **Criptografia de Dados:**
Todos os dados em trânsito são protegidos por meio de protocolos de criptografía, como o SSL/TLS, assegurando a confidencialidade durante a comunicação entre os diferentes componentes do sistema.
- **Proteção contra Ataques:**
Mecanismos de segurança, como Web Application Firewalls (WAF), são implementados para detectar e mitigar possíveis ataques, como injeções de código SQL, XSS (Cross-Site Scripting) e CSRF (Cross-Site Request Forgery).
- **Monitoramento Contínuo:**
Ferramentas de monitoramento contínuo são empregadas para identificar padrões incomuns, comportamentos suspeitos ou tentativas de acesso não autorizado em tempo real. Isso permite uma resposta rápida a potenciais ameaças.
#### Controles de Acesso
- **Modelo de Controle de Acesso Baseado em Funções (RBAC):**
A implementação do RBAC assegura que os usuários recebam permissões específicas com base em suas funções no sistema. Isso limita o acesso apenas ao que é estritamente necessário para suas responsabilidades.
- **Políticas de Acesso Granulares:**
Políticas de acesso granulares são estabelecidas para garantir que diferentes partes do sistema tenham restrições específicas. Isso é especialmente crucial ao lidar com dados sensíveis ou operações críticas.
#### Autenticação:
- **OAuth 2.0 e OpenID Connect:**
O OAuth 2.0 é adotado para autorização, permitindo que os usuários concedam acesso a recursos específicos sem compartilhar suas credenciais. O OpenID Connect é utilizado para autenticação, garantindo a identificação segura dos usuários.
- **Autenticação Multifatorial (MFA):**
A autenticação multifatorial é implementada para adicionar uma camada adicional de segurança, exigindo múltiplos métodos de verificação durante o processo de login.

- **Segurança da Comunicação Entre Microserviços (Tráfego Leste-Oeste):**
A comunicação entre microserviços deve ser protegida usando abordagens como segurança na camada de transporte, combinada com autenticação e autorização na camada de mensagem. Essa prática assegura que a comunicação seja segura e acessível apenas a usuários autorizados, fortalecendo a integridade do sistema.

- **Uso de Contêineres Seguros:**
Dada a natureza distribuída dos microserviços, o uso de contêineres simplifica as implantações. No entanto, é crucial garantir a segurança dos contêineres, incluindo a proteção do registro de contêineres onde as imagens são armazenadas. Ferramentas de orquestração segura, como Kubernetes, desempenham um papel vital na implementação de práticas seguras na nuvem.
- **Proteção e Criptografia de Segredos:**
Microsserviços frequentemente lidam com segredos para comunicação, como chaves de API e credenciais. É imperativo evitar a verificação desses segredos no controle de versão. Em vez disso, a criptografia de segredos usando ferramentas como HashiCorp Vault, Microsoft Azure Key Vault ou Amazon KMS adiciona uma camada adicional de segurança, protegendo informações sensíveis.
- **Conhecimento da Segurança da Nuvem e do Cluster:**
Compreender os quatro Cs da segurança nativa da nuvem (código, contêiner, cluster e datacenter corporativo/co-localizado) é essencial. Cada aspecto depende da segurança dos componentes nos quais se encaixam. O conhecimento profundo desses elementos é vital para proteger efetivamente os microserviços contra ameaças
