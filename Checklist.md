# 📝 CHECKLIST GERAL DE DESENVOLVIMENTO DE PROJETO

# Nome do Projeto:


* Objetivo: reduzir retrabalho, garantir segurança e entregar funcionalidades completas
da versão inicial que deverá ser diponibilizada somente após o cumprimento de todas as fases descritas aqui.

-------------------------------------------------------------------------------------------
## 📝 FASE 1 — PRD SIMPLES (DOCUMENTO DO PRODUTO):

- [] Problema que o sistema resolve descrito
- [] Quem usa e como usa (exemplos reais)
- [] Fluxo principal do usuário descrito
- [] Regras de negócio explicadas
- [] O que acontece em caso de erro definido (casos de borda)
- [] Critérios de aceite listados
- [] Documento salvo em formato `.md` e versionado
--------------------------------------------------------------------------------------------
## 🧱 FASE 2 - CONTROLE DE VERSIONAMENTO:

- [] Repositório local inicializado com git init
- [] Repositório em nuvem criado (Git Hub ou Git Lab)
- [] Definido o tipo de versionamento
- [] Preenchido o checklist de Features e Versionamento

---------------------------------------------------------------------------------------------
## 🧱 FASE 3 — DADOS E BACKEND ANTES DA INTERFACE:

- [] Definido o tipo de banco de dados que será utilizado, bem como o SGDB;
- [] Tabelas criadas e revisadas (Modelagem de dados)
- [] Permissões configuradas
- [] RLS ativado desde o início
- [] Definida a linguagem de programação do beck end 
- [] API criada e respondendo corretamente
- [] Testes realizados com aprovação total
- [] Depois disso → conectar frontend

*O Front end terá o seu desenvolvimento iniciado somente depois que as funcionalidades basicas da API 
e as principais tabelas do Banco de Dados estiverem prontas e testadas.*

------------------------------------------------------------------------------------------
## 🧱 FASE 4 - FRONT END:

- [] Definidas as tecnologias que serão utilizadas no front end;
- [] Definido layout base das telas por meio de prototipagem;
------------------------------------------------------------------------------------------
## 🛠️ FASE 5 — DEBUG E TESTES:

- [] Erro reproduzido
- [] Hipótese escrita (o que pode estar acontecendo)
- [] IA usada como apoio, não como solução cega
- [] Correção aplicada
- [] Teste criado para evitar o erro no futuro
- [] Mocks usados quando necessário
- [] Preferir também testes de integração
------------------------------------------------------------------------------------------
## 🔐 FASE 6 — CHECKLIST DE SEGURANÇA:

- [] RLS ligado
- [] APIs exigem autenticação
- [] Edge functions revisadas
- [] Variáveis secretas protegidas
- [] Logs ativos (registro de ações)
- [] Rate-limit configurado (evita abuso)
- [] Revisão final antes do deploy
-------------------------------------------------------------------------------------------
## 🎯 FLUXO RESUMIDO:
1. PRD criado  
2. Modelar dados + backend  
5. Criar Front End  
5. Testar e corrigir  
6. Passar no checklist de segurança  
7. Controle de versionamento  
--------------------------------------------------------------------------------------------
## 🧩 GLOSSÁRIO TÉCNICO:

*PRD*: 
É o Documento de Requisitos do Produto — uma explicação clara do que o sistema faz.

*Banco de Dados*: 
Onde as informações ficam guardadas.

*RLS (Row Level Security)*: 
Regra que impede usuários de verem dados de outras pessoas.

*Permissões*: 
Quem pode acessar o quê.

*Debug*: 
Processo de descobrir e resolver erros.

*Mock*: 
Simulação de algo real para testar sem depender do sistema inteiro.

*API protegida*: 
Só pessoas/autos permitidos acessam.

*Edge functions*: 
Funções que rodam próximas ao usuário (ex.: serverless)

*Check de segurança*:  
Revisão final antes de publicar.



