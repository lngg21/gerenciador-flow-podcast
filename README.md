# Gerenciador de Podcast

# Funcionalidades
- Listar as sessões dos podcast em categorias(saúde, fitness, humor e etc).
- Filtrar episodios por nome.

# Implementação
Retornar em uma API REST(json) => nome do podcast, nome do episódio, imagem de capa, link


```js
[
{
    podcastName: "Flow",
    episode: "FLÁVIO AUGUSTO - Flow#489",
    cover: "https://i.ytimg.com/vi/L6w3vPY2mFE/hqdefault.jpg?sqp=-oaymwEnCNACELwBSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGBACGAY4AUAB&rs=AOn4CLDT2fZWpbFsL6TDiatLPeBpdbNOPA",
    link: "https://www.youtube.com/live/L6w3vPY2mFE?si=Za3RbGNBNnH8UFhP",
    category: ["finanças", "humor"]
}
]
```