# Sistema de Gestão de Clientes

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![CustomTkinter](https://img.shields.io/badge/CustomTkinter-5.2.1-orange)
![OpenPyXL](https://img.shields.io/badge/OpenPyXL-3.0.10-green)

Um aplicativo de desktop desenvolvido em Python para cadastrar e gerenciar clientes. Os dados são armazenados em uma planilha Excel, e a interface gráfica foi criada usando a biblioteca **CustomTkinter**, que permite temas personalizáveis (Light, Dark, System).

---

## 📋 Descrição

O **Sistema de Gestão de Clientes** é uma aplicação desktop que permite cadastrar clientes, armazenar seus dados em uma planilha Excel e validar as entradas do usuário. O sistema foi desenvolvido com foco em uma interface moderna e intuitiva, utilizando a biblioteca **CustomTkinter** para a criação da interface gráfica.

---

## 🚀 Funcionalidades

- **Cadastro de Clientes**:
  - Campos: Nome, Contato, Idade, Gênero, Endereço, Orçamento e Observações.
- **Armazenamento em Excel**:
  - Os dados são salvos automaticamente em uma planilha Excel (`Clientes.xlsx`).
- **Validação de Campos**:
  - Verifica se todos os campos obrigatórios foram preenchidos antes de salvar.
- **Limpeza de Campos**:
  - Limpa todos os campos após o cadastro.
- **Temas Personalizáveis**:
  - Alterna entre temas Light, Dark e System.
- **Interface Moderna**:
  - Design limpo e responsivo, com uso de componentes modernos do CustomTkinter.

---

## 🛠️ Tecnologias Utilizadas

- **Python** (versão 3.8 ou superior)
- **CustomTkinter** (para a interface gráfica)
- **OpenPyXL** (para manipulação de arquivos Excel)
- **Tkinter** (para funcionalidades básicas de interface)
- **Pathlib** (para manipulação de caminhos de arquivos)

---

## 📸 Capturas de Tela

### Tela Principal
![image](https://github.com/user-attachments/assets/7a33d092-a4d6-4512-ad88-5201fd339a9e)

### Tema Dark
![image](https://github.com/user-attachments/assets/b071c04e-b623-42c7-a9ce-cb22e9661e1a)

### Tema Light
![image](https://github.com/user-attachments/assets/c31e9593-0eb7-46b4-b0e0-a57c79a03f1e)

### Planilha Gerada
![image](https://github.com/user-attachments/assets/fa8f1775-ae43-420d-a270-133de2bcb771)

![image](https://github.com/user-attachments/assets/4fefcb3a-4def-43eb-8f5d-b69f91e1e486)

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos
- Python 3.8 ou superior instalado.
- Bibliotecas necessárias instaladas (veja abaixo).

### Passo a Passo

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/sistema-gestao-clientes.git
   cd sistema-gestao-clientes
   ```

2. **Crie um ambiente virtual** (opcional, mas recomendado):
   ```bash
   python -m venv venv
   ```

   - No Windows:
     ```bash
     venv\Scripts\activate
     ```
   - No Linux/Mac:
     ```bash
     source venv/bin/activate
     ```

3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute o projeto**:
   ```bash
   python app.py
   ```

---

## 📂 Estrutura do Projeto

```
sistema-gestao-clientes/
sistema-gestao-clientes/
├── app.py                  # Código principal do aplicativo
├── Clientes.xlsx           # Planilha gerada pelo sistema
├── requirements.txt        # Lista de dependências
├── README.md               # Este arquivo
```

---

## 📝 Como Usar

1. **Preencha os Campos**:
   - Insira os dados do cliente nos campos: Nome, Contato, Idade, Gênero, Endereço, Orçamento e Observações.

2. **Salve os Dados**:
   - Clique no botão **"Salvar dados"** para armazenar as informações na planilha Excel.

3. **Limpe os Campos**:
   - Clique no botão **"Limpar campos"** para apagar todos os dados inseridos.

4. **Altere o Tema**:
   - Use o menu suspenso no canto inferior esquerdo para alternar entre os temas Light, Dark e System.

---

## 📜 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🤝 Contribuição

Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adicionando nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

---

## 📧 Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- **Nome**: Allan Borges
- **E-mail**: allanborges@myyahoo.com
- **GitHub**: https://github.com/allan-felipe23
---
