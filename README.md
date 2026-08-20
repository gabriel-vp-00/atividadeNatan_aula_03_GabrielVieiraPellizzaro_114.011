# Atividade Aula 03 - CSS

## Tema da página
A página representa o site institucional de um projeto ou empresa fictícia, apresentando seções de sobre o site, projetos recentes e contato.

## Cores escolhidas
- **Verde e Azul (`green` e `blue`):** Usados no fundo do site e no cabeçalho.
- **Roxo e Vermelho (`purple` e `red`):** Usados no texto principal, no título `h2` e no fundo da seção de contato.
- **Castanho (`brown`):** Usado no fundo dos cards da seção de projetos.
- **Amarelo e Verde Limão (`yellow`, `yellowgreen` e `white`):** Usados no texto do rodapé, em bordas e títulos secundários para dar destaque.

## Seletores utilizados
- **Seletor por Tag:** `body`, `header`, `main`, `footer`, `h1`, `h2`, `h3`, `p`, `img`.
- **Seletor por Classe:** `.header-container`, `.cards-container`, `.card`.
- **Seletor por ID:** `#sobre` e `#contato`.

## Onde foram aplicados margin, padding e border
- **Margin:** Aplicado entre as seções (`margin-bottom: 100px`), na margem superior da imagem (`margin-top: 500px`), nos cards e para centralizar os blocos principais (`margin: 0 auto` / `margin: 40px auto`).
- **Padding:** Aplicado no cabeçalho (`padding: 20px 0`), no rodapé (`padding: 20px 0`), na seção sobre (`10px`), de contato (`25px`) e dentro dos cards (`25px`).
- **Border:** Aplicado abaixo dos títulos `h2` (`border-bottom: 3px solid #23d8d5`), na imagem (`border: 20px solid blueviolet`), nos cards (`border: 1px solid yellow`) e no topo do rodapé (`border-top: 1px solid brown`).

## Como o box model foi utilizado
O Box Model foi ativado no início do CSS através da regra universal `* { box-sizing: border-box; margin: 0; padding: 0; }`. Essa configuração inclui as bordas e os espaçamentos internos no tamanho total dos elementos, permitindo controlar o layout com precisão.

## Uma dificuldade encontrada e como ela foi resolvida
- **Dificuldade:** Ajustar as proporções e o alinhamento da imagem dentro da seção "Sobre".
- **Solução:** Utilização das propriedades `width: 100%;` e `max-width: 100%;` para manter a imagem responsiva ao contêiner pai.
- 
