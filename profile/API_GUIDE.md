## API ⚙
Essa sessão ensina como usar nossa API, veja abaixo:

### Vídeo do YouTube
Você pode pegar informações sobre um vídeo do **YouTube** com nossa API.

#### Exemplo
Você precisa fazer um *HTTP Request* do tipo **GET** na URL abaixo:
```
https://nighthouse.vercel.app/api/youtube
```

Você também precisa adicionar os parâmetros na URL. Por exemplo, neste caso, você precisa adicionar apenas o URL do vídeo. Então, insira na frente do link o parâmetro `url` e o seu valor (o link do vídeo).
```
https://nighthouse.vercel.app/api/youtube?url=https://www.youtube.com/watch?v=3adexmpmle42
```

### Clipe da Twitch
Você pode pegar informações sobre um clipe da **Twitch** com nossa API.

#### Exemplo
Você precisa fazer um *HTTP Request* do tipo **GET** na URL abaixo:
```
https://nighthouse.vercel.app/api/twitchClip
```

Você também precisa adicionar os parâmetros na URL. Por exemplo, neste caso, você precisa adicionar apenas o URL do clipe. Então, insira na frente do link o parâmetro `url` e o seu valor (o link do clipe).
```
https://nighthouse.vercel.app/api/twichClip?url=https://clips.twitch.tv/FlaccidCryGarbageCho-J783v1m
```
