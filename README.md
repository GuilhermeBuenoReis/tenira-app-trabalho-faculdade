# Tenira

Aplicativo com Expo SDK 58, React Native, TypeScript e Expo Router para Android, iOS e web.

## Desenvolvimento

```bash
npm ci
npm start
```

Use `npm run android`, `npm run ios` ou `npm run web` para iniciar na plataforma desejada.

## Estrutura

- `src/app/_layout.tsx`: navegação e tema claro/escuro.
- `src/app/index.tsx`: tela inicial.
- `assets/`: ícones e splash utilizados em `app.json`.

Mantenha componentes, hooks e utilitários fora de `src/app/`, que é reservado às rotas.

## Validação

```bash
npm run lint
npm run typecheck
```

Instale dependências com `npx expo install <pacote>` para usar versões compatíveis com o SDK.
