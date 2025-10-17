```mermaid
flowchart TD
    A(["Entrar"])
    A --> B{"Decidir pedido"}
    B --> C["Adicionar o pedido no carrinho"]
    B --> D["Sair do aplicativo"]
    C --> F{"Realizar pagamento"}
    F --> G["Pagamento confirmado"]
    F --> H["Pagamento NÃO APROVADO."]
    G --> I["Esperar pedido"]
    I --> J["Buscar pedido"]
