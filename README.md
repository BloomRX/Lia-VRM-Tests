<h1 align="center">Lia VRM Tests</h1>

<p align="center">
  <strong>Espaço reservado para ensaios de avatares 3D do ecossistema Lia.</strong><br>
  A ideia é reunir verificações de importação, rig, expressões e animações VRM sem confundir testes técnicos com aprovação visual da personagem.
</p>

> **Estado: repositório inicial.** Este checkout contém apenas a documentação de abertura. Não existem aqui um test runner, modelos de referência, fixtures ou relatórios executados. Nenhuma compatibilidade VRM foi comprovada por este repositório.

## Objetivo pretendido

O ecossistema usa ou planeja usar avatares 3D em diferentes etapas:

| Produto | Relação com VRM |
| --- | --- |
| [**Lia Desktop**](https://github.com/BloomRX/Lia-Project) | Importa e apresenta avatares VRM locais; possui seus próprios gates de Electron e renderização. |
| [**Lia Forge**](https://github.com/BloomRX/Lia-Forge) | Inspeciona e prepara assets 3D e uma receita para produção do avatar canônico. |
| [**Lia Studio**](https://github.com/BloomRX/Lia-Studio) | Planeja e edita dados de animação; a interoperabilidade real exige validação específica. |

Este repositório poderá futuramente receber fixtures **redistribuíveis e licenciadas**, scripts de reprodução e evidências separadas por versão do formato, runtime e dispositivo. Nada disso está implementado nesta revisão.

## Critérios para futuros testes

- **Estrutura:** arquivos reais, formatos declarados, integridade e recursos embutidos.
- **Rig:** mapeamento humanoide, skinning, pose de repouso e deformações.
- **Expressões:** olhos, boca, piscadas e transições.
- **Animação:** execução, loops e compatibilidade entre produtor e consumidor.
- **Aceite visual:** comparação humana com as fichas oficiais da Lia, separada do resultado dos testes de estrutura.

A **personagem Lia 3D oficial ainda depende de produção e aprovação artística**; não use exemplos ou modelos de terceiros como se fossem o avatar canônico.

## Estado e colaboração

Não há instalação nem comando de execução neste momento. Para testar a implementação existente, use os comandos de validação documentados nos repositórios do **Desktop** e do **Forge**. O material publicado aqui futuramente deverá incluir origem, licença e limites de cada evidência.
