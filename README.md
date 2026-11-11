# CleanGUI Filters

Uma coleção de filtros cosméticos para remover elementos desnecessários das interfaces de sites, deixando a navegação mais limpa e focada.

## Objetivo

O CleanGUI Filters remove distrações visuais, como:

- Banners promocionais e ofertas Premium.
- Avisos para instalar aplicativos.
- Pop-ups e chamadas para abrir o aplicativo.
- Elementos repetitivos ou que ocupam espaço sem necessidade.

## Compatibilidade

As regras usam sintaxe de filtros cosméticos no estilo Adblock/uBlock, compatível com o suporte a filtros personalizados do Brave Shields e outros navegadores baseados em Chromium que aceitem esse formato.

**Arquivo principal:** [cleangui-filters.txt](cleangui-filters.txt)

## Como usar no Brave

1. Abra as configurações do Brave.
2. Entre em **Shields** e procure **Filtros de conteúdo**.
3. Abra a área de filtros personalizados.
4. Cole o conteúdo de `cleangui-filters.txt` ou adicione a lista quando houver uma URL pública de assinatura.

A disponibilidade e o nome exato das opções podem variar conforme a versão do Brave.

## Boas práticas

- As regras são cosméticas: escondem elementos da página; não bloqueiam necessariamente requisições de rede ou anúncios em vídeo.
- Seletores baseados em classes geradas podem deixar de funcionar quando o site atualiza a interface.
- Revise os filtros após atualizações dos sites para evitar ocultar controles úteis.
- Novas regras devem ser adicionadas sem apagar as regras existentes.

## Contribuição

Sugestões, melhorias e relatos de filtros que escondem conteúdo útil são bem-vindos.

## Licença

Este projeto está licenciado sob a **MIT License**. Consulte [LICENSE](LICENSE).

Copyright © 2026 CleanGUI Filters.
