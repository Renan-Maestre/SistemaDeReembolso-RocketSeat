# 💰 Sistema de Reembolso - Rocketseat

Uma aplicação web moderna e responsiva para gerenciamento de despesas e solicitação de reembolsos, desenvolvida durante o curso Fullstack da Rocketseat.

![Sistema de Reembolso](./img/Captura%20de%20Tela%202025-11-01%20às%2008.39.40.png)

## 🚀 Sobre o Projeto

O Sistema de Reembolso é uma aplicação que permite aos usuários cadastrar suas despesas de forma organizada, categorizá-las e acompanhar o valor total de reembolsos solicitados. A aplicação oferece uma interface intuitiva e moderna para facilitar o controle financeiro corporativo.

### ✨ Funcionalidades

- ✅ **Cadastro de Despesas**: Adicione despesas com nome, categoria e valor
- 📊 **Categorização**: Organize despesas por categorias (Alimentação, Hospedagem, Transporte, Serviços, Outros)
- 💱 **Formatação Automática**: Valores em moeda brasileira (R$) com formatação automática
- 🗑️ **Remoção de Itens**: Remova despesas individualmente com um clique
- 📈 **Cálculo Automático**: Totalizador automático de valores e contador de despesas
- 📱 **Design Responsivo**: Interface adaptada para diferentes tamanhos de tela
- 🎨 **Interface Moderna**: Design clean e profissional

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna com Flexbox e Grid
- **JavaScript**: Funcionalidades interativas e manipulação do DOM
- **Google Fonts**: Tipografia Open Sans

## 📂 Estrutura do Projeto

```
SistemaDeReembolso-RocketSeat/
├── index.html              # Página principal
├── styles.css              # Estilos da aplicação
├── scripts.js              # Lógica JavaScript
└── img/                    # Recursos visuais
    ├── logo.svg            # Logo da aplicação
    ├── accommodation.svg    # Ícone hospedagem
    ├── food.svg            # Ícone alimentação
    ├── transport.svg       # Ícone transporte
    ├── services.svg        # Ícone serviços
    ├── others.svg          # Ícone outros
    ├── remove.svg          # Ícone remover
    └── chevron-down.svg    # Ícone dropdown
```

## 🎯 Como Usar

1. **Adicionar Despesa**:
   - Preencha o nome da despesa
   - Selecione a categoria correspondente
   - Digite o valor (formatação automática em R$)
   - Clique em "Adicionar despesa"

2. **Visualizar Despesas**:
   - Todas as despesas aparecem na lateral direita
   - Cada item mostra ícone da categoria, nome, categoria e valor
   - O total e contador são atualizados automaticamente

3. **Remover Despesa**:
   - Clique no ícone de lixeira ao lado da despesa
   - A despesa será removida e os totais atualizados

## 💻 Instalação e Execução

1. **Clone o repositório**:
```bash
git clone https://github.com/Renan-Maestre/SistemaDeReembolso-RocketSeat.git
```

2. **Navegue até o diretório**:
```bash
cd SistemaDeReembolso-RocketSeat
```

3. **Abra o projeto**:
   - Abra o arquivo `index.html` no seu navegador preferido
   - Ou use um servidor local como Live Server (VS Code)

## 🎨 Características do Design

### 🎨 Paleta de Cores
- **Verde Principal**: `#1f8459` - Botões e elementos ativos
- **Verde Claro**: `#2cb178` - Hover states
- **Fundo**: `#e4ece9` - Background principal
- **Cards**: `#f9fbfa` - Background dos cards
- **Texto Principal**: `#1f2523`
- **Texto Secundário**: `#4d5c57`

### 📱 Responsividade
- **Desktop**: Layout em duas colunas (formulário + lista)
- **Tablet**: Adaptação de fontes e espaçamentos
- **Mobile**: Layout em coluna única com header empilhado

## 🔧 Funcionalidades Técnicas

### JavaScript Features
- **Formatação de Moeda**: Conversão automática para formato brasileiro
- **Validação de Formulário**: Campos obrigatórios e validações
- **Manipulação do DOM**: Criação dinâmica de elementos
- **Event Listeners**: Gerenciamento de eventos de forma eficiente
- **Cálculos Dinâmicos**: Atualização automática de totais

### CSS Features
- **Flexbox Layout**: Sistema de layout flexível
- **Custom Properties**: Variáveis CSS para consistência
- **Transitions**: Animações suaves nos elementos
- **Media Queries**: Responsividade para diferentes dispositivos
- **Custom Scrollbar**: Barra de rolagem personalizada

## 📚 Aprendizados

Este projeto foi desenvolvido como parte do curso Fullstack da Rocketseat e aborda conceitos fundamentais:

- Manipulação avançada do DOM
- Formatação de dados (moeda brasileira)
- Responsividade e design mobile-first
- Organização de código JavaScript
- Estruturação de projetos frontend
- Boas práticas de HTML semântico
- CSS moderno com variáveis e flexbox

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais como parte do curso da Rocketseat.

## 👨‍💻 Desenvolvedor

**Renan Maestre**
- GitHub: [@Renan-Maestre](https://github.com/Renan-Maestre)

---

<p align="center">
  Desenvolvido com 💚 durante o curso Fullstack da <strong>Rocketseat</strong>
</p>
