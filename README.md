# Apoio de Estudos

## Acesse o app

👉 **https://carlabigosinski.github.io/apoio-de-estudos/**

## Sobre o projeto

O Apoio de Estudos Java é um aplicativo de estudos desenvolvido para organizar e facilitar o aprendizado de programação. A proposta é reunir em um só lugar conteúdos, exercícios e ferramentas que ajudam a entender, praticar e acompanhar cada etapa dos estudos.

## Por que criei este projeto?

Criei este aplicativo para me ajudar a estudar Java de uma forma mais organizada, já que muitas ferramentas de estudo oferecem recursos pagos.

Decidi usar a inteligência artificial para transformar minha ideia em algo real. Todo o desenvolvimento foi feito com o auxílio do Claude, a partir das minhas ideias e orientações sobre como o aplicativo deveria funcionar.

Além de criar uma ferramenta para meus estudos, essa experiência me permitiu aprender a comunicar ideias, dar instruções, tomar decisões e conduzir o desenvolvimento com o apoio da IA.

No final, aprendi não só sobre programação, mas também sobre como transformar uma ideia em um projeto e conduzir um desenvolvimento com IA.


## No projeto/aplicativo, como serão os estudos?

- Trilha de estudos: 56 aulas organizadas em uma sequência, do básico ao avançado.
- Explicações e exemplos: conteúdos em linguagem simples, com exemplos de código para facilitar o entendimento.
- Leitura de código linha por linha: nos desafios e projetos, cada linha do código vem com uma explicação de como lê-la e interpretá-la em voz alta, usando os nomes reais de cada coisa (método, parâmetro, lista, `if`, `for`, `JOIN`...). Ajuda a entender o que o algoritmo faz passo a passo, sem decorar.
- Quizzes: mais de 500 perguntas para testar o que você aprendeu, incluindo perguntas de achar o bug, completar a lacuna e as que um recrutador faria em uma vaga júnior.
- Anotações: espaço para escrever o que entendeu com suas próprias palavras.
- Desafios e projetos: exercícios para praticar lógica e desenvolver o raciocínio.
- Pensar como dev, do problema à decisão: trilha para treinar o que as empresas avaliam em um teste técnico. Entender o problema, ler um projeto que você não escreveu, diagnosticar melhorias, decidir entre opções, comandar a IA com o raciocínio de negócio e explicar com termos técnicos como pensou e por que escolheu aquele caminho.
- Acompanhamento: o aplicativo salva seu progresso e mostra onde você parou.
- Backup do progresso: exporte seu progresso em um arquivo JSON e importe de volta, para guardar uma cópia ou levar para outro aparelho.


## Temas abordados

**Iniciante**
- Fundamentos de Java e lógica de programação.
- Variáveis, tipos de dados, condições, repetições, loops e arrays.
- Programação orientada a objetos: classes, objetos, encapsulamento, herança, polimorfismo.
- Conhecendo a JVM e o IntelliJ IDEA.

**Intermediário**
- Estruturas de dados e desafios de lógica.
- Projetos práticos com Java.
- APIs, REST, JSON e DTO, banco de dados, Git e GitHub, arquitetura em camadas (MVC).
- Spring Boot, JPA e organização de projetos.
- Testes e conceitos de Java moderno.

**Avançado**
- Entender o que acontece por trás de uma aplicação.
- Memória, threads, banco de dados e transações.
- Boas práticas, arquitetura, segurança e desempenho.
- Docker e CI/CD.

**Pensar como dev, do problema à decisão**
- Entender o problema antes de programar.
- Ler um projeto que você não escreveu.
- Diagnosticar melhorias.
- Decidir entre opções e justificar a escolha.
- Comandar a IA com o raciocínio de negócio.
- Explicar com termos técnicos como pensou e por que escolheu aquele caminho.

**Carreira**
- Preparação para oportunidades como desenvolvedora e uso da inteligência artificial como apoio nos estudos e no desenvolvimento.
- Raciocínio de negócio: entender o problema, avaliar opções, decidir e explicar a decisão, como em um teste técnico.
- Treino de teste técnico: um mini-desafio com enunciado ambíguo, gabarito e rubrica de autoavaliação.
- Entrevista: perguntas de entrevista com resposta-modelo e um roteiro de live coding para pensar em voz alta.

## O que foi atualizado

- **Quiz difícil de chutar:** as alternativas das 524 perguntas foram revisadas para a certa não se entregar pelo tamanho. Ela passou de ser a mais longa em 69% das perguntas para 24%.
- **Consultar antes de responder:** no modo treino, um botão mostra a dica, os pontos-chave e os termos da aula.
- **Escrever a resposta:** opção de responder com as próprias palavras, sem ver as alternativas. A correção é automática, por palavras-chave (não é IA) e pode errar, por isso há um botão para contestar.
- **Voltar à aula:** depois de treinar o que errou no quiz de uma aula, o botão "Voltar à aula e anotar" continua na tela de resultado.
- **Correções:** voltar do resultado não conta a mesma rodada duas vezes, e tipos como `<String>` voltaram a aparecer nas perguntas.
- **Backup do progresso:** exportar e importar em arquivo JSON, com migração de versão que preserva seus dados. Importar pede confirmação e recusa arquivo inválido.
- **Revisão técnica do conteúdo:** exemplos de código que agora compilam, fatos corrigidos (LAZY, CORS, índice, `binarySearch`, BCrypt e outros), configurações que não vazam senha e textos mais claros nas aulas, na leitura linha por linha e no quiz.
- **Quiz:** agora com 524 perguntas. Entraram perguntas de achar o bug, completar a lacuna e de entrevista júnior (`equals`, `==` com texto, `finally`, `@Transactional`, SQL Injection, entre outras). Perguntas repetidas foram trocadas por perguntas novas.
- **Carreira e teste técnico:** mini-desafio com gabarito e rubrica, perguntas de entrevista com resposta-modelo e roteiro de live coding. A aula do caso completo foi corrigida e ganhou um achado novo sobre e-mail duplicado em requisições simultâneas.
- **Aula de Testes:** o "Veja acontecer" mostra um exemplo que passa (verde) e um que falha (vermelho), explicando o motivo de cada um, e o exemplo do frete traz as classes que ele usa.
- **Aula de Docker:** o `docker compose` espera o banco ficar pronto antes de subir a API.

## Tecnologias utilizadas

| Tecnologia | Para que serve |
|---|---|
| HTML | Estrutura das páginas |
| CSS | Aparência, cores e adaptação para celular e computador |
| JavaScript (puro) | Funcionamento das aulas, quizzes, anotações e revisão |
| localStorage | Armazenamento do progresso e das anotações no próprio navegador (com backup em arquivo JSON) |
| PWA | Permite instalar o app e usar alguns recursos mesmo sem internet |
| Git e GitHub | Controle das alterações e publicação do projeto |

> O conteúdo foi criado com apoio de inteligência artificial e ainda está em revisão. Pode haver imprecisões.
