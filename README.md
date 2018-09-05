# gdocs-pdf-exporter
Export multiple google docs as pdf files

First  - create client_secret.json file as described here, for example:
https://developers.google.com/api-client-library/python/guide/aaa_oauth

Put this file next to main.go .

Now execute :
go run main.go <pattern>
  
The app will find all doc files matching the pattern and download them to your current directory as pdfs.
