# Assistente de Dublagem Automática de Vídeos

Este projeto oferece um assistente de dublagem automática que converte vídeos do inglês para o português brasileiro usando tecnologias avançadas de IA.

## 🚀 Acesso Rápido

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ssousa455/video-dubbing-assistant/blob/main/video_dubbing_assistant.ipynb)

## 🚀 Funcionalidades

- Extração de áudio de vídeos
- Transcrição de áudio em inglês
- Tradução do texto para português brasileiro
- Geração de áudio em português com várias opções de vozes
- Substituição do áudio original pelo áudio dublado

## 🛠️ Tecnologias Utilizadas

- **FFmpeg**: Manipulação de áudio e vídeo
- **Whisper (OpenAI)**: Transcrição de áudio
- **Google Cloud Text-to-Speech**: Síntese de voz de alta qualidade
- **Google Cloud Translate**: Tradução precisa de texto
- **MoviePy & Pydub**: Processamento de áudio e vídeo em Python
- **spaCy**: Processamento de linguagem natural

## 📋 Pré-requisitos

- Python 3.7+
- Conta no Google Cloud com as APIs Text-to-Speech e Translate ativadas
- FFmpeg instalado no sistema

## 🔧 Instalação

1. Clone o repositório:  git clone https://github.com/ssousa455/video-dubbing-assistant.git

2. Instale as dependências: pip install -r requirements.txt

3. Configure as credenciais do Google Cloud:
- Crie um projeto no [Console do Google Cloud](https://console.cloud.google.com/)
- Ative as APIs Cloud Text-to-Speech e Cloud Translation
- Crie uma chave de conta de serviço e baixe o arquivo JSON
- Renomeie o arquivo para `google_cloud_credentials.json` e coloque-o na pasta `Dubbing` do seu Google Drive

## 🎬 Como Usar

1. Faça upload do vídeo que deseja dublar para a pasta `Dubbing` no seu Google Drive
2. Abra o notebook `video_dubbing_assistant.ipynb` no Google Colab
3. Execute as células do notebook em ordem
4. Siga as instruções para selecionar o vídeo e escolher a voz para dublagem
5. Aguarde o processo de dublagem ser concluído
6. O vídeo dublado será salvo na pasta `Dubbing` do seu Google Drive

## 📝 Notas

- Este projeto foi desenvolvido para uso no Google Colab, aproveitando seus recursos de GPU para processamento mais rápido
- O tempo de processamento pode variar dependendo do tamanho do vídeo e da capacidade de processamento disponível
- Certifique-se de ter espaço suficiente no seu Google Drive para o vídeo original e o dublado

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 🙏 Agradecimentos

- OpenAI pelo modelo Whisper
- Google Cloud pela infraestrutura de tradução e síntese de voz
- Comunidade de código aberto pelas excelentes bibliotecas utilizadas

---

**Observação**: Este projeto foi desenvolvido com a assistência do Claude 3.5 Sonnet, um modelo de linguagem avançado da Anthropic.

