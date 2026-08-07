# Regras de Negócio (RN)

## RN01 – Cadastro de Usuários
- O sistema deve permitir o cadastro de usuários com diferentes perfis de acesso.
- Cada usuário poderá editar apenas suas próprias informações.
- Apenas administradores poderão cadastrar ou remover outros administradores.

---

## RN02 – Controle de Acesso
- O sistema utilizará autenticação para acesso às funcionalidades.
- Cada perfil de usuário terá permissões específicas.
- Usuários só poderão acessar projetos dos quais fazem parte.

---

## RN03 – Gerenciamento de Projetos
- Um usuário poderá participar de um ou mais projetos.
- Cada projeto possuirá seus próprios casos de teste, suítes, bugs e relatórios.
- Apenas membros autorizados poderão editar as informações do projeto.

---

## RN04 – Casos de Teste
- Todo caso de teste deverá estar vinculado a um projeto.
- Um caso de teste poderá pertencer a apenas uma suíte.
- Cada caso de teste deverá possuir título, descrição, prioridade, status e responsável.

---

## RN05 – Suítes de Teste
- Uma suíte poderá conter vários casos de teste.
- Casos de teste poderão ser movidos entre suítes do mesmo projeto.
- Não será permitido criar suítes duplicadas dentro de um mesmo projeto.

---

## RN06 – Execução de Testes
- Cada execução deverá registrar:
  - Responsável pela execução;
  - Data e hora;
  - Resultado da execução;
  - Observações.
- O resultado poderá ser:
  - Aprovado
  - Reprovado
  - Bloqueado
  - Não Executado

---

## RN07 – Sessões de Teste
- Uma sessão de teste deverá estar vinculada a um projeto.
- A sessão poderá conter um ou mais casos de teste.
- Cada sessão deverá registrar responsável, data, horário e resultado.
- O resultado poderá ser: Aprovado, Reprovado, Bloqueado ou Não Executado.

---

## RN08 – Registro de Bugs
- Um bug deverá estar vinculado a um projeto.
- Um bug poderá ser associado a um ou mais casos de teste.
- Cada bug deverá possuir:
  - Título;
  - Descrição;
  - Prioridade;
  - Severidade;
  - Status;
  - Responsável.

---

## RN09 – Evidências
- O sistema permitirá anexar imagens, documentos e vídeos como evidências.
- As evidências ficarão vinculadas à execução do teste.
- Apenas usuários autorizados poderão excluir evidências.

---

## RN10 – Histórico
- O sistema registrará todas as alterações importantes.
- Cada alteração armazenará:
  - Usuário responsável;
  - Data;
  - Hora;
  - Ação realizada.

---

## RN11 – Relatórios
- Os relatórios serão gerados automaticamente.
- Os relatórios poderão apresentar:
  - Total de casos de teste;
  - Casos aprovados;
  - Casos reprovados;
  - Bugs encontrados;
  - Taxa de sucesso;
  - Tempo médio de execução.

---

## RN12 – Dashboard
- O dashboard exibirá indicadores em tempo real.
- As informações serão atualizadas automaticamente após alterações no sistema.

---

## RN13 – Notificações
- O sistema poderá enviar notificações para:
  - Novos bugs;
  - Novas atribuições;
  - Atualizações de projetos;
  - Alterações importantes.

---

## RN14 – Pesquisa e Filtros
- Usuários poderão pesquisar por:
  - Projetos;
  - Casos de teste;
  - Bugs;
  - Usuários.
- Será possível aplicar filtros por:
  - Status;
  - Prioridade;
  - Responsável;
  - Data.

---

## RN15 – Exclusão de Dados
- Apenas usuários autorizados poderão excluir informações.
- Antes da exclusão, o sistema solicitará confirmação.
- A exclusão de um projeto removerá todos os registros relacionados, caso o usuário confirme a ação.

---

## RN16 – Integridade dos Dados
- Não será permitido cadastrar casos de teste sem projeto.
- Não será permitido registrar execuções para casos inexistentes.
- Não será permitido associar bugs a projetos diferentes do caso de teste relacionado.
- Campos obrigatórios deverão ser validados antes do salvamento.

---

## RN17 – Auditoria
- Todas as ações críticas serão registradas em um log de auditoria.
- Os registros de auditoria não poderão ser alterados pelos usuários.

---

## RN18 – Segurança
- As senhas deverão ser armazenadas de forma criptografada.
- O sistema encerrará automaticamente sessões inativas após um período configurável.
- Usuários autenticados deverão possuir sessão válida para acessar funcionalidades protegidas.

---

## RN19 – Escalabilidade
- O sistema deverá suportar múltiplos projetos simultaneamente.
- O desempenho deverá ser mantido mesmo com grande volume de casos de teste, execuções e bugs registrados.
