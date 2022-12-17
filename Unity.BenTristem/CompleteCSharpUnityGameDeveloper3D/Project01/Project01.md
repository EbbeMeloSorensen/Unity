## Udemy Course: "Complete C# Unity Game Developer 3D"

### Instructor: Ben Tristem

https://www.udemy.com/course/unitycourse2/

## Section 1: Introduction & Setup

1) Download og installer Unity Hub, og sørg for at konfigurere med WebGL build support

2) Download seneste Unity Release

3) Installer Visual Studio Code

4) Kør Unity og lav et nyt projekt, hvor du vælger 3D templaten

5) Lav et antal objekter ved at højreklikke i Hierarchy-vinduet

6) Prøv at panorere i scenen (mens du bibeholder view direction) ved at holde musens rullehjul nede og dragge

7) Prøv at rotere scenen (mens du bibeholder focus point) ved at holde ALT-knappen nede samt venstre museknap nede og dragge

8) Prøv at ændre synsretning (mens du bibeholder viewpoint) ved at holde højre museknap nede og dragge

9) Prøv at zoome ind og ud ved at dreje på musens rulleknap

10) Prøv at zoome mere kontinuerligt ind og ud ved at holde ALT-knappen nede samt højre museknap og dragge

11) Prøv at fokusere på et valgfrit scene object ved at selecte det i Hierarchyet, flytte musen tilbage i scene viewet og klikke F.

12) Prøv at dreje rundt om et valgfrit scene object ved først at selecte det og fokusere ved tryk på F-knappen, og dernæst holde ALT-knappen nede samt venstre museknap og så dragge.

13) Manipuler et objekt ved at aktivere et af de 5 modes:

    * Hand tool (shortcut: Q)
    * Move tool (shortcut: W)
    * Rotate tool (shortcut: E)
    * Scale (shortcut: R)
    * Rect tool (shortcut: T)

14) Prøv at duplikere et objekt ved at selecte det i Hierarchyet og så taste CTRL+D

15) Prøv at dreje et objekt i 5 grader steps ved at holde CTRL-tasten nede mens du drejer

16) Prøv at flytte flere objekter på én gang ved at udvide selection med SHIFT eller CTRL og klik og så flytte.

17) Lav en gruppering af et antal objekter ved først at højreklikke i Hierarchyet og vælge "Create Empty". Her anbefaler han, at man klikker på "Transform" i Inspector-viewet og vælger "Reset". Select til sidst de objekter, der skal omfattes af grupperingen i Hierarchyet og drag dem oven i det tomme objekt.

18) Tilføj et Plane object til scenen

19) Dupliker et grupperet objekt med CTRL+D. Bemærk, at det nye objekt er uafhængigt af første, så ændringer vil kun slå igennem på et objekt. I mange situationer er det bedre at benytte sig af såkaldte prefabs

20) Lav en prefab ved at holde venstre museknap nede og dragge et objekt ned i Assets-viewet

21) Lav en ny instans af prefaben fra assets viewet ved at dragge den ind i scenen

22) Gå ind i edit mode for en prefab ved at dobbeltklikke på den i Assets-viewet. Ændr på den og gå tilbage til scenen ved at klikke på pilen øverst til venstre i Hierarchy-viewet

23) Lav en ændring af en instans af en prefab ved at selecte instansen i Hierarchy-viewet og lave ændringer, f.eks. af en child komponent. Bemærk, at det ikke ændrer de andre instanser.

24) Lav et C# script ved at højreklikke i Assets-viewet og vælge "Create" -> "C# Script". Sørg gerne for at navngive det med det samme, dvs før du f.eks. selecter noget andet.

25) Sørg for at have Unity konfigureret til at åbne scripts i VS Code ved at klikke på "Edit"->"Preferences"->"External Tools" og vælge "Visual Studio Code" som "External Script Editor"

26) Dobbeltklik på scriptet for at åbne det i VS Code

27) Sørg gerne for at følgende extensions er installeret i VS Code:

    * C# 
    * Unity Code Snippets

28)  Ændr scriptet, så det ser således ud:

    ```c#
    using System.Collections;
    using System.Collections.Generic;
    using UnityEngine;
    
    public class PrintToConsole : MonoBehaviour
    {
        // Start is called before the first frame update
        void Start()
        {
            Debug.Log("Hejsa");
        }
    
        // Update is called once per frame
        void Update()
        {
            
        }
    }
    ```

29) Attach scritpet til et game objekt i Hierarchy-viewet ved at selecte game objektet, så det vises i inspector viewet, og drag derefter scriptet fra Assets viewet og hen i Inspector viewet under Transform-sektionen.

30) Skift nu til "Console"-tabben i nederst i Unity-grænsefladen, så man kan se output fra spillet, og klik på "Play"-knappen over scene viewet. Så skulle den gerne vise outout fra det script, der nu knytter sig til game objektet.

## Section 2: Obstacle Course

(Coming soon)

