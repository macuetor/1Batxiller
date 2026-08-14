# UD04. Funcions i modularitat en la programació

## 1. Context i relació amb el currículum
**Blocs de sabers bàsics treballats:**
- Bloc 1: Programació (funcions, modularitat, reutilització de codi).
- Bloc 4: Ciutadania digital (ús eficient i responsable de recursos digitals).

**Competències específiques relacionades:**
- CE2: Desenvolupar solucions digitals aplicant estratègies de programació.
- CE4: Formular i implementar algorismes utilitzant estructures modulars.

## 2. Objectius d’aprenentatge
- Comprendre el concepte de funció i la seua utilitat.
- Crear funcions senzilles amb paràmetres i retorns.
- Modularitzar programes per fer-los més clars i reutilitzables.
- Entendre l’abast de les variables (local vs global).
- Millorar programes existents aplicant modularitat.

## 3. Sabers bàsics de la unitat
- Definició i crida de funcions.
- Paràmetres i valors de retorn.
- Modularitat i reutilització de codi.
- Variables locals i globals.
- Bones pràctiques en la creació de funcions.

## 4. Desenvolupament de la unitat

### 4.1. Introducció
Les funcions permeten dividir un programa en parts més xicotetes, clares i reutilitzables. Són essencials per organitzar el codi i evitar repeticions. En esta unitat aprendrem a definir-les, utilitzar-les i integrar-les en programes més complexos.

### 4.2. Continguts explicats

#### Què és una funció?
Una funció és un bloc de codi que realitza una tasca concreta i que pot ser reutilitzat.

#### Paràmetres i retorns
Els paràmetres permeten passar informació a la funció. El retorn envia un resultat de tornada.

#### Modularitat
Dividir un programa en funcions facilita la lectura, el manteniment i la reutilització.

#### Variables locals i globals
Les variables locals només existeixen dins de la funció. Les globals existeixen en tot el programa.

### 4.3. Exemples pràctics

```python
# Funció senzilla sense paràmetres
def saludar():
    print("Hola, benvingut a la programació modular!")

saludar()
```
```python
# Variables locals vs globals
x = 10  # variable global

def mostrar():
    x = 5  # variable local
    print("Valor local:", x)

mostrar()
print("Valor global:", x)
```

## 5. Activitats

### 5.1. Activitats guiades

1. Crea una funció que retorne el quadrat d’un nombre.

2. Escriu una funció que determine si un nombre és parell o senar.

### 5.2. Activitats d’ampliació

1. Crea un programa modular amb tres funcions: entrada de dades, càlcul i eixida.

2. Implementa una funció que retorne el nombre de vocals d’una cadena.

### 5.3. Activitats d’aplicació real

1. Dissenya un programa que gestione un menú utilitzant funcions per a cada opció.

2. Crea una funció que valide una contrasenya segons diversos criteris.

## 6. Instruments i criteris d’avaluació

### Instruments:

- Exercicis de funcions.

- Rúbrica de modularitat.

- Observació directa.

- Mini-projectes.

### Criteris (vinculats a CE):

- CE2 → Implementa solucions digitals utilitzant funcions i modularitat.

- CE4 → Formula algorismes coherents i els transforma en codi modular.

## 7. Recursos

- Documentació oficial de Python.

- Tutorials interactius (Replit, CodeCombat).

- Generadors de diagrames modulars.

## 8. Autoavaluació de l’alumnat

- Sé crear funcions amb paràmetres?

- Entenc la diferència entre variables locals i globals?

- Puc reorganitzar un programa en funcions?

## 9. Glossari

- Funció: bloc de codi reutilitzable.

- Paràmetre: valor que es passa a una funció.

- Retorn: resultat que una funció envia de tornada.

- Modularitat: organització del codi en parts independents.