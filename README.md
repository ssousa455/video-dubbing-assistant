# Assistente de Dublagem Automática de Vídeos

Este projeto dubla vídeos do inglês para português brasileiro usando IA. Processa todos os vídeos na pasta "Dubbing" do seu Google Drive e salva os resultados em "Dubbing/Results".

## 🚀 Experimente agora!

1. **Abra no Colab:** Clique no link abaixo para abrir o notebook no Google Colab.

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ssousa455/video-dubbing-assistant/blob/main/video_dubbing_assistant.ipynb)

2. **Copie para o Drive:** Copie o notebook para o seu Google Drive.

3. **Prepare os arquivos:**

    - **Vídeos:** Coloque os vídeos a serem dublados na pasta "Dubbing" do seu Google Drive.
    - **`google_cloud_credentials.json`:**  Este arquivo contém suas credenciais do Google Cloud.  Para obtê-lo:
        1. Crie um projeto no [Google Cloud Console](https://console.cloud.google.com/).
        2. Ative as APIs Cloud Text-to-Speech e Cloud Translation.
        3. Crie uma chave de conta de serviço.  (Veja este vídeo para um guia visual: [Como criar a chave de conta de serviço](https://www.youtube.com/watch?v=rWcLDax-VmM)).  Baixe o arquivo JSON resultante.
        4. Renomeie o arquivo para `google_cloud_credentials.json` e coloque-o na pasta "Dubbing" do seu Google Drive.

4. **Execute:** No Colab, selecione `Ambiente de execução > Executar tudo`. Aguarde a conclusão do processo. Os vídeos dublados estarão em `Dubbing/Results`.

**(Observação: para melhores resultados, considere usar o modelo `large-v3` do Whisper, se disponível.)**


## Tecnologias

- FFmpeg
- Whisper (OpenAI)
- Google Cloud Text-to-Speech
- Google Cloud Translate
- MoviePy & Pydub
- spaCy


## Pré-requisitos

- Conta Google Cloud com APIs Text-to-Speech e Cloud Translation ativadas.
- FFmpeg instalado (o Colab geralmente já o tem).


## Agradecimentos

- OpenAI
- Google Cloud
- Comunidade open source
- [poe.com](https://poe.com/) (Gemini 1.5 Flash 128k)
