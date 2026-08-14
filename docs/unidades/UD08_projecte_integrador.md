# UD08. Projecte integrador: desenvolupament d’una solució digital completa

## 1. Context i relació amb el currículum
**Blocs de sabers bàsics treballats:**
- Bloc 1: Programació (disseny, implementació i depuració).
- Bloc 2: Sistemes informàtics (configuració i ús eficient de dispositius).
- Bloc 3: Xarxes (connectivitat, proves i serveis).
- Bloc 4: Ciutadania digital (seguretat, privacitat i ús responsable).

**Competències específiques relacionades:**
- CE1: Utilitzar de manera responsable i segura els sistemes digitals.
- CE2: Desenvolupar solucions digitals aplicant estratègies de programació.
- CE3: Analitzar riscos i aplicar mesures de protecció en entorns digitals.
- CE4: Formular i implementar algorismes coherents en projectes reals.

## 2. Objectius d’aprenentatge
- Integrar coneixements de tot el curs en un projecte complet.
- Dissenyar, implementar i documentar una solució digital funcional.
- Treballar en equip utilitzant eines de col·laboració.
- Aplicar bones pràctiques de seguretat i privacitat.
- Presentar i justificar les decisions tècniques del projecte.

## 3. Sabers bàsics de la unitat
- Planificació de projectes digitals.
- Disseny d’algorismes i estructures modulars.
- Implementació de programari en Python.
- Gestió de fitxers, dades i serveis en xarxa.
- Documentació tècnica i presentació del projecte.
- Bones pràctiques de seguretat i manteniment.

## 4. Desenvolupament de la unitat

### 4.1. Introducció
El projecte integrador és l’activitat final del curs. L’alumnat haurà de crear una solució digital que combine programació, gestió de dades, ús de serveis en xarxa i mesures de seguretat. El projecte es realitzarà en grups i inclourà una presentació final.

### 4.2. Proposta de projecte
Cada grup haurà de desenvolupar una aplicació o sistema senzill que complisca els següents requisits:

- Tindre **una part de programació** (Python).
- Utilitzar **fitxers o dades** (lectura, escriptura o processament).
- Incloure **interacció amb algun servei en xarxa** (API, consulta DNS, etc.).
- Incorporar **mesures de seguretat** (validació, contrasenyes, permisos).
- Presentar **documentació tècnica** i **memòria final**.

Exemples de projectes:
- Gestor de notes amb contrasenya i còpia en el núvol.
- Aplicació que analitze l’estat de la xarxa i genere un informe.
- Joc senzill modular amb estadístiques guardades en fitxer.
- Sistema de validació d’usuaris amb registre d’activitat.

### 4.3. Exemples pràctics

```python
# Exemple: gestor simple de notes amb contrasenya
contrasenya = "1234"

entrada = input("Introdueix la contrasenya: ")
if entrada == contrasenya:
    nota = input("Escriu la teua nota: ")
    with open("notes.txt", "a") as f:
        f.write(nota + "\n")
    print("Nota guardada correctament.")
else:
    print("Contrasenya incorrecta.")
```

```bash
# Exemple: comprovació de l'estat de la xarxa
ping 8.8.8.8
```

```bash
nslookup www.wikipedia.org
```

### 4.4. Procediments i habilitats treballades

- Planificar un projecte digital real.

- Dividir el projecte en tasques i assignar rols.

- Programar de manera modular i documentada.

- Integrar funcionalitats de xarxa i gestió de dades.

- Presentar i defensar decisions tècniques.

## 5. Activitats

### 5.1. Activitats guiades

1. Dissenya l’estructura del projecte: objectiu, funcionalitats i fases.

2. Crea un diagrama de flux del procés principal del programa.

### 5.2. Activitats d’ampliació

1. Afig una funcionalitat extra al projecte (estadístiques, interfície, etc.).

2. Implementa un sistema de permisos o validació avançada.

### 5.3. Activitats d’aplicació real

1. Presenta el projecte davant la classe explicant decisions tècniques.

2. Publica el projecte en un repositori (GitHub) amb documentació completa.

## 6. Instruments i criteris d’avaluació

### Instruments:

- Rúbrica del projecte.

- Documentació tècnica.

- Presentació oral.

- Observació del treball en equip.

### Criteris (vinculats a CE):

- CE1 → Aplica mesures de seguretat en el projecte.

- CE2 → Implementa una solució digital funcional.

- CE3 → Analitza riscos i proposa mesures de protecció.

- CE4 → Formula i implementa algorismes coherents i modulars.

## 7. Recursos

- Replit, GitHub, VS Code.

- Documentació de Python.

- Eines de col·laboració (Drive, Teams).

## 8. Autoavaluació de l’alumnat

- He contribuït activament al projecte?

- El codi és modular i entenedor?

- Hem aplicat mesures de seguretat?

- La documentació és clara i completa?

## 9. Glossari

- Projecte integrador: activitat final que combina tots els sabers del curs.

- Documentació tècnica: explicació del funcionament del programa.

- API: interfície per comunicar-se amb serveis en xarxa.