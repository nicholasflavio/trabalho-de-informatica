# Define a velocidade da luz em metros por segundo

velocidade_da_luz = 299792458

# Define a distância média entre o Sol e a Lua em metros

distancia_media = 384400000

# Define o tamanho do incremento em metros

incremento = 1000

# Inicializa o tempo total em zero

tempo_total = 0

# Percorre a distância em incrementos e soma o tempo de viagem da luz

while distancia_atual < distancia_media:

    tempo_viagem = incremento / velocidade_da_luz

    distancia_atual += incremento

    tempo_total += tempo_viagem

for distancia_atual in range(0, distancia_media, incremento):

    tempo_atual = distancia_atual / velocidade_da_luz

    tempo_total += tempo_atual

# Exibe o resultado em minutos e segundos

print("A luz do Sol leva cerca de", int(tempo_total / 60), "minutos e", int(tempo_total % 60), "segundos para chegar à Lua.")
