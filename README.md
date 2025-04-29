# 🧾 Automação de Credenciais para Idosos e PNE

Este projeto foi desenvolvido por mim durante o meu estágio na prefeitura, com o objetivo de automatizar o processo de criação de credenciais para **idosos** e **pessoas com necessidades especiais (PNE)**. O sistema visa otimizar o tempo gasto na geração manual dessas credenciais, integrando dados de uma planilha Excel e gerando automaticamente documentos no formato Word prontos para impressão.

## 📌 Funcionalidades

- 📥 Leitura de dados de uma planilha Excel (`controle.xlsx`) contendo informações dos solicitantes.
- 🖨️ Geração automática de credenciais personalizadas em formato Word, utilizando os modelos `modelo_idoso.docx` e `modelo_pne.docx`.
- 🗃️ Armazenamento e controle eficiente dos registros processados.

## 🗂️ Estrutura do Projeto

```
automacao_credencial_idoso_e_pne/
├── carteirinhas.py          # Script principal para geração das credenciais
├── controle.xlsx            # Planilha com os dados dos solicitantes
├── imagem.ico               # Ícone do executável
├── modelo_idoso.docx        # Modelo de credencial para idosos
├── modelo_pne.docx          # Modelo de credencial para PNE
└── README.md                # Documentação do projeto
```

## ⚙️ Requisitos

- Python 3.x
- Bibliotecas Python:
  - `pandas`
  - `python-docx`
  - `openpyxl`
  - `ttkbootstrap`

## 🚀 Como Utilizar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/Eduardo-Bauer/automacao_credencial_idoso_e_pne.git
   ```

2. **Instale as dependências:**

   ```bash
   pip install pandas
   pip install python-docx
   pip install openpyxl
   python -m pip install ttkbootstrap
   ```

3. **Prepare a planilha `controle.xlsx`:**

   - Insira os dados dos solicitantes conforme o formato esperado pelo script.

4. **Execute o script principal:**

   ```bash
   python carteirinhas.py
   ```

   - O script processará os dados da planilha e gerará os documentos de credenciais correspondentes.

## 🧠 Observações

- Certifique-se de que os modelos `modelo_idoso.docx` e `modelo_pne.docx` estejam devidamente formatados e contenham os campos necessários para a substituição dos dados.
- Este projeto foi desenvolvido com foco na automação de tarefas administrativas, visando aumentar a eficiência e reduzir erros manuais.

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

> *"A automação não apenas economiza tempo, mas também melhora a precisão e a consistência dos processos."*
