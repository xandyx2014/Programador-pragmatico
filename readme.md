- [Capitulo 1. Una filosofia pragmatica](#capitulo-1-una-filosofia-pragmatica)
  * [1.-El Gato Se Comio Mi Codigo Fuente](#1-el-gato-se-comio-mi-codigo-fuente)
  * [2.-Entropia del software](#2-entropia-del-software)
  * [3.-Sopa de piedra y ranas hervidas](#3-sopa-de-piedra-y-ranas-hervidas)
  * [4.-Sopa suficientemente buena](#4-sopa-suficientemente-buena)
  * [5.-Su cartera de conocimientos](#5-su-cartera-de-conocimientos)
    + [Construir su cartera](#construir-su-cartera)
    + [Objetivos](#objetivos)
  * [6.-Comunicar](#6-comunicar)
- [Capítulo 2. Un enfoque pragmatico](#capitulo-2-un-enfoque-pragmatico)
  * [7.-Los males de la duplicacion](#7-los-males-de-la-duplicacion)
  * [8.-Ortogonalidad](#8-ortogonalidad)
  * [9.-Reversibilidad](#9-reversibilidad)
  * [10-Balas Trazadoras](#10-balas-trazadoras)
    + [Las balas trazadoras no siempre dan en el blanco](#las-balas-trazadoras-no-siempre-dan-en-el-blanco)
    + [Código trazador frente a prototipo](#codigo-trazador-frente-a-prototipo)
  * [11.-Prototipos y notas Post it](#11-prototipos-y-notas-post-it)
  * [12.-Lenguajes de Dominio](#12-lenguajes-de-dominio)
  * [13.-Estimacion](#13-estimacion)
    + [Qué grado de precisión es suficiente?](#que-grado-de-precision-es-suficiente)
    + [¿De dónde salen las estimaciones?](#de-donde-salen-las-estimaciones)
    + [Estimación de Calendarios de Proyectos](#estimacion-de-calendarios-de-proyectos)
    + [Qué decir cuando se pide un presupuesto](#que-decir-cuando-se-pide-un-presupuesto)
    + [Desafíos](#desafios)
- [Capítulo 3. Las herramientas básicas](#capitulo-3-las-herramientas-basicas)
  * [14.-El poder del texto sin formato](#14-el-poder-del-texto-sin-formato)
    + [Inconvenientes](#inconvenientes)
    + [El Poder del Texto](#el-poder-del-texto)
  * [15.-Juegos de Shell](#15-juegos-de-shell)
  * [16.-Power Editing](#16-power-editing)
    + [Características "imprescindibles" del editor](#caracteristicas-imprescindibles-del-editor)
  * [17.-Control del Código Fuente](#17-control-del-codigo-fuente)
  * [18.-Depuración](#18-depuracion)
    + [Una mentalidad de depuración](#una-mentalidad-de-depuraci-n)
    + [Por dónde empezar](#por-d-nde-empezar)
    + [Antes de empezar, comprueba las advertencias o, mejor, elimínalas todas.](#antes-de-empezar--comprueba-las-advertencias-o--mejor--elim-nalas-todas)
    + [Primero necesitas ser preciso en tus observaciones y datos.](#primero-necesitas-ser-preciso-en-tus-observaciones-y-datos)
    + [Estrategias de depuración](#estrategias-de-depuraci-n)
      - [Reproducción de errores](#reproducci-n-de-errores)
      - [Visualice sus datos](#visualice-sus-datos)
      - [Rastrear](#rastrear)
      - [Evasión](#evasi-n)
      - [Proceso de eliminación](#proceso-de-eliminaci-n)
    + [El Elemento Sorpresa](#el-elemento-sorpresa)
    + [Lista de comprobación para la depuración](#lista-de-comprobaci-n-para-la-depuraci-n)
  * [19.-Manipulación de Texto](#19-manipulaci-n-de-texto)
  * [20.-Generadores de Código](#20-generadores-de-c-digo)
    + [Los generadores de código no tienen por qué ser complejos](#los-generadores-de-c-digo-no-tienen-por-qu--ser-complejos)
    + [Los generadores de código no necesitan generar código](#los-generadores-de-c-digo-no-necesitan-generar-c-digo)
- [Capítulo 4. Una paranoia pragmática](#cap-tulo-4-una-paranoia-pragm-tica)
  * [21.-Diseño por Contrato](#21-dise-o-por-contrato)
    + [Implementación de DBC](#implementaci-n-de-dbc)
    + [Aserciones](#aserciones)
    + [DBC enforce Crashing Early** (Aplicar DBC antes de tiempo)](#dbc-enforce-crashing-early----aplicar-dbc-antes-de-tiempo-)
    + [Invariantes](#invariantes)
  * [22.-Los Programas Muertos No Mienten](#22-los-programas-muertos-no-mienten)
  * [23.-Programación Asertiva](#23-programaci-n-asertiva)
  * [24.-Cuando Usar Excepciones](#24-cuando-usar-excepciones)
    + [¿Qué es Excepcional?](#-qu--es-excepcional-)
  * [25.-Cómo Balancear Recursos](#25-c-mo-balancear-recursos)
    + [Asignaciones de Nidos](#asignaciones-de-nidos)
    + [Objetos y Excepciones](#objetos-y-excepciones)
- [Capítulo 5. Doblar o romper](#cap-tulo-5-doblar-o-romper)
  * [26.-Desacoplamiento y la Ley de Demeter](#26-desacoplamiento-y-la-ley-de-demeter)
    + [Minimizar el Acoplamiento](#minimizar-el-acoplamiento)
    + [La Ley de Demeter para Funciones](#la-ley-de-demeter-para-funciones)
    + [Realmente marca la diferencia?](#realmente-marca-la-diferencia-)
  * [27.-Metaprogramación](#27-metaprogramaci-n)
    + [Configuración dinámica](#configuraci-n-din-mica)
    + [Aplicaciones basadas en metadatos](#aplicaciones-basadas-en-metadatos)
    + [Cuando configurar](#cuando-configurar)
  * [28.- Acoplamiento Temporal](#28--acoplamiento-temporal)
    + [Workflow](#workflow)
    + [Arquitectura](#arquitectura)
    + [Diseno para la concurrencia](#diseno-para-la-concurrencia)
    + [Interfaces mas limpias](#interfaces-mas-limpias)
    + [Despliegue](#despliegue)
  * [29.-It's Just a View](#29-it-s-just-a-view)
    + [Publish/Subscribe](#publish-subscribe)
    + [Modelo-Vista-Controlador](#modelo-vista-controlador)
    + [Beyond GUIs](#beyond-guis)
  * [30.-Pizarras](#30-pizarras)
    + [Implementaciones de Pizarras Negras](#implementaciones-de-pizarras-negras)
- [Capítulo 6. Mientras codifica](#cap-tulo-6-mientras-codifica)
  * [31.-Programar por coincidencia](#31-programar-por-coincidencia)
    + [Como programar deliberadamente](#como-programar-deliberadamente)
  * [32.-Velocidad del algoritmo](#32-velocidad-del-algoritmo)
    + [Uso: Notacion Big O](#uso--notacion-big-o)
    + [Estimacion con sentido comun](#estimacion-con-sentido-comun)
    + [Bucles simples: O(n)](#bucles-simples--o-n-)
    + [Lo mejor no siempre es lo mejor](#lo-mejor-no-siempre-es-lo-mejor)
  * [33.-Refactorizacion](#33-refactorizacion)
    + [¿Cuándo debe Refactorizar?](#-cu-ndo-debe-refactorizar-)
  * [Duplicacion. Has descubierto una violacion del principio DRY Los males de la duplicacion.](#duplicacion-has-descubierto-una-violacion-del-principio-dry-los-males-de-la-duplicacion)
    + [¿Cómo Refactorizar?](#-c-mo-refactorizar-)
  * [34.-Codigo fácil de probar](#34-codigo-f-cil-de-probar)
    + [Pruebas unitarias](#pruebas-unitarias)
    + [Pruebas contra contrato](#pruebas-contra-contrato)
    + [Escribir pruebas unitarias](#escribir-pruebas-unitarias)
    + [Uso de arneses de pruebas](#uso-de-arneses-de-pruebas)
    + [Construir una ventana de prueba](#construir-una-ventana-de-prueba)
    + [Una cultura de pruebas](#una-cultura-de-pruebas)
  * [35.-Malvados Asistentes](#35-malvados-asistentes)
- [Capítulo 7. Antes del proyecto](#cap-tulo-7-antes-del-proyecto)
  * [36.-El Foso de los Requisitos](#36-el-foso-de-los-requisitos)
    + [Digging for Requirements](#digging-for-requirements)
    + [Documentacion de requisitos](#documentacion-de-requisitos)
    + [Sobreespecificar](#sobreespecificar)
    + [Ver mas alla](#ver-mas-alla)
    + [Just One More Wafer-Thin Mint...](#just-one-more-wafer-thin-mint)
    + [Mantener un glosario](#mantener-un-glosario)
    + [Corra la voz](#corra-la-voz)
  * [37.-Resolver enigmas imposibles](#37-resolver-enigmas-imposibles)
    + [Grados de libertad](#grados-de-libertad)
    + [Debe haber una manera mas fácil!](#debe-haber-una-manera-mas-f-cil-)
  * [¿Tiene que hacerse de alguna manera?](#-tiene-que-hacerse-de-alguna-manera-)
  * [38.-No hasta que estes preparado](#38-no-hasta-que-estes-preparado)
    + [¿Buen Juicio o Procrastinacion?](#-buen-juicio-o-procrastinacion-)
  * [39.-La trampa de la especificación](#39-la-trampa-de-la-especificaci-n)
  * [40.-Circulos y Flechas](#40-circulos-y-flechas)
    + [¿Resultan rentables los metodos?](#-resultan-rentables-los-metodos-)
    + [¿Deberiamos utilizar metodos formales?](#-deberiamos-utilizar-metodos-formales-)
  * [41.-Equipos pragmaticos](#41-equipos-pragmaticos)
    + [Sin ventanas rotas](#sin-ventanas-rotas)
    + [Ranas hervidas](#ranas-hervidas)
    + [Comunicar](#comunicar)
    + [No te repitas](#no-te-repitas)
    + [Ortogonalidad](#ortogonalidad)
    + [Automatizacion](#automatizacion)
    + [Saber cuándo dejar de añadir pintura](#saber-cu-ndo-dejar-de-a-adir-pintura)
  * [42.-Automatizacion Ubicua](#42-automatizacion-ubicua)
    + [Todo en Automatico](#todo-en-automatico)
    + [Compilando el Proyecto](#compilando-el-proyecto)
    + [Automatizacion de la compilacion](#automatizacion-de-la-compilacion)
    + [Administracion automática](#administracion-autom-tica)
    + [Los hijos del zapatero](#los-hijos-del-zapatero)
  * [43.-Pruebas implacables](#43-pruebas-implacables)
    + [3 Aspectos principales:](#3-aspectos-principales-)
      - [1.-Que probar](#1-que-probar)
      - [2.-Como probar](#2-como-probar)
      - [3.-Cuando probar](#3-cuando-probar)
    + [Tightening the Net](#tightening-the-net)
  * [44.-Todo es escribir](#44-todo-es-escribir)
    + [Comentarios en el codigo](#comentarios-en-el-codigo)
    + [Documentos ejecutables](#documentos-ejecutables)
    + [Redactores técnicos](#redactores-t-cnicos)
    + [Print It or Weave It](#print-it-or-weave-it)
    + [Lenguajes de marcado](#lenguajes-de-marcado)
  * [45.-Grandes expectativas](#45-grandes-expectativas)
    + [Comunicar Expectativas](#comunicar-expectativas)
    + [La milla extra](#la-milla-extra)
    + [Orgullo y prejuicio](#orgullo-y-prejuicio)
- [Referencia rápida](#referencia-rapida)
  * [Consejos](#consejos)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>




# Capitulo 1. Una filosofia pragmatica
**Consejo 1: Preocupate por tu oficio**

¿Por qué pasarse la vida desarrollando software si no te importa hacerlo bien?

**Consejo 2: ¡Piensa! sobre tu trabajo**

Apaga el piloto automático y toma el control. Critica y evalúa constantemente tu trabajo.

## 1.-El Gato Se Comio Mi Codigo Fuente

**Consejo 3: Ofrece opciones, no inventes excusas falsas**

En lugar de excusas, ofrece opciones. No digas que no se puede hacer; explica qué se puede hacer para salvar la situación.

## 2.-Entropia del software
Una ventana rota, sin reparar durante un periodo de tiempo considerable, infunde en los habitantes del edificio una sensación de abandono: la sensación de que los poderes fácticos no se preocupan por el edificio. Así que se rompe otra ventana. La gente empieza a tirar basura. Aparecen pintadas. Comienzan los daños estructurales graves. En un espacio de tiempo relativamente corto, el edificio está más dañado de lo que el propietario desea arreglar, y la sensación de abandono se hace realidad.

**Consejo 4: No vivas con las ventanas rotas**.

No estropees la alfombra al arreglar la ventana rota.

## 3.-Sopa de piedra y ranas hervidas
Es hora de sacar las piedras. Calcula qué puedes pedir razonablemente. Desarróllalo bien. Cuando lo tengas, enséñaselo a la gente y deja que se maravillen. Luego di "por supuesto, sería mejor si añadiéramos....".

A la gente le resulta más fácil unirse a un éxito continuo.

**Consejo 5: Sea un catalizador del cambio**.

La mayoría de las catástrofes de software empiezan siendo demasiado pequeñas para notarlas, y la mayoría de los excesos de proyecto ocurren de un día para otro.

Si metes una rana en agua hirviendo, volverá a salir. Sin embargo, si la metes en una olla con agua fría y luego la calientas poco a poco, la rana no notará el lento aumento de temperatura y se quedará quieta hasta que se cueza.

No seas como la rana. No pierdas de vista el panorama general.

**Consejo 6: Recuerda el panorama general**

## 4.-Sopa suficientemente buena
El alcance y la calidad del sistema que produzcas deben especificarse como parte de los requisitos de ese sistema.

**Consejo 7: Haga de la calidad una cuestión de requisitos**

Un software excelente hoy suele ser preferible a un software perfecto mañana. **Saber cuándo parar**

## 5.-Su cartera de conocimientos
Una inversión en conocimiento siempre paga los mejores intereses.

* Los inversores serios invierten con regularidad, como un hábito.
* La diversificación es la clave del éxito a largo plazo.
* Los inversores inteligentes equilibran sus carteras entre inversiones conservadoras e inversiones de alto riesgo y alta rentabilidad.
* Los inversores intentan comprar barato y vender caro para obtener la máxima rentabilidad.
* Las carteras deben revisarse y reequilibrarse periódicamente.


### Construir su cartera
* Invertir con regularidad
* Diversificar
* Gestionar el riesgo
* Comprar barato, vender caro
* Revisar y reequilibrar

**Consejo 8: Invierta regularmente en su cartera de conocimientos**

### Objetivos
* Aprender al menos un idioma nuevo cada año.
* Leer un libro técnico cada trimestre.
* Lea también libros no técnicos.
* Asista a clases.
* Participar en grupos de usuarios locales.
* Experimente con distintos entornos.
* Mantente al día.
* Conéctese.

Debes asegurarte de que los conocimientos de tu cartera son precisos y no están influenciados por las exageraciones de los vendedores o los medios de comunicación.

**Consejo 9: Analice críticamente lo que lee y oye**.


## 6.-Comunicar
* Sepa lo que quiere decir. Planifique lo que quiere decir. Escriba un esquema.
* Conoce a tu audiencia. (Acróstico de SABIDURÍA)
  * ¿Qué **quieren**?
  * ¿Cuál es su **interés**?
  * ¿Cuál es su nivel de sofisticación?
  * ¿Cuántos **detalles** quieren?
  * ¿Quién quiere que sea el **propietario** de la información?
  * ¿Cómo puedes motivarles para que te escuchen?
* Elige el momento:  Entender cuándo su audiencia necesita escuchar su información.
* Elige un estilo:  Sólo los hechos, grandes informes encuadernados, un simple memorándum.
* Que tenga buen aspecto: Añada un vehículo atractivo a sus ideas importantes y atraiga a su audiencia.
* Involucra a tu audiencia:  Obtén su opinión y escucha sus ideas.
* Escuche: Anima a la gente a hablar haciéndoles preguntas.
* Responde a la gente: Mantén a la gente informada después.

**Consejo 10: Lo importante es lo que dices y cómo lo dices**.


# Capitulo 2. Un enfoque pragmatico

## 7.-Los males de la duplicacion
El problema surge cuando hay que cambiar una representación de cosas que están en toda la base de código.
Cada pieza de conocimiento debe tener una representación única, inequívoca y autorizada dentro de un sistema.

**Consejo 11: DRY: no te repitas**.

Tipos de duplicación:

* **Duplicación impuesta** Los desarrolladores creen que no tienen elección: el entorno parece exigir la duplicación.
* **Duplicación involuntaria** Los desarrolladores no se dan cuenta de que están duplicando información.
* **Duplicación impaciente** Los desarrolladores se vuelven perezosos y duplican porque parece más fácil.
* **Duplicación entre desarrolladores** Varias personas de un equipo (o de equipos diferentes) duplican una información.

**Consejo 12: Facilita la reutilización**.

## 8.-Ortogonalidad

Dos o más cosas son ortogonales si los cambios en una no afectan a ninguna de las otras. También llamada *cohesión*.
Escribe código "tímido".

**Consejo 13: Eliminar efectos entre cosas no relacionadas**

Ventajas:

* Gana Productividad
	* Los cambios se localizan
	* Promueve la reutilización
	* M x N componentes ortogonales hacen más que M x N componentes no ortogonales
* Reduce el riesgo
	* Se aíslan secciones o código enfermos
	* Se prueban mejor
	* No están atados a un producto o plataforma
* Equipos de proyecto: La funcionalidad se divide
* Diseño: Es más fácil diseñar un proyecto completo a través de sus componentes
* Conjuntos de herramientas y bibliotecas: Elegir sabiamente para mantener la ortogonalidad
* Codificación: Para mantener la ortogonalidad al añadir código haz:
	* Mantenga su código desacoplado
	* Evitar datos globales
	* Evite funciones similares
* Pruebas: Los sistemas ortogonales son más fáciles de probar.
* Documentación: También gana calidad

## 9.-Reversibilidad
Prepárate para los cambios.

**Consejo 14: No hay decisiones finales.**

## 10-Balas Trazadoras
En los nuevos proyectos, los requisitos de los usuarios pueden ser imprecisos. Llegará el uso de nuevos algoritmos, técnicas, lenguajes o librerías desconocidas. Y el entorno cambiará con el tiempo antes de que hayas terminado.
Buscamos algo que nos lleve de un requisito a algún aspecto del sistema final de forma rápida, visible y repetible.

**Consejo 15: Utilizar balas trazadoras para encontrar el objetivo**

Ventajas:

* Los usuarios pueden ver algo funcionando desde el principio.
* Los desarrolladores construyen una estructura en la que trabajar
* Tienes una plataforma de integración
* Tienes algo que demostrar
* Se tiene una mejor idea del progreso

### Las balas trazadoras no siempre dan en el blanco
Las balas trazadoras muestran lo que se está alcanzando. Puede que no siempre sea el objetivo. Entonces ajustas tu puntería hasta que den en el blanco. De eso se trata.


### Codigo trazador frente a prototipo
Con un prototipo, tu objetivo es explorar aspectos específicos del sistema final.
El código trazador se utiliza para saber cómo funciona la aplicación en su conjunto.

La creación de prototipos genera código desechable.
El código trazador es magro pero completo, y forma parte del esqueleto del sistema final.

## 11.-Prototipos y notas Post it
Construimos prototipos de software para analizar y exponer riesgos, y para ofrecer posibilidades de corrección a un coste muy reducido.

Prototipar cualquier cosa que

* conlleve un riesgo
* no se haya probado antes
* sea absolutamente crítico para el sistema final
* No está probado
* es experimental
* es dudoso

Muestras:

* Arquitectura
* Nueva funcionalidad en un sistema existente
* Estructura o contenido de datos externos
* Herramientas o componentes de terceros
* Problemas de rendimiento
* Diseño de la interfaz de usuario


**Consejo 16: Prototipar para aprender


Evite los detalles:

* Corrección
* Completitud
* Robustez
* Estilo

Arquitectura de prototipos:

* ¿Están bien definidas y son adecuadas las responsabilidades de los componentes principales?
* ¿Están bien definidas las colaboraciones entre los principales componentes?
* ¿Se minimiza el acoplamiento?
* ¿Se pueden identificar posibles fuentes de duplicación?
* ¿Son aceptables las definiciones de interfaz y las restricciones?
* ¿Tiene cada módulo una ruta de acceso a los datos que necesita durante la ejecución?

**Nunca despliegues el prototipo**

## 12.-Lenguajes de Dominio

**Consejo 17: Programa cerca del dominio del problema.

## 13.-Estimacion
**Consejo 18: Estimar para evitar sorpresas**

### Que grado de precision es suficiente?
**Primero:** ¿Necesitan una gran precisión o buscan una cifra aproximada?

**Segundo:** Escala adecuadamente las estimaciones de tiempo.

| Duración | Presupuesto estimado en |
|------------ |-------------------------------------- |
| 1-15 días Días
| 3-8 semanas
| 8-30 semanas Meses
| 30+ semanas | Piense bien antes de dar una estimación |

### De donde salen las estimaciones?
Pregunte a alguien que haya estado en una situación similar en el pasado.

* Comprender lo que se pide
* Construya un modelo del sistema
* Divida el modelo en componentes
* Dé un valor a cada parámetro
* Calcule las respuestas
* Mantenga un registro de su destreza en la estimación

### Estimacion de Calendarios de Proyectos
La única forma de determinar el calendario de un proyecto es adquiriendo experiencia en ese mismo proyecto.
Practique el desarrollo incremental, repitiendo los siguientes pasos:

* Adivinar la estimación
* Compruebe los requisitos
* Analizar riesgos
* Diseñar, implementar, integrar
* Validar con los usuarios
* Repetir

El refinamiento y la confianza en el cronograma mejoran en cada iteración.

**Consejo 19: Iterar el calendario con el código

### Que decir cuando se pide un presupuesto
**"Me pondré en contacto con usted "**.

### Desafios
Empieza a llevar un registro de tus estimaciones. Para cada una de ellas, registra el grado de precisión que has obtenido. Si tu error fue superior al 50%, intenta averiguar en qué se equivocó tu estimación.

# Capitulo 3. Las herramientas basicas

**Consejo 20: Conserva el conocimiento en texto sin formato**

## 14.-El poder del texto sin formato

### Inconvenientes
* más espacio
* computacionalmente más caro

### El Poder del Texto
* Seguro contra la obsolescencia: siempre tendrás la posibilidad de poder usar texto.
* Apalancamiento: Prácticamente todas las herramientas informáticas pueden funcionar con texto plano.
* Pruebas más fáciles

## 15.-Juegos de Shell
**Consejo 21: Utiliza el poder de las Shells de comandos**

¿No se puede hacer todo igual de bien apuntando y haciendo clic en una GUI?
**No**. Una ventaja de las GUIs es _WYSIWYG_-lo que ves es lo que obtienes. La desventaja es _WYSIAYG_-lo que ves es todo lo que obtienes.

## 16.-Power Editing
**Consejo 22: Utiliza bien un único editor**

### Caracteristicas imprescindibles del editor
* Configurable
* Extensible
* Programable
* Resaltado de sintaxis
* Autocompletado
* Auto-indentación
* Código inicial o documento repetitivo
* Vinculación con sistemas de ayuda
* Funciones tipo IDE (compilar, depurar, etc.)

## 17.-Control del Codigo Fuente
**Consejo 23: Utilice siempre el Control de Código Fuente**.

## 18.-Depuracion
**Consejo 24: Arregla el problema, no la culpa**

**Consejo 25: Que no cunda el pánico**

### Una mentalidad de depuración
No malgastes ni una sola neurona en el tren de pensamiento que empieza "pero eso no puede pasar", porque está claro que puede pasar, y ha pasado.
Intenta descubrir la raíz del problema, no sólo su apariencia.

### Por dónde empezar
### Antes de empezar, comprueba las advertencias o, mejor, elimínalas todas.
### Primero necesitas ser preciso en tus observaciones y datos.

### Estrategias de depuración
#### Reproducción de errores
* La mejor manera de empezar a arreglar un bug es hacerlo reproducible.
* La segunda mejor manera es hacerlo reproducible con un _solo comando_.

#### Visualice sus datos
Utiliza las herramientas que te ofrece el depurador. El lápiz y el papel también pueden ayudar.
#### Rastrear
Sepa qué ocurre antes y después.
#### Evasión
Explica el fallo a otra persona.
#### Proceso de eliminación
Es posible que exista un error en el sistema operativo, en el compilador o en un producto de terceros, pero esto no debería ser lo primero que pienses.

**Consejo 26: "seleccionar" no está roto**

### El Elemento Sorpresa
**Consejo 27: No lo Asuma-Pruébelo** ### Debugging Checklist

### Lista de comprobación para la depuración
* ¿Es el problema del que se informa un resultado directo del fallo subyacente, o simplemente un asíntoma?
* ¿El fallo está realmente en el compilador? ¿Está en el sistema operativo? ¿O está en tu código?
* Si le explicaras este problema en detalle a un compañero de trabajo, ¿qué le dirías?
* Si el código sospechoso pasa sus pruebas unitarias, ¿son las pruebas lo suficientemente completas? ¿Qué ocurre si ejecutas la prueba unitaria con estos datos?
* ¿Las condiciones que causaron este fallo existen en algún otro lugar del sistema?

## 19.-Manipulación de Texto
**Consejo 28: Aprende un lenguaje de manipulación de texto.

## 20.-Generadores de Codigo
**Consejo 29: Escribe código que escriba código**
Dos tipos principales de generadores de código:

* **Los generadores de código pasivos** se ejecutan una vez para producir un resultado. Son básicamente plantillas parametrizadas, que generan una salida dada a partir de un conjunto de entradas.
* Los generadores de código activo** se utilizan cada vez que se necesitan sus resultados. Toman una única representación de alguna pieza de conocimiento y la convierten en todas las formas que su aplicación necesita.

### Los generadores de código no tienen por qué ser complejos
Si el formato de entrada es sencillo, el generador de código también lo será.

### Los generadores de código no necesitan generar código
Puede utilizar generadores de código para escribir casi cualquier salida: HTML, XML, texto plano - cualquier texto que podría ser una entrada en algún lugar
en su proyecto.

# Capitulo 4. Una paranoia pragmática

**Consejo 30: No se puede escribir software perfecto**

Nadie en la breve historia de la informática ha escrito nunca un software perfecto.
Los Programadores Pragmáticos tampoco confían en sí mismos.

## 21.-Diseño por Contrato
Un programa correcto es aquel que no hace ni más ni menos de lo que dice hacer.
Utiliza:

* Precondiciones
* Postcondiciones
* Invariantes


**Consejo 31: Diseñar con contratos**

Escriba código "perezoso": sea estricto en lo que aceptará antes de empezar, y prometa lo menos posible a cambio.

### Implementación de DBC
Simplemente enumerando en tiempo de diseño:

* cuál es el rango del dominio de entrada
* cuáles son las condiciones de contorno
* qué promete ofrecer la rutina (y qué no)

### Aserciones
Puedes usar aserciones para aplicar DBC en algún rango. (Las aserciones no se propagan en las subclases)

### DBC enforce Crashing Early** (Aplicar DBC antes de tiempo)
### Invariantes
* Invariantes de Bucle: Es cierto antes y durante el bucle por lo tanto también cuando el bucle termina
* Invariantes semánticas: es decir, el error debe estar en el lado de no procesar una transacción en lugar de procesar una transacción duplicada.

## 22.-Los Programas Muertos No Mienten
Todos los errores dan información. Los Programadores Pragmáticos se dicen a sí mismos que si hay un error, algo muy, muy malo ha pasado.

**Consejo 32: Crash Early**

Un programa muerto normalmente hace mucho menos daño que uno lisiado.

Cuando su código descubre que algo que se suponía imposible acaba de suceder, su programa ya no es viable.
programa ya no es viable.

## 23.-Programación Asertiva
**Consejo 33: Si no puede ocurrir, usa aserciones para asegurarte de que no ocurrirá**

* Las aserciones también son útiles para comprobar el funcionamiento de un algoritmo.
* No use aserciones en lugar de un verdadero manejo de errores.
* Deje las aserciones activadas, a menos que tenga problemas críticos de rendimiento.

## 24.-Cuando Usar Excepciones
**Consejo 34: Use Excepciones para Problemas Excepcionales**
### ¿Qué es Excepcional?
El programa debe ejecutarse si se eliminan todos los manejadores de excepciones
Si su código intenta abrir un fichero para lectura y ese fichero no existe, debería lanzarse una excepción

* Sí: Si el archivo debería haber estado allí
* No: Si no tienes ni idea de si el fichero debería existir o no

## 25.-Cómo Balancear Recursos
Cuando gestionamos recursos: memoria, transacciones, hilos, moscas, temporizadores-todo tipo de cosas con disponibilidad limitada, tenemos que cerrarlas, terminarlas, borrarlas, desasignarlas cuando hayamos terminado.

**Consejo 35: Termina lo que empiezas**

### Asignaciones de Nidos

* 1.-Desasigna los recursos en orden inverso al que los asignas
* 2.-Cuando asignes el mismo conjunto de recursos en diferentes lugares de tu código, asígnalos siempre en el mismo orden (previene deadlocks)

### Objetos y Excepciones
Usa `finally` para liberar recursos.




# Capítulo 5. Doblar o romper

## 26.-Desacoplamiento y la Ley de Demeter

### Minimizar el Acoplamiento
Ten cuidado con cuántos otros módulos interactúas y cómo llegaste a interactuar con ellos.

Recorrer directamente las relaciones entre objetos puede llevar rápidamente a una explosión combinatoria.

```java

	book.pages().last().text().

	// Instead, we're supposed to go with:

	book.textOfLastPage()
```

Síntomas:
1. Proyectos grandes en los que el comando para enlazar una prueba unitaria es más largo que el propio programa de prueba
2. Cambios "simples" en un módulo que se propagan a través de módulos no relacionados en el sistema
3. Desarrolladores que tienen miedo de cambiar el código porque no están seguros de lo que podría verse afectado

### La Ley de Demeter para Funciones

La Ley de Demeter para las funciones establece que cualquier método de un objeto debe llamar sólo a los métodos pertenecientes a:
```js

class Demeter {
	private A a;
	void m(B b) {
		a.hello(); 							//itself
		b.hello(); 							//any parameters that were passed to the method
		new Z().hello(); 					// any object it created
		Singleton.INSTANCE.hello(); 		// any directly held component
	}
}
```

**Consejo 36: Minimizar el acoplamiento entre módulos**

### Realmente marca la diferencia?
Usar La Ley de Demeter hará tu código más adaptable y robusto, pero a un coste:
estará escribiendo un gran número de métodos envolventes que simplemente reenvían la petición a un delegado. imponiendo tanto un coste de tiempo de ejecución como una sobrecarga de espacio.
Equilibre los pros y los contras para su aplicación particular.

## 27.-Metaprogramación
"¡Fuera los detalles!" Sácalos del código. Ya que estamos, podemos hacer que nuestro código sea altamente configurable y "suave", es decir, fácilmente adaptable a los cambios.

### Configuración dinámica

**Consejo 37: Configurar, no integrar**.

### Aplicaciones basadas en metadatos

Queremos configurar y conducir la aplicación a través de metadatos tanto como sea posible.
Programar para el caso general, y poner los detalles en otro lugar -fuera de la base de código compilado.

**Consejo 38: Ponga las abstracciones en el código y los detalles en los metadatos**.

Ventajas:

* Te obliga a desacoplar tu diseño, lo que resulta en un programa más flexible y adaptable.
* Le obliga a crear un diseño más robusto y abstracto difiriendo los detalles, difiriéndolos completamente fuera del programa.
* Se puede personalizar la aplicación sin tener que recompilarla.
* Los metadatos pueden expresarse de una forma mucho más cercana al dominio del problema que con un lenguaje de programación de propósito general.
* Incluso puede ser capaz de implementar varios proyectos diferentes utilizando el mismo motor de aplicación, pero con diferentes metadatos.

### Cuando configurar
Un enfoque flexible es escribir programas que puedan recargar su configuración mientras se están ejecutando.

* proceso de servidor de larga ejecución: proporcionar alguna forma de releer y aplicar metadatos mientras el programa se está ejecutando.
* pequeña aplicación GUI cliente: si se reinicia rápidamente no hay problema.

## 28.- Acoplamiento Temporal
Dos aspectos del tiempo:

* Concurrencia: cosas que suceden al mismo tiempo.
* Ordenación: las posiciones relativas de las cosas en el tiempo

Necesitamos permitir la concurrencia y pensar en desacoplar cualquier dependencia temporal o de orden.
Reducir las dependencias temporales

### Workflow

Use [activity diagrams](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Activity_conducting.svg/2000px-Activity_conducting.svg.png) to maximize parallelism by identifying activities that could be performed in parallel, but aren't.

**Consejo 39: Analizar el flujo de trabajo para mejorar la concurrencia

### Arquitectura
Equilibrar la carga entre múltiples procesos consumidores: **el modelo de consumidor hambriento.**

En un modelo de consumidor hambriento, se sustituye el planificador central por una serie de tareas consumidoras independientes y una cola de trabajo centralizada. Cada tarea de consumo toma una parte de la cola de trabajo y se dedica a procesarla. A medida que cada tarea termina su trabajo, vuelve a la cola a por más. De este modo, si una tarea se queda atascada, las demás pueden ocuparse de ella y cada componente puede avanzar a su propio ritmo. Cada componente está temporalmente desacoplado de los demás.

**Consejo 40: Diseñar utilizando servicios

### Diseno para la concurrencia
Programar con hilos impone algunas restricciones de diseño, y eso es bueno.

* Las variables globales o estáticas deben estar protegidas del acceso concurrente.
* Comprueba si necesitas una variable global en primer lugar.
* Información de estado consistente, independientemente del orden de las llamadas.
* Los objetos deben estar siempre en un estado válido cuando son llamados, y pueden ser llamados en los momentos más incómodos. Use invariantes de clase, discutidos en Diseño por Contrato.

### Interfaces mas limpias
Pensar en la concurrencia y en las dependencias ordenadas en el tiempo también puede llevarte a diseñar interfaces más limpias.

**Consejo 41: Diseña siempre para la concurrencia.

### Despliegue
Puede ser flexible en cuanto a cómo se despliega la aplicación: independiente, cliente-servidor, o n-capas.

Si diseñamos para permitir la concurrencia, podemos cumplir más fácilmente con los requisitos de escalabilidad o rendimiento cuando llegue el momento - y si nunca llega el momento, todavía tenemos el beneficio de un diseño más limpio.

## 29.-It's Just a View

### Publish/Subscribe
Los objetos deben ser capaces de registrarse para recibir sólo los eventos que necesitan, y nunca deben recibir eventos que no necesitan.

Utiliza este mecanismo de publicación/suscripción para implementar un concepto de diseño muy importante: la separación de un modelo de las vistas del modelo.

### Modelo-Vista-Controlador
Separa el modelo tanto de la GUI que lo representa como de los controles que gestionan la vista.

Ventajas:

* Soporta múltiples vistas del mismo modelo de datos.
* Usar visores comunes en muchos modelos de datos diferentes.
* Soportar múltiples controladores para proporcionar mecanismos de entrada no tradicionales.

**Consejo 42: Separar las vistas de los modelos.

### Beyond GUIs
El controlador es más un mecanismo de coordinación, y no tiene por qué estar relacionado con ningún tipo de dispositivo de entrada.

* **Modelo** El modelo de datos abstracto que representa el objeto de destino. El modelo no tiene conocimiento directo de ninguna vista o controlador.
* Vista** Una forma de interpretar el modelo. Se suscribe a los cambios en el modelo y a los eventos lógicos del controlador.
* Controlador** Una forma de controlar la vista y proporcionar nuevos datos al modelo. Publica eventos tanto para el modelo como para la vista.


## 30.-Pizarras
Un sistema de pizarra nos permite desacoplar completamente nuestros objetos, proporcionando un foro donde consumidores y productores de conocimiento pueden intercambiar datos de forma anónima y asíncrona.

### Implementaciones de Pizarras Negras
Con los sistemas de pizarra, se pueden almacenar objetos activos -no sólo datos- en la pizarra, y recuperarlos por coincidencia parcial de campos (mediante plantillas y comodines) o por subtipos.

Funciones que debe tener un sistema de Pizarra:

* **leer** Buscar y recuperar datos del espacio.
* Escribir** Colocar un elemento en el espacio.
* Tomar** Similar a leer, pero también elimina el elemento del espacio.
* **notificar** Configurar una notificación para que se produzca cada vez que se escriba un objeto que coincida con la plantilla.

Organizar su Pizarra particionándola cuando trabaje en casos grandes.

**Consejo 43: Usar Pizarras para Coordinar el Flujo de Trabajo**

# Capítulo 6. Mientras codifica
## 31.-Programar por coincidencia
Debemos evitar programar por casualidad -confiando en la suerte y los éxitos accidentales- en favor de programar deliberadamente.
**Consejo 44: No programes por casualidad**

### Como programar deliberadamente
* Sé siempre consciente de lo que estás haciendo.
* No programes con los ojos vendados.
* Procede a partir de un plan.
* Confía sólo en cosas fiables.
* Documenta tus suposiciones. Diseña por contrato
* No pruebe sólo su código, pruebe también sus suposiciones. No adivines Programación asertiva
* Prioriza tu esfuerzo.
* No sea esclavo de la historia. No dejes que el código existente dicte el código futuro.

## 32.-Velocidad del algoritmo
Los Programadores Pragmáticos estiman los recursos que usan los algoritmos-tiempo, procesador, memoria, etc.

### Uso: Notacion Big O
* **O(1)**: Constante (acceso a elemento en array, sentencias simples)
```js
	bool IsFirstElementNull(IList<string> elements)
	{
    	return elements[0] == null;
	}
```

* **O(lg(n))**: Logarithmic (binary search) lg(n) = lg2(n)

```js

	Int BinarySearch(list, target)
	{
	   lo = 1, hi = size(list)
	   while (lo <= hi){
	      mid = lo + (hi-lo)/2
	      if (list[mid] == target) return mid
	      else if (list[mid] < target) lo = mid+1
	      else hi = mid-1
	   }
	}

```

* **O(n)**: Linear: Sequential search

```js

	bool ContainsValue(IList<string> elements, string value)
	{
	    foreach (var element in elements)
	    {
	        if (element == value) return true;
	    }

	    return false;
	}

```
* **O(n lg(n))**: Worse than linear but not much worse(average runtime of quickshort, headsort)
* **O(n²)**: Square law (selection and insertion sorts)

```js

	bool ContainsDuplicates(IList<string> elements)
	{
	    for (var outer = 0; outer < elements.Count; outer++)
	    {
	        for (var inner = 0; inner < elements.Count; inner++)
	        {
	            // Don't compare with self
	            if (outer == inner) continue;

	            if (elements[outer] == elements[inner]) return true;
	        }
	    }

	    return false;
	}

```
* **O(n³)**: Cubic (multiplication of 2 n x n matrices)
* **O(Cⁿ)**: Exponential (travelling salesman problem, set partitioning)

```js

	int Fibonacci(int number)
	{
	    if (number <= 1) return number;

	    return Fibonacci(number - 2) + Fibonacci(number - 1);
	}
```
### Estimacion con sentido comun
### Bucles simples: O(n)
* Bucles anidados: O(n²)
* Bucle binario O(lg(n))
* Divide y vencerás: O(n lg(n)). Algoritmos que dividen su entrada, trabajan en las dos mitades independientemente y luego combinan el resultado.
* Combinatoria: O(Cⁿ)


**Consejo 45: Estime el orden de sus algoritmos**.

**Consejo 46: Pon a prueba tus estimaciones**

### Lo mejor no siempre es lo mejor
Sea pragmático a la hora de elegir los algoritmos adecuados: el más rápido no siempre es el mejor para el trabajo.

Desconfíe de la optimización prematura. Asegúrese de que un algoritmo es realmente un cuello de botella antes de invertir tiempo en mejorarlo.

## 33.-Refactorizacion
El código necesita evolucionar; no es algo estático.

### ¿Cuándo debe Refactorizar?
## Duplicacion. Has descubierto una violacion del principio DRY Los males de la duplicacion.
* Diseño no ortogonal. Has descubierto algún código o diseño que podría hacerse más ortogonal ([Ortogonalidad](#8-ortogonalidad)).
* Conocimientos obsoletos. Las cosas cambian, los requisitos cambian, y tu conocimiento del problema aumenta. El código debe mantenerse al día.
* Rendimiento. Necesitas mover funcionalidad de un área del sistema a otra para mejorar el rendimiento.

**Consejo 47: Refactorice pronto, refactorice a menudo.

### ¿Cómo Refactorizar?
* 1. No intentes refactorizar y añadir funcionalidad al mismo tiempo.
* 2. Asegúrate de que tienes buenas pruebas antes de empezar a refactorizar.
* 3. Da pasos cortos y deliberados.

## 34.-Codigo fácil de probar
Construye testabilidad en el software desde el principio, y prueba cada pieza a fondo antes de intentar conectarlas.

### Pruebas unitarias
Pruebas realizadas en cada módulo, de forma aislada, para verificar su comportamiento.
Una prueba unitaria de software es un código que ejercita un módulo.

### Pruebas contra contrato
Esto nos dirá dos cosas:

1. Si el código cumple el contrato
2. Si el contrato significa lo que pensamos que significa.

**Consejo 48: Diseñar para probar**

No hay mejor forma de corregir errores que evitarlos desde el principio.
Construye las pruebas antes de implementar el código.

### Escribir pruebas unitarias
Haciendo el código de pruebas fácilmente accesible, estás proporcionando a los desarrolladores que puedan usar tu código dos recursos inestimables:

1. Ejemplos de cómo utilizar toda la funcionalidad de tu módulo.
2. 2. Un medio para construir pruebas de regresión para validar cualquier cambio futuro en el código.

Debes ejecutarlas, y ejecutarlas a menudo.

### Uso de arneses de pruebas
Los arneses de pruebas deben incluir las siguientes capacidades:

* Una forma estándar de especificar la configuración y la limpieza
* Un método para seleccionar pruebas individuales o todas las pruebas disponibles.
* Un medio para analizar los resultados esperados (o inesperados).
* Una forma estandarizada de notificación de fallos

### Construir una ventana de prueba

* Archivos de registro.
* Secuencia de teclas de acceso rápido.
* Servidor Web incorporado.

### Una cultura de pruebas

**Consejo 49: Pruebe su software, o lo haran sus usuarios**

## 35.-Malvados Asistentes
Si usas un asistente, y no entiendes todo el código que produce, no tendrás el control de tu propia aplicación.

**Consejo 50: No uses codigo de asistente que no entiendas**

# Capítulo 7. Antes del proyecto

## 36.-El Foso de los Requisitos
_La perfección se alcanza, no cuando no queda nada por añadir, sino cuando no queda nada por quitar...._

**Consejo 51: No reúna requisitos, excave en busca de ellos**

### Digging for Requirements
La política puede acabar como metadatos en la aplicación.

Recopilar requisitos de esta manera le lleva de forma natural a un sistema que está bien preparado para soportar metadatos.

**Consejo 52: Trabajar con un usuario para pensar como un usuario

### Documentacion de requisitos
Utilizar "casos de uso"

### Sobreespecificar
Los requisitos no son arquitectura. Los requisitos no son el diseño, ni la interfaz de usuario. Los requisitos son necesidad.

### Ver mas alla
**Consejo 53: Las abstracciones viven más que los detalles**

### Just One More Wafer-Thin Mint...
¿Qué podemos hacer para evitar que los requisitos crezcan sigilosamente?

La clave para gestionar el crecimiento de los requisitos es señalar a los patrocinadores del proyecto el impacto de cada nueva característica en el calendario.

### Mantener un glosario
Es muy difícil tener éxito en un proyecto en el que los usuarios y los desarrolladores se refieren a la misma cosa con nombres diferentes o, peor aún, se refieren a cosas diferentes con el mismo nombre.

**Consejo 54: Utilice un glosario del proyecto.

### Corra la voz
Publicar los documentos del proyecto en sitios web internos para facilitar el acceso de todos los participantes.

## 37.-Resolver enigmas imposibles
### Grados de libertad
La clave para resolver puzzles es tanto reconocer las limitaciones que te imponen como los grados de libertad que tienes, pues en ellos encontrarás la solución.

**Consejo 55: No pienses fuera de la caja, encuentra la caja**.

### Debe haber una manera mas fácil!
Si no puedes encontrar la solución, da un paso atrás y hazte estas preguntas:

* ¿Existe una forma más fácil?
* ¿Estás intentando resolver el problema correcto, o te has distraído con un tecnicismo periférico?
* ¿Por qué es esto un problema?
* ¿Qué es lo que hace que sea tan difícil de resolver?
* ¿Hay que hacerlo así?
## ¿Tiene que hacerse de alguna manera?

## 38.-No hasta que estes preparado
Si te sientas a empezar a escribir y hay alguna duda persistente en tu mente, hazle caso.

**Consejo 56: Escucha las dudas persistentes-Empieza cuando estés preparado**.

### ¿Buen Juicio o Procrastinacion?
Empiece a crear prototipos. Elija un área que le parezca difícil y empiece a producir algún tipo de prueba de concepto, y asegúrese de recordar
por qué lo estás haciendo y que se trata de un prototipo.

## 39.-La trampa de la especificación
Escribir una especificación es toda una responsabilidad.

Debes saber cuándo parar:

* La especificación nunca capturará todos los detalles de un sistema o sus requisitos.
* El poder expresivo del lenguaje puede no ser suficiente para describir una especificación.
* Un diseño que no deja margen de interpretación al programador despoja al esfuerzo de programación de toda habilidad y arte.

**Consejo 57: Algunas cosas es mejor hacerlas que describirlas**.

## 40.-Circulos y Flechas

**Consejo 58: No seas esclavo de los métodos formales**

Los métodos formales tienen algunos defectos graves:
* Los diagramas no tienen sentido para los usuarios finales, muéstrale al usuario un prototipo y déjale jugar con él.
* Los métodos formales parecen fomentar la especialización. Puede que no sea posible tener un conocimiento profundo de cada aspecto de un sistema.
* Nos gusta escribir sistemas adaptables y dinámicos, utilizando metadatos que nos permitan cambiar el carácter de las aplicaciones en tiempo de ejecución, pero la mayoría de los métodos formales actuales no lo permiten.

### ¿Resultan rentables los metodos?
Nunca subestime el coste de adoptar nuevas herramientas y métodos.

### ¿Deberiamos utilizar metodos formales?
Por supuesto, pero recuerde que es sólo una herramienta más en la caja de herramientas.

**Consejo 59: Las herramientas caras no producen mejores diseños**

#Capítulo 8. Proyectos pragmáticos

## 41.-Equipos pragmaticos
Las técnicas pragmáticas que ayudan a un individuo pueden funcionar para los equipos.

### Sin ventanas rotas
La calidad es una cuestión de equipo.

Los equipos en su conjunto no deben tolerar ventanas rotas: esas pequeñas imperfecciones que nadie arregla.

La calidad sólo puede provenir de las contribuciones individuales de todos los miembros del equipo.

### Ranas hervidas
La gente da por sentado que otra persona se está ocupando de un problema, o que el jefe de equipo debe haber dado el visto bueno a un cambio que su usuario está solicitando. Lucha contra esto.

### Comunicar
El equipo como entidad necesita comunicarse claramente con el resto del mundo.

La gente espera con impaciencia las reuniones con ellos, porque saben que verán una actuación bien preparada que hace que todos se sientan bien.

Existe un sencillo truco de marketing que ayuda a los equipos a comunicarse como uno solo: generar una marca.

### No te repitas
Designe a un miembro como bibliotecario del proyecto.

### Ortogonalidad
Es un error pensar que las actividades de un proyecto -análisis, diseño, codificación y pruebas- pueden desarrollarse de forma aislada. No es así. Son visiones diferentes del mismo problema, y separarlas artificialmente puede causar un montón de problemas.

**Consejo 60: Organicese en torno a la funcionalidad, no a las funciones**.

* Divide los equipos por funciones. Base de datos, interfaz de usuario, API
* Deja que los equipos se organicen internamente
* Cada equipo tiene responsabilidades con otros en el proyecto (definidas por sus compromisos acordados).
* Buscamos equipos de personas cohesionados y en gran medida autónomos

Organizamos nuestros recursos utilizando las mismas técnicas que utilizamos para organizar el código, utilizando técnicas como los contratos (Design by Contract), el desacoplamiento (Decoupling and the Law of Demeter), y la ortogonalidad (Orthogonality), y ayudamos a aislar al equipo en su conjunto de los efectos del cambio.

### Automatizacion
La automatización es un componente esencial de todo equipo de proyecto

### Saber cuándo dejar de añadir pintura

## 42.-Automatizacion Ubicua
### Todo en Automatico
**Consejo 61: No uses procedimientos manuales**

Usando _cron_, podemos programar copias de seguridad, compilación nocturna, sitio Web... desatendidos, automáticamente.

### Compilando el Proyecto
Queremos comprobar, compilar, probar y enviar con un solo comando

* Generar Código
* Pruebas de Regresión

### Automatizacion de la compilacion
Una compilación es un procedimiento que toma un directorio vacío (y un entorno de compilación conocido) y construye el proyecto desde cero, produciendo lo que se espera producir como entregable final.

* 1. Obtener el código fuente del repositorio
* 2. Construir el proyecto desde cero (marcado con el número de versión).
* 3. Crear una imagen distribuible
* 4. Ejecutar las pruebas especificadas

Cuando no ejecutas pruebas con regularidad, puedes descubrir que la aplicación se rompió debido a un cambio de código realizado hace tres meses. Buena suerte para encontrarlo.

**Compilación nocturna**: ejecútala todas las noches.

**Las compilaciones finales (para enviar como productos) pueden tener requisitos diferentes a los de las compilaciones nocturnas.

### Administracion automática
Nuestro objetivo es mantener un flujo de trabajo automático, desatendido y basado en el contenido.

* Resultados de generación del sitio web de la propia compilación, pruebas de regresión, estadísticas de rendimiento, métricas de codificación...
* Procedimientos de aprobación obtener marcas `/* Status: needs_review */`, enviar email...

### Los hijos del zapatero
Dejemos que el ordenador haga lo repetitivo, lo mundano: lo hará mejor que nosotros. Tenemos cosas más importantes y más difíciles que hacer.
## 43.-Pruebas implacables
Los Programadores Pragmáticos estamos impulsados a encontrar nuestros bugs ahora, para no tener que soportar la vergüenza de que otros encuentren nuestros bugs más tarde.

**Consejo 62: Prueba pronto. Prueba a menudo. Prueba automáticamente.**

Las pruebas que se ejecutan con cada compilación son las más eficaces.

Cuanto antes se detecte un error, menos costará remediarlo. "Codifica poco, prueba poco".

**Consejo 63: No se ha terminado de programar hasta que no se han ejecutado todas las pruebas.

### 3 Aspectos principales:

#### 1.-Que probar

* Pruebas unitarias: código que ejercita un módulo.
* Pruebas de integración: los principales subsistemas que componen el proyecto funcionan y se desempeñan bien entre sí.
* Validación y verificación: prueba si se está entregando lo que los usuarios necesitan.
* Agotamiento de recursos, errores y recuperación: descubre cómo se comportará en condiciones reales. (Memoria, disco, CPU, pantalla...)
* Pruebas de rendimiento: cumple los requisitos de rendimiento en condiciones reales.
* Pruebas de usabilidad: se realizan con usuarios reales, en condiciones ambientales reales.

#### 2.-Como probar
* Pruebas de regresión: compara el resultado de la prueba actual con valores anteriores (o conocidos). La mayoría de las pruebas son de regresión.
* Datos de prueba: sólo hay dos tipos de datos: los del mundo real y los sintéticos.
* Ejercitar los sistemas GUI: requiere herramientas de prueba especializadas, basadas en un modelo simple de captura/reproducción de eventos.
* Probar las pruebas: Después de haber escrito una prueba para detectar un fallo en particular, provoque el fallo deliberadamente y asegúrese de que la prueba se queja.
	
**Consejo 64: Utiliza saboteadores para probar tus pruebas.**
* Probar a fondo:

**Consejo 65: Probar la cobertura de estado, no la cobertura de código**

#### 3.-Cuando probar
Tan pronto como exista cualquier código de producción, necesita ser probado.
La mayoría de las pruebas deberían hacerse automáticamente.

### Tightening the Net
Si un fallo se cuela por la red de pruebas existentes, necesitas añadir una nueva prueba para atraparlo la próxima vez.

**Consejo 66: Encuentre los bugs una vez**

## 44.-Todo es escribir
Si hay una discrepancia, lo que importa es el código, para bien o para mal.

**Consejo 67: Trate el ingles como un lenguaje de programación mas**

**Consejo 68: Incorpore la documentación, no la atornille**

### Comentarios en el codigo
En general, los comentarios deberían explicar por qué se hace algo, su propósito y su objetivo.

Recuerde que usted (y otros después de usted) leerán el código muchos cientos de veces, pero sólo lo escribirán unas pocas veces.

Peor aún que los nombres sin sentido son los nombres engañosos.

Uno de los datos más importantes que debe aparecer en el archivo fuente es el nombre del autor, no necesariamente quién lo editó por última vez, sino el propietario.

### Documentos ejecutables
Cree documentos que creen esquemas. La única forma de cambiar el esquema es cambiar el documento.

### Redactores técnicos
Queremos que los redactores adopten los mismos principios básicos que un programador pragmático, especialmente el principio DRY, la ortogonalidad, el concepto de modelo-vista y el uso de automatización y secuencias de comandos.

### Print It or Weave It
La documentación en papel puede quedar desfasada en cuanto se imprime.

Publíquela en línea, en la Web.

Recuerde poner un sello con la fecha o un número de versión en cada página Web.

Utilizando un sistema de marcado, tendrá la flexibilidad de implementar tantos formatos de salida como necesite.

### Lenguajes de marcado
La documentación y el código son vistas diferentes del mismo modelo subyacente, pero la vista es lo único que debe ser diferente.

## 45.-Grandes expectativas
El éxito de un proyecto se mide por lo bien que satisface las expectativas de sus usuarios.

**Consejo 69: Supera suavemente las expectativas de tus usuarios**

### Comunicar Expectativas
Al principio, los usuarios acuden a usted con una cierta visión de lo que quieren. No puede simplemente ignorarla.

Todos deben entender lo que se espera y cómo se construirá.

### La milla extra
Ofrezca a los usuarios un poco más de lo que esperaban.

* Globo de ayuda o ToolTip
* Atajos de teclado
* Una guía de referencia rápida como suplemento al manual del usuario.
* Coloración
* Analizadores de archivos de registro
* Instalación automática
* Herramientas para comprobar la integridad del sistema
* La posibilidad de ejecutar varias versiones del sistema para la formación.
* Una pantalla de bienvenida personalizada para su organización

### Orgullo y prejuicio
Los programadores pragmáticos no eludimos la responsabilidad. Por el contrario, nos alegramos de aceptar retos y de dar a conocer nuestra experiencia.

Queremos ver orgullo de pertenencia. "Yo escribí esto, y estoy detrás de mi trabajo".

**Consejo 70: Firma tu trabajo**

# Referencia rapida
## Consejos
**Consejo 1: Preocupate por tu trabajo**
¿Por qué pasarse la vida desarrollando software si no te importa hacerlo bien?
**Consejo 2: ¡Piensa! sobre tu trabajo**
Apaga el piloto automático y toma el control. Critica y evalúa constantemente tu trabajo.

**Consejo 3: Ofrezca opciones, no invente excusas poco convincentes**.
En lugar de excusas, ofrece opciones. No digas que no se puede hacer; explica qué se puede hacer.

**Consejo 4: No viva con ventanas rotas**.
Corrige los malos diseños, las decisiones equivocadas y el código deficiente cuando los veas.

**Consejo 5: Sea un catalizador del cambio**
No se puede imponer el cambio a la gente. En su lugar, muéstreles cómo podría ser el futuro y ayúdeles a participar en su creación.

**Consejo 6: Recuerde el panorama general.**
No se quede tan absorto en los detalles que se olvide de comprobar lo que ocurre a su alrededor.

**Consejo 7: Haga de la calidad una cuestión de requisitos**.
Involucre a los usuarios en la determinación de los requisitos de calidad reales del proyecto.

**Consejo 8: Invierta regularmente en su cartera de conocimientos**.
Convierta el aprendizaje en un hábito.

**Consejo 9: Analice críticamente lo que lee y escucha**.
No se deje influir por los vendedores, los medios de comunicación o los dogmas. Analice la información en función de usted y de su proyecto.

**Consejo 10: Lo importante es lo que se dice y cómo se dice**.
De nada sirve tener grandes ideas si no las comunicas con eficacia.

**Consejo 11: DRY - No te repitas**.
Todo conocimiento debe tener una representación única, inequívoca y autorizada dentro de un sistema.

**Consejo 12: Facilite la reutilización**.
Si es fácil de reutilizar, la gente lo hará. Cree un entorno que favorezca la reutilización.

**Consejo 13: Elimine los efectos entre elementos no relacionados**.
Diseña componentes autónomos, independientes y con una finalidad única y bien definida.

**Consejo 14: No hay decisiones definitivas**
Ninguna decisión es inamovible. En su lugar, considere cada una como si estuviera escrita en la arena de la playa, y planifique para el cambio.

**Consejo 15: Utiliza balas trazadoras para encontrar el objetivo.
Las balas trazadoras te permiten encontrar tu objetivo probando cosas y viendo lo cerca que caen.

**Consejo 16: Crear prototipos para aprender
Crear prototipos es una experiencia de aprendizaje. Su valor no reside en el código que produce, sino en las lecciones que aprende.

**Consejo 17: Programe cerca del ámbito del problema**
Diseñe y codifique en el lenguaje de su usuario.

**Consejo 18: Calcule para evitar sorpresas**
Calcule antes de empezar. Detectará posibles problemas desde el principio.

**Consejo 19: Itere el calendario con el código**.
Utilice la experiencia que vaya adquiriendo a medida que ejecute para perfeccionar los plazos del proyecto.

**Consejo 20: Conserve los conocimientos en texto sin formato**
El texto sin formato no quedará obsoleto. Ayuda a aprovechar su trabajo y simplifica la depuración y las pruebas.
**Consejo 21: Utiliza la potencia del intérprete de comandos**.
Utilice el intérprete de comandos cuando las interfaces gráficas de usuario no sean suficientes.

**Consejo 22: Utilice bien un único editor**.
El editor debe ser una extensión de su mano; asegúrese de que su editor es configurable, extensible y programable.

**Consejo 23: Utilice siempre el control de código fuente**
El control del código fuente es una máquina del tiempo para tu trabajo: puedes volver atrás.

**Consejo 24: Solucione el problema, no la culpa**.
No importa si el error es culpa tuya o de otro: sigue siendo tu problema y hay que solucionarlo.

**Consejo 25: No te asustes cuando depures**
Respira hondo y ¡PIENSA! sobre lo que podría estar causando el fallo.

**Consejo 26: "Seleccionar" no está roto**.
Es raro encontrar un fallo en el sistema operativo o en el compilador, o incluso en un producto o librería de terceros. Lo más probable es que el fallo esté en la aplicación.

**Consejo 27: No lo suponga, demuéstrelo**.
Demuestre sus suposiciones en el entorno real, con datos y condiciones de contorno reales.

**Consejo 28: Aprenda un lenguaje de manipulación de textos.
Pasas gran parte del día trabajando con texto. ¿Por qué no hacer que el ordenador lo haga por usted?

**Consejo 29: Escriba código que escriba código**.
Los generadores de código aumentan su productividad y le ayudan a evitar la duplicación.

**Consejo 30: No se puede escribir software perfecto**.
El software no puede ser perfecto. Proteja su código y a sus usuarios de los inevitables errores.

**Consejo 31: Diseñe con contratos**
Utilice contratos para documentar y verificar que el código no hace ni más ni menos de lo que dice hacer.

**Consejo 32: Crash Early**
Un programa muerto normalmente hace mucho menos daño que uno lisiado.

**Consejo 33: Utilice aserciones para evitar lo imposible**.
Las aserciones validan sus suposiciones. Úsalas para proteger tu código de un mundo incierto.

**Consejo 34: Use Excepciones para Problemas Excepcionales**
Las excepciones pueden sufrir todos los problemas de legibilidad y mantenimiento del clásico código espagueti. Reserva las excepciones para cosas excepcionales.

**Consejo 35: Termina lo que empiezas**
Siempre que sea posible, la rutina u objeto que asigna un recurso debe ser responsable de su liberación.

**Consejo 36: Minimizar el acoplamiento entre módulos**
Evite el acoplamiento escribiendo código "tímido" y aplicando la Ley de Deméter.

**Consejo 37: Configurar, no integrar**
Implemente las opciones tecnológicas de una aplicación como opciones de configuración, no mediante integración o ingeniería.

**Consejo 38: Ponga las abstracciones en el código, los detalles en los metadatos**.
Programe para el caso general y deje los detalles fuera de la base de código compilado.

**Consejo 39: Analice el flujo de trabajo para mejorar la concurrencia**.
Aproveche la concurrencia en el flujo de trabajo de su usuario.

**Consejo 40: Diseñar utilizando servicios
Diseñe en términos de servicios - objetos independientes y concurrentes detrás de interfaces bien definidas y consistentes.

**Consejo 41: Diseñe siempre para la concurrencia**
Tenga en cuenta la concurrencia y diseñará interfaces más limpias con menos suposiciones.

**Consejo 42: Separe las vistas de los modelos**.
Gane flexibilidad a bajo coste diseñando su aplicación en términos de modelos y vistas.

**Consejo 43: Utilice pizarras para coordinar el flujo de trabajo**.
Utilice pizarras para coordinar hechos y agentes dispares, manteniendo la independencia y el aislamiento entre los participantes.

**Consejo 44: No programe por coincidencia**
Confíe sólo en cosas fiables. Tenga cuidado con la complejidad accidental y no confunda una feliz coincidencia con un plan intencionado.

**Consejo 45: Estime el orden de sus algoritmos**
Hazte una idea de lo que tardarán las cosas antes de escribir el código.

**Consejo 46: Comprueba tus estimaciones**
El análisis matemático de algoritmos no lo dice todo. Pruebe a cronometrar su código en su entorno de destino.
**Consejo 47: Refactorice pronto, refactorice a menudo**.
Del mismo modo que desbroza y arregla un jardín, reescriba, reelabore y rediseñe el código cuando sea necesario. Solucione el problema de raíz.

**Consejo 48: Diseñe para probar
Empieza a pensar en las pruebas antes de escribir una línea de código.

**Consejo 49: Pruebe su software o lo harán sus usuarios**
Pruebe sin piedad. No hagas que tus usuarios encuentren errores por ti.

**Consejo 50: No utilice código de asistentes que no entienda**.
Los asistentes pueden generar montones de código. Asegúrese de que lo entiende todo antes de incorporarlo a su proyecto.

**Consejo 51: No reúna requisitos, búsquelos.
Los requisitos rara vez se encuentran en la superficie. Están enterrados bajo capas de suposiciones, ideas erróneas y políticas.

**Consejo 52: Trabaje con un usuario para pensar como un usuario**.
Es la mejor manera de comprender cómo se utilizará realmente el sistema.

**Consejo 53: Las abstracciones viven más que los detalles**.
Invierte en la abstracción, no en la implementación. Las abstracciones pueden sobrevivir al aluvión de cambios de diferentes implementaciones y nuevas tecnologías.

**Consejo 54: Utilizar un glosario del proyecto
Cree y mantenga una fuente única de todos los términos y vocabulario específicos de un proyecto.

**Consejo 55: No piense fuera de la caja: encuentre la caja**.
Cuando se enfrente a un problema imposible, identifique las limitaciones reales. Pregúntese: "¿Tiene que hacerse así? ¿Tiene que hacerse de alguna manera?".

**Consejo 56: Empiece cuando esté preparado.
Llevas toda la vida acumulando experiencia. No ignores las dudas.

**Consejo 57: Algunas cosas es mejor hacerlas que describirlas**.
No caigas en la espiral de la especificación: en algún momento tienes que empezar a programar.

**Consejo 58: No seas esclavo de los métodos formales.
No adoptes ciegamente ninguna técnica sin situarla en el contexto de tus prácticas y capacidades de desarrollo.

**Consejo 59: Las herramientas costosas no producen mejores diseños**.
Tenga cuidado con el bombo publicitario del vendedor, el dogma de la industria y el aura de la etiqueta de precio. Juzgue las herramientas por sus méritos.

**Consejo 60: Organizar los equipos en torno a la funcionalidad**
No separe a los diseñadores de los programadores, ni a los probadores de los modeladores de datos. Cree equipos del mismo modo que crea código.

**Consejo 61: No utilice procedimientos manuales**.
Una secuencia de comandos o un archivo por lotes ejecutarán las mismas instrucciones, en el mismo orden, una y otra vez.

**Consejo 62: Pruebe pronto. Pruebe a menudo. Pruebe automáticamente**
Las pruebas que se ejecutan con cada compilación son mucho más eficaces que los planes de prueba que se quedan en un estante.

**Consejo 63: La programación no se ha terminado hasta que se ejecutan todas las pruebas**.
Suficiente.

**Consejo 64: Use Saboteadores para Probar sus Pruebas**.
Introduce errores a propósito en una copia separada del código fuente para verificar que las pruebas los detectan.

**Consejo 65: Pruebe la cobertura de estado, no la cobertura de código.
Identifique y pruebe los estados significativos del programa. No basta con probar líneas de código.

**Consejo 66: Encuentre los fallos una vez**
Una vez que un evaluador humano encuentra un error, debería ser la última vez que lo encuentra. Las pruebas automáticas deberían comprobarlo a partir de ese momento.

**Consejo 67: El inglés es sólo un lenguaje de programación**
Escriba documentos como escribiría código: respete el principio DRY, utilice metadatos, MVC, generación automática, etc.

**Consejo 68: Incorpore la documentación, no la atornille**.
Es menos probable que la documentación creada al margen del código sea correcta y esté actualizada.

**Consejo 69: Supera las expectativas de tus usuarios**
Comprenda las expectativas de sus usuarios y, a continuación, ofrezca un poco más.

**Consejo 70: Firme su trabajo**
Los artesanos de antaño estaban orgullosos de firmar su trabajo. Usted también debería estarlo.
## CheckList

### Lenguajes que aprender
¿Cansado de C, C++ y Java? Pruebe los siguientes lenguajes. Cada uno de estos lenguajes tiene distintas capacidades y un "sabor" diferente. Prueba un pequeño proyecto en casa utilizando uno o más de ellos.
- CLOS
- Dylan
- Eiffel
- Objetivo C
- Prolog
- Smalltalk
- TOM

### El acróstico de WISDOM
- ¿Qué quieres que aprendan?
- ¿Qué interés tienen en lo que les dices?
- ¿Cómo son de sofisticados?
- ¿Cuánto **d**detalle quieren?
- ¿A quién quieres que transmita la información?
- ¿Cómo puedes motivarles para que te escuchen?
 
### Cómo mantener la ortogonalidad
- Diseñe componentes independientes y bien definidos.
- Mantenga el código desacoplado.
- Evite los datos globales.
- Refactorice funciones similares.

### Cosas que prototipar
- Arquitectura
- Nueva funcionalidad en un sistema existente
- Estructura o contenido de datos externos
- Herramientas o componentes de terceros
- Problemas de rendimiento
- Diseño de la interfaz de usuario

### Cuestiones de arquitectura
- ¿Están bien definidas las responsabilidades?
- ¿Están bien definidas las colaboraciones?
- ¿Se minimiza el acoplamiento?
- ¿Se pueden identificar posibles duplicaciones?
- ¿Son aceptables las definiciones de interfaz y las restricciones?
- ¿Pueden los módulos acceder a los datos necesarios cuando lo necesitan?

### Lista de comprobación de la depuración
- ¿El problema del que se informa es consecuencia directa del fallo subyacente o simplemente un síntoma?
- ¿El fallo está realmente en el compilador? ¿Está en el sistema operativo? ¿O está en tu código?
- Si explicaras este problema en detalle a un compañero de trabajo, ¿qué le dirías?
- Si el código sospechoso pasa sus pruebas unitarias, ¿son las pruebas lo suficientemente completas? ¿Qué ocurre si ejecutas la prueba unitaria con estos datos?
- ¿Existen las condiciones que causaron este fallo en algún otro lugar del sistema?

### Ley de Demeter para Funciones
Un método de un objeto debe llamar sólo a métodos que pertenezcan a:

- A sí mismo
- Cualquier parámetro pasado
- Los objetos que crea
- Objetos componentes

### Cómo Programar Deliberadamente
- Sé consciente de lo que haces.
- No codifique con los ojos vendados.
- Procede a partir de un plan.
- Confíe sólo en cosas fiables.
- Documenta tus suposiciones.
- Pruebe tanto las hipótesis como el código.
- Priorice sus esfuerzos.
- No sea esclavo de la historia.

### Cuándo refactorizar
- Descubres una violación del principio DRY.
- Descubres cosas que podrían ser más ortogonales.
- Tus conocimientos mejoran.
- Los requisitos evolucionan.
- Necesitas mejorar el rendimiento.

### Cortar el nudo gordiano
Cuando resuelva problemas _imposibles_, pregúntese:

- ¿Existe una forma más fácil?
- ¿Estoy resolviendo el problema correcto?
- ¿Por qué es un problema?
- ¿Por qué es difícil?
- ¿Tengo que hacerlo así?
- ¿Hay que hacerlo así?

### Aspectos de las pruebas
- Pruebas unitarias
- Pruebas de integración
- Validación y verificación
- Agotamiento de recursos, errores y recuperación
- Pruebas de rendimiento
- Pruebas de usabilidad
- Pruebas de las propias pruebas

