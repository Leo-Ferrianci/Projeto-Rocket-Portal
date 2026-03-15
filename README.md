# 🚀 Portal de Gerenciamento de Tarefas  | Gestão Ágil e Comunicação Interna

![Bubble](https://img.shields.io/badge/Made_with-Bubble.io-1148d5?style=for-the-badge&logo=bubble&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)
![SPA](https://img.shields.io/badge/Architecture-SPA-8A2BE2?style=for-the-badge)

## 📌 Sobre o Projeto
É um MVP (*Minimum Viable Product*) corporativo B2B desenvolvido para solucionar gargalos operacionais e centralizar a comunicação de equipes em startups. O ecossistema integra a gestão de demandas em um modelo ágil (Kanban) a um mural de comunicação global, eliminando a dependência de múltiplas ferramentas desestruturadas.

A aplicação foi arquitetada utilizando o paradigma **No-Code/Low-Code**, priorizando a rápida validação do modelo de negócio com usuários reais, sem abrir mão da segurança, da integridade de um banco de dados relacional e da escalabilidade.

## 💻 Arquitetura e Tecnologias
* **Plataforma:** [Bubble.io](https://bubble.io/) (Desenvolvimento visual Full-Stack).
* **Frontend:** *Responsive Engine* (Flexbox) focado em usabilidade e design limpo.
* **Backend:** Banco de dados relacional nativo e estruturação de regras de privacidade (*Privacy Rules*).
* **Padrão Arquitetural:** SPA (*Single Page Application*) operada via *Custom States*, garantindo navegação instantânea e fluida sem recarregamento de página.

## ⚙️ Funcionalidades Principais
* **🔐 Controle de Acesso (RBAC):** Sistema de *Route Guard* para proteção de rotas privadas. A gestão de permissões utiliza o conceito de *Role-Based Access Control*, onde apenas perfis "Admin" possuem autorização no servidor para registrar novos membros.
* **📋 Kanban Dinâmico e Reativo:** Gerenciamento visual do fluxo de trabalho (`To Do`, `In Progress` e `Done`). As transições de cards nos workflows alteram o status diretamente no banco de dados e refletem em tempo real na interface.
* **💬 Mural Global:** Feed assíncrono para a equipe manter o alinhamento diário, reduzindo ruídos de comunicação entre as *squads*.
* **👥 Gestão de Time:** Painel de administração com listagem de membros e indicadores visuais de cargo.

## 🌐 Como Acessar e Testar

A aplicação está em produção e disponível para testes no ambiente *Live*:

🔗 **Acessar a Aplicação:** [http://leonardoferrianci-35335.bubbleapps.io](http://leonardoferrianci-35335.bubbleapps.io)

A senha e Usuário estão no arquivo da entrega

---
*Desenvolvido como projeto prático de Engenharia de Software aplicado ao ecossistema Low-Code.*
