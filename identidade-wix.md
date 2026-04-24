# Identidade Visual: pt.wix.com

## Cores

| Tipo | Hex |
|------|-----|
| Primária | #166AEA |
| Secundária | #000000 |
| Background | #FFFFFF |
| Texto | #1C1D21 |
| Acentos | #116DFF, #E2E2E2, #8F8F8F |

## Fontes

- **Madefor** (família proprietária do Wix)
  - madefor-text
  - madefor-text-bold
  - madefor-text-mediumbold
  - madefor-display
- **Fallback**: Helvetica, Arial, sans-serif

## Estilo Visual

- **Bordas**: border-radius 50px (botões principais), 24px (skip-to-content)
- **Transições**: 0.2s ease
- **Gradientes**: Blue gradient overlay com transparências
  - Exemplo: `linear-gradient(180deg, #FFFFFF 0%, rgba(255,255,255,0.65) 5.6%, rgba(152,197,255,0.42) 30.6%, rgba(197,222,255,0.56) 49.8%, #FFFFFF 71.7%, #FFFFFF 99.3%)`

## Informações do Site

- **Título**: "Criador de Sites: Criar Site Grátis | Wix.com"
- **Descrição**: Aprenda a criar um site do seu jeito com o criador de sites Wix. Veja como criar um site profissional com templates feitos por designers e recursos avançados.

## Paleta para CSS

```css
:root {
  --wix-primary: #166AEA;
  --wix-secondary: #000000;
  --wix-background: #FFFFFF;
  --wix-text: #1C1D21;
  --wix-accent: #116DFF;
  --wix-gray-light: #E2E2E2;
  --wix-gray-dark: #8F8F8F;
  --wix-border-radius: 50px;
  --wix-transition: 0.2s ease;
}
```

## Exemplo de Botão Estilizado

```css
.btn-wix {
  background: #166AEA;
  color: #FFFFFF;
  border-radius: 50px;
  padding: 12px 38px;
  font-family: 'madefor-text-bold', Helvetica, Arial, sans-serif;
  transition: all 0.2s ease;
  border: none;
}

.btn-wix:hover {
  background: #116DFF;
}

.btn-wix:disabled {
  background: #E2E2E2;
  color: #8F8F8F;
}
```