# 🚀 SmartQuote - Hackathon RCS

<div align="center">
  <img src="./RCS.png" alt="RCS Logo" width="100" height="100" />
  
  **Sistema Inteligente de Gestão de Cotações com IA**
  
  [![Node.js](https://img.shields.io/badge/Node.js-18.0+-green.svg)](https://nodejs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue.svg)](https://www.typescriptlang.org/)
  [![React](https://img.shields.io/badge/React-18.3.1-blue.svg)](https://reactjs.org/)
  [![Python](https://img.shields.io/badge/Python-3.10+-yellow.svg)](https://www.python.org/)
  [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
</div>

## 📋 Sobre o Projeto

Este repositório contém **três componentes paralelos** que constituem o sistema completo SmartQuote, uma solução inovadora de gestão de cotações desenvolvida para a RCS Angola. Cada componente está em seu próprio diretório e pode ser executado independentemente.

### Credenciais de Acesso para Avaliação

```
Email: teste@rcs.com
Senha: Teste123@
```

## 🗂️ Estrutura do Repositório

Este repositório contém três subrepositórios paralelos:

```
hackathon-smartquote/
├── frontend_repo/       # Interface do usuário em React
├── backend_repo/        # API REST em Node.js/TypeScript
└── smartQuote-python/   # API Python de busca com IA
```

## 🌐 Componentes do Sistema

### 1. Frontend (frontend_repo)

Interface do usuário moderna e responsiva desenvolvida com React, TypeScript e Tailwind CSS.

**Principais Características:**
- 🤖 **IA Integrada** - Busca automática de produtos e sugestões inteligentes
- 📊 **Dashboard Analytics** - Métricas em tempo real e relatórios detalhados
- 🔒 **Sistema de Permissões** - Controle de acesso baseado em funções
- 📱 **Responsivo** - Interface adaptável para desktop, tablet e mobile
- 🔄 **Tempo Real** - Notificações e atualizações instantâneas
- 📄 **Exportação** - Relatórios em PDF, Excel e CSV

[Saiba mais sobre o Frontend](./frontend_repo/README.md)

### 2. Backend (backend_repo)

API RESTful desenvolvida em Node.js e TypeScript, responsável por gerenciar as principais funcionalidades do SmartQuote.

**Principais Características:**
- 🔐 **Autenticação** - Sistema de login e gerenciamento de usuários com tokens
- 📦 **Gerenciamento de Cotações** - CRUD completo para cotações e itens
- 🔍 **Busca de Produtos** - Busca interna e externa via API Python
- 🔄 **Integração com Dynamics** - Sincronização com Microsoft Dynamics ERP
- 📧 **Monitoramento de E-mail** - Worker para processar cotações automaticamente
- 🤖 **IA Generativa** - Integração com Google Gemini para interpretação de dados
- 🔔 **Notificações** - Sistema para alertar usuários sobre eventos importantes
- 📊 **Relatórios** - Geração de relatórios em XLSX e CSV

[Saiba mais sobre o Backend](./backend_repo/README.md)

### 3. API Python (smartQuote-python)

API Flask independente para processamento de interpretações e busca híbrida de produtos.

**Principais Características:**
- 🏗️ **Arquitetura Desacoplada** - API Python independente da API Node.js
- 🚀 **Deploy Isolado** - Pode ser hospedada em qualquer servidor/cloud
- ⚡ **Escalabilidade Horizontal** - Múltiplas instâncias com load balancing
- 🔄 **Zero Dependências** - Apenas Weaviate, Supabase e GROQ
- 📊 **Sistema de Auditoria** - Rastreabilidade completa de todas as análises e decisões
- 🔍 **Busca Híbrida** - Combinação de busca vetorial e textual para resultados precisos

[Saiba mais sobre a API Python](./smartQuote-python/README.md)

## 🚀 Início Rápido

### Configuração Completa

1. **Clone o repositório**
   ```bash
   git clone https://github.com/smartquote-rcs/hackathon-smartquote.git
   cd hackathon-smartquote
   ```

2. **Configure cada componente**
   
   Siga as instruções de instalação em cada README específico dos componentes:
   - [Instruções do Frontend](./frontend_repo/README.md)
   - [Instruções do Backend](./backend_repo/README.md)
   - [Instruções da API Python](./smartQuote-python/README.md)


## 🏢 Sobre a RCS

A **RCS** é uma empresa líder em soluções tecnológicas em Angola, oferecendo:

- 💼 **Consultoria em TI**
- 🖥️ **Soluções de Hardware**
- ☁️ **Serviços em Nuvem**
- 🔧 **Suporte Técnico 24/7**

### 📞 Contato

- **Website**: [https://smartquote-rcs-front-end.onrender.com/](https://smartquote-rcs-front-end.onrender.com/)

### 📍 Localização


<div align="center">
  <strong>Desenvolvido por Devs da 42 Luanda</strong>
  <br />
  <small>© 2025 RCS Angola. Todos os direitos reservados.</small>
</div>