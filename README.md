# 🌦 Previsão do Tempo - São Paulo

## 📌 Sobre o Projeto

Este é um projeto acadêmico desenvolvido para buscar a previsão do tempo de São Paulo usando **Python** e a biblioteca **Selenium**. O aplicativo tem uma interface simples criada com **Tkinter**, onde o usuário pode atualizar a previsão do tempo (temperatura e umidade) em tempo real. As informações são então salvas em um arquivo **Excel** para registro.

## 🛠 Tecnologias Utilizadas

- **Python**  
- **Selenium** (para automação de navegação e coleta de dados da web)  
- **Tkinter** (para a interface gráfica)  
- **Openpyxl** (para manipulação de arquivos Excel)  
- **Google Search** (para buscar informações sobre o clima)  

## 📄 Funcionalidade

O programa abre um navegador **Chrome** e pesquisa a previsão do tempo para São Paulo no Google. Ele extrai a **temperatura** e a **umidade** e exibe as informações para o usuário. Essas informações são salvas automaticamente em uma planilha **Excel**, incluindo a **data**, **hora**, **temperatura** e **umidade**.

## 🚀 Como Usar

1. Clone o repositório:

   ```bash
   git clone https://github.com/SeuUsuario/Previsao-Do-Tempo.git

2. Instale as dependências necessárias:

   ```bash
   pip install selenium openpyxl

3. Execute o arquivo Python para iniciar a interface gráfica:

   ```bash
   python app.py

4. Clique no botão "Buscar previsão" para atualizar as informações de temperatura e umidade, que serão salvas automaticamente em um arquivo captacao.xlsx.

## 📊 Exemplo de Planilha Excel
Após a execução do programa, a planilha captacao.xlsx será atualizada com os seguintes dados:

| DATA       | HORA    | TEMPERATURA (°C) | UMIDADE (%) |
|------------|---------|------------------|-------------|
| 2025-02-21 | 14:30:00| 28°C             | 60%         |
| 2025-02-21 | 15:00:00| 29°C             | 55%         |
