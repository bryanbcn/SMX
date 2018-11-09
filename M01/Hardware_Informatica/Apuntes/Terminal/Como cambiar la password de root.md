# Metodo 1
## Con permisos Root
- Primero que todo,Ponemos en el terminal
 
  $ sudo su
  
- Ponemos la contraseña root actual y entramos como root, Vamos a cambiar la contraseña con el siguiente comando
  
  $ passwd root
  
- Ahora podremos poner una contraseña nueva, hecho esto nuestra contraseña habra sido cambiada
  
# Metodo 2 
## Sin permisos Root

- Con este comando no nos pedira contraseña para entrar como root se cambiara mas facil

  $ sudo passwd root 
 
- Una vez echo esto te pedira nueva contraseña, cuando ya este echo para ver si cambiastes la contraseña entramos con el comando

  $ su -
 
- Nos pedira la contraseña que cambiamos,nose ve que se escirbe en la contraseña es por mas seguridad.
