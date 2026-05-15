# Looksmaxing Site

Site estático pronto para publicar no GitHub Pages.

## Estrutura

```txt
index.html
style.css
script.js
assets/
  img/
  pdf/
```

## Como publicar no GitHub Pages

1. Entre no GitHub.
2. Crie um repositório chamado `looksmaxing-site`.
3. Faça upload de todos os arquivos desta pasta.
4. Vá em `Settings`.
5. Clique em `Pages`.
6. Em `Build and deployment`, escolha:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
7. Clique em `Save`.
8. O site ficará disponível em:

```txt
https://SEUUSUARIO.github.io/looksmaxing-site/
```

## O que você precisa editar

No `index.html`, procure e substitua:

```txt
SEU-LINK-DE-COMPRA-AQUI.com
```

por seu link da Hotmart, Kiwify, Gumroad, Mercado Pago ou outra plataforma.

Troque também:

```txt
https://wa.me/5565999999999
https://instagram.com/SEUUSUARIO
```

pelos seus links reais.

## Onde colocar suas imagens

Coloque fotos em:

```txt
assets/img/
```

Exemplos:

```txt
assets/img/antes.jpg
assets/img/depois.jpg
assets/img/preview.jpg
```

Depois edite o `index.html` para trocar o bloco `photo-placeholder` por uma imagem real, por exemplo:

```html
<img src="assets/img/depois.jpg" alt="Foto da transformação" class="hero-image">
```

E no `style.css` adicione:

```css
.hero-image {
  width: 100%;
  height: 520px;
  object-fit: cover;
  border-radius: 26px;
}
```

## Venda

Recomendação:

- GitHub Pages: vitrine, blog, transformação, conteúdo gratuito.
- Hotmart/Kiwify/Gumroad/Mercado Pago: checkout e entrega do produto.
- WhatsApp/Instagram: contato e conversão.
- Google Forms/Tally/Typeform: formulário de avaliação.

Evite processar pagamento, senha, login ou dados sensíveis diretamente pelo GitHub Pages.

## Aviso legal recomendado

O site já contém aviso legal no rodapé e no FAQ. Mantenha algo parecido:

> Este conteúdo é educativo e não substitui avaliação médica, dermatológica, nutricional, psicológica ou de outro profissional habilitado.
