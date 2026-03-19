# 🏋️ Treino

Aplicativo web para registro e acompanhamento de fichas de treino de academia. Funciona direto no navegador do celular, salva os dados **offline** no próprio dispositivo e pode ser instalado na tela inicial como um app nativo.

---

## ✨ Funcionalidades

- **3 séries de treino (A, B, C)** — cada uma com sua própria lista de exercícios
- **Adicionar, editar e remover exercícios** em qualquer série
- **Seletor de peso por exercício** — com botões de +/− em incrementos de 1,25 kg
- **Número de séries** configurável por exercício
- **Seletor de academia** — os pesos de cada exercício são salvos separadamente por academia, permitindo usar a mesma ficha em academias diferentes com cargas diferentes
- **Funciona offline** — todos os dados são salvos no `localStorage` do navegador
- **Instalável como PWA** — pode ser adicionado à tela inicial do celular

---

## 📱 Como instalar no celular

### Android (Google Chrome) — recomendado

1. Acesse a URL do projeto pelo **Google Chrome**
2. Toque no menu **⋮** (canto superior direito)
3. Toque em **"Adicionar à tela inicial"**
4. Confirme — o ícone aparecerá na tela inicial como um app

### iPhone (Safari)

1. Acesse a URL pelo **Safari**
2. Toque no botão de **compartilhar** (ícone de seta para cima)
3. Toque em **"Adicionar à Tela de Início"**
4. Confirme

---

## 🚀 Como publicar no GitHub Pages (hospedagem gratuita)

1. Faça um fork ou clone este repositório
2. Certifique-se de que o arquivo principal se chama `index.html`
3. No repositório, vá em **Settings → Pages**
4. Em **Branch**, selecione `main` e clique em **Save**
5. Aguarde alguns minutos — seu app estará disponível em:
   ```
   https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO
   ```

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Uso |
|---|---|
| HTML + CSS + JavaScript puro | Interface e lógica do app |
| `localStorage` | Persistência dos dados offline |
| [Google Fonts](https://fonts.google.com) | Tipografia (Bebas Neue + DM Sans) |
| GitHub Pages | Hospedagem gratuita |

---

## 📁 Estrutura do projeto

```
/
├── index.html   # App completo (single-file)
└── README.md    # Este arquivo
```

O app é um único arquivo HTML autocontido — sem dependências externas instaláveis, sem build, sem servidor.

---

## 🔒 Privacidade

- Nenhum dado de treino é enviado para servidores externos
- Os dados ficam armazenados exclusivamente no navegador do seu dispositivo
- A chave de API da Anthropic é usada apenas no momento do escaneamento de imagem e não é registrada em nenhum lugar além do seu `localStorage`

---

## 📄 Licença

Projeto pessoal de uso livre. Faça o que quiser com ele.
