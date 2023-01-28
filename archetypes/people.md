---
name: "{{ replace .Name "-" " " | title }}"
# you have to upload this image: static/img/people/{{ .Name }}.jpg
picture: /img/people/{{ .Name }}.jpg
status: (fill this in)
---
