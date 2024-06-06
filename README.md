# Trabalho para a AC4 de Projetos. 

## Aplicativo de fila de clientes. 

- **Metodologia ágil:** Scrum
- **Modelo:** Cascata
- **Quadro Kanban**
- **Issues ou Projects do Github**
- **Readme do Github**
- **Draw.io**
- **Github**

1. **Entendimento do Problema e Definição de Escopo:** 
    - Nosso projeto visa viabilizar uma automação e agilização do processo de comunicação entre cliente e loja, através de um sistema ágil, responsivo e autônomo, que permita ao cliente agendar seus horários e ao lojista visualizar em quais horários estão preenchidos. Neste projeto, será incluído o sistema para gerenciamento, um diferenciador de acesso cliente|lojista e um controle por parte do lojista sobre os horários disponíveis. Não estará incluso integração com calendário externo ao app, nem integração com data e horário local, caso o fuso horário seja diferente. Nossos Stakeholders Externos são os lojistas e clientes, que disponibilizarão os requisitos do sistema, as funcionalidades necessárias para um MVP e quais funcionalidades não podem faltar para tal projeto.
      
2. **Levantamento de Requisitos:** 
    - A necessidade de pequenos estabelecimentos de terem um controle sobre seus próximos clientes a serem atendidos

    Documentar os requisitos funcionais e não funcionais

3. **Técnica de descrição de requisitos escolhida:** Descrição com tabelas Ator x Usuário de casos de uso. (Justificar a escolha da técnica)

## Requisitos: Aplicativo de fila de clientes. 
Lista de requisitos funcionais para o projeto.

1. Cadastro de usuários:
O sistema deve permitir o cadastro dos clientes na plataforma.
Os campos obrigatórios para o cadastro incluem: nome completo, e-mail, telefone e endereço.

2. Validação do CNPJ:
O sistema deve validar o CNPJ fornecido pelos clientes.
O CNPJ deve ser único para cada loja cadastrado.

3. Informações Pessoais:
Os clientes deve fornecer seu nome completo, primeiro nome e sobrenome.
O campo de e-mail deve ser validado quanto ao formato correto.

4. Agendamento de horários:
Permitir que os usuários agendem horários específicos para serem atendidos, ajudando a reduzir o tempo de espera e melhorando a experiência do cliente.

5. Cancelamento e reagendamento:
Capacidade para os clientes cancelarem ou reagendarem suas reservas na fila, se necessário.

6. Endereço:
Os clientes deve informar seu endereço, incluindo rua, número, bairro, cidade, CEP, país e estado.

7. Sistema de pagamento:
Integrar o aplicativo com um sistema de pagamento para permitir que os clientes paguem taxas de reserva ou depósitos. Forma de pagamento (Cartão de crédito, cartão de débito, dinheiro, pix).

8. Suporte multicanal:
Garantir que o aplicativo funcione em várias plataformas, como iOS, Android e Web, para alcançar o maior número possível de clientes.

9. Segurança dos dados:
Implementar medidas de segurança robustas para proteger as informações pessoais dos clientes armazenadas no aplicativo.


## Requisitos Não Funcionais: Aplicativo de fila de clientes. 
1. Desempenho:
O aplicativo deve ser responsivo e rápido, mesmo em períodos de alta demanda, para garantir uma experiência fluida para os usuários.

2. Escalabilidade:
O sistema deve ser capaz de lidar com um grande número de clientes simultaneamente, escalando conforme necessário para atender às demandas.

3. Segurança da informação:
Garantir a segurança dos dados dos clientes, incluindo medidas como criptografia de dados, autenticação robusta e proteção contra ameaças cibernéticas.

4. Compatibilidade:
O aplicativo deve ser compatível com uma ampla variedade de dispositivos e sistemas operacionais para alcançar o maior número possível de usuários.

5. Regulamentações:
O aplicativo deve cumprir todas as regulamentações e padrões relevantes da indústria, incluindo aqueles relacionados à segurança de dados e proteção do consumidor.

6. Manutenção:
O aplicativo deve ser fácil de manter e atualizar, com procedimentos claros para implementar correções de bugs e lançar novos recursos.

7. Tempo de Resposta:
O sistema deve ter um tempo de resposta em 3 segundos, garantindo que as interações do usuário sejam rápidas e eficientes.

8. Interface:
O aplicativo deve ter um design de interface do usuário reconhecidos e consistentes para fornecer uma experiência coesa em todas as plataformas e dispositivos.

