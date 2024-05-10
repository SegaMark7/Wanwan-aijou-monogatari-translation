# РУС
### Описание
В данном репозитории собранны файлы которые помогут перевести игру Wanwan aijou monogatari выходившей на casio loopy на другие языки 
### Структура
Для более удобного парсинга перевода игры, перевод записан в формате json.
Структура json
- "frameNum": n,
n - это номер кадра, кадром считается одно изображение.
- "name"
название кадра
- "text"
массив объектов строк, которые содержат текст на различных языках
в формате: "две буквы кода языка из [ISO 639 language codes](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes)" : "текст перевода"


# ENG
### Description
In this repository you can find files that will help you translate the Wanwan aijou monogatari game that came out on casio loopy to other languages
### Structure
For easier parsing of the translation of the game, the translation is written in json format.
Json structure
- "frameNum": n,
n - is the number of the frame, a frame is one of the images.
- "name"
name of the frame
- "text"
array of objects that contain text on different languages
in the format: "two letters language code from [ISO 639 language codes](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes)" : "translation text"
