<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuestionario de Análisis de Datos</title>
    <!-- Incluimos Tailwind CSS para un diseño moderno -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Usamos la fuente Inter, que es muy legible y moderna -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            /* Fondo con gradiente tecnológico */
            background-color: #f0fdf4; /* green-50 */
        }

        /* Clase para ocultar elementos */
        .hidden {
            display: none;
        }

        /* Estilos de los botones de opción */
        .option-btn {
            background-color: #ffffff; /* white */
            border: 2px solid #d1d5db; /* gray-300 */
            color: #374151; /* gray-700 */
            padding: 1rem;
            border-radius: 0.5rem;
            text-align: left;
            width: 100%;
            font-weight: 600;
            transition: all 0.3s ease;
            cursor: pointer;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }

        .option-btn:hover {
            background-color: #f0fdf4; /* green-50 */
            border-color: #22c55e; /* green-500 */
            transform: translateY(-2px);
        }

        /* Clases para feedback visual */
        .option-btn.correct {
            background-color: #16a34a; /* green-600 */
            border-color: #15803d; /* green-700 */
            color: white;
        }

        .option-btn.incorrect {
            background-color: #dc2626; /* red-600 */
            border-color: #b91c1c; /* red-700 */
            color: white;
        }

        .option-btn.incorrect {
            background-color: #991b1b; /* red-800 */
            border-color: #ef4444; /* red-500 */
            color: white;
        }

        /* Deshabilitar botones después de la respuesta */
        .option-btn:disabled {
            opacity: 0.7;
            cursor: not-allowed;
        }

        /* Estilo del bloque de código */
        pre {
            background-color: #f3f4f6; /* gray-100 */
            border: 1px solid #e5e7eb; /* gray-200 */
            border-radius: 0.5rem;
            padding: 1rem;
            overflow-x: auto;
            color: #1f2937; /* gray-800 */
            position: relative;
        }
         
        /* Estilo para el código inline */
        /* FIX: Reemplazados los @apply (que no funcionan con CDN) por CSS estándar */
        code {
            background-color: #f3f4f6; /* gray-100 */
            color: #047857; /* green-700 */
            border-radius: 0.25rem;
            padding: 0.25rem 0.375rem;
            font-family: monospace;
            font-size: 0.875rem; /* text-sm */
            font-weight: 600;
        }

        pre code {
            background-color: transparent;
            color: inherit;
            border-radius: 0;
            padding: 0;
            font-size: 1rem; /* text-base */
            font-weight: 400;
        }
        
        /* Botón de copiar */
        .copy-btn {
            position: absolute;
            top: 0.5rem;
            right: 0.5rem;
            background-color: #e5e7eb; /* gray-200 */
            color: #1f2937; /* gray-800 */
            border: none;
            border-radius: 0.375rem;
            padding: 0.25rem 0.75rem;
            font-size: 0.875rem;
            cursor: pointer;
            transition: background-color 0.2s;
        }

        .copy-btn:hover {
            background-color: #d1d5db; /* gray-300 */
        }

        /* Estilo del diploma */
        .diploma {
            background-color: #ffffff;
            color: #1e293b;
            border: 8px solid #22c55e; /* green-500 */
            border-radius: 0.5rem;
            padding: 2rem;
            text-align: center;
            box-shadow: 0 0 30px rgba(34, 197, 94, 0.5);
        }

        /* Estilo del botón de ayuda */
        .help-btn {
            background-color: #f3f4f6; /* gray-100 */
            border: 2px solid #d1d5db; /* gray-300 */
            color: #374151; /* gray-700 */
            font-weight: bold;
            width: 2rem;
            height: 2rem;
            border-radius: 9999px; /* Círculo */
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.2s ease;
        }
        .help-btn:hover {
            background-color: #dcfce7; /* green-100 */
            border-color: #22c55e; /* green-500 */
        }

        /* Estilos del Modal de Ayuda */
        #help-modal p {
            margin-bottom: 0.75rem; /* mb-3 */
        }
        #help-modal code {
             font-size: 1rem; /* text-base */
        }

    </style>
