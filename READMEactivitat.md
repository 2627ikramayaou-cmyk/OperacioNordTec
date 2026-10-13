# Operador Nord Tec Ikram Ayaou ASIX 1r B
## Índex:

1. Aquesta és l'activitat en el GitHub [GitHub READMEactivitat.md](https://github.com/2627ikramayaou-cmyk/OperacioNordTec/blob/main/READMEactivitat.md).
2. Enunciat de l'activitat [Activitat: Esquema README.md](https://educaciodigital.cat/iticbcn/moodle/mod/page/view.php?id=78294).

### Recursos:
1. [Guia de sintaxi Makdown](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax?utm_source=chatgpt.com)
2. [hackmd.io markdown](https://educaciodigital.cat/iticbcn/moodle/mod/url/view.php?id=77607)

## Estat del projecte: 
> **Indicant què s'ha fet i què està pendent**

### Què s'ha fet:
- [x] Creació i inicialització del repositori a GitHub amb `git init`.
- [x] Configuració de la branca principal (`main`) i connexió amb el repositori remot (`git remote add origin`).
- [x] Creació de l'estructura bàsica del fitxer `README.md` utilitzant Markdown.
- [x] Documentació de les primeres comandes de control de versions (`git status`, `git add`, `git commit`, `git push`).

### Què està pendent (Pròximes fases del projecte):
- [ ] Dissenyar i desplegar l'arquitectura de la infraestructura i de l'aplicació per a la nova empresa.
- [ ] Integrar i detallar la informació de xarxa amb les adreces IP definitives a la secció corresponent.
- [ ] Afegir els fitxers de configuració detallats de les següents fases del curs.
- [ ] Incorporar les captures de pantalla i comandes addicionals a mesura que avancin les peticions del client.

## Arquitectura de xarxa

<img src="/img/img2.png" alt="Esquema de la xarxa" width="500">

## Configuracions

>Durant aquesta pràctica hem treballat amb fitxers de configuració de sistemes Linux i comandes de control de versions a través de la terminal de Visual Studio Code.

### Comandes bàsiques de Git utilitzades:
- `git status`: Comprova quins fitxers s'han modificat o estan pendents de pujar.
- `git add .`: Prepara i afegeix tots els fitxers modificats per al proper commit.
- `git commit -m "missatge"`: Desa els canvis localment amb una descripció clara.
- `git push origin main`: Puja els canvis definitius al repositori remot de GitHub.

---

## Incidències i solucions

### 1. Error de sintaxi en les comandes de Git
- **Missatge d'error exacte:** `git: 'estatus' is not a git command. See 'git --help'.` (també amb `gir`).
- **Quan (fase i context):** Durant la fase inicial de proves a la terminal de VS Code mentre s'introduïen comandes ràpidament.
- **Causa:** Simple error de tecat (typo) al escriure `estatus` en comptes de `status`, o `gir` en comptes de `git`.
- **Solució:** Es va corregir tornant a escriure correctament la comanda (`git status` i `git remote -v`).

---

## Decisions tècniques

- **Ús de Markdown:** S'ha triat Markdown (`.md`) per documentar el projecte perquè s'integra nativament a GitHub, permetent una lectura neta i estructurada amb taules, llistes de tasques i alertes visuals.
- **Visual Studio Code:** S'ha utilitzat VS Code com a entorn de treball principal gràcies a la seva terminal integrada i el control de versions de Git integrat, facilitant el flux de treball de pujada de canvis.

---

## Reflexions tècniques

Aquesta activitat ens ajuda a entendre la importància de portar un control de versions rigorós mitjançant Git i GitHub. Aprendre a documentar pas a pas les incidències i l'estat del projecte facilita molt la detecció d'errors i millora la col·laboració tècnica en l'àmbit d'administració de sistemes.

---