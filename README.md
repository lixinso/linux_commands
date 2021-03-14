# Common Used Linux Commands

- split zip file

zip MyArchive.zip inputfolder/
zip MyArchive.zip --out SplitArchive.zip -s 100m

- curl

$ curl -LI http://www.example.org -o /dev/null -w '%{http_code}\n' -s

https://superuser.com/questions/272265/getting-curl-to-output-http-status-code
