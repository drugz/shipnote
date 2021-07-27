# § Snipnote! Блокнот в браузере

Вдруг потребуется срочно записать какую-нибудь важную информацию после звонка, а под рукой ничего кроме браузера. Блокнот или бумагу искать долго, а ссылка на панели закладок всегда на виду. Однажды создайте себе ссылку-сниппет и пользуйтесь когда и сколько захотите!

Проверено в Google Chrome, Mozilla Firefox
- Быстро создавай заметки в браузере
- Просматривай и редактируй заметки оффлайн
- Храни содержимое прямо в закладке просто перенося значок § на панель закладок
- Сохраняй текст или всю страницу в файл

Скопируйте ниже представленный код букмарклета в адресную строку браузера и нажмите Enter


```
data:text/html;charset=utf-8,<html><head><title>Snipnote!</title><link rel="shortcut icon"href="data:image/x-icon;base64,AAABAAEAEBACAAEAAQCwAAAAFgAAACgAAAAQAAAAIAAAAAEAAQAAAAAAAAAAABMLAAATCwAAAgAAAAAAAAAA3f8AAAAAAAAPZTV/7wAAQCNlNUArAAB/62VzQCtvbUArAGt/6wAAQCtlNUArAAB/62U1AAsAAN/7ZXPAAzg2//9DOv//cm8AD2Ftf+9pbEAjIChAKzYpf+tvbUArbiBAK2xlf+tDb0Arb25AK29nf+ttVwALMzLf+zpcwANvZ///bSD//2xl"/><script>w=window.webkitURL||window.URL;function s(){var d=new Date();return d.getFullYear()+'_'+(d.getMonth()+1)+'_'+d.getDate()+'_snipnote';}</script></head><body><a onmouseover="this.href='data:text/html;charset=utf-8,'+encodeURI(document.documentElement.innerHTML);"title="Snippet for browser Favorite">§</a><a onmouseover="this.setAttribute('download',s()+'.txt');this.href=w.createObjectURL(new Blob([document.getElementById('note').innerHTML],{type:'text/plain'}));"download="snipnote.txt">Save text</a><a onmouseover="this.setAttribute('download',s()+'.html');this.href=w.createObjectURL(new Blob([document.documentElement.innerHTML],{type:'text/html'}));"download="snipnote.html">Save page</a><a target="_blank"href="https://github.com/drugz/shipnote">@drug_z</a><note contenteditable id="note"> Snipnote!</note></body><style>body{background:cyan;font-family:calibri;}body *{padding:10px;}a{cursor:move;text-decoration:none;}note{margin:10px;display:block;min-height:77%;background:lightyellow;border-radius:5px;box-shadow:2px 2px 10px black;}</style></html>
```
