# Ambiente Base para Projetos com TypeScript e Sass

Este repositório contém uma estrutura básica e organizada para facilitar o início de novos projetos que utilizam **TypeScript** e **Sass**. A ideia é economizar tempo, evitando a repetição da configuração inicial a cada novo projeto.

## 🚀 Tecnologias e Ferramentas

- [TypeScript](https://www.typescriptlang.org/)
- [Sass (SCSS)](https://sass-lang.com/)
- Estrutura de pastas organizada
- Scripts de build e desenvolvimento

## 📁 Estrutura do Projeto
```
meu-projeto/
├── public/
│   ├── index.html
│   └── assets/
│       ├── js/
│       │   └── index.js
│       └── styles/
│           └── style.css
├── src/
│   ├── sass/
│   │   └── style.scss
│   ├── ts/
│   │   └── index.ts
│   └── templates/
├── package.json
└── tsconfig.json

```


---

## ⚙️ Scripts disponíveis

Você pode usar os seguintes scripts npm para compilar seus arquivos:

| Comando               | Descrição                                  |
|-----------------------|--------------------------------------------|
| `npm run build:ts`    | Compila os arquivos TypeScript (`.ts`)    |
| `npm run build:sass`  | Compila os arquivos Sass (`.scss`)         |
| `npm run build`       | Compila TypeScript e Sass juntos           |
| `npm run watch:ts`    | Observa mudanças nos arquivos `.ts` e recompila automaticamente |
| `npm run watch:sass`  | Observa mudanças nos arquivos `.scss` e recompila automaticamente |

---

## 🛠️ Como usar

### 1. Clone o repositório

```bash
git clone https://github.com/CarlosPassosMartins/arquivo-de-start
```

### 2. Instale as dependências
Se você **não tem o TypeScript e Sass instalados globalmente**, execute:

```bash
npm install
```

> Isso irá instalar as dependências listadas no `package.json` e criar a pasta `node_modules`.

Se preferir usar as ferramentas globalmente, pode pular esta etapa.

## ⚠️ Nota importante

Este projeto **assume que você tenha o `typescript` e o `sass` instalados globalmente**, caso opte por não instalar as dependências localmente.  
Se não estiver instalado globalmente, recomendamos rodar:

```bash
npm install --global typescript sass
```

---

## 🤝 Contribuição

Sinta-se à vontade para adaptar este ambiente conforme suas necessidades em futuros projetos.

---

## 📄 Licença

Este projeto está aberto para uso livre e adaptação.




