# Step by step : 

- creer l’architecture du projet
include
sources
map
texture
makefile
…

- faire des maps simples
- map complexes
- map fausses pour tester validité ?

- installer minilibx ( faire comme pour so_long ? Linux + mac )
- libft ? necessaire ou pas ?

- faire le parsing du projet
    - check extension .cub
    - check presence de toutes les textures NO, SO, WE, EA
    - check les couleurs ( entre 0 - 255)
    - check validité des maps
        - entourée de murs (1)
        - validité des caracteres comme ds so_long mais avec 0, 1, N, S, E, W
    - faire des messages d’erreur pour chaque cas et quitter de maniere clean
    
- creer des structures
    - struct player
    - struct game
    - struct pour texture ? couleur ?
    - faire une struc generale avec tt dedans
    
- initialiser MLX et creer les fenetres
- charger les textures (mlx_xpm_file_to_image)
- buffer d’image ??
- gerer fermeture fenetre ( ESC + la croix )

- RAYCASTING
- ( plein de trucs a faire ici mais j’ai pas encore assez de connaissance pour savoir quoi )

- player avec touche W A S D
- mise a jour de position du joueur
- gerer les colisions avec les murs ( c’est bonus mais on va le faire immediatement  parce que c’est naze de traverser les murs )

- boucle mlx comme ds so_long
- gerer évenement clavier et fermeture de fenetre

- liberer touuuuut
    - les maps
    - textures
    - image buffer
    - fenetre et struct mlx
- attention aux leaks valgrind etc …
