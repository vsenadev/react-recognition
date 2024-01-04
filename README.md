# React Recognition

Bem-vindo ao React Recognition! Esta aplicação, desenvolvida em Python, utiliza a biblioteca OpenCV e o DeepFace para reconhecer a emoção de uma pessoa com base em suas feições. A aplicação coloca um quadrado vermelho ao redor do rosto detectado e fornece informações sobre o estado emocional da pessoa.

## Funcionalidades

- **Reconhecimento de Emoções**: A aplicação analisa as expressões faciais da pessoa para determinar a emoção, como felicidade, tristeza, raiva, surpresa, entre outras.

- **Indicação Visual**: Um quadrado vermelho é desenhado ao redor do rosto detectado, proporcionando uma indicação visual da região analisada.

- **Feedback Emocional**: A aplicação fornece informações sobre o estado emocional da pessoa com base na análise das expressões faciais.

## Pré-requisitos

Certifique-se de ter o Python instalado em sua máquina antes de executar a aplicação.

Instale as bibliotecas necessárias utilizando o seguinte comando:

```bash
pip install -r requirements.txt
```

## Como Utilizar a Aplicação

1. Clone este repositório em sua máquina local.

    ```bash
    git clone https://github.com/vsenadev/react-recognition.git
    ```

2. Acesse o diretório da aplicação.

    ```bash
    cd react-recognition
    ```

3. Execute o script principal.

    ```bash
    python reactrecognition.py
    ```

4. A aplicação utilizará a câmera do dispositivo para capturar a imagem facial. Aguarde até que um rosto seja detectado.

5. Um quadrado vermelho será desenhado ao redor do rosto, e as informações sobre a emoção da pessoa serão exibidas no console.

## Tecnologias Utilizadas

[![My Skills](https://skillicons.dev/icons?i=py,css,js)](https://skillicons.dev)
- OpenCV
- DeepFace (modelo de treinamento para reconhecimento facial)

## Como Contribuir

Se você quiser contribuir para melhorar o Emotion Recognition App, sinta-se à vontade para:

- Abrir problemas para relatar bugs ou sugerir melhorias.
- Enviar solicitações de pull para corrigir problemas ou adicionar novos recursos.

Esperamos que esta aplicação ofereça uma experiência interessante ao analisar emoções faciais!
