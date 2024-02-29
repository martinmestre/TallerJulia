# Taller Julia
Algunos recursos (notebooks) para iniciar en la práctica.


# Instalación de Julia
Seguiremos la instalación propuesta en las [Notas de Julia](https://m3g.github.io/JuliaNotes.jl/stable/workflow/) de Leandro Martínez, basada en el programa instalador [juliaup](https://github.com/JuliaLang/juliaup).
Para instalar la ultima versión estable de Julia basta ejecutar el siguiente comando como
usuario:

`curl -fsSL https://install.julialang.org | sh`

# Instalación de paquetes
Los códigos subidos realizan la instalación automática de los paquetes necesarios en un
entorno (environment) local (asociado al directorio local). Puede tardar un buen tiempo
la primera vez que se instalen nuevos paquetes. Asimismo, Julia puede tardar mucho la primera
vez que compila las funciones, no frustarse ☺.
Para mayor información sobre el administrador de paquetes de Julia, "Pkg", se puede
leer [estas notas](https://m3g.github.io/JuliaNotes.jl/stable/workflow/#Environments).