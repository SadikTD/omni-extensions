<div align="center">

<img src="icon/eu.kanade.tachiyomi.animeextension.all.omni.png" width="128" alt="Omni icon">

# Omni

**One extension for anime, dramas, and movies in [Aniyomi](https://github.com/aniyomiorg/aniyomi).**

</div>

## Install

In Aniyomi, go to **More → Settings → Browse → Anime extension repos → Add**, and paste:

```
https://raw.githubusercontent.com/SadikTD/omni-extensions/main/index.min.json
```

Then open **Browse → Anime Extensions** and install **Omni**.

## What's inside

| Section | Sources |
|---|---|
| Anime (sub & dub) | AnimePahe, Hianimes, AnimeHeaven, Gogoanime, Anidap, Animex, AllAnime |
| K/C-Dramas | MyAsianTV |
| Movies & TV | FboxTV, Movies2Watch, Vidbox, Watchroo, FlixHub |

## Features

- **Automatic fallback.** If a source has no working video for an episode, Omni finds the same show
  and episode on another source in the same section and plays that instead. Dramas fall back to the
  movie & TV sources too.
- **Fastest server first.** Servers are timed when an episode opens and the quickest is tried first.
- **Hands-free Cloudflare.** AnimePahe passes its Cloudflare check without opening WebView.
- **Checked daily.** Every source is probed once a day; breakages are flagged automatically.

Both Omni features can be switched off per source under the source's settings.

AllAnime asks for a Security Check before playing its own servers. Omni plays those episodes from
another source automatically; to use AllAnime's own servers, open the episode in WebView and pass the
check yourself.

## Credits

Omni bundles source code from
[salmanbappi/sb-extensions-source](https://github.com/salmanbappi/sb-extensions-source),
which builds on the work of the Aniyomi and Keiyoushi extension communities.
Licensed under the [Apache License 2.0](LICENSE).

Omni does not host any content and is not affiliated with Aniyomi or with any of the sites it reads from.
