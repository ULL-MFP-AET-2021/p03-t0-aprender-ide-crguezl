# Curriculum Vitae

## datos Personales

**Nombre:** Casiano Rodríguez León

![](images/casianorodriguezleon2.png)

* Color favorito: {{ site.color }}

* Mi emoji: :rocket:

## Estudios

* {{site.estudios[0]}}
* {{ site.estudios[1]}}

## Asignaturas

{% for asignatura in site.data.teaching.subjects %}

* {{ asignatura}}

{% endfor %}

## Deportes Favoritos

{% for sport in site.data.teaching.sports %}
* {{ sport }}
{% endfor %}}

## Repl.it

[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3511572&assignment_repo_type=AssignmentRepo)
