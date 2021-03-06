[![Run on Repl.it](https://repl.it/badge/github/DeltaCoderr/KarmaBot)](https://repl.it/github/XdayronDev/G-Music)
[![Discord](https://img.shields.io/discord/658113349384667198.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/e9E8zBYXJf)
[![](https://img.shields.io/badge/discord.js-v12.0.0--dev-blue.svg?logo=npm)](https://discord.js.org/#/)
![logo](https://i.imgur.com/73OfCtg.png)

# 🤖 G-Music (Bot de Musica Discord)
> G-Music es un bot de musica construido con discord.js y usa Comandos  Handler para [Guia de Discord.js](https://discordjs.guide)

## Invite the Bot 💕

<a href="https://top.gg/bot/863573454920613929">
    <img src="https://top.gg/api/widget/863573454920613929.svg" alt="G-Music Bot" />
</a>

## Status 📥

[![Estado](https://top.gg/api/widget/status/863573454920613929.svg)](https://top.gg/bot/863573454920613929)
[![Servidores](https://top.gg/api/widget/servers/863573454920613929.svg)](https://top.gg/bot/863573454920613929)
[![Lib](https://top.gg/api/widget/lib/863573454920613929.svg)](https://top.gg/bot/863573454920613929)
[![Owner](https://top.gg/api/widget/owner/863573454920613929.svg)](https://top.gg/bot/863573454920613929)

## Requerimientos

1. Discord Bot Token **[Guia](https://portalmybot.com/guia/mybot/cuenta-discord)**
2. YouTube Data API v3 Key **[Guia](https://developers.google.com/youtube/v3/getting-started)**  
2.1 **(Opcional)** Soundcloud Client ID **[Guia](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v14.0.0 o mas reciente

## 🚀 Para empezar



```
git clone https://github.com/XdayronDev/G-music.git
cd G-Music Public
npm install
```

Una vez finalizada la instalación, puedes usar `node index.js` para iniciar el bot.

## ⚙️ Configuracion

Copia y renombra `config.json.ejemplo` a `config.json` y complete los valores:

⚠️ ** Nota: Nunca confíe ni comparta públicamente sus claves de token o API ** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "!",
  "PRUNING": false,
  "LOCALE": "es",
  "DEFAULT_VOLUME": 100,
  "STAY_TIME": 30
}
```

Idiomas que encontraras:
- Ingles (en)
- Arabica (ar)
- Portugués brasileño (pt_br)
- Holandes (nl)
- Frances(fr)
- Aleman (de)
- Italiano (it)
- Coreano (ko)
- Polaco (pl)
- Ruso (ru)
- Chino Simplificado (zh_cn)
- Español (es)
- Sueco(sv)
- Chino Tradicional (zh_tw)
- Turco (tr)
- Vietnamita (vi)


## 📝 Funciones y Comandos

> Nota: el prefix predeterminado es '!'

* 🎶 Reproducir música de YouTube a través de URL

`!play https://www.youtube.com/watch?v=doLMt10ytHY`

* 🔎 Reproducir música de YouTube a través de una consulta de búsqueda

`!play fiel rmx`

* 🎶 Reproducir música de Soundcloud a través de URL

`!play https://soundcloud.com/imerickfinesse-742386424/lagrimas-de-un-mal`

* 🔎 Busca y selecciona música para reproducir

`!search lagrimas de un mal`

Responda con el número de la canción o los números separados por comas que desea reproducir

Ejemplos: `1` o` 1,2,3`

* 📃 Reproducir listas de reproducción de youtube a través de URL

`!playlist https://www.youtube.com/watch?v=kPc3Pe42bGI&list=PLkqz3S84Tw-SgB7NcQjqpvE_z6veqjAu6`

* 🔎 Reproducir listas de reproducción de youtube a través de una consulta de búsqueda

`!playlist Oasis jbalvin playlist`
* Now Playing (!np)
* Cola de reproduccion (!queue, !q)
* Bucle / Repetir (!loop)
* Shuffle (!shuffle)
* Control de Volumen(!volume, !v)
* Lyrics (!lyrics, !ly)
* Pausar (!pause)
* Resumir (!resume, !r)
* Saltar (!skip, !s)
* Saltar a la canción n. # en la cola (!skipto, !st)
* Mover una canción en la cola (!move, !mv)
* Eliminar la canción n.# de la cola (!remove, !rm)
*Reproducir un clip de mp3 (!clip song.mp3) (poner el archivo en la carpeta de sonidos)
* Lista de todos los clips (!clips)
* Mostrar api ping (!ping)
* Mostrar el tiempo de actividad del bot (!uptime)
* Alternar la eliminación de mensajes de bot (!pruning)
* Localización en mas de 6 idiomas
* Ayuda (!help, !h)
* Creado con comandos handler, Gracias a [Guia de Discord.js](https://portalmybot.com/guia/mybot/inicio)
* Controles de medios a través de reacciones

![Reacciones](https://i.imgur.com/ptTCcS4.png)
* **Tiene Preguntas/Sugerencias? Te respondemos en el servidor de soporte**
</br></br>
<a href="https://discord.gg/e9E8zBYXJf"><img src="https://invidget.switchblade.xyz/e9E8zBYXJf"/></a>
<br><br>
