<h1 align="center"> LIBRAS.app </h1>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-objetivo">Objetivo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-estrutura">Estrutura</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-contribuir">Contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-notas">Notas Finais</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>

<p align="center">
  <img alt="LIBRAS.app" src="/images/preview.png" width="100%">
</p>


---

## 💻 Projeto

O **LIBRAS App** é um projeto voltado para a criação de um banco de dados multimídia com vídeos e imagens representando gestos da Língua Brasileira de Sinais (LIBRAS). O objetivo principal é, futuramente, desenvolver um aplicativo capaz de interpretar sinais realizados por uma pessoa e traduzir seu significado em texto, promovendo acessibilidade e inclusão.

## 📝 Objetivo

- **Fase 1:** Criar um banco de dados com vídeos curtos e imagens estáticas que representam os sinais da LIBRAS. Pesquisar livros, trabalhos e APIs com repositórios que possam ser utilizados durante o projeto.
- **Fase 2:** Desenvolver um modelo de inteligência artificial capaz de interpretar os sinais com base no banco de dados, bem como, ser treinado para aprender com novas fontes de sinais.
- **Fase 3:** Construir um aplicativo móvel que utilize a câmera para interpretar sinais em tempo real.

---

## 📚 Funcionalidades do Projeto

### Fase 1: Banco de Dados
- Vídeos curtos representando gestos da LIBRAS (alfabeto, cumprimentos e expressões básicas como "bom dia", "boa noite", "obrigado", "com licença").
- Captura de imagens estáticas dos vídeos para facilitar o treinamento de IA.
- Arquivo de metadados contendo descrições, nomes dos gestos e referências aos arquivos.

### Fase 2: Inteligência Artificial
- Treinamento de um modelo para reconhecimento de sinais com base no banco de dados.

### Fase 3: Aplicativo Móvel
- Uso da câmera para gravar sinais em tempo real.
- Interpretação dos sinais e exibição do significado em texto.

---

## 🛠️ Tecnologias Utilizadas

- **Python**: Para manipulação de vídeos e imagens.
- **OpenCV**: Para captura de frames dos vídeos.
- **JSON**: Para armazenamento de metadados.
- **GitHub**: Para versionamento e colaboração.
- Novas tecnologias que sejam necessárias para dar continuidade ao projeto.

---

## 📂 Estrutura Inicial do Repositório

```
LIBRAS-App/
│
├── videos/               # Pasta contendo os vídeos originais
├── frames/               # Imagens extraídas dos vídeos
├── metadata.json         # Metadados dos vídeos e imagens
├── scripts/              # Scripts de processamento
│   └── extract_frames.py # Script para extrair frames dos vídeos
├── README.md             # Documentação do projeto
└── .gitignore            # Arquivos a serem ignorados no versionamento
```

---

## 🚀 Como Contribuir

1. Faça um fork deste repositório.
2. Clone o seu fork:
   ```bash
   git clone https://github.com/seu-usuario/LIBRAS-App.git
   ```
3. Crie uma branch para a sua contribuição:
   ```bash
   git checkout -b minha-contribuicao
   ```
4. Faça as alterações necessárias e adicione os arquivos:
   ```bash
   git add .
   ```
5. Commit suas mudanças:
   ```bash
   git commit -m "Descrição das alterações"
   ```
6. Envie para o repositório remoto:
   ```bash
   git push origin minha-contribuicao
   ```
7. Abra um Pull Request!

---

## 🗒️ Notas Finais

O LIBRAS App é um projeto em andamento e todas as contribuições são bem-vindas! Nosso objetivo é construir uma ferramenta acessível que beneficie a comunidade surda e promova a inclusão social.

## 🪪 Licença

Esse projeto está sob a licença MIT.

---

Feito com ☕️  por [BrunnoML](https://www.brunnoml.com.br)