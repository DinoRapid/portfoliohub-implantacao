# Gestão de Usuarios e Políticas de Segurança (Simulação)

## Estrutura de Usuarios

Simulação de criação de contas no Google Workspace:

- **Administrador**
  - Nome: Gabriel Gazineli
  - Email: admin.portfoliohub@gmail.com
  - Permissões: controle total, integracoes, configuracoes

- **Aluno (Contribuidor)**
  - Nome: Fulano da Silva
  - Email: fulano.portfoliohub@gmail.com
  - Permissões: acesso a arquivos, edicao de documentos e eventos

- **Revisor (Leitor com comentario)**
  - Nome: Fulana de Souza
  - Email: fulana.portfoliohub@gmail.com
  - Permissões: leitura e comentarios apenas

## Grupos criados

- `admin@portfoliohub.com`
- `alunos@portfoliohub.com`
- `revisores@portfoliohub.com`

## Compartilhamento com permissoes

- Google Drive:
  - Pasta principal com permissão total para administradores
  - Subpastas separadas por grupo com permissões restritas

- Google Calendar:
  - Agenda compartilhada com edição para admins e visualização para alunos

- Google Docs:
  - Documentos colaborativos compartilhados por grupo

## Politicas de Seguranca Aplicadas (Simuladas)

- Obrigatoriedade de autenticação em duas etapas (2FA) para todos os usuarios
- Restrição de acesso a documentos apenas via contas autorizadas
- Revisão manual de permissões a cada nova etapa do projeto
- Utilização de logs de atividades via painel do administrador Google Workspace
- Backup de documentos automatizado no Google Drive
