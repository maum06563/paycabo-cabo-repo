Ver refs remotas (alternativa)
git branch -r | grep origin/payjoy || echo "no encontrada en branch -r"Comprobar si existe la rama remota payjoy
git ls-remote --heads origin payjoy

