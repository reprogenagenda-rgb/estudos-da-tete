# Estudos da Tété / AT V1.5

App educativo infantil em PWA para GitHub Pages.

## O que mudou na V1.5

- Nova sequência pedagógica: **Aula rápida → áudio → exemplo → quiz → revisão → desempenho**.
- Cada matéria e ano abre primeiro uma tela de aula antes das questões.
- Botão **🔊 Ouvir aula** usando `speechSynthesis`.
- Botões **← Voltar** e **🏠 Início** nas telas principais.
- Revisão das questões com resposta dada, resposta correta e explicação.
- Painel de desempenho com aulas abertas, questões, acertos, erros, aproveitamento, estrelas, melhor matéria e matéria para revisar.
- Conteúdo do 1º ao 6º ano para Matemática, Ciências, Biologia, Lógica, Inglês Inicial e Língua Portuguesa.

## Arquivos

```text
index.html
manifest.json
service-worker.js
README.md
.nojekyll
icons/icon-192.png
icons/icon-512.png
```

## Como subir no GitHub Pages

1. Criar ou abrir o repositório `estudos-da-tete`.
2. Enviar todos os arquivos para a raiz do repositório.
3. Não colocar os arquivos dentro de uma pasta extra.
4. Ir em **Settings → Pages**.
5. Selecionar **Deploy from a branch**.
6. Selecionar branch `main` e pasta `/root`.
7. Salvar.

## Mensagem de commit sugerida

```text
Atualiza Estudos da Tété V1.5 com aulas ilustradas e respostas misturadas
```

## Checklist de aprovação

1. Abrir o app.
2. Entrar em Biologia.
3. Escolher 1º ano.
4. Confirmar que aparece a aula antes do quiz.
5. Tocar em **🔊 Ouvir aula**.
6. Tocar em **Começar questões**.
7. Responder questões.
8. Conferir explicação.
9. Testar **← Voltar**.
10. Testar **🏠 Início**.
11. Abrir revisão.
12. Conferir painel de desempenho.
13. Abrir no celular.
14. Instalar como app.
15. Abrir uma vez online.
16. Desligar internet e testar offline.
