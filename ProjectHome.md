<a href='Hidden comment: 
*NOTE: the online demo may be offline on Tuesday, Dec 22, between 11:00 and 15:00 UTC (8:00-12:00 in Argentina)*
'></a>


_(El texto en castellano se encuentra más abajo)_


## What is Litero? ##

Litero is an Online Public Access Catalog (OPAC) that attempts to implement some of the recommendations in Martha Yee's article _[FRBRization: a Method for Turning Online Public Finding Lists into Online Public Catalogs](http://escholarship.org/uc/item/7gx5v7q5)_ (2005). The main goal is to make a better use of the data stored in current MARC 21 bibliographic and authority records created according to AACR2, in order to improve the retrieval and display capabilities of library catalogs.

Please note that **Litero is under development; it's not a product ready for use yet**.

The paper [Rediseño de OpacMarc usando conceptos de FRBR](http://dl.dropbox.com/u/2434042/Redise%C3%B1o%20de%20OpacMarc%20usando%20conceptos%20de%20FRBR.pdf) (in Spanish), presented at the II Encuentro Nacional de Catalogadores (Biblioteca Nacional, Buenos Aires, Argentina) in November 2009, describes the main features of Litero.

A [very early online demo](http://litero.inmabb-conicet.gob.ar/demo/browse/) is available. It's just a prototype that implements part of the desired features. For example, see what's under the following names in the alphabetic index:

  * [Hofstadter](http://litero.inmabb-conicet.gov.ar/demo/browse/?index=accesspoints_all&start=hofstadter)—an author with works _by_ him, works _related to_ him, and works _about_ him.
  * [Shakespeare](http://litero.inmabb-conicet.gov.ar/demo/browse/?index=accesspoints_all&start=shakespeare)—same as above, plus some works with many editions and related works (e.g. _Macbeth_)
  * [Palacios](http://litero.inmabb-conicet.gov.ar/demo/browse/?index=accesspoints_all&start=palacios)—a cross-reference

The development of Litero began in July 2009. Source code and extensive documentation will be available here.

The core of Litero is written in Python, and the Web interface uses the [Django](http://djangoproject.com) framework. The database engine is [Malete](http://malete.org/), a modern successor to CDS/ISIS—though other alternatives may be considered. Litero is written as a _[literate program](http://en.wikipedia.org/wiki/Literate_programming)_, using [noweb](http://www.cs.tufts.edu/~nr/noweb/) (so its name probably comes from "literate opac"!).

Litero is being developed at INMABB, Instituto de Matemática de Bahía Blanca (Conicet / Universidad Nacional del Sur), in Argentina. INMABB is also the home of two related projects: [Catalis](http://code.google.com/p/catalis/), and Litero's ancestor [OpacMarc](http://code.google.com/p/opacmarc/).

If you are interested in this project, please **[join the discussion list](http://groups.google.com/group/litero)**. (Or you may contact the project owner, fjgomez at gmail.)


---


## ¿Qué es Litero? ##

Litero es un Catálogo en Línea de Acceso Público (OPAC) que intenta implementar algunas de las recomendaciones del artículo de Martha Yee _[FRBRization: a Method for Turning Online Public Finding Lists into Online Public Catalogs](http://escholarship.org/uc/item/7gx5v7q5)_ (2005). El objetivo principal es hacer un mejor uso de los datos almacenados en los actuales registros MARC 21 bibliográficos y de autoridad creados de acuerdo con AACR2, con el fin de mejorar las capacidades de recuperación y visualización de los catálogos de bibliotecas.

Por favor, tenga en cuenta que **Litero está en desarrollo; no es un producto listo para ser usado aún**.

El artículo [Rediseño de OpacMarc usando conceptos de FRBR](http://dl.dropbox.com/u/2434042/Redise%C3%B1o%20de%20OpacMarc%20usando%20conceptos%20de%20FRBR.pdf), presentado en el II Encuentro Nacional de Catalogadores (Biblioteca Nacional, Buenos Aires, Argentina) en noviembre de 2009, describe las principales características de Litero.

Se encuentra disponible un [demo en línea, bastante prematuro](http://litero.inmabb-conicet.gob.ar/demo/browse/). Es apenas un prototipo que implementa parte de la funcionalidad deseada. Por ejemplo, vea lo que hay bajo los siguientes nombres en el índice alfabético:

  * [Hofstadter](http://litero.inmabb-conicet.gov.ar/demo/browse/?index=accesspoints_all&start=hofstadter)—un autor con obras _de_ él, obras _relacionadas con_ él, y obras _acerca de_ él.
  * [Shakespeare](http://litero.inmabb-conicet.gov.ar/demo/browse/?index=accesspoints_all&start=shakespeare)—igual que arriba, más algunas obras con muchas ediciones y obras relacionadas (e.g. _Macbeth_)
  * [Palacios](http://litero.inmabb-conicet.gov.ar/demo/browse/?index=accesspoints_all&start=palacios)—una referencia cruzada

El desarrollo de Litero se inició en julio de 2009. El código fuente y una extensa documentación estarán disponibles aquí mismo.

El núcleo de Litero está escrito en Python, y la interfaz Web utiliza el framework [Django](http://djangoproject.com). El motor de bases de datos es [Malete](http://malete.org/), un moderno sucesor de CDS/ISIS—si bien se pueden llegar a considerar otras alternativas. Litero está escrito como un _[literate program](http://en.wikipedia.org/wiki/Literate_programming)_, usando [noweb](http://www.cs.tufts.edu/~nr/noweb/) (así que su nombre probablemente viene de "literate opac"!)

Litero está siendo desarrollado en el INMABB, Instituto de Matemática de Bahía Blanca (Conicet / Universidad Nacional del Sur), en Argentina. El INMABB es también el "hogar" de dos proyectos relacionados: [Catalis](http://code.google.com/p/catalis/), y el antecesor de Litero, [OpacMarc](http://code.google.com/p/opacmarc/).

Si usted tiene interés en este proyecto, por favor **[únase a la lista de discusión](http://groups.google.com/group/litero)**. (O puede contactar al responsable del proyecto, fjgomez at gmail.)


---


Fernando Gómez, 16-aug-2010