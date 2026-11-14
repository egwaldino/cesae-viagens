# CESAE Viagens

Projeto individual de desenvolvimento web. O objetivo do exercício é reproduzir o layout de referência da página CESAE Viagens, com atenção à apresentação em diferentes tamanhos de ecrã nomeadamente, mobile e desktop, usando componentes do Bootstrap 5.3.

**Autor:** Egwaldino Cassuente  
**Tutor:** Francisco Perez  
**Repositório:** [github.com/egwaldino/cesae-viagens](https://github.com/egwaldino/cesae-viagens)
**Site publicado:** [egwaldino.github.io/cesae-viagens](https://egwaldino.github.io/cesae-viagens/)

## Sobre o projeto

A página apresenta uma agência de viagens e reúne informação sobre os seus destinos e planos. Inclui:

- Navegação responsiva com menu colapsável e ligações às secções.
- Destaque inicial com atalhos para planos e destinos.
- Secção de vantagens.
- Carrossel com destinos em destaque.
- Cartões com três planos de viagem.
- Perguntas frequentes em acordeão.
- Formulário de pedido de proposta.
- Rodapé com ligações, subscrição e ícones de redes sociais.

## Tecnologias e conceitos aplicados

- HTML5 e estrutura semântica.
- Bootstrap 5.3: grelha responsiva, utilitários de layout e componentes interativos.
- Bootstrap Icons.
- Recursos externos carregados por CDN.

**Nota sobre a implementação:** o `index.html` contém alguns atributos `style` inline para dimensões e apresentação. O enunciado pede a utilização exclusiva de classes Bootstrap; Mas é sabido que quando precisamos de estilos personalizados devido a limitação do Bootstrap usamos style para chegar até ao resultado pretendido.

## Estrutura do projeto

```text
CesaeViagens/
|-- index.html
|-- README.md
`-- assets/
    |-- brasilia.webp
    |-- lisboa.webp
    |-- luanda.webp
    `-- sal.webp
```

## Como visualizar

1. Clona o repositório:

   ```bash
   git clone https://github.com/egwaldino/cesae-viagens.git
   ```

2. Abre `index.html` num navegador. Também podes usar a extensão Live Server do VS Code.

O Bootstrap e os ícones são carregados através de CDN, por isso é necessária uma ligação à Internet. As imagens dos destinos estão na pasta `assets/`.

## Critérios de entrega

De acordo com o enunciado, a página deve reproduzir o modelo em computador e telemóvel, e os componentes devem funcionar usando Bootstrap 5.3. Antes de submeter, confirma no navegador se os estilos e as imagens carregam corretamente e entrega o link do repositório GitHub, não um ficheiro ZIP nem um link do GitHub Pages.

## O que este exercício permite praticar

- Construir uma página com secções semânticas.
- Organizar conteúdo com a grelha e os breakpoints do Bootstrap.
- Utilizar componentes interativos, como navbar, carrossel e acordeão.
- Criar navegação por âncoras e estruturar um formulário.

---

© 2026 Egwaldino Cassuente. Exercício realizado para fins de aprendizagem.
