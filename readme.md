# § Snipnote! Блокнот в браузере | Bookmarklet-notepad

![Snipnote preview](https://github.com/drugz/shipnote/raw/master/preview/snipnote_1.jpg)


Suddenly you need to urgently write down some important information after the call, and nothing but a browser is at hand. It takes a long time to search for a notebook or paper, and the link on the bookmark bar is always in sight. Create yourself a snippet link once and use it whenever and for as long as you want!

Вдруг потребуется срочно записать какую-нибудь важную информацию после звонка, а под рукой ничего кроме браузера. Блокнот или бумагу искать долго, а ссылка на панели закладок всегда на виду. Однажды создайте себе ссылку-сниппет и пользуйтесь когда и сколько захотите!

Проверено в Google Chrome, Mozilla Firefox
- Быстро создавай заметки в браузере
- Просматривай и редактируй заметки оффлайн
- Храни содержимое прямо в закладке просто перенося значок § на панель закладок
- Сохраняй текст или всю страницу в файл

Tested in Google Chrome, Mozilla Firefox
- Quickly create notes in the browser
- View and edit notes offline
- Store content directly in a bookmark by simply dragging the § icon to the bookmark bar
- Save text or entire page to file

Скопируйте код букмарклета в адресную строку браузера и нажмите Enter

Copy the bookmarklet code to the address bar of your browser and press Enter

```
data:text/html;charset=utf-8,<html><head><title>Snipnote!</title><link rel="shortcut icon"href="data:image/x-icon;base64,AAABAAEAEBACAAEAAQCwAAAAFgAAACgAAAAQAAAAIAAAAAEAAQAAAAAAAAAAABMLAAATCwAAAgAAAAAAAAAA3f8AAAAAAAAPZTV/7wAAQCNlNUArAAB/62VzQCtvbUArAGt/6wAAQCtlNUArAAB/62U1AAsAAN/7ZXPAAzg2//9DOv//cm8AD2Ftf+9pbEAjIChAKzYpf+tvbUArbiBAK2xlf+tDb0Arb25AK29nf+ttVwALMzLf+zpcwANvZ///bSD//2xl"/><script>w=window.webkitURL||window.URL;function s(){var d=new Date();return d.getFullYear()+'_'+(d.getMonth()+1)+'_'+d.getDate()+'_snipnote';}</script></head><body><a onmouseover="this.href='data:text/html;charset=utf-8,'+encodeURI(document.documentElement.innerHTML);"title="Snippet for browser Favorite">§</a><a onmouseover="this.setAttribute('download',s()+'.txt');this.href=w.createObjectURL(new Blob([document.getElementById('note').innerHTML],{type:'text/plain'}));"download="snipnote.txt">Save text</a><a onmouseover="this.setAttribute('download',s()+'.html');this.href=w.createObjectURL(new Blob([document.documentElement.innerHTML],{type:'text/html'}));"download="snipnote.html">Save page</a><a target="_blank"href="https://github.com/drugz/shipnote">@drug_z</a><note contenteditable id="note"> Snipnote!</note></body><style>body{background:cyan;font-family:calibri;}body *{padding:10px;}a{cursor:move;text-decoration:none;}note{margin:10px;display:block;min-height:77%;background:lightyellow;border-radius:5px;box-shadow:2px 2px 10px black;}</style></html>
```

Other link
```
data:text/html;charset=utf-8,%3Chead%3E%3Ctitle%3ESnipnote!%3C/title%3E%3Clink%20rel=%22shortcut%20icon%22%20href=%22data:image/x-icon;base64,AAABAAEAEBACAAEAAQCwAAAAFgAAACgAAAAQAAAAIAAAAAEAAQAAAAAAAAAAABMLAAATCwAAAgAAAAAAAAAA3f8AAAAAAAAPZTV/7wAAQCNlNUArAAB/62VzQCtvbUArAGt/6wAAQCtlNUArAAB/62U1AAsAAN/7ZXPAAzg2//9DOv//cm8AD2Ftf+9pbEAjIChAKzYpf+tvbUArbiBAK2xlf+tDb0Arb25AK29nf+ttVwALMzLf+zpcwANvZ///bSD//2xl%22%3E%3Cscript%3Ew=window.webkitURL%7C%7Cwindow.URL;function%20s()%7Bvar%20d=new%20Date();return%20d.getFullYear()+'_'+(d.getMonth()+1)+'_'+d.getDate()+'_snipnote';%7D%3C/script%3E%3C/head%3E%3Cbody%3E%3Ca%20onmouseover=%22this.href='data:text/html;charset=utf-8,'+encodeURI(document.documentElement.innerHTML);%22%20title=%22Snippet%20for%20browser%20Favorite%22%3E%C2%A7%3C/a%3E%3Ca%20onmouseover=%22this.setAttribute('download',s()+'.txt');this.href=w.createObjectURL(new%20Blob(%5Bdocument.getElementById('note').innerHTML%5D,%7Btype:'text/plain'%7D));%22%20download=%222021_7_27_snipnote.txt%22%20href=%22blob:null/c4bfa361-eb79-44ae-99f9-d6c541c12cca%22%3ESave%20text%3C/a%3E%3Ca%20onmouseover=%22this.setAttribute('download',s()+'.html');this.href=w.createObjectURL(new%20Blob(%5Bdocument.documentElement.innerHTML%5D,%7Btype:'text/html'%7D));%22%20download=%222021_7_27_snipnote.html%22%20href=%22blob:null/1c47682b-8674-4579-98b3-ebfc5023edbd%22%3ESave%20page%3C/a%3E%3Ca%20target=%22_blank%22%20href=%22https://github.com/drugz/shipnote%22%3E@drug_z%3C/a%3E%3Cnote%20contenteditable=%22%22%20id=%22note%22%3E%20Snipnote!%3C/note%3E%3Cstyle%3Ebody%7Bbackground:cyan;font-family:calibri;%7Dbody%20*%7Bpadding:10px;%7Da%7Bcursor:move;text-decoration:none;%7Dnote%7Bmargin:10px;display:block;min-height:77%25;background:lightyellow;border-radius:5px;box-shadow:2px%202px%2010px%20black;%7D%3C/style%3E%3C/body%3E
```

## Preview 
![Snipnote preview](https://github.com/drugz/shipnote/raw/master/preview/snipnote_2.jpg)
![Snipnote preview](https://github.com/drugz/shipnote/raw/master/preview/snipnote_3.jpg)
![Snipnote preview](https://github.com/drugz/shipnote/raw/master/preview/snipnote_4.jpg)
