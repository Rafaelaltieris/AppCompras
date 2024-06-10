# AppCompras

AppCompras é um aplicativo de gerenciamento de compras desenvolvido usando .NET MAUI e o padrão MVVM. Este aplicativo permite que os usuários criem, editem e visualizem listas de compras de forma simples e intuitiva.

## Funcionalidades

- **Cadastro de Produtos**: Adicione novos produtos à sua lista de compras.
- **Edição de Produtos**: Edite informações dos produtos existentes.
- **Visualização de Lista**: Veja todas as listas de compras salvas.
- **Marcação de Itens**: Marque os itens como comprados.
- **Persistência de Dados**: Dados salvos localmente para acesso offline.

## Estrutura do Projeto

O projeto segue a arquitetura MVVM (Model-View-ViewModel) para separar a lógica de negócios da interface do usuário, facilitando a manutenção e escalabilidade.

- **Models**: Contêm as definições das entidades e a lógica de negócios.
- **Views**: Contêm as definições da interface do usuário.
- **ViewModels**: Contêm a lógica de apresentação e atuam como um intermediário entre os Models e as Views.

## Requisitos

- [.NET 8.0 ou superior](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) com a carga de trabalho "Desenvolvimento de aplicativos móveis com .NET"

## Instalação

1. Clone este repositório:
    ```sh
    git clone https://github.com/seuusuario/AppCompras.git
    cd AppCompras
    ```

2. Abra a solução no Visual Studio:
    ```sh
    start AppCompras.sln
    ```

3. Restaure os pacotes NuGet:
    ```sh
    dotnet restore
    ```

4. Compile o projeto:
    ```sh
    dotnet build
    ```

5. Execute o projeto:
    - Para Windows:
      ```sh
      dotnet run --framework net7.0-windows
      ```
    - Para Android:
      ```sh
      dotnet build -t:Run -f net7.0-android
      ```
    - Para iOS (em um Mac):
      ```sh
      dotnet build -t:Run -f net7.0-ios
      ```

## Utilização

- **Adicionar Produto**: Clique no botão "Adicionar Produto" na tela principal e preencha os detalhes.
- **Editar Produto**: Clique em um produto na lista para editar suas informações.
- **Marcar Produto Como Comprado**: Marque a caixa de seleção ao lado de um produto para sinalizar que foi comprado.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
