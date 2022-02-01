# Teste de fábrica para display AGM

Modelos compatíveis:
> AGM 12864A (Todo: Realizar teste)

> AGM 12864D2

> AGM 12864E1 (Todo: Realizar teste)

## Ligação Controle Lógico

| Módulo LCD | Arduino |
|------------|---------|
|     VDD    |    5V   |
|     VSS    |   GND   |
|      E     |    13   |
|     DI     |    12   |
|     RW     |    11   |
|     CS1    |    10   |
|     CS2    |    9    |
|     DB0    |    A0   |
|     DB1    |    2    |
|     DB2    |    3    |
|     DB3    |    4    |
|     DB4    |    5    |
|     DB5    |    6    |
|     DB6    |    7    |
|     DB7    |    8    |

## Ligação Controle de Contraste

| Módulo LCD | TRIMPOT 10K~20K |
|------------|-----------------|
|     VEE    |        A        |
|     GND    |        B        |
|     V0     |   C (MIDDLE)    |

## Ligação Backlight

| Módulo LCD | TRIMPOT 10K~20K |
|------------|-----------------|
|      A     |       3.3V      |
|      K     |       GND       |

## Depuração

Habilitando a depuração, é possível pelo console serial acompanhar o log de comunicação.
```
//==================================
// Depurar?
// 1 = Sim, exibe no console serial.
// 0 = Não.
//
// Nota: Pode apresentar um atraso
// na renderização das imagens 
// quando serial habilitado.
//
//==================================

#define DEBUG 0
```
