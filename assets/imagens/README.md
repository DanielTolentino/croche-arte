# Imagens selecionadas — Crochê Arte

As imagens `.webp` na raiz desta pasta são as versões finais tratadas para uso no site. Elas foram selecionadas para equilibrar foto de ambiente, detalhes de textura e variedade de peças.

## Arquivos

| Arquivo | Uso sugerido | Texto alternativo sugerido |
| --- | --- | --- |
| `hero-runner.webp` | Hero / destaque principal | Caminho de mesa de crochê branco decorando uma mesa com flores vermelhas |
| `tapete-branco-vermelho.webp` | Card de peça / catálogo | Tapete oval de crochê branco e vermelho com flores coloridas no centro |
| `toalha-vermelha-dourada.webp` | Detalhe de acabamento | Peça redonda de crochê vermelho com acabamento dourado |
| `tapete-azul-preto.webp` | Card de peça / inspiração | Tapete oval de crochê azul e preto sob uma planta ornamental |
| `capa-amarela.webp` | Utilidades para a casa | Capa de crochê amarela e vermelha para eletrodoméstico |
| `organizador-vermelho.webp` | Organizadores | Organizador de parede de crochê vermelho com flores e pérolas |
| `capa-bebedouro-neutra.webp` | Utilidades para a casa | Capa bege de crochê para bebedouro com flor vermelha |
| `mesa-redonda-branca.webp` | Lifestyle / decoração | Toalha redonda de crochê branco com vaso de flores vermelhas |
| `organizador-azul.webp` | Organizadores | Organizador azul de crochê com dois compartimentos arredondados |

## Uso no HTML

```html
<picture>
  <source srcset="assets/imagens/hero-runner.webp" type="image/webp">
  <img
    src="assets/imagens/hero-runner.webp"
    alt="Caminho de mesa de crochê branco decorando uma mesa com flores vermelhas"
    loading="eager"
  >
</picture>
```

A pasta `masters/` contém as versões PNG editadas em alta qualidade para eventual reprocessamento. Os arquivos originais enviados continuam preservados na pasta Downloads.
