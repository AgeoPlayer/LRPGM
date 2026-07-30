<div align="center">

<a href="https://lrpgm.netlify.app/">
  <img src="https://lrpgm.netlify.app/img/icon.png" width="116" alt="Logo do LRPGM">
</a>

# LRPGM

### Traduza jogos de RPG Maker sem instalar Ruby, sem alterar os arquivos originais e sem quebrar o jogo.

O LRPGM entende a estrutura do projeto, protege comandos sensíveis e aplica a tradução de forma reversível — para você se concentrar no texto, não em reconstruir um jogo quebrado.

[![Baixar LRPGM](https://img.shields.io/badge/Baixar_LRPGM-087FF5?style=for-the-badge&logo=windows11&logoColor=white)](https://lrpgm.netlify.app/download)
[![Site oficial](https://img.shields.io/badge/Site_oficial-172033?style=for-the-badge&logo=googlechrome&logoColor=white)](https://lrpgm.netlify.app/)
[![Discord](https://img.shields.io/badge/Comunidade-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/FFz58GqCBM)

[English](README.md) · [Português](README.pt-BR.md)

![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?logo=windows11&logoColor=white)
![RPG Maker](https://img.shields.io/badge/RPG%20Maker-XP%20%7C%20VX%20%7C%20VX%20Ace%20%7C%20MV%20%7C%20MZ-087FF5)
![Desenvolvimento](https://img.shields.io/badge/Desenvolvimento-ativo-22C55E)

**Mais de 250 assinantes · mais de 500 membros · mais de 3 mil downloads**

</div>

---

<div align="center">
  <img src="https://lrpgm.netlify.app/img/evolution/image_v4.png" alt="Interface do LRPGM" width="100%">
</div>

## Não é apenas um tradutor

Traduzir um jogo de RPG Maker não é simplesmente substituir palavras. Um comando alterado, uma quebra de linha ignorada, uma fonte incompatível ou o nome errado de uma imagem pode impedir o jogo de iniciar ou quebrar eventos durante a execução.

O LRPGM foi criado para resolver esse fluxo completo. Ele identifica o modelo e a estrutura do jogo, extrai os textos úteis, preserva elementos sensíveis, permite revisar o resultado e aplica a tradução de forma pensada para manter o projeto jogável.

> **O benefício não é apenas traduzir. É traduzir com segurança.**

## Por que usar o LRPGM?

| Simples para começar | Inteligente durante a tradução | Seguro ao aplicar |
| --- | --- | --- |
| Não exige Ruby instalado | Detecta códigos de controle e estruturas sensíveis | Mantém os arquivos originais preservados |
| Identifica automaticamente o modelo do jogo | Reconhece quebras de linha e padrões personalizados | Aplica a tradução por plugin e arquivo separado |
| Organiza os projetos em uma única biblioteca | Evita traduzir elementos que não devem ser alterados | Permite desativar a tradução e retornar ao estado original |
| Permite continuar e revisar o trabalho depois | Ajusta fontes e referências que poderiam quebrar o jogo | Valida o conteúdo antes de concluir a aplicação |

## Compatibilidade com projetos antigos e modernos

O LRPGM possui leitura e escrita próprias para formatos usados pelo **RPG Maker XP, VX e VX Ace**, sem exigir uma instalação externa do Ruby. Para **MV e MZ**, o programa entende a estrutura moderna do projeto, seus arquivos, plugins e padrões de controle.

Modelos suportados:

- RPG Maker XP
- RPG Maker VX
- RPG Maker VX Ace
- RPG Maker MV
- RPG Maker MZ

> Jogos modificados, plugins de terceiros e estruturas personalizadas podem exigir ajustes específicos. O sistema de reports integrado ajuda a transformar casos reais de compatibilidade em melhorias reutilizáveis.

## Um fluxo completo de tradução

### 1. Adicione o jogo

Escolha a pasta do projeto. O LRPGM identifica automaticamente o modelo, a estrutura dos arquivos, os plugins ativos e o fluxo mais adequado.

### 2. Extraia somente o que importa

Selecione diálogos, eventos, banco de dados, plugins, scripts e outros recursos detectados. Os filtros reduzem ruídos e protegem comandos que não devem ser tratados como texto comum.

### 3. Traduza com contexto

O programa identifica os idiomas encontrados no projeto e permite escolher o idioma de destino e o provedor de tradução mais adequado.

### 4. Revise antes de aplicar

Corrija nomes, termos recorrentes e frases diretamente no fluxo de revisão. Você mantém o controle do resultado antes de qualquer alteração no jogo.

### 5. Aplique de forma reversível

No fluxo principal, o LRPGM adiciona um plugin leve e um arquivo separado com a tradução. Os arquivos originais permanecem preservados e, ao desativar o plugin, o jogo pode retornar ao estado anterior.

## Proteções que evitam jogos quebrados

- Preserva comandos, variáveis, scripts e padrões de plugins.
- Detecta códigos de controle usados nas mensagens do RPG Maker.
- Reconhece quebras de linha padrão e personalizadas.
- Substitui fontes incompatíveis quando necessário.
- Protege valores técnicos que não devem entrar na tradução.
- Corrige referências para imagens e arquivos quando nomes traduzidos poderiam causar erros.
- Reutiliza perfis de compatibilidade e correções aprendidas.
- Envia reports técnicos pelo aplicativo com o contexto necessário para investigação.

## Download e instalação

O LRPGM está disponível para **Windows 10 e Windows 11**.

### [Baixar a versão mais recente pelo site oficial](https://lrpgm.netlify.app/download)

A página de download oferece dois instaladores oficiais:

- **Instalador completo:** inclui o runtime necessário do .NET e é recomendado para a maioria dos usuários.
- **Instalador compacto:** possui download menor e requer o .NET 9 Desktop Runtime x64 instalado.

O instalador verifica a integridade dos arquivos antes de realizar alterações no computador. Baixe o LRPGM somente pelo site oficial ou pelos arquivos publicados na seção **Releases** deste repositório.

## Veja o LRPGM em ação

- [Conheça o fluxo do LRPGM](https://www.youtube.com/watch?v=OuEVYdBpO40)
- [Veja uma demonstração prática](https://www.youtube.com/watch?v=4CCLuPYL7bE)
- [Explore mais recursos do programa](https://www.youtube.com/watch?v=An9FgHVAh_I)

## Planos e acesso

Você pode baixar o LRPGM gratuitamente e conhecer seu fluxo principal. Os planos **Basic** e **Plus** oferecem recursos adicionais, limites ampliados, mais provedores de tradução e opções para fluxos avançados.

[Comparar os planos do LRPGM](https://lrpgm.netlify.app/adquirir)

## Ajuda, comunidade e reports

- [Central de ajuda](https://lrpgm.netlify.app/help)
- [Servidor oficial no Discord](https://discord.gg/FFz58GqCBM)
- [Histórico de atualizações](https://lrpgm.netlify.app/updates)
- [Página de contato](https://lrpgm.netlify.app/contact)

Problemas relacionados a um jogo devem ser reportados pelo próprio LRPGM. Dessa forma, o report inclui o modelo, a versão do aplicativo e o contexto técnico necessário para a análise. Para dúvidas de conta, acesso ou orientações gerais, utilize o Discord oficial.

## Sobre este repositório

Este é o repositório público de apresentação e distribuição oficial do LRPGM. Ele reúne informações do projeto, notas de atualização e instaladores publicados.

O código-fonte do LRPGM e sua infraestrutura interna não são distribuídos neste repositório.

## Perguntas frequentes

<details>
<summary><strong>Preciso instalar Ruby?</strong></summary>

Não. O LRPGM possui tecnologia própria para trabalhar com os formatos antigos suportados e não depende de uma instalação externa do Ruby.

</details>

<details>
<summary><strong>A tradução substitui os arquivos originais?</strong></summary>

No fluxo principal, não. A tradução é aplicada por plugin e arquivo separado, mantendo os dados originais do jogo preservados e permitindo uma aplicação reversível.

</details>

<details>
<summary><strong>Posso revisar a tradução antes de aplicar?</strong></summary>

Sim. O LRPGM possui um fluxo de revisão para corrigir nomes, frases e termos recorrentes antes da aplicação no jogo.

</details>

<details>
<summary><strong>Todos os jogos são automaticamente compatíveis?</strong></summary>

O LRPGM atende XP, VX, VX Ace, MV e MZ. Porém, jogos profundamente modificados ou com plugins próprios podem exigir ajustes de compatibilidade. Esses casos podem ser reportados diretamente pelo aplicativo.

</details>

<details>
<summary><strong>O LRPGM é gratuito?</strong></summary>

Existe uma forma gratuita de começar. Os planos Basic e Plus liberam recursos, provedores, limites e opções adicionais.

</details>

---

<div align="center">

**LRPGM — simples por fora, inteligente por dentro e seguro onde realmente importa.**

RPG Maker é uma marca de seus respectivos proprietários. O LRPGM é uma ferramenta independente e não possui afiliação oficial com os criadores do RPG Maker.

</div>
