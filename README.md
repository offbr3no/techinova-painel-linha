# 🏭 Painel da Linha 3 - TechInova

O **Painel da Linha 3** é uma aplicação web desenvolvida para monitorar e exibir em tempo real a leitura dos sensores industriais instalados na Linha 3 da fábrica da TechInova.

---

## 🎯 Sobre o Projeto

A solução oferece uma interface intuitiva para visualização de alertas, acompanhamento de telemetria e integração com corretores de mensagens industriais (MQTT), permitindo monitorar métricas como vibração do eixo principal e estado geral dos equipamentos.

---

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estruturação da interface web.
- **CSS3:** Estilização e layout responsivo do painel.
- **JavaScript (ES6+):** Lógica de consumo de dados, conversão de medições e manipulação do DOM.
- **MQTT Broker:** Comunicação e recepção de dados em tempo real dos sensores.

---

## 📁 Estrutura do Repositório

```text
├── .github/      # Workflows e verificações automáticas
├── config/       # Configurações de acesso ao broker MQTT
├── css/          # Estilos e parametrização visual da aplicação
├── dados/        # Arquivos de cadastro e configuração dos sensores
├── js/           # Funções de conversão e lógica de negócios
├── index.html    # Interface principal do painel
└── RESPOSTAS.md  # Formulário e registro de relatórios/missões
