# Data-Transformation
 
En este proyecto, se desarrolla las actividades propuestas en  [R for Data Science](https://es.r4ds.hadley.nz/index.html) de Hadley Wickham y Garrett Grolemund.  

Se examina las funciones del paquete dplyr para resolver desafios de reducir el volúmen de datos y lograr las datos necesarios para responder a ciertas preguntas.

Para estos ejercicios, los autores proponen  trabajar con datos de los vuelos de los principales aeropuestos de Nueva York de la oficina de Estadística de Transporte de EEUU.
```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

```{r, echo=FALSE}
options(repos = list(CRAN="http://cran.rstudio.com/"))
```

```{r, include=FALSE}
##Asignamos directorio de trabajo. 
setwd("C:/Users/Vane/Documents/R basico")
```

```{r load-packages, message=FALSE, warning=F, echo=F}
library(tidyverse)
```

```{r data, include= FALSE, message = FALSE, warning=F}
library(nycflights13)
data("fligths")
```
## Transformación

En este proyecto, se desarrolla las actividades propuestas en  [R for Data Science](https://es.r4ds.hadley.nz/index.html) de Hadley Wickham y Garrett Grolemund.  

Se examina las funciones del paquete dplyr para resolver desafios de reducir el volúmen de datos y lograr las datos necesarios para responder a ciertas preguntas.

Para estos ejercicios, los autores proponen  trabajar con datos de los vuelos de los principales aeropuestos de Nueva York de la oficina de Estadística de Transporte de EEUU.

```{r primeras filas, echo=F}
head(flights)
```

```{r tipo de variables, echo=T}
glimpse(flights)
```

```{r, eval=F}
??flights
```
