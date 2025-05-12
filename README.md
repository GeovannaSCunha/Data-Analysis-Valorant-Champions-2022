
# Análise do Valorant Champions 2022 - Istanbul

Este notebook contém uma análise exploratória dos dados dos jogadores que participaram do campeonato Valorant Champions 2022 em Istanbul.

# Conteúdo do Dataset

O dataset contém estatísticas de 40 jogadores de 8 times diferentes, com as seguintes colunas:

- **Player**: Nome do jogador.
- **Team**: Time do jogador.
- **Nationality**: Nacionalidade do jogador.
- **Kil**: Número de kills.
- **Death**: Número de deaths.
- **K/D**: Razão kills/deaths.
- **KAST %**: Porcentagem de rounds onde o jogador contribuiu (Kill, Assist, Survived, Traded).
- **Prize**: Prêmio em dólares recebido.
- **Role**: Função do jogador no time.
- **HS %**: Porcentagem de headshots.
- **Rounds Played**: Total de rounds jogados.
- **Rounds Win**: Rounds vencidos.
- **Rounds Lose**: Rounds perdidos.

Colunas Adicionais:
- **Rank**: Classificação final do time.
- **Win %**: Porcentagem de rounds ganhos.

# Principais Análises Realizadas

**1. Pré-processamento dos dados:**
- Limpeza e conversão de colunas (KAST %, Prize).
- Correção da coluna Rank para refletir corretamente a classificação dos times.

**2. Análise por nacionalidade:**
- Visualização da distribuição de jogadores por país.
- Identificação que a Coreia do Sul teve a maior representação.

**3. Análise por time:**
- LOUD teve o maior percentual de vitórias.
- OPTC venceu o maior número de rounds.
- LEV teve o menor número de rounds vencidos.

**4. Análise individual dos jogadores:**
- kiNgg (LEV) teve o maior K/D.
- yay (OPTC) fez o maior número de kills.
- Jogadores na função 'Duelist' tiveram mais kills em média.

# Como Usar
1. Certifique-se de ter as bibliotecas pandas, numpy e matplotlib instaladas

2. Execute as células sequencialmente para reproduzir a análise

# Requisitos
- Python 3.x
- Pandas
- NumPy
- Matplotlib

# Autor
Geovanna Silva Cunha
