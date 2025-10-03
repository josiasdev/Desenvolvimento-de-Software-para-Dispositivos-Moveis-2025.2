# Desenvolvimento de Software para Dispositivos Móveis - 2025.2
**Universidade Federal do Ceará (UFC) - Campus Quixadá**

## Justificativa

Os dispositivos móveis são uma parte integral e onipresente em nosso cotidiano. O mercado de software mobile continua em franca expansão, gerando uma demanda constante por profissionais altamente qualificados. Segundo projeções de mercado, o faturamento e o número de downloads de aplicativos continuam a crescer exponencialmente, mas esse crescimento ainda enfrenta o desafio da escassez de desenvolvedores especializados.

Esta disciplina foi projetada para capacitar os alunos a se aprofundarem em uma das áreas mais relevantes da engenharia de software, abordando os requisitos, restrições e padrões de arquitetura que demandam um tratamento diferenciado no desenvolvimento para plataformas móveis.

## Objetivos da Disciplina

#### Objetivos Gerais
Apresentar os conceitos fundamentais do desenvolvimento de software para dispositivos móveis, abordando desde os desafios de requisitos e arquitetura até os mecanismos de comunicação e as principais plataformas. Durante o curso, conceitos de **Computação Ubíqua e Pervasiva** serão introduzidos. A parte prática da disciplina será focada no ecossistema de desenvolvimento **Android Nativo com Kotlin**.

## Ementa

1.  **Visão Geral sobre Dispositivos Móveis:**
    * Comparativo entre dispositivos de sensoriamento, smartphones, tablets e computadores convencionais.
2.  **Ecossistemas de Desenvolvimento Móvel:**
    * Análise das principais plataformas: Android (Kotlin), iOS (Swift) e frameworks multiplataforma.
3.  **Requisitos e Desafios para Computação Móvel:**
    * Gerenciamento de recursos, conectividade intermitente, diversidade de hardware e usabilidade.
4.  **Arquitetura de Software Móvel:**
    * Padrões de projeto, componentização e arquiteturas reativas.
5.  **Comunicação para Software Móvel:**
    * Consumo de APIs RESTful, WebSockets e estratégias de sincronização de dados.
6.  **Middleware e Frameworks para Computação Móvel.**
7.  **Sensibilidade ao Contexto e Adaptação:**
    * Uso de sensores, localização e personalização da experiência do usuário.
8.  **A Plataforma Android com Kotlin:**
    * **Componentes Essenciais:** `Activities`, `Services`, `Broadcast Receivers`.
    * **Navegação e Comunicação:** `Intents` e `Navigation Component`.
    * **Interfaces de Usuário:** `Jetpack Compose`, `Layouts` e gerenciamento de estado.
    * **Recursos do Dispositivo:** Localização, Mapas e Sensores.

## plano meticulosamente estruturado para o curso, dividido em unidades distintas para facilitar o aprendizado e o desenvolvimento do projeto.


### Unidade 1 - Fundamentos de Desenvolvimento Android com Kotlin e Compose
* **Introdução:** Histórico da plataforma Android, sua arquitetura e o ecossistema moderno.
* **Ambiente de Desenvolvimento:** Configuração do Android Studio, Gradle e Android Virtual Device (AVD).
* **Estrutura de um Projeto:** Análise do `build.gradle`, `AndroidManifest.xml` e organização de recursos (`res`).
* **Componentes Fundamentais:** `Activities`, `Intents` e o ciclo de vida de um app.
* **Interfaces Gráficas Modernas:** Introdução à UI declarativa com **Jetpack Compose**, gerenciamento de estado e a `View API` para interoperabilidade.

### Unidade 2 - Arquitetura de Aplicativos e Navegação
* **Arquitetura de Software:** Implementação do padrão **MVVM (Model-View-ViewModel)** para criar apps robustos e testáveis.
* **Navegação:** Gerenciamento de fluxos de telas e passagem de dados utilizando o **Jetpack Navigation Compose**.

### Unidade 3 - Persistência de Dados e Conectividade
* **Armazenamento Local:**
    * **DataStore:** Persistência de dados simples (chave-valor) de forma assíncrona.
    * **Room Database:** Abstração sobre o SQLite para armazenamento de dados estruturados.
* **Processamento Assíncrono:** Utilização de **Kotlin Coroutines** para executar tarefas em segundo plano sem bloquear a thread principal.
* **Integração com Serviços Remotos:** Consumo de APIs RESTful utilizando bibliotecas como Retrofit e Ktor.

### Unidade 4 - Sensibilidade ao Contexto e Recursos Avançados
* **Recursos de Hardware:** Integração com APIs de GPS, câmera e outros sensores do dispositivo.
* **Notificações:** Engajamento do usuário com notificações locais e push.
* **Trabalho em Background:** Execução de tarefas de longa duração com `Services` e agendamento de tarefas com `Broadcast Receivers`.
