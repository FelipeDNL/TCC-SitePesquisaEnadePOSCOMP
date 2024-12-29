# Plataforma Web de Auxílio de Discentes e Docentes

Esta é uma plataforma web desenvolvida para facilitar o estudo e a preparação para os exames POSCOMP e Enade. Oferece funcionalidades como pesquisa de questões, geração de simulados personalizados, relatórios de desempenho e muito mais.

Este é o repositório público do projeto. O site está disponivel para uso a partir do link https://tcc-site-33c66.web.app/.

![image](https://github.com/user-attachments/assets/71135bd0-82b6-43bb-971c-3a252d6c3572)


## 🚀 Funcionalidades

- Pesquisa detalhada de questões por ano, disciplina, dificuldade e tipo de prova.
- Criação de simulados personalizados.
- Feedback imediato sobre respostas e relatórios de desempenho detalhados.
- Interface intuitiva e responsiva.
- Gerenciamento de níveis de acesso (admin e usuário).
- Sincronização de dados em tempo real com Firebase.

## 🛠 Tecnologias Utilizadas

- **Frontend**: [React](https://react.dev) com suporte a componentes reutilizáveis e responsividade.
- **Backend**: [Firebase](https://firebase.google.com/), com Firestore para banco de dados NoSQL e Firebase Auth para autenticação.
- **Design e Protótipos**: [Figma](https://figma.com) para desenvolvimento de interfaces.
- **Gerenciamento de Projetos**: [Trello](https://trello.com) e metodologia Scrum.
- **Outras Ferramentas**: Typesense para buscas rápidas e Node.js para scripts de carregamento de dados.

## 🎯 Público-Alvo

- **Estudantes**: Facilita a prática e a revisão de conteúdos específicos para POSCOMP e Enade.
- **Professores**: Disponibiliza ferramentas para criar simulados e analisar o desempenho dos estudantes.

## 📂 Estrutura do Projeto

1. **Módulo de Autenticação do Usuário**:
   - Login seguro com Firebase Auth.
   - Registro de novos usuários com validações de segurança.
   - Recuperação de senha.

2. **Módulo de Questões**:
   - Cadastro e edição de questões para administradores.
   - Sincronização de questões com Typesense para busca eficiente.

3. **Módulo de Pesquisa e Simulados**:
   - Busca avançada por palavras-chave, tags, e filtros.
   - Geração de simulados personalizados.
   - Feedback e estatísticas detalhadas.

4. **Módulo de Relatórios e Desempenho**:
   - Dashboard de desempenho do usuário.
   - Gráficos dinâmicos para análise de acertos, erros e evolução ao longo do tempo.

## 🧪 Testes e Usabilidade

O sistema foi avaliado utilizando o **System Usability Scale (SUS)**, obtendo uma pontuação média de **86,9**, considerada excelente. Feedbacks dos usuários ajudaram a identificar melhorias e validar as funcionalidades.

---

Desenvolvido por **Felipe Davi do Nascimento Lopes**, **Lucas Oliveira Bleyer**, e **Edinilson da Silva Vida**.
