# CAI1-INSEGUS

Este repositorio contiene una solución de software para cifrar y descifrar archivos utilizando el algoritmo AES256-GCM en Python. La solución proporciona una forma eficaz de proteger la confidencialidad de los datos sensibles mediante un cifrado robusto y seguro.

## Uso

El código proporcionado incluye dos funciones principales: `encrypt_file_AES256_GCM` y `decrypt_file_AES256_GCM`, que se utilizan para cifrar y descifrar archivos respectivamente. Estas funciones requieren una clave de cifrado y la ubicación del archivo de entrada.

### Ejemplo de cifrado:

```python
key = os.urandom(32)  # Clave aleatoria de 256 bits (32 bytes)
input_file = "/Users/fonsi/Desktop/pruebasCAI1G/prueba.txt"  # Especifica la ruta completa del archivo de entrada

# Cifrar el archivo
encrypt_file_AES256_GCM(key, input_file)

# Descifrar el archivo
decrypt_file_AES256_GCM(key, archivo_cifrado) # El archivo cifrado lo proporciona la función anterior

