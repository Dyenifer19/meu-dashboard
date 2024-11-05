
Este projeto é uma página inicial de dashboard com um layout simples. Ele inclui um cabeçalho, um menu lateral, cartões de estatísticas e atividades recentes. O objetivo é fornecer uma estrutura básica que pode ser expandida e personalizada conforme necessário.

O projeto consiste nos seguintes arquivos:

1. **index.html**: O arquivo principal que contém a estrutura do dashboard.
2. **styles.css**: O arquivo de estilo (CSS) para personalizar a aparência do dashboard.

- **Cabeçalho (`header`)**:
  - Contém o título "Meu Dashboard".
  - Inclui uma barra de navegação com links: "Início", "Relatórios" e "Configurações".
  - Ícone de notificações com um badge indicando 5 notificações.

- **Menu Lateral (`aside`)**:
  - Um menu com 4 opções: "Início", "Relatórios", "Estatísticas", "Configurações".
  - Cada item do menu tem um ícone associado.

- **Conteúdo Principal (`main-content`)**:
  - **Cartões de Estatísticas**: Cada cartão representa uma categoria, como "Vendas", "Lucros", "Usuários" e "Visitas".
  - **Atividades Recentes**: Uma lista com algumas atividades recentes (ex: venda realizada, pedido cancelado, pagamento pendente), cada uma com um ícone de status.

- **Rodapé (`footer`)**:
  - Links para "Privacidade", "Termos de Uso" e "Contato".
  - Texto com o copyright da empresa.

Comentários do Código

- **Cabeçalho**:
  ```html
  <header class="header">
    <h1>Meu Dashboard</h1>
    <nav class="nav">
      <a href="#">Início</a>
      <a href="#">Relatórios</a>
      <a href="#">Configurações</a>
    </nav>
    <div class="notification-icon">
      🔔
      <span class="badge">5</span>
    </div>
  </header>
