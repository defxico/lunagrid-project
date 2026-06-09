# LunaGrid

**Sistema de gestão de recursos para uma colônia lunar fictícia.**

Projeto desenvolvido para a Global Solution | Indústria Espacial, com foco em Web Design, UX, organização visual, acessibilidade e responsividade.

## Integrante

- Francisco Caetano Bernareds - RM571399

## Descrição do projeto

O **LunaGrid** é um protótipo navegável de uma interface web para monitoramento e gestão de recursos críticos em uma colônia lunar fictícia.

A solução permite visualizar, de forma clara e rápida, o estado operacional da colônia, incluindo energia, água, oxigênio, alimentos, alertas críticos e módulos estruturais.

Os dados utilizados no protótipo são simulados. O projeto não possui backend, banco de dados ou integração real com satélites.

## Problema abordado

Em uma colônia lunar, recursos como energia, água, oxigênio e alimentos são limitados e precisam ser monitorados constantemente. Qualquer falha de gestão pode afetar a segurança dos habitantes e a continuidade da operação.

O LunaGrid propõe uma interface centralizada para apoiar a tomada de decisão rápida em cenários de operação crítica.

## Funcionalidades principais

- Dashboard geral da colônia.
- Monitoramento de energia, água, oxigênio e alimentos.
- Central de alertas com níveis de severidade.
- Visualização dos módulos da colônia.
- Indicadores visuais de status e criticidade.
- Navegação funcional entre páginas.
- Layout responsivo.

## Páginas do protótipo

| Página | Descrição |
|---|---|
| `index.html` | Dashboard geral com visão dos recursos, status da colônia e alertas rápidos. |
| `recursos.html` | Detalhamento dos recursos críticos, níveis atuais, consumo, status e ações recomendadas. |
| `alertas.html` | Central de alertas com severidade, módulo afetado, tempo simulado e status da ação. |
| `modulos.html` | Visão dos módulos da colônia, como Habitat Core, BioDome, Solar Array, Water Recycler, Life Support e Communications. |

## Decisões de design e UX

A interface adota uma estética minimalista e operacional, combinando fundo escuro com componentes brancos/off-white. Essa escolha cria contraste, reforça o contexto espacial e aproxima o sistema de uma linguagem visual moderna, inspirada em equipamentos espaciais contemporâneos e interfaces premium.

As cores são usadas de forma semântica:

- Verde: status estável.
- Amarelo: atenção.
- Vermelho: situação crítica.
- Ciano: destaque, informação e ações principais.

A hierarquia visual prioriza leitura rápida, com cards, indicadores numéricos, barras de progresso e alertas destacados. O objetivo é facilitar decisões sob pressão.

## Relação com os ODS

O projeto se conecta principalmente aos seguintes Objetivos de Desenvolvimento Sustentável:

- **ODS 9 - Indústria, inovação e infraestrutura:** uso de tecnologia para gestão de infraestrutura crítica.
- **ODS 11 - Cidades e comunidades sustentáveis:** lógica aplicável a comunidades fechadas, cidades inteligentes e gestão urbana.
- **ODS 13 - Ação contra a mudança global do clima:** monitoramento ambiental e uso racional de recursos.
- **ODS 2 - Fome zero e agricultura sustentável:** produção e controle de alimentos em ambiente fechado, como o BioDome.

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons

## Como executar o projeto

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto no VS Code.
3. Abra o arquivo `index.html` com Live Server.
4. Navegue entre as páginas pelo menu da interface.

## Links

- Repositório GitHub: https://github.com/defxico/lunagrid-project
