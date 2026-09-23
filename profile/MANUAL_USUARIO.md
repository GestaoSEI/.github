# Manual do Usuário — Gestão SEI

## 1. Apresentação

O Gestão SEI é uma aplicação para acompanhamento de processos administrativos, prazos, unidades responsáveis e histórico de tramitações.

Este manual descreve as operações disponíveis para os perfis `ADMIN` e `USER`.

## 2. Acesso ao sistema

1. Abra o endereço da aplicação na intranet.
2. Informe seu login e sua senha.
3. Selecione **Entrar**.
4. No primeiro acesso, altere a senha inicial fornecida pela administração.

Caso a sessão expire, o sistema redirecionará para a tela de login. Faça a autenticação novamente.

## 3. Perfis de acesso

### Usuário (`USER`)

Pode:

- consultar processos;
- cadastrar e atualizar processos;
- acompanhar prazos;
- consultar o histórico de tramitações;
- alterar a própria senha;
- gerar relatórios conforme as permissões disponíveis.

### Administrador (`ADMIN`)

Além das funções de usuário, pode:

- cadastrar, editar e excluir usuários conforme as regras do sistema;
- redefinir a senha de outros usuários;
- importar processos por CSV;
- revisar registros marcados como duplicados.

## 4. Dashboard de processos

O dashboard apresenta a listagem dos processos e um resumo visual do recorte atual.

Os indicadores mostram:

- total de processos no recorte;
- processos com prazo próximo;
- processos expirados;
- processos concluídos ou encerrados;
- percentual de cada indicador em relação ao total exibido.

### Gráficos interativos

- Clique em uma barra de **status** para filtrar a listagem por aquele status.
- Clique em uma barra de **unidade** para filtrar os processos daquela unidade.
- O painel de prazos separa processos vencidos, vencendo em até 5 dias, com prazo acima de 5 dias e sem prazo definido.

Os gráficos acompanham os filtros ativos e são recalculados quando a listagem muda.

## 5. Busca e filtros

A barra de filtros permite combinar:

- palavra-chave, pesquisando número, tipo, origem, unidade e observação;
- status do processo;
- unidade atual;
- opção **Apenas Vencidos**.

Use **Limpar** para remover os filtros e voltar à listagem completa.

A coluna **Prazo Final** pode ser ordenada clicando no título da coluna.

## 6. Cadastro e atualização de processos

Para cadastrar um processo:

1. Selecione **Novo Processo**.
2. Preencha o número do processo, tipo, origem, unidade atual, status e prazo final.
3. Inclua uma observação quando necessário.
4. Selecione **Salvar**.

Para atualizar um processo, selecione **Editar** na linha correspondente. Alterações de status ou unidade ficam registradas no histórico com o usuário responsável.

Processos duplicados são identificados para revisão. A exclusão fica restrita aos registros marcados como duplicata e às permissões administrativas aplicáveis.

## 7. Prazos e status

O sistema atualiza automaticamente os status relacionados ao fluxo de prazo:

- **Em andamento**: processo dentro do prazo normal;
- **Prazo próximo**: prazo final em até 5 dias;
- **Expirado**: prazo final ultrapassado;
- **Respondido**, **Concluído** e **Encerrado**: estados de finalização ou resposta do processo.

A verificação automática dos prazos é executada diariamente. O cadastro e a atualização de processos também podem disparar o recálculo do status quando necessário.

## 8. Histórico de tramitações

Na listagem, selecione **Histórico** para consultar as alterações de um processo.

O histórico registra, quando aplicável:

- data da alteração;
- usuário responsável;
- status anterior e novo status;
- unidade anterior e nova unidade;
- observação informada na alteração.

## 9. Relatórios e exportação

### Relatório PDF de processos

Selecione **Gerar PDF** para baixar o relatório dos processos conforme os filtros ativos. O relatório inclui data e horário de emissão.

### Relatório PDF de usuários

Administradores podem gerar o relatório dos usuários cadastrados pelo menu de usuários. O relatório também registra data e horário de emissão.

### Exportação CSV

Selecione **Exportar CSV** para baixar os processos cadastrados em formato compatível com planilhas.

## 10. Importação de processos

A importação CSV está disponível para administradores.

1. Acesse **Importar CSV**.
2. Selecione um arquivo no modelo disponibilizado pelo sistema.
3. Confira o resultado da importação.
4. Revise eventuais erros e duplicatas informados.

Mantenha uma cópia do arquivo original antes de importar dados.

## 11. Senhas e segurança

- Não compartilhe sua senha.
- Altere a senha inicial no primeiro acesso.
- Use uma senha individual e difícil de adivinhar.
- Encerre a sessão ao utilizar um computador compartilhado.
- Informe à administração qualquer acesso indevido ou dado incorreto.

## 12. Suporte e feedback

Ao relatar um problema, informe a tela utilizada, o processo envolvido, os filtros aplicados e o horário aproximado da ocorrência. Não envie senhas nem dados sensíveis em mensagens de suporte.
