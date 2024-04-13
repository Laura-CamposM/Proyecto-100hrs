# Mobile firts 
1. Lo que esta por fuera de los media-q es el dispositivo más pequeño (movil)
2. Los media-q se van incrementando desde el dispositivo más pequeño al más grande y se colocan en ese orden uno debajo del otro
3. Los breakpoints se definen usando la propiedad min-width
4. Codigo de ejemplo 
    ``` css
    .mobile {
    ... (aqui va todo lo del dispositivo movil)
    }
    @media (min-width: 567px) {
    ... (aqui va todo lo de el dispositivo mas grande que el anterior, ver linea de 7 a 9)
    }
    @media (min-width: 768px) {
    ... (aqui va todo lo de el dispositivo mas grande que el anterior, ver linea de la 10 a 12)
    }
    @media (min-width: 992px) {
    ... (aqui va todo lo de el dispositivo mas grande que el anterior, ver linea de la 13 a 15)
    }
    @media (min-width: 1200px) {
    ... (aqui va todo lo de el dispositivo mas grande que el anterior, ver linea de la 16 a 18)
    }
    @media (min-width: 1400px) {
    ... (aqui va todo lo de el dispositivo mas grande que el anterior, ver linea de la 19 a 21)
    }
    ``` 

# Desktop firts 
1. Lo que esta por fuera de los media-q es el dispositivo más grande (desktop)
2. Los media-q se van decrementando desde el dispositivo más grande al más pequeño y se colocan en ese orden uno encima del otro
3. Los breakpoints se definen usando la propiedad max-width
4. Codigo de ejemplo 
    ``` css
    .desktop {
        ... (aqui va todo lo del dispositivo mas grande del desktop)
    }
    @media (max-width: 1400px) {
        ... (aqui va todo lo de el dispositivo mas pequeño que el anterior, ver linea de la 33 a 35)
    }
    @media (max-width: 1200px) {
        ... (aqui va todo lo de el dispositivo mas pequeño que el anterior, ver linea de la 36 a 38)
    }
    @media (max-width: 992px) {
        ... (aqui va todo lo de el dispositivo mas pequeño que el anterior, ver linea de la 39 a 41)
    }
    @media (max-width: 768px) {
        ... (aqui va todo lo de el dispositivo mas pequeño que el anterior, ver linea de la 42 a 44)
    }
    @media (max-width: 567px) {
        ... (aqui va todo lo de el dispositivo mas pequeño que el anterior, ver linea de la 45 a 47)
    }
    ``` 
