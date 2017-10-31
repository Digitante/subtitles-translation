## License

[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)

## Info:

This is a repository for collective translation of subtitle files.

We use "self-proclaimed" multilanguage SRT format (.msrt)m where each line have prefix indicating translation language:

```
5
00:00:26,640 --> 00:00:30,640
[rus] Кажется, я снова уснула с открытым окном...
[eng] It seems I feel asleep with the window open, again...
[spa] Al parecer me quedé dormida con la ventana abierta de nuevo...

6
00:00:32,360 --> 00:00:35,360
[rus] Уфф... Как дует то...
[eng] Oh... It so windy...
[spa] Oh... Cuánto viento...
```

NOTE: The language codes are defined according to [ISO 639-3 standard](https://en.wikipedia.org/wiki/ISO_639:a)

With this repository we are providing a special utility (msrt_tool.py) which allows to extract any language as regular SRT subtitle file:

```./msrt_tool.py pepper-and-carrot-ep6.msrt eng -o pepper-and-carrot-ep6-en.srt```

## Translation status:

* pepper-and-carrot-ep6.msrt - [ACCEPTING-TRANSLATIONS]
* morevna-ep3.msrt - [ACCEPTING-TRANSLATIONS]
* synfig-course-promo.msrt - [ENGLISH-POLISHING, RUSSIAN-DRAFT, SPANISH-DRAFT]
