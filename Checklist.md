# 🧭 Checklist Operacional de Projetos
# Nome do Projeto:

* Objetivo: reduzir retrabalho, garantir segurança e entregar funcionalidades completas.

------------------------------------------------------------------------------------------

## ✅ FASE 1 — DEFINIÇÃO DO ESCOPO ############################

- [ ] Funcionalidades da versão atual definidas
- [ ] Itens que NÃO entram nesta versão registrados
- [ ] Critérios de sucesso descritos em linguagem simples
- [ ] Mudanças só entram em versão futura (escopo controlado)

------------------------------------------------------------------------------------------

## 📝 FASE 2 — PRD SIMPLES (DOCUMENTO DO PRODUTO) ##############

- [ ] Problema que o sistema resolve descrito
- [ ] Quem usa e como usa (exemplos reais)
- [ ] Regras de negócio explicadas
- [ ] O que acontece em caso de erro definido
- [ ] Critérios de aceite listados
- [ ] Documento salvo em formato `.md`

------------------------------------------------------------------------------------------

## 🧱 FASE 3 — DADOS E BACKEND ANTES DA INTERFACE ###############

**Termos simples**
- Banco de dados = onde as informações ficam guardadas  
- Permissões = quem pode acessar o quê  
- RLS = impede um usuário de ver dados de outro

Checklist:

- [ ] Tabelas criadas e revisadas
- [ ] Permissões configuradas
- [ ] RLS ativado desde o início
- [ ] API criada e respondendo corretamente
- [ ] Depois disso → conectar frontend

-----------------------------------------------------------------------------------------

## 🧩 FASE 4 — UMA FEATURE POR VEZ #################################

**Feature = funcionalidade completa do início ao fim**

Definition of Done:

- [ ] Funciona de ponta a ponta
- [ ] Conectada ao banco
- [ ] Testada
- [ ] Revisada
- [ ] Pode ir para produção sem riscos

Nada de “quase pronto”.

-------------------------------------------------------------------------------------------

## 🛠️ FASE 5 — DEBUG E TESTES #########################################

**Debug = processo de entender e corrigir erros**

- [ ] Erro reproduzido
- [ ] Hipótese escrita (o que pode estar acontecendo)
- [ ] IA usada como apoio, não como solução cega
- [ ] Correção aplicada
- [ ] Teste criado para evitar o erro no futuro
- [ ] Mocks usados quando necessário
- [ ] Preferir também testes de integração

--------------------------------------------------------------------------------------------

## 🔐 FASE 6 — CHECKLIST DE SEGURANÇA ##################################

**Termos simples**
- API protegida = só pessoas autorizadas acessam  
- Edge functions = funções que rodam no servidor próximo ao usuário  
- Secrets = dados sensíveis fora do código

Checklist:

- [ ] RLS ligado
- [ ] APIs exigem autenticação
- [ ] Edge functions revisadas
- [ ] Variáveis secretas protegidas
- [ ] Logs ativos (registro de ações)
- [ ] Rate-limit configurado (evita abuso)
- [ ] Revisão final antes do deploy

-----------------------------------------------------------------------------------------------

## 🎯 FLUXO RESUMIDO ###################################################

1. Definir escopo  
2. Criar PRD simples  
3. Modelar dados + backend  
4. Construir uma feature completa  
5. Testar e corrigir  
6. Passar no checklist de segurança  
7. Só então avançar para a próxima feature  

-----------------------------------------------------------------------------------------------

## ✍️ ASSINATURA DE ENTREGA (opcional) ###################################

Responsável: __________________________  

Data: ____ / ____ / ______

Status:  ☐ Aprovado   ☐ Ajustar
