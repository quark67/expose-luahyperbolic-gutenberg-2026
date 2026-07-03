# expose-luahyperbolic-gutenberg-2026


Slides de l'exposé "Géométrie hyperbolique avec Lua et (Lua)Latex" (2 juillet 2026, en visio)

https://www.gutenberg-asso.fr/2-juillet-2026-Geometrie-hyperbolique-dans-lua-latex-avec-le-package

(Attention, ces slides contiennent essentiellement des illustrations, animations et du code, elles ne sont pas autocontenues et risquent d'être incompréhensibles sans l'exposé oral)

## Résumé de l'exposé : 

Le package [luahyperbolic](https://www.ctan.org/pkg/luahyperbolic) permet d’effectuer des calculs et de produire des illustrations de géométrie hyperbolique dans le modèle du disque de Poincaré.

Dans cet exposé, nous présenterons dans un premier temps le disque de Poincaré et ses propriétés métriques les plus importantes, en particulier la notion de géodésique : le plus court chemin entre deux points n’est plus, en général, le segment, et le cinquième postulat d’Euclide n’est plus vérifié. Les concepts géométriques habituels, rotations, symétries, translations, subsistent souvent mais leurs propriétés peuvent évoluer. Par exemple, la somme des angles d’un triangle est inférieure à π et ses médiatrices ne sont pas toujours concourantes !

Dans la seconde partie de l’exposé, nous verrons comment produire, à l’aide du package luahyperbolic, les illustrations montrées dans la première partie. Le package est écrit en lua et permet de définir des points, segments, droites, cercles, horocycles etc, d’effectuer des calculs sur ces objets (intersections, distances, images par différentes isométries hyperboliques), et finalement de produire des figures, dont des figures de pavages hyperboliques.

## Dépôt github du package 'luahyperbolic'

https://github.com/dmegy/luahyperbolic/