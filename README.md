# Geração de Animações em uma Matriz de LEDs 5x5

Este projeto faz parte da atividade obrigatória da unidade 4 do curso Embarcatech em sistemas embarcados e tem como objetivo utilizar o simulador Wokwi, o microcontrolador Raspberry Pi Pico W, e um teclado matricial 4x4 para controlar animações em uma matriz de LEDs coloridos 5x5 WS2812.

## Descrição do Projeto:

Neste projeto, você deverá utilizar os seguintes componentes conectados à placa BitDogLab:
1. Matriz 5x5 de LEDs (endereçáveis) WS2812, conectada à GPIO 7.
2. LED RGB, com os pinos conectados às GPIOs (11, 12 e 13).
3. Botão A conectado à GPIO 5.
4. Botão B conectado à GPIO 6.

# Funcionalidades do Projeto

1. O LED vermelho do LED RGB deve piscar continuamente 5 vezes por segundo.
2. O botão A deve incrementar o número exibido na matriz de LEDs cada vez que for pressionado.
3. O botão B deve decrementar o número exibido na matriz de LEDs cada vez que for pressionado.
4. Os LEDs WS2812 devem ser usados para criar efeitos visuais representando números de 0 a 9.
• Formatação fixa: Cada número deve ser exibido na matriz em um formato fixo, como
caracteres em estilo digital (ex.: segmentos iluminados que formem o número).
• Alternativamente, é permitido utilizar um estilo criativo, desde que o número seja claramente
identificável.

## Requisitos do Projeto
Para o desenvolvimento, devem ser seguidos os seguintes requisitos:
1. Uso de interrupções: Todas as funcionalidades relacionadas aos botões devem ser implementadas
utilizando rotinas de interrupção (IRQ).
2. Debouncing: É obrigatório implementar o tratamento do bouncing dos botões via software.
3. Controle de LEDs: O projeto deve incluir o uso de LEDs comuns e LEDs WS2812, demonstrando o
domínio de diferentes tipos de controle.
4. Organização do código: O código deve estar bem estruturado e comentado para facilitar o
entendimento.

## Componentes Utilizados

- **Teclado Matricial 4x4**: Dispositivo de entrada para seleção das animações e comandos.
- **Microcontrolador Raspberry Pi Pico W**: Responsável pelo processamento e controle do sistema.
- **Matriz de LEDs Coloridos (5x5 WS2812)**: Exibe as animações definidas.


---

## Pré-requisitos

- **Ambiente de Desenvolvimento:** VS Code configurado com o Kit de Desenvolvimento Pico SDK.
- **Simulador:** [Wokwi](https://wokwi.com) para simulação dos componentes.
- **Linguagem:** C.
- **Controle de Versão:** Git e GitHub para versionamento do código.

---

## Instruções de Uso

1. Clone este repositório:
   ```bash
   git clone <https://github.com/Chaves25/Tarefa1U427.git>
   ```

2. Abra o projeto no VS Code.

3. Configure o Pico SDK e o simulador Wokwi seguindo [esta documentação](https://wokwi.com/docs).

4. Compile e execute o código no simulador Wokwi.

---

## Vídeo Apresentação

Confira o vídeo demonstrativo do projeto: [Link para o vídeo](#)

---

### Checklist de Desenvolvimento
    

- [x] **Teclas de controle:** 

- [x] O LED vermelho do LED RGB deve piscar continuamente 5 vezes por segundo.
- [x] O botão A deve incrementar o número exibido na matriz de LEDs cada vez que for pressionado.
- [x] O botão B deve decrementar o número exibido na matriz de LEDs cada vez que for pressionado.
- [x] Os LEDs WS2812 devem ser usados para criar efeitos visuais representando números de 0 a 9.
- [x] Formatação fixa: Cada número deve ser exibido na matriz em um formato fixo, como
     caracteres em estilo digital (ex.: segmentos iluminados que formem o número). 

- [x] **Outras tarefas:**  
  - [x] Configuração do simulador Wokwi.  
  - [x] Configuração do ambiente de desenvolvimento no VS Code com Pico SDK.  
  - [x] Criação do repositório GitHub e documentação inicial.

---

