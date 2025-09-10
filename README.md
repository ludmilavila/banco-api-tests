# banco-api-tests

Este projeto tem como objetivo realizar a automação de testes de API REST para o [banco-api], validando endpoints e garantindo o correto funcionamento dos fluxos definidos.

---

## 📌 Objetivo

Automatizar os testes da API REST do [banco-api], utilizando ferramentas de testes em JavaScript, permitindo fácil execução, validação de cenários e geração de relatórios.

---

## 🚀 Stack Utilizada

- [JavaScript (Node.js)](https://nodejs.org/)
- [Mocha](https://mochajs.org/) – framework de testes
- [Chai](https://www.chaijs.com/) – biblioteca de asserções
- [Supertest](https://github.com/visionmedia/supertest) – para simular requisições HTTP
- [Dotenv](https://github.com/motdotla/dotenv) – para gerenciamento de variáveis de ambiente
- [Mochawesome](https://github.com/adamgruber/mochawesome) – geração de relatórios em HTML

---

## 📁 Estrutura de Diretórios

```bash
banco-api-tests/
├── test/
│   ├── transferencia/
│   └── login/
├── mochawesome-report/   # Relatórios HTML gerados automaticamente
├── .env                  # Arquivo com variáveis de ambiente (não versionado)
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Configuração do .env

Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

```env
BASE_URL=http://localhost:3000
```

Substitua o valor por **sua URL local ou hospedada** da API `banco-api`.

---

## Pré-requisitos

- Node.js instalado
- Clonar e executar:
  - [banco-api](https://github.com/juliodelimas/banco-api)


## 📦 Instalação

1. Clone este repositório:
   ```sh
   git clone https://github.com/ludmilavila/banco-api-tests.git
   cd banco-api-tests
   ```
   
2. Instale as dependências:

```bash
npm install
```


## 🧪 Executando os Testes

### Testes com saída padrão no terminal:

```bash
npm test
```

O relatório será gerado automaticamente após a execução dos testes, no diretório `./mochawesome-report/` e pode ser aberto em seu navegador.

---

## 📄 Documentação das Dependências

- [Mocha](https://mochajs.org/)
- [Chai](https://www.chaijs.com/)
- [Supertest](https://github.com/visionmedia/supertest)
- [Dotenv](https://github.com/motdotla/dotenv)
- [Mochawesome](https://github.com/adamgruber/mochawesome)


## 🌸 Desenvolvido por:

**Ludmila Ávila** - [GitHub](https://github.com/ludmilavila)
[LinkedIn](https://www.linkedin.com/in/ludmilaavilamendes)
