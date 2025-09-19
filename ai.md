

LangChain 👉 Es un framework en Python y JavaScript para construir aplicaciones que usan Large Language Models (LLMs). Facilita conectar modelos (como GPT) con fuentes de datos, memoria, herramientas externas (APIs, bases de datos) y cadenas de prompts. Ejemplo: un chatbot que busca info en tu base de datos.

LangGraph 👉 Es una librería basada en LangChain que permite representar flujos de LLMs como grafos. Cada nodo es una acción (ejemplo: llamar a un modelo, ejecutar un paso lógico), y las conexiones controlan el flujo de la conversación o proceso. Sirve para crear agentes multi-paso con más control y menos “magia negra”.

AutoGen 👉 Es de Microsoft. Permite crear agentes colaborativos de IA que se comunican entre sí y con humanos. Ejemplo: un agente “programador” y otro “tester” que trabajan juntos para resolver un problema de software. Muy usado para multi-agent systems.

En simple:

LangChain = caja de herramientas para apps con LLMs.

LangGraph = organizar esas apps como grafos de pasos.

AutoGen = varios agentes que hablan entre sí y cooperan.


## LangChain vs Semantic Kernel

Ambos son frameworks para orquestar LLMs (GPT, Claude, etc.).

Te permiten combinar prompts, memoria, herramientas y datos externos.

Están pensados para crear aplicaciones inteligentes, no solo chatbots.

Se integran con plugins/APIs externas (bases de datos, buscadores, etc.).

Diferencias principales

Origen / Comunidad:

LangChain → Proyecto independiente, con gran comunidad open-source.

Semantic Kernel (SK) → Hecho por Microsoft, pensado para integrarse muy bien con Azure OpenAI, Microsoft 365 y ecosistema .NET.

Lenguajes:

LangChain → Python y JavaScript/TypeScript.

SK → C#, Python y Java (con foco fuerte en .NET).

Diseño:

LangChain → Enfoque de “chains” (cadenas de pasos) y agents.

SK → Enfoque en “skills” y “planners” (planificación automática de tareas).

👉 En pocas palabras:

LangChain es más usado en el mundo Python/JS, rápido para prototipos y startups.

Semantic Kernel es la apuesta de Microsoft para empresas que ya usan Azure/.NET.

¿Querés que te arme una tablita comparativa con ejemplos de casos de uso de cada uno?
