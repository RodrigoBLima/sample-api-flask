
<!-- VARS -->
[linkedin]: https://www.linkedin.com/in/rodrigo-barbosa-710b10180/,

[star-badge]: https://img.shields.io/github/stars/RodrigoBLima/sample-api-flask?color=8257E5&logo=github
[last-commit-badge]: https://img.shields.io/github/last-commit/RodrigoBLima/sample-api-flask?color=%238257E5
[codacy-badge]: https://app.codacy.com/project/badge/Grade/b2d32fa731984f3e9c3eaa814861c9db
[license-url]: https://github.com/RodrigoBLima/sample-api-flask/blob/master/LICENSE


# SIMPLE API FLASK

<div align="center">  

[![Linkedin Badge](https://img.shields.io/badge/-RodrigoBarbosa-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://https://www.linkedin.com/in/rodrigo-barbosa-710b10180/)][linkedin]
![Git Stars][star-badge]
![Last Commit][last-commit-badge]
![Codacy Quality][codacy-badge]

</div>

### Instale as dependencias do projeto

```
pip install requirements.txt
```

### Rode o Projeto localmente 
```
$ export FLASK_APP=main.py
 & 
$ flask run
```

### Execute o script start.sh para criar a imagem do Docker e construir um contêiner a partir da imagem resultante:

```
$ sudo bash start.sh
```

### Para recarregar o aplicativo,utilize a opção touch para ativar a condição:

```
$ sudo touch uwsgi.ini
```