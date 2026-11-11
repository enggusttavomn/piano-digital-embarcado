# Piano Digital Embarcado

Protótipo de piano digital que transforma entradas de teclado em resposta
eletrônica com LCD, LEDs e circuitaria dedicada. Desenvolvido durante o
curso Técnico em Mecatrônica (ETEP).

> **Documentação de protótipo.** Este repositório contém a descrição e
> imagens do projeto. O firmware original ainda não está disponível;
> não é possível compilar ou reproduzir o controle a partir deste snapshot.

## Material disponível

| Conteúdo | Disponibilidade |
|---|---|
| Descrição, componentes e contexto | Neste README |
| Imagens do projeto | [img/](img/) |
| Código-fonte / firmware original | Ainda não disponível |

## 🎯 Descrição do Projeto

A experiência de tocar depende de ler comandos físicos com consistência e
devolver uma resposta imediata que una som, indicação visual e informação
no display. O sistema mapeia as entradas do teclado para notas musicais e
coordena a saída eletrônica, o LCD e os LEDs como uma única interface
musical — unindo leitura de entradas, lógica de firmware, resposta visual
e uma placa de circuito dedicada.

## 🔁 Resposta a Cada Nota

1. Tecla pressionada
2. Leitura de entrada
3. Mapeamento da nota
4. Som e LEDs correspondentes
5. LCD atualiza

## 🖼️ Visão do Projeto

<p>
  <img src="img/piano_visual_1.png" width="24%" alt="Visão geral do protótipo do piano digital" />
  <img src="img/piano_visual_2.png" width="24%" alt="Detalhe do teclado e da interface eletrônica" />
  <img src="img/piano_visual_3.png" width="24%" alt="Circuito e placa dedicada do projeto" />
  <img src="img/piano_visual_4.png" width="24%" alt="Integração de LCD e LEDs no piano digital" />
</p>

## 🔧 Componentes de Hardware

- **Arduino** (unidade de controle)
- **Teclado** (entrada de notas)
- **Display LCD** (informação em tempo real)
- **LEDs** (sinalização visual)
- **PCB dedicada** (circuito impresso do projeto)

## 🛠️ Stack

`Arduino` · `C/C++` · `LCD` · `LEDs` · `PCB`

## 📦 Entregáveis do Protótipo

- Firmware Arduino
- Integração de LCD
- Sinalização visual por LEDs
- Protótipo eletrônico com placa de circuito dedicada

## 🎓 Contexto

Projeto desenvolvido durante o curso **Técnico em Mecatrônica** na
**ETEP**, como parte da formação em eletrônica, circuitos digitais e
desenvolvimento de placas de circuito impresso.

## 🤝 Autor

Desenvolvido por **Gustavo Nascimento**.
