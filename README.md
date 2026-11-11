FoodTruck Manager (JavaFX)

Um aplicativo desktop desenvolvido em JavaFX para o gerenciamento de pedidos, cardápio e controle de vendas de um Food Truck.

🚀 Funcionalidades

• Gerenciamento de Cardápio: Adicionar, editar, listar e remover itens do menu (lanches, bebidas, porções).
• Fila de Pedidos: Acompanhamento de pedidos em tempo real (Em preparo, Pronto, Entregue).
• Carrinho de Compras / PDV: Seleção de itens, cálculo automático de troco e total.
• Relatório de Vendas: Visualização do faturamento diário e quantidade de itens vendidos.
• Interface Moderna: Construida com FXML e estilizada com CSS via JavaFX.

🛠️ Tecnologias Utilizadas

• Java (JDK 17 ou superior)
• JavaFX (OpenJFX 17+)
• Maven (Gerenciador de dependências)
• Scene Builder (Para edição visual das telas FXML)
• SQLite / H2 (Banco de dados local embutido)

📋 Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:
• Java JDK 17+
• Maven
• IDE de sua preferência com suporte a JavaFX (IntelliJ IDEA, Eclipse ou NetBeans)

⚙️ Como Executar o Projeto

1. Clone o repositório:bash
git clone https://github.com
cd foodtruck-javafx
Use o código com cuidado.
2. Configure o JavaFX na sua IDE:
	• Se estiver usando o IntelliJ IDEA, configure o SDK do JavaFX em Project Structure e adicione as seguintes VM Options na sua configuração de execução:bash
--module-path /caminho/para/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml
Use o código com cuidado.
3. Execute o projeto via Maven:bash
mvn clean javafx:run
Use o código com cuidado.

📁 Estrutura de Pastas

text
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── foodtruck/
│   │           ├── controller/  # Controladores das telas (FXML)
│   │           ├── model/       # Classes de Domínio (Produto, Pedido, Cliente)
│   │           ├── dao/         # Camada de Acesso a Dados
│   │           └── Main.java    # Ponto de entrada da aplicação
│   └── resources/
│       ├── view/                # Arquivos de layout (.fxml)
│       ├── styles/              # Arquivos CSS da interface
│       └── db/                  # Scripts do banco de dados
└── test/                        # Testes unitários
Use o código com cuidado.

🤝 Como Contribuir

1. Faça um Fork do projeto.
2. Crie uma Branch para a sua feature (git checkout -b feature/nova-funcionalidade).
3. Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade').
4. Faça o Push para a branch (git push origin feature/nova-funcionalidade).
5. Abra um Pull Request.

📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar para fins educacionais ou comerciais.
Se você precisar ajustar algo específico — como conexão com banco de dados, integração com impressora térmica ou telas específicas —, é só me avisar que eu adapto o código ou o README!