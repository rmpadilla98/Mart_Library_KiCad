# Mart Library KiCad

Librería global de símbolos, footprints y modelos 3D para los proyectos electrónicos del equipo Mart.

## 📁 Estructura
- **Symbols/** → Librerías de símbolos (`.kicad_sym`)
- **Footprints/** → Footprints en formato `.pretty`
- **3DModels/** → Modelos 3D en `.step`
- **Scripts/** → Herramientas opcionales para validación o generación

## 🛠 Cómo usar esta librería en KiCad 9

### 1. Clonar este repositorio
git clone https://github.com/<TU_ORGANIZACION>/Mart_Library_KiCad.git

### 2. Añadir símbolos
KiCad → Preferences → Manage Symbol Libraries → Add  
Ruta: `Mart_Library_KiCad/Symbols/Mart_Symbols.kicad_sym`  
Tipo: **Global**

### 3. Añadir footprints
KiCad → Preferences → Manage Footprint Libraries → Add  
Ruta: `Mart_Library_KiCad/Footprints/Mart_Footprints.pretty`  
Tipo: **Global**

### 4. Añadir modelos 3D
KiCad → Preferences → Configure Paths  
Añadir variable:
MART_3D = /ruta/a/Mart_Library_KiCad/3DModels

## 🔄 Flujo de trabajo recomendado
1. Crear rama feature para añadir o modificar un componente  
2. Hacer commit y push  
3. Crear Pull Request  
4. Revisar cambios antes de hacer merge  

## 🧩 Reglas internas
- Nombres consistentes  
- Footprints validados  
- Modelos 3D alineados  
- No duplicar componentes  
