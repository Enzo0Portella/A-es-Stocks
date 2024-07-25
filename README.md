# Dashboard de Ações

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Faryanvichare%2Fstocks)

Demo usando Next.js, React Server Components e streaming "server-rendered" de dados de preços de ações da API Polygon.io. Inspiração original do tweet de @rauchg - https://x.com/rauchg/status/1809389050568298625

Este projeto usa a nova biblioteca de gráficos shadcn/ui - https://ui.shadcn.com/charts.

<img width="1718" alt="Screenshot 2024-07-06 at 3 23 43 AM" src="https://github.com/aryanvichare/stocks/assets/34843135/e106c427-90eb-4826-9fda-36b99d667175">

<img width="1050" alt="Screenshot 2024-07-06 at 3 24 26 AM" src="https://github.com/aryanvichare/stocks/assets/34843135/627391ef-5c54-4e54-9b3a-1371be31e690">

# Features

- Construido com Next.js App Router, Typescript, TailwindCSS, e Shadcn/UI (e a mais recentes bibliotecas de gráficos)
- Usa React Server Components e streaming "server-rendered" de preços de ações da API Polygon.io

# Primeiros passos

1. Clone este repositório em sua máquina local:

   ```bash
   git clone https://github.com/aryanvichare/stocks.git
   ```

2. Vá para o diretório clonado:

   ```bash
   cd A-es-Stocks
   ```

3. Instale dependências:

   ```bash
   npm install
   ```

4. Copie o .env.example para o seu .env.local

   ```bash
   cp .env.example .env.local
   ```

5. Obtenha sua chave de API em [Polygon.io](https://polygon.io/) e cole-a em seu .env.local

6. Execute o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```
