# Luna • IA Companheira

PWA mobile com interface Funko Pop e backend Node.js usando a OpenAI Responses API.

## Requisitos
- Node.js 20+
- Uma chave da OpenAI API

## Rodar
1. Copie `.env.example` para `.env`.
2. Coloque sua chave em `OPENAI_API_KEY`.
3. Execute `npm install`.
4. Execute `npm start`.
5. Abra `http://localhost:3000`.

Para instalar no Android como app, publique o servidor em HTTPS e abra o endereço no Chrome; use “Adicionar à tela inicial”.

## Segurança
A chave da API fica somente no servidor. Não coloque a chave no HTML/JavaScript do celular.

## Próximas evoluções
- memória persistente por usuário (PostgreSQL/Supabase)
- login
- voz com Realtime API
- avatar animado
- geração de imagens
- notificações e eventos da Luna
