# Sharing Successes Docs
Development docs of Sharing Successes

# Telas

- Home
  - Lista de aprovados
  - Lista de rejeitados(administrador)
  - Lista de pendentes(administrador)
- Criação de indicação
- Edição de indicação(administrador)
- Página da indicação(administrador)
- Login(administrador)
- Tela de Aprovação(gestor)

tem que fazer a tela do email
- Telas de confirmação
  - Tela de confimação do indicador
  - Tela de confirmação do gestor
- Tela de notificação 


# Descrição

Compartilhando sucessos é um programa anual cujo um colaborador ou cliente pode indicar seu colega de trabalho ou equipe caso ele se destaque em um dos princípios da GS, após a verificação dos indicados, são selecionados alguns para receberem prêmios.

# Desenvolvedores

- Guilherme Abe - Full Stack
- Vitor Miura - Full Stack
- Daniel Dante - Front-end
- João Montanari - Front-end
- Ícaro Duarte - Back-end
- Giovanna Freitas - Front-end
- Nathã Wolff - Front-end

# User Story

Como um colaborador ou cliente
Eu quero indicar um colega ou equipe de trabalho pelo seu esforço em um dos princípios da organização
Para valorizar o esforço de outra pessoa

Cenário:
    Dado que quero indicar alguém
    Vou acessar o website do boschview
    E vou clicar no botão de indicação
    E vou preencher o formulário
    E vou clicar no botão de envio do formulário
    E vou confirmar a autenticidade clicando no botão do email

Como o gestor do indicado
Eu quero certificar que o indicado realmente se adequa aos princípios da organização
Para não haver indicações falsas

Cenário:
    Dado que quero certificar os indicados
    Receberei o email de verificação com os dados do indicado
    E vou analisar as informações
    E vou editar as informações se preciso e aprovar
    Ou vou clicar no botão de recusar indicação

Como o organizador do evento
Eu quero organizar o evento, apresentar os canditados, editá-los e aprová-los
Para organizar evento

Cenário:
    Dado que quero certificar os indicados
    Receberei o email de verificação com os dados do indicado
    E vou analisar as informações
    E vou editar as informações se preciso e aprovar
    Ou vou clicar no botão de recusar indicação

# Anotação antiga:

Storybook

Compartilhando Sucessos é um programa anual cujo um colaborador pode indicar seu colega de trabalho caso ele se destaque em um dos princípios da Área da GS/CFIO-LA, e após uma verificação dos indicados, alguns podem ter a change de ganhar prêmios.

	- clientes podem indicar também.
	- times e colegas podem ser indicados.

-> Um colaborador da GS indica o colaborador preenchendo um formulário, contendo o próprio email, algumas perguntas, um vídeo e o email do gestor.

	- nome gestor dropdown

-> O colaborador verifica a autenticidade confirmando a indicação no próprio email.

-> Após a verificação, os dados do formulários são enviados para o gestor, que pode aprovar, editar ou recusar a indicação.

	- Pode somente editar os indicados.

-> Caso aprovado ou editado, esses dados vão para o banco de dados como sendo os indicados, nele, a nossa aplicação web exibe esses indicados.

-> O admininstrador (organizador do evento) do sistema pode adicionar, editar ou deletar informações, e adicionar imagem.

-> No final do programa, parte dos indicados recebem o prêmio.

-> Todos os cadastrados no banco de dados são categorizados como "Edição do ano XXXX", podendo arquivar as edições do evento que acontece anualmente.

Backlog:

- Prova de conceito do email, com dados do form (Video incluso)
- Autenticação
- Modelo do banco de dados (Tabela indicações)


