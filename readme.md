# MaskTheFace - Convert face dataset to masked dataset
### Clone the repository
```
git clone https://github.com/aqeelanwar/MaskTheFace.git
```

### Instalar paquetes requeridos
El repositorio provee un archivo .txt para instalar los requerimientos con el siguiente comando
```
cd MaskTheFace
pip install –r requirements.txt
```
## Como ejecutar MaskTheFace

```
cd MaskTheFace

python mask_the_face.py --path <path-to-file-or-dir> --mask_type <type-of-mask> --verbose --write_original_image

# Example
python mask_the_face.py --path C:\Users\estilos\.spyder-py3\grafica\proyecto\MaskTheFace-master\img\lfw_mini --mask_type N95 --verbose --write_original_image
```
