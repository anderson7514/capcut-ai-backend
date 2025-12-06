# CapCut-AI-Backend

Backend do aplicativo estilo CapCut com Inteligência Artificial.

Este repositório contém:
- `server.js`: servidor principal com endpoints para gerar prompts, roteiros e palavras-chave para vídeos.
- `package.json`: dependências e scripts do projeto.
- `README.md`: documentação do projeto.

## Como usar
1. Faça o deploy do backend no Render ou outro serviço Node.js.
2. Configure variáveis de ambiente para integração com IA (opcional).
3. Acesse os endpoints via navegador ou Postman.

## Endpoints principais
- `/` → teste do servidor
- `/analise-video-viral` → gera análise de vídeo viral
- `/generate-package` → gera pacote completo (roteiro + hashtags + thumbnail)
- `/gerar-roteiro` → gera roteiro curto
