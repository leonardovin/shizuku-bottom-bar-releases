# AutoPanel

**As três telas do seu Haval H6, trabalhando juntas.** Em teste beta.

[![Assista ao vídeo do AutoPanel](media/autopanel-poster.jpg)](https://drive.google.com/file/d/1Y-6_BrS857P7v4lqmCF8CB2jefNrbtLI/view?usp=sharing)

▶️ [Assista ao vídeo de apresentação (1min42s)](https://drive.google.com/file/d/1Y-6_BrS857P7v4lqmCF8CB2jefNrbtLI/view?usp=sharing) · [baixar o .mp4](media/autopanel.mp4)

📘 **[Manual de instalação e uso](https://tinyurl.com/28qooy2m)**: o passo a passo completo, com as telas do app.

## Instalar

1. **Instale o Impulse primeiro.** Siga o guia do Impulse no canal dos Havaleiros. Ele já deixa o Shizuku e o frida prontos.
2. No Impulse, abra **Instalar Apps** e digite no campo **URL do APK**:

   ```
   https://github.com/leonardovin/shizuku-bottom-bar-releases/releases/latest/download/haval-bottom-bar-latest.apk
   ```

3. Toque no botão ao lado do campo e espere a instalação terminar.
4. Abra o **AutoPanel Shizuku**, toque em **Li e concordo** e dê as duas permissões pedidas: **Sobreposição de tela** e **Permissão Shizuku**.

Depois disso, as atualizações chegam pelo próprio app. Todas as versões ficam na [página de releases](https://github.com/leonardovin/shizuku-bottom-bar-releases/releases).

## O que ele faz

**Na central**
- Uma barra com clima, bancos e modos de condução sempre à mão, embaixo de qualquer app.
- Centro de controle: condução, potência, direção, regeneração, bancos, volume e brilho numa tela só.
- Gesto de três dedos: para cima ou para baixo ajusta a temperatura; para os lados, a ventilação.
- Ao trocar entre ECO, NORMAL e SPORT, a animação do carro acompanha o modo.

**No painel: Rich Cluster**

O Rich Cluster é uma segunda transmissão de vídeo do CarPlay ou do Android Auto, feita só para o painel de instrumentos, no formato largo dele e separada da central. Não é espelhamento: você pode ter música ou ligação na central e o mapa no painel ao mesmo tempo.

- **Somente mapa:** um recorte do mapa no centro do painel.
- **Mapa full:** o mapa ocupa o painel inteiro, por baixo do velocímetro.
- Camadas, tamanho e posição ajustáveis pelo app.

**No HUD**
- A seta de navegação do CarPlay ou do Android Auto mostra a próxima curva na altura dos olhos.
- **Dica:** desative o tema do Impulse por enquanto. Ele desliga o serviço do sistema que projeta as setas.

Cada recurso pode ser ligado ou desligado separadamente.

## Requisitos

- Haval H6 com a central Android de fábrica.
- [Impulse](https://github.com/bobaoapae/haval-app-tool-multimidia) instalado: ele traz o [Shizuku](https://shizuku.rikka.app/) e o frida.
- Root: não precisa fazer nada, o app consegue o acesso sozinho pelo Shizuku.
- Celular com CarPlay ou Android Auto, para o mapa no painel e a seta no HUD.

## Aviso

Projeto independente e não oficial, sem vínculo com a Haval, a GWM ou os desenvolvedores do Shizuku. Use por sua conta e risco: pode afetar a garantia do carro. Não mexa no app enquanto dirige.
