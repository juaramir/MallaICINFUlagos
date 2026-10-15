# juaramir.github.io

En la línea 1221 aproximadamente modificar "const DATA_ICINF" para cambiar los datos de los cursos, la estructura es la misma del archivo "data_ICINF.json"

La estructura de DATA_ICINF es Semestre: [Nombre Asignatura, Codigo, Horas Docencia Directa, Horas Trabajo Autónomo, SCT, Competencia a la que está asociada, ["Previaturas"], Semestre en que se imparte]
["Previaturas"] puede quedar como [] para cuando no posee previaturas, pueden ser separadas con comas cuando es más de una
Semestre en que se imparte puede ser A: Ambos, I: Impar, P: Par.
Competencia: es una sigla según lo indicado en "const COLORS_ICINF"

En la línea Siguiente "const COLORS_ICINF" se pueden modificar las competencias y colores, la misma estructura del archivo "colors_ICINF.json"
MAX_SCT_SEMESTER = 33; Es la cantidad máxima de SCT por semestre para establecer una advertencia.

const LICENCIATURA_CONFIG se establecen los prerequisitos de la licenciatura.


NOTA:
Los archivos json no son utilizados, solo son referenciales de la estructura.
