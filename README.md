![GitHub](https://img.shields.io/github/license/giupolub/Tasks)
# Tasks

Projeto elaborado com a função de criar uma lista de tarefas.

## 🔨 Funcionalidades do projeto

Este projeto foi elaborado com o Navigation Drawer, um painel lateral que mostra o menu de navegação principal do aplicativo. Para acessar este menu, basta tocar o ícone na barra de aplicativos ou passar o dedo na borda esquerda da tela.

Outras funcionalidades importantes utilizadas foram: o `ROOM`, que basicamente é uma biblioteca que facilita o acesso e manuseio do banco de dados `SQLite`; `consumo de API` em quase todas as atividades presentes no aplicativo, como o login e a manipulação das tarefas; e o `RetroFit`, que é uma camada de abstração para chamadas a API, ou seja, fornece um padrão simples de implementação para transmissão de dados entre aplicativo e servidor.

### Uso do aplicativo

Primeiramente é necessário criar uma conta através do atalho "Cadastre-se" no rodapé da tela inicial. A área de registro será iniciada e nela o usuário deverá fornecer o nome, um e-mail e uma senha. Ao selecionar o botão "CADASTRAR" os dados serão salvos e a tela de login reabrirá. Dessa vez, basta digitar os dados e efetuar o login.

![giftaskslogin](https://user-images.githubusercontent.com/110063157/182977278-698abba5-6e89-40ac-b399-85f8766dc442.gif)

Uma vez dentro do aplicativo o usuário poderá criar as tarefas, para isso, basta selecionar o atalho :heavy_plus_sign: e fornecer os dados solicitados: descrição, prioridade e a data.

![giftasksnewtask](https://user-images.githubusercontent.com/110063157/182977317-1e08b974-06fe-4aa6-85bb-ab880cbeb6c9.gif)

Uma vez de volta à tela principal (que armazena todas as tarefas) o usuário poderá selecionar o :radio_button: para registrar se a tarefa foi concluída, poderá também selecionar aquela tarefa que ele deseja editar ou pressionar para fazer uma remoção. Para acessar as demais telas (fragments) ou sair do aplicativo, basta entrar no menu lateral.

![giftaskslogout](https://user-images.githubusercontent.com/110063157/182977336-f37395e9-0f19-43b0-b599-6616e5d99f91.gif)

## ✔️ Técnicas e tecnologias utilizadas

Tecnologias:

- [Kotlin](https://kotlinlang.org/)
- [Android Studio](https://developer.android.com/studio?hl=pt&gclid=Cj0KCQjwio6XBhCMARIsAC0u9aFcStoZloea7hLJnt5StTOh7VHBqr15T1HpjgvOY00QfByC4676HYAaAmxmEALw_wcB&gclsrc=aw.ds)

Técnicas:

- `MVVM`: padrão de arquitetura com divisão de responsabilidades entre as classes
- `ROOM`: camada de abstração de acesso ao banco de dados
- `RetroFit`: camada de abstração para chamadas a API
- `Consumo de API`: transmissão de dados entre aplicativo e servidor remoto
- `Shared preferences`: dados armazenados e reutilizados
- `BiometricPrompt`: autenticação biométrica
- `Navigation Drawer`: painel lateral que mostra o menu de navegação principal do aplicativo
- `Fragment`: representa uma parte reutilizável da IU do seu app
- `View Binding`: busca de views do layout de forma segura
- `AlertDialog`: yma subclasse de diálogo que pode exibir um, dois ou três botões
- `Toast notification`: um aviso fornecendo um feedback simples sobre uma operação em uma pequena janela pop-up
- `startActivity`: navegação entre activities e fragments
- `Intent e Bundle`: para navegar entre as activities com parâmetros previamente estabelecidos
- `RecycleView`: lista que mostra grandes conjuntos de dados na IU enquanto minimiza o uso de memória
- `Adapter e ViewHolder`: necessários para a criação da RecycleView
- `LiveData`: diferente de um observável comum, o LiveData conta com reconhecimento de ciclo de vida, ou seja, ele respeita o ciclo de vida de outros componentes do app, como ativities e fragments
- `Singleton`: é um padrão de projeto de software, ele garante a existência de apenas uma instância de uma classe, mantendo um ponto global de acesso

## 📁 Acesso ao projeto

Você pode [acessar o código fonte do projeto inicial](https://github.com/giupolub/Tasks) ou [baixá-lo](https://github.com/giupolub/Tasks/archive/refs/heads/main.zip).

## 🛠️ Abrir e rodar o projeto

Após baixar o projeto, você pode abrir com o Android Studio. Para isso, na tela de launcher clique em:

- **Open project**
- Procure o local onde o projeto está e o selecione (caso o projeto seja baixado via zip, é necessário extraí-lo antes de procurá-lo)
- Por fim clique em OK

O Android Studio deve executar algumas tasks do Gradle para configurar o projeto, aguarde até finalizar. Ao finalizar as tasks, você pode executar o App 🏆
