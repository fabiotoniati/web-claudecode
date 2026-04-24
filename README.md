# Agência Digital

Website institucional da Agência Digital com serviços de criação de sites e hospedagem premium.

## Estrutura do Projeto

```
├── V1/                    # Versão original do site
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── V2/                    # Versão redesenhada (identidade Wix)
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── identidade-wix.md        # Documentação de identidade visual
├── package.json           # Configuração npm
└── .gitignore           # Arquivos ignorados pelo git
```

## Como Executar

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm start
# ou
npm run dev
```

O site estará disponível em http://localhost:3000

## Tecnologias

- HTML5 semântico
- CSS3 com variáveis personalizadas
- JavaScript vanilla (sem frameworks)
- Design responsivo (mobile-first)

## Versões

- **V1**: Versão original com design padrão
- **V2**: Versão redesenhada inspirada na identidade visual do Wix

## Customização

Para alterar as cores, edite as variáveis CSS em `V2/styles.css`:

```css
:root {
  --primary: #166AEA;
  --secondary: #000000;
  --wix-border-radius: 50px;
}
```

## Licença

MIT © 2026 Agência Digital