# kontrole-app
Código fonte kontrole TCC - Engenharia Software
# Kontrole - Aplicativo de Controle Financeiro Pessoal

O **Kontrole** é um aplicativo de controle financeiro pessoal projetado para ajudar os usuários a gerenciar suas finanças de forma eficiente. O aplicativo permite o registro de transações financeiras, a definição de orçamentos mensais, e a geração de relatórios com gráficos para análise de desempenho financeiro ao longo do tempo. Este projeto foi desenvolvido com foco em usabilidade, segurança e flexibilidade, com o objetivo de fornecer uma solução acessível para indivíduos e famílias que buscam organizar suas finanças pessoais.

## Funcionalidades

- **Registro de Transações**: O usuário pode registrar receitas e despesas, categorizando-as para facilitar o controle financeiro.
- **Gestão de Orçamentos**: Permite a definição de orçamentos mensais para diferentes categorias de gastos, com alertas e lembretes para ajudar os usuários a manterem-se dentro do orçamento.
- **Relatórios Financeiros**: O aplicativo gera gráficos interativos (como gráficos de pizza) para visualizar as despesas e tendências financeiras ao longo do tempo.
- **Segurança**: Implementação de medidas de segurança, como criptografia de dados, para proteger as informações financeiras dos usuários.
- **Interface Intuitiva**: O design é focado na simplicidade e facilidade de uso, com uma interface amigável tanto para Android quanto para iOS.

## Tecnologias Utilizadas

### Android
- **Kotlin**: Linguagem de programação principal para desenvolvimento Android.
- **MPAndroidChart**: Biblioteca para gerar gráficos (usada para relatórios financeiros).
- **SQLite/Room**: Para armazenamento local de dados financeiros.

### iOS
- **Swift**: Linguagem de programação principal para desenvolvimento iOS.
- **Charts**: Biblioteca para gerar gráficos (usada para relatórios financeiros).
- **CoreData/UserDefaults**: Para armazenamento local de dados financeiros.

### Backend (Opcional)
- **Java + Spring Framework** (caso decida integrar um backend para sincronização de dados entre dispositivos ou autenticação de usuários).
- **MySQL**: Banco de dados relacional para armazenar dados financeiros.

## Como Executar o Projeto

### Requisitos

Antes de executar o projeto, você precisa ter os seguintes softwares instalados:

- **Android Studio** (para o projeto Android)
  - [Download Android Studio](https://developer.android.com/studio)
- **Xcode** (para o projeto iOS)
  - [Download Xcode](https://developer.apple.com/xcode/)
- **Homebrew** (para instalar o CocoaPods no macOS, necessário para o iOS)
  - [Homebrew](https://brew.sh/)
- **CocoaPods** (para gerenciar dependências do iOS)

### Android

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/kontrole-app.git
