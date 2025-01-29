# Virtual Voice Assistant

Este é um assistente de voz simples, desenvolvido em Python, que pode realizar várias funções, como procurar no YouTube, pesquisar no Wikipedia, contar piadas, reproduzir música, entre outras. O assistente utiliza várias bibliotecas, como `gTTS`, `speech_recognition`, `pyjokes`, `wikipedia`, `pygame`, e outras para reconhecer comandos de voz e executar ações correspondentes.

## Funcionalidades

- **Reconhecimento de fala:** O assistente escuta os comandos de voz do usuário e os converte em texto.
- **Respostas por voz:** O assistente usa a biblioteca `gTTS` para responder em voz ao usuário.
- **Ações baseadas em comandos:** O assistente pode realizar várias ações, como:
  - Pesquisar no YouTube.
  - Pesquisar na Wikipedia.
  - Contar piadas.
  - Esvaziar a Lixeira.
  - Reproduzir música.
  - Informar a hora atual.

### Requisitos

Certifique-se de ter as seguintes bibliotecas instaladas:

```bash
pip install gTTS
pip install playsound
pip install pyjokes
pip install wikipedia
pip install pyaudio
pip install pipwin
pipwin install pyaudio
pip install sounddevice
