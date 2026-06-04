# Estudos da Tété 🌟 — V1.1 PT/EN

App educativo infantil em HTML/CSS/JavaScript, com matérias, níveis, quiz, estrelas, sequência de estudo e progresso salvo no navegador.

Kids learning app in HTML/CSS/JavaScript with subjects, levels, quizzes, stars, study streak, and browser-saved progress.

## Identidade / Identity

- Nome principal: **Estudos da Tété**
- Nome de apoio em inglês: **Tété Studies**
- Sigla operacional: **AT / App da Tété**
- Versão: **V1.1 — Interface bilíngue PT/EN**

## O que evoluiu na V1.1 / What changed in V1.1

- Botão de idioma **PT / EN** na tela inicial.
- Interface principal traduzida: home, matérias, níveis, botões, resultado, mensagens e status.
- Português segue como idioma padrão.
- Estrutura PWA pronta para GitHub Pages.
- Cache atualizado para `estudos-da-tete-v1.1.0`.
- Progresso salvo no navegador com chave nova da versão.

Observação: nesta V1.1 a interface está bilíngue. O banco completo de perguntas, alternativas e explicações traduzidas para inglês fica planejado para a **V1.2**, para evitar quebra do quiz original já funcional.

## Arquivos / Files

- `index.html` — app principal / main app
- `manifest.json` — instalação como PWA / PWA install support
- `service-worker.js` — cache offline após o primeiro carregamento / offline cache after first load
- `icons/` — ícones do app / app icons
- `.nojekyll` — compatibilidade com GitHub Pages

## Como subir no GitHub Pages / How to publish on GitHub Pages

1. Criar um repositório chamado `estudos-da-tete` ou `app-da-tete`.
2. Enviar todos os arquivos deste pacote para a raiz do repositório.
3. Ir em **Settings → Pages**.
4. Em **Build and deployment**, selecionar **Deploy from a branch**.
5. Selecionar branch `main` e pasta `/root`.
6. Salvar e abrir o link publicado.

## Mensagem de commit sugerida / Suggested commit message

`Publica Estudos da Tété V1.1 bilíngue PT EN`

## Teste rápido / Quick test

1. Abrir o app no celular e no computador.
2. Conferir se aparece **Estudos da Tété**.
3. Tocar em **EN** e confirmar mudança dos textos da interface.
4. Tocar em **PT** e confirmar retorno para português.
5. Entrar em uma matéria e responder um quiz.
6. Conferir resultado, estrelas e desbloqueio de nível.
7. Fechar e abrir novamente para confirmar que o progresso permanece salvo.
8. Instalar pelo navegador e testar offline depois do primeiro carregamento.

## Critério de aprovação / Approval criteria

- O app abre no GitHub Pages.
- O botão PT/EN funciona sem travar.
- O quiz inicia e finaliza normalmente.
- O progresso fica salvo após fechar e abrir o navegador.
- O app instala como PWA no Android.
- Após o primeiro carregamento online, o app abre offline.

## Próxima evolução recomendada / Recommended next evolution

- **V1.2:** traduzir banco completo de perguntas, alternativas e explicações para inglês.
- **V1.3:** perfil da criança e painel dos pais/responsáveis.
- **V1.4:** relatórios de evolução por matéria e série.
- **V1.5:** mais perguntas por série, com revisão espaçada.
