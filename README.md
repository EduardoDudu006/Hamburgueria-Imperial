README: Projeto Hamburgueria Imperial

Este repositório contém o código-fonte para um projeto web que simula o site de uma hamburgueria artesanal localizada em Recife, a Hamburgueria Imperial. O site apresenta um design moderno, responsivo e focado na conversão de pedidos via WhatsApp.

🚀 Funcionalidades Principais

Página Inicial (Home): Banner de destaque com informações de contato, estatísticas de clientes e imagem ilustrativa.
Cardápio Completo: Lista de produtos organizada em grid, com preços, descrições detalhadas, selos de "Mais Vendido", "Novidade" e "Promoção". Todos os itens possuem links diretos para pedido via WhatsApp.
Seção Sobre Nós: Detalhes sobre a história da hamburgueria, ingredientes de qualidade e métodos de pagamento aceitos.
Chamada para Ação (CTA): Seção de destaque convidando o cliente a fazer o pedido.
Rodapé Detalhado: Informações de contato, horário de funcionamento e redes sociais.
Design Responsivo: Utiliza Flexbox e Grid CSS para garantir a visualização correta em dispositivos móveis e desktops.
Navegação Suave: Usa scroll-behavior: smooth para uma melhor experiência de navegação entre as seções.

🛠️ Tecnologias Utilizadas

O projeto é construído exclusivamente com tecnologias front-end básicas:
HTML5: Estrutura semântica da página.

CSS3: Estilização, layout (Flexbox/Grid), variáveis CSS (:root), e transições visuais.
Imagens Externas: Utiliza URLs de imagens do Unsplash e iStockphoto.

📁 Estrutura de Arquivos

A estrutura do projeto segue um padrão básico:
/hamburgueria-imperial/
├── index.html
├── style.css
└── /img/
    └── (Nenhuma imagem local; todas são links externos)
    
📖 Como Usar

Para visualizar o projeto, basta abrir o arquivo index.html em qualquer navegador web moderno. Não há necessidade de servidor web ou instalação de dependências.
Detalhes de Implementação
Variáveis CSS (:root): Define cores primárias, sombras e raios de borda para fácil manutenção e consistência visual.
Layout de Cardápio: A seção .menu-grid utiliza display: grid com repeat(auto-fit, minmax(300px, 1fr)) para criar um layout fluido e que se ajusta automaticamente à largura disponível. (p. 13)
Botões: Utiliza classes utilitárias (.btn, .btn-outline, .btn-light) para diferentes estilos de botões com efeitos de hover.

🖼️ Fontes das Imagens Utilizadas

Todas as imagens do projeto são referenciadas através de URLs externas de serviços como Unsplash e iStockphoto, garantindo alta qualidade e diversidade visual.
Seção/Produto	Fonte e URL de Exemplo
Home Hero	https://images.unsplash.com...
Duplo X-Bacon	https://images.unsplash.com...
X-Burger	https://images.unsplash.com...
Triplo X-Burger	https://images.unsplash.com...
Polvo Burger	https://images.unsplash.com...
Combo Especial	https://images.unsplash.com...
Batata Frita	https://media.istockphoto.com...
Coxinhas	https://media.istockphoto.com... 
MilkShake	https://images.unsplash.com...
Sucos	https://images.unsplash.com...
Sobre Nós	https://images.unsplash.com...
© Direitos Autorais
© 2026 - GV Burger - Todos os direitos reservados.
