# Content-Patcher-TEMPLATE
Template padrão para os mods que usam o Content Patcher 
Para facilitar o trabalho com os repositorios e padronizar os mods da serie
Esse template contempla todos os arquivos necessarios para o mod funcionar
Basta apenas modificar os nomes e demais itens conforme necessario
Remova todas as pastas e arquivos que não forem necessarios quando for lancar a versao inicial do mod no Nexus
Adicionar requerimento opcional do "Generic Mod Config Menu" na descricao do site ao adicionar o mod para download


# Descrição

The dream of everyone who dabbles in alchemy: equivalent exchange.
Modify the properties of elements without any loss.
Freely transform one material into another.
Create matter from dust.

Manipulate everything at will.

The alchemist's dream is now in your hands!

A collection of recipes ranging from coal to diamond.
Convert, multiply, and transform!
Powers never before imagined are now available to you!

Simply find the pages of the alchemist's lost grimoire and master the secrets of alchemy.


# Recipes
 - Pedra para Carvão 
    "Carvão": "390 99/Field/382/false/default/",
 
 - Carvão para Diamante 
    "Diamante": "382 99/Field/72/false/default/",
 
 - Fragmento Prismatico 
    "Fragmento Prismatico": "60 1 62 1 64 1 66 1 68 1 70 1 72 1/Field/74/false/default/"
 
 - Quebrar Cobre
    "Cobre": "334 1/Field/378 6/false/default/",
 
 - Quebrar Ferro
    "Ferro": "335 1/Field/380 6/false/default/",
 
 - Quebrar Ouro
    "Ouro": "336 1/Field/384 6/false/default/",
 
 - Quebrar Iridio
    "Iridio": "337 1/Field/386 6/false/default/",
 
 - Quebrar Radioativo
    "Radioativo": "910 1/Field/909 6/false/default/",

# Changelog

- v0.1.0
    feat: todas as receitas abertas para teste


# Roadmap

-V0.1.0 — Recipes Preview

*Criar todas as receitas.
*Testar todas.
*Tirar screenshots.
*Lançar como versão de testes (tag Cheating).

-V0.1.1

*Correções.
*Balanceamento.
*Traduções.

-V0.2.0 — Mail Framework

*Alterar todas as receitas para aprendidas por carta.
*Criar cartas de teste.
*Aprender a usar todas as condições de envio do Mail Framework. O modelo suporta diversos gatilhos, como datas, eventos, cartas recebidas, receitas conhecidas e condições do Expanded Preconditions.
*Validar que o aprendizado das receitas funciona corretamente.

-V0.3.0 — Páginas Perdidas

*Criar os objetos das páginas.
*Adicionar aos pontos de artefato.
*Criar as flags de descoberta.
*Fazer cada página disparar sua respectiva carta.

-V0.4.0 — A Quest

*Criar a missão do Mago.
*Fazer as páginas aparecerem apenas após a missão ser iniciada.
*Validar todo o fluxo:
*Receber a missão.
*Encontrar uma página.
*Criar a flag.
*Receber a carta.
*Aprender a receita.
*Repetir até completar o grimório.