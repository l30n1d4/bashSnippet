# bashSnippet
Bash Snippet


    $ echo string | gzip -cf | base64
    H4sIAF9Om14AAysuKcrMS+cCAG2jQ50HAAAA
    $ base64 -d <<<"H4sIAF9Om14AAysuKcrMS+cCAG2jQ50HAAAA" | gunzip
    string

### meteo
    $ curl http://wttr.in/parma?F2Q&lang=it
    $ curl http://wttr.in/moon?F&lang=it

### git
    $ git log --all --decorate --oneline --graph --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)'

### qrcore
    $ curl qrenco.de/test