Lorenzo de Castro, Bautista Chalier, Lucio Barrionuevo, Ian Montaño, Emanuel Chumbes, Emanuel Silva
# Trabajo Práctico Integrador - Administración de Linux

## Integrantes del grupo
- Lorenzo de Castro
- Bautista Chalier
- Lucio Barrionuevo
- Ian Montaño
- Emanuel Chumbes
- Emanuel Silva
  
## Contenido
- root.tar.gz, etc.tar.gz, opt.tar.gz, www_dir.tar.gz, backup_dir.tar.gz: directorios comprimidos del servidor.
- var.tar.gz.part_aa hasta var.tar.gz.part_ad: directorio /var spliteado en partes de 20MB.

## Reconstrucción del /var
Para reconstruir el archivo completo:
cat var.tar.gz.part_* > var.tar.gz
