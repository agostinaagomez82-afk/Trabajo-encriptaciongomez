
# Trabajo Práctico: Encriptación

## Parte 1: Cuestionario de Investigación

### 1. Objetivo principal de la encriptación en seguridad informática

El objetivo principal es mantener la confidencialidad de los datos.

Básicamente se agarra información que se puede leer (texto plano) y se la transforma con un algoritmo y una clave en algo ilegible (texto cifrado). Si alguien intercepta los datos o entra donde no debe, ve información sin sentido a menos que tenga la clave correcta para volverlo a leer.

### 2. Niveles de encriptación en bases de datos

- **Encriptación en tránsito:** Protege los datos cuando viajan por la red, por ejemplo entre la aplicación o el usuario y el servidor de la base de datos. Se suele utilizar TLS/SSL.

- **Encriptación a nivel de columna o campo:** Cifra ciertos datos sensibles dentro de una tabla, como tarjetas de crédito, contraseñas o DNI.

- **Encriptación a nivel de tabla o espacio de tablas:** Encripta toda una tabla o un tablespace, protegiendo todos los datos de esa estructura.

- **Encriptación transparente de datos (TDE):** Cifra los archivos físicos de la base de datos y las copias de seguridad directamente en el disco.

### 3. Diferencia principal entre cifrado simétrico y asimétrico

La diferencia está en cómo se manejan las claves:

- **Simétrico:** Usa una sola clave tanto para encriptar como para desencriptar. Es rápido, pero hay que compartir la clave de forma segura. Ejemplo: AES.

- **Asimétrico:** Usa dos claves relacionadas entre sí: una pública y una privada. Ejemplo: RSA.

---

## Parte 3: Actividades Prácticas

### Desafío 1: Encriptar (+3)

- B → E
- A → D
- N → Q
- C → F
- O → R

**Palabra original:** BANCO

**Palabra cifrada:** EDQFR

### Desafío 2: Desencriptar (-3)

- K → H
- O → L
- U → R
- O → L

**Apellido cifrado:** KOUO

**Apellido real:** HLRL