</head>
<body class="text-gray-800 min-h-screen flex items-center justify-center p-4">

    <!-- Contenedor principal de la aplicación -->
    <div id="app-container" class="w-full max-w-3xl mx-auto">

        <!-- Pantalla de Bienvenida -->
        <div id="welcome-screen" class="text-center p-8 bg-white shadow-2xl border border-gray-200 rounded-2xl">
            <h1 class="text-4xl font-bold mb-4 text-green-600">Cuestionario de Análisis de Datos</h1>
            <h2 class="text-2xl font-semibold mb-6">Demuestra lo que sabes 🧠</h2>
            <p class="text-lg mb-8 text-gray-600">¡Hola! Este es un cuestionario para probar tus conocimientos en análisis de datos, Pandas, Python y Power BI.</p>
            <p class="text-lg mb-4 text-gray-600">Responde las preguntas y, si te atoras, <b>¡oprima el botón de ayuda (?)</b> para ver la explicación del concepto!</p>
            <p class="text-lg mb-8 text-gray-600">Para saber a quién felicitar al final, regálame tu nombre:</p>
            <input type="text" id="player-name-input" class="w-full max-w-md p-3 rounded-lg bg-white border border-gray-300 text-gray-800 text-lg focus:outline-none focus:ring-2 focus:ring-green-500" placeholder="Escriba su nombre aquí...">
            <button id="start-game-btn" class="mt-6 w-full max-w-md bg-green-600 hover:bg-green-500 text-white text-xl font-bold py-3 px-6 rounded-lg shadow-lg transform transition-all duration-300 hover:scale-105">
                ¡Empezar Cuestionario!
            </button>
        </div>

        <!-- Pantalla de Juego -->
        <div id="game-screen" class="hidden p-6 md:p-10 bg-white shadow-2xl border border-gray-200 rounded-2xl">
            <!-- Encabezado del Juego -->
            <div class="flex justify-between items-center mb-6 pb-4 border-b border-gray-200">
                <div class="flex items-center gap-3">
                    <h2 class="text-2xl font-bold text-green-600" id="step-title"></h2>
                    <!-- Botón de ayuda -->
                    <button id="help-button" class="help-btn">?</button>
                </div>
                <div class="text-lg font-semibold">
                    <span class="mr-2">Vidas:</span>
                    <span id="lives-container" class="text-xl"></span>
                </div>
            </div>

            <!-- Contenedor de Concepto (No se usará en este quiz, pero se deja por si acaso) -->
            <div id="concept-container" class="hidden">
                <p class="text-xl font-medium mb-6" id="concept-text"></p>
                <button id="concept-continue-btn" class="mt-4 w-full bg-sky-600 hover:bg-sky-500 text-white font-bold py-3 px-6 rounded-lg shadow-lg transition-all duration-300">
                    Continuar
                </button>
            </div>

            <!-- Contenedor de Pregunta -->
            <div id="question-container" class="hidden">
                <p class="text-xl font-medium mb-6" id="question-text"></p>
                <div id="answer-options" class="grid grid-cols-1 gap-4">
                    <!-- Opciones de respuesta se insertan aquí -->
                </div>
            </div>

            <!-- Contenedor de Feedback -->
            <div id="feedback-container" class="hidden mt-6 p-5 bg-gray-50 rounded-lg border border-gray-200">
                <p id="feedback-text" class="text-lg"></p>
                <button id="next-step-btn" class="mt-4 w-full bg-green-600 hover:bg-green-500 text-white font-bold py-3 px-6 rounded-lg shadow-lg transition-all duration-300">
                    Siguiente
                </button>
            </div>

            <!-- Contenedor de Código (No se usará en este quiz, pero se deja por si acaso) -->
            <div id="code-container" class="hidden">
                <p class="text-lg font-medium mb-4" id="code-explanation"></p>
                <div class="relative mb-4">
                    <button class="copy-btn" id="copy-code-btn">Copiar</button>
                    <!-- Usamos un textarea oculto para la funcionalidad de copiar -->
                    <textarea id="clipboard-helper" style="position: absolute; left: -9999px; top: 0;"></textarea>
                    <pre><code id="code-snippet" class="language-python"></code></pre>
                </div>
                
                <h3 class="text-xl font-semibold mb-2 text-green-600">¿Qué significa lo que sale en Colab?</h3>
                <p class="text-lg p-4 bg-gray-50 rounded-lg border border-gray-200" id="output-explanation"></p>
                
                <button id="continue-btn" class="mt-6 w-full bg-green-600 hover:bg-green-500 text-white font-bold py-3 px-6 rounded-lg shadow-lg transition-all duration-300">
                    ¡Entendido! Continuar
                </button>
            </div>

        </div>

        <!-- Pantalla de Game Over -->
        <div id="gameover-screen" class="hidden text-center p-8 bg-white shadow-2xl border border-gray-200 rounded-2xl">
            <h1 class="text-4xl font-bold mb-4 text-red-500">¡Oh, no!</h1>
            <p class="text-xl mb-8 text-gray-600">Se nos acabaron las vidas. ¡Pero no te preocupes! El que persevera, alcanza. ¡Repasa los conceptos y vuelve a intentarlo! ¡Tú puedes!</p>
            <button id="restart-game-btn" class="w-full max-w-md bg-green-600 hover:bg-green-500 text-white text-xl font-bold py-3 px-6 rounded-lg shadow-lg transform transition-all duration-300 hover:scale-105">
                Volver a Empezar
            </button>
        </div>

        <!-- Pantalla de Diploma -->
        <div id="diploma-screen" class="hidden p-8">
            <div class="diploma">
                <h1 class="text-5xl font-black mb-4 text-green-600">¡FELICITACIONES!</h1>
                <p class="text-2xl font-semibold mb-6 text-gray-700">Este cuestionario certifica a:</p>
                <h2 id="diploma-name" class="text-4xl font-bold mb-8 text-gray-900" style="font-family: 'Brush Script MT', cursive;"></h2>
                <p class="text-2xl font-semibold mb-8 text-gray-700">Por superar con éxito el</p>
                <p class="text-3xl font-bold mb-10 text-gray-800">Cuestionario de Análisis de Datos</p>
                <p class="text-lg text-gray-600">¡Has demostrado un gran conocimiento en los conceptos clave del análisis de datos!</p>
            </div>
            <button id="play-again-btn" class="mt-8 w-full max-w-md mx-auto block bg-green-600 hover:bg-green-500 text-white text-xl font-bold py-3 px-6 rounded-lg shadow-lg transform transition-all duration-300 hover:scale-105">
                Jugar de Nuevo
            </button>
        </div>

    </div>

    <!-- Modal de Ayuda (Aquí se inyecta el contenido de la guía) -->
    <div id="help-modal" class="hidden fixed inset-0 bg-black bg-opacity-50 backdrop-blur-sm flex items-center justify-center p-4 z-50">
        <div class="bg-white w-full max-w-2xl p-6 rounded-2xl shadow-2xl border border-gray-200 text-gray-800 overflow-y-auto max-h-[90vh]">
            <h3 id="help-modal-title" class="text-2xl font-bold mb-4 text-green-600"></h3>
            <div id="help-modal-text" class="text-lg space-y-4">
                <!-- El contenido de la ayuda se inyecta aquí -->
            </div>
            <button id="help-modal-close-btn" class="mt-6 w-full bg-green-600 hover:bg-green-500 text-white font-bold py-2 px-5 rounded-lg shadow-lg">
                ¡Entendido!
            </button>
        </div>
    </div>


    <!-- Lógica del Juego -->
    <script>
        // Referencias a los elementos del DOM
        const welcomeScreen = document.getElementById('welcome-screen');
        const gameScreen = document.getElementById('game-screen');
        const gameoverScreen = document.getElementById('gameover-screen');
        const diplomaScreen = document.getElementById('diploma-screen');

        const nameInput = document.getElementById('player-name-input');
        const startGameBtn = document.getElementById('start-game-btn');
        
        const stepTitle = document.getElementById('step-title');
        const livesContainer = document.getElementById('lives-container');

        const conceptContainer = document.getElementById('concept-container');
        const conceptText = document.getElementById('concept-text');
        const conceptContinueBtn = document.getElementById('concept-continue-btn');

        const questionContainer = document.getElementById('question-container');
        const questionText = document.getElementById('question-text');
        const answerOptions = document.getElementById('answer-options');

        const feedbackContainer = document.getElementById('feedback-container');
        const feedbackText = document.getElementById('feedback-text');
        const nextStepBtn = document.getElementById('next-step-btn');

        const codeContainer = document.getElementById('code-container');
        const codeExplanation = document.getElementById('code-explanation');
        const codeSnippet = document.getElementById('code-snippet');
        const outputExplanation = document.getElementById('output-explanation');
        const continueBtn = document.getElementById('continue-btn');
        const copyCodeBtn = document.getElementById('copy-code-btn');
        const clipboardHelper = document.getElementById('clipboard-helper');

        const diplomaName = document.getElementById('diploma-name');
        const restartGameBtn = document.getElementById('restart-game-btn');
        const playAgainBtn = document.getElementById('play-again-btn');

        // Referencias al Modal de Ayuda
        const helpButton = document.getElementById('help-button');
        const helpModal = document.getElementById('help-modal');
        const helpModalTitle = document.getElementById('help-modal-title');
        const helpModalText = document.getElementById('help-modal-text');
        const helpModalCloseBtn = document.getElementById('help-modal-close-btn');

        // Estado del juego
        let playerName = "";
        let lives = 3;
        let currentStep = 0; // Índice del paso actual

        // =======================================================================
        // NUEVA BASE DE DATOS DE PREGUNTAS
        // Aquí es donde se insertó tu cuestionario de 10 preguntas.
        // Cada objeto "help" contiene la explicación del concepto.
        // =======================================================================
        const gameSteps = [
            {
                type: 'question',
                title: 'Pregunta 1/10: Propósito del Análisis',
                question: '¿Cuál es el propósito principal del análisis de datos?',
                options: [
                    { text: 'Recolectar datos sin procesarlos', correct: false },
                    { text: 'Eliminar datos innecesarios', correct: false },
                    { text: 'Adivinar tendencias sin pruebas', correct: false },
                    { text: 'Extraer información valiosa a partir de datos', correct: true }
                ],
                feedback_correct: '¡Correcto! La palabra clave es <b>extraer información valiosa</b>. Las otras opciones (<code>recolectar</code>, <code>eliminar</code>) son solo <i>pasos</i> del proceso, no el <i>propósito</i> final.',
                feedback_incorrect: 'Cerca. La respuesta correcta es "Extraer información valiosa". Recolectar o eliminar son solo pasos, no el propósito final.',
                help: {
                    title: 'Concepto: Propósito del Análisis de Datos',
                    text: '<p>El análisis de datos es un proceso completo. El objetivo final es <b>convertir datos crudos en conocimiento</b>.</p><p>Las otras opciones son solo partes del proceso:</p><ul class="list-disc list-inside ml-4"><li><code>Recolectar</code>: Es el primer paso, pero no el fin.</li><li><code>Eliminar datos (Limpieza)</code>: Es un paso necesario, pero no el propósito.</li><li><code>Adivinar</code>: Es lo opuesto al análisis, que se basa en <b>pruebas</b>.</li></ul><p class="mt-2"><b>Palabra Clave:</b> <code>Extraer información valiosa</code> (o <i>"insights"</i>) para tomar decisiones.</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 2/10: DataFrames de Pandas',
                question: '¿Qué tipo de datos se almacenan en un DataFrame de Pandas?',
                options: [
                    { text: 'Datos en formato de imagen', correct: false },
                    { text: 'Solo números', correct: false },
                    { text: 'Solo texto', correct: false },
                    { text: 'Datos tabulares con múltiples tipos de datos', correct: true }
                ],
                feedback_correct: '¡Exacto! Un <code>DataFrame</code> es una <b>tabla</b>. Su poder es que una columna puede ser de <code>texto</code>, otra de <code>números</code> y otra de <code>fechas</code>.',
                feedback_incorrect: 'No exactamente. Un DataFrame es mucho más flexible que eso.',
                help: {
                    title: 'Concepto: DataFrame de Pandas',
                    text: '<p>Un <code>DataFrame</code> es la estructura de datos principal en Pandas. Piénsalo como una tabla de Excel.</p><p>La clave es que es <b>tabular</b> (filas y columnas) y puede manejar <b>múltiples tipos de datos</b>:</p><ul class="list-disc list-inside ml-4"><li>Columna A: Nombres (<code>texto</code>)</li><li>Columna B: Edades (<code>números</code>)</li><li>Columna C: Fechas (<code>datetime</code>)</li></ul><p class="mt-2"><b>Palabras Clave:</b> <code>Datos Tabulares</code> y <code>Múltiples Tipos</code>.</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 3/10: Resumen Estadístico',
                question: '¿Qué método de Pandas se usa para obtener un resumen estadístico de un DataFrame?',
                options: [
                    { text: '.head()', correct: false },
                    { text: '.info()', correct: false },
                    { text: '.tail()', correct: false },
                    { text: '.describe()', correct: true }
                ],
                feedback_correct: '¡Muy bien! <code>.describe()</code> es el comando clave para obtener un <b>resumen estadístico</b> (media, mediana, min, max) de las columnas numéricas.',
                feedback_incorrect: 'Mmm, no. Esos otros métodos son útiles, pero para otras cosas.',
                help: {
                    title: 'Concepto: Métodos de Exploración de Pandas',
                    text: '<p>Cuando cargas un DataFrame, quieres "explorarlo". Hay varios métodos clave:</p><ul class="list-disc list-inside ml-4"><li><code>.head()</code>: Muestra las primeras 5 filas (la "cabeza").</li><li><code>.tail()</code>: Muestra las últimas 5 filas (la "cola").</li><li><code>.info()</code>: Da información sobre tipos de datos y nulos.</li><li><code>.describe()</code>: Este es el método que da un <b>resumen estadístico</b>. Para las columnas numéricas, calcula automáticamente la <code>media</code>, <code>desviación estándar</code>, <code>mínimo</code>, <code>máximo</code> y los <code>percentiles</code>.</li></ul><p class="mt-2"><b>Palabra Clave:</b> <code>.describe()</code> = <code>Resumen Estadístico</code>.</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 4/10: Manejo de Nulos',
                question: '¿Qué técnica se usa para manejar valores nulos en un conjunto de datos?',
                options: [
                    { text: 'Ignorar los valores nulos y continuar el análisis', correct: false },
                    { text: 'Eliminar todas las filas', correct: false },
                    { text: 'Convertir los valores nulos en texto', correct: false },
                    { text: 'Usar dropna() o fillna() en Pandas', correct: true }
                ],
                feedback_correct: '¡Correcto! Tienes dos opciones principales: <code>.dropna()</code> (<b>eliminar</b> la fila) o <code>.fillna()</code> (<b>rellenar</b> el hueco).',
                feedback_incorrect: '¡Ojo! Ignorar los nulos puede arruinar tu análisis. La respuesta correcta es más específica.',
                help: {
                    title: 'Concepto: Manejo de Valores Nulos (NaN)',
                    text: '<p>Los valores nulos (<code>NaN</code>) son un problema. Ignorarlos puede romper tus cálculos.</p><p>Pandas ofrece dos estrategias principales:</p><ol class="list-decimal list-inside ml-4"><li><b>Eliminación:</b> Usar <code>.dropna()</code>. Esto <b>elimina</b> filas (o columnas) que contengan nulos.</li><li><b>Imputación:</b> Usar <code>.fillna()</code>. Esto <b>rellena</b> los huecos con un valor (ej. <code>0</code>, la <code>media</code>, la <code>mediana</code>).</li></ol><p class="mt-2"><b>Palabras Clave:</b> <code>.dropna()</code> (eliminar) y <code>.fillna()</code> (rellenar).</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 5/10: Power BI',
                question: 'En Power BI, ¿cuál es el componente utilizado para realizar transformaciones y limpieza de datos?',
                options: [
                    { text: 'Power Pivot', correct: false },
                    { text: 'Power BI Desktop', correct: false },
                    { text: 'Power View', correct: false },
                    { text: 'Power Query', correct: true }
                ],
                feedback_correct: '¡Eso es! <code>Power Query</code> es la herramienta de <b>ETL</b> (Extracción, <b>Transformación</b> y Carga). Su trabajo es <b>limpiar y transformar</b> los datos <i>antes</i> de que lleguen a los gráficos.',
                feedback_incorrect: 'Casi. Es fácil confundir los "Power". Piensa en "Query" como "consulta" o "transformación".',
                help: {
                    title: 'Concepto: Componentes de Power BI',
                    text: '<p>Power BI Desktop es la herramienta principal, pero dentro tiene varios componentes:</p><ul class="list-disc list-inside ml-4"><li><b><code>Power Query</code>:</b> Es el editor de consultas. Se usa para <b>limpiar y transformar</b> los datos. Es el paso de "ETL".</li><li><b><code>Power Pivot</code>:</b> Es el motor de <b>modelado</b> de datos. Aquí se crean las <b>relaciones</b> y se usa <b>DAX</b>.</li><li><b><code>Power View</code>:</b> Es el lienzo de <b>visualización</b> (los gráficos).</li></ul><p class="mt-2"><b>Palabra Clave:</b> <code>Power Query</code> = <code>Transformación y Limpieza</code>.</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 6/10: Listas vs. Diccionarios',
                question: '¿Cuál es la diferencia entre una lista y un diccionario en Python?',
                options: [
                    { text: 'No hay diferencia, ambos funcionan igual', correct: false },
                    { text: 'Un diccionario almacena pares clave-valor y una lista almacena elementos indexados', correct: true },
                    { text: 'Una lista almacena pares clave-valor y un diccionario almacena solo valores', correct: false },
                    { text: 'Los diccionarios solo pueden almacenar texto', correct: false }
                ],
                feedback_correct: '¡Perfecto! Una <code>lista</code> usa un <b>índice numérico</b> (<code>lista[0]</code>) y un <code>diccionario</code> usa una <b>clave de texto</b> (<code>diccionario[\'nombre\']</code>).',
                feedback_incorrect: 'No, son muy diferentes. Piensa en cómo accedes a los datos.',
                help: {
                    title: 'Concepto: Listas y Diccionarios en Python',
                    text: '<p>Ambos son "contenedores" de datos, pero funcionan diferente:</p><p><b>Lista (<code>[]</code>)</b>: Almacena elementos en <b>orden</b> y se accede por <b>índice numérico</b> (empezando en 0).</p><p><code>mi_lista = ["Manzana", "Pera"]</code><br><code>mi_lista[0]</code> &rarr; "Manzana".</p><p><b>Diccionario (<code>{}</code>)</b>: Almacena datos en pares <b><code>clave:valor</code></b>. Se accede a los valores usando la <b>clave</b>.</p><p><code>mi_dicc = {"fruta": "Manzana"}</code><br><code>mi_dicc["fruta"]</code> &rarr; "Manzana".</p><p class="mt-2"><b>Palabra Clave:</b> <code>Lista</code> = <code>Índice</code>, <code>Diccionario</code> = <code>Clave-Valor</code>.</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 7/10: Tipos de Gráficos',
                question: '¿Qué gráfico es el más adecuado para analizar la relación entre dos variables numéricas?',
                options: [
                    { text: 'Gráfico de dispersión', correct: true },
                    { text: 'Gráfico de barras', correct: false },
                    { text: 'Histograma', correct: false },
                    { text: 'Gráfico de líneas', correct: false }
                ],
                feedback_correct: '¡Correcto! Un <b>gráfico de dispersión</b> (scatter plot) pone una variable numérica en el eje X y la otra en el eje Y para ver si hay una <b>relación</b>.',
                feedback_incorrect: 'No. Esos gráficos son para otros propósitos. Piensa en cómo se verían los ejes.',
                help: {
                    title: 'Concepto: Selección de Gráficos',
                    text: '<ul class="list-disc list-inside ml-4"><li><b><code>Gráfico de dispersión</code>:</b> Es el mejor para ver la <b>relación</b> entre <b>dos variables numéricas</b> (ej. Eje X: "Altura", Eje Y: "Peso").</li><li><b><code>Gráfico de barras</code>:</b> Compara un número (ej. "Ventas") entre <b>categorías</b> (ej. "Ciudades").</li><li><b><code>Histograma</code>:</b> Muestra la <b>distribución</b> de <b>una sola variable numérica</b> (ej. "Edades").</li><li><b><code>Gráfico de líneas</code>:</b> Muestra una variable numérica a lo largo del <b>tiempo</b>.</li></ul><p class="mt-2"><b>Palabra Clave:</b> <code>Dispersión</code> = <code>Relación entre dos variables numéricas</code>.</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 8/10: Correlación',
                question: '¿Qué significa el término "correlación" en análisis de datos?',
                options: [
                    { text: 'La diferencia entre los valores máximos y mínimos de un conjunto de datos', correct: false },
                    { text: 'La relación entre dos variables y cómo cambian juntas', correct: true },
                    { text: 'Un proceso para eliminar datos duplicados', correct: false },
                    { text: 'Un método para convertir texto en números', correct: false }
                ],
                feedback_correct: '¡Exacto! <b>Correlación</b> (co-relación) mide si dos variables <b>cambian juntas</b> (ambas suben, o una sube y la otra baja).',
                feedback_incorrect: 'Nop. "Correlación" viene de "co-relación", es decir, relación mutua.',
                help: {
                    title: 'Concepto: Correlación',
                    text: '<p>La correlación es una medida estadística que describe la <b>relación entre dos variables</b>. Nos dice si, cuando una variable sube, la otra tiende a subir, a bajar o no hace nada.</p><ul class="list-disc list-inside ml-4"><li><b>Positiva:</b> Ambas suben juntas (<code>Altura</code> y <code>Peso</code>).</li><li><b>Negativa:</b> Cuando una sube, la otra baja (<code>Horas de estudio</code> y <code>Errores</code>).</li><li><b>Cero:</b> No hay relación.</li></ul><p class="mt-2"><b>Palabra Clave:</b> <code>Correlación</code> = <code>Cómo cambian juntas</code>.</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 9/10: GroupBy en Pandas',
                question: '¿Cuál es el beneficio de usar groupby() en Pandas?',
                options: [
                    { text: 'Crear un nuevo DataFrame vacío', correct: false },
                    { text: 'Borrar columnas de un DataFrame', correct: false },
                    { text: 'Agrupar datos y calcular estadísticas por categoría', correct: true },
                    { text: 'Ordenar datos en orden alfabético', correct: false }
                ],
                feedback_correct: '¡Correcto! <code>.groupby()</code> es como una tabla dinámica. Te permite <b>agrupar por categoría</b> (ej. "Ciudad") y luego <b>calcular estadísticas</b> (ej. la <code>suma</code> de "Ventas").',
                feedback_incorrect: 'Nop. Para ordenar se usa <code>.sort_values()</code>. Para borrar, <code>.drop()</code>.',
                help: {
                    title: 'Concepto: GroupBy (Agrupar por)',
                    text: '<p>El método <code>.groupby()</code> es uno de los más poderosos de Pandas. Permite un proceso de <b>"Separar-Aplicar-Combinar"</b>.</p><ol class="list-decimal list-inside ml-4"><li><b>Separar:</b> Separa el DataFrame en grupos basado en una <b>categoría</b> (ej. "Ciudad").</li><li><b>Aplicar:</b> Aplica una función a cada grupo (ej. <code>.sum()</code>, <code>.mean()</code>).</li><li><b>Combinar:</b> Devuelve un nuevo DataFrame con los resultados.</li></ol><p class="mt-2"><b>Palabra Clave:</b> <code>.groupby()</code> = <code>Agrupar y calcular por categoría</code>.</p>'
                }
            },
            {
                type: 'question',
                title: 'Pregunta 10/10: Importar CSV',
                question: '¿Cuál es la forma correcta de importar datos desde un archivo CSV en Pandas?',
                options: [
                    { text: 'open("archivo.csv") as df', correct: false },
                    { text: 'pandas.load("archivo.csv")', correct: false },
                    { text: 'import csv from pandas', correct: false },
                    { text: 'pd.read_csv("archivo.csv")', correct: true }
                ],
                feedback_correct: '¡Así es! El alias <code>pd</code> (de <code>import pandas as pd</code>) se usa para llamar a la función <code>.read_csv()</code>.',
                feedback_incorrect: 'Ojo con la sintaxis. La función específica de Pandas es muy clara.',
                help: {
                    title: 'Concepto: Lectura de CSV en Pandas',
                    text: '<p>Para leer un archivo CSV, Pandas tiene una función optimizada: <code>read_csv()</code>.</p><p>La sintaxis estándar es:</p><ol class="list-decimal list-inside ml-4"><li>Importar la librería: <code>import pandas as pd</code></li><li>Usar la función con el alias: <code>df = pd.read_csv("archivo.csv")</code></li></ol><p>La opción (a) <code>open()</code> es de Python básico y no crea un DataFrame. Las otras son sintaxis incorrectas.</p><p class="mt-2"><b>Palabra Clave:</b> <code>pd.read_csv("...")</code>.</p>'
                }
            }
        ];
        // =======================================================================
        // FIN DE LA BASE DE DATOS DE PREGUNTAS
        // =======================================================================


        // --- LÓGICA DEL JUEGO (MODIFICADA LIGERAMENTE PARA SER UN QUIZ) ---

        // Función para actualizar el contador de vidas
        function updateLivesDisplay() {
            livesContainer.innerHTML = '❤️'.repeat(lives) + '🖤'.repeat(3 - lives);
        }

        // Función para mostrar una pantalla y ocultar las demás
        function showScreen(screenId) {
            [welcomeScreen, gameScreen, gameoverScreen, diplomaScreen].forEach(screen => {
                screen.classList.add('hidden');
            });
            document.getElementById(screenId).classList.remove('hidden');
        }

        // Función para mostrar un contenedor dentro de la pantalla de juego
        function showGameContainer(containerId) {
            [conceptContainer, questionContainer, feedbackContainer, codeContainer].forEach(container => {
                container.classList.add('hidden');
            });
            if (containerId) {
                document.getElementById(containerId).classList.remove('hidden');
            }
        }

        // Cargar el paso actual del juego
        function loadStep() {
            if (currentStep >= gameSteps.length) {
                // ¡Juego completado! Mostrar diploma
                diplomaName.textContent = playerName || "Valiente Estudiante";
                showScreen('diploma-screen');
                return;
            }

            const step = gameSteps[currentStep];
            stepTitle.textContent = step.title;

            // Rellenar y mostrar modal de ayuda
            helpModalTitle.textContent = step.help.title;
            helpModalText.innerHTML = step.help.text;

            switch (step.type) {
                case 'concept':
                    // Este tipo no se usa en el nuevo quiz, pero se deja la lógica
                    conceptText.innerHTML = step.text;
                    showGameContainer('concept-container');
                    break;
                
                case 'question':
                    questionText.innerHTML = step.question;
                    answerOptions.innerHTML = ''; // Limpiar opciones anteriores
                    step.options.forEach(option => {
                        const button = document.createElement('button');
                        button.className = 'option-btn';
                        button.innerHTML = option.text;
                        button.onclick = () => handleAnswer(option.correct, event); // Pasar el evento
                        answerOptions.appendChild(button);
                    });
                    showGameContainer('question-container');
                    break;
                
                case 'code':
                     // Este tipo no se usa en el nuevo quiz, pero se deja la lógica
                    codeExplanation.innerHTML = step.code_explanation;
                    codeSnippet.textContent = step.code;
                    outputExplanation.innerHTML = step.output_explanation;
                    clipboardHelper.value = step.code; // Para el botón de copiar
                    showGameContainer('code-container');
                    break;
            }
        }

        // Manejar la respuesta a una pregunta
        function handleAnswer(isCorrect, event) { // Recibir el evento
            // Deshabilitar todos los botones de opción
            const buttons = answerOptions.querySelectorAll('.option-btn');
            buttons.forEach((btn, index) => {
                btn.disabled = true;
                if (gameSteps[currentStep].options[index].correct) {
                    btn.classList.add('correct'); // Mostrar la correcta
                } else if (btn.innerHTML === event.target.innerHTML && !isCorrect) {
                    btn.classList.add('incorrect'); // Mostrar la incorrecta que se eligió
                }
            });

            const step = gameSteps[currentStep];
            if (isCorrect) {
                feedbackText.innerHTML = '<b>¡Correcto!</b> 🎉<br>' + step.feedback_correct;
            } else {
                lives--;
                updateLivesDisplay();
                feedbackText.innerHTML = '<b>¡Incorrecto!</b> 😟<br>' + step.feedback_incorrect;
                if (lives <= 0) {
                    setTimeout(() => showScreen('gameover-screen'), 1500);
                    return;
                }
            }
            showGameContainer('question-container'); // Mantener la pregunta visible
            feedbackContainer.classList.remove('hidden'); // Mostrar el feedback
        }

        // Avanzar al siguiente paso
        function nextStep() {
            currentStep++;
            showGameContainer(null); // Ocultar todo
            feedbackContainer.classList.add('hidden'); // Ocultar feedback
            loadStep();
        }

        // Iniciar el juego
        function startGame() {
            playerName = nameInput.value.trim();
            if (playerName.length === 0) {
                // Forzar un nombre si está vacío, para que no se vea feo
                playerName = "Analista";
            }
            lives = 3;
            currentStep = 0;
            updateLivesDisplay();
            showScreen('game-screen');
            loadStep();
        }

        // Reiniciar el juego
        function restart() {
            showScreen('welcome-screen');
            nameInput.value = playerName; // Mantener el nombre
        }

        // --- Event Listeners ---

        startGameBtn.addEventListener('click', startGame);
        
        // Botón para ir al siguiente paso (desde el feedback)
        nextStepBtn.addEventListener('click', nextStep);

        // Botones para reiniciar el juego
        restartGameBtn.addEventListener('click', restart);
        playAgainBtn.addEventListener('click', restart);

        // --- Event Listeners del Modal de Ayuda ---
        helpButton.addEventListener('click', () => {
            helpModal.classList.remove('hidden');
        });

        helpModalCloseBtn.addEventListener('click', () => {
            helpModal.classList.add('hidden');
        });

        // --- Lógica del botón de Copiar (del juego original) ---
        copyCodeBtn.addEventListener('click', () => {
            clipboardHelper.select();
            try {
                // Usamos execCommand como fallback, ya que navigator.clipboard puede fallar en iframes
                document.execCommand('copy');
                copyCodeBtn.textContent = '¡Copiado!';
            } catch (err) {
                copyCodeBtn.textContent = 'Error al copiar';
            }
            setTimeout(() => { copyCodeBtn.textContent = 'Copiar'; }, 2000);
        });

        // --- Lógica de botones de continuar (del juego original) ---
        conceptContinueBtn.addEventListener('click', nextStep);
        continueBtn.addEventListener('click', nextStep);

        // Cargar estado inicial (mostrar bienvenida)
        showScreen('welcome-screen');
    </script>
</body>
</html>
