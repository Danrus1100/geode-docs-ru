***
![Geode Logo](https://github.com/geode-sdk.png?size=80) 

**Geode** ([Произносится](https://www.google.com/search?q=geode+how+to+pronounce&sca_esv=28bf11c19ea21427&sca_upv=1&sxsrf=ACQVn08-mIYi3HyV1dAKLj2WzL05pgWkQw%3A1712173924896&source=hp&ei=ZLMNZsi-NMr_wPAP-aO1iA4&iflsig=ANes7DEAAAAAZg3BdB52-0MQfjL0daHxMWG4Ce9YsB2g&udm=&oq=Geode+how+&gs_lp=Egdnd3Mtd2l6IgpHZW9kZSBob3cgKgIIADIKECMYgAQYigUYJzIIEAAYgAQYywEyCBAAGIAEGMsBMggQABiABBjLATIIEAAYgAQYywEyCBAAGIAEGMsBMggQABiABBjLATIGEAAYFhgeMgYQABgWGB4yCBAAGBYYHhgPSP4dUABYzhVwAHgAkAEAmAFsoAHWBqoBAzguMrgBAcgBAPgBAZgCCqAC-AbCAgQQIxgnwgILEAAYgAQYsQMYgwHCAhEQLhiABBixAxiDARjHARjRA8ICCBAAGIAEGLEDwgIIEC4YgAQYsQPCAgsQLhiABBixAxjUAsICBRAAGIAEwgILEC4Y1AIYsQMYgATCAgUQLhiABMICCBAuGIAEGMsBmAMAkgcDOC4yoAfmZQ&sclient=gws-wiz) как Джиод) - Загрузчик модов и SDK для разработки модов для [Geometry Dash](https://store.steampowered.com/app/322170/Geometry_Dash/) с современным подходом разработки. Прошлые загрузчики просто инджектили (внедряли) DLL файлы и оставляли разработчиков заниматься остальными вопросами работы мода, а Geode же стримится стать более комплексным проектом, который сам управляет загруженными модами и хуками.

> Эта документация предназначена для **разработчиков**, которые хотят использовать для своих целей Geode. Если ты тот, кто просто хочет использовать моды, [посети главную страницу проекта](https://geode-sdk.org/install).

## Почему Geode?
***
Главная цель Geode - **положить конец несовместимости модов**, потому что традиционный моддинг очень легко приводил к такой проблеме, и Geode предлагает более эффективные решения этих проблем.

On top of this, and perhaps more interestingly, **Geode provides much better ergonomics for modding**. Instead of having to deal with calling conventions, trampolines, manually setting hooks (likely in another source file), you can have all the code relevant to hooks in a [nice, clean, readable syntax](/tutorials/modify.md) contained within a single source file.
К тому же, что интересно, Geode предоставляет улучшенную эргономику модов, вместо того чтобы идти на компромиссы с calling'ами, trampolin'ами и ручной установкой хуков, ты можешь при себе иметь весь код, относящийся к хукам, в красивом и читаемом синтаксисе в одном исходном файле.
## Help, Contributing, Etc.

If you need help using Geode or would like to contribute, feel free to join our [Discord Server](https://discord.gg/9e43WMKzhp).

Alternatively, if you hate joining Discord servers to work with a framework, you can also just **open up an issue or pull request** on any [Geode repository on Github](https://github.com/orgs/geode-sdk/repositories).

## Начало работы

See [Getting Started](/getting-started) for a step by step tutorial on getting started with Geode SDK.

See [Handbook](/handbook/chap0) for a beginner-friendly tutorial series on using Geode and GD Modding in general (WIP!!).

## Credits

### Contributors

<a href="https://github.com/geode-sdk/geode/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=geode-sdk/geode" />
</a>

### Special Thanks

 * [NachoBIT](https://github.com/TheNachoBIT)
 * [RobTop Games](https://twitter.com/RobTopGames/) for making this amazing game and providing us and so many others with hours of entertainment ❤
