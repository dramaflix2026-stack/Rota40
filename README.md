# Rota 40 by Eduverso — prévia v0.1

Protótipo responsivo navegável, sem dependências de npm. `npm start` inicia em `0.0.0.0:$PORT` (padrão 3000). Railway: conectar repositório, usar ambiente production, gerar domínio e configurar healthcheck `/health`.

Inclui landing page, painel, diagnóstico de quatro questões ilustrativas, rota por erros e tempo, catálogo de 20 disciplinas, mini-simulado, caderno de erros e flashcards. Os resultados ficam no localStorage do navegador, sem autenticação. O mentor IA é explicitamente indisponível. Não é um produto comercial nem uma base jurídica revisada.

Antes de lançar: migrar para arquitetura de produção com autenticação, Postgres/RLS, conteúdo revisado e versionado, RAG com fontes oficiais, limites e auditoria de IA, direitos de conteúdo, checkout e webhook, métricas e LGPD. Não usar como área paga até que essas integrações estejam implementadas e verificadas.