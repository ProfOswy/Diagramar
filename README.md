# Diagramar

## Apresentação
Diagramar é uma ferramenta web de análise de vigas — um arquivo HTML único e interativo que calcula reações de apoio, esforço normal (N), esforço cortante (V) e momento fletor (M), com resolução passo a passo. Desenvolvido pelo Prof. Me. Rodrigo Gonçalves (Prof Oswy).

## Funcionalidades Principais
- Editor visual de vigas: apoios (móvel, fixo, engaste), cargas concentradas em qualquer direção, cargas distribuídas uniformes/triangulares/trapezoidais, momentos aplicados e rótulas internas (vigas Gerber).
- Cálculo automático de reações por equilíbrio estático (vigas isostáticas) ou pelo método da rigidez direta (vigas hiperestáticas).
- Resolução passo a passo narrada, incluindo o método das seções, pensada para uso em sala de aula.
- Vigas Gerber: divisão automática em trechos pelas rótulas, com os corpos livres ilustrados lado a lado antes da resolução numérica de cada trecho.
- Diagramas de N, V e M com valores extremos destacados e leitura interativa ao passar o mouse.
- Diagrama de Corpo Livre (DCL) com todas as cargas aplicadas e reações calculadas.
- Seletor de unidades (kN/N, m/cm/mm).
- Exportação em PDF, incluindo o enunciado (a viga montada) além dos resultados.
- Glossário de termos técnicos.
- Tema claro/escuro.

## Instruções de Uso
Basta abrir o arquivo `index.html` em um navegador — não há instalação nem dependências, além de conexão à internet para carregar as fontes do Google Fonts. Monte a viga no editor visual, clique em "Calcular reações e diagramas" e explore os resultados, o passo a passo e os diagramas.

## Deployment
Para uso local, recomenda-se servir com um servidor simples (`python -m http.server`, por exemplo). No GitHub Pages, o arquivo principal deve se chamar `index.html`, com o Pages ativado no branch `main`.

## Bibliotecas e Atribuições
Nenhuma dependência externa além das fontes IBM Plex Sans, IBM Plex Mono e Kalam, carregadas via Google Fonts. Todo o cálculo estrutural, a interface e os diagramas são gerados em JavaScript puro, sem bibliotecas de terceiros.

## Direitos Autorais
© 2026 Prof. Me. Rodrigo Gonçalves — uso pessoal e educacional permitido; redistribuição, modificação e remoção de créditos exigem autorização do autor. Veja [LICENSE.md](LICENSE.md).
