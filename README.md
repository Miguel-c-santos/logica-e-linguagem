# Tupla com os 20 filmes de maior bilheteira mundial em ordem do mais lucrativo ao menos lucrativo
filmes = (
    "Avatar (2009)",
    "Vingadores: Ultimato (2019)",
    "Avatar: O Caminho da Água (2022)",
    "Titanic (1997)",
    "Star Wars: O Despertar da Força (2015)",
    "Vingadores: Guerra Infinita (2018)",
    "Homem-Aranha: Sem Volta Para Casa (2021)",
    "Jurassic World (2015)",
    "O Rei Leão (2019)",
    "Os Vingadores (2012)",
    "Vingadores: Era de Ultron (2015)",
    "Frozen II (2019)",
    "Barbie (2023)",
    "Frozen – Uma Aventura Congelante (2013)",
    "Super Mario Bros. O Filme (2023)",
    "Harry Potter e as Relíquias da Morte: Parte 2 (2011)",
    "Pantera Negra (2018)",
    "Star Wars: Os Últimos Jedi (2017)",
    "Jurassic World: Reino Ameaçado (2018)"
)

# 5 primeiros colocados
print("Top 5 filmes:")
print(filmes[:5])

# Últimos 4 colocados
print("\nÚltimos 4 filmes:")
print(filmes[-4:])

# Lista em ordem alfabética
print("\nFilmes em ordem alfabética:")
print(sorted(filmes))

# Posição do Titanic
print("\nPosição do Titanic:")
print(f"O filme Titanic está na posição {filmes.index('Titanic (1997)') + 1}")

"#Miguel Caldeira Santos#"
