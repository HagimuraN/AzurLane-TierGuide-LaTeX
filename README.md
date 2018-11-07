# Azur Lane Tier Guide LaTeX
Azur Lane JP and EN tier guide formatted with LaTeX.

Text taken from:<br/> 
<https://pastebin.com/ZMBi8g6R><br/>
<https://pastebin.com/bffW2aNa><br/> 
(06-11-2018)

Images taken from:<br/> 
<https://azurlane.koumakan.jp/List_of_Ships_by_Image>

Use `\entry` macro to add ships:
```
\entry{Ship Name}[image-name.png]
{Skill Text}
{Description Title}
{Description Text}
```

## Compilation Note
Comment/uncomment the `\input{...}` part in main.tex to choose between JP/EN tier guide.

Cyrillic package needed.
