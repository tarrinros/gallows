## Программа "Виселица"

Попробуй угадать загаданное слово по одной букве за ход.
Всего 7 попыток до того, как твою шею обовьет веревка.

----------------------------------------------------------------------------

Программа написана на __ruby 2.5.1__

Для того, чтобы она работала, необходимо установить интерпрeтатор [ruby]
(https://www.ruby-lang.org/en/news/2018/03/28/ruby-2-5-1-released)



Для запуска программы необходимо набрать команду в __cmd__ или __terminal__

`ruby gallows.rb`

----------------------------------------------------------------------------

`gallows.rb` - иосновной файл программы

`game.rb` - файл с классом __"Game"__, отвечающим за обработку игры

`word_reader.rb` - файл с классом __"WordReader"__, отвечающим считывание 
данных 
из файла со словами.

`result_printer.rb` - файл с классом __"ResultPrinter"__, отвечающим за 
обработку и вывод резутата.

`./data/words.txt` - текстовый файл, в который вы можете добавлять слова, 
которые программа будет загадывать.

`./image/*.txt` - файлы с текствой графикой (виселица) для разных этапов игры.
