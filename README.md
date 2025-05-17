# 🧠 Gerador de Dados Fictícios

Este projeto é uma aplicação web simples que permite gerar dados fictícios de pessoas com nome, email, telefone, endereço e data de nascimento. Os dados são obtidos via API pública e podem ser copiados, baixados como `.txt` ou `.sql`, ou convertidos para comandos SQL (`CREATE TABLE` e `INSERT INTO`) com um clique.

## ✨ Funcionalidades

- ✅ Seleção de atributos desejados (email, telefone, endereço, nascimento)
- ✅ Geração de múltiplas pessoas fictícias (usando a [RandomUser API](https://randomuser.me))
- ✅ Visualização dos dados em formato simples e estruturado
- ✅ Download dos dados:
  - `.txt` (simples, sem rótulos)
  - `.sql` (com `CREATE TABLE` e `INSERT INTO`)
- ✅ Cópia direta do SQL para a área de transferência

---

## 🖥️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- [RandomUser.me API](https://randomuser.me)
- Funções modernas como `fetch()`, `async/await` e `Blob` para download

---

## ▶️ Como Usar

1. Abra o arquivo `index.html` no navegador.
2. Informe quantas pessoas deseja gerar.
3. Marque os atributos que deseja incluir nos dados.
4. Clique em **Gerar Dados**.
5. Use os botões para:
   - Copiar os dados
   - Baixar em `.txt` ou `.sql`
   - Visualizar comandos SQL prontos

---

## 📂 Estrutura do Projeto

gerador-de-dados/
├── index.html
├── style.css
├── script.js (se você separou)
└── README.md


---

## 📌 Observações

- A separação entre pessoas nos dados exportados é feita por **ENTER**.
- O SQL gerado é compatível com bancos MySQL/PostgreSQL padrão.
- Este projeto não salva os dados em servidor, é 100% local e seguro.

---

## 📄 Licença

Este projeto é open-source e gratuito para fins educacionais ou pessoais.

