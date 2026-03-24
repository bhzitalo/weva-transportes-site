# 🏗️ Arquitetura do Sistema – Weva Transportes

## 1. Introdução

Este documento apresenta a arquitetura proposta para o site institucional da Weva Transportes.

A arquitetura foi definida com foco em simplicidade, organização, facilidade de manutenção e compatibilidade com os requisitos do projeto acadêmico.

## 2. Tipo de Arquitetura

O sistema seguirá uma arquitetura de site estático, composta por páginas web desenvolvidas com HTML, CSS e JavaScript.

Essa abordagem foi escolhida por ser adequada ao objetivo do projeto, que é apresentar informações institucionais, serviços, frota e meios de contato da empresa.

## 3. Tecnologias Utilizadas

- **HTML5** para estruturação das páginas  
- **CSS3** para estilização e responsividade  
- **JavaScript** para interações e comportamentos dinâmicos  
- **GitHub** para versionamento e compartilhamento do projeto  

## 4. Estrutura do Sistema

O sistema será dividido em páginas independentes, cada uma com uma função específica.

### Páginas previstas

- **index.html** – Página inicial  
- **servicos.html** – Página com detalhamento dos serviços  
- **frota.html** – Página com informações sobre a frota  
- **sobre.html** – Página com história, missão, visão e valores  
- **contato.html** – Página com formulário e dados de contato  

## 5. Organização de Pastas

```text
/weva-transportes-site
├── README.md
├── docs/
│   ├── documentacao.md
│   ├── requisitos.md
│   ├── regras-de-negocio.md
│   ├── casos-de-uso.md
│   └── arquitetura.md
├── src/
│   ├── index.html
│   ├── servicos.html
│   ├── frota.html
│   ├── sobre.html
│   ├── contato.html
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
└── assets/
```

## 6. Componentes da Interface

A interface será composta pelos seguintes elementos principais:

### Header
Contém o logotipo da empresa e o menu de navegação.

### Banner principal
Apresenta a empresa de forma visual e objetiva.

### Seções de conteúdo
Exibição de serviços, frota, diferenciais e informações institucionais.

### Formulário de contato
Permite que o usuário envie mensagens e solicite orçamento.

### Footer
Contém informações de contato, redes sociais e direitos autorais.

## 7. Fluxo de Navegação

O fluxo de navegação do usuário ocorrerá da seguinte forma:

1. O usuário acessa a página inicial  
2. Navega pelo menu principal  
3. Visualiza serviços, frota e informações da empresa  
4. Acessa a página de contato  
5. Envia uma solicitação ou entra em contato via WhatsApp  

## 8. Responsividade

O sistema será desenvolvido de forma responsiva, permitindo boa visualização em:

- Smartphones  
- Tablets  
- Notebooks  
- Monitores desktop  

## 9. Manutenção e Escalabilidade

A organização em arquivos separados facilitará a manutenção do sistema.

No futuro, novas páginas, funcionalidades ou integrações poderão ser adicionadas sem comprometer a estrutura principal do projeto.

Exemplos de futuras expansões:
- Galeria de viagens  
- Página de depoimentos  
- Integração com mapa  
- Sistema de orçamento mais avançado  

## 10. Considerações Finais

A arquitetura proposta atende às necessidades do projeto por ser simples, funcional, organizada e adequada ao desenvolvimento de um site institucional acadêmico.

Ela também permite que o grupo trabalhe de forma colaborativa, com divisão clara entre documentação, estrutura visual e programação.