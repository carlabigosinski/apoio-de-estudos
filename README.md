# Apoio de Estudos

App de estudos para quem está começando em programação e quer chegar ao **backend com Java e Spring**. Trilha de aulas em ordem, quiz com explicação, desafios de lógica, projetos, anotações com correção automática e revisão espaçada. Roda direto no navegador, sem servidor e sem cadastro.

## O que tem

- **Trilha com 48 aulas**, do básico (variáveis, laços, classes) até Spring, JPA, SQL, segurança, desempenho e infraestrutura.
- **Mais de 460 perguntas** de quiz, com ordem e alternativas sorteadas a cada rodada, dica, explicação e analogia.
- **Revisão espaçada:** o que você erra volta depois de 1, 3, 7 e 14 dias.
- **Fluxo por aula:** quiz, depois anotação, depois "finalizar", e o app volta à trilha na aula seguinte.
- **Anotações com correção automática:** confere as palavras-chave do tema (aceita sinônimos e analogias) e libera o avanço com pelo menos metade coberta.
- **Animações passo a passo**, desafios de lógica, projetos, glossário e guia de status HTTP.
- **Instalável (PWA)** e funciona offline.

## Tecnologias usadas

| Tecnologia | Para que serve aqui |
| --- | --- |
| HTML | Estrutura das telas |
| CSS | Aparência, modo claro e escuro, layout para celular e computador |
| JavaScript (puro) | Toda a lógica: trilha, quiz, animações, anotações e revisão |
| localStorage | Guarda o progresso no navegador do aluno |
| PWA (manifest + service worker) | Instalar como app e abrir sem internet |
| Git e GitHub | Histórico das mudanças e publicação |

Não há framework, build nem backend: o app é um único `index.html`, mais `sw.js`, `manifest.webmanifest` e `icon.svg`.

## Como usar

Abra o `index.html` no navegador. Para testar o modo instalável, sirva a pasta por HTTP, por exemplo:

```
python3 -m http.server 8000
```

e acesse `http://localhost:8000`.

## Sobre o conteúdo

O conteúdo de estudo (aulas, perguntas e glossário) foi escrito com apoio de IA e passou por revisão, mas pode conter imprecisões. Em caso de dúvida, confirme na documentação oficial.
