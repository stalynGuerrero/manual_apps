---
title: "Manual de Usuario Aplicación Validación UPMS"
author: "Andrés Gutiérrez^[Experto Regional en Estadísticas Sociales - Comisión Económica para América Latina y el Caribe (CEPAL) -  andres.gutierrez@cepal.org], Stalyn Guerrero^[Consultor - Comisión Económica para América Latina y el Caribe (CEPAL), guerrerostalyn@gmail.com], Cristian Alvarez^[Consultor - Comisión Económica para América Latina y el Caribe (CEPAL), cristianjalvarez123@gmail.com]"
date: "2024-11-12"
documentclass: book
biblio-style: apalike
link-citations: yes
colorlinks: yes
lot: yes
lof: yes
fontsize: 12pt
geometry: margin=3cm
header-includes:
  - \usepackage[spanish, spanishkw, onelanguage, linesnumbered]{algorithm2e}
github-repo: psirusteam/coneval
description: "Manual de procesamiento."
knit: "bookdown::render_book"
lang: es
linkcolor: blue
output: 
  bookdown::pdf_book:
    toc: true
    toc_depth: 1
    keep_tex: true
    latex_engine: xelatex
---




# Introducción {-}

Este documento proporciona una guía detallada para el uso de la aplicación de Validación de Unidades Primarias de Muestreo (UPMS). La aplicación está diseñada para asistir en la validación de UPMs en áreas geográficas específicas, permitiendo la visualización de mapas, la selección y unión de polígonos, así como la generación de estadísticas y reportes necesarios para el análisis de cada polígono de muestra.

El proceso de validación se centra en la evaluación de la adecuación de las UPMs iniciales, considerando criterios como el área, el número de viviendas, y características geográficas específicas. A partir de esta evaluación, los usuarios pueden tomar decisiones informadas sobre la conformación de nuevas UPMs cuando sea necesario.

A lo largo de este documento, se describen los pasos para poner en marcha la aplicación, los elementos de la interfaz de usuario, y el procedimiento para la creación y modificación de UPMs, con ejemplos prácticos que ilustran el flujo de trabajo.


