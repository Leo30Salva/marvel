1. Creamos el directorio marvel e iniciamos un repositorio en él.

mkdir marvel
cd marvel
git init

2. Renombramos la rama master/main a marvel

git branch -m master marvel
git branch --show-current

3. Creamos un fichero llamado filmografia.txt

touch filmografia.txt

4. Lo añadimos al repositorio como “Índice de películas”

git add filmografia.txt
git commit -m "Índice de películas"

5. Creamos una rama llamada capitan_america

git branch capitan_america
git checkout capitan_america 
nano filmografia.txt 
git add filmografia.txt
git commit -m "Pelicula 1"
git checkout marvel 
git merge capitan_america 

6. Creamos una rama llamada capitana_marvel

git branch capitana_marvel
git checkout capitana_marvel 
nano filmografia.txt
git add filmografia.txt 
git commit -m "Pelicula 2"
git checkout marvel 
git merge capitana_marvel 

7. Creamos una rama llamada ironman

git branch ironman
git checkout ironman 
nano filmografia.txt
git add filmografia.txt 
git commit -m "Pelicula 3"
nano filmografia.txt
git add filmografia.txt 
git commit -m "Pelicula 4"
git checkout marvel 
git merge ironman 

8. Creamos una rama llamada hulk

git branch hulk
git checkout hulk
nano filmografia.txt
git add filmografia.txt 
git commit -m "Pelicula 5"
git checkout marvel 
git merge hulk 

9. Creamos una rama llamada thor

git branch thor
git checkout thor
nano filmografia.txt
git add filmografia.txt 
git commit -m "Pelicula 6"
git checkout marvel 
git merge thor 

10. Creamos una rama llamada vengadores

git branch vengadores
git checkout vengadores 
nano filmografia.txt
git add filmografia.txt 
git commit -m "Pelicula 7"
git checkout marvel 
git merge vengadores 

11. Cambiamos a la rama ironman

git checkout ironman 
nano filmografia.txt 
git rebase marvel 
nano filmografia.txt 
git add filmografia.txt 
git commit -m "Pelicula 8"
git checkout marvel 
git merge ironman

12. Cambiamos la rama thor

git checkout thor 
nano filmografia.txt
git add .
git commit -m "Pelicula 9"
git checkout marvel
git merge thor

13. Cambiamos la rama capitan_america

git checkout capitan_america
git nano filmografia.txt
git add .
git commit -m "Pelicula 10"
git checkout marvel
git merge capitan_america

14. Crearemos una rama llamada guardianes_galaxia

git branch guardianes_galaxia
git checkout guardianes_galaxia
nano filmografia.txt
git add . 
git commit -m "Pelicula 11"
git checkout marvel
git merge guardianes_galaxia
git nano filmografia.txt
git add . 
git commit -m "Pelicula 12"
git checkout marvel	
git merge guardianes_galaxia

15. Cambiamos la rama vengadores

git checkout vengadores
nano filmografia.txt
git add .
git commit -m "Pelicula 13"
git checkout marvel
git merge vengadores

16. Creamos una rama llamada antman

git branch antman
git checkout antman
nano filmografia.txt
git add .
git commit -m "Pelicula 14"
git checkout marvel
git merge antman

17. Cambios la rama capitan_america

git checkout capitan_america
nano filmografia.txt
git merge marvel
nano filmografia.txt
git add .
git commit -m "Pelicula 15"
git checkout marvel
git merge capitan_america

18. Creamos una rama llamada black_widow

git branch black_widow
git checkout black_widow
nano filmografia.txt
git add .
git commit -m "Pelicula 16"
git checkout marvel
git merge black_widow

19. Creamos una rama llamada spiderman

git branch spiderman
git checkout spiderman
nano filmografia.txt
git add .
git commit -m "Pelicula 17"
git checkout marvel
git merge spiderman

20. Creamos una rama llamada strange

git branch strange
git checkout strange
nano filmografia.txt
git add .
git commit -m "Pelicula 18"
git checkout marvel
git merge strange

21. Creamos una rama llamada black_phanter

git branch strange
git checkout strange
nano filmografia.txt
git add . 
git commit -m "Pelicula 19"
git checkout marvel
git merge black_phanter

22. Cambiamos a la rama thor

git checkout thor
git merge marvel
nano filmografia.txt
git add . 
git commit -m "Pelicula 20"
git checkout marvel
git merge thor

23. Cambiamos a la rama vengadores

git checkout vengadores
git merge marvel
nano filmografia.txt
git add .
git commit -m "Pelicula 21"
git checkout marvel
git merge vengadores

24. Cambiamos a la rama antman

git checkout antman
git merge marvel
git nano filmografia.txt
git add . 
git commit -m "Pelicula 22"
git checkout marvel
git merge antman

25. Cambiamos a la rama vengadores

git checkout vengadores
git merge marvel
nano filmografia.txt
git add .
git commit -m "Pelicula 23"
git checkout marvel
git merge vengadores 

26. Creamos una rama llamada shangchi

git branch shangchi
git checkout shangchi
git add . 
git commit -m "Pelicula 24"
git checkout marvel
git merge shangchi

27. Cambiamos a la rama spiderman

git checkout spiderman
git merge marvel
nano filmografia.txt
git add . 
git commit -m "Pelicula 25"
git checkout marvel
git merge spiderman

28. Creamos una rama llamada eternals

git branch eternals
git checkout eternals
nano filmografia.txt
git add . 
git commit -m "Pelicula 26"
git checkout marvel
git merge eternals

29. Cambiamos a la rama spiderman

git checkout eternals
git merge marvel
nano filmografia.txt
git add . 
git commit -m "Pelicula 27"
git checkout marvel
git merge spiderman

30. Cambiamos a la rama strange

git checkout strange
git merge marvel
nano filmografia.txt
git add . 
git commit -m "Pelicula 28"
git checkout marvel
git merge strange

31. Cambiamos a la rama thor

git checkout thor
git merge marvel
nano filmografia.txt
git add . 
git commit -m "Pelicula 29"
git checkout marvel
git merge thor

32. Cambiamos a la rama black_panther

git checkout black_phanter
git merge marvel
nano filmografia.txt
git add . 
git commit -m "Pelicula 30"
git checkout marvel
git merge black_phanter

SUBIR A GITHUB

git remote add origin https://github.com/Leo30Salva/marvel.git 
git push -u origin marvel
TOKEN: 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
nano MARKDOWN.MD
git push -u origin marvel

