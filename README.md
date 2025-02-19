# PROJETO: Assistente Virtual

Este projeto implementa um assistente virtual capaz de reconhecer comandos de voz, converter fala em texto e fornecer respostas utilizando Wikipedia, YouTube e localização de farmácias próximas.

## Funcionalidades
- **Conversão de texto para fala (TTS)** usando Google Text-to-Speech (gTTS).
- **Reconhecimento de fala (STT)** com SpeechRecognition e PyAudio.
- **Busca na Wikipedia** para fornecer informações resumidas sobre um tópico.
- **Pesquisa no YouTube** e geração de links para vídeos.
- **Localização de farmácias próximas** utilizando geolocalização.

## Requisitos
Este projeto requer Python 3 e as seguintes bibliotecas:

```
pip install -r requirements.txt
```

## Instalação e Uso
1. Clone este repositório:
   ```sh
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>
   ```
2. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```
3. Execute o script principal:
   ```sh
   python assistente_virtual.py
   ```

## Dependências
As bibliotecas necessárias estão listadas no arquivo `requirements.txt`. Certifique-se de que elas estão instaladas antes de rodar o código.

## Autores
- Criado por: [Seu Nome]
- Última atualização: [Data]

## Licença
Este projeto está sob a licença MIT.
