# Estudos da Tété 🌟 — V1.2

App educativo infantil PWA para GitHub Pages, com matérias, níveis, quiz, estrelas, progresso local, módulo de Inglês Inicial, áudio por navegador, revisão das questões e painel de desempenho.

Kids learning PWA for GitHub Pages with subjects, levels, quizzes, stars, local progress, Beginner English, browser audio, question review and performance dashboard.

## Identidade / Identity

- Nome principal: **Estudos da Tété**
- Nome de apoio em inglês: **Tété Studies**
- Sigla operacional: **AT / App da Tété**
- Versão: **V1.2 — Inglês Inicial + Áudio + Desempenho**

## O que evoluiu na V1.2

- Nova matéria: **Inglês Inicial / Beginner English**.
- Progressão de Inglês do **1º ao 6º ano do Ensino Fundamental brasileiro**.
- Perguntas de escrita, leitura, tradução, vocabulário e frases simples.
- Botão **🔊 Ouvir / Listen** usando `speechSynthesis` do navegador.
- Painel inicial **Meu Desempenho** com questões, acertos, erros, aproveitamento e desempenho por matéria.
- Tela **Revisão** para estudar as questões aplicadas, com resposta da criança, resposta correta e explicação.
- Botões de voltar no quiz e nas telas principais.
- Interface mais organizada e premium, preservando o visual infantil.
- Cache offline atualizado para `estudos-da-tete-v1.2.0`.

## Arquivos / Files

- `index.html` — app principal / main app
- `manifest.json` — instalação como PWA / PWA install support
- `service-worker.js` — cache offline após primeiro carregamento / offline cache after first load
- `icons/` — ícones do app / app icons
- `.nojekyll` — compatibilidade com GitHub Pages

## Como subir no GitHub Pages

1. Criar ou abrir o repositório `estudos-da-tete`.
2. Enviar todos os arquivos deste pacote para a raiz do repositório.
3. Não colocar os arquivos dentro de uma pasta extra.
4. Ir em **Settings → Pages**.
5. Em **Build and deployment**, selecionar **Deploy from a branch**.
6. Selecionar branch `main` e pasta `/root`.
7. Salvar e abrir o link publicado.

## Mensagem de commit sugerida

`Atualiza Estudos da Tété V1.2 com inglês áudio revisão e desempenho`

## Teste rápido

1. Abrir o app no celular e no computador.
2. Conferir se aparece **Estudos da Tété**.
3. Conferir o painel **Meu Desempenho** na tela inicial.
4. Entrar na matéria **Inglês Inicial**.
5. Tocar em **🔊 Ouvir** e confirmar que o navegador fala a palavra/frase em inglês.
6. Responder um quiz.
7. Na tela de resultado, tocar em **📚 Revisar questões**.
8. Conferir se aparecem resposta dada, resposta correta e explicação.
9. Voltar para o início e verificar se o painel de desempenho atualizou.
10. Instalar como PWA e testar offline após primeiro acesso online.

## Critério de aprovação

- O app abre no GitHub Pages.
- As matérias antigas continuam funcionando.
- A nova matéria Inglês aparece e abre.
- O áudio funciona nos navegadores compatíveis.
- O painel de desempenho atualiza após o quiz.
- A revisão mostra acertos e erros.
- O app instala como PWA.
- O app funciona offline após primeiro carregamento online.
