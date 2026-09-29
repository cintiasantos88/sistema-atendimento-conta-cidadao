#Funcionais: 
- RF01 - O sistema deve ter o perfil de gestor e atendente.  O gestor tem um papel de gestão do sistema enquanto o atendente está designado às tarefas operacionais. O gestor cadastra e gerencia os perfis de atendente. Somente o perfil de atendente atende o cidadão.
- RF02 - Os atendentes e gerentes devem acessar o sistem,  seja na web seja na versão para mobile,através do seu login único de governo e respectiva senha.
- RF03 - Um atendente deve cadastrar a documentação de um cidadão no sistema para confirmação de identidade,através do upload do documento.
- RF04 - O sistema deve conferir se os dados cadastrados (foto do rosto, nome completo, data de nascimento e nome da mãe) são similares aos dados cadastrados na base de dados biométrica.
- RF05 - Caso os dados não sejam correspondentes, o sistema deve gerar automaticamente uma solicitação no canal de suporte para atendimento do cidadão cujos dados não correspondam à base de dados biométrica e pelo menos um deles indique que o cidadão possui cadastro único do governo válido..
- RF06 - O sistema deve registrar todos os atendimentos, tanto os bem sucedidos como os que não puderam ser realizados. 
- RF07 - Caso o cidadão seja devidamente identificado, o atendente pode atualizar a conta única  (com a atualização de dados de e-mail e/ou telefone) para restaurar o acesso do cidadão.
- RF08 - O sistema deve possuir relatórios dos atendimentos realizados por unidade, por atendente, por período.
- RF09 - O sistema deve permitir a exportação dos relatórios em pdf ou csv
- RF10 - O perfil de gerente deve permitir realização de auditorias nos atendimentos, com detalhamento de histórico dos dados alterados.
- RF11 - O sistema deve permitir alteração de dados apenas de usuários maiores de idade. Uma vez identificada a menoridade e impossibilidade de atendimento, o sistema abre automaticamente uma solicitação de atendimento junto ao canal de suporte.
- RF12 - Uma vez identificada a menoridade e impossibilidade de atendimento, o sistema deve permitir que o atendente abra uma solicitação de atendimento junto ao canal de suporte.
- RF13 -  A solicitação de atendimento para o canal de suporte deve aproveitar os dados do usuário e validações já utilizados pelo sistema, sem a necessidade de digitação novamente dos dados do cidadão. 
- RF14 - A solicitação gerada para o canal de suporte a partir de um atendimento, deve considerar que o cidadão será atendido por outro canal (instância superior) e permitir que o atendente esteja disponível para atender outro cidadão.
- RF15 - O sistema deve garantir a rastreabilidade das solicitações geradas para o canal de suporte.


#Não Funcionais: 
- RNF01 - O sistema deve garantir disponibilidade em 95% do horário comercial (8-18h).
- RNF02 - O sistema deve garantir que dados sensíveis tenham camada extra de segurança, de forma a evitar o vazamento de dados.
- RNF03 - O uso de dados deve obedecer a Lei Geral de Proteção de dados.
- RNF04 - O sistema deve guardar o histórico de ações na conta dos cidadãos que usarem o sistema.
- RNF05 - Todos os registros de histórico deverão ser mantidos por no mínimo 3 anos.
- RNF06 - O sistema deve suportar acessos simultâneos no Brasil, considerando a possibilidade de funcionamento nos 5570 municípios, com pelo menos 2 atendentes por cidade.
- RNF07 - O sistema deve ser compatível com web e mobile
- RNF08 - O sistema deve registrar histórico de erros
- RNF09 - O sistema deve levar no máximo 25 segundos para validar ou não a identificação do usuário.
- RNF10 - O sistema deve permitir integração com base de dados oficiais de biometria para conferência da identidade dos cidadãos.
- RNF11 - O sistema deve permitir a integração com o sistema utilizado pelo canal de suporte, para importação de dados do usuário.