# App para gestão de fila de clientes

Para levantamento de requisitos com os stakeholders, utilizamos entrevistas e observação. Nosso objetivo com essas duas técnicas é a proximidade com o cliente e a compreensão direta do seu objeto com o app desenvolvido. A etapa da entrevista é importante para elucidar, abranger e compreender todas as dúvidas e necessidades do usuário, mesclando a compreensão tecnológica do projeto, mas também humana. Com o objetivo de completa compreensão do usuário final, a entrevista visa, por meio do questionamento, chegar ao centro da funcionalidade do app, e assim ramificar posteriormente suas aplicações e funcionalidades. A observação nos dá uma visibilidade maior de como apps parecidos com esse operam atualmente, podendo extrair alguns parâmetros de funcionalidade. Um advento desta etapa são os problemas que ainda são recorrentes e presentes em apps já existentes, podem ser evitados e contornados, já começando o desenvolvimento do app, evitando erros comuns neste segmento.

## ENTREVISTA COM O STAKEHOLDER

- Quais são os recursos mais importantes para gerenciar filas de clientes em salões de beleza?

    Resposta - Gerenciar filas de clientes em salões de beleza é essencial para garantir um atendimento eficiente e uma experiência positiva para os clientes. Minhas prioridades são:
    - Agendamento Online
    - Notificações e Lembretes
    - Priorização Inteligente
    - Monitoramento em Tempo Real
    - Integração com PDV
    - Relatórios e Análises
    - Aplicativo para Clientes

- Qual a maneira mais fácil para seus clientes usarem esta funcionalidade, WhatsApp, app ou site?

    A escolha é o WhatsApp, devido à sua facilidade de uso. Muitas pessoas já estão familiarizadas com o WhatsApp, tornando-o uma opção conveniente. Os clientes podem simplesmente enviar uma mensagem para agendar ou verificar sua posição na fila. O WhatsApp permite uma comunicação direta entre o cliente e o salão. Os clientes podem fazer perguntas, receber atualizações e até mesmo cancelar ou reagendar seus horários. Alguns salões usam chatbots no WhatsApp para automatizar o agendamento e fornecer respostas rápidas.

- Além desta ferramenta, gostaria de um app integrado a ela?

    Sim, seria interessante ter um app que integrasse as respostas recebidas pelo WhatsApp, para que eu possa visualizar com mais clareza a lista de clientes que serão atendidos naquele dia.

## OBSERVAÇÃO

Pela nossa observação, um problema recorrente com os atuais apps de gestão de fila é que os perfis de usuário não são carregados corretamente. Os usuários não conseguem retornar ao acesso e ver as escolhas que tinham feito anteriormente, e o sistema quando vai notificar o usuário, não notifica, pois não realiza o cruzamento das informações corretamente. Problemas de interface também são comuns, os apps muitas vezes possuem mais informações do que o necessário, induzindo o usuário ao erro e falha durante o preenchimento de informação. Como por exemplo, a ausência de especificação se a data a ser preenchida é a que gostaria para o atendimento, ou a data atual.

## Casos de Uso
Segue abaixo imagem do Casos de Uso.
![image](https://github.com/Nayayaa/AC3_ProjetoSoftware/assets/101233011/358882d8-0d6d-42f6-bb2d-ea49b1185f42)

## Modelo Conceitual
Segue abaixo imagem do Modelo Conceitual.
![Modelo Conceitual](https://github.com/Nayayaa/AC4_ProjetoSoftware/assets/101233011/50b0e8a4-eed7-4b6f-9195-5764073380ad)

## Diagrama de Classes
Segue abaixo imagem do Diagrama de Classes.
![Diagrama de Classes](https://github.com/Nayayaa/AC4_ProjetoSoftware/assets/101233011/5d62a1d4-4eb3-4b72-8dba-1eae91b843af)

## Diagrama de Estado
Segue abaixo imagem do Diagrama de Estado.
![image](https://github.com/Nayayaa/AC4_ProjetoSoftware/assets/101233011/18b5935f-0f0a-4b6c-8230-9804856de01e)

## Diagrama de Sequência
Segue abaixo imagem do Diagrama de Sequência.
![Diagrama_de_sequencia](https://github.com/Nayayaa/AC4_ProjetoSoftware/assets/101948164/5bb94556-b26d-4a41-9cc1-21ab623c13af)


