# Mrs.Stikman_Tan_tan
Proyecto final de programación de computadores.
 ### Integrantes del grupo ###
 - Maria Paula Machuca Hortua
 - Aarón Alejandro Suarez Bonilla
 - Diego Alejandro Muñoz Penna
 ### Nombre del grupo Pythonbrokers. ###
 [![logo.jpg](https://i.postimg.cc/HL4kxVwv/logo.jpg)](https://postimg.cc/4Kyg24Fp)
# El codigo del proyecto estaria dividido en diferentes secciones 
## Situación problema
La situación problema consiste en la necesidad de construir una aplicación en Python que emule el juego del ahorcado. El objetivo es desarrollar un programa interactivo que permita a los usuarios jugar el clásico juego del ahorcado en la consola.

La aplicación debe cumplir con las siguientes condiciones:

- Código original: Se requiere que el código de la aplicación sea escrito desde cero, utilizando las habilidades y conocimientos adquiridos en el curso.
- Uso de herramientas vistas en el curso: La aplicación debe hacer uso de las herramientas y técnicas de programación que se han enseñado en el curso de Python.
- Interacción y manejo a través de la consola: La aplicación debe permitir una interacción sencilla y amigable con el usuario a través de la consola. Esto implica que el usuario podrá ingresar letras, seleccionar el nivel de dificultad y recibir retroalimentación sobre su progreso en el juego.
- Base de datos de al menos 1000 palabras: Se requiere una base de datos que contenga una amplia variedad de palabras para que el juego pueda seleccionar una palabra aleatoria en cada partida. La base de datos debe incluir al menos 1000 palabras para asegurar la diversidad y la jugabilidad a largo plazo.
- Dibujo de hangman en integración gráfica: La aplicación debe incluir la representación visual del ahorcado a medida que el jugador comete errores en sus intentos de adivinar la palabra. Para lograr esto, se debe hacer uso de una biblioteca de integración gráfica, como Tkinter o Pygame, para dibujar progresivamente las partes del ahorcado.
### Además de las condiciones mencionadas, se han definido algunos features extra para mejorar la experiencia del juego:
- Cuenta regresiva: La aplicación debe incluir una cuenta regresiva para limitar la cantidad de intentos que el jugador tiene para adivinar la palabra. Esto añade un elemento de desafío y emoción al juego.
- Manejo de puntajes: La aplicación debe llevar un registro de los puntajes obtenidos por los jugadores. Esto permitirá realizar un seguimiento de los logros y rendimientos de los jugadores a lo largo del tiempo.
- Soporte para otros idiomas: La aplicación debe ser capaz de ofrecer el juego del ahorcado en diferentes idiomas, como inglés, francés y alemán. Esto implica la necesidad de traducir las palabras utilizadas en el juego y proporcionar las interacciones con el usuario en el idioma seleccionado.
- Manejo de jugadores: La aplicación debe permitir a los jugadores jugar simultáneamente, incluso en diferentes partidas. Esto implica la gestión de múltiples instancias del juego, cada una con su propio estado y progreso.

## Solución 
En respuesta al problema planteado, hemos abordado la solución a través de un enfoque basado en la investigación y el aprendizaje mediante la revisión de varios videos relevantes. Los videos que hemos consultado y utilizado como recursos para resolver el problema son los siguientes:

- Video 1: "https://youtu.be/ipyIYYhS_7w"
- Video 2: "https://youtu.be/fZpJ6UWaOo8"
- Video 3: "https://youtu.be/fi_iBRPr0aw"
- Video 4: "https://youtu.be/R6DISDFO1c8"
- Video 5: "https://youtu.be/Q0pAPBrJyAY"
- Video 6: "https://www.youtube.com/watch?v=p46_z5XBG14"

Estos videos nos proporcionaron información valiosa y detallada sobre la solución al problema en cuestión. A través de ellos, obtuvimos una explicación clara de los pasos necesarios para abordar el problema y aplicamos ese conocimiento en nuestra solución. Estos recursos audiovisuales nos brindaron una guía paso a paso, consejos prácticos y ejemplos prácticos para lograr la solución deseada.

- Diagrama de flujo de la función principal
[![](https://mermaid.ink/img/pako:eNp1Vctu2zAQ_BVCpxZIgJx9KJDETdLCRZM4zUXKYUOtZSIUqfLhxnH8Vf2E_lh3SdmWY9gXG9LO7OzskF4V0tZYjIqZtn_kHFwQD-PKCPqcl-dz6yTU9kmcnn55v4pGqn9_jeicol8d6HdxUU5RaA0tCBAaxIxrrBG_IwrUqkERDQgqhWdHJRohWKfgKXe4YF5xWY7RdxG98CisjDokqg0INTaqBiGJNprcgVT0FJeJYkwUM2VUaz1DJZhAkFrUKJQJaAI9R5O0LID6P2tkPEO_lpMjAFIDugWJBgyjbXCH8KtBZ9QiKGw7SxxKKtDJN3H96XgHYm5haR25d_Y5U96UE_Yzj-K3jhKOHpEEt3WGHXFagGtiy4RcMzAuW9kL_VbqiI3Nu-ptGi5rZl3LXgsf1EtLspgcP5ITbiO-5_1eTvZ592IAtVooQ5I1snncaOAqm5pe9FwvJb2UDhPFxmgBUjlqz9gFOjVTElIq-AW6JEyL6CPV255owqkEGSJo9cbVA1eWQwUONrEwERcH2_2x8rumScFgx-gDMtpYg-tcb7gvvVT4xueBLAw0-xZCrFT0s98EZVkqqS1bLxxK6xzyUoGynu3aW-eTSOjb1VTx01yhTOPQ0wkVnU2Neh9InFANjZ_XkU6jD4mR-6jaronrLtlEDA3sKOEwQjsra17VLUHvS6-MTVZm_P7OsvLs6YbrMJk00T1xTXmkfplk5B0_qsyUvh7KwRw8xKE0OkLDSbc3zU4xi1Qt3VltHh5l4E0w_688ReesRJIMtAbPG-NARJOOK-yFPqdnTtnhZigj5BuRwD10l4-O0-XhGV2SPrwA-gp6nAwlJY_9Wo8b_2GlB1cqOffARJV5pK_X8hpMH3Zn245vY56zcXRMqeUr1Sy553YyuxftbaszDsobH0xKtSPtRymLk6JFukRUTf8mK76dqyLMscWqGNHPGtxLVVRmTXUQg50ujSxGwUU8KWJXQ8CxAuYqRjPQHtf_AcXQUxg?type=png)](https://mermaid.live/edit#pako:eNp1Vctu2zAQ_BVCpxZIgJx9KJDETdLCRZM4zUXKYUOtZSIUqfLhxnH8Vf2E_lh3SdmWY9gXG9LO7OzskF4V0tZYjIqZtn_kHFwQD-PKCPqcl-dz6yTU9kmcnn55v4pGqn9_jeicol8d6HdxUU5RaA0tCBAaxIxrrBG_IwrUqkERDQgqhWdHJRohWKfgKXe4YF5xWY7RdxG98CisjDokqg0INTaqBiGJNprcgVT0FJeJYkwUM2VUaz1DJZhAkFrUKJQJaAI9R5O0LID6P2tkPEO_lpMjAFIDugWJBgyjbXCH8KtBZ9QiKGw7SxxKKtDJN3H96XgHYm5haR25d_Y5U96UE_Yzj-K3jhKOHpEEt3WGHXFagGtiy4RcMzAuW9kL_VbqiI3Nu-ptGi5rZl3LXgsf1EtLspgcP5ITbiO-5_1eTvZ592IAtVooQ5I1snncaOAqm5pe9FwvJb2UDhPFxmgBUjlqz9gFOjVTElIq-AW6JEyL6CPV255owqkEGSJo9cbVA1eWQwUONrEwERcH2_2x8rumScFgx-gDMtpYg-tcb7gvvVT4xueBLAw0-xZCrFT0s98EZVkqqS1bLxxK6xzyUoGynu3aW-eTSOjb1VTx01yhTOPQ0wkVnU2Neh9InFANjZ_XkU6jD4mR-6jaronrLtlEDA3sKOEwQjsra17VLUHvS6-MTVZm_P7OsvLs6YbrMJk00T1xTXmkfplk5B0_qsyUvh7KwRw8xKE0OkLDSbc3zU4xi1Qt3VltHh5l4E0w_688ReesRJIMtAbPG-NARJOOK-yFPqdnTtnhZigj5BuRwD10l4-O0-XhGV2SPrwA-gp6nAwlJY_9Wo8b_2GlB1cqOffARJV5pK_X8hpMH3Zn245vY56zcXRMqeUr1Sy553YyuxftbaszDsobH0xKtSPtRymLk6JFukRUTf8mK76dqyLMscWqGNHPGtxLVVRmTXUQg50ujSxGwUU8KWJXQ8CxAuYqRjPQHtf_AcXQUxg)
```
import random
import time

a= (int(input("seleccione por favor un idioma:1(Español)\nChose a language: 2.(English)\nsi prega di selezionare una lingua:3(Italian)\nBitte wähle eine Sprache:4(German)\nveuillez sélectionner une langue:5(France)\n nkérjük válasszon nyelvet:6(Hungarian):")))
if a == 1:
    Multiplayer = int(input("seleccione la cantidad de jugadores 1-2:"))
    if Multiplayer == 2:
        b=int(input("Por favor seleccione una dificultad:\n1.facil\n2.medio\n3.dificil" ))
        if b == 1:

            lista = ['Compañerismo', 'Galleta', 'Abrazo', 'Lealtad', 'Enriquecedor', 'Otoño', 'Ambición', 'Brillante', 'Quietud', 'Ciencia', ' Rojo', ' Lápiz', 'Canela', 'Aire', 'Amor', ' Autopista', ' Paciencia', 'Soledad', 'Estrategia', 'Avance', ' Moda', 'Crecimiento', 'Tenacidad', 'Emocionado', ' Literatura', 'Fiesta', ' Esperanza', 'Inspirador', ' Innovación', 'Creatividad', 'Electrizante', 'Embelesamiento', 'Carne', ' Reloj', ' Silencio', 'Rumbo', 'Nieve', 'Reverencia', 'Capacidad', 'Sueño', ' Naranja', 'Maravillarse', 'Cordialidad', 'Cambio', 'Computadora', 'Música', ' Uva', 'Epifanía', 'Correr', 'Agradecimiento', ' Liderazgo', ' Misterio', ' Gafas', 'Comunicación', 'Revelación', 'Aclamado', ' Lágrimas', 'Innovador', 'Susurro', ' Nieve', ' Horizonte', ' Marcador', ' Descubrimiento', 'Estilo', 'Embelesador', ' Deporte', 'Literatura', 'Sanar', 'Serenidad', ' Canino', 'Refrescante', 'Maravilla', 'Oficina', 'Relajación', ' Estilo', 'Vitalidad', 'Conservación', ' Dignidad', 'Redención', ' Natación', ' Descanso', 'Excitante', 'Profesión', ' Avena', ' Logro', 'Aplaudido', 'Tiempo', ' Yogur', ' Océano', 'Cine', 'Pueblo', ' Satisfacción', 'Café', ' Guitarra', 'Agua', ' Tiza', 'Responsabilidad', 'Prestigio', ' Placer', ' Llanto', 'Optimismo', 'Equipo', ' Igualdad', ' Vainilla', ' Baile', ' Autobús', 'Hobby', 'Imaginación', 'Irresistible', 'Resplandor', 'Adaptabilidad', 'Apreciación', ' Bolígrafo', ' Voluntariado', ' Esperanza ', 'Intrigante', 'Iluminador', 'Edificante', 'Impresionismo', ' Martes', ' Arquitectura', 'Progreso', 'Estrellas', ' Comunidad', 'Transcendental', 'Esplendoroso', 'Colina', 'Medio ambiente', ' Refresco', 'Anochecer', ' Inocencia', 'Maíz', ' Coraje', 'Sorprendido', ' Ejercicio', 'Espera', ' Fotografía', 'Realidad', ' Agradable', 'Encantamiento', ' Anochecer', ' Desierto', 'Impresionado', ' Triste', ' Aceite', 'Euforia', ' Pintura', ' Bienestar', ' Aldea', ' Resplandor', 'Reflexión', ' Danza', 'Pluma', 'Dedicación', 'Delicia', ' Risa', 'Enamoramiento', ' Pastel', 'Deporte', 'Reinvención', ' Cacao', ' Gastronomía', 'Simetría', 'Fraternidad', ' Ingeniero', 'Satisfactorio', 'Cacao', 'Aspiración', 'Autenticidad', 'Humildad', 'Intriga', 'Placer', 'Conciencia', 'Exhilarante', 'Abogado', ' Dinero', 'Yogur', 'Unidad', ' Computadora', ' Jugo', ' Fuego', 'Retroceso', 'Fascinación', 'Planeta', ' Felicidad', ' Gato', 'Grandeza', ' Elefante', 'Dulce', ' Conejo', 'Llanura', ' Amargo', ' Agua', ' Libro', ' Invierno', ' Trabajo', 'Atractivo', ' Optimismo', ' Escultura', 'Gastronomía', ' Bello', 'Gafas', ' Fútbol', 'Prodigio', ' Experiencia', 'Inspírate', ' Mar', ' Místico', ' Naturaleza', ' Escribir', ' Fantasía', ' Caminar', ' Alegría', 'Universo', ' Te', 'Expresión', ' Carcajada', 'Espiritualidad', 'Rejuvenecimiento', ' Río', 'Felicidad', 'banana', ' Yoga', 'Emocional', 'Oportunidad', 'Casa', ' Lapiz', 'Paciencia', ' Carretera', 'Gozo', ' Confianza', 'Atracción', 'Soñar', 'Impresionante', ' Cumpleaños', 'Pesadilla', 'Asombro', ' Nubes', 'Maravilloso', 'Equilibrio', ' Colaboración', 'Espacio', ' Empoderamiento', 'Diseño', ' Estudio', 'Emocionalmente', ' Resiliencia', 'Baloncesto', 'Resplandeciente', ' Empatía', 'Interiores', 'Estupor', 'Inolvidable', 'Admiración', ' Hermoso', 'Montaña', 'Realización', ' Ácido', 'Escribir', 'Abrazo', 'Cerámica', ' Saltar', 'Accion', ' Suspiro', 'Enojo', 'Mesa', ' Sombrero', ' Motocicleta', 'Cerveza', ' Zapatos', 'Verdad', 'Apasionantemente', 'Estrella', ' Vacaciones', 'Ritmo', ' Cielo', 'Pasatiempo', ' Colorido', 'Viajes', ' Rocío', 'Prodigioso', ' Psicología', 'Amanecer', ' Gratitud', ' Desafío', ' Nadar', 'Análisis', 'Exquisito', ' Patrimonio', ' Televisión', ' Pantalón', ' Regalo', 'Recompensa', 'Desierto', ' Nobleza', 'Conexión', ' Cuento', 'Escuela', ' Madurez', ' Lluvia', 'Lámpara', 'Espontaneidad', ' Claro', 'Constelación', ' Mouse', 'Cultura', ' Fresco', ' Inspiración', ' Sol Guitarra', 'Libro', ' Diversidad', 'Riesgo', 'naranja', 'Universidad', ' Determinación', ' Festival', ' Amabilidad', ' Brisa', ' Hámster ', 'Autopista', ' Maravilla', 'Abeja', 'Esperanza', ' Conocimiento', ' Colina', ' Hámster', ' Gentil', ' Energía', ' Radiante', ' Medicina', 'Natación', ' Cascada', ' Cariñoso', ' Cálido', 'Amistad', ' Teléfono', 'Conejo', ' Lunes', 'Aire libre', 'Carretera', ' Luminoso', ' Saxofón', 'Ética', ' Tenis', ' Camión', 'Aprendizaje', 'Sinceridad', ' Sostenibilidad', ' Bondad', 'Selva', 'Luminosidad', 'Enfoque', ' Perro', ' Universidad', ' Crianza', 'Descubrimiento', ' Jardín', 'Destreza', 'Tren', ' Iluminación', 'Planificación', ' Arena', 'Tenis', ' Exuberante', 'Superación', ' Verano', 'Ingeniero', ' Bosque', 'Tormenta', 'Trascendencia', 'Divorciado', 'Armonía', 'Empatía', ' Respeto', 'Reloj', ' Amigo', 'Hilo', ' Yogurt', ' Colegio', 'Serendipia', 'Avión', ' Juego', 'Risas', ' Plenitud', 'Escultura', 'Hospital', ' Sonrisa', 'Cautivador', 'Intuición', 'Experiencia', 'Esplendor', 'Océano', 'Prosperidad', 'Consciencia', ' Tequila', 'Aniversario', 'Seducción', 'Liderazgo', 'Sobresaliente', ' Cortés', 'Renovación', ' Valle', 'Mañana', 'Noche', 'Invierno', 'Carisma', 'Evolución', ' Flexibilidad', ' Enérgico', ' Cambio', ' Baloncesto', ' Profesionalismo', 'Inspiração', 'Emocionante', ' Maravilloso', 'Éxito', 'Solidaridad', 'Renacimiento', ' Verdura', ' Vestido', ' Conchas', 'Mar', ' Médico', 'Fe', 'Camiseta', ' Creatividad', 'Amargo', ' Celebración', ' Vitalidad', ' Flores', ' Noche', 'Risueño', 'Gratificación', ' Aventura', ' Pimienta', 'Primavera', 'Estimulante', ' Techo', 'Azúcar', 'Vestido', ' Calma', ' Libertad', ' Tranquilidad', ' Consciencia', ' Aniversario', 'Momentos', ' Feliz', ' Galaxia', ' Autenticidad', ' Meditación', ' Competencia', ' Árbol', 'Nutrición', 'Glorioso', 'Ciencia', 'Elevación', ' Aire', ' Justicia', 'Eficiencia', ' Encanto', 'Fuego', ' Tradición', ' Oasis', 'Sorpresa', 'Enseñanza', 'Júbilo', ' Soñar', 'Desbordante', 'Aventura', 'Televisión', 'Zapatos', ' Chocolate', 'Perro', 'Inspiración', ' Boda', ' Enojo', 'Apasionado', 'Medicina', ' Cepillo', 'Claridad', 'Envolvente', ' Pizza', 'Luna', 'Justicia', 'Empoderamiento', 'Silla', 'Desbordado', ' Viento', 'Riqueza', 'Recuerdos', ' Entusiasmo', ' Tecnología', ' Tienda', 'Galaxia', 'Magia', ' Encantador', ' Pasta', 'Exuberancia', 'Equidad', ' Cine', 'Perseverancia', 'Organización', ' Perseverancia', 'Carrera', 'Estupefacto', 'Sueños', 'Originalidad', 'Extraordinario', ' Trascendental', ' Oficina', ' Llanura', 'Leche', ' Patineta', ' Celular', 'Inteligencia', ' Relajante', ' Sonido', 'Arrebato', ' Atardecer', ' Inspirador', 'Caminar', ' Serenidad', 'Fantasía', 'Emancipador', ' Atento', ' Helado', 'Tarde', 'Lápiz', ' Pertenencia', 'Emprendimiento', 'Integridad', 'Inocencia', 'Harmonía', 'Autoestima', 'Alegría', ' Té', 'Cuaderno', 'Pintura', 'Arroz', 'Enriquecimiento', 'Motivador', 'Inclusión', 'manzana', ' Mindfulness', 'Respeto', ' Exploración', ' Vecino', ' Riqueza', 'Transformación', ' Pintar', ' Gozo', 'Caos', ' Tierra', 'Mariposa', ' Admiración', ' Exótico', 'Sostenibilidad', ' Apasionado', 'Vainilla', 'Fascinador', 'Ácido', 'Tigre', ' Tristeza', 'Visión', 'Relámpago', 'Satélite', ' Sincero', 'Celular', 'Verdura', 'Revigorizante', ' Whisky', 'Teatro', 'Paisaje', 'Sensación', 'Fortaleza', ' Calle', 'Puerta', ' Carne', 'Misterio', ' Teatro', 'Pasta', ' Sábado', 'Compromiso', 'Triunfo', ' Fascinante', 'Valentía', ' Trigo', 'Amabilidad', 'Paz', 'Sustentabilidad', 'Persistencia', ' Ciudad', 'Arquitectura', ' Fiesta', 'Soñador', ' Enfermería', ' Fortaleza', 'Suspiro', ' Tierno', ' Humildad', ' Escalar', ' Manzana', ' Coche', 'Luminoso', ' Soltero', 'Relaciones', 'Alegre', 'Revitalizante', ' Amistoso', 'Emocionadamente', 'Avenida', ' Belleza', ' Amarillo', 'Desafío', ' Cultura', ' Eficiencia', ' Batería', ' Majestuoso', ' Escáner', 'Sal', ' Compañero', ' Familia', 'Vibrante', ' Medio Ambiente', ' Aprendizaje', ' Abogado', 'Entretenimiento', 'Valores', 'Tienda', ' Aceptación', 'Familia', 'Conocimiento', 'Fuerza', 'Espíritu', ' Valiente', 'Revolución', 'Cuidado', ' Explorador', 'Playa', ' Sofá', ' Amistad', 'Autobús', 'Pescado', 'Danza', ' Encantamiento', ' Montaña', 'Bosque', 'Sobrevivencia', 'Incomparable', ' Hospital', ' Jardin', ' Leyenda', ' Avenida', 'Sublimación', ' Ensalada', 'Destino', ' Amable', ' Dulce', 'Eternidad', 'Sombrero', ' Eterno', ' Amoroso', 'Pintar', 'Corazón', 'Constancia', ' Silla', 'Maestro', ' Automóvil', ' Metrópoli', ' Vibrante', 'Té', 'Subyugado', 'Cepillo', ' Harmonía', 'Plenitud', 'Adictivo', ' Violín', ' Meta', 'Pletórico', 'Pensamiento', ' Lámpara', ' Disfrute', 'Ingenio', 'Retos', 'Alucinante', 'Trabajo', ' Playa', ' Refugio', ' Mañana', ' Enojado', ' Honestidad', 'Fantástico', ' Cautivador', ' Sorprendido', ' Transformación', 'Verano', ' Matemáticas', ' Sosiego', ' Moto', ' León', ' Confort', ' Recuerdo', 'Compañía', 'Gota', ' Sueño', 'Conmovedor', 'Desarrollo', 'Sabiduría', ' Casado', 'Casado', ' Amor', 'Moda', ' Arte', ' Heroico', 'Médico', 'Recuerdo', 'Trascendental', 'Autonomía', 'Techo', 'Filosofía', 'Asombroso', 'Sororidad', ' Papel', 'Tolerancia', ' Pared', ' Escuela', 'Escalar', ' Azúcar', 'Igualdad', ' Tarde', 'Refresco', 'Futuro', ' Paraíso', 'Ingeniería', 'Sublime', 'Descanso', 'Mantequilla', ' Romance', 'Mediodía', ' Rayo', ' Generoso', 'Motivación', 'Voluntad', 'Viudo', ' Ingeniería', ' Amanecer', 'Pared', 'Vivacidad', 'Exteriores', ' Independencia', 'Elefante', ' Viudo', ' Mediodía', 'Feliz', 'Maravillar', 'Embriagador', 'Prometedor', ' Educación', ' Sushi', ' Paciente', 'Innovación', 'Agricultura', 'Determinación', ' Trueno', 'Energía', 'Libélula', 'Increíble', 'Solución', 'Rayo', ' Tigre', 'Gato', ' Dedicación', ' Barco', 'Exaltación', 'Enjuague', 'Pasión', ' Ecología', 'Honestidad', ' Emoción', ' Correr', 'Tecnología', 'Revelador', 'Explorar', 'Deslumbramiento', 'Despertar', ' Vino', 'Tristeza', ' Historia', ' Luna', 'Estudio', ' Salud', ' Sabiduría', 'Exorbitante', 'Encantador', ' Leche', 'Metas', 'Bufanda', 'Nadar', 'Arte', 'Valle', 'Río', ' Natura', ' Hamburguesa', 'Historia', 'Bienestar', ' Bendición', 'Diversión', 'Exploración', 'Naturaleza', 'Inquietud', 'Melodía', ' Filantropía', ' Bufanda', 'Vigorizante', 'Cantar', ' Tolerancia', ' Gota', 'Mirada', 'Descubrir', ' Sal', ' Diversión', 'Ciudad', ' Perdón', ' Pueblo', 'Serendipidad', ' Solidaridad', ' Domingo', 'Herencia', 'Fútbol', 'Comunidad', 'Magnífico', ' Arcoíris', ' Estímulo', 'Disciplina', ' Guardería', 'Estupendo', 'Anhelo', ' Entrega', ' Música', 'Provechoso', 'Salud', ' Puerta', ' Negocios', ' Ventana', 'Sensibilidad', ' Tren', ' Estabilidad', ' Jirafa', 'Enigma', ' Valentía', 'Jugo', ' Magia', 'Palabra', ' Único', ' Piano', ' Metrópolis', 'Productividad', 'Regocijo', ' Pintoresco', 'Metrópolis', ' Renovador', 'Estremecimiento', 'Viaje', 'Coraje', 'Estremecedor', ' Cantar', 'Celebración', 'Cooperación', ' Bailar', ' Enjuague', 'Embeleso', 'Religión', ' Idílico', 'Generación', 'Trascendente', ' Pluma', 'Trigo', 'Satisfacción', 'Negocio', ' Reptil', 'Fruta', ' Mesa', ' Organización', ' Estrellas', ' Impresora', 'Meta', ' Motivación', 'Intrepidez', ' Equilibrio', 'Tranquilidad', 'Cumpleaños', ' Divorciado', 'Brillo', 'Colaboración', ' Verde', ' Postre', 'Melancolía', 'Fotografía', 'Risa', 'Aroma', ' Fruta', ' Relajación', 'Rocío', 'Vigor', ' Generosidad', 'Sonrisa', 'Otoño', 'Impulso', 'Encanto', 'Subyugante', ' Salado', ' Lucidez', ' Azul', 'Entusiasmo', 'Belleza', ' Crecimiento', ' Azucar', 'Aceite', 'Arcoíris', ' Viaje', 'Hámster', ' Sorpresa', ' Aventurero', ' Café', 'Sorprendente', 'Curiosidad', ' Hilo', ' Pescado', 'Notable', ' Comprensión', ' Mantequilla', 'Madrugada', 'Estudiante', ' Primavera', ' Lago', ' Terapia', 'Habilidad', 'Gracia', 'Inigualable', 'Propósito', ' Beso', ' Felino', 'Soltero', ' Paz', ' Técnico', 'pera', 'Bailar', 'Colibrí', ' Avión', 'Lago', 'Embriagante', 'Eufórico', 'Apasionante', 'Festividad', ' Sol', 'Pantalón', 'Saltar', 'Barco', ' Cerámica', ' Interdependencia', ' Jugar', 'Elocuencia', 'Estimulado', 'Esencia', 'Salado', 'Confianza', 'Avena', ' Ética', 'Iniciativa', ' Platano', ' Nube', 'Exuberante', ' Escribir ', 'Encuentro', ' Nutrición', 'Deseo', ' Noble', ' Espiritualidad', ' Cooperación', ' Armonía', 'Pimienta', ' Superación', ' Sublime', 'Deslumbrante', 'Tradición', 'Flexibilidad', ' Universo', 'Jirafa', 'Calle', 'Diversidad', ' Actuar', ' Sensible', 'Técnico', 'Compasión', 'Espectacular', ' Arroz', ' Ave', ' Cuaderno', 'Genuino', 'Silencio', ' Queso', ' Camiseta', ' Madrugada', 'Abundancia', 'Compañerismo', 'Desafiante', 'Astonante', 'Impresión', ' Instituto', 'Atardecer', 'Logro', ' Tablet', ' Tormenta', ' Emprendimiento', 'Trueno', 'Excentricidad', 'Aldea', 'Sentimientos', 'Electrizado', 'Fascinante', 'Gratitud', ' Canela', 'Victoria', ' Lealtad', ' Bicicleta', ' Maíz', ' Éxito', 'Emoción', 'Educación', 'Cascada', 'Libertad', ' Odontología', ' Integridad', 'Sofá', 'Investigación', 'Queso', 'Iluminación', 'Generosidad', ' Pasión', 'Tierra', ' Poesía', 'Sacrificio', 'Resiliencia', 'Maravillosamente', 'Enérgico', 'Ventana']


            def Palabra_Aleatoria(lista_palabras):
                """
                Función para escoger una palabra aleatoriamente

                Argumentos:
                parametro1: lista de palabras.
         
                Returns:
                palabra aleatoria pertenciente a la lista
                """ 
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                """
                Función para ocultar la palabra elegida

                Argumentos:
                parametro1: operación para ocultar cada caracter de la palabra
         
                Returns:
                palabra aleatoria pertenciente a la lista oculta
               """ 
            
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                """
                Función que mostrara la palabra oculta

                Argumentos:
                parametro1: palabra oculta
         
                Returns:
                Muestra la palabra que estaba oculta
                """ 
                print("Palabra:", " ".join(palabra_oculta))

            def adivinar_letra():
                """
                Función para adivinar la palabra

                Argumentos:
                parametro1: La letra ingresada por el usuario
                """ 
                return input("Adivina una letra: ")

            def Stickman(intentos):
                """
                Función que forma al muñeco segun los intentos

                Argumentos:
                parametro1: Intentos
        
                Returns:
                Stikman 
        
                """ 
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                """
                Funcion principal para jugar
        
                Returns:
                Juego ahorcado
                """ 
                palabra = Palabra_Aleatoria(lista) # En palabra se almacenara la palara aleatoria
                palabra_oculta = ocultar_palabra(palabra) # En palabra_oculta se almacenara la palabra aleatoria pero oculta
                intentos_totales = 1000 # Definimos la cantidad de intentos en este modo de juego
                intentos_restantes = intentos_totales # En intentos_restantes se almacena los intentos_totales del nivel
                tiempo_inicial= time.time() # Tiempo inicial, se utilizará para el temporizador
                

                while intentos_restantes > 0: # Bucle que permite seguir el programa mientras hallan intentos 
                    mostrar_palabra(palabra_oculta) # Llamamos la función mostra_palabra con el argumento de palabra_oculta
                    Stickman(intentos_restantes) # Llamamos la función del stikman con el argumento de los intentos
                    letra = adivinar_letra() # La variable letra almacena la función adivinar_letra
                    acierto = False # verifica el acierto del usuario
                    nueva_palabra_oculta = "" # Actualiza la palabra

                    if tiempo_inicial is None:  # Verificar si es la primera letra ingresada
                     tiempo_inicial = time.time()  # Asignar tiempo inicial


                    for i in range(len(palabra)): # Ciclo para comprobar que la letra ingresada sea de la palabra
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        tiempo_total = 120  # Establecer aquí el tiempo total en segundos
                        tiempo_transcurrido = time.time() - tiempo_inicial
                        tiempo_restante = tiempo_total - tiempo_transcurrido
                        print("¡Correcto!! Te quedan", int(tiempo_restante), "segundos.")                  

                    else:
                        intentos_restantes -= 1
                        tiempo_total = 120  # Establecer aquí el tiempo total en segundos
                        tiempo_transcurrido = time.time() - tiempo_inicial
                        tiempo_restante = tiempo_total - tiempo_transcurrido
                    
                        print("Incorrecto. Te quedan", intentos_restantes, "intentos y", int(tiempo_restante), "segundos.")                   

                    if palabra_oculta.lower() == palabra.lower(): # Condicion para verficar que la palabra adivinada sea la misma que la palabra oculta
                        print("¡Ganaste! Has adivinado la palabra:", palabra)
                        break
                    
                    if tiempo_restante <= 0:
                     print("¡Perdiste! La palabra era:", palabra)
                     break



            print("Jugador 1:")
            jugar_ahorcado()
            print("Jugador 2:")
            jugar_ahorcado()

            
        elif b == 2:


            lista = [' Compañerismo', ' Galleta', ' Abrazo', 'Lealtad', 'Enriquecedor', ' Otoño', 'Ambición', 'Brillante', 'Quietud', ' Ciencia', ' Rojo', ' Lápiz', 'Canela', 'Aire', 'Amor', ' Autopista', ' Paciencia', 'Soledad', 'Estrategia', 'Avance', ' Moda', 'Crecimiento', 'Tenacidad', 'Emocionado', ' Literatura', 'Fiesta', ' Esperanza', 'Inspirador', ' Innovación', 'Creatividad', 'Electrizante', 'Embelesamiento', 'Carne', ' Reloj', ' Silencio', 'Rumbo', 'Nieve', 'Reverencia', 'Capacidad', 'Sueño', ' Naranja', 'Maravillarse', 'Cordialidad', 'Cambio', 'Computadora', 'Música', ' Uva', 'Epifanía', 'Correr', 'Agradecimiento', ' Liderazgo', ' Misterio', ' Gafas', 'Comunicación', 'Revelación', 'Aclamado', ' Lágrimas', 'Innovador', 'Susurro', ' Nieve', ' Horizonte', ' Marcador', ' Descubrimiento', 'Estilo', 'Embelesador', ' Deporte', 'Literatura', 'Sanar', 'Serenidad', ' Canino', 'Refrescante', 'Maravilla', 'Oficina', 'Relajación', ' Estilo', 'Vitalidad', 'Conservación', ' Dignidad', 'Redención', ' Natación', ' Descanso', 'Excitante', 'Profesión', ' Avena', ' Logro', 'Aplaudido', 'Tiempo', ' Yogur', ' Océano', 'Cine', 'Pueblo', ' Satisfacción', 'Café', ' Guitarra', 'Agua', ' Tiza', 'Responsabilidad', 'Prestigio', ' Placer', ' Llanto', 'Optimismo', 'Equipo', ' Igualdad', ' Vainilla', ' Baile', ' Autobús', 'Hobby', 'Imaginación', 'Irresistible', 'Resplandor', 'Adaptabilidad', 'Apreciación', ' Bolígrafo', ' Voluntariado', ' Esperanza ', 'Intrigante', 'Iluminador', 'Edificante', 'Impresionismo', ' Martes', ' Arquitectura', 'Progreso', 'Estrellas', ' Comunidad', 'Transcendental', 'Esplendoroso', 'Colina', 'Medio ambiente', ' Refresco', 'Anochecer', ' Inocencia', 'Maíz', ' Coraje', 'Sorprendido', ' Ejercicio', 'Espera', ' Fotografía', 'Realidad', ' Agradable', 'Encantamiento', ' Anochecer', ' Desierto', 'Impresionado', ' Triste', ' Aceite', 'Euforia', ' Pintura', ' Bienestar', ' Aldea', ' Resplandor', 'Reflexión', ' Danza', 'Pluma', 'Dedicación', 'Delicia', ' Risa', 'Enamoramiento', ' Pastel', 'Deporte', 'Reinvención', ' Cacao', ' Gastronomía', 'Simetría', 'Fraternidad', ' Ingeniero', 'Satisfactorio', 'Cacao', 'Aspiración', 'Autenticidad', 'Humildad', 'Intriga', 'Placer', 'Conciencia', 'Exhilarante', 'Abogado', ' Dinero', 'Yogur', 'Unidad', ' Computadora', ' Jugo', ' Fuego', 'Retroceso', 'Fascinación', 'Planeta', ' Felicidad', ' Gato', 'Grandeza', ' Elefante', 'Dulce', ' Conejo', 'Llanura', ' Amargo', ' Agua', ' Libro', ' Invierno', ' Trabajo', 'Atractivo', ' Optimismo', ' Escultura', 'Gastronomía', ' Bello', 'Gafas', ' Fútbol', 'Prodigio', ' Experiencia', 'Inspírate', ' Mar', ' Místico', ' Naturaleza', ' Escribir', ' Fantasía', ' Caminar', ' Alegría', 'Universo', ' Te', 'Expresión', ' Carcajada', 'Espiritualidad', 'Rejuvenecimiento', ' Río', 'Felicidad', 'banana', ' Yoga', 'Emocional', 'Oportunidad', 'Casa', ' Lapiz', 'Paciencia', ' Carretera', 'Gozo', ' Confianza', 'Atracción', 'Soñar', 'Impresionante', ' Cumpleaños', 'Pesadilla', 'Asombro', ' Nubes', 'Maravilloso', 'Equilibrio', ' Colaboración', 'Espacio', ' Empoderamiento', 'Diseño', ' Estudio', 'Emocionalmente', ' Resiliencia', 'Baloncesto', 'Resplandeciente', ' Empatía', 'Interiores', 'Estupor', 'Inolvidable', 'Admiración', ' Hermoso', 'Montaña', 'Realización', ' Ácido', 'Escribir', 'Abrazo', 'Cerámica', ' Saltar', 'Accion', ' Suspiro', 'Enojo', 'Mesa', ' Sombrero', ' Motocicleta', 'Cerveza', ' Zapatos', 'Verdad', 'Apasionantemente', 'Estrella', ' Vacaciones', 'Ritmo', ' Cielo', 'Pasatiempo', ' Colorido', 'Viajes', ' Rocío', 'Prodigioso', ' Psicología', 'Amanecer', ' Gratitud', ' Desafío', ' Nadar', 'Análisis', 'Exquisito', ' Patrimonio', ' Televisión', ' Pantalón', ' Regalo', 'Recompensa', 'Desierto', ' Nobleza', 'Conexión', ' Cuento', 'Escuela', ' Madurez', ' Lluvia', 'Lámpara', 'Espontaneidad', ' Claro', 'Constelación', ' Mouse', 'Cultura', ' Fresco', ' Inspiración', ' Sol Guitarra', 'Libro', ' Diversidad', 'Riesgo', 'naranja', 'Universidad', ' Determinación', ' Festival', ' Amabilidad', ' Brisa', ' Hámster ', 'Autopista', ' Maravilla', 'Abeja', 'Esperanza', ' Conocimiento', ' Colina', ' Hámster', ' Gentil', ' Energía', ' Radiante', ' Medicina', 'Natación', ' Cascada', ' Cariñoso', ' Cálido', 'Amistad', ' Teléfono', 'Conejo', ' Lunes', 'Aire libre', 'Carretera', ' Luminoso', ' Saxofón', 'Ética', ' Tenis', ' Camión', 'Aprendizaje', 'Sinceridad', ' Sostenibilidad', ' Bondad', 'Selva', 'Luminosidad', 'Enfoque', ' Perro', ' Universidad', ' Crianza', 'Descubrimiento', ' Jardín', 'Destreza', 'Tren', ' Iluminación', 'Planificación', ' Arena', 'Tenis', ' Exuberante', 'Superación', ' Verano', 'Ingeniero', ' Bosque', 'Tormenta', 'Trascendencia', 'Divorciado', 'Armonía', 'Empatía', ' Respeto', 'Reloj', ' Amigo', 'Hilo', ' Yogurt', ' Colegio', 'Serendipia', 'Avión', ' Juego', 'Risas', ' Plenitud', 'Escultura', 'Hospital', ' Sonrisa', 'Cautivador', 'Intuición', 'Experiencia', 'Esplendor', 'Océano', 'Prosperidad', 'Consciencia', ' Tequila', 'Aniversario', 'Seducción', 'Liderazgo', 'Sobresaliente', ' Cortés', 'Renovación', ' Valle', 'Mañana', 'Noche', 'Invierno', 'Carisma', 'Evolución', ' Flexibilidad', ' Enérgico', ' Cambio', ' Baloncesto', ' Profesionalismo', 'Inspiração', 'Emocionante', ' Maravilloso', 'Éxito', 'Solidaridad', 'Renacimiento', ' Verdura', ' Vestido', ' Conchas', 'Mar', ' Médico', 'Fe', 'Camiseta', ' Creatividad', 'Amargo', ' Celebración', ' Vitalidad', ' Flores', ' Noche', 'Risueño', 'Gratificación', ' Aventura', ' Pimienta', 'Primavera', 'Estimulante', ' Techo', 'Azúcar', 'Vestido', ' Calma', ' Libertad', ' Tranquilidad', ' Consciencia', ' Aniversario', 'Momentos', ' Feliz', ' Galaxia', ' Autenticidad', ' Meditación', ' Competencia', ' Árbol', 'Nutrición', 'Glorioso', 'Ciencia', 'Elevación', ' Aire', ' Justicia', 'Eficiencia', ' Encanto', 'Fuego', ' Tradición', ' Oasis', 'Sorpresa', 'Enseñanza', 'Júbilo', ' Soñar', 'Desbordante', 'Aventura', 'Televisión', 'Zapatos', ' Chocolate', 'Perro', 'Inspiración', ' Boda', ' Enojo', 'Apasionado', 'Medicina', ' Cepillo', 'Claridad', 'Envolvente', ' Pizza', 'Luna', 'Justicia', 'Empoderamiento', 'Silla', 'Desbordado', ' Viento', 'Riqueza', 'Recuerdos', ' Entusiasmo', ' Tecnología', ' Tienda', 'Galaxia', 'Magia', ' Encantador', ' Pasta', 'Exuberancia', 'Equidad', ' Cine', 'Perseverancia', 'Organización', ' Perseverancia', 'Carrera', 'Estupefacto', 'Sueños', 'Originalidad', 'Extraordinario', ' Trascendental', ' Oficina', ' Llanura', 'Leche', ' Patineta', ' Celular', 'Inteligencia', ' Relajante', ' Sonido', 'Arrebato', ' Atardecer', ' Inspirador', 'Caminar', ' Serenidad', 'Fantasía', 'Emancipador', ' Atento', ' Helado', 'Tarde', 'Lápiz', ' Pertenencia', 'Emprendimiento', 'Integridad', 'Inocencia', 'Harmonía', 'Autoestima', 'Alegría', ' Té', 'Cuaderno', 'Pintura', 'Arroz', 'Enriquecimiento', 'Motivador', 'Inclusión', 'manzana', ' Mindfulness', 'Respeto', ' Exploración', ' Vecino', ' Riqueza', 'Transformación', ' Pintar', ' Gozo', 'Caos', ' Tierra', 'Mariposa', ' Admiración', ' Exótico', 'Sostenibilidad', ' Apasionado', 'Vainilla', 'Fascinador', 'Ácido', 'Tigre', ' Tristeza', 'Visión', 'Relámpago', 'Satélite', ' Sincero', 'Celular', 'Verdura', 'Revigorizante', ' Whisky', 'Teatro', 'Paisaje', 'Sensación', 'Fortaleza', ' Calle', 'Puerta', ' Carne', 'Misterio', ' Teatro', 'Pasta', ' Sábado', 'Compromiso', 'Triunfo', ' Fascinante', 'Valentía', ' Trigo', 'Amabilidad', 'Paz', 'Sustentabilidad', 'Persistencia', ' Ciudad', 'Arquitectura', ' Fiesta', 'Soñador', ' Enfermería', ' Fortaleza', 'Suspiro', ' Tierno', ' Humildad', ' Escalar', ' Manzana', ' Coche', 'Luminoso', ' Soltero', 'Relaciones', 'Alegre', 'Revitalizante', ' Amistoso', 'Emocionadamente', 'Avenida', ' Belleza', ' Amarillo', 'Desafío', ' Cultura', ' Eficiencia', ' Batería', ' Majestuoso', ' Escáner', 'Sal', ' Compañero', ' Familia', 'Vibrante', ' Medio Ambiente', ' Aprendizaje', ' Abogado', 'Entretenimiento', 'Valores', 'Tienda', ' Aceptación', 'Familia', 'Conocimiento', 'Fuerza', 'Espíritu', ' Valiente', 'Revolución', 'Cuidado', ' Explorador', 'Playa', ' Sofá', ' Amistad', 'Autobús', 'Pescado', 'Danza', ' Encantamiento', ' Montaña', 'Bosque', 'Sobrevivencia', 'Incomparable', ' Hospital', ' Jardin', ' Leyenda', ' Avenida', 'Sublimación', ' Ensalada', 'Destino', ' Amable', ' Dulce', 'Eternidad', 'Sombrero', ' Eterno', ' Amoroso', 'Pintar', 'Corazón', 'Constancia', ' Silla', 'Maestro', ' Automóvil', ' Metrópoli', ' Vibrante', 'Té', 'Subyugado', 'Cepillo', ' Harmonía', 'Plenitud', 'Adictivo', ' Violín', ' Meta', 'Pletórico', 'Pensamiento', ' Lámpara', ' Disfrute', 'Ingenio', 'Retos', 'Alucinante', 'Trabajo', ' Playa', ' Refugio', ' Mañana', ' Enojado', ' Honestidad', 'Fantástico', ' Cautivador', ' Sorprendido', ' Transformación', 'Verano', ' Matemáticas', ' Sosiego', ' Moto', ' León', ' Confort', ' Recuerdo', 'Compañía', 'Gota', ' Sueño', 'Conmovedor', 'Desarrollo', 'Sabiduría', ' Casado', 'Casado', ' Amor', 'Moda', ' Arte', ' Heroico', 'Médico', 'Recuerdo', 'Trascendental', 'Autonomía', 'Techo', 'Filosofía', 'Asombroso', 'Sororidad', ' Papel', 'Tolerancia', ' Pared', ' Escuela', 'Escalar', ' Azúcar', 'Igualdad', ' Tarde', 'Refresco', 'Futuro', ' Paraíso', 'Ingeniería', 'Sublime', 'Descanso', 'Mantequilla', ' Romance', 'Mediodía', ' Rayo', ' Generoso', 'Motivación', 'Voluntad', 'Viudo', ' Ingeniería', ' Amanecer', 'Pared', 'Vivacidad', 'Exteriores', ' Independencia', 'Elefante', ' Viudo', ' Mediodía', 'Feliz', 'Maravillar', 'Embriagador', 'Prometedor', ' Educación', ' Sushi', ' Paciente', 'Innovación', 'Agricultura', 'Determinación', ' Trueno', 'Energía', 'Libélula', 'Increíble', 'Solución', 'Rayo', ' Tigre', 'Gato', ' Dedicación', ' Barco', 'Exaltación', 'Enjuague', 'Pasión', ' Ecología', 'Honestidad', ' Emoción', ' Correr', 'Tecnología', 'Revelador', 'Explorar', 'Deslumbramiento', 'Despertar', ' Vino', 'Tristeza', ' Historia', ' Luna', 'Estudio', ' Salud', ' Sabiduría', 'Exorbitante', 'Encantador', ' Leche', 'Metas', 'Bufanda', 'Nadar', 'Arte', 'Valle', 'Río', ' Natura', ' Hamburguesa', 'Historia', 'Bienestar', ' Bendición', 'Diversión', 'Exploración', 'Naturaleza', 'Inquietud', 'Melodía', ' Filantropía', ' Bufanda', 'Vigorizante', 'Cantar', ' Tolerancia', ' Gota', 'Mirada', 'Descubrir', ' Sal', ' Diversión', 'Ciudad', ' Perdón', ' Pueblo', 'Serendipidad', ' Solidaridad', ' Domingo', 'Herencia', 'Fútbol', 'Comunidad', 'Magnífico', ' Arcoíris', ' Estímulo', 'Disciplina', ' Guardería', 'Estupendo', 'Anhelo', ' Entrega', ' Música', 'Provechoso', 'Salud', ' Puerta', ' Negocios', ' Ventana', 'Sensibilidad', ' Tren', ' Estabilidad', ' Jirafa', 'Enigma', ' Valentía', 'Jugo', ' Magia', 'Palabra', ' Único', ' Piano', ' Metrópolis', 'Productividad', 'Regocijo', ' Pintoresco', 'Metrópolis', ' Renovador', 'Estremecimiento', 'Viaje', 'Coraje', 'Estremecedor', ' Cantar', 'Celebración', 'Cooperación', ' Bailar', ' Enjuague', 'Embeleso', 'Religión', ' Idílico', 'Generación', 'Trascendente', ' Pluma', 'Trigo', 'Satisfacción', 'Negocio', ' Reptil', 'Fruta', ' Mesa', ' Organización', ' Estrellas', ' Impresora', 'Meta', ' Motivación', 'Intrepidez', ' Equilibrio', 'Tranquilidad', 'Cumpleaños', ' Divorciado', 'Brillo', 'Colaboración', ' Verde', ' Postre', 'Melancolía', 'Fotografía', 'Risa', 'Aroma', ' Fruta', ' Relajación', 'Rocío', 'Vigor', ' Generosidad', 'Sonrisa', 'Otoño', 'Impulso', 'Encanto', 'Subyugante', ' Salado', ' Lucidez', ' Azul', 'Entusiasmo', 'Belleza', ' Crecimiento', ' Azucar', 'Aceite', 'Arcoíris', ' Viaje', 'Hámster', ' Sorpresa', ' Aventurero', ' Café', 'Sorprendente', 'Curiosidad', ' Hilo', ' Pescado', 'Notable', ' Comprensión', ' Mantequilla', 'Madrugada', 'Estudiante', ' Primavera', ' Lago', ' Terapia', 'Habilidad', 'Gracia', 'Inigualable', 'Propósito', ' Beso', ' Felino', 'Soltero', ' Paz', ' Técnico', 'pera', 'Bailar', 'Colibrí', ' Avión', 'Lago', 'Embriagante', 'Eufórico', 'Apasionante', 'Festividad', ' Sol', 'Pantalón', 'Saltar', 'Barco', ' Cerámica', ' Interdependencia', ' Jugar', 'Elocuencia', 'Estimulado', 'Esencia', 'Salado', 'Confianza', 'Avena', ' Ética', 'Iniciativa', ' Platano', ' Nube', 'Exuberante', ' Escribir ', 'Encuentro', ' Nutrición', 'Deseo', ' Noble', ' Espiritualidad', ' Cooperación', ' Armonía', 'Pimienta', ' Superación', ' Sublime', 'Deslumbrante', 'Tradición', 'Flexibilidad', ' Universo', 'Jirafa', 'Calle', 'Diversidad', ' Actuar', ' Sensible', 'Técnico', 'Compasión', 'Espectacular', ' Arroz', ' Ave', ' Cuaderno', 'Genuino', 'Silencio', ' Queso', ' Camiseta', ' Madrugada', 'Abundancia', 'Compañerismo', 'Desafiante', 'Astonante', 'Impresión', ' Instituto', 'Atardecer', 'Logro', ' Tablet', ' Tormenta', ' Emprendimiento', 'Trueno', 'Excentricidad', 'Aldea', 'Sentimientos', 'Electrizado', 'Fascinante', 'Gratitud', ' Canela', 'Victoria', ' Lealtad', ' Bicicleta', ' Maíz', ' Éxito', 'Emoción', 'Educación', 'Cascada', 'Libertad', ' Odontología', ' Integridad', 'Sofá', 'Investigación', 'Queso', 'Iluminación', 'Generosidad', ' Pasión', 'Tierra', ' Poesía', 'Sacrificio', 'Resiliencia', 'Maravillosamente', 'Enérgico', 'Ventana']

            def Palabra_Aleatoria(lista_palabras):
                """
                Función para escoger una palabra aleatoriamente

                Argumentos:
                parametro1: lista de palabras.
         
                Returns:
                palabra aleatoria pertenciente a la lista
                """    
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                """
                Función para ocultar la palabra elegida

                Argumentos:
                parametro1: operación para ocultar cada caracter de la palabra
         
                Returns:
                palabra aleatoria pertenciente a la lista oculta
               """ 
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                """
                Función que mostrara la palabra oculta

                Argumentos:
                parametro1: palabra oculta
         
                Returns:
                Muestra la palabra que estaba oculta
                """
                print("Palabra:", " ".join(palabra_oculta))

            def adivinar_letra():
                """
                Función para adivinar la palabra

                Argumentos:
                parametro1: La letra ingresada por el usuario
                """ 
                return input("Adivina una letra: ")

            def Stickman(intentos):
                """
                Función que forma al muñeco segun los intentos

                Argumentos:
                parametro1: Intentos
        
                Returns:
                Stikman 
        
                """ 
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                """
                Funcion principal para jugar
        
                Returns:
                Juego ahorcado
                """ 
                palabra = Palabra_Aleatoria(lista)# En palabra se almacenara la palara aleatoria
                palabra_oculta = ocultar_palabra(palabra) # En palabra_oculta se almacenara la palabra aleatoria pero oculta
                intentos_totales = 10 # Definimos la cantidad de intentos en este modo de juego
                intentos_restantes = intentos_totales # En intentos_restantes se almacena los intentos_totales del nivel
                tiempo_inicial = time.time()# Tiempo inicial, se utilizará para el temporizador


                while intentos_restantes > 0: #bucle que permite seguir el programa mientras hallan intentos 
                    mostrar_palabra(palabra_oculta) # Llamamos la función mostra_palabra con el argumento de palabra_oculta
                    Stickman(intentos_restantes) # Llamamos la función del stikman con el argumento de los intentos
                    letra = adivinar_letra() # La variable letra almacena la función adivinar_letra
                    acierto = False # verifica el acierto del usuario
                    nueva_palabra_oculta = "" # Actualiza la palabra

                    for i in range(len(palabra)): # Ciclo para comprobar que la letra ingresada sea de la palabra
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        tiempo_total = 60  # Establecer aquí el tiempo total en segundos
                        tiempo_transcurrido = time.time() - tiempo_inicial
                        tiempo_restante = tiempo_total - tiempo_transcurrido
                        print("¡Correcto!! Te quedan", int(tiempo_restante), "segundos.")                  

                    else:
                        intentos_restantes -= 1
                        tiempo_total = 60  # Establecer aquí el tiempo total en segundos
                        tiempo_transcurrido = time.time() - tiempo_inicial
                        tiempo_restante = tiempo_total - tiempo_transcurrido
                    
                        print("Incorrecto. Te quedan", intentos_restantes, "intentos y", int(tiempo_restante), "segundos.")                   

                    if palabra_oculta.lower() == palabra.lower(): # Condicion para verficar que la palabra adivinada sea la misma que la palabra oculta
                        print("¡Ganaste! Has adivinado la palabra:", palabra)
                        break
                    
                    if tiempo_restante <= 0:
                     print("¡Perdiste! La palabra era:", palabra)
                     break



            print("Jugador 1:")
            jugar_ahorcado()
            print("Jugador 2:")
            jugar_ahorcado()


        elif b == 3:

            import random
            lista = [' Compañerismo', ' Galleta', ' Abrazo', 'Lealtad', 'Enriquecedor', ' Otoño', 'Ambición', 'Brillante', 'Quietud', ' Ciencia', ' Rojo', ' Lápiz', 'Canela', 'Aire', 'Amor', ' Autopista', ' Paciencia', 'Soledad', 'Estrategia', 'Avance', ' Moda', 'Crecimiento', 'Tenacidad', 'Emocionado', ' Literatura', 'Fiesta', ' Esperanza', 'Inspirador', ' Innovación', 'Creatividad', 'Electrizante', 'Embelesamiento', 'Carne', ' Reloj', ' Silencio', 'Rumbo', 'Nieve', 'Reverencia', 'Capacidad', 'Sueño', ' Naranja', 'Maravillarse', 'Cordialidad', 'Cambio', 'Computadora', 'Música', ' Uva', 'Epifanía', 'Correr', 'Agradecimiento', ' Liderazgo', ' Misterio', ' Gafas', 'Comunicación', 'Revelación', 'Aclamado', ' Lágrimas', 'Innovador', 'Susurro', ' Nieve', ' Horizonte', ' Marcador', ' Descubrimiento', 'Estilo', 'Embelesador', ' Deporte', 'Literatura', 'Sanar', 'Serenidad', ' Canino', 'Refrescante', 'Maravilla', 'Oficina', 'Relajación', ' Estilo', 'Vitalidad', 'Conservación', ' Dignidad', 'Redención', ' Natación', ' Descanso', 'Excitante', 'Profesión', ' Avena', ' Logro', 'Aplaudido', 'Tiempo', ' Yogur', ' Océano', 'Cine', 'Pueblo', ' Satisfacción', 'Café', ' Guitarra', 'Agua', ' Tiza', 'Responsabilidad', 'Prestigio', ' Placer', ' Llanto', 'Optimismo', 'Equipo', ' Igualdad', ' Vainilla', ' Baile', ' Autobús', 'Hobby', 'Imaginación', 'Irresistible', 'Resplandor', 'Adaptabilidad', 'Apreciación', ' Bolígrafo', ' Voluntariado', ' Esperanza ', 'Intrigante', 'Iluminador', 'Edificante', 'Impresionismo', ' Martes', ' Arquitectura', 'Progreso', 'Estrellas', ' Comunidad', 'Transcendental', 'Esplendoroso', 'Colina', 'Medio ambiente', ' Refresco', 'Anochecer', ' Inocencia', 'Maíz', ' Coraje', 'Sorprendido', ' Ejercicio', 'Espera', ' Fotografía', 'Realidad', ' Agradable', 'Encantamiento', ' Anochecer', ' Desierto', 'Impresionado', ' Triste', ' Aceite', 'Euforia', ' Pintura', ' Bienestar', ' Aldea', ' Resplandor', 'Reflexión', ' Danza', 'Pluma', 'Dedicación', 'Delicia', ' Risa', 'Enamoramiento', ' Pastel', 'Deporte', 'Reinvención', ' Cacao', ' Gastronomía', 'Simetría', 'Fraternidad', ' Ingeniero', 'Satisfactorio', 'Cacao', 'Aspiración', 'Autenticidad', 'Humildad', 'Intriga', 'Placer', 'Conciencia', 'Exhilarante', 'Abogado', ' Dinero', 'Yogur', 'Unidad', ' Computadora', ' Jugo', ' Fuego', 'Retroceso', 'Fascinación', 'Planeta', ' Felicidad', ' Gato', 'Grandeza', ' Elefante', 'Dulce', ' Conejo', 'Llanura', ' Amargo', ' Agua', ' Libro', ' Invierno', ' Trabajo', 'Atractivo', ' Optimismo', ' Escultura', 'Gastronomía', ' Bello', 'Gafas', ' Fútbol', 'Prodigio', ' Experiencia', 'Inspírate', ' Mar', ' Místico', ' Naturaleza', ' Escribir', ' Fantasía', ' Caminar', ' Alegría', 'Universo', ' Te', 'Expresión', ' Carcajada', 'Espiritualidad', 'Rejuvenecimiento', ' Río', 'Felicidad', 'banana', ' Yoga', 'Emocional', 'Oportunidad', 'Casa', ' Lapiz', 'Paciencia', ' Carretera', 'Gozo', ' Confianza', 'Atracción', 'Soñar', 'Impresionante', ' Cumpleaños', 'Pesadilla', 'Asombro', ' Nubes', 'Maravilloso', 'Equilibrio', ' Colaboración', 'Espacio', ' Empoderamiento', 'Diseño', ' Estudio', 'Emocionalmente', ' Resiliencia', 'Baloncesto', 'Resplandeciente', ' Empatía', 'Interiores', 'Estupor', 'Inolvidable', 'Admiración', ' Hermoso', 'Montaña', 'Realización', ' Ácido', 'Escribir', 'Abrazo', 'Cerámica', ' Saltar', 'Accion', ' Suspiro', 'Enojo', 'Mesa', ' Sombrero', ' Motocicleta', 'Cerveza', ' Zapatos', 'Verdad', 'Apasionantemente', 'Estrella', ' Vacaciones', 'Ritmo', ' Cielo', 'Pasatiempo', ' Colorido', 'Viajes', ' Rocío', 'Prodigioso', ' Psicología', 'Amanecer', ' Gratitud', ' Desafío', ' Nadar', 'Análisis', 'Exquisito', ' Patrimonio', ' Televisión', ' Pantalón', ' Regalo', 'Recompensa', 'Desierto', ' Nobleza', 'Conexión', ' Cuento', 'Escuela', ' Madurez', ' Lluvia', 'Lámpara', 'Espontaneidad', ' Claro', 'Constelación', ' Mouse', 'Cultura', ' Fresco', ' Inspiración', ' Sol Guitarra', 'Libro', ' Diversidad', 'Riesgo', 'naranja', 'Universidad', ' Determinación', ' Festival', ' Amabilidad', ' Brisa', ' Hámster ', 'Autopista', ' Maravilla', 'Abeja', 'Esperanza', ' Conocimiento', ' Colina', ' Hámster', ' Gentil', ' Energía', ' Radiante', ' Medicina', 'Natación', ' Cascada', ' Cariñoso', ' Cálido', 'Amistad', ' Teléfono', 'Conejo', ' Lunes', 'Aire libre', 'Carretera', ' Luminoso', ' Saxofón', 'Ética', ' Tenis', ' Camión', 'Aprendizaje', 'Sinceridad', ' Sostenibilidad', ' Bondad', 'Selva', 'Luminosidad', 'Enfoque', ' Perro', ' Universidad', ' Crianza', 'Descubrimiento', ' Jardín', 'Destreza', 'Tren', ' Iluminación', 'Planificación', ' Arena', 'Tenis', ' Exuberante', 'Superación', ' Verano', 'Ingeniero', ' Bosque', 'Tormenta', 'Trascendencia', 'Divorciado', 'Armonía', 'Empatía', ' Respeto', 'Reloj', ' Amigo', 'Hilo', ' Yogurt', ' Colegio', 'Serendipia', 'Avión', ' Juego', 'Risas', ' Plenitud', 'Escultura', 'Hospital', ' Sonrisa', 'Cautivador', 'Intuición', 'Experiencia', 'Esplendor', 'Océano', 'Prosperidad', 'Consciencia', ' Tequila', 'Aniversario', 'Seducción', 'Liderazgo', 'Sobresaliente', ' Cortés', 'Renovación', ' Valle', 'Mañana', 'Noche', 'Invierno', 'Carisma', 'Evolución', ' Flexibilidad', ' Enérgico', ' Cambio', ' Baloncesto', ' Profesionalismo', 'Inspiração', 'Emocionante', ' Maravilloso', 'Éxito', 'Solidaridad', 'Renacimiento', ' Verdura', ' Vestido', ' Conchas', 'Mar', ' Médico', 'Fe', 'Camiseta', ' Creatividad', 'Amargo', ' Celebración', ' Vitalidad', ' Flores', ' Noche', 'Risueño', 'Gratificación', ' Aventura', ' Pimienta', 'Primavera', 'Estimulante', ' Techo', 'Azúcar', 'Vestido', ' Calma', ' Libertad', ' Tranquilidad', ' Consciencia', ' Aniversario', 'Momentos', ' Feliz', ' Galaxia', ' Autenticidad', ' Meditación', ' Competencia', ' Árbol', 'Nutrición', 'Glorioso', 'Ciencia', 'Elevación', ' Aire', ' Justicia', 'Eficiencia', ' Encanto', 'Fuego', ' Tradición', ' Oasis', 'Sorpresa', 'Enseñanza', 'Júbilo', ' Soñar', 'Desbordante', 'Aventura', 'Televisión', 'Zapatos', ' Chocolate', 'Perro', 'Inspiración', ' Boda', ' Enojo', 'Apasionado', 'Medicina', ' Cepillo', 'Claridad', 'Envolvente', ' Pizza', 'Luna', 'Justicia', 'Empoderamiento', 'Silla', 'Desbordado', ' Viento', 'Riqueza', 'Recuerdos', ' Entusiasmo', ' Tecnología', ' Tienda', 'Galaxia', 'Magia', ' Encantador', ' Pasta', 'Exuberancia', 'Equidad', ' Cine', 'Perseverancia', 'Organización', ' Perseverancia', 'Carrera', 'Estupefacto', 'Sueños', 'Originalidad', 'Extraordinario', ' Trascendental', ' Oficina', ' Llanura', 'Leche', ' Patineta', ' Celular', 'Inteligencia', ' Relajante', ' Sonido', 'Arrebato', ' Atardecer', ' Inspirador', 'Caminar', ' Serenidad', 'Fantasía', 'Emancipador', ' Atento', ' Helado', 'Tarde', 'Lápiz', ' Pertenencia', 'Emprendimiento', 'Integridad', 'Inocencia', 'Harmonía', 'Autoestima', 'Alegría', ' Té', 'Cuaderno', 'Pintura', 'Arroz', 'Enriquecimiento', 'Motivador', 'Inclusión', 'manzana', ' Mindfulness', 'Respeto', ' Exploración', ' Vecino', ' Riqueza', 'Transformación', ' Pintar', ' Gozo', 'Caos', ' Tierra', 'Mariposa', ' Admiración', ' Exótico', 'Sostenibilidad', ' Apasionado', 'Vainilla', 'Fascinador', 'Ácido', 'Tigre', ' Tristeza', 'Visión', 'Relámpago', 'Satélite', ' Sincero', 'Celular', 'Verdura', 'Revigorizante', ' Whisky', 'Teatro', 'Paisaje', 'Sensación', 'Fortaleza', ' Calle', 'Puerta', ' Carne', 'Misterio', ' Teatro', 'Pasta', ' Sábado', 'Compromiso', 'Triunfo', ' Fascinante', 'Valentía', ' Trigo', 'Amabilidad', 'Paz', 'Sustentabilidad', 'Persistencia', ' Ciudad', 'Arquitectura', ' Fiesta', 'Soñador', ' Enfermería', ' Fortaleza', 'Suspiro', ' Tierno', ' Humildad', ' Escalar', ' Manzana', ' Coche', 'Luminoso', ' Soltero', 'Relaciones', 'Alegre', 'Revitalizante', ' Amistoso', 'Emocionadamente', 'Avenida', ' Belleza', ' Amarillo', 'Desafío', ' Cultura', ' Eficiencia', ' Batería', ' Majestuoso', ' Escáner', 'Sal', ' Compañero', ' Familia', 'Vibrante', ' Medio Ambiente', ' Aprendizaje', ' Abogado', 'Entretenimiento', 'Valores', 'Tienda', ' Aceptación', 'Familia', 'Conocimiento', 'Fuerza', 'Espíritu', ' Valiente', 'Revolución', 'Cuidado', ' Explorador', 'Playa', ' Sofá', ' Amistad', 'Autobús', 'Pescado', 'Danza', ' Encantamiento', ' Montaña', 'Bosque', 'Sobrevivencia', 'Incomparable', ' Hospital', ' Jardin', ' Leyenda', ' Avenida', 'Sublimación', ' Ensalada', 'Destino', ' Amable', ' Dulce', 'Eternidad', 'Sombrero', ' Eterno', ' Amoroso', 'Pintar', 'Corazón', 'Constancia', ' Silla', 'Maestro', ' Automóvil', ' Metrópoli', ' Vibrante', 'Té', 'Subyugado', 'Cepillo', ' Harmonía', 'Plenitud', 'Adictivo', ' Violín', ' Meta', 'Pletórico', 'Pensamiento', ' Lámpara', ' Disfrute', 'Ingenio', 'Retos', 'Alucinante', 'Trabajo', ' Playa', ' Refugio', ' Mañana', ' Enojado', ' Honestidad', 'Fantástico', ' Cautivador', ' Sorprendido', ' Transformación', 'Verano', ' Matemáticas', ' Sosiego', ' Moto', ' León', ' Confort', ' Recuerdo', 'Compañía', 'Gota', ' Sueño', 'Conmovedor', 'Desarrollo', 'Sabiduría', ' Casado', 'Casado', ' Amor', 'Moda', ' Arte', ' Heroico', 'Médico', 'Recuerdo', 'Trascendental', 'Autonomía', 'Techo', 'Filosofía', 'Asombroso', 'Sororidad', ' Papel', 'Tolerancia', ' Pared', ' Escuela', 'Escalar', ' Azúcar', 'Igualdad', ' Tarde', 'Refresco', 'Futuro', ' Paraíso', 'Ingeniería', 'Sublime', 'Descanso', 'Mantequilla', ' Romance', 'Mediodía', ' Rayo', ' Generoso', 'Motivación', 'Voluntad', 'Viudo', ' Ingeniería', ' Amanecer', 'Pared', 'Vivacidad', 'Exteriores', ' Independencia', 'Elefante', ' Viudo', ' Mediodía', 'Feliz', 'Maravillar', 'Embriagador', 'Prometedor', ' Educación', ' Sushi', ' Paciente', 'Innovación', 'Agricultura', 'Determinación', ' Trueno', 'Energía', 'Libélula', 'Increíble', 'Solución', 'Rayo', ' Tigre', 'Gato', ' Dedicación', ' Barco', 'Exaltación', 'Enjuague', 'Pasión', ' Ecología', 'Honestidad', ' Emoción', ' Correr', 'Tecnología', 'Revelador', 'Explorar', 'Deslumbramiento', 'Despertar', ' Vino', 'Tristeza', ' Historia', ' Luna', 'Estudio', ' Salud', ' Sabiduría', 'Exorbitante', 'Encantador', ' Leche', 'Metas', 'Bufanda', 'Nadar', 'Arte', 'Valle', 'Río', ' Natura', ' Hamburguesa', 'Historia', 'Bienestar', ' Bendición', 'Diversión', 'Exploración', 'Naturaleza', 'Inquietud', 'Melodía', ' Filantropía', ' Bufanda', 'Vigorizante', 'Cantar', ' Tolerancia', ' Gota', 'Mirada', 'Descubrir', ' Sal', ' Diversión', 'Ciudad', ' Perdón', ' Pueblo', 'Serendipidad', ' Solidaridad', ' Domingo', 'Herencia', 'Fútbol', 'Comunidad', 'Magnífico', ' Arcoíris', ' Estímulo', 'Disciplina', ' Guardería', 'Estupendo', 'Anhelo', ' Entrega', ' Música', 'Provechoso', 'Salud', ' Puerta', ' Negocios', ' Ventana', 'Sensibilidad', ' Tren', ' Estabilidad', ' Jirafa', 'Enigma', ' Valentía', 'Jugo', ' Magia', 'Palabra', ' Único', ' Piano', ' Metrópolis', 'Productividad', 'Regocijo', ' Pintoresco', 'Metrópolis', ' Renovador', 'Estremecimiento', 'Viaje', 'Coraje', 'Estremecedor', ' Cantar', 'Celebración', 'Cooperación', ' Bailar', ' Enjuague', 'Embeleso', 'Religión', ' Idílico', 'Generación', 'Trascendente', ' Pluma', 'Trigo', 'Satisfacción', 'Negocio', ' Reptil', 'Fruta', ' Mesa', ' Organización', ' Estrellas', ' Impresora', 'Meta', ' Motivación', 'Intrepidez', ' Equilibrio', 'Tranquilidad', 'Cumpleaños', ' Divorciado', 'Brillo', 'Colaboración', ' Verde', ' Postre', 'Melancolía', 'Fotografía', 'Risa', 'Aroma', ' Fruta', ' Relajación', 'Rocío', 'Vigor', ' Generosidad', 'Sonrisa', 'Otoño', 'Impulso', 'Encanto', 'Subyugante', ' Salado', ' Lucidez', ' Azul', 'Entusiasmo', 'Belleza', ' Crecimiento', ' Azucar', 'Aceite', 'Arcoíris', ' Viaje', 'Hámster', ' Sorpresa', ' Aventurero', ' Café', 'Sorprendente', 'Curiosidad', ' Hilo', ' Pescado', 'Notable', ' Comprensión', ' Mantequilla', 'Madrugada', 'Estudiante', ' Primavera', ' Lago', ' Terapia', 'Habilidad', 'Gracia', 'Inigualable', 'Propósito', ' Beso', ' Felino', 'Soltero', ' Paz', ' Técnico', 'pera', 'Bailar', 'Colibrí', ' Avión', 'Lago', 'Embriagante', 'Eufórico', 'Apasionante', 'Festividad', ' Sol', 'Pantalón', 'Saltar', 'Barco', ' Cerámica', ' Interdependencia', ' Jugar', 'Elocuencia', 'Estimulado', 'Esencia', 'Salado', 'Confianza', 'Avena', ' Ética', 'Iniciativa', ' Platano', ' Nube', 'Exuberante', ' Escribir ', 'Encuentro', ' Nutrición', 'Deseo', ' Noble', ' Espiritualidad', ' Cooperación', ' Armonía', 'Pimienta', ' Superación', ' Sublime', 'Deslumbrante', 'Tradición', 'Flexibilidad', ' Universo', 'Jirafa', 'Calle', 'Diversidad', ' Actuar', ' Sensible', 'Técnico', 'Compasión', 'Espectacular', ' Arroz', ' Ave', ' Cuaderno', 'Genuino', 'Silencio', ' Queso', ' Camiseta', ' Madrugada', 'Abundancia', 'Compañerismo', 'Desafiante', 'Astonante', 'Impresión', ' Instituto', 'Atardecer', 'Logro', ' Tablet', ' Tormenta', ' Emprendimiento', 'Trueno', 'Excentricidad', 'Aldea', 'Sentimientos', 'Electrizado', 'Fascinante', 'Gratitud', ' Canela', 'Victoria', ' Lealtad', ' Bicicleta', ' Maíz', ' Éxito', 'Emoción', 'Educación', 'Cascada', 'Libertad', ' Odontología', ' Integridad', 'Sofá', 'Investigación', 'Queso', 'Iluminación', 'Generosidad', ' Pasión', 'Tierra', ' Poesía', 'Sacrificio', 'Resiliencia', 'Maravillosamente', 'Enérgico', 'Ventana']


            def Palabra_Aleatoria(lista_palabras):
                """
                Función para escoger una palabra aleatoriamente

                Argumentos:
                parametro1: lista de palabras.
         
                Returns:
                palabra aleatoria pertenciente a la lista
                """    
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                """
                Función para ocultar la palabra elegida

                Argumentos:
                parametro1: operación para ocultar cada caracter de la palabra
         
                Returns:
                palabra aleatoria pertenciente a la lista oculta
               """ 
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                """
                Función que mostrara la palabra oculta

                Argumentos:
                parametro1: palabra oculta
         
                Returns:
                Muestra la palabra que estaba oculta
                """
                print("Palabra:", " ".join(palabra_oculta))

            def adivinar_letra():
                """
                Función para adivinar la palabra

                Argumentos:
                parametro1: La letra ingresada por el usuario
                """ 
                return input("Adivina una letra: ")

            def Stickman(intentos):
                """
                Función que forma al muñeco segun los intentos

                Argumentos:
                parametro1: Intentos
        
                Returns:
                Stikman 
        
                """
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                """
                Funcion principal para jugar
        
                Returns:
                Juego ahorcado
                """ 
                palabra = Palabra_Aleatoria(lista)# En palabra se almacenara la palara aleatoria
                palabra_oculta = ocultar_palabra(palabra) # En palabra_oculta se almacenara la palabra aleatoria pero oculta
                intentos_totales = 4 # Definimos la cantidad de intentos en este modo de juego
                intentos_restantes = intentos_totales # En intentos_restantes se almacena los intentos_totales del nivel
                tiempo_inicial = time.time()# Tiempo inicial, se utilizará para el temporizador


                while intentos_restantes > 0: #bucle que permite seguir el programa mientras hallan intentos 
                    mostrar_palabra(palabra_oculta) # Llamamos la función mostra_palabra con el argumento de palabra_oculta
                    Stickman(intentos_restantes) # Llamamos la función del stikman con el argumento de los intentos
                    letra = adivinar_letra() # La variable letra almacena la función adivinar_letra
                    acierto = False # verifica el acierto del usuario
                    nueva_palabra_oculta = "" # Actualiza la palabra

                    for i in range(len(palabra)): # Ciclo para comprobar que la letra ingresada sea de la palabra
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        tiempo_total = 30  # Establecer aquí el tiempo total en segundos
                        tiempo_transcurrido = time.time() - tiempo_inicial
                        tiempo_restante = tiempo_total - tiempo_transcurrido
                        print("¡Correcto!! Te quedan", int(tiempo_restante), "segundos.")                  

                    else:
                        intentos_restantes -= 1
                        tiempo_total = 30  # Establecer aquí el tiempo total en segundos
                        tiempo_transcurrido = time.time() - tiempo_inicial
                        tiempo_restante = tiempo_total - tiempo_transcurrido
                    
                        print("Incorrecto. Te quedan", intentos_restantes, "intentos y", int(tiempo_restante), "segundos.")                   

                    if palabra_oculta.lower() == palabra.lower(): # Condicion para verficar que la palabra adivinada sea la misma que la palabra oculta
                        print("¡Ganaste! Has adivinado la palabra:", palabra)
                        break
                    
                    if tiempo_restante <= 0:
                     print("¡Perdiste! La palabra era:", palabra)
                     break



            print("Jugador 1:")
            jugar_ahorcado()
            print("Jugador 2:")
            jugar_ahorcado()


    if Multiplayer == 1:
            b   = int(input("Por favor seleccione una dificultad:\n1.facil\n2.medio\n3.dificil"))
            if b == 1:
                lista = ['Compañerismo', 'Galleta', 'Abrazo', 'Lealtad', 'Enriquecedor', 'Otoño', 'Ambición', 'Brillante', 'Quietud', 'Ciencia', ' Rojo', ' Lápiz', 'Canela', 'Aire', 'Amor', ' Autopista', ' Paciencia', 'Soledad', 'Estrategia', 'Avance', ' Moda', 'Crecimiento', 'Tenacidad', 'Emocionado', ' Literatura', 'Fiesta', ' Esperanza', 'Inspirador', ' Innovación', 'Creatividad', 'Electrizante', 'Embelesamiento', 'Carne', ' Reloj', ' Silencio', 'Rumbo', 'Nieve', 'Reverencia', 'Capacidad', 'Sueño', ' Naranja', 'Maravillarse', 'Cordialidad', 'Cambio', 'Computadora', 'Música', ' Uva', 'Epifanía', 'Correr', 'Agradecimiento', ' Liderazgo', ' Misterio', ' Gafas', 'Comunicación', 'Revelación', 'Aclamado', ' Lágrimas', 'Innovador', 'Susurro', ' Nieve', ' Horizonte', ' Marcador', ' Descubrimiento', 'Estilo', 'Embelesador', ' Deporte', 'Literatura', 'Sanar', 'Serenidad', ' Canino', 'Refrescante', 'Maravilla', 'Oficina', 'Relajación', ' Estilo', 'Vitalidad', 'Conservación', ' Dignidad', 'Redención', ' Natación', ' Descanso', 'Excitante', 'Profesión', ' Avena', ' Logro', 'Aplaudido', 'Tiempo', ' Yogur', ' Océano', 'Cine', 'Pueblo', ' Satisfacción', 'Café', ' Guitarra', 'Agua', ' Tiza', 'Responsabilidad', 'Prestigio', ' Placer', ' Llanto', 'Optimismo', 'Equipo', ' Igualdad', ' Vainilla', ' Baile', ' Autobús', 'Hobby', 'Imaginación', 'Irresistible', 'Resplandor', 'Adaptabilidad', 'Apreciación', ' Bolígrafo', ' Voluntariado', ' Esperanza ', 'Intrigante', 'Iluminador', 'Edificante', 'Impresionismo', ' Martes', ' Arquitectura', 'Progreso', 'Estrellas', ' Comunidad', 'Transcendental', 'Esplendoroso', 'Colina', 'Medio ambiente', ' Refresco', 'Anochecer', ' Inocencia', 'Maíz', ' Coraje', 'Sorprendido', ' Ejercicio', 'Espera', ' Fotografía', 'Realidad', ' Agradable', 'Encantamiento', ' Anochecer', ' Desierto', 'Impresionado', ' Triste', ' Aceite', 'Euforia', ' Pintura', ' Bienestar', ' Aldea', ' Resplandor', 'Reflexión', ' Danza', 'Pluma', 'Dedicación', 'Delicia', ' Risa', 'Enamoramiento', ' Pastel', 'Deporte', 'Reinvención', ' Cacao', ' Gastronomía', 'Simetría', 'Fraternidad', ' Ingeniero', 'Satisfactorio', 'Cacao', 'Aspiración', 'Autenticidad', 'Humildad', 'Intriga', 'Placer', 'Conciencia', 'Exhilarante', 'Abogado', ' Dinero', 'Yogur', 'Unidad', ' Computadora', ' Jugo', ' Fuego', 'Retroceso', 'Fascinación', 'Planeta', ' Felicidad', ' Gato', 'Grandeza', ' Elefante', 'Dulce', ' Conejo', 'Llanura', ' Amargo', ' Agua', ' Libro', ' Invierno', ' Trabajo', 'Atractivo', ' Optimismo', ' Escultura', 'Gastronomía', ' Bello', 'Gafas', ' Fútbol', 'Prodigio', ' Experiencia', 'Inspírate', ' Mar', ' Místico', ' Naturaleza', ' Escribir', ' Fantasía', ' Caminar', ' Alegría', 'Universo', ' Te', 'Expresión', ' Carcajada', 'Espiritualidad', 'Rejuvenecimiento', ' Río', 'Felicidad', 'banana', ' Yoga', 'Emocional', 'Oportunidad', 'Casa', ' Lapiz', 'Paciencia', ' Carretera', 'Gozo', ' Confianza', 'Atracción', 'Soñar', 'Impresionante', ' Cumpleaños', 'Pesadilla', 'Asombro', ' Nubes', 'Maravilloso', 'Equilibrio', ' Colaboración', 'Espacio', ' Empoderamiento', 'Diseño', ' Estudio', 'Emocionalmente', ' Resiliencia', 'Baloncesto', 'Resplandeciente', ' Empatía', 'Interiores', 'Estupor', 'Inolvidable', 'Admiración', ' Hermoso', 'Montaña', 'Realización', ' Ácido', 'Escribir', 'Abrazo', 'Cerámica', ' Saltar', 'Accion', ' Suspiro', 'Enojo', 'Mesa', ' Sombrero', ' Motocicleta', 'Cerveza', ' Zapatos', 'Verdad', 'Apasionantemente', 'Estrella', ' Vacaciones', 'Ritmo', ' Cielo', 'Pasatiempo', ' Colorido', 'Viajes', ' Rocío', 'Prodigioso', ' Psicología', 'Amanecer', ' Gratitud', ' Desafío', ' Nadar', 'Análisis', 'Exquisito', ' Patrimonio', ' Televisión', ' Pantalón', ' Regalo', 'Recompensa', 'Desierto', ' Nobleza', 'Conexión', ' Cuento', 'Escuela', ' Madurez', ' Lluvia', 'Lámpara', 'Espontaneidad', ' Claro', 'Constelación', ' Mouse', 'Cultura', ' Fresco', ' Inspiración', ' Sol Guitarra', 'Libro', ' Diversidad', 'Riesgo', 'naranja', 'Universidad', ' Determinación', ' Festival', ' Amabilidad', ' Brisa', ' Hámster ', 'Autopista', ' Maravilla', 'Abeja', 'Esperanza', ' Conocimiento', ' Colina', ' Hámster', ' Gentil', ' Energía', ' Radiante', ' Medicina', 'Natación', ' Cascada', ' Cariñoso', ' Cálido', 'Amistad', ' Teléfono', 'Conejo', ' Lunes', 'Aire libre', 'Carretera', ' Luminoso', ' Saxofón', 'Ética', ' Tenis', ' Camión', 'Aprendizaje', 'Sinceridad', ' Sostenibilidad', ' Bondad', 'Selva', 'Luminosidad', 'Enfoque', ' Perro', ' Universidad', ' Crianza', 'Descubrimiento', ' Jardín', 'Destreza', 'Tren', ' Iluminación', 'Planificación', ' Arena', 'Tenis', ' Exuberante', 'Superación', ' Verano', 'Ingeniero', ' Bosque', 'Tormenta', 'Trascendencia', 'Divorciado', 'Armonía', 'Empatía', ' Respeto', 'Reloj', ' Amigo', 'Hilo', ' Yogurt', ' Colegio', 'Serendipia', 'Avión', ' Juego', 'Risas', ' Plenitud', 'Escultura', 'Hospital', ' Sonrisa', 'Cautivador', 'Intuición', 'Experiencia', 'Esplendor', 'Océano', 'Prosperidad', 'Consciencia', ' Tequila', 'Aniversario', 'Seducción', 'Liderazgo', 'Sobresaliente', ' Cortés', 'Renovación', ' Valle', 'Mañana', 'Noche', 'Invierno', 'Carisma', 'Evolución', ' Flexibilidad', ' Enérgico', ' Cambio', ' Baloncesto', ' Profesionalismo', 'Inspiração', 'Emocionante', ' Maravilloso', 'Éxito', 'Solidaridad', 'Renacimiento', ' Verdura', ' Vestido', ' Conchas', 'Mar', ' Médico', 'Fe', 'Camiseta', ' Creatividad', 'Amargo', ' Celebración', ' Vitalidad', ' Flores', ' Noche', 'Risueño', 'Gratificación', ' Aventura', ' Pimienta', 'Primavera', 'Estimulante', ' Techo', 'Azúcar', 'Vestido', ' Calma', ' Libertad', ' Tranquilidad', ' Consciencia', ' Aniversario', 'Momentos', ' Feliz', ' Galaxia', ' Autenticidad', ' Meditación', ' Competencia', ' Árbol', 'Nutrición', 'Glorioso', 'Ciencia', 'Elevación', ' Aire', ' Justicia', 'Eficiencia', ' Encanto', 'Fuego', ' Tradición', ' Oasis', 'Sorpresa', 'Enseñanza', 'Júbilo', ' Soñar', 'Desbordante', 'Aventura', 'Televisión', 'Zapatos', ' Chocolate', 'Perro', 'Inspiración', ' Boda', ' Enojo', 'Apasionado', 'Medicina', ' Cepillo', 'Claridad', 'Envolvente', ' Pizza', 'Luna', 'Justicia', 'Empoderamiento', 'Silla', 'Desbordado', ' Viento', 'Riqueza', 'Recuerdos', ' Entusiasmo', ' Tecnología', ' Tienda', 'Galaxia', 'Magia', ' Encantador', ' Pasta', 'Exuberancia', 'Equidad', ' Cine', 'Perseverancia', 'Organización', ' Perseverancia', 'Carrera', 'Estupefacto', 'Sueños', 'Originalidad', 'Extraordinario', ' Trascendental', ' Oficina', ' Llanura', 'Leche', ' Patineta', ' Celular', 'Inteligencia', ' Relajante', ' Sonido', 'Arrebato', ' Atardecer', ' Inspirador', 'Caminar', ' Serenidad', 'Fantasía', 'Emancipador', ' Atento', ' Helado', 'Tarde', 'Lápiz', ' Pertenencia', 'Emprendimiento', 'Integridad', 'Inocencia', 'Harmonía', 'Autoestima', 'Alegría', ' Té', 'Cuaderno', 'Pintura', 'Arroz', 'Enriquecimiento', 'Motivador', 'Inclusión', 'manzana', ' Mindfulness', 'Respeto', ' Exploración', ' Vecino', ' Riqueza', 'Transformación', ' Pintar', ' Gozo', 'Caos', ' Tierra', 'Mariposa', ' Admiración', ' Exótico', 'Sostenibilidad', ' Apasionado', 'Vainilla', 'Fascinador', 'Ácido', 'Tigre', ' Tristeza', 'Visión', 'Relámpago', 'Satélite', ' Sincero', 'Celular', 'Verdura', 'Revigorizante', ' Whisky', 'Teatro', 'Paisaje', 'Sensación', 'Fortaleza', ' Calle', 'Puerta', ' Carne', 'Misterio', ' Teatro', 'Pasta', ' Sábado', 'Compromiso', 'Triunfo', ' Fascinante', 'Valentía', ' Trigo', 'Amabilidad', 'Paz', 'Sustentabilidad', 'Persistencia', ' Ciudad', 'Arquitectura', ' Fiesta', 'Soñador', ' Enfermería', ' Fortaleza', 'Suspiro', ' Tierno', ' Humildad', ' Escalar', ' Manzana', ' Coche', 'Luminoso', ' Soltero', 'Relaciones', 'Alegre', 'Revitalizante', ' Amistoso', 'Emocionadamente', 'Avenida', ' Belleza', ' Amarillo', 'Desafío', ' Cultura', ' Eficiencia', ' Batería', ' Majestuoso', ' Escáner', 'Sal', ' Compañero', ' Familia', 'Vibrante', ' Medio Ambiente', ' Aprendizaje', ' Abogado', 'Entretenimiento', 'Valores', 'Tienda', ' Aceptación', 'Familia', 'Conocimiento', 'Fuerza', 'Espíritu', ' Valiente', 'Revolución', 'Cuidado', ' Explorador', 'Playa', ' Sofá', ' Amistad', 'Autobús', 'Pescado', 'Danza', ' Encantamiento', ' Montaña', 'Bosque', 'Sobrevivencia', 'Incomparable', ' Hospital', ' Jardin', ' Leyenda', ' Avenida', 'Sublimación', ' Ensalada', 'Destino', ' Amable', ' Dulce', 'Eternidad', 'Sombrero', ' Eterno', ' Amoroso', 'Pintar', 'Corazón', 'Constancia', ' Silla', 'Maestro', ' Automóvil', ' Metrópoli', ' Vibrante', 'Té', 'Subyugado', 'Cepillo', ' Harmonía', 'Plenitud', 'Adictivo', ' Violín', ' Meta', 'Pletórico', 'Pensamiento', ' Lámpara', ' Disfrute', 'Ingenio', 'Retos', 'Alucinante', 'Trabajo', ' Playa', ' Refugio', ' Mañana', ' Enojado', ' Honestidad', 'Fantástico', ' Cautivador', ' Sorprendido', ' Transformación', 'Verano', ' Matemáticas', ' Sosiego', ' Moto', ' León', ' Confort', ' Recuerdo', 'Compañía', 'Gota', ' Sueño', 'Conmovedor', 'Desarrollo', 'Sabiduría', ' Casado', 'Casado', ' Amor', 'Moda', ' Arte', ' Heroico', 'Médico', 'Recuerdo', 'Trascendental', 'Autonomía', 'Techo', 'Filosofía', 'Asombroso', 'Sororidad', ' Papel', 'Tolerancia', ' Pared', ' Escuela', 'Escalar', ' Azúcar', 'Igualdad', ' Tarde', 'Refresco', 'Futuro', ' Paraíso', 'Ingeniería', 'Sublime', 'Descanso', 'Mantequilla', ' Romance', 'Mediodía', ' Rayo', ' Generoso', 'Motivación', 'Voluntad', 'Viudo', ' Ingeniería', ' Amanecer', 'Pared', 'Vivacidad', 'Exteriores', ' Independencia', 'Elefante', ' Viudo', ' Mediodía', 'Feliz', 'Maravillar', 'Embriagador', 'Prometedor', ' Educación', ' Sushi', ' Paciente', 'Innovación', 'Agricultura', 'Determinación', ' Trueno', 'Energía', 'Libélula', 'Increíble', 'Solución', 'Rayo', ' Tigre', 'Gato', ' Dedicación', ' Barco', 'Exaltación', 'Enjuague', 'Pasión', ' Ecología', 'Honestidad', ' Emoción', ' Correr', 'Tecnología', 'Revelador', 'Explorar', 'Deslumbramiento', 'Despertar', ' Vino', 'Tristeza', ' Historia', ' Luna', 'Estudio', ' Salud', ' Sabiduría', 'Exorbitante', 'Encantador', ' Leche', 'Metas', 'Bufanda', 'Nadar', 'Arte', 'Valle', 'Río', ' Natura', ' Hamburguesa', 'Historia', 'Bienestar', ' Bendición', 'Diversión', 'Exploración', 'Naturaleza', 'Inquietud', 'Melodía', ' Filantropía', ' Bufanda', 'Vigorizante', 'Cantar', ' Tolerancia', ' Gota', 'Mirada', 'Descubrir', ' Sal', ' Diversión', 'Ciudad', ' Perdón', ' Pueblo', 'Serendipidad', ' Solidaridad', ' Domingo', 'Herencia', 'Fútbol', 'Comunidad', 'Magnífico', ' Arcoíris', ' Estímulo', 'Disciplina', ' Guardería', 'Estupendo', 'Anhelo', ' Entrega', ' Música', 'Provechoso', 'Salud', ' Puerta', ' Negocios', ' Ventana', 'Sensibilidad', ' Tren', ' Estabilidad', ' Jirafa', 'Enigma', ' Valentía', 'Jugo', ' Magia', 'Palabra', ' Único', ' Piano', ' Metrópolis', 'Productividad', 'Regocijo', ' Pintoresco', 'Metrópolis', ' Renovador', 'Estremecimiento', 'Viaje', 'Coraje', 'Estremecedor', ' Cantar', 'Celebración', 'Cooperación', ' Bailar', ' Enjuague', 'Embeleso', 'Religión', ' Idílico', 'Generación', 'Trascendente', ' Pluma', 'Trigo', 'Satisfacción', 'Negocio', ' Reptil', 'Fruta', ' Mesa', ' Organización', ' Estrellas', ' Impresora', 'Meta', ' Motivación', 'Intrepidez', ' Equilibrio', 'Tranquilidad', 'Cumpleaños', ' Divorciado', 'Brillo', 'Colaboración', ' Verde', ' Postre', 'Melancolía', 'Fotografía', 'Risa', 'Aroma', ' Fruta', ' Relajación', 'Rocío', 'Vigor', ' Generosidad', 'Sonrisa', 'Otoño', 'Impulso', 'Encanto', 'Subyugante', ' Salado', ' Lucidez', ' Azul', 'Entusiasmo', 'Belleza', ' Crecimiento', ' Azucar', 'Aceite', 'Arcoíris', ' Viaje', 'Hámster', ' Sorpresa', ' Aventurero', ' Café', 'Sorprendente', 'Curiosidad', ' Hilo', ' Pescado', 'Notable', ' Comprensión', ' Mantequilla', 'Madrugada', 'Estudiante', ' Primavera', ' Lago', ' Terapia', 'Habilidad', 'Gracia', 'Inigualable', 'Propósito', ' Beso', ' Felino', 'Soltero', ' Paz', ' Técnico', 'pera', 'Bailar', 'Colibrí', ' Avión', 'Lago', 'Embriagante', 'Eufórico', 'Apasionante', 'Festividad', ' Sol', 'Pantalón', 'Saltar', 'Barco', ' Cerámica', ' Interdependencia', ' Jugar', 'Elocuencia', 'Estimulado', 'Esencia', 'Salado', 'Confianza', 'Avena', ' Ética', 'Iniciativa', ' Platano', ' Nube', 'Exuberante', ' Escribir ', 'Encuentro', ' Nutrición', 'Deseo', ' Noble', ' Espiritualidad', ' Cooperación', ' Armonía', 'Pimienta', ' Superación', ' Sublime', 'Deslumbrante', 'Tradición', 'Flexibilidad', ' Universo', 'Jirafa', 'Calle', 'Diversidad', ' Actuar', ' Sensible', 'Técnico', 'Compasión', 'Espectacular', ' Arroz', ' Ave', ' Cuaderno', 'Genuino', 'Silencio', ' Queso', ' Camiseta', ' Madrugada', 'Abundancia', 'Compañerismo', 'Desafiante', 'Astonante', 'Impresión', ' Instituto', 'Atardecer', 'Logro', ' Tablet', ' Tormenta', ' Emprendimiento', 'Trueno', 'Excentricidad', 'Aldea', 'Sentimientos', 'Electrizado', 'Fascinante', 'Gratitud', ' Canela', 'Victoria', ' Lealtad', ' Bicicleta', ' Maíz', ' Éxito', 'Emoción', 'Educación', 'Cascada', 'Libertad', ' Odontología', ' Integridad', 'Sofá', 'Investigación', 'Queso', 'Iluminación', 'Generosidad', ' Pasión', 'Tierra', ' Poesía', 'Sacrificio', 'Resiliencia', 'Maravillosamente', 'Enérgico', 'Ventana']

                def Palabra_Aleatoria(lista_palabras):
                    """
                    Función para escoger una palabra aleatoriamente

                    Argumentos:
                    parametro1: lista de palabras.
         
                    Returns:
                    palabra aleatoria pertenciente a la lista
                    """    
                    palabra_aleatoria = random.choice(lista_palabras)
                    return palabra_aleatoria

                def ocultar_palabra(palabra):
                    """
                    Función para ocultar la palabra elegida

                    Argumentos:
                    parametro1: operación para ocultar cada caracter de la palabra
         
                    Returns:
                    palabra aleatoria pertenciente a la lista oculta
                    """ 
                    oculta = "_" * len(palabra)
                    return oculta

                def mostrar_palabra(palabra_oculta):
                    """
                    Función que mostrara la palabra oculta

                    Argumentos:
                    parametro1: palabra oculta
         
                    Returns:
                    Muestra la palabra que estaba oculta
                    """
                    print("Palabra:", " ".join(palabra_oculta))

                def adivinar_letra():
                    """
                    Función para adivinar la palabra

                    Argumentos:
                    parametro1: La letra ingresada por el usuario
                    """ 
                    return input("Adivina una letra: ")

                def Stickman(intentos):
                    """
                    Función que forma al muñeco segun los intentos

                    Argumentos:
                    parametro1: Intentos
        
                    Returns:
                    Stikman 
        
                    """
                    if intentos == range(1, 1000):
                        print("")
                        print("")
                        print("")
                        print("")
                        print("")
                        print("")
                        print("=====")

                def jugar_ahorcado():
                    palabra = Palabra_Aleatoria(lista)# En palabra se almacenara la palara aleatoria
                    palabra_oculta = ocultar_palabra(palabra) # En palabra_oculta se almacenara la palabra aleatoria pero oculta
                    intentos_totales = 1000 # Definimos la cantidad de intentos en este modo de juego
                    intentos_restantes = intentos_totales # En intentos_restantes se almacena los intentos_totales del nivel
                    tiempo_inicial = time.time()# Tiempo inicial, se utilizará para el temporizador

 
                    while intentos_restantes > 0: #bucle que permite seguir el programa mientras hallan intentos 
                        mostrar_palabra(palabra_oculta) # Llamamos la función mostra_palabra con el argumento de palabra_oculta
                        Stickman(intentos_restantes) # Llamamos la función del stikman con el argumento de los intentos
                        letra = adivinar_letra() # La variable letra almacena la función adivinar_letra
                        acierto = False # verifica el acierto del usuario
                        nueva_palabra_oculta = "" # Actualiza la palabra

                        for i in range(len(palabra)): # Ciclo para comprobar que la letra ingresada sea de la palabra
                            if palabra[i].lower() == letra.lower():
                               nueva_palabra_oculta += letra
                               acierto = True
                            else:
                               nueva_palabra_oculta += palabra_oculta[i]

                        if acierto:
                            palabra_oculta = nueva_palabra_oculta
                            tiempo_total = 120 # Establecer aquí el tiempo total en segundos
                            tiempo_transcurrido = time.time() - tiempo_inicial
                            tiempo_restante = tiempo_total - tiempo_transcurrido
                            print("¡Correcto!! Te quedan", int(tiempo_restante), "segundos.")                  

                        else:
                            intentos_restantes -= 1
                            tiempo_total = 120  # Establecer aquí el tiempo total en segundos
                            tiempo_transcurrido = time.time() - tiempo_inicial
                            tiempo_restante = tiempo_total - tiempo_transcurrido
                    
                            print("Incorrecto. Te quedan", intentos_restantes, "intentos y", int(tiempo_restante), "segundos.")                   

                        if palabra_oculta.lower() == palabra.lower(): # Condicion para verficar que la palabra adivinada sea la misma que la palabra oculta
                            print("¡Ganaste! Has adivinado la palabra:", palabra)
                            break
                    
                        if tiempo_restante <= 0:
                            print("¡Perdiste! La palabra era:", palabra)
                            break


                print("Jugador 1:")
                jugar_ahorcado()

                
            elif b == 2:


                lista = [' Compañerismo', ' Galleta', ' Abrazo', 'Lealtad', 'Enriquecedor', ' Otoño', 'Ambición', 'Brillante', 'Quietud', ' Ciencia', ' Rojo', ' Lápiz', 'Canela', 'Aire', 'Amor', ' Autopista', ' Paciencia', 'Soledad', 'Estrategia', 'Avance', ' Moda', 'Crecimiento', 'Tenacidad', 'Emocionado', ' Literatura', 'Fiesta', ' Esperanza', 'Inspirador', ' Innovación', 'Creatividad', 'Electrizante', 'Embelesamiento', 'Carne', ' Reloj', ' Silencio', 'Rumbo', 'Nieve', 'Reverencia', 'Capacidad', 'Sueño', ' Naranja', 'Maravillarse', 'Cordialidad', 'Cambio', 'Computadora', 'Música', ' Uva', 'Epifanía', 'Correr', 'Agradecimiento', ' Liderazgo', ' Misterio', ' Gafas', 'Comunicación', 'Revelación', 'Aclamado', ' Lágrimas', 'Innovador', 'Susurro', ' Nieve', ' Horizonte', ' Marcador', ' Descubrimiento', 'Estilo', 'Embelesador', ' Deporte', 'Literatura', 'Sanar', 'Serenidad', ' Canino', 'Refrescante', 'Maravilla', 'Oficina', 'Relajación', ' Estilo', 'Vitalidad', 'Conservación', ' Dignidad', 'Redención', ' Natación', ' Descanso', 'Excitante', 'Profesión', ' Avena', ' Logro', 'Aplaudido', 'Tiempo', ' Yogur', ' Océano', 'Cine', 'Pueblo', ' Satisfacción', 'Café', ' Guitarra', 'Agua', ' Tiza', 'Responsabilidad', 'Prestigio', ' Placer', ' Llanto', 'Optimismo', 'Equipo', ' Igualdad', ' Vainilla', ' Baile', ' Autobús', 'Hobby', 'Imaginación', 'Irresistible', 'Resplandor', 'Adaptabilidad', 'Apreciación', ' Bolígrafo', ' Voluntariado', ' Esperanza ', 'Intrigante', 'Iluminador', 'Edificante', 'Impresionismo', ' Martes', ' Arquitectura', 'Progreso', 'Estrellas', ' Comunidad', 'Transcendental', 'Esplendoroso', 'Colina', 'Medio ambiente', ' Refresco', 'Anochecer', ' Inocencia', 'Maíz', ' Coraje', 'Sorprendido', ' Ejercicio', 'Espera', ' Fotografía', 'Realidad', ' Agradable', 'Encantamiento', ' Anochecer', ' Desierto', 'Impresionado', ' Triste', ' Aceite', 'Euforia', ' Pintura', ' Bienestar', ' Aldea', ' Resplandor', 'Reflexión', ' Danza', 'Pluma', 'Dedicación', 'Delicia', ' Risa', 'Enamoramiento', ' Pastel', 'Deporte', 'Reinvención', ' Cacao', ' Gastronomía', 'Simetría', 'Fraternidad', ' Ingeniero', 'Satisfactorio', 'Cacao', 'Aspiración', 'Autenticidad', 'Humildad', 'Intriga', 'Placer', 'Conciencia', 'Exhilarante', 'Abogado', ' Dinero', 'Yogur', 'Unidad', ' Computadora', ' Jugo', ' Fuego', 'Retroceso', 'Fascinación', 'Planeta', ' Felicidad', ' Gato', 'Grandeza', ' Elefante', 'Dulce', ' Conejo', 'Llanura', ' Amargo', ' Agua', ' Libro', ' Invierno', ' Trabajo', 'Atractivo', ' Optimismo', ' Escultura', 'Gastronomía', ' Bello', 'Gafas', ' Fútbol', 'Prodigio', ' Experiencia', 'Inspírate', ' Mar', ' Místico', ' Naturaleza', ' Escribir', ' Fantasía', ' Caminar', ' Alegría', 'Universo', ' Te', 'Expresión', ' Carcajada', 'Espiritualidad', 'Rejuvenecimiento', ' Río', 'Felicidad', 'banana', ' Yoga', 'Emocional', 'Oportunidad', 'Casa', ' Lapiz', 'Paciencia', ' Carretera', 'Gozo', ' Confianza', 'Atracción', 'Soñar', 'Impresionante', ' Cumpleaños', 'Pesadilla', 'Asombro', ' Nubes', 'Maravilloso', 'Equilibrio', ' Colaboración', 'Espacio', ' Empoderamiento', 'Diseño', ' Estudio', 'Emocionalmente', ' Resiliencia', 'Baloncesto', 'Resplandeciente', ' Empatía', 'Interiores', 'Estupor', 'Inolvidable', 'Admiración', ' Hermoso', 'Montaña', 'Realización', ' Ácido', 'Escribir', 'Abrazo', 'Cerámica', ' Saltar', 'Accion', ' Suspiro', 'Enojo', 'Mesa', ' Sombrero', ' Motocicleta', 'Cerveza', ' Zapatos', 'Verdad', 'Apasionantemente', 'Estrella', ' Vacaciones', 'Ritmo', ' Cielo', 'Pasatiempo', ' Colorido', 'Viajes', ' Rocío', 'Prodigioso', ' Psicología', 'Amanecer', ' Gratitud', ' Desafío', ' Nadar', 'Análisis', 'Exquisito', ' Patrimonio', ' Televisión', ' Pantalón', ' Regalo', 'Recompensa', 'Desierto', ' Nobleza', 'Conexión', ' Cuento', 'Escuela', ' Madurez', ' Lluvia', 'Lámpara', 'Espontaneidad', ' Claro', 'Constelación', ' Mouse', 'Cultura', ' Fresco', ' Inspiración', ' Sol Guitarra', 'Libro', ' Diversidad', 'Riesgo', 'naranja', 'Universidad', ' Determinación', ' Festival', ' Amabilidad', ' Brisa', ' Hámster ', 'Autopista', ' Maravilla', 'Abeja', 'Esperanza', ' Conocimiento', ' Colina', ' Hámster', ' Gentil', ' Energía', ' Radiante', ' Medicina', 'Natación', ' Cascada', ' Cariñoso', ' Cálido', 'Amistad', ' Teléfono', 'Conejo', ' Lunes', 'Aire libre', 'Carretera', ' Luminoso', ' Saxofón', 'Ética', ' Tenis', ' Camión', 'Aprendizaje', 'Sinceridad', ' Sostenibilidad', ' Bondad', 'Selva', 'Luminosidad', 'Enfoque', ' Perro', ' Universidad', ' Crianza', 'Descubrimiento', ' Jardín', 'Destreza', 'Tren', ' Iluminación', 'Planificación', ' Arena', 'Tenis', ' Exuberante', 'Superación', ' Verano', 'Ingeniero', ' Bosque', 'Tormenta', 'Trascendencia', 'Divorciado', 'Armonía', 'Empatía', ' Respeto', 'Reloj', ' Amigo', 'Hilo', ' Yogurt', ' Colegio', 'Serendipia', 'Avión', ' Juego', 'Risas', ' Plenitud', 'Escultura', 'Hospital', ' Sonrisa', 'Cautivador', 'Intuición', 'Experiencia', 'Esplendor', 'Océano', 'Prosperidad', 'Consciencia', ' Tequila', 'Aniversario', 'Seducción', 'Liderazgo', 'Sobresaliente', ' Cortés', 'Renovación', ' Valle', 'Mañana', 'Noche', 'Invierno', 'Carisma', 'Evolución', ' Flexibilidad', ' Enérgico', ' Cambio', ' Baloncesto', ' Profesionalismo', 'Inspiração', 'Emocionante', ' Maravilloso', 'Éxito', 'Solidaridad', 'Renacimiento', ' Verdura', ' Vestido', ' Conchas', 'Mar', ' Médico', 'Fe', 'Camiseta', ' Creatividad', 'Amargo', ' Celebración', ' Vitalidad', ' Flores', ' Noche', 'Risueño', 'Gratificación', ' Aventura', ' Pimienta', 'Primavera', 'Estimulante', ' Techo', 'Azúcar', 'Vestido', ' Calma', ' Libertad', ' Tranquilidad', ' Consciencia', ' Aniversario', 'Momentos', ' Feliz', ' Galaxia', ' Autenticidad', ' Meditación', ' Competencia', ' Árbol', 'Nutrición', 'Glorioso', 'Ciencia', 'Elevación', ' Aire', ' Justicia', 'Eficiencia', ' Encanto', 'Fuego', ' Tradición', ' Oasis', 'Sorpresa', 'Enseñanza', 'Júbilo', ' Soñar', 'Desbordante', 'Aventura', 'Televisión', 'Zapatos', ' Chocolate', 'Perro', 'Inspiración', ' Boda', ' Enojo', 'Apasionado', 'Medicina', ' Cepillo', 'Claridad', 'Envolvente', ' Pizza', 'Luna', 'Justicia', 'Empoderamiento', 'Silla', 'Desbordado', ' Viento', 'Riqueza', 'Recuerdos', ' Entusiasmo', ' Tecnología', ' Tienda', 'Galaxia', 'Magia', ' Encantador', ' Pasta', 'Exuberancia', 'Equidad', ' Cine', 'Perseverancia', 'Organización', ' Perseverancia', 'Carrera', 'Estupefacto', 'Sueños', 'Originalidad', 'Extraordinario', ' Trascendental', ' Oficina', ' Llanura', 'Leche', ' Patineta', ' Celular', 'Inteligencia', ' Relajante', ' Sonido', 'Arrebato', ' Atardecer', ' Inspirador', 'Caminar', ' Serenidad', 'Fantasía', 'Emancipador', ' Atento', ' Helado', 'Tarde', 'Lápiz', ' Pertenencia', 'Emprendimiento', 'Integridad', 'Inocencia', 'Harmonía', 'Autoestima', 'Alegría', ' Té', 'Cuaderno', 'Pintura', 'Arroz', 'Enriquecimiento', 'Motivador', 'Inclusión', 'manzana', ' Mindfulness', 'Respeto', ' Exploración', ' Vecino', ' Riqueza', 'Transformación', ' Pintar', ' Gozo', 'Caos', ' Tierra', 'Mariposa', ' Admiración', ' Exótico', 'Sostenibilidad', ' Apasionado', 'Vainilla', 'Fascinador', 'Ácido', 'Tigre', ' Tristeza', 'Visión', 'Relámpago', 'Satélite', ' Sincero', 'Celular', 'Verdura', 'Revigorizante', ' Whisky', 'Teatro', 'Paisaje', 'Sensación', 'Fortaleza', ' Calle', 'Puerta', ' Carne', 'Misterio', ' Teatro', 'Pasta', ' Sábado', 'Compromiso', 'Triunfo', ' Fascinante', 'Valentía', ' Trigo', 'Amabilidad', 'Paz', 'Sustentabilidad', 'Persistencia', ' Ciudad', 'Arquitectura', ' Fiesta', 'Soñador', ' Enfermería', ' Fortaleza', 'Suspiro', ' Tierno', ' Humildad', ' Escalar', ' Manzana', ' Coche', 'Luminoso', ' Soltero', 'Relaciones', 'Alegre', 'Revitalizante', ' Amistoso', 'Emocionadamente', 'Avenida', ' Belleza', ' Amarillo', 'Desafío', ' Cultura', ' Eficiencia', ' Batería', ' Majestuoso', ' Escáner', 'Sal', ' Compañero', ' Familia', 'Vibrante', ' Medio Ambiente', ' Aprendizaje', ' Abogado', 'Entretenimiento', 'Valores', 'Tienda', ' Aceptación', 'Familia', 'Conocimiento', 'Fuerza', 'Espíritu', ' Valiente', 'Revolución', 'Cuidado', ' Explorador', 'Playa', ' Sofá', ' Amistad', 'Autobús', 'Pescado', 'Danza', ' Encantamiento', ' Montaña', 'Bosque', 'Sobrevivencia', 'Incomparable', ' Hospital', ' Jardin', ' Leyenda', ' Avenida', 'Sublimación', ' Ensalada', 'Destino', ' Amable', ' Dulce', 'Eternidad', 'Sombrero', ' Eterno', ' Amoroso', 'Pintar', 'Corazón', 'Constancia', ' Silla', 'Maestro', ' Automóvil', ' Metrópoli', ' Vibrante', 'Té', 'Subyugado', 'Cepillo', ' Harmonía', 'Plenitud', 'Adictivo', ' Violín', ' Meta', 'Pletórico', 'Pensamiento', ' Lámpara', ' Disfrute', 'Ingenio', 'Retos', 'Alucinante', 'Trabajo', ' Playa', ' Refugio', ' Mañana', ' Enojado', ' Honestidad', 'Fantástico', ' Cautivador', ' Sorprendido', ' Transformación', 'Verano', ' Matemáticas', ' Sosiego', ' Moto', ' León', ' Confort', ' Recuerdo', 'Compañía', 'Gota', ' Sueño', 'Conmovedor', 'Desarrollo', 'Sabiduría', ' Casado', 'Casado', ' Amor', 'Moda', ' Arte', ' Heroico', 'Médico', 'Recuerdo', 'Trascendental', 'Autonomía', 'Techo', 'Filosofía', 'Asombroso', 'Sororidad', ' Papel', 'Tolerancia', ' Pared', ' Escuela', 'Escalar', ' Azúcar', 'Igualdad', ' Tarde', 'Refresco', 'Futuro', ' Paraíso', 'Ingeniería', 'Sublime', 'Descanso', 'Mantequilla', ' Romance', 'Mediodía', ' Rayo', ' Generoso', 'Motivación', 'Voluntad', 'Viudo', ' Ingeniería', ' Amanecer', 'Pared', 'Vivacidad', 'Exteriores', ' Independencia', 'Elefante', ' Viudo', ' Mediodía', 'Feliz', 'Maravillar', 'Embriagador', 'Prometedor', ' Educación', ' Sushi', ' Paciente', 'Innovación', 'Agricultura', 'Determinación', ' Trueno', 'Energía', 'Libélula', 'Increíble', 'Solución', 'Rayo', ' Tigre', 'Gato', ' Dedicación', ' Barco', 'Exaltación', 'Enjuague', 'Pasión', ' Ecología', 'Honestidad', ' Emoción', ' Correr', 'Tecnología', 'Revelador', 'Explorar', 'Deslumbramiento', 'Despertar', ' Vino', 'Tristeza', ' Historia', ' Luna', 'Estudio', ' Salud', ' Sabiduría', 'Exorbitante', 'Encantador', ' Leche', 'Metas', 'Bufanda', 'Nadar', 'Arte', 'Valle', 'Río', ' Natura', ' Hamburguesa', 'Historia', 'Bienestar', ' Bendición', 'Diversión', 'Exploración', 'Naturaleza', 'Inquietud', 'Melodía', ' Filantropía', ' Bufanda', 'Vigorizante', 'Cantar', ' Tolerancia', ' Gota', 'Mirada', 'Descubrir', ' Sal', ' Diversión', 'Ciudad', ' Perdón', ' Pueblo', 'Serendipidad', ' Solidaridad', ' Domingo', 'Herencia', 'Fútbol', 'Comunidad', 'Magnífico', ' Arcoíris', ' Estímulo', 'Disciplina', ' Guardería', 'Estupendo', 'Anhelo', ' Entrega', ' Música', 'Provechoso', 'Salud', ' Puerta', ' Negocios', ' Ventana', 'Sensibilidad', ' Tren', ' Estabilidad', ' Jirafa', 'Enigma', ' Valentía', 'Jugo', ' Magia', 'Palabra', ' Único', ' Piano', ' Metrópolis', 'Productividad', 'Regocijo', ' Pintoresco', 'Metrópolis', ' Renovador', 'Estremecimiento', 'Viaje', 'Coraje', 'Estremecedor', ' Cantar', 'Celebración', 'Cooperación', ' Bailar', ' Enjuague', 'Embeleso', 'Religión', ' Idílico', 'Generación', 'Trascendente', ' Pluma', 'Trigo', 'Satisfacción', 'Negocio', ' Reptil', 'Fruta', ' Mesa', ' Organización', ' Estrellas', ' Impresora', 'Meta', ' Motivación', 'Intrepidez', ' Equilibrio', 'Tranquilidad', 'Cumpleaños', ' Divorciado', 'Brillo', 'Colaboración', ' Verde', ' Postre', 'Melancolía', 'Fotografía', 'Risa', 'Aroma', ' Fruta', ' Relajación', 'Rocío', 'Vigor', ' Generosidad', 'Sonrisa', 'Otoño', 'Impulso', 'Encanto', 'Subyugante', ' Salado', ' Lucidez', ' Azul', 'Entusiasmo', 'Belleza', ' Crecimiento', ' Azucar', 'Aceite', 'Arcoíris', ' Viaje', 'Hámster', ' Sorpresa', ' Aventurero', ' Café', 'Sorprendente', 'Curiosidad', ' Hilo', ' Pescado', 'Notable', ' Comprensión', ' Mantequilla', 'Madrugada', 'Estudiante', ' Primavera', ' Lago', ' Terapia', 'Habilidad', 'Gracia', 'Inigualable', 'Propósito', ' Beso', ' Felino', 'Soltero', ' Paz', ' Técnico', 'pera', 'Bailar', 'Colibrí', ' Avión', 'Lago', 'Embriagante', 'Eufórico', 'Apasionante', 'Festividad', ' Sol', 'Pantalón', 'Saltar', 'Barco', ' Cerámica', ' Interdependencia', ' Jugar', 'Elocuencia', 'Estimulado', 'Esencia', 'Salado', 'Confianza', 'Avena', ' Ética', 'Iniciativa', ' Platano', ' Nube', 'Exuberante', ' Escribir ', 'Encuentro', ' Nutrición', 'Deseo', ' Noble', ' Espiritualidad', ' Cooperación', ' Armonía', 'Pimienta', ' Superación', ' Sublime', 'Deslumbrante', 'Tradición', 'Flexibilidad', ' Universo', 'Jirafa', 'Calle', 'Diversidad', ' Actuar', ' Sensible', 'Técnico', 'Compasión', 'Espectacular', ' Arroz', ' Ave', ' Cuaderno', 'Genuino', 'Silencio', ' Queso', ' Camiseta', ' Madrugada', 'Abundancia', 'Compañerismo', 'Desafiante', 'Astonante', 'Impresión', ' Instituto', 'Atardecer', 'Logro', ' Tablet', ' Tormenta', ' Emprendimiento', 'Trueno', 'Excentricidad', 'Aldea', 'Sentimientos', 'Electrizado', 'Fascinante', 'Gratitud', ' Canela', 'Victoria', ' Lealtad', ' Bicicleta', ' Maíz', ' Éxito', 'Emoción', 'Educación', 'Cascada', 'Libertad', ' Odontología', ' Integridad', 'Sofá', 'Investigación', 'Queso', 'Iluminación', 'Generosidad', ' Pasión', 'Tierra', ' Poesía', 'Sacrificio', 'Resiliencia', 'Maravillosamente', 'Enérgico', 'Ventana']

                def Palabra_Aleatoria(lista_palabras):
                    """
                    Función para escoger una palabra aleatoriamente

                    Argumentos:
                    parametro1: lista de palabras.
         
                    Returns:
                    palabra aleatoria pertenciente a la lista
                    """    
                    palabra_aleatoria = random.choice(lista_palabras)
                    return palabra_aleatoria

                def ocultar_palabra(palabra):
                    """
                    Función para ocultar la palabra elegida

                    Argumentos:
                    parametro1: operación para ocultar cada caracter de la palabra
         
                    Returns:
                    palabra aleatoria pertenciente a la lista oculta
                    """ 
                    oculta = "_" * len(palabra)
                    return oculta

                def mostrar_palabra(palabra_oculta):
                    """
                    Función que mostrara la palabra oculta

                    Argumentos:
                    parametro1: palabra oculta
         
                    Returns:
                    Muestra la palabra que estaba oculta
                    """
                    print("Palabra:", " ".join(palabra_oculta))

                def adivinar_letra():
                    """
                    Función para adivinar la palabra

                    Argumentos:
                    parametro1: La letra ingresada por el usuario
                    """ 
                    return input("Adivina una letra: ")

                def Stickman(intentos):
                    """
                    Función que forma al muñeco segun los intentos

                    Argumentos:
                    parametro1: Intentos
        
                    Returns:
                    Stikman 
        
                    """
                    if intentos == 0:
                        print("  -------")
                        print("  |     |")
                        print("  |     O")
                        print("  |    /|\\")
                        print("  |    / \\")
                        print("  |")
                        print("=====")
                    elif intentos == 1:
                        print("  -------")
                        print("  |     |")
                        print("  |     O")
                        print("  |    /|\\")
                        print("  |    /")
                        print("  |")
                        print("=====")
                    elif intentos == 2:
                        print("  -------")
                        print("  |     |")
                        print("  |     O")
                        print("  |    /|\\")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 3:
                        print("  -------")
                        print("  |     |")
                        print("  |     O")
                        print("  |     |\\")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 4:
                        print("  -------")
                        print("  |     |")
                        print("  |     O")
                        print("  |     |")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 5:
                        print("  -------")
                        print("  |     |")
                        print("  |     O")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 6:
                        print("  -------")
                        print("  |     |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 7:
                        print("  -------")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 8:
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 9:
                        print("")
                        print("")
                        print("")
                        print("")
                        print("")
                        print("")
                        print("=====")
                    elif intentos == 10:
                        print("")
                        print("")
                        print("")
                        print("")
                        print("")
                        print("")
                        print("=====")

                def jugar_ahorcado():
                    palabra = Palabra_Aleatoria(lista)# En palabra se almacenara la palara aleatoria
                    palabra_oculta = ocultar_palabra(palabra) # En palabra_oculta se almacenara la palabra aleatoria pero oculta
                    intentos_totales = 10 # Definimos la cantidad de intentos en este modo de juego
                    intentos_restantes = intentos_totales # En intentos_restantes se almacena los intentos_totales del nivel
                    tiempo_inicial = time.time()# Tiempo inicial, se utilizará para el temporizador

 
                    while intentos_restantes > 0: #bucle que permite seguir el programa mientras hallan intentos 
                        mostrar_palabra(palabra_oculta) # Llamamos la función mostra_palabra con el argumento de palabra_oculta
                        Stickman(intentos_restantes) # Llamamos la función del stikman con el argumento de los intentos
                        letra = adivinar_letra() # La variable letra almacena la función adivinar_letra
                        acierto = False # verifica el acierto del usuario
                        nueva_palabra_oculta = "" # Actualiza la palabra

                        for i in range(len(palabra)): # Ciclo para comprobar que la letra ingresada sea de la palabra
                            if palabra[i].lower() == letra.lower():
                               nueva_palabra_oculta += letra
                               acierto = True
                            else:
                               nueva_palabra_oculta += palabra_oculta[i]

                        if acierto:
                            palabra_oculta = nueva_palabra_oculta
                            tiempo_total = 60 # Establecer aquí el tiempo total en segundos
                            tiempo_transcurrido = time.time() - tiempo_inicial
                            tiempo_restante = tiempo_total - tiempo_transcurrido
                            print("¡Correcto!! Te quedan", int(tiempo_restante), "segundos.")                  

                        else:
                            intentos_restantes -= 1
                            tiempo_total = 60  # Establecer aquí el tiempo total en segundos
                            tiempo_transcurrido = time.time() - tiempo_inicial
                            tiempo_restante = tiempo_total - tiempo_transcurrido
                    
                            print("Incorrecto. Te quedan", intentos_restantes, "intentos y", int(tiempo_restante), "segundos.")                   

                        if palabra_oculta.lower() == palabra.lower(): # Condicion para verficar que la palabra adivinada sea la misma que la palabra oculta
                            print("¡Ganaste! Has adivinado la palabra:", palabra)
                            break
                    
                        if tiempo_restante <= 0:
                            print("¡Perdiste! La palabra era:", palabra)
                            break



                print("Jugador 1:")
                jugar_ahorcado()

            elif b == 3:

                import random
                lista = [' Compañerismo', ' Galleta', ' Abrazo', 'Lealtad', 'Enriquecedor', ' Otoño', 'Ambición', 'Brillante', 'Quietud', ' Ciencia', ' Rojo', ' Lápiz', 'Canela', 'Aire', 'Amor', ' Autopista', ' Paciencia', 'Soledad', 'Estrategia', 'Avance', ' Moda', 'Crecimiento', 'Tenacidad', 'Emocionado', ' Literatura', 'Fiesta', ' Esperanza', 'Inspirador', ' Innovación', 'Creatividad', 'Electrizante', 'Embelesamiento', 'Carne', ' Reloj', ' Silencio', 'Rumbo', 'Nieve', 'Reverencia', 'Capacidad', 'Sueño', ' Naranja', 'Maravillarse', 'Cordialidad', 'Cambio', 'Computadora', 'Música', ' Uva', 'Epifanía', 'Correr', 'Agradecimiento', ' Liderazgo', ' Misterio', ' Gafas', 'Comunicación', 'Revelación', 'Aclamado', ' Lágrimas', 'Innovador', 'Susurro', ' Nieve', ' Horizonte', ' Marcador', ' Descubrimiento', 'Estilo', 'Embelesador', ' Deporte', 'Literatura', 'Sanar', 'Serenidad', ' Canino', 'Refrescante', 'Maravilla', 'Oficina', 'Relajación', ' Estilo', 'Vitalidad', 'Conservación', ' Dignidad', 'Redención', ' Natación', ' Descanso', 'Excitante', 'Profesión', ' Avena', ' Logro', 'Aplaudido', 'Tiempo', ' Yogur', ' Océano', 'Cine', 'Pueblo', ' Satisfacción', 'Café', ' Guitarra', 'Agua', ' Tiza', 'Responsabilidad', 'Prestigio', ' Placer', ' Llanto', 'Optimismo', 'Equipo', ' Igualdad', ' Vainilla', ' Baile', ' Autobús', 'Hobby', 'Imaginación', 'Irresistible', 'Resplandor', 'Adaptabilidad', 'Apreciación', ' Bolígrafo', ' Voluntariado', ' Esperanza ', 'Intrigante', 'Iluminador', 'Edificante', 'Impresionismo', ' Martes', ' Arquitectura', 'Progreso', 'Estrellas', ' Comunidad', 'Transcendental', 'Esplendoroso', 'Colina', 'Medio ambiente', ' Refresco', 'Anochecer', ' Inocencia', 'Maíz', ' Coraje', 'Sorprendido', ' Ejercicio', 'Espera', ' Fotografía', 'Realidad', ' Agradable', 'Encantamiento', ' Anochecer', ' Desierto', 'Impresionado', ' Triste', ' Aceite', 'Euforia', ' Pintura', ' Bienestar', ' Aldea', ' Resplandor', 'Reflexión', ' Danza', 'Pluma', 'Dedicación', 'Delicia', ' Risa', 'Enamoramiento', ' Pastel', 'Deporte', 'Reinvención', ' Cacao', ' Gastronomía', 'Simetría', 'Fraternidad', ' Ingeniero', 'Satisfactorio', 'Cacao', 'Aspiración', 'Autenticidad', 'Humildad', 'Intriga', 'Placer', 'Conciencia', 'Exhilarante', 'Abogado', ' Dinero', 'Yogur', 'Unidad', ' Computadora', ' Jugo', ' Fuego', 'Retroceso', 'Fascinación', 'Planeta', ' Felicidad', ' Gato', 'Grandeza', ' Elefante', 'Dulce', ' Conejo', 'Llanura', ' Amargo', ' Agua', ' Libro', ' Invierno', ' Trabajo', 'Atractivo', ' Optimismo', ' Escultura', 'Gastronomía', ' Bello', 'Gafas', ' Fútbol', 'Prodigio', ' Experiencia', 'Inspírate', ' Mar', ' Místico', ' Naturaleza', ' Escribir', ' Fantasía', ' Caminar', ' Alegría', 'Universo', ' Te', 'Expresión', ' Carcajada', 'Espiritualidad', 'Rejuvenecimiento', ' Río', 'Felicidad', 'banana', ' Yoga', 'Emocional', 'Oportunidad', 'Casa', ' Lapiz', 'Paciencia', ' Carretera', 'Gozo', ' Confianza', 'Atracción', 'Soñar', 'Impresionante', ' Cumpleaños', 'Pesadilla', 'Asombro', ' Nubes', 'Maravilloso', 'Equilibrio', ' Colaboración', 'Espacio', ' Empoderamiento', 'Diseño', ' Estudio', 'Emocionalmente', ' Resiliencia', 'Baloncesto', 'Resplandeciente', ' Empatía', 'Interiores', 'Estupor', 'Inolvidable', 'Admiración', ' Hermoso', 'Montaña', 'Realización', ' Ácido', 'Escribir', 'Abrazo', 'Cerámica', ' Saltar', 'Accion', ' Suspiro', 'Enojo', 'Mesa', ' Sombrero', ' Motocicleta', 'Cerveza', ' Zapatos', 'Verdad', 'Apasionantemente', 'Estrella', ' Vacaciones', 'Ritmo', ' Cielo', 'Pasatiempo', ' Colorido', 'Viajes', ' Rocío', 'Prodigioso', ' Psicología', 'Amanecer', ' Gratitud', ' Desafío', ' Nadar', 'Análisis', 'Exquisito', ' Patrimonio', ' Televisión', ' Pantalón', ' Regalo', 'Recompensa', 'Desierto', ' Nobleza', 'Conexión', ' Cuento', 'Escuela', ' Madurez', ' Lluvia', 'Lámpara', 'Espontaneidad', ' Claro', 'Constelación', ' Mouse', 'Cultura', ' Fresco', ' Inspiración', ' Sol Guitarra', 'Libro', ' Diversidad', 'Riesgo', 'naranja', 'Universidad', ' Determinación', ' Festival', ' Amabilidad', ' Brisa', ' Hámster ', 'Autopista', ' Maravilla', 'Abeja', 'Esperanza', ' Conocimiento', ' Colina', ' Hámster', ' Gentil', ' Energía', ' Radiante', ' Medicina', 'Natación', ' Cascada', ' Cariñoso', ' Cálido', 'Amistad', ' Teléfono', 'Conejo', ' Lunes', 'Aire libre', 'Carretera', ' Luminoso', ' Saxofón', 'Ética', ' Tenis', ' Camión', 'Aprendizaje', 'Sinceridad', ' Sostenibilidad', ' Bondad', 'Selva', 'Luminosidad', 'Enfoque', ' Perro', ' Universidad', ' Crianza', 'Descubrimiento', ' Jardín', 'Destreza', 'Tren', ' Iluminación', 'Planificación', ' Arena', 'Tenis', ' Exuberante', 'Superación', ' Verano', 'Ingeniero', ' Bosque', 'Tormenta', 'Trascendencia', 'Divorciado', 'Armonía', 'Empatía', ' Respeto', 'Reloj', ' Amigo', 'Hilo', ' Yogurt', ' Colegio', 'Serendipia', 'Avión', ' Juego', 'Risas', ' Plenitud', 'Escultura', 'Hospital', ' Sonrisa', 'Cautivador', 'Intuición', 'Experiencia', 'Esplendor', 'Océano', 'Prosperidad', 'Consciencia', ' Tequila', 'Aniversario', 'Seducción', 'Liderazgo', 'Sobresaliente', ' Cortés', 'Renovación', ' Valle', 'Mañana', 'Noche', 'Invierno', 'Carisma', 'Evolución', ' Flexibilidad', ' Enérgico', ' Cambio', ' Baloncesto', ' Profesionalismo', 'Inspiração', 'Emocionante', ' Maravilloso', 'Éxito', 'Solidaridad', 'Renacimiento', ' Verdura', ' Vestido', ' Conchas', 'Mar', ' Médico', 'Fe', 'Camiseta', ' Creatividad', 'Amargo', ' Celebración', ' Vitalidad', ' Flores', ' Noche', 'Risueño', 'Gratificación', ' Aventura', ' Pimienta', 'Primavera', 'Estimulante', ' Techo', 'Azúcar', 'Vestido', ' Calma', ' Libertad', ' Tranquilidad', ' Consciencia', ' Aniversario', 'Momentos', ' Feliz', ' Galaxia', ' Autenticidad', ' Meditación', ' Competencia', ' Árbol', 'Nutrición', 'Glorioso', 'Ciencia', 'Elevación', ' Aire', ' Justicia', 'Eficiencia', ' Encanto', 'Fuego', ' Tradición', ' Oasis', 'Sorpresa', 'Enseñanza', 'Júbilo', ' Soñar', 'Desbordante', 'Aventura', 'Televisión', 'Zapatos', ' Chocolate', 'Perro', 'Inspiración', ' Boda', ' Enojo', 'Apasionado', 'Medicina', ' Cepillo', 'Claridad', 'Envolvente', ' Pizza', 'Luna', 'Justicia', 'Empoderamiento', 'Silla', 'Desbordado', ' Viento', 'Riqueza', 'Recuerdos', ' Entusiasmo', ' Tecnología', ' Tienda', 'Galaxia', 'Magia', ' Encantador', ' Pasta', 'Exuberancia', 'Equidad', ' Cine', 'Perseverancia', 'Organización', ' Perseverancia', 'Carrera', 'Estupefacto', 'Sueños', 'Originalidad', 'Extraordinario', ' Trascendental', ' Oficina', ' Llanura', 'Leche', ' Patineta', ' Celular', 'Inteligencia', ' Relajante', ' Sonido', 'Arrebato', ' Atardecer', ' Inspirador', 'Caminar', ' Serenidad', 'Fantasía', 'Emancipador', ' Atento', ' Helado', 'Tarde', 'Lápiz', ' Pertenencia', 'Emprendimiento', 'Integridad', 'Inocencia', 'Harmonía', 'Autoestima', 'Alegría', ' Té', 'Cuaderno', 'Pintura', 'Arroz', 'Enriquecimiento', 'Motivador', 'Inclusión', 'manzana', ' Mindfulness', 'Respeto', ' Exploración', ' Vecino', ' Riqueza', 'Transformación', ' Pintar', ' Gozo', 'Caos', ' Tierra', 'Mariposa', ' Admiración', ' Exótico', 'Sostenibilidad', ' Apasionado', 'Vainilla', 'Fascinador', 'Ácido', 'Tigre', ' Tristeza', 'Visión', 'Relámpago', 'Satélite', ' Sincero', 'Celular', 'Verdura', 'Revigorizante', ' Whisky', 'Teatro', 'Paisaje', 'Sensación', 'Fortaleza', ' Calle', 'Puerta', ' Carne', 'Misterio', ' Teatro', 'Pasta', ' Sábado', 'Compromiso', 'Triunfo', ' Fascinante', 'Valentía', ' Trigo', 'Amabilidad', 'Paz', 'Sustentabilidad', 'Persistencia', ' Ciudad', 'Arquitectura', ' Fiesta', 'Soñador', ' Enfermería', ' Fortaleza', 'Suspiro', ' Tierno', ' Humildad', ' Escalar', ' Manzana', ' Coche', 'Luminoso', ' Soltero', 'Relaciones', 'Alegre', 'Revitalizante', ' Amistoso', 'Emocionadamente', 'Avenida', ' Belleza', ' Amarillo', 'Desafío', ' Cultura', ' Eficiencia', ' Batería', ' Majestuoso', ' Escáner', 'Sal', ' Compañero', ' Familia', 'Vibrante', ' Medio Ambiente', ' Aprendizaje', ' Abogado', 'Entretenimiento', 'Valores', 'Tienda', ' Aceptación', 'Familia', 'Conocimiento', 'Fuerza', 'Espíritu', ' Valiente', 'Revolución', 'Cuidado', ' Explorador', 'Playa', ' Sofá', ' Amistad', 'Autobús', 'Pescado', 'Danza', ' Encantamiento', ' Montaña', 'Bosque', 'Sobrevivencia', 'Incomparable', ' Hospital', ' Jardin', ' Leyenda', ' Avenida', 'Sublimación', ' Ensalada', 'Destino', ' Amable', ' Dulce', 'Eternidad', 'Sombrero', ' Eterno', ' Amoroso', 'Pintar', 'Corazón', 'Constancia', ' Silla', 'Maestro', ' Automóvil', ' Metrópoli', ' Vibrante', 'Té', 'Subyugado', 'Cepillo', ' Harmonía', 'Plenitud', 'Adictivo', ' Violín', ' Meta', 'Pletórico', 'Pensamiento', ' Lámpara', ' Disfrute', 'Ingenio', 'Retos', 'Alucinante', 'Trabajo', ' Playa', ' Refugio', ' Mañana', ' Enojado', ' Honestidad', 'Fantástico', ' Cautivador', ' Sorprendido', ' Transformación', 'Verano', ' Matemáticas', ' Sosiego', ' Moto', ' León', ' Confort', ' Recuerdo', 'Compañía', 'Gota', ' Sueño', 'Conmovedor', 'Desarrollo', 'Sabiduría', ' Casado', 'Casado', ' Amor', 'Moda', ' Arte', ' Heroico', 'Médico', 'Recuerdo', 'Trascendental', 'Autonomía', 'Techo', 'Filosofía', 'Asombroso', 'Sororidad', ' Papel', 'Tolerancia', ' Pared', ' Escuela', 'Escalar', ' Azúcar', 'Igualdad', ' Tarde', 'Refresco', 'Futuro', ' Paraíso', 'Ingeniería', 'Sublime', 'Descanso', 'Mantequilla', ' Romance', 'Mediodía', ' Rayo', ' Generoso', 'Motivación', 'Voluntad', 'Viudo', ' Ingeniería', ' Amanecer', 'Pared', 'Vivacidad', 'Exteriores', ' Independencia', 'Elefante', ' Viudo', ' Mediodía', 'Feliz', 'Maravillar', 'Embriagador', 'Prometedor', ' Educación', ' Sushi', ' Paciente', 'Innovación', 'Agricultura', 'Determinación', ' Trueno', 'Energía', 'Libélula', 'Increíble', 'Solución', 'Rayo', ' Tigre', 'Gato', ' Dedicación', ' Barco', 'Exaltación', 'Enjuague', 'Pasión', ' Ecología', 'Honestidad', ' Emoción', ' Correr', 'Tecnología', 'Revelador', 'Explorar', 'Deslumbramiento', 'Despertar', ' Vino', 'Tristeza', ' Historia', ' Luna', 'Estudio', ' Salud', ' Sabiduría', 'Exorbitante', 'Encantador', ' Leche', 'Metas', 'Bufanda', 'Nadar', 'Arte', 'Valle', 'Río', ' Natura', ' Hamburguesa', 'Historia', 'Bienestar', ' Bendición', 'Diversión', 'Exploración', 'Naturaleza', 'Inquietud', 'Melodía', ' Filantropía', ' Bufanda', 'Vigorizante', 'Cantar', ' Tolerancia', ' Gota', 'Mirada', 'Descubrir', ' Sal', ' Diversión', 'Ciudad', ' Perdón', ' Pueblo', 'Serendipidad', ' Solidaridad', ' Domingo', 'Herencia', 'Fútbol', 'Comunidad', 'Magnífico', ' Arcoíris', ' Estímulo', 'Disciplina', ' Guardería', 'Estupendo', 'Anhelo', ' Entrega', ' Música', 'Provechoso', 'Salud', ' Puerta', ' Negocios', ' Ventana', 'Sensibilidad', ' Tren', ' Estabilidad', ' Jirafa', 'Enigma', ' Valentía', 'Jugo', ' Magia', 'Palabra', ' Único', ' Piano', ' Metrópolis', 'Productividad', 'Regocijo', ' Pintoresco', 'Metrópolis', ' Renovador', 'Estremecimiento', 'Viaje', 'Coraje', 'Estremecedor', ' Cantar', 'Celebración', 'Cooperación', ' Bailar', ' Enjuague', 'Embeleso', 'Religión', ' Idílico', 'Generación', 'Trascendente', ' Pluma', 'Trigo', 'Satisfacción', 'Negocio', ' Reptil', 'Fruta', ' Mesa', ' Organización', ' Estrellas', ' Impresora', 'Meta', ' Motivación', 'Intrepidez', ' Equilibrio', 'Tranquilidad', 'Cumpleaños', ' Divorciado', 'Brillo', 'Colaboración', ' Verde', ' Postre', 'Melancolía', 'Fotografía', 'Risa', 'Aroma', ' Fruta', ' Relajación', 'Rocío', 'Vigor', ' Generosidad', 'Sonrisa', 'Otoño', 'Impulso', 'Encanto', 'Subyugante', ' Salado', ' Lucidez', ' Azul', 'Entusiasmo', 'Belleza', ' Crecimiento', ' Azucar', 'Aceite', 'Arcoíris', ' Viaje', 'Hámster', ' Sorpresa', ' Aventurero', ' Café', 'Sorprendente', 'Curiosidad', ' Hilo', ' Pescado', 'Notable', ' Comprensión', ' Mantequilla', 'Madrugada', 'Estudiante', ' Primavera', ' Lago', ' Terapia', 'Habilidad', 'Gracia', 'Inigualable', 'Propósito', ' Beso', ' Felino', 'Soltero', ' Paz', ' Técnico', 'pera', 'Bailar', 'Colibrí', ' Avión', 'Lago', 'Embriagante', 'Eufórico', 'Apasionante', 'Festividad', ' Sol', 'Pantalón', 'Saltar', 'Barco', ' Cerámica', ' Interdependencia', ' Jugar', 'Elocuencia', 'Estimulado', 'Esencia', 'Salado', 'Confianza', 'Avena', ' Ética', 'Iniciativa', ' Platano', ' Nube', 'Exuberante', ' Escribir ', 'Encuentro', ' Nutrición', 'Deseo', ' Noble', ' Espiritualidad', ' Cooperación', ' Armonía', 'Pimienta', ' Superación', ' Sublime', 'Deslumbrante', 'Tradición', 'Flexibilidad', ' Universo', 'Jirafa', 'Calle', 'Diversidad', ' Actuar', ' Sensible', 'Técnico', 'Compasión', 'Espectacular', ' Arroz', ' Ave', ' Cuaderno', 'Genuino', 'Silencio', ' Queso', ' Camiseta', ' Madrugada', 'Abundancia', 'Compañerismo', 'Desafiante', 'Astonante', 'Impresión', ' Instituto', 'Atardecer', 'Logro', ' Tablet', ' Tormenta', ' Emprendimiento', 'Trueno', 'Excentricidad', 'Aldea', 'Sentimientos', 'Electrizado', 'Fascinante', 'Gratitud', ' Canela', 'Victoria', ' Lealtad', ' Bicicleta', ' Maíz', ' Éxito', 'Emoción', 'Educación', 'Cascada', 'Libertad', ' Odontología', ' Integridad', 'Sofá', 'Investigación', 'Queso', 'Iluminación', 'Generosidad', ' Pasión', 'Tierra', ' Poesía', 'Sacrificio', 'Resiliencia', 'Maravillosamente', 'Enérgico', 'Ventana']



                def Palabra_Aleatoria(lista_palabras):
                    """
                    Función para escoger una palabra aleatoriamente

                    Argumentos:
                    parametro1: lista de palabras.
         
                    Returns:
                    palabra aleatoria pertenciente a la lista
                    """    
                    palabra_aleatoria = random.choice(lista_palabras)
                    return palabra_aleatoria

                def ocultar_palabra(palabra):
                    """
                    Función para ocultar la palabra elegida

                    Argumentos:
                    parametro1: operación para ocultar cada caracter de la palabra
         
                    Returns:
                    palabra aleatoria pertenciente a la lista oculta
                    """ 
                    oculta = "_" * len(palabra)
                    return oculta

                def mostrar_palabra(palabra_oculta):
                    """
                    Función que mostrara la palabra oculta

                    Argumentos:
                    parametro1: palabra oculta
         
                    Returns:
                    Muestra la palabra que estaba oculta
                    """
                    print("Palabra:", " ".join(palabra_oculta))

                def adivinar_letra():
                    """
                    Función para adivinar la palabra

                    Argumentos:
                    parametro1: La letra ingresada por el usuario
                    """ 
                    return input("Adivina una letra: ")

                def Stickman(intentos):
                    """
                    Función que forma al muñeco segun los intentos

                    Argumentos:
                    parametro1: Intentos
        
                    Returns:
                    Stikman 
        
                    """
                    if intentos == 1:
                        print("  -------")
                        print("  |     |")
                        print("  |     O")
                        print("  |    /|\\")
                        print("  |    / \\")
                        print("  |")
                        print("=====")
                    elif intentos == 2:
                        print("  -------")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 3:
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("  |")
                        print("=====")
                    elif intentos == 4:
                        print("")
                        print("")
                        print("")
                        print("")
                        print("")
                        print("")
                        print("=====")

                def jugar_ahorcado():
                    palabra = Palabra_Aleatoria(lista)# En palabra se almacenara la palara aleatoria
                    palabra_oculta = ocultar_palabra(palabra) # En palabra_oculta se almacenara la palabra aleatoria pero oculta
                    intentos_totales = 4 # Definimos la cantidad de intentos en este modo de juego
                    intentos_restantes = intentos_totales # En intentos_restantes se almacena los intentos_totales del nivel
                    tiempo_inicial = time.time()# Tiempo inicial, se utilizará para el temporizador

 
                    while intentos_restantes > 0: #bucle que permite seguir el programa mientras hallan intentos 
                        mostrar_palabra(palabra_oculta) # Llamamos la función mostra_palabra con el argumento de palabra_oculta
                        Stickman(intentos_restantes) # Llamamos la función del stikman con el argumento de los intentos
                        letra = adivinar_letra() # La variable letra almacena la función adivinar_letra
                        acierto = False # verifica el acierto del usuario
                        nueva_palabra_oculta = "" # Actualiza la palabra

                        for i in range(len(palabra)): # Ciclo para comprobar que la letra ingresada sea de la palabra
                            if palabra[i].lower() == letra.lower():
                               nueva_palabra_oculta += letra
                               acierto = True
                            else:
                               nueva_palabra_oculta += palabra_oculta[i]

                        if acierto:
                            palabra_oculta = nueva_palabra_oculta
                            tiempo_total = 30 # Establecer aquí el tiempo total en segundos
                            tiempo_transcurrido = time.time() - tiempo_inicial
                            tiempo_restante = tiempo_total - tiempo_transcurrido
                            print("¡Correcto!! Te quedan", int(tiempo_restante), "segundos.")                  

                        else:
                            intentos_restantes -= 1
                            tiempo_total = 30  # Establecer aquí el tiempo total en segundos
                            tiempo_transcurrido = time.time() - tiempo_inicial
                            tiempo_restante = tiempo_total - tiempo_transcurrido
                    
                            print("Incorrecto. Te quedan", intentos_restantes, "intentos y", int(tiempo_restante), "segundos.")                   

                        if palabra_oculta.lower() == palabra.lower(): # Condicion para verficar que la palabra adivinada sea la misma que la palabra oculta
                            print("¡Ganaste! Has adivinado la palabra:", palabra)
                            break
                    
                        if tiempo_restante <= 0:
                            print("¡Perdiste! La palabra era:", palabra)
                            break



                print("Jugador 1:")
                jugar_ahorcado()

elif a == 2:
    Multiplayer = int(input("seleccione la cantidad de jugadores 1-2:"))
    if Multiplayer == 2:
        b=int(input("Please select a difficulty:\n1.easy\n2.medium\n3.hard" ))
        if b == 1:

            

            lista = ['Companionship', 'Biscuit', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Bright', 'Stillness', 'Science', 'Red', 'Pencil', 'Cinnamon ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Amazement', 'Meat', 'Clock', 'Silence', 'Heading', 'Snow', 'Bow ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Style', 'Enchanting', 'Sport', 'Literature', 'Heal', 'Serenity', 'Dog', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Career', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt' , 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen ', 'Volunteering', 'Hope', 'Intriguing', 'Enlightening', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Momentous', 'Splendid', 'Hill', 'Environment', 'Refreshment', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photograph', ' Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Village', 'Glow' , 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Fall in love', 'Cake', 'Sport', 'Reinvention', 'Cocoa', 'Gastronomy', ' Symmetry', 'Brotherhood', 'Engineer', 'Fulfilling', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer' , 'Money', 'Yogurt', 'Drive', 'Computer', 'Juice', 'Fire', 'Backwind', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', ' Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work', 'Attractive', 'Optimism', 'Sculpture', 'Gastronomy' , 'Beautiful', 'Glasses', 'Football', 'Prodigy', 'Experience', 'Get Inspired', 'Sea', 'Mystic', 'Nature', 'Write', 'Fantasy', 'Walking', ' Joy', 'Universe', 'Te', 'Expression', 'Laughter', 'Spirituality', 'Rejuvenation', 'River', 'Happiness', 'Banana', 'Yoga', 'Emotional', 'Opportunity' , 'Home', 'Pen', 'Patience', 'Road', 'Joy', 'Trust', 'Attraction', 'Dreaming', 'Awesome', 'Birthday', 'Nightmare', 'Amazement', ' Clouds', 'Gorgeous', 'Balance', 'Collaboration', 'Space', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing', 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', 'Jump', ' Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motorcycle', 'Beer', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday', 'Rhythm' , 'Sky', 'Pastime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', 'Analysis', ' Exquisite', 'Heritage', 'Television', 'Pants', 'Gift', 'Reward', 'Desert', 'Nobility', 'Connection', 'Story', 'School', 'Maturity', 'Rain' , 'Lamp', 'Spontaneity', 'Claro', 'Constellation', 'Mouse', 'Culture', 'Fresh', 'Inspiration', 'Sun Guitar', 'Book', 'Diversity', 'Risk', 'orange', 'University', 'Determination', 'Festival', 'Kindness', 'Breeze', 'Hamster', 'Highway', 'Wonder', 'Bee', 'Hope', 'Knowledge', 'Hill ', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Sincerity', 'Sustainability', 'Kindness', 'Jungle', 'Shine', 'Focus ', 'Dog', 'University', 'Nurture', 'Discovery', 'Garden', 'Skill', 'Train', 'Lighting', 'Planning', 'Arena', 'Tennis', 'Lush', 'Overcoming', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendence', 'Divorced', 'Harmony', 'Empathy', 'Respect', 'Clock', 'Friend', 'Thread ', 'Yogurt', 'School', 'Serendipity', 'Airplane', 'Game', 'Laughter', 'Plenitude', 'Sculpture', 'Hospital', 'Smile', 'Captivating', 'Intuition', 'Experience', 'Splendor', 'Ocean', 'Prosperity', 'Consciousness', 'Tequila', 'Anniversary', 'Seduction', 'Leadership', 'Outstanding', 'Courteous', 'Renewal', 'Valley ', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter ', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Giggle', 'Reward', 'Adventure', 'Pepper', 'Spring', 'Exhilarating', 'Ceiling', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Consciousness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competence', 'Tree ', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate' , 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization ', 'Perseverance', 'Career', 'Dazed', 'Dreams', 'Originality', 'Extraordinary', 'Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Mindful', 'Icy', 'Evening ', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivator', 'Inclusion', 'apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos ', 'Earth', 'Butterfly', 'Amazement', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Candid', 'Cellular', 'Vegetable', 'Invigorating', 'Whisky', 'Theatre', 'Landscape', 'Feeling', 'Fortress', 'Street', 'Door ', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Kindness', 'Peace', 'Sustainability', 'Persistence', 'City', 'Architecture', 'Party', 'Dreamer', 'Nursing', 'Fortitude', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple ', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', 'Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Family', 'Vibrant', 'Environment', 'Learning', 'Lawyer', ' Entertainment', 'Values', 'Shop', 'Acceptance', 'Family', 'Knowledge', 'Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Explorer', 'Beach' , 'Sofa', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment', 'Mountain', 'Forest', 'Survival', 'Incomparable', 'Hospital', 'Garden', ' Legend', 'Avenue', 'Sublimation', 'Salad', 'Fate', 'Kind', 'Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart' , 'Constancy', 'Chair', 'Master', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive', ' Violin', 'Goal', 'Plethoric', 'Thought', 'Lamp', 'Enjoyment', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning' , 'Angry', 'Honesty', 'Fantastic', 'Enthralling', 'Surprised', 'Transformation', 'Summer', 'Math', 'Calm', 'Motorbike', 'Lion', 'Comfort', ' Souvenir', 'Company', 'Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic' , 'Medical', 'Memory', 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', ' Climb', 'Sugar', 'Equality', 'Evening', 'Soda', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning' , 'Generous', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Amazing', 'Heady', 'Promising', 'Education', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Determination', 'Thunder', 'Energy' , 'Dragonfly', 'Incredible', 'Solution', 'Lightning', 'Tiger', 'Cat', 'Dedication', 'Boat', 'Exaltation', 'Rinsing', 'Passion', 'Ecology', 'Honesty', 'Emotion', 'Running', 'Technology', 'Revealing', 'Explore', 'Dazzle', 'Awakening', 'Wine', 'Sadness', 'History', 'Moon', 'Study' , 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', 'History', 'Wellness', 'Blessing', 'Fun', 'Exploration', 'Nature', 'Restlessness', 'Melody', 'Philanthropy', 'Scarf', 'Invigorating', 'Sing ', 'Tolerance', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage', 'Football', 'Community', 'Gorgeous', 'Rainbow', 'Encouragement', 'Discipline', 'Nursery', 'Great', 'Longing', 'Dedication', 'Music', 'Profitable' , 'Health', 'Door', 'Business', 'Window', 'Sensitivity', 'Train', 'Stability', 'Giraffe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Exhilaration', 'Picturesque', 'Metropolis', 'Renewal', 'Shocking', 'Journey', 'Courage', 'Shocking' , 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinse', 'Enchantment', 'Religion', 'Idyllic', 'Generation', 'Transcendent', 'Feather', 'Wheat', 'Satisfaction', 'Business', 'Reptile', 'Fruit', 'Table', 'Organization', 'Stars', 'Printer', 'Goal', 'Motivation', 'Fearlessness', 'Balance', 'Tranquility' , 'Birthday', 'Divorced', 'Shine', 'Collaboration', 'Green', 'Dessert', 'Melancholy', 'Photography', 'Laughter', 'Aroma', 'Fruit', 'Relaxation', 'Dew', 'Vigor', 'Generosity', 'Smile', 'Autumn', 'Impulse', 'Charm', 'Enchanting', 'Salty', 'Lucidity', 'Blue', 'Enthusiasm', 'Beauty ', 'Growth', 'Sugar', 'Oil', 'Rainbow', 'Travel', 'Hamster', 'Surprise', 'Adventurer', 'Coffee', 'Amazing', 'Curiosity', 'Thread', 'Fish', 'Remarkable', 'Understanding', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Purpose' , 'Kiss', 'Feline', 'Single', 'Peace', 'Technician', 'Pear', 'Dance', 'Hummingbird', 'Airplane', 'Lake', 'Intoxicating', 'Euphoric', 'Exciting', 'Festivity', 'Sun', 'Pants', 'Jump', 'Boat', 'Ceramic', 'Interdependence', 'Play', 'Eloquence', 'Stimulated', 'Essence', 'Salty' , 'Trust', 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Desire', 'Noble', 'Spirituality', 'Cooperation', 'Harmony', 'Pepper', 'Improvement', 'Sublime', 'Dazzling', 'Tradition', 'Flexibility', 'Universe', 'Giraffe', 'Street', 'Diversity' , 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Entrepreneurship', 'Thunder ', 'Eccentricity', 'Village', 'Feelings', 'Electrified', 'Fascinating', 'Gratitude', 'Cinnamon', 'Victory', 'Loyalty', 'Bicycle', 'Corn', 'Success', 'Emotion', 'Education', 'Waterfall', 'Freedom', 'Dentistry', 'Integrity', 'Sofa', 'Research', 'Cheese', 'Enlightenment', 'Generosity', 'Passion', 'Earth ', 'Poetry', 'Sacrifice', 'Resilience', 'Wonderfully', 'Energetic', 'Window']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("The word:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Guess a letter: ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("¡Correct!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrect. you have left ", intentos_restantes, "Attempts.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Won! You have guessed the word:", palabra)
                        break

                if intentos_restantes == 0:
                        print("You lost! The word was:", palabra)


            print("Player 1:")
            jugar_ahorcado()
            print("Player 2:")
            jugar_ahorcado()
            
        elif b == 2:


            lista = ['Companionship', 'Biscuit', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Bright', 'Stillness', 'Science', 'Red', 'Pencil', 'Cinnamon ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Amazement', 'Meat', 'Clock', 'Silence', 'Heading', 'Snow', 'Bow ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Style', 'Enchanting', 'Sport', 'Literature', 'Heal', 'Serenity', 'Dog', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Career', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt' , 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen ', 'Volunteering', 'Hope', 'Intriguing', 'Enlightening', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Momentous', 'Splendid', 'Hill', 'Environment', 'Refreshment', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photograph', ' Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Village', 'Glow' , 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Fall in love', 'Cake', 'Sport', 'Reinvention', 'Cocoa', 'Gastronomy', ' Symmetry', 'Brotherhood', 'Engineer', 'Fulfilling', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer' , 'Money', 'Yogurt', 'Drive', 'Computer', 'Juice', 'Fire', 'Backwind', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', ' Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work', 'Attractive', 'Optimism', 'Sculpture', 'Gastronomy' , 'Beautiful', 'Glasses', 'Football', 'Prodigy', 'Experience', 'Get Inspired', 'Sea', 'Mystic', 'Nature', 'Write', 'Fantasy', 'Walking', ' Joy', 'Universe', 'Te', 'Expression', 'Laughter', 'Spirituality', 'Rejuvenation', 'River', 'Happiness', 'Banana', 'Yoga', 'Emotional', 'Opportunity' , 'Home', 'Pen', 'Patience', 'Road', 'Joy', 'Trust', 'Attraction', 'Dreaming', 'Awesome', 'Birthday', 'Nightmare', 'Amazement', ' Clouds', 'Gorgeous', 'Balance', 'Collaboration', 'Space', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing', 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', 'Jump', ' Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motorcycle', 'Beer', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday', 'Rhythm' , 'Sky', 'Pastime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', 'Analysis', ' Exquisite', 'Heritage', 'Television', 'Pants', 'Gift', 'Reward', 'Desert', 'Nobility', 'Connection', 'Story', 'School', 'Maturity', 'Rain' , 'Lamp', 'Spontaneity', 'Claro', 'Constellation', 'Mouse', 'Culture', 'Fresh', 'Inspiration', 'Sun Guitar', 'Book', 'Diversity', 'Risk', 'orange', 'University', 'Determination', 'Festival', 'Kindness', 'Breeze', 'Hamster', 'Highway', 'Wonder', 'Bee', 'Hope', 'Knowledge', 'Hill ', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Sincerity', 'Sustainability', 'Kindness', 'Jungle', 'Shine', 'Focus ', 'Dog', 'University', 'Nurture', 'Discovery', 'Garden', 'Skill', 'Train', 'Lighting', 'Planning', 'Arena', 'Tennis', 'Lush', 'Overcoming', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendence', 'Divorced', 'Harmony', 'Empathy', 'Respect', 'Clock', 'Friend', 'Thread ', 'Yogurt', 'School', 'Serendipity', 'Airplane', 'Game', 'Laughter', 'Plenitude', 'Sculpture', 'Hospital', 'Smile', 'Captivating', 'Intuition', 'Experience', 'Splendor', 'Ocean', 'Prosperity', 'Consciousness', 'Tequila', 'Anniversary', 'Seduction', 'Leadership', 'Outstanding', 'Courteous', 'Renewal', 'Valley ', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter ', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Giggle', 'Reward', 'Adventure', 'Pepper', 'Spring', 'Exhilarating', 'Ceiling', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Consciousness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competence', 'Tree ', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate' , 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization ', 'Perseverance', 'Career', 'Dazed', 'Dreams', 'Originality', 'Extraordinary', 'Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Mindful', 'Icy', 'Evening ', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivator', 'Inclusion', 'apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos ', 'Earth', 'Butterfly', 'Amazement', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Candid', 'Cellular', 'Vegetable', 'Invigorating', 'Whisky', 'Theatre', 'Landscape', 'Feeling', 'Fortress', 'Street', 'Door ', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Kindness', 'Peace', 'Sustainability', 'Persistence', 'City', 'Architecture', 'Party', 'Dreamer', 'Nursing', 'Fortitude', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple ', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', 'Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Family', 'Vibrant', 'Environment', 'Learning', 'Lawyer', ' Entertainment', 'Values', 'Shop', 'Acceptance', 'Family', 'Knowledge', 'Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Explorer', 'Beach' , 'Sofa', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment', 'Mountain', 'Forest', 'Survival', 'Incomparable', 'Hospital', 'Garden', 'Legend', 'Avenue', 'Sublimation', 'Salad', 'Fate', 'Kind', 'Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart' , 'Constancy', 'Chair', 'Master', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive', ' Violin', 'Goal', 'Plethoric', 'Thought', 'Lamp', 'Enjoyment', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning' , 'Angry', 'Honesty', 'Fantastic', 'Enthralling', 'Surprised', 'Transformation', 'Summer', 'Math', 'Calm', 'Motorbike', 'Lion', 'Comfort', ' Souvenir', 'Company', 'Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic' , 'Medical', 'Memory', 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', ' Climb', 'Sugar', 'Equality', 'Evening', 'Soda', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning' , 'Generous', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Amazing', 'Heady', 'Promising', 'Education', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Determination', 'Thunder', 'Energy' , 'Dragonfly', 'Incredible', 'Solution', 'Lightning', 'Tiger', 'Cat', 'Dedication', 'Boat', 'Exaltation', 'Rinsing', 'Passion', 'Ecology', 'Honesty', 'Emotion', 'Running', 'Technology', 'Revealing', 'Explore', 'Dazzle', 'Awakening', 'Wine', 'Sadness', 'History', 'Moon', 'Study' , 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', 'History', 'Wellness', 'Blessing', 'Fun', 'Exploration', 'Nature', 'Restlessness', 'Melody', 'Philanthropy', 'Scarf', 'Invigorating', 'Sing ', 'Tolerance', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage', 'Football', 'Community', 'Gorgeous', 'Rainbow', 'Encouragement', 'Discipline', 'Nursery', 'Great', 'Longing', 'Dedication', 'Music', 'Profitable' , 'Health', 'Door', 'Business', 'Window', 'Sensitivity', 'Train', 'Stability', 'Giraffe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Exhilaration', 'Picturesque', 'Metropolis', 'Renewal', 'Shocking', 'Journey', 'Courage', 'Shocking' , 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinse', 'Enchantment', 'Religion', 'Idyllic', 'Generation', 'Transcendent', 'Feather', 'Wheat', 'Satisfaction', 'Business', 'Reptile', 'Fruit', 'Table', 'Organization', 'Stars', 'Printer', 'Goal', 'Motivation', 'Fearlessness', 'Balance', 'Tranquility' , 'Birthday', 'Divorced', 'Shine', 'Collaboration', 'Green', 'Dessert', 'Melancholy', 'Photography', 'Laughter', 'Aroma', 'Fruit', 'Relaxation', 'Dew', 'Vigor', 'Generosity', 'Smile', 'Autumn', 'Impulse', 'Charm', 'Enchanting', 'Salty', 'Lucidity', 'Blue', 'Enthusiasm', 'Beauty ', 'Growth', 'Sugar', 'Oil', 'Rainbow', 'Travel', 'Hamster', 'Surprise', 'Adventurer', 'Coffee', 'Amazing', 'Curiosity', 'Thread', 'Fish', 'Remarkable', 'Understanding', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Purpose' , 'Kiss', 'Feline', 'Single', 'Peace', 'Technician', 'Pear', 'Dance', 'Hummingbird', 'Airplane', 'Lake', 'Intoxicating', 'Euphoric', 'Exciting', 'Festivity', 'Sun', 'Pants', 'Jump', 'Boat', 'Ceramic', 'Interdependence', 'Play', 'Eloquence', 'Stimulated', 'Essence', 'Salty' , 'Trust', 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Desire', 'Noble', 'Spirituality', 'Cooperation', 'Harmony', 'Pepper', 'Improvement', 'Sublime', 'Dazzling', 'Tradition', 'Flexibility', 'Universe', 'Giraffe', 'Street', 'Diversity' , 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Entrepreneurship', 'Thunder ', 'Eccentricity', 'Village', 'Feelings', 'Electrified', 'Fascinating', 'Gratitude', 'Cinnamon', 'Victory', 'Loyalty', 'Bicycle', 'Corn', 'Success', 'Emotion', 'Education', 'Waterfall', 'Freedom', 'Dentistry', 'Integrity', 'Sofa', 'Research', 'Cheese', 'Enlightenment', 'Generosity', 'Passion', 'Earth ', 'Poetry', 'Sacrifice', 'Resilience', 'Wonderfully', 'Energetic', 'Window']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("The word:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Guess a letter: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("¡Correct!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrect. you have left ", intentos_restantes, "Attempts.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Won! You have guessed the word: ", palabra)
                        break

                    if intentos_restantes == 0:
                        print("You lost! The word was:", palabra)


            print("Player 1:")
            jugar_ahorcado()
            print("player 2:")
            jugar_ahorcado()

        elif b == 3:

            import random
            lista = ['Companionship', 'Biscuit', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Bright', 'Stillness', 'Science', 'Red', 'Pencil', 'Cinnamon ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Amazement', 'Meat', 'Clock', 'Silence', 'Heading', 'Snow', 'Bow ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Style', 'Enchanting', 'Sport', 'Literature', 'Heal', 'Serenity', 'Dog', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Career', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt' , 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen ', 'Volunteering', 'Hope', 'Intriguing', 'Enlightening', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Momentous', 'Splendid', 'Hill', 'Environment', 'Refreshment', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photograph', ' Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Village', 'Glow' , 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Fall in love', 'Cake', 'Sport', 'Reinvention', 'Cocoa', 'Gastronomy', ' Symmetry', 'Brotherhood', 'Engineer', 'Fulfilling', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer' , 'Money', 'Yogurt', 'Drive', 'Computer', 'Juice', 'Fire', 'Backwind', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', ' Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work', 'Attractive', 'Optimism', 'Sculpture', 'Gastronomy' , 'Beautiful', 'Glasses', 'Football', 'Prodigy', 'Experience', 'Get Inspired', 'Sea', 'Mystic', 'Nature', 'Write', 'Fantasy', 'Walking', ' Joy', 'Universe', 'Te', 'Expression', 'Laughter', 'Spirituality', 'Rejuvenation', 'River', 'Happiness', 'Banana', 'Yoga', 'Emotional', 'Opportunity' , 'Home', 'Pen', 'Patience', 'Road', 'Joy', 'Trust', 'Attraction', 'Dreaming', 'Awesome', 'Birthday', 'Nightmare', 'Amazement', ' Clouds', 'Gorgeous', 'Balance', 'Collaboration', 'Space', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing', 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', 'Jump', ' Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motorcycle', 'Beer', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday', 'Rhythm' , 'Sky', 'Pastime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', 'Analysis', ' Exquisite', 'Heritage', 'Television', 'Pants', 'Gift', 'Reward', 'Desert', 'Nobility', 'Connection', 'Story', 'School', 'Maturity', 'Rain' , 'Lamp', 'Spontaneity', 'Claro', 'Constellation', 'Mouse', 'Culture', 'Fresh', 'Inspiration', 'Sun Guitar', 'Book', 'Diversity', 'Risk', 'orange', 'University', 'Determination', 'Festival', 'Kindness', 'Breeze', 'Hamster', 'Highway', 'Wonder', 'Bee', 'Hope', 'Knowledge', 'Hill ', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Sincerity', 'Sustainability', 'Kindness', 'Jungle', 'Shine', 'Focus ', 'Dog', 'University', 'Nurture', 'Discovery', 'Garden', 'Skill', 'Train', 'Lighting', 'Planning', 'Arena', 'Tennis', 'Lush', 'Overcoming', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendence', 'Divorced', 'Harmony', 'Empathy', 'Respect', 'Clock', 'Friend', 'Thread ', 'Yogurt', 'School', 'Serendipity', 'Airplane', 'Game', 'Laughter', 'Plenitude', 'Sculpture', 'Hospital', 'Smile', 'Captivating', 'Intuition', 'Experience', 'Splendor', 'Ocean', 'Prosperity', 'Consciousness', 'Tequila', 'Anniversary', 'Seduction', 'Leadership', 'Outstanding', 'Courteous', 'Renewal', 'Valley ', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter ', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Giggle', 'Reward', 'Adventure', 'Pepper', 'Spring', 'Exhilarating', 'Ceiling', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Consciousness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competence', 'Tree ', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate' , 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization ', 'Perseverance', 'Career', 'Dazed', 'Dreams', 'Originality', 'Extraordinary', 'Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Mindful', 'Icy', 'Evening ', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivator', 'Inclusion', 'apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos ', 'Earth', 'Butterfly', 'Amazement', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Candid', 'Cellular', 'Vegetable', 'Invigorating', 'Whisky', 'Theatre', 'Landscape', 'Feeling', 'Fortress', 'Street', 'Door ', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Kindness', 'Peace', 'Sustainability', 'Persistence', 'City', 'Architecture', 'Party', 'Dreamer', 'Nursing', 'Fortitude', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple ', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', 'Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Family', 'Vibrant', 'Environment', 'Learning', 'Lawyer', ' Entertainment', 'Values', 'Shop', 'Acceptance', 'Family', 'Knowledge', 'Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Explorer', 'Beach' , 'Sofa', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment', 'Mountain', 'Forest', 'Survival', 'Incomparable', 'Hospital', 'Garden', ' Legend', 'Avenue', 'Sublimation', 'Salad', 'Fate', 'Kind', 'Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart' , 'Constancy', 'Chair', 'Master', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive', ' Violin', 'Goal', 'Plethoric', 'Thought', 'Lamp', 'Enjoyment', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning' , 'Angry', 'Honesty', 'Fantastic', 'Enthralling', 'Surprised', 'Transformation', 'Summer', 'Math', 'Calm', 'Motorbike', 'Lion', 'Comfort', ' Souvenir', 'Company', 'Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic' , 'Medical', 'Memory', 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', ' Climb', 'Sugar', 'Equality', 'Evening', 'Soda', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning' , 'Generous', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Amazing', 'Heady', 'Promising', 'Education', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Determination', 'Thunder', 'Energy' , 'Dragonfly', 'Incredible', 'Solution', 'Lightning', 'Tiger', 'Cat', 'Dedication', 'Boat', 'Exaltation', 'Rinsing', 'Passion', 'Ecology', 'Honesty', 'Emotion', 'Running', 'Technology', 'Revealing', 'Explore', 'Dazzle', 'Awakening', 'Wine', 'Sadness', 'History', 'Moon', 'Study' , 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', 'History', 'Wellness', 'Blessing', 'Fun', 'Exploration', 'Nature', 'Restlessness', 'Melody', 'Philanthropy', 'Scarf', 'Invigorating', 'Sing ', 'Tolerance', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage', 'Football', 'Community', 'Gorgeous', 'Rainbow', 'Encouragement', 'Discipline', 'Nursery', 'Great', 'Longing', 'Dedication', 'Music', 'Profitable' , 'Health', 'Door', 'Business', 'Window', 'Sensitivity', 'Train', 'Stability', 'Giraffe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Exhilaration', 'Picturesque', 'Metropolis', 'Renewal', 'Shocking', 'Journey', 'Courage', 'Shocking' , 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinse', 'Enchantment', 'Religion', 'Idyllic', 'Generation', 'Transcendent', 'Feather', 'Wheat', 'Satisfaction', 'Business', 'Reptile', 'Fruit', 'Table', 'Organization', 'Stars', 'Printer', 'Goal', 'Motivation', 'Fearlessness', 'Balance', 'Tranquility' , 'Birthday', 'Divorced', 'Shine', 'Collaboration', 'Green', 'Dessert', 'Melancholy', 'Photography', 'Laughter', 'Aroma', 'Fruit', 'Relaxation', 'Dew', 'Vigor', 'Generosity', 'Smile', 'Autumn', 'Impulse', 'Charm', 'Enchanting', 'Salty', 'Lucidity', 'Blue', 'Enthusiasm', 'Beauty ', 'Growth', 'Sugar', 'Oil', 'Rainbow', 'Travel', 'Hamster', 'Surprise', 'Adventurer', 'Coffee', 'Amazing', 'Curiosity', 'Thread', 'Fish', 'Remarkable', 'Understanding', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Purpose' , 'Kiss', 'Feline', 'Single', 'Peace', 'Technician', 'Pear', 'Dance', 'Hummingbird', 'Airplane', 'Lake', 'Intoxicating', 'Euphoric', 'Exciting', 'Festivity', 'Sun', 'Pants', 'Jump', 'Boat', 'Ceramic', 'Interdependence', 'Play', 'Eloquence', 'Stimulated', 'Essence', 'Salty' , 'Trust', 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Desire', 'Noble', 'Spirituality', 'Cooperation', 'Harmony', 'Pepper', 'Improvement', 'Sublime', 'Dazzling', 'Tradition', 'Flexibility', 'Universe', 'Giraffe', 'Street', 'Diversity' , 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Entrepreneurship', 'Thunder ', 'Eccentricity', 'Village', 'Feelings', 'Electrified', 'Fascinating', 'Gratitude', 'Cinnamon', 'Victory', 'Loyalty', 'Bicycle', 'Corn', 'Success', 'Emotion', 'Education', 'Waterfall', 'Freedom', 'Dentistry', 'Integrity', 'Sofa', 'Research', 'Cheese', 'Enlightenment', 'Generosity', 'Passion', 'Earth ', 'Poetry', 'Sacrifice', 'Resilience', 'Wonderfully', 'Energetic', 'Window']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("The word:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Guess a letter: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("¡Correct!")
                    else:
                        intentos_restantes -= 1
                        print("Incorrect. you have left ", intentos_restantes, "Attempts.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Won! You have guessed the word:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("You lost! The word was:", palabra)
            print("Player 1:")
            jugar_ahorcado()
            print("Player 2:")
            jugar_ahorcado()


    if Multiplayer == 1:
        b=int(input("Please select a difficulty:\n1.easy\n2.medium\n3.hard" ))
        if b == 1:

            

            lista = ['Companionship', 'Biscuit', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Bright', 'Stillness', 'Science', 'Red', 'Pencil', 'Cinnamon ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Amazement', 'Meat', 'Clock', 'Silence', 'Heading', 'Snow', 'Bow ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Style', 'Enchanting', 'Sport', 'Literature', 'Heal', 'Serenity', 'Dog', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Career', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt' , 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen ', 'Volunteering', 'Hope', 'Intriguing', 'Enlightening', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Momentous', 'Splendid', 'Hill', 'Environment', 'Refreshment', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photograph', ' Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Village', 'Glow' , 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Fall in love', 'Cake', 'Sport', 'Reinvention', 'Cocoa', 'Gastronomy', ' Symmetry', 'Brotherhood', 'Engineer', 'Fulfilling', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer' , 'Money', 'Yogurt', 'Drive', 'Computer', 'Juice', 'Fire', 'Backwind', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', ' Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work', 'Attractive', 'Optimism', 'Sculpture', 'Gastronomy' , 'Beautiful', 'Glasses', 'Football', 'Prodigy', 'Experience', 'Get Inspired', 'Sea', 'Mystic', 'Nature', 'Write', 'Fantasy', 'Walking', ' Joy', 'Universe', 'Te', 'Expression', 'Laughter', 'Spirituality', 'Rejuvenation', 'River', 'Happiness', 'Banana', 'Yoga', 'Emotional', 'Opportunity' , 'Home', 'Pen', 'Patience', 'Road', 'Joy', 'Trust', 'Attraction', 'Dreaming', 'Awesome', 'Birthday', 'Nightmare', 'Amazement', ' Clouds', 'Gorgeous', 'Balance', 'Collaboration', 'Space', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing', 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', 'Jump', ' Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motorcycle', 'Beer', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday', 'Rhythm' , 'Sky', 'Pastime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', 'Analysis', ' Exquisite', 'Heritage', 'Television', 'Pants', 'Gift', 'Reward', 'Desert', 'Nobility', 'Connection', 'Story', 'School', 'Maturity', 'Rain' , 'Lamp', 'Spontaneity', 'Claro', 'Constellation', 'Mouse', 'Culture', 'Fresh', 'Inspiration', 'Sun Guitar', 'Book', 'Diversity', 'Risk', 'orange', 'University', 'Determination', 'Festival', 'Kindness', 'Breeze', 'Hamster', 'Highway', 'Wonder', 'Bee', 'Hope', 'Knowledge', 'Hill ', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Sincerity', 'Sustainability', 'Kindness', 'Jungle', 'Shine', 'Focus ', 'Dog', 'University', 'Nurture', 'Discovery', 'Garden', 'Skill', 'Train', 'Lighting', 'Planning', 'Arena', 'Tennis', 'Lush', 'Overcoming', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendence', 'Divorced', 'Harmony', 'Empathy', 'Respect', 'Clock', 'Friend', 'Thread ', 'Yogurt', 'School', 'Serendipity', 'Airplane', 'Game', 'Laughter', 'Plenitude', 'Sculpture', 'Hospital', 'Smile', 'Captivating', 'Intuition', 'Experience', 'Splendor', 'Ocean', 'Prosperity', 'Consciousness', 'Tequila', 'Anniversary', 'Seduction', 'Leadership', 'Outstanding', 'Courteous', 'Renewal', 'Valley ', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter ', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Giggle', 'Reward', 'Adventure', 'Pepper', 'Spring', 'Exhilarating', 'Ceiling', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Consciousness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competence', 'Tree ', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate' , 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization ', 'Perseverance', 'Career', 'Dazed', 'Dreams', 'Originality', 'Extraordinary', 'Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Mindful', 'Icy', 'Evening ', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivator', 'Inclusion', 'apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos ', 'Earth', 'Butterfly', 'Amazement', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Candid', 'Cellular', 'Vegetable', 'Invigorating', 'Whisky', 'Theatre', 'Landscape', 'Feeling', 'Fortress', 'Street', 'Door ', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Kindness', 'Peace', 'Sustainability', 'Persistence', 'City', 'Architecture', 'Party', 'Dreamer', 'Nursing', 'Fortitude', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple ', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', 'Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Family', 'Vibrant', 'Environment', 'Learning', 'Lawyer', ' Entertainment', 'Values', 'Shop', 'Acceptance', 'Family', 'Knowledge', 'Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Explorer', 'Beach' , 'Sofa', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment', 'Mountain', 'Forest', 'Survival', 'Incomparable', 'Hospital', 'Garden', ' Legend', 'Avenue', 'Sublimation', 'Salad', 'Fate', 'Kind', 'Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart' , 'Constancy', 'Chair', 'Master', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive', ' Violin', 'Goal', 'Plethoric', 'Thought', 'Lamp', 'Enjoyment', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning' , 'Angry', 'Honesty', 'Fantastic', 'Enthralling', 'Surprised', 'Transformation', 'Summer', 'Math', 'Calm', 'Motorbike', 'Lion', 'Comfort', ' Souvenir', 'Company', 'Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic' , 'Medical', 'Memory', 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', ' Climb', 'Sugar', 'Equality', 'Evening', 'Soda', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning' , 'Generous', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Amazing', 'Heady', 'Promising', 'Education', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Determination', 'Thunder', 'Energy' , 'Dragonfly', 'Incredible', 'Solution', 'Lightning', 'Tiger', 'Cat', 'Dedication', 'Boat', 'Exaltation', 'Rinsing', 'Passion', 'Ecology', 'Honesty', 'Emotion', 'Running', 'Technology', 'Revealing', 'Explore', 'Dazzle', 'Awakening', 'Wine', 'Sadness', 'History', 'Moon', 'Study' , 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', 'History', 'Wellness', 'Blessing', 'Fun', 'Exploration', 'Nature', 'Restlessness', 'Melody', 'Philanthropy', 'Scarf', 'Invigorating', 'Sing ', 'Tolerance', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage', 'Football', 'Community', 'Gorgeous', 'Rainbow', 'Encouragement', 'Discipline', 'Nursery', 'Great', 'Longing', 'Dedication', 'Music', 'Profitable' , 'Health', 'Door', 'Business', 'Window', 'Sensitivity', 'Train', 'Stability', 'Giraffe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Exhilaration', 'Picturesque', 'Metropolis', 'Renewal', 'Shocking', 'Journey', 'Courage', 'Shocking' , 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinse', 'Enchantment', 'Religion', 'Idyllic', 'Generation', 'Transcendent', 'Feather', 'Wheat', 'Satisfaction', 'Business', 'Reptile', 'Fruit', 'Table', 'Organization', 'Stars', 'Printer', 'Goal', 'Motivation', 'Fearlessness', 'Balance', 'Tranquility' , 'Birthday', 'Divorced', 'Shine', 'Collaboration', 'Green', 'Dessert', 'Melancholy', 'Photography', 'Laughter', 'Aroma', 'Fruit', 'Relaxation', 'Dew', 'Vigor', 'Generosity', 'Smile', 'Autumn', 'Impulse', 'Charm', 'Enchanting', 'Salty', 'Lucidity', 'Blue', 'Enthusiasm', 'Beauty ', 'Growth', 'Sugar', 'Oil', 'Rainbow', 'Travel', 'Hamster', 'Surprise', 'Adventurer', 'Coffee', 'Amazing', 'Curiosity', 'Thread', 'Fish', 'Remarkable', 'Understanding', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Purpose' , 'Kiss', 'Feline', 'Single', 'Peace', 'Technician', 'Pear', 'Dance', 'Hummingbird', 'Airplane', 'Lake', 'Intoxicating', 'Euphoric', 'Exciting', 'Festivity', 'Sun', 'Pants', 'Jump', 'Boat', 'Ceramic', 'Interdependence', 'Play', 'Eloquence', 'Stimulated', 'Essence', 'Salty' , 'Trust', 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Desire', 'Noble', 'Spirituality', 'Cooperation', 'Harmony', 'Pepper', 'Improvement', 'Sublime', 'Dazzling', 'Tradition', 'Flexibility', 'Universe', 'Giraffe', 'Street', 'Diversity' , 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Entrepreneurship', 'Thunder ', 'Eccentricity', 'Village', 'Feelings', 'Electrified', 'Fascinating', 'Gratitude', 'Cinnamon', 'Victory', 'Loyalty', 'Bicycle', 'Corn', 'Success', 'Emotion', 'Education', 'Waterfall', 'Freedom', 'Dentistry', 'Integrity', 'Sofa', 'Research', 'Cheese', 'Enlightenment', 'Generosity', 'Passion', 'Earth ', 'Poetry', 'Sacrifice', 'Resilience', 'Wonderfully', 'Energetic', 'Window']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("The word:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Guess a letter: ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("¡Correct!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrect. you have left ", intentos_restantes, "Attempts.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Won! You have guessed the word:", palabra)
                        break

                if intentos_restantes == 0:
                        print("You lost! The word was:", palabra)


            print("Player 1:")
            jugar_ahorcado()

            
        elif b == 2:


            lista = ['Companionship', 'Biscuit', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Bright', 'Stillness', 'Science', 'Red', 'Pencil', 'Cinnamon ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Amazement', 'Meat', 'Clock', 'Silence', 'Heading', 'Snow', 'Bow ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Style', 'Enchanting', 'Sport', 'Literature', 'Heal', 'Serenity', 'Dog', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Career', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt' , 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen ', 'Volunteering', 'Hope', 'Intriguing', 'Enlightening', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Momentous', 'Splendid', 'Hill', 'Environment', 'Refreshment', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photograph', ' Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Village', 'Glow' , 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Fall in love', 'Cake', 'Sport', 'Reinvention', 'Cocoa', 'Gastronomy', ' Symmetry', 'Brotherhood', 'Engineer', 'Fulfilling', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer' , 'Money', 'Yogurt', 'Drive', 'Computer', 'Juice', 'Fire', 'Backwind', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', ' Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work', 'Attractive', 'Optimism', 'Sculpture', 'Gastronomy' , 'Beautiful', 'Glasses', 'Football', 'Prodigy', 'Experience', 'Get Inspired', 'Sea', 'Mystic', 'Nature', 'Write', 'Fantasy', 'Walking', ' Joy', 'Universe', 'Te', 'Expression', 'Laughter', 'Spirituality', 'Rejuvenation', 'River', 'Happiness', 'Banana', 'Yoga', 'Emotional', 'Opportunity' , 'Home', 'Pen', 'Patience', 'Road', 'Joy', 'Trust', 'Attraction', 'Dreaming', 'Awesome', 'Birthday', 'Nightmare', 'Amazement', ' Clouds', 'Gorgeous', 'Balance', 'Collaboration', 'Space', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing', 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', 'Jump', ' Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motorcycle', 'Beer', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday', 'Rhythm' , 'Sky', 'Pastime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', 'Analysis', ' Exquisite', 'Heritage', 'Television', 'Pants', 'Gift', 'Reward', 'Desert', 'Nobility', 'Connection', 'Story', 'School', 'Maturity', 'Rain' , 'Lamp', 'Spontaneity', 'Claro', 'Constellation', 'Mouse', 'Culture', 'Fresh', 'Inspiration', 'Sun Guitar', 'Book', 'Diversity', 'Risk', 'orange', 'University', 'Determination', 'Festival', 'Kindness', 'Breeze', 'Hamster', 'Highway', 'Wonder', 'Bee', 'Hope', 'Knowledge', 'Hill ', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Sincerity', 'Sustainability', 'Kindness', 'Jungle', 'Shine', 'Focus ', 'Dog', 'University', 'Nurture', 'Discovery', 'Garden', 'Skill', 'Train', 'Lighting', 'Planning', 'Arena', 'Tennis', 'Lush', 'Overcoming', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendence', 'Divorced', 'Harmony', 'Empathy', 'Respect', 'Clock', 'Friend', 'Thread ', 'Yogurt', 'School', 'Serendipity', 'Airplane', 'Game', 'Laughter', 'Plenitude', 'Sculpture', 'Hospital', 'Smile', 'Captivating', 'Intuition', 'Experience', 'Splendor', 'Ocean', 'Prosperity', 'Consciousness', 'Tequila', 'Anniversary', 'Seduction', 'Leadership', 'Outstanding', 'Courteous', 'Renewal', 'Valley ', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter ', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Giggle', 'Reward', 'Adventure', 'Pepper', 'Spring', 'Exhilarating', 'Ceiling', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Consciousness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competence', 'Tree ', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate' , 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization ', 'Perseverance', 'Career', 'Dazed', 'Dreams', 'Originality', 'Extraordinary', 'Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Mindful', 'Icy', 'Evening ', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivator', 'Inclusion', 'apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos ', 'Earth', 'Butterfly', 'Amazement', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Candid', 'Cellular', 'Vegetable', 'Invigorating', 'Whisky', 'Theatre', 'Landscape', 'Feeling', 'Fortress', 'Street', 'Door ', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Kindness', 'Peace', 'Sustainability', 'Persistence', 'City', 'Architecture', 'Party', 'Dreamer', 'Nursing', 'Fortitude', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple ', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', 'Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Family', 'Vibrant', 'Environment', 'Learning', 'Lawyer', ' Entertainment', 'Values', 'Shop', 'Acceptance', 'Family', 'Knowledge', 'Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Explorer', 'Beach' , 'Sofa', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment', 'Mountain', 'Forest', 'Survival', 'Incomparable', 'Hospital', 'Garden', 'Legend', 'Avenue', 'Sublimation', 'Salad', 'Fate', 'Kind', 'Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart' , 'Constancy', 'Chair', 'Master', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive', ' Violin', 'Goal', 'Plethoric', 'Thought', 'Lamp', 'Enjoyment', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning' , 'Angry', 'Honesty', 'Fantastic', 'Enthralling', 'Surprised', 'Transformation', 'Summer', 'Math', 'Calm', 'Motorbike', 'Lion', 'Comfort', ' Souvenir', 'Company', 'Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic' , 'Medical', 'Memory', 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', ' Climb', 'Sugar', 'Equality', 'Evening', 'Soda', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning' , 'Generous', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Amazing', 'Heady', 'Promising', 'Education', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Determination', 'Thunder', 'Energy' , 'Dragonfly', 'Incredible', 'Solution', 'Lightning', 'Tiger', 'Cat', 'Dedication', 'Boat', 'Exaltation', 'Rinsing', 'Passion', 'Ecology', 'Honesty', 'Emotion', 'Running', 'Technology', 'Revealing', 'Explore', 'Dazzle', 'Awakening', 'Wine', 'Sadness', 'History', 'Moon', 'Study' , 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', 'History', 'Wellness', 'Blessing', 'Fun', 'Exploration', 'Nature', 'Restlessness', 'Melody', 'Philanthropy', 'Scarf', 'Invigorating', 'Sing ', 'Tolerance', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage', 'Football', 'Community', 'Gorgeous', 'Rainbow', 'Encouragement', 'Discipline', 'Nursery', 'Great', 'Longing', 'Dedication', 'Music', 'Profitable' , 'Health', 'Door', 'Business', 'Window', 'Sensitivity', 'Train', 'Stability', 'Giraffe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Exhilaration', 'Picturesque', 'Metropolis', 'Renewal', 'Shocking', 'Journey', 'Courage', 'Shocking' , 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinse', 'Enchantment', 'Religion', 'Idyllic', 'Generation', 'Transcendent', 'Feather', 'Wheat', 'Satisfaction', 'Business', 'Reptile', 'Fruit', 'Table', 'Organization', 'Stars', 'Printer', 'Goal', 'Motivation', 'Fearlessness', 'Balance', 'Tranquility' , 'Birthday', 'Divorced', 'Shine', 'Collaboration', 'Green', 'Dessert', 'Melancholy', 'Photography', 'Laughter', 'Aroma', 'Fruit', 'Relaxation', 'Dew', 'Vigor', 'Generosity', 'Smile', 'Autumn', 'Impulse', 'Charm', 'Enchanting', 'Salty', 'Lucidity', 'Blue', 'Enthusiasm', 'Beauty ', 'Growth', 'Sugar', 'Oil', 'Rainbow', 'Travel', 'Hamster', 'Surprise', 'Adventurer', 'Coffee', 'Amazing', 'Curiosity', 'Thread', 'Fish', 'Remarkable', 'Understanding', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Purpose' , 'Kiss', 'Feline', 'Single', 'Peace', 'Technician', 'Pear', 'Dance', 'Hummingbird', 'Airplane', 'Lake', 'Intoxicating', 'Euphoric', 'Exciting', 'Festivity', 'Sun', 'Pants', 'Jump', 'Boat', 'Ceramic', 'Interdependence', 'Play', 'Eloquence', 'Stimulated', 'Essence', 'Salty' , 'Trust', 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Desire', 'Noble', 'Spirituality', 'Cooperation', 'Harmony', 'Pepper', 'Improvement', 'Sublime', 'Dazzling', 'Tradition', 'Flexibility', 'Universe', 'Giraffe', 'Street', 'Diversity' , 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Entrepreneurship', 'Thunder ', 'Eccentricity', 'Village', 'Feelings', 'Electrified', 'Fascinating', 'Gratitude', 'Cinnamon', 'Victory', 'Loyalty', 'Bicycle', 'Corn', 'Success', 'Emotion', 'Education', 'Waterfall', 'Freedom', 'Dentistry', 'Integrity', 'Sofa', 'Research', 'Cheese', 'Enlightenment', 'Generosity', 'Passion', 'Earth ', 'Poetry', 'Sacrifice', 'Resilience', 'Wonderfully', 'Energetic', 'Window']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("The word:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Guess a letter: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("¡Correct!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrect. you have left ", intentos_restantes, "Attempts.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Won! You have guessed the word: ", palabra)
                        break

                    if intentos_restantes == 0:
                        print("You lost! The word was:", palabra)


            print("Player 1:")
            jugar_ahorcado()


        elif b == 3:

            import random
            lista = ['Companionship', 'Biscuit', 'Hug', 'Loyalty', 'Enriching', 'Autumn', 'Ambition', 'Bright', 'Stillness', 'Science', 'Red', 'Pencil', 'Cinnamon ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Growth', 'Tenacity', 'Excited', 'Literature', 'Party', 'Hope', 'Inspiring', 'Innovation', 'Creativity', 'Electrifying', 'Amazement', 'Meat', 'Clock', 'Silence', 'Heading', 'Snow', 'Bow ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystery', 'Glasses', 'Communication', 'Revelation', 'Acclaimed', 'Tears', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Style', 'Enchanting', 'Sport', 'Literature', 'Heal', 'Serenity', 'Dog', 'Refreshing', 'Wonder', 'Office', 'Relaxation', 'Style', 'Vitality', 'Conservation', 'Dignity', 'Redemption', 'Swimming', 'Rest', 'Exciting', 'Career', 'Oatmeal', 'Achievement', 'Applauded', 'Time', 'Yogurt' , 'Ocean', 'Cinema', 'Village', 'Satisfaction', 'Coffee', 'Guitar', 'Water', 'Chalk', 'Responsibility', 'Prestige', 'Pleasure', 'Crying', 'Optimism', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Pen ', 'Volunteering', 'Hope', 'Intriguing', 'Enlightening', 'Uplifting', 'Impressionism', 'Tuesday', 'Architecture', 'Progress', 'Stars', 'Community', 'Momentous', 'Splendid', 'Hill', 'Environment', 'Refreshment', 'Dusk', 'Innocence', 'Corn', 'Courage', 'Surprised', 'Exercise', 'Wait', 'Photograph', ' Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Village', 'Glow' , 'Reflection', 'Dance', 'Feather', 'Dedication', 'Delight', 'Laughter', 'Fall in love', 'Cake', 'Sport', 'Reinvention', 'Cocoa', 'Gastronomy', ' Symmetry', 'Brotherhood', 'Engineer', 'Fulfilling', 'Cocoa', 'Aspiration', 'Authenticity', 'Humility', 'Intrigue', 'Pleasure', 'Consciousness', 'Exhilarating', 'Lawyer' , 'Money', 'Yogurt', 'Drive', 'Computer', 'Juice', 'Fire', 'Backwind', 'Fascination', 'Planet', 'Happiness', 'Cat', 'Greatness', ' Elephant', 'Sweet', 'Rabbit', 'Plain', 'Bitter', 'Water', 'Book', 'Winter', 'Work', 'Attractive', 'Optimism', 'Sculpture', 'Gastronomy' , 'Beautiful', 'Glasses', 'Football', 'Prodigy', 'Experience', 'Get Inspired', 'Sea', 'Mystic', 'Nature', 'Write', 'Fantasy', 'Walking', ' Joy', 'Universe', 'Te', 'Expression', 'Laughter', 'Spirituality', 'Rejuvenation', 'River', 'Happiness', 'Banana', 'Yoga', 'Emotional', 'Opportunity' , 'Home', 'Pen', 'Patience', 'Road', 'Joy', 'Trust', 'Attraction', 'Dreaming', 'Awesome', 'Birthday', 'Nightmare', 'Amazement', ' Clouds', 'Gorgeous', 'Balance', 'Collaboration', 'Space', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing', 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', 'Jump', ' Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motorcycle', 'Beer', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday', 'Rhythm' , 'Sky', 'Pastime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', 'Analysis', ' Exquisite', 'Heritage', 'Television', 'Pants', 'Gift', 'Reward', 'Desert', 'Nobility', 'Connection', 'Story', 'School', 'Maturity', 'Rain' , 'Lamp', 'Spontaneity', 'Claro', 'Constellation', 'Mouse', 'Culture', 'Fresh', 'Inspiration', 'Sun Guitar', 'Book', 'Diversity', 'Risk', 'orange', 'University', 'Determination', 'Festival', 'Kindness', 'Breeze', 'Hamster', 'Highway', 'Wonder', 'Bee', 'Hope', 'Knowledge', 'Hill ', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Sincerity', 'Sustainability', 'Kindness', 'Jungle', 'Shine', 'Focus ', 'Dog', 'University', 'Nurture', 'Discovery', 'Garden', 'Skill', 'Train', 'Lighting', 'Planning', 'Arena', 'Tennis', 'Lush', 'Overcoming', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendence', 'Divorced', 'Harmony', 'Empathy', 'Respect', 'Clock', 'Friend', 'Thread ', 'Yogurt', 'School', 'Serendipity', 'Airplane', 'Game', 'Laughter', 'Plenitude', 'Sculpture', 'Hospital', 'Smile', 'Captivating', 'Intuition', 'Experience', 'Splendor', 'Ocean', 'Prosperity', 'Consciousness', 'Tequila', 'Anniversary', 'Seduction', 'Leadership', 'Outstanding', 'Courteous', 'Renewal', 'Valley ', 'Morning', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change', 'Basketball', 'Professionalism', 'Inspiration', 'Exciting', 'Wonderful', 'Success', 'Solidarity', 'Renaissance', 'Vegetable', 'Dress', 'Shells', 'Sea', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter ', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Giggle', 'Reward', 'Adventure', 'Pepper', 'Spring', 'Exhilarating', 'Ceiling', 'Sugar', 'Dress', 'Calm', 'Freedom', 'Tranquility', 'Consciousness', 'Anniversary', 'Moments', 'Happy', 'Galaxy', 'Authenticity', 'Meditation', 'Competence', 'Tree ', 'Nutrition', 'Glorious', 'Science', 'Elevation', 'Air', 'Justice', 'Efficiency', 'Charm', 'Fire', 'Tradition', 'Oasis', 'Surprise', 'Teaching', 'Joy', 'Dreaming', 'Overflowing', 'Adventure', 'Television', 'Shoes', 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Anger', 'Passionate' , 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', 'Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Enthusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting', 'Pasta', 'Exuberance', 'Equity', 'Cinema', 'Perseverance', 'Organization ', 'Perseverance', 'Career', 'Dazed', 'Dreams', 'Originality', 'Extraordinary', 'Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellphone', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Mindful', 'Icy', 'Evening ', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-esteem', 'Joy', 'Tea', 'Notebook', 'Painting', 'Rice', 'Enrichment', 'Motivator', 'Inclusion', 'apple', 'Mindfulness', 'Respect', 'Exploration', 'Neighbor', 'Wealth', 'Transformation', 'Painting', 'Joy', 'Chaos ', 'Earth', 'Butterfly', 'Amazement', 'Exotic', 'Sustainability', 'Passionate', 'Vanilla', 'Fascinating', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Candid', 'Cellular', 'Vegetable', 'Invigorating', 'Whisky', 'Theatre', 'Landscape', 'Feeling', 'Fortress', 'Street', 'Door ', 'Meat', 'Mystery', 'Theater', 'Pasta', 'Saturday', 'Commitment', 'Triumph', 'Fascinating', 'Courage', 'Wheat', 'Kindness', 'Peace', 'Sustainability', 'Persistence', 'City', 'Architecture', 'Party', 'Dreamer', 'Nursing', 'Fortitude', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple ', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', 'Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Family', 'Vibrant', 'Environment', 'Learning', 'Lawyer', ' Entertainment', 'Values', 'Shop', 'Acceptance', 'Family', 'Knowledge', 'Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Explorer', 'Beach' , 'Sofa', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment', 'Mountain', 'Forest', 'Survival', 'Incomparable', 'Hospital', 'Garden', ' Legend', 'Avenue', 'Sublimation', 'Salad', 'Fate', 'Kind', 'Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart' , 'Constancy', 'Chair', 'Master', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive', ' Violin', 'Goal', 'Plethoric', 'Thought', 'Lamp', 'Enjoyment', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning' , 'Angry', 'Honesty', 'Fantastic', 'Enthralling', 'Surprised', 'Transformation', 'Summer', 'Math', 'Calm', 'Motorbike', 'Lion', 'Comfort', ' Souvenir', 'Company', 'Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic' , 'Medical', 'Memory', 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', ' Climb', 'Sugar', 'Equality', 'Evening', 'Soda', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning' , 'Generous', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Amazing', 'Heady', 'Promising', 'Education', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Determination', 'Thunder', 'Energy' , 'Dragonfly', 'Incredible', 'Solution', 'Lightning', 'Tiger', 'Cat', 'Dedication', 'Boat', 'Exaltation', 'Rinsing', 'Passion', 'Ecology', 'Honesty', 'Emotion', 'Running', 'Technology', 'Revealing', 'Explore', 'Dazzle', 'Awakening', 'Wine', 'Sadness', 'History', 'Moon', 'Study' , 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', 'History', 'Wellness', 'Blessing', 'Fun', 'Exploration', 'Nature', 'Restlessness', 'Melody', 'Philanthropy', 'Scarf', 'Invigorating', 'Sing ', 'Tolerance', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage', 'Football', 'Community', 'Gorgeous', 'Rainbow', 'Encouragement', 'Discipline', 'Nursery', 'Great', 'Longing', 'Dedication', 'Music', 'Profitable' , 'Health', 'Door', 'Business', 'Window', 'Sensitivity', 'Train', 'Stability', 'Giraffe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Exhilaration', 'Picturesque', 'Metropolis', 'Renewal', 'Shocking', 'Journey', 'Courage', 'Shocking' , 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinse', 'Enchantment', 'Religion', 'Idyllic', 'Generation', 'Transcendent', 'Feather', 'Wheat', 'Satisfaction', 'Business', 'Reptile', 'Fruit', 'Table', 'Organization', 'Stars', 'Printer', 'Goal', 'Motivation', 'Fearlessness', 'Balance', 'Tranquility' , 'Birthday', 'Divorced', 'Shine', 'Collaboration', 'Green', 'Dessert', 'Melancholy', 'Photography', 'Laughter', 'Aroma', 'Fruit', 'Relaxation', 'Dew', 'Vigor', 'Generosity', 'Smile', 'Autumn', 'Impulse', 'Charm', 'Enchanting', 'Salty', 'Lucidity', 'Blue', 'Enthusiasm', 'Beauty ', 'Growth', 'Sugar', 'Oil', 'Rainbow', 'Travel', 'Hamster', 'Surprise', 'Adventurer', 'Coffee', 'Amazing', 'Curiosity', 'Thread', 'Fish', 'Remarkable', 'Understanding', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Purpose' , 'Kiss', 'Feline', 'Single', 'Peace', 'Technician', 'Pear', 'Dance', 'Hummingbird', 'Airplane', 'Lake', 'Intoxicating', 'Euphoric', 'Exciting', 'Festivity', 'Sun', 'Pants', 'Jump', 'Boat', 'Ceramic', 'Interdependence', 'Play', 'Eloquence', 'Stimulated', 'Essence', 'Salty' , 'Trust', 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Desire', 'Noble', 'Spirituality', 'Cooperation', 'Harmony', 'Pepper', 'Improvement', 'Sublime', 'Dazzling', 'Tradition', 'Flexibility', 'Universe', 'Giraffe', 'Street', 'Diversity' , 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Entrepreneurship', 'Thunder ', 'Eccentricity', 'Village', 'Feelings', 'Electrified', 'Fascinating', 'Gratitude', 'Cinnamon', 'Victory', 'Loyalty', 'Bicycle', 'Corn', 'Success', 'Emotion', 'Education', 'Waterfall', 'Freedom', 'Dentistry', 'Integrity', 'Sofa', 'Research', 'Cheese', 'Enlightenment', 'Generosity', 'Passion', 'Earth ', 'Poetry', 'Sacrifice', 'Resilience', 'Wonderfully', 'Energetic', 'Window']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("The word:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Guess a letter: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("¡Correct!")
                    else:
                        intentos_restantes -= 1
                        print("Incorrect. you have left ", intentos_restantes, "Attempts.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Won! You have guessed the word:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("You lost! The word was:", palabra)
            print("Player 1:")
            jugar_ahorcado()

elif a == 3:
    Multiplayer = int(input("seleziona il numero di giocatori 1-2:"))
    if Multiplayer == 2:
        b=int(input("Seleziona una difficoltà:\n1.facile\n2.medio\n3.difficile" ))
        if b == 1:

            lista = ['Compagnia', 'Biscotto', 'Abbraccio', 'Lealtà', 'Arricchimento', 'Autunno', 'Ambizione', 'Brillante', 'Immobilità', 'Scienza', 'Rosso', 'Matita', 'Cannella ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Crowth', 'Tenacity', 'Excited', 'Literature', 'Festa', 'Speranza', 'Ispiratrice', 'Innovazione', 'Creatività', 'Elettrizzante', 'Stupore', 'Carne', 'Orologio', 'Silenzio', 'Intestazione', 'Neve', 'Bow ', 'Capacità', 'Sonno', 'Arancione', 'Meraviglia', 'Cordialità', 'Cambiamento', 'Computer', 'Musica', 'Uva', 'Epifania', 'Corsa', 'Gratitudine', 'Leadership', 'Mistero', 'Occhiali', 'Comunicazione', 'Rivelazione', 'Acclamato', 'Lacrime', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Stile', 'Incantevole', 'Sport', 'Letteratura', 'Guarigione', 'Serenità', 'Cane', 'Rinfrescante', 'Meraviglia', 'Ufficio', 'Relax', 'Stile' , 'Vitalità', 'Conservazione', 'Dignità', 'Redenzione', 'Nuoto', 'Riposo', 'Emozionante', 'Carriera', 'Farina d avena', 'Risultato', 'Applauso', 'Tempo', 'Yogurt', 'Oceano', 'Cinema', 'Villaggio', 'Soddisfazione', 'Caffè', 'Chitarra', 'Acqua', 'Gesso', 'Responsabilità', 'Prestigio', 'Piacere', 'Piangere ', 'Ottimismo', 'Squadra', 'Uguaglianza', 'Vaniglia', 'Danza', 'Autobus', 'Hobby', 'Immaginazione', 'Irresistibile', 'Bagliore', 'Adattabilità', 'Apprezzamento', 'Penna', 'Volontariato', 'Speranza', 'Intrigante', 'Illuminante', 'Edificante', 'Impressionismo', 'Martedì', 'Architettura', 'Progresso', 'Stelle', 'Comunità', 'Indimenticabile ', 'Splendido', 'Collina', 'Ambiente', 'Rinfresco', 'Crepuscolo', 'Innocenza', 'Mais', 'Coraggio', 'Sorpresa', 'Esercizio', 'Aspetta', 'Fotografia', ' Realtà', 'Bello', 'Incanto', 'Crepuscolo', 'Deserto', 'Impressionato', 'Triste', 'Petrolio', 'Euforia', 'Pittura', 'Benessere', 'Villaggio', 'Bagliore ' , 'Riflesso', 'Danza', 'Piuma', 'Dedica', 'Delizia', 'Risate', 'Innamorarsi', 'Torta', 'Sport', 'Reinvenzione', 'Cacao', 'Gastronomia ', ' Simmetria', 'Fratellanza', 'Ingegnere', 'Soddisfacente', 'Cacao', 'Aspirazione', 'Autenticità', 'Umiltà', 'Intrigo', 'Piacere', 'Coscienza', 'Esilarante', 'Avvocato', 'Soldi', 'Yogurt', 'Drive', 'Computer', 'Succo', 'Fuoco', 'Backwind', 'Fascino', 'Pianeta', 'Felicità', 'Gatto', 'Grandezza ', ' Elefante', 'Dolce', 'Coniglio', 'Semplice', 'Amaro', 'Acqua', 'Libro', 'Inverno', 'Lavoro', 'Attraente', 'Ottimismo', 'Scultura', 'Gastronomia', 'Bello', 'Occhiali', 'Calcio', 'Prodigio', 'Esperienza', 'Ispirati', 'Mare', 'Mistico', 'Natura', 'Scrivi', 'Fantasia', 'Camminare', 'Gioia', 'Universo', 'Te', 'Espressione', 'Risate', 'Spiritualità', 'Ringiovanimento', 'Fiume', 'Felicità', 'Banana', 'Yoga', 'Emotivo' , 'Opportunità', 'Casa', 'Penna', 'Pazienza', 'Strada', 'Gioia', 'Fiducia', 'Attrazione', 'Sogno', 'Fantastico', 'Compleanno', 'Incubo', 'Stupore', 'Nuvole', 'Splendido', 'Equilibrio', 'Collaborazione', 'Spazio', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing' , 'Empatia' , 'Interni', 'Sbalorditivo', 'Indimenticabile', 'Ammirazione', 'Bellissimo', 'Montagna', 'Realizzazione', 'Acido', 'Scrivi', 'Abbraccio', 'Ceramica', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motocycle', 'Birra', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passtime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Sfida', 'Nuoto', 'Analisi', 'Squisito', 'Patrimonio', 'Televisione', 'Pantaloni', 'Regalo', 'Ricompensa', 'Desolazione', 'Nobiltà', 'Connessione', ' Story', 'School', 'Maturity', 'Rain', 'Lamp', 'Spontaneity', 'Clear', 'Constellation', 'Topo', 'Culture', 'Fresh', 'Ispiration', 'Sun Guitar ', 'Libro', 'Diversità', 'Rischio', 'Orange', 'Università', 'Determinazione', 'Festival', 'Gentilezza', 'Brezza', 'Criceto', 'Autostrada', 'Meraviglia', 'Ape', 'Speranza', 'Conoscenza', 'Collina', 'Criceto', 'Delicato', 'Energia', 'Radiante', 'Medicina', 'Nuoto', 'Cascata', 'Affettuoso', 'Caldo' , 'Friendship', 'Telephone', 'Rabbit', 'Lunedì', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning' , 'Sincerità', 'Sostenibilità', 'Gentilezza', 'Giungla', 'Leggerezza', 'Focus', 'Cane', 'Università', 'Nutrizione', 'Scoperta', 'Giardino', 'Abilità', ' Treno ', 'Illuminazione', 'Pianificazione', 'Sabbia', 'Tennis', 'Lussureggiante', 'Superamento', 'Estate', 'Ingegnere', 'Foresta', 'Tempesta', 'Trascendenza', 'Divorziato' , 'Armonia', 'Empatia', 'Rispetto', 'Orologio', 'Amico', 'Filo', 'Yogurt', 'Scuola', 'Serendipità', 'Aeroplano', 'Gioco', 'Risate', 'Pienezza', 'Scultura', 'Ospedale', 'Sorriso', 'Accattivante', 'Intuizione', 'Esperienza', 'Splendore', 'Oceano', 'Prosperità', 'Coscienza', 'Tequila', 'Anniversario' , 'Seduzione', 'Comando', 'Eccezionale', 'Cortese', 'Rinnovamento', 'Valle', 'Mattina', 'Notte', 'Inverno', 'Carisma', 'Evoluzione', 'Flessibilità', 'Energia', 'Cambiamento', 'Basket', 'Professionalità', 'Ispirazione', 'Emozionante', 'Meraviglioso', 'Successo', 'Solidarietà', 'Rinascimento', 'Verdure', 'Vestito', 'Conchiglie' , 'Mare', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Laughing', 'Gratefulness', ' Avventura', 'Pepe', 'Primavera', 'Esilarante', 'Soffitto', 'Zucchero', 'Vestito', 'Calma', 'Libertà', 'Tranquillità', 'Coscienza', 'Anniversario', 'Momenti ' , 'Felice', 'Galaxy', 'Autenticità', 'Meditazione', 'Competenza', 'Albero', 'Nutrizione', 'Glorioso', 'Scienza', 'Elevazione', 'Aria', 'Giustizia', ' Efficienza', 'Fascino', 'Fuoco', 'Tradizione', 'Oasi', 'Sorpresa', 'Insegnamento', 'Gioia', 'Sogno', 'Traboccante', 'Avventura', 'Televisione', 'Scarpe ' , 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Angry', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', ' Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Entusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting ' , 'Pasta', 'Esuberanza', 'Equità', 'Cinema', 'Perseveranza', 'Organizzazione', 'Perseveranza', 'Carriera', 'Incredibile', 'Sogni', 'Originalità', 'Straordinario', ' Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking ' , 'Serenità', 'Fantasia', 'Emancipatore', 'Attento', 'Gelato', 'Sera', 'Matita', 'Appartenenza', 'Imprenditorialità', 'Integrità', 'Innocenza', 'Armonia' , 'Autostima', 'Gioia', 'Tè', 'Quaderno', 'Pittura', 'Riso', 'Arricchimento', 'Motivatore', 'Inclusione', 'mela', 'Consapevolezza', 'Rispetto' , 'Esplorazione', 'Vicino', 'Ricchezza', 'Trasformazione', 'Dipinto', 'Gioia', 'Caos', 'Terra', 'Farfalla', 'Ammirazione', 'Esotico', 'Sostenibilità', 'Passionate', 'Vanilla', 'Affascinante', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Vegetable', 'Invigorating' , 'Whisky', 'Teatro', 'Paesaggio', 'Sensazione', 'Fortezza', 'Strada', 'Porta', 'Carne', 'Mistero', 'Teatro', 'Pasta', 'Sabato', 'Engagement', 'Trionfo', 'Affascinante', 'Coraggio', 'Grano', 'Gentilezza', 'Pace', 'Sostenibilità', 'Persistenza', 'Città', 'Architettura', 'Festa', 'Sognatore' , 'Nursing' , 'Forza', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', ' Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt' , 'Compagno' , 'Famiglia', 'Vivace', 'Ambiente', 'Apprendimento', 'Avvocato', 'Intrattenimento', 'Valori', 'Negozio', 'Accettazione', 'Famiglia', 'Conoscenza', ' Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Scout', 'Beach', 'Couch', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment' , 'Montagna', 'Foresta', 'Sopravvivenza', 'Incomparabile', 'Ospedale', 'Giardino', 'Leggenda', 'Viale', 'Sublimazione', 'Insalata', 'Destino', 'Gentile', ' Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart', 'Steady', 'Chair', 'Master', 'Auto', 'Metropolis', 'Vibrant', 'Tea', 'Subjugated', 'Brush', 'Harmony', 'Plenitude', 'Addictive', 'Violin', 'Meta', ' Plethoric', 'Thought', 'Lamp', 'Enjoy', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning', 'Angry', 'Honesty' , 'Fantastico', 'Accattivante', 'Sorpresa', 'Trasformazione', 'Estate', 'Matematica', 'Calma', 'Motociclista', 'Leone', 'Comfort', 'Ricordi', 'Compagnia', ' Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic', 'Medical', 'Souvenir' , 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', ' Equality', 'Evening', 'Soft Drink', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning', 'Generous ', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elefant', 'Widower', 'Noon', ' Felice', 'Incredibile', 'Inebriante', 'Promettente', 'Istruzione', 'Sushi', 'Paziente', 'Innovazione', 'Agricoltura', 'Determinazione', 'Tuono', 'Energia', 'Libellula ' , 'Incredibile', 'Soluzione', 'Fulmine', 'Tigre', 'Gatto', 'Dedizione', 'Barca', 'Esaltazione', 'Risciacquo', 'Passione', 'Ecologia', 'Onestà', ' Emotion', 'Running', 'Technology', 'Revealer', 'Explore', 'Glare', 'Awakening', 'Wine', 'Trisness', 'Story', 'Luna', 'Study', 'Health ' , 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', ' Storia', 'Benessere', 'Benedizione', 'Divertimento', 'Esplorazione', 'Natura', 'Irrequietezza', 'Melodia', 'Filantropia', 'Sciarpa', 'Rinvigorente', 'Canto', 'Tolleranza', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage ', ' Calcio', 'Comunità', 'Splendido', 'Arcobaleno', 'Incoraggiamento', 'Disciplina', 'Nursery', 'Fantastico', 'Desiderio', 'Dedizione', 'Musica', 'Utile', 'Salute', 'Porta', 'Affari', 'Finestra', 'Sensibilità', 'Treno', 'Stabilità', 'Giraffa', 'Enigma', 'Coraggio', 'Succo', 'Magia', 'Parola ', 'Unico', 'Pianoforte', 'Metropoli', 'Produttività', 'Euforia', 'Pittoresco', 'Metropoli', 'Rinfrescante', 'Shock', 'Viaggio', 'Coraggio', 'Scioccante', 'Canta', 'Celebrazione', 'Cooperazione', 'Danza', 'Risciacquo', 'Incanto', 'Religione', 'Idillio', 'Generazione', 'Trascendente', 'Piuma', 'Grano', 'Soddisfazione ', ' Affari', 'Rettile', 'Frutta', 'Tavolo', 'Organizzazione', 'Stelle', 'Stampante', 'Obiettivo', 'Motivazione', 'Impavidità', 'Equilibrio', 'Calma', 'Compleanno' , 'Divorziato', 'Brillante', 'Collaborazione', 'Verde', 'Dessert', 'Malinconia', 'Fotografia', 'Risate', 'Aroma', 'Frutta', 'Relax', 'Rugiada ', 'Vigore', 'Generosità', 'Sorriso', 'Autunno', 'Impulso', 'Fascino', 'Incantevole', 'Salato', 'Lucidità', 'Blu', 'Entusiasmo', 'Bellezza', 'Crescita', 'Zucchero', 'Petrolio', 'Arcobaleno', 'Viaggio', 'Criceto', 'Sorpresa', 'Avventuriero', 'Caffè', 'Incredibile', 'Curiosità', 'Filo', 'Pesce ', ' Notevole', 'Comprensione', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Scopo' , 'Bacio', 'Felino', 'Singolo', 'Pace', 'Tecnico', 'Pera', 'Danza', 'Colibrì', 'Aereo', 'Lago', 'Inebriante', 'Euforico', 'Emozionante', 'Festival', 'Sole', 'Pantaloni', 'Salto', 'Barca', 'Ceramica', 'Interdipendenza', 'Gioco', 'Eloquenza', 'Stimolato', 'Essenza', 'Salto' , 'Trust' , 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Wish', 'Noble', ' Spiritualità', 'Cooperazione', 'Armonia', 'Pepe', 'Miglioramento', 'Sublime', 'Accecante', 'Tradizione', 'Flessibilità', 'Universo', 'Giraffa', 'Strada', 'Diversità' , 'Act' , ' Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt' , 'Dawn', 'Abbondanza', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Enterpreneurship', ' Tuono', 'Eccentricità', 'Villaggio', 'Sentimenti', 'Elettrificato', 'Affascinante', 'Gratitudine', 'Cannella', 'Vittoria', 'Lealtà', 'Bicicletta', 'Mais', 'Successo' , 'Emozione', 'Istruzione', 'Cascata', 'Libertà', 'Odontoiatria', 'Integrità', 'Divano', 'Ricerca', 'Formaggio', 'Illuminazione', 'Generosità', 'Passione', 'Terra', 'Poesia', 'Sacrificio', 'Resilienza', 'Meravigliosamente', 'Energia', 'Finestra']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Parola:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("indovina una lettera: ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Corretto!")

                    else:
                        intentos_restantes -= 1
                        print("Errato. Te ne sei andato", intentos_restantes, "tentativi.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Vinto! hai indovinato la parola:", palabra)
                        break

                if intentos_restantes == 0:
                        print("Hai perso! la parola era:", palabra)


            print("Giocatore 1:")
            jugar_ahorcado()
            print("Giocatore 2:")
            jugar_ahorcado()
            
        elif b == 2:


            lista = ['Compagnia', 'Biscotto', 'Abbraccio', 'Lealtà', 'Arricchimento', 'Autunno', 'Ambizione', 'Brillante', 'Immobilità', 'Scienza', 'Rosso', 'Matita', 'Cannella ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Crowth', 'Tenacity', 'Excited', 'Literature', 'Festa', 'Speranza', 'Ispiratrice', 'Innovazione', 'Creatività', 'Elettrizzante', 'Stupore', 'Carne', 'Orologio', 'Silenzio', 'Intestazione', 'Neve', 'Bow ', 'Capacità', 'Sonno', 'Arancione', 'Meraviglia', 'Cordialità', 'Cambiamento', 'Computer', 'Musica', 'Uva', 'Epifania', 'Corsa', 'Gratitudine', 'Leadership', 'Mistero', 'Occhiali', 'Comunicazione', 'Rivelazione', 'Acclamato', 'Lacrime', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Stile', 'Incantevole', 'Sport', 'Letteratura', 'Guarigione', 'Serenità', 'Cane', 'Rinfrescante', 'Meraviglia', 'Ufficio', 'Relax', 'Stile' , 'Vitalità', 'Conservazione', 'Dignità', 'Redenzione', 'Nuoto', 'Riposo', 'Emozionante', 'Carriera', 'Farina d avena', 'Risultato', 'Applauso', 'Tempo', 'Yogurt', 'Oceano', 'Cinema', 'Villaggio', 'Soddisfazione', 'Caffè', 'Chitarra', 'Acqua', 'Gesso', 'Responsabilità', 'Prestigio', 'Piacere', 'Piangere ', 'Ottimismo', 'Squadra', 'Uguaglianza', 'Vaniglia', 'Danza', 'Autobus', 'Hobby', 'Immaginazione', 'Irresistibile', 'Bagliore', 'Adattabilità', 'Apprezzamento', 'Penna', 'Volontariato', 'Speranza', 'Intrigante', 'Illuminante', 'Edificante', 'Impressionismo', 'Martedì', 'Architettura', 'Progresso', 'Stelle', 'Comunità', 'Indimenticabile ', 'Splendido', 'Collina', 'Ambiente', 'Rinfresco', 'Crepuscolo', 'Innocenza', 'Mais', 'Coraggio', 'Sorpresa', 'Esercizio', 'Aspetta', 'Fotografia', ' Realtà', 'Bello', 'Incanto', 'Crepuscolo', 'Deserto', 'Impressionato', 'Triste', 'Petrolio', 'Euforia', 'Pittura', 'Benessere', 'Villaggio', 'Bagliore ' , 'Riflesso', 'Danza', 'Piuma', 'Dedica', 'Delizia', 'Risate', 'Innamorarsi', 'Torta', 'Sport', 'Reinvenzione', 'Cacao', 'Gastronomia ', ' Simmetria', 'Fratellanza', 'Ingegnere', 'Soddisfacente', 'Cacao', 'Aspirazione', 'Autenticità', 'Umiltà', 'Intrigo', 'Piacere', 'Coscienza', 'Esilarante', 'Avvocato', 'Soldi', 'Yogurt', 'Drive', 'Computer', 'Succo', 'Fuoco', 'Backwind', 'Fascino', 'Pianeta', 'Felicità', 'Gatto', 'Grandezza ', ' Elefante', 'Dolce', 'Coniglio', 'Semplice', 'Amaro', 'Acqua', 'Libro', 'Inverno', 'Lavoro', 'Attraente', 'Ottimismo', 'Scultura', 'Gastronomia', 'Bello', 'Occhiali', 'Calcio', 'Prodigio', 'Esperienza', 'Ispirati', 'Mare', 'Mistico', 'Natura', 'Scrivi', 'Fantasia', 'Camminare', 'Gioia', 'Universo', 'Te', 'Espressione', 'Risate', 'Spiritualità', 'Ringiovanimento', 'Fiume', 'Felicità', 'Banana', 'Yoga', 'Emotivo' , 'Opportunità', 'Casa', 'Penna', 'Pazienza', 'Strada', 'Gioia', 'Fiducia', 'Attrazione', 'Sogno', 'Fantastico', 'Compleanno', 'Incubo', 'Stupore', 'Nuvole', 'Splendido', 'Equilibrio', 'Collaborazione', 'Spazio', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing' , 'Empatia' , 'Interni', 'Sbalorditivo', 'Indimenticabile', 'Ammirazione', 'Bellissimo', 'Montagna', 'Realizzazione', 'Acido', 'Scrivi', 'Abbraccio', 'Ceramica', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motocycle', 'Birra', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passtime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Sfida', 'Nuoto', 'Analisi', 'Squisito', 'Patrimonio', 'Televisione', 'Pantaloni', 'Regalo', 'Ricompensa', 'Desolazione', 'Nobiltà', 'Connessione', ' Story', 'School', 'Maturity', 'Rain', 'Lamp', 'Spontaneity', 'Clear', 'Constellation', 'Topo', 'Culture', 'Fresh', 'Ispiration', 'Sun Guitar ', 'Libro', 'Diversità', 'Rischio', 'Orange', 'Università', 'Determinazione', 'Festival', 'Gentilezza', 'Brezza', 'Criceto', 'Autostrada', 'Meraviglia', 'Ape', 'Speranza', 'Conoscenza', 'Collina', 'Criceto', 'Delicato', 'Energia', 'Radiante', 'Medicina', 'Nuoto', 'Cascata', 'Affettuoso', 'Caldo' , 'Friendship', 'Telephone', 'Rabbit', 'Lunedì', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning' , 'Sincerità', 'Sostenibilità', 'Gentilezza', 'Giungla', 'Leggerezza', 'Focus', 'Cane', 'Università', 'Nutrizione', 'Scoperta', 'Giardino', 'Abilità', ' Treno ', 'Illuminazione', 'Pianificazione', 'Sabbia', 'Tennis', 'Lussureggiante', 'Superamento', 'Estate', 'Ingegnere', 'Foresta', 'Tempesta', 'Trascendenza', 'Divorziato' , 'Armonia', 'Empatia', 'Rispetto', 'Orologio', 'Amico', 'Filo', 'Yogurt', 'Scuola', 'Serendipità', 'Aeroplano', 'Gioco', 'Risate', 'Pienezza', 'Scultura', 'Ospedale', 'Sorriso', 'Accattivante', 'Intuizione', 'Esperienza', 'Splendore', 'Oceano', 'Prosperità', 'Coscienza', 'Tequila', 'Anniversario' , 'Seduzione', 'Comando', 'Eccezionale', 'Cortese', 'Rinnovamento', 'Valle', 'Mattina', 'Notte', 'Inverno', 'Carisma', 'Evoluzione', 'Flessibilità', 'Energia', 'Cambiamento', 'Basket', 'Professionalità', 'Ispirazione', 'Emozionante', 'Meraviglioso', 'Successo', 'Solidarietà', 'Rinascimento', 'Verdure', 'Vestito', 'Conchiglie' , 'Mare', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Laughing', 'Gratefulness', ' Avventura', 'Pepe', 'Primavera', 'Esilarante', 'Soffitto', 'Zucchero', 'Vestito', 'Calma', 'Libertà', 'Tranquillità', 'Coscienza', 'Anniversario', 'Momenti ' , 'Felice', 'Galaxy', 'Autenticità', 'Meditazione', 'Competenza', 'Albero', 'Nutrizione', 'Glorioso', 'Scienza', 'Elevazione', 'Aria', 'Giustizia', ' Efficienza', 'Fascino', 'Fuoco', 'Tradizione', 'Oasi', 'Sorpresa', 'Insegnamento', 'Gioia', 'Sogno', 'Traboccante', 'Avventura', 'Televisione', 'Scarpe ' , 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Angry', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', ' Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Entusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting ' , 'Pasta', 'Esuberanza', 'Equità', 'Cinema', 'Perseveranza', 'Organizzazione', 'Perseveranza', 'Carriera', 'Incredibile', 'Sogni', 'Originalità', 'Straordinario', ' Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking ' , 'Serenità', 'Fantasia', 'Emancipatore', 'Attento', 'Gelato', 'Sera', 'Matita', 'Appartenenza', 'Imprenditorialità', 'Integrità', 'Innocenza', 'Armonia' , 'Autostima', 'Gioia', 'Tè', 'Quaderno', 'Pittura', 'Riso', 'Arricchimento', 'Motivatore', 'Inclusione', 'mela', 'Consapevolezza', 'Rispetto' , 'Esplorazione', 'Vicino', 'Ricchezza', 'Trasformazione', 'Dipinto', 'Gioia', 'Caos', 'Terra', 'Farfalla', 'Ammirazione', 'Esotico', 'Sostenibilità', 'Passionate', 'Vanilla', 'Affascinante', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Vegetable', 'Invigorating' , 'Whisky', 'Teatro', 'Paesaggio', 'Sensazione', 'Fortezza', 'Strada', 'Porta', 'Carne', 'Mistero', 'Teatro', 'Pasta', 'Sabato', 'Engagement', 'Trionfo', 'Affascinante', 'Coraggio', 'Grano', 'Gentilezza', 'Pace', 'Sostenibilità', 'Persistenza', 'Città', 'Architettura', 'Festa', 'Sognatore' , 'Nursing' , 'Forza', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', ' Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt' , 'Compagno' , 'Famiglia', 'Vivace', 'Ambiente', 'Apprendimento', 'Avvocato', 'Intrattenimento', 'Valori', 'Negozio', 'Accettazione', 'Famiglia', 'Conoscenza', ' Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Scout', 'Beach', 'Couch', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment' , 'Montagna', 'Foresta', 'Sopravvivenza', 'Incomparabile', 'Ospedale', 'Giardino', 'Leggenda', 'Viale', 'Sublimazione', 'Insalata', 'Destino', 'Gentile', ' Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart', 'Steady', 'Chair', 'Master', 'Auto', 'Metropolis', 'Vibrant', 'Tea', 'Subjugated', 'Brush', 'Harmony', 'Plenitude', 'Addictive', 'Violin', 'Meta', ' Plethoric', 'Thought', 'Lamp', 'Enjoy', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning', 'Angry', 'Honesty' , 'Fantastico', 'Accattivante', 'Sorpresa', 'Trasformazione', 'Estate', 'Matematica', 'Calma', 'Motociclista', 'Leone', 'Comfort', 'Ricordi', 'Compagnia', ' Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic', 'Medical', 'Souvenir' , 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', ' Equality', 'Evening', 'Soft Drink', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning', 'Generous ', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elefant', 'Widower', 'Noon', ' Felice', 'Incredibile', 'Inebriante', 'Promettente', 'Istruzione', 'Sushi', 'Paziente', 'Innovazione', 'Agricoltura', 'Determinazione', 'Tuono', 'Energia', 'Libellula ' , 'Incredibile', 'Soluzione', 'Fulmine', 'Tigre', 'Gatto', 'Dedizione', 'Barca', 'Esaltazione', 'Risciacquo', 'Passione', 'Ecologia', 'Onestà', ' Emotion', 'Running', 'Technology', 'Revealer', 'Explore', 'Glare', 'Awakening', 'Wine', 'Trisness', 'Story', 'Luna', 'Study', 'Health ' , 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', ' Storia', 'Benessere', 'Benedizione', 'Divertimento', 'Esplorazione', 'Natura', 'Irrequietezza', 'Melodia', 'Filantropia', 'Sciarpa', 'Rinvigorente', 'Canto', 'Tolleranza', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage ', ' Calcio', 'Comunità', 'Splendido', 'Arcobaleno', 'Incoraggiamento', 'Disciplina', 'Nursery', 'Fantastico', 'Desiderio', 'Dedizione', 'Musica', 'Utile', 'Salute', 'Porta', 'Affari', 'Finestra', 'Sensibilità', 'Treno', 'Stabilità', 'Giraffa', 'Enigma', 'Coraggio', 'Succo', 'Magia', 'Parola ', 'Unico', 'Pianoforte', 'Metropoli', 'Produttività', 'Euforia', 'Pittoresco', 'Metropoli', 'Rinfrescante', 'Shock', 'Viaggio', 'Coraggio', 'Scioccante', 'Canta', 'Celebrazione', 'Cooperazione', 'Danza', 'Risciacquo', 'Incanto', 'Religione', 'Idillio', 'Generazione', 'Trascendente', 'Piuma', 'Grano', 'Soddisfazione ', ' Affari', 'Rettile', 'Frutta', 'Tavolo', 'Organizzazione', 'Stelle', 'Stampante', 'Obiettivo', 'Motivazione', 'Impavidità', 'Equilibrio', 'Calma', 'Compleanno' , 'Divorziato', 'Brillante', 'Collaborazione', 'Verde', 'Dessert', 'Malinconia', 'Fotografia', 'Risate', 'Aroma', 'Frutta', 'Relax', 'Rugiada ', 'Vigore', 'Generosità', 'Sorriso', 'Autunno', 'Impulso', 'Fascino', 'Incantevole', 'Salato', 'Lucidità', 'Blu', 'Entusiasmo', 'Bellezza', 'Crescita', 'Zucchero', 'Petrolio', 'Arcobaleno', 'Viaggio', 'Criceto', 'Sorpresa', 'Avventuriero', 'Caffè', 'Incredibile', 'Curiosità', 'Filo', 'Pesce ', ' Notevole', 'Comprensione', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Scopo' , 'Bacio', 'Felino', 'Singolo', 'Pace', 'Tecnico', 'Pera', 'Danza', 'Colibrì', 'Aereo', 'Lago', 'Inebriante', 'Euforico', 'Emozionante', 'Festival', 'Sole', 'Pantaloni', 'Salto', 'Barca', 'Ceramica', 'Interdipendenza', 'Gioco', 'Eloquenza', 'Stimolato', 'Essenza', 'Salto' , 'Trust' , 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Wish', 'Noble', ' Spiritualità', 'Cooperazione', 'Armonia', 'Pepe', 'Miglioramento', 'Sublime', 'Accecante', 'Tradizione', 'Flessibilità', 'Universo', 'Giraffa', 'Strada', 'Diversità' , 'Act' , ' Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt' , 'Dawn', 'Abbondanza', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Enterpreneurship', ' Tuono', 'Eccentricità', 'Villaggio', 'Sentimenti', 'Elettrificato', 'Affascinante', 'Gratitudine', 'Cannella', 'Vittoria', 'Lealtà', 'Bicicletta', 'Mais', 'Successo' , 'Emozione', 'Istruzione', 'Cascata', 'Libertà', 'Odontoiatria', 'Integrità', 'Divano', 'Ricerca', 'Formaggio', 'Illuminazione', 'Generosità', 'Passione', 'Terra', 'Poesia', 'Sacrificio', 'Resilienza', 'Meravigliosamente', 'Energia', 'Finestra']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Parola:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("indovina una lettera: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Corretto!")

                    else:
                        intentos_restantes -= 1
                        print("Errato. Te ne sei andato", intentos_restantes, "tentativi.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Vinto! hai indovinato la parola:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Hai perso! la parola era:", palabra)


            print("Giocatore 1:")
            jugar_ahorcado()
            print("Giocatore 2:")
            jugar_ahorcado()


        elif b == 3:

            import random
            lista = ['Compagnia', 'Biscotto', 'Abbraccio', 'Lealtà', 'Arricchimento', 'Autunno', 'Ambizione', 'Brillante', 'Immobilità', 'Scienza', 'Rosso', 'Matita', 'Cannella ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Crowth', 'Tenacity', 'Excited', 'Literature', 'Festa', 'Speranza', 'Ispiratrice', 'Innovazione', 'Creatività', 'Elettrizzante', 'Stupore', 'Carne', 'Orologio', 'Silenzio', 'Intestazione', 'Neve', 'Bow ', 'Capacità', 'Sonno', 'Arancione', 'Meraviglia', 'Cordialità', 'Cambiamento', 'Computer', 'Musica', 'Uva', 'Epifania', 'Corsa', 'Gratitudine', 'Leadership', 'Mistero', 'Occhiali', 'Comunicazione', 'Rivelazione', 'Acclamato', 'Lacrime', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Stile', 'Incantevole', 'Sport', 'Letteratura', 'Guarigione', 'Serenità', 'Cane', 'Rinfrescante', 'Meraviglia', 'Ufficio', 'Relax', 'Stile' , 'Vitalità', 'Conservazione', 'Dignità', 'Redenzione', 'Nuoto', 'Riposo', 'Emozionante', 'Carriera', 'Farina d avena', 'Risultato', 'Applauso', 'Tempo', 'Yogurt', 'Oceano', 'Cinema', 'Villaggio', 'Soddisfazione', 'Caffè', 'Chitarra', 'Acqua', 'Gesso', 'Responsabilità', 'Prestigio', 'Piacere', 'Piangere ', 'Ottimismo', 'Squadra', 'Uguaglianza', 'Vaniglia', 'Danza', 'Autobus', 'Hobby', 'Immaginazione', 'Irresistibile', 'Bagliore', 'Adattabilità', 'Apprezzamento', 'Penna', 'Volontariato', 'Speranza', 'Intrigante', 'Illuminante', 'Edificante', 'Impressionismo', 'Martedì', 'Architettura', 'Progresso', 'Stelle', 'Comunità', 'Indimenticabile ', 'Splendido', 'Collina', 'Ambiente', 'Rinfresco', 'Crepuscolo', 'Innocenza', 'Mais', 'Coraggio', 'Sorpresa', 'Esercizio', 'Aspetta', 'Fotografia', ' Realtà', 'Bello', 'Incanto', 'Crepuscolo', 'Deserto', 'Impressionato', 'Triste', 'Petrolio', 'Euforia', 'Pittura', 'Benessere', 'Villaggio', 'Bagliore ' , 'Riflesso', 'Danza', 'Piuma', 'Dedica', 'Delizia', 'Risate', 'Innamorarsi', 'Torta', 'Sport', 'Reinvenzione', 'Cacao', 'Gastronomia ', ' Simmetria', 'Fratellanza', 'Ingegnere', 'Soddisfacente', 'Cacao', 'Aspirazione', 'Autenticità', 'Umiltà', 'Intrigo', 'Piacere', 'Coscienza', 'Esilarante', 'Avvocato', 'Soldi', 'Yogurt', 'Drive', 'Computer', 'Succo', 'Fuoco', 'Backwind', 'Fascino', 'Pianeta', 'Felicità', 'Gatto', 'Grandezza ', ' Elefante', 'Dolce', 'Coniglio', 'Semplice', 'Amaro', 'Acqua', 'Libro', 'Inverno', 'Lavoro', 'Attraente', 'Ottimismo', 'Scultura', 'Gastronomia', 'Bello', 'Occhiali', 'Calcio', 'Prodigio', 'Esperienza', 'Ispirati', 'Mare', 'Mistico', 'Natura', 'Scrivi', 'Fantasia', 'Camminare', 'Gioia', 'Universo', 'Te', 'Espressione', 'Risate', 'Spiritualità', 'Ringiovanimento', 'Fiume', 'Felicità', 'Banana', 'Yoga', 'Emotivo' , 'Opportunità', 'Casa', 'Penna', 'Pazienza', 'Strada', 'Gioia', 'Fiducia', 'Attrazione', 'Sogno', 'Fantastico', 'Compleanno', 'Incubo', 'Stupore', 'Nuvole', 'Splendido', 'Equilibrio', 'Collaborazione', 'Spazio', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing' , 'Empatia' , 'Interni', 'Sbalorditivo', 'Indimenticabile', 'Ammirazione', 'Bellissimo', 'Montagna', 'Realizzazione', 'Acido', 'Scrivi', 'Abbraccio', 'Ceramica', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motocycle', 'Birra', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passtime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Sfida', 'Nuoto', 'Analisi', 'Squisito', 'Patrimonio', 'Televisione', 'Pantaloni', 'Regalo', 'Ricompensa', 'Desolazione', 'Nobiltà', 'Connessione', ' Story', 'School', 'Maturity', 'Rain', 'Lamp', 'Spontaneity', 'Clear', 'Constellation', 'Topo', 'Culture', 'Fresh', 'Ispiration', 'Sun Guitar ', 'Libro', 'Diversità', 'Rischio', 'Orange', 'Università', 'Determinazione', 'Festival', 'Gentilezza', 'Brezza', 'Criceto', 'Autostrada', 'Meraviglia', 'Ape', 'Speranza', 'Conoscenza', 'Collina', 'Criceto', 'Delicato', 'Energia', 'Radiante', 'Medicina', 'Nuoto', 'Cascata', 'Affettuoso', 'Caldo' , 'Friendship', 'Telephone', 'Rabbit', 'Lunedì', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning' , 'Sincerità', 'Sostenibilità', 'Gentilezza', 'Giungla', 'Leggerezza', 'Focus', 'Cane', 'Università', 'Nutrizione', 'Scoperta', 'Giardino', 'Abilità', ' Treno ', 'Illuminazione', 'Pianificazione', 'Sabbia', 'Tennis', 'Lussureggiante', 'Superamento', 'Estate', 'Ingegnere', 'Foresta', 'Tempesta', 'Trascendenza', 'Divorziato' , 'Armonia', 'Empatia', 'Rispetto', 'Orologio', 'Amico', 'Filo', 'Yogurt', 'Scuola', 'Serendipità', 'Aeroplano', 'Gioco', 'Risate', 'Pienezza', 'Scultura', 'Ospedale', 'Sorriso', 'Accattivante', 'Intuizione', 'Esperienza', 'Splendore', 'Oceano', 'Prosperità', 'Coscienza', 'Tequila', 'Anniversario' , 'Seduzione', 'Comando', 'Eccezionale', 'Cortese', 'Rinnovamento', 'Valle', 'Mattina', 'Notte', 'Inverno', 'Carisma', 'Evoluzione', 'Flessibilità', 'Energia', 'Cambiamento', 'Basket', 'Professionalità', 'Ispirazione', 'Emozionante', 'Meraviglioso', 'Successo', 'Solidarietà', 'Rinascimento', 'Verdure', 'Vestito', 'Conchiglie' , 'Mare', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Laughing', 'Gratefulness', ' Avventura', 'Pepe', 'Primavera', 'Esilarante', 'Soffitto', 'Zucchero', 'Vestito', 'Calma', 'Libertà', 'Tranquillità', 'Coscienza', 'Anniversario', 'Momenti ' , 'Felice', 'Galaxy', 'Autenticità', 'Meditazione', 'Competenza', 'Albero', 'Nutrizione', 'Glorioso', 'Scienza', 'Elevazione', 'Aria', 'Giustizia', ' Efficienza', 'Fascino', 'Fuoco', 'Tradizione', 'Oasi', 'Sorpresa', 'Insegnamento', 'Gioia', 'Sogno', 'Traboccante', 'Avventura', 'Televisione', 'Scarpe ' , 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Angry', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', ' Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Entusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting ' , 'Pasta', 'Esuberanza', 'Equità', 'Cinema', 'Perseveranza', 'Organizzazione', 'Perseveranza', 'Carriera', 'Incredibile', 'Sogni', 'Originalità', 'Straordinario', ' Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking ' , 'Serenità', 'Fantasia', 'Emancipatore', 'Attento', 'Gelato', 'Sera', 'Matita', 'Appartenenza', 'Imprenditorialità', 'Integrità', 'Innocenza', 'Armonia' , 'Autostima', 'Gioia', 'Tè', 'Quaderno', 'Pittura', 'Riso', 'Arricchimento', 'Motivatore', 'Inclusione', 'mela', 'Consapevolezza', 'Rispetto' , 'Esplorazione', 'Vicino', 'Ricchezza', 'Trasformazione', 'Dipinto', 'Gioia', 'Caos', 'Terra', 'Farfalla', 'Ammirazione', 'Esotico', 'Sostenibilità', 'Passionate', 'Vanilla', 'Affascinante', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Vegetable', 'Invigorating' , 'Whisky', 'Teatro', 'Paesaggio', 'Sensazione', 'Fortezza', 'Strada', 'Porta', 'Carne', 'Mistero', 'Teatro', 'Pasta', 'Sabato', 'Engagement', 'Trionfo', 'Affascinante', 'Coraggio', 'Grano', 'Gentilezza', 'Pace', 'Sostenibilità', 'Persistenza', 'Città', 'Architettura', 'Festa', 'Sognatore' , 'Nursing' , 'Forza', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', ' Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt' , 'Compagno' , 'Famiglia', 'Vivace', 'Ambiente', 'Apprendimento', 'Avvocato', 'Intrattenimento', 'Valori', 'Negozio', 'Accettazione', 'Famiglia', 'Conoscenza', ' Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Scout', 'Beach', 'Couch', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment' , 'Montagna', 'Foresta', 'Sopravvivenza', 'Incomparabile', 'Ospedale', 'Giardino', 'Leggenda', 'Viale', 'Sublimazione', 'Insalata', 'Destino', 'Gentile', ' Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart', 'Steady', 'Chair', 'Master', 'Auto', 'Metropolis', 'Vibrant', 'Tea', 'Subjugated', 'Brush', 'Harmony', 'Plenitude', 'Addictive', 'Violin', 'Meta', ' Plethoric', 'Thought', 'Lamp', 'Enjoy', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning', 'Angry', 'Honesty' , 'Fantastico', 'Accattivante', 'Sorpresa', 'Trasformazione', 'Estate', 'Matematica', 'Calma', 'Motociclista', 'Leone', 'Comfort', 'Ricordi', 'Compagnia', ' Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic', 'Medical', 'Souvenir' , 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', ' Equality', 'Evening', 'Soft Drink', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning', 'Generous ', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elefant', 'Widower', 'Noon', ' Felice', 'Incredibile', 'Inebriante', 'Promettente', 'Istruzione', 'Sushi', 'Paziente', 'Innovazione', 'Agricoltura', 'Determinazione', 'Tuono', 'Energia', 'Libellula ' , 'Incredibile', 'Soluzione', 'Fulmine', 'Tigre', 'Gatto', 'Dedizione', 'Barca', 'Esaltazione', 'Risciacquo', 'Passione', 'Ecologia', 'Onestà', ' Emotion', 'Running', 'Technology', 'Revealer', 'Explore', 'Glare', 'Awakening', 'Wine', 'Trisness', 'Story', 'Luna', 'Study', 'Health ' , 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', ' Storia', 'Benessere', 'Benedizione', 'Divertimento', 'Esplorazione', 'Natura', 'Irrequietezza', 'Melodia', 'Filantropia', 'Sciarpa', 'Rinvigorente', 'Canto', 'Tolleranza', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage ', ' Calcio', 'Comunità', 'Splendido', 'Arcobaleno', 'Incoraggiamento', 'Disciplina', 'Nursery', 'Fantastico', 'Desiderio', 'Dedizione', 'Musica', 'Utile', 'Salute', 'Porta', 'Affari', 'Finestra', 'Sensibilità', 'Treno', 'Stabilità', 'Giraffa', 'Enigma', 'Coraggio', 'Succo', 'Magia', 'Parola ', 'Unico', 'Pianoforte', 'Metropoli', 'Produttività', 'Euforia', 'Pittoresco', 'Metropoli', 'Rinfrescante', 'Shock', 'Viaggio', 'Coraggio', 'Scioccante', 'Canta', 'Celebrazione', 'Cooperazione', 'Danza', 'Risciacquo', 'Incanto', 'Religione', 'Idillio', 'Generazione', 'Trascendente', 'Piuma', 'Grano', 'Soddisfazione ', ' Affari', 'Rettile', 'Frutta', 'Tavolo', 'Organizzazione', 'Stelle', 'Stampante', 'Obiettivo', 'Motivazione', 'Impavidità', 'Equilibrio', 'Calma', 'Compleanno' , 'Divorziato', 'Brillante', 'Collaborazione', 'Verde', 'Dessert', 'Malinconia', 'Fotografia', 'Risate', 'Aroma', 'Frutta', 'Relax', 'Rugiada ', 'Vigore', 'Generosità', 'Sorriso', 'Autunno', 'Impulso', 'Fascino', 'Incantevole', 'Salato', 'Lucidità', 'Blu', 'Entusiasmo', 'Bellezza', 'Crescita', 'Zucchero', 'Petrolio', 'Arcobaleno', 'Viaggio', 'Criceto', 'Sorpresa', 'Avventuriero', 'Caffè', 'Incredibile', 'Curiosità', 'Filo', 'Pesce ', ' Notevole', 'Comprensione', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Scopo' , 'Bacio', 'Felino', 'Singolo', 'Pace', 'Tecnico', 'Pera', 'Danza', 'Colibrì', 'Aereo', 'Lago', 'Inebriante', 'Euforico', 'Emozionante', 'Festival', 'Sole', 'Pantaloni', 'Salto', 'Barca', 'Ceramica', 'Interdipendenza', 'Gioco', 'Eloquenza', 'Stimolato', 'Essenza', 'Salto' , 'Trust' , 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Wish', 'Noble', ' Spiritualità', 'Cooperazione', 'Armonia', 'Pepe', 'Miglioramento', 'Sublime', 'Accecante', 'Tradizione', 'Flessibilità', 'Universo', 'Giraffa', 'Strada', 'Diversità' , 'Act' , ' Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt' , 'Dawn', 'Abbondanza', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Enterpreneurship', ' Tuono', 'Eccentricità', 'Villaggio', 'Sentimenti', 'Elettrificato', 'Affascinante', 'Gratitudine', 'Cannella', 'Vittoria', 'Lealtà', 'Bicicletta', 'Mais', 'Successo' , 'Emozione', 'Istruzione', 'Cascata', 'Libertà', 'Odontoiatria', 'Integrità', 'Divano', 'Ricerca', 'Formaggio', 'Illuminazione', 'Generosità', 'Passione', 'Terra', 'Poesia', 'Sacrificio', 'Resilienza', 'Meravigliosamente', 'Energia', 'Finestra']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Parola:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("indovina una lettera: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Corretto!")
                    else:
                        intentos_restantes -= 1
                        print("Errato. Te ne sei andato", intentos_restantes, "tentativi.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Vinto! hai indovinato la parola:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Hai perso! la parola era:", palabra)
            print("Giocatore 1:")
            jugar_ahorcado()
            print("Giocatore 2:")
            jugar_ahorcado()


    if Multiplayer == 1:
        b=int(input("Seleziona una difficoltà:\n1.facile\n2.medio\n3.difficile" ))
        if b == 1:

            lista = ['Compagnia', 'Biscotto', 'Abbraccio', 'Lealtà', 'Arricchimento', 'Autunno', 'Ambizione', 'Brillante', 'Immobilità', 'Scienza', 'Rosso', 'Matita', 'Cannella ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Crowth', 'Tenacity', 'Excited', 'Literature', 'Festa', 'Speranza', 'Ispiratrice', 'Innovazione', 'Creatività', 'Elettrizzante', 'Stupore', 'Carne', 'Orologio', 'Silenzio', 'Intestazione', 'Neve', 'Bow ', 'Capacità', 'Sonno', 'Arancione', 'Meraviglia', 'Cordialità', 'Cambiamento', 'Computer', 'Musica', 'Uva', 'Epifania', 'Corsa', 'Gratitudine', 'Leadership', 'Mistero', 'Occhiali', 'Comunicazione', 'Rivelazione', 'Acclamato', 'Lacrime', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Stile', 'Incantevole', 'Sport', 'Letteratura', 'Guarigione', 'Serenità', 'Cane', 'Rinfrescante', 'Meraviglia', 'Ufficio', 'Relax', 'Stile' , 'Vitalità', 'Conservazione', 'Dignità', 'Redenzione', 'Nuoto', 'Riposo', 'Emozionante', 'Carriera', 'Farina d avena', 'Risultato', 'Applauso', 'Tempo', 'Yogurt', 'Oceano', 'Cinema', 'Villaggio', 'Soddisfazione', 'Caffè', 'Chitarra', 'Acqua', 'Gesso', 'Responsabilità', 'Prestigio', 'Piacere', 'Piangere ', 'Ottimismo', 'Squadra', 'Uguaglianza', 'Vaniglia', 'Danza', 'Autobus', 'Hobby', 'Immaginazione', 'Irresistibile', 'Bagliore', 'Adattabilità', 'Apprezzamento', 'Penna', 'Volontariato', 'Speranza', 'Intrigante', 'Illuminante', 'Edificante', 'Impressionismo', 'Martedì', 'Architettura', 'Progresso', 'Stelle', 'Comunità', 'Indimenticabile ', 'Splendido', 'Collina', 'Ambiente', 'Rinfresco', 'Crepuscolo', 'Innocenza', 'Mais', 'Coraggio', 'Sorpresa', 'Esercizio', 'Aspetta', 'Fotografia', ' Realtà', 'Bello', 'Incanto', 'Crepuscolo', 'Deserto', 'Impressionato', 'Triste', 'Petrolio', 'Euforia', 'Pittura', 'Benessere', 'Villaggio', 'Bagliore ' , 'Riflesso', 'Danza', 'Piuma', 'Dedica', 'Delizia', 'Risate', 'Innamorarsi', 'Torta', 'Sport', 'Reinvenzione', 'Cacao', 'Gastronomia ', ' Simmetria', 'Fratellanza', 'Ingegnere', 'Soddisfacente', 'Cacao', 'Aspirazione', 'Autenticità', 'Umiltà', 'Intrigo', 'Piacere', 'Coscienza', 'Esilarante', 'Avvocato', 'Soldi', 'Yogurt', 'Drive', 'Computer', 'Succo', 'Fuoco', 'Backwind', 'Fascino', 'Pianeta', 'Felicità', 'Gatto', 'Grandezza ', ' Elefante', 'Dolce', 'Coniglio', 'Semplice', 'Amaro', 'Acqua', 'Libro', 'Inverno', 'Lavoro', 'Attraente', 'Ottimismo', 'Scultura', 'Gastronomia', 'Bello', 'Occhiali', 'Calcio', 'Prodigio', 'Esperienza', 'Ispirati', 'Mare', 'Mistico', 'Natura', 'Scrivi', 'Fantasia', 'Camminare', 'Gioia', 'Universo', 'Te', 'Espressione', 'Risate', 'Spiritualità', 'Ringiovanimento', 'Fiume', 'Felicità', 'Banana', 'Yoga', 'Emotivo' , 'Opportunità', 'Casa', 'Penna', 'Pazienza', 'Strada', 'Gioia', 'Fiducia', 'Attrazione', 'Sogno', 'Fantastico', 'Compleanno', 'Incubo', 'Stupore', 'Nuvole', 'Splendido', 'Equilibrio', 'Collaborazione', 'Spazio', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing' , 'Empatia' , 'Interni', 'Sbalorditivo', 'Indimenticabile', 'Ammirazione', 'Bellissimo', 'Montagna', 'Realizzazione', 'Acido', 'Scrivi', 'Abbraccio', 'Ceramica', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motocycle', 'Birra', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passtime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Sfida', 'Nuoto', 'Analisi', 'Squisito', 'Patrimonio', 'Televisione', 'Pantaloni', 'Regalo', 'Ricompensa', 'Desolazione', 'Nobiltà', 'Connessione', ' Story', 'School', 'Maturity', 'Rain', 'Lamp', 'Spontaneity', 'Clear', 'Constellation', 'Topo', 'Culture', 'Fresh', 'Ispiration', 'Sun Guitar ', 'Libro', 'Diversità', 'Rischio', 'Orange', 'Università', 'Determinazione', 'Festival', 'Gentilezza', 'Brezza', 'Criceto', 'Autostrada', 'Meraviglia', 'Ape', 'Speranza', 'Conoscenza', 'Collina', 'Criceto', 'Delicato', 'Energia', 'Radiante', 'Medicina', 'Nuoto', 'Cascata', 'Affettuoso', 'Caldo' , 'Friendship', 'Telephone', 'Rabbit', 'Lunedì', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning' , 'Sincerità', 'Sostenibilità', 'Gentilezza', 'Giungla', 'Leggerezza', 'Focus', 'Cane', 'Università', 'Nutrizione', 'Scoperta', 'Giardino', 'Abilità', ' Treno ', 'Illuminazione', 'Pianificazione', 'Sabbia', 'Tennis', 'Lussureggiante', 'Superamento', 'Estate', 'Ingegnere', 'Foresta', 'Tempesta', 'Trascendenza', 'Divorziato' , 'Armonia', 'Empatia', 'Rispetto', 'Orologio', 'Amico', 'Filo', 'Yogurt', 'Scuola', 'Serendipità', 'Aeroplano', 'Gioco', 'Risate', 'Pienezza', 'Scultura', 'Ospedale', 'Sorriso', 'Accattivante', 'Intuizione', 'Esperienza', 'Splendore', 'Oceano', 'Prosperità', 'Coscienza', 'Tequila', 'Anniversario' , 'Seduzione', 'Comando', 'Eccezionale', 'Cortese', 'Rinnovamento', 'Valle', 'Mattina', 'Notte', 'Inverno', 'Carisma', 'Evoluzione', 'Flessibilità', 'Energia', 'Cambiamento', 'Basket', 'Professionalità', 'Ispirazione', 'Emozionante', 'Meraviglioso', 'Successo', 'Solidarietà', 'Rinascimento', 'Verdure', 'Vestito', 'Conchiglie' , 'Mare', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Laughing', 'Gratefulness', ' Avventura', 'Pepe', 'Primavera', 'Esilarante', 'Soffitto', 'Zucchero', 'Vestito', 'Calma', 'Libertà', 'Tranquillità', 'Coscienza', 'Anniversario', 'Momenti ' , 'Felice', 'Galaxy', 'Autenticità', 'Meditazione', 'Competenza', 'Albero', 'Nutrizione', 'Glorioso', 'Scienza', 'Elevazione', 'Aria', 'Giustizia', ' Efficienza', 'Fascino', 'Fuoco', 'Tradizione', 'Oasi', 'Sorpresa', 'Insegnamento', 'Gioia', 'Sogno', 'Traboccante', 'Avventura', 'Televisione', 'Scarpe ' , 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Angry', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', ' Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Entusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting ' , 'Pasta', 'Esuberanza', 'Equità', 'Cinema', 'Perseveranza', 'Organizzazione', 'Perseveranza', 'Carriera', 'Incredibile', 'Sogni', 'Originalità', 'Straordinario', ' Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking ' , 'Serenità', 'Fantasia', 'Emancipatore', 'Attento', 'Gelato', 'Sera', 'Matita', 'Appartenenza', 'Imprenditorialità', 'Integrità', 'Innocenza', 'Armonia' , 'Autostima', 'Gioia', 'Tè', 'Quaderno', 'Pittura', 'Riso', 'Arricchimento', 'Motivatore', 'Inclusione', 'mela', 'Consapevolezza', 'Rispetto' , 'Esplorazione', 'Vicino', 'Ricchezza', 'Trasformazione', 'Dipinto', 'Gioia', 'Caos', 'Terra', 'Farfalla', 'Ammirazione', 'Esotico', 'Sostenibilità', 'Passionate', 'Vanilla', 'Affascinante', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Vegetable', 'Invigorating' , 'Whisky', 'Teatro', 'Paesaggio', 'Sensazione', 'Fortezza', 'Strada', 'Porta', 'Carne', 'Mistero', 'Teatro', 'Pasta', 'Sabato', 'Engagement', 'Trionfo', 'Affascinante', 'Coraggio', 'Grano', 'Gentilezza', 'Pace', 'Sostenibilità', 'Persistenza', 'Città', 'Architettura', 'Festa', 'Sognatore' , 'Nursing' , 'Forza', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', ' Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt' , 'Compagno' , 'Famiglia', 'Vivace', 'Ambiente', 'Apprendimento', 'Avvocato', 'Intrattenimento', 'Valori', 'Negozio', 'Accettazione', 'Famiglia', 'Conoscenza', ' Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Scout', 'Beach', 'Couch', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment' , 'Montagna', 'Foresta', 'Sopravvivenza', 'Incomparabile', 'Ospedale', 'Giardino', 'Leggenda', 'Viale', 'Sublimazione', 'Insalata', 'Destino', 'Gentile', ' Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart', 'Steady', 'Chair', 'Master', 'Auto', 'Metropolis', 'Vibrant', 'Tea', 'Subjugated', 'Brush', 'Harmony', 'Plenitude', 'Addictive', 'Violin', 'Meta', ' Plethoric', 'Thought', 'Lamp', 'Enjoy', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning', 'Angry', 'Honesty' , 'Fantastico', 'Accattivante', 'Sorpresa', 'Trasformazione', 'Estate', 'Matematica', 'Calma', 'Motociclista', 'Leone', 'Comfort', 'Ricordi', 'Compagnia', ' Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic', 'Medical', 'Souvenir' , 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', ' Equality', 'Evening', 'Soft Drink', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning', 'Generous ', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elefant', 'Widower', 'Noon', ' Felice', 'Incredibile', 'Inebriante', 'Promettente', 'Istruzione', 'Sushi', 'Paziente', 'Innovazione', 'Agricoltura', 'Determinazione', 'Tuono', 'Energia', 'Libellula ' , 'Incredibile', 'Soluzione', 'Fulmine', 'Tigre', 'Gatto', 'Dedizione', 'Barca', 'Esaltazione', 'Risciacquo', 'Passione', 'Ecologia', 'Onestà', ' Emotion', 'Running', 'Technology', 'Revealer', 'Explore', 'Glare', 'Awakening', 'Wine', 'Trisness', 'Story', 'Luna', 'Study', 'Health ' , 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', ' Storia', 'Benessere', 'Benedizione', 'Divertimento', 'Esplorazione', 'Natura', 'Irrequietezza', 'Melodia', 'Filantropia', 'Sciarpa', 'Rinvigorente', 'Canto', 'Tolleranza', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage ', ' Calcio', 'Comunità', 'Splendido', 'Arcobaleno', 'Incoraggiamento', 'Disciplina', 'Nursery', 'Fantastico', 'Desiderio', 'Dedizione', 'Musica', 'Utile', 'Salute', 'Porta', 'Affari', 'Finestra', 'Sensibilità', 'Treno', 'Stabilità', 'Giraffa', 'Enigma', 'Coraggio', 'Succo', 'Magia', 'Parola ', 'Unico', 'Pianoforte', 'Metropoli', 'Produttività', 'Euforia', 'Pittoresco', 'Metropoli', 'Rinfrescante', 'Shock', 'Viaggio', 'Coraggio', 'Scioccante', 'Canta', 'Celebrazione', 'Cooperazione', 'Danza', 'Risciacquo', 'Incanto', 'Religione', 'Idillio', 'Generazione', 'Trascendente', 'Piuma', 'Grano', 'Soddisfazione ', ' Affari', 'Rettile', 'Frutta', 'Tavolo', 'Organizzazione', 'Stelle', 'Stampante', 'Obiettivo', 'Motivazione', 'Impavidità', 'Equilibrio', 'Calma', 'Compleanno' , 'Divorziato', 'Brillante', 'Collaborazione', 'Verde', 'Dessert', 'Malinconia', 'Fotografia', 'Risate', 'Aroma', 'Frutta', 'Relax', 'Rugiada ', 'Vigore', 'Generosità', 'Sorriso', 'Autunno', 'Impulso', 'Fascino', 'Incantevole', 'Salato', 'Lucidità', 'Blu', 'Entusiasmo', 'Bellezza', 'Crescita', 'Zucchero', 'Petrolio', 'Arcobaleno', 'Viaggio', 'Criceto', 'Sorpresa', 'Avventuriero', 'Caffè', 'Incredibile', 'Curiosità', 'Filo', 'Pesce ', ' Notevole', 'Comprensione', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Scopo' , 'Bacio', 'Felino', 'Singolo', 'Pace', 'Tecnico', 'Pera', 'Danza', 'Colibrì', 'Aereo', 'Lago', 'Inebriante', 'Euforico', 'Emozionante', 'Festival', 'Sole', 'Pantaloni', 'Salto', 'Barca', 'Ceramica', 'Interdipendenza', 'Gioco', 'Eloquenza', 'Stimolato', 'Essenza', 'Salto' , 'Trust' , 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Wish', 'Noble', ' Spiritualità', 'Cooperazione', 'Armonia', 'Pepe', 'Miglioramento', 'Sublime', 'Accecante', 'Tradizione', 'Flessibilità', 'Universo', 'Giraffa', 'Strada', 'Diversità' , 'Act' , ' Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt' , 'Dawn', 'Abbondanza', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Enterpreneurship', ' Tuono', 'Eccentricità', 'Villaggio', 'Sentimenti', 'Elettrificato', 'Affascinante', 'Gratitudine', 'Cannella', 'Vittoria', 'Lealtà', 'Bicicletta', 'Mais', 'Successo' , 'Emozione', 'Istruzione', 'Cascata', 'Libertà', 'Odontoiatria', 'Integrità', 'Divano', 'Ricerca', 'Formaggio', 'Illuminazione', 'Generosità', 'Passione', 'Terra', 'Poesia', 'Sacrificio', 'Resilienza', 'Meravigliosamente', 'Energia', 'Finestra']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Parola:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("indovina una lettera: ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Corretto!")

                    else:
                        intentos_restantes -= 1
                        print("Errato. Te ne sei andato", intentos_restantes, "tentativi.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Vinto! hai indovinato la parola:", palabra)
                        break

                if intentos_restantes == 0:
                        print("Hai perso! la parola era:", palabra)


            print("Giocatore 1:")
            jugar_ahorcado()

        elif b == 2:


            lista = ['Compagnia', 'Biscotto', 'Abbraccio', 'Lealtà', 'Arricchimento', 'Autunno', 'Ambizione', 'Brillante', 'Immobilità', 'Scienza', 'Rosso', 'Matita', 'Cannella ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Crowth', 'Tenacity', 'Excited', 'Literature', 'Festa', 'Speranza', 'Ispiratrice', 'Innovazione', 'Creatività', 'Elettrizzante', 'Stupore', 'Carne', 'Orologio', 'Silenzio', 'Intestazione', 'Neve', 'Bow ', 'Capacità', 'Sonno', 'Arancione', 'Meraviglia', 'Cordialità', 'Cambiamento', 'Computer', 'Musica', 'Uva', 'Epifania', 'Corsa', 'Gratitudine', 'Leadership', 'Mistero', 'Occhiali', 'Comunicazione', 'Rivelazione', 'Acclamato', 'Lacrime', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Stile', 'Incantevole', 'Sport', 'Letteratura', 'Guarigione', 'Serenità', 'Cane', 'Rinfrescante', 'Meraviglia', 'Ufficio', 'Relax', 'Stile' , 'Vitalità', 'Conservazione', 'Dignità', 'Redenzione', 'Nuoto', 'Riposo', 'Emozionante', 'Carriera', 'Farina d avena', 'Risultato', 'Applauso', 'Tempo', 'Yogurt', 'Oceano', 'Cinema', 'Villaggio', 'Soddisfazione', 'Caffè', 'Chitarra', 'Acqua', 'Gesso', 'Responsabilità', 'Prestigio', 'Piacere', 'Piangere ', 'Ottimismo', 'Squadra', 'Uguaglianza', 'Vaniglia', 'Danza', 'Autobus', 'Hobby', 'Immaginazione', 'Irresistibile', 'Bagliore', 'Adattabilità', 'Apprezzamento', 'Penna', 'Volontariato', 'Speranza', 'Intrigante', 'Illuminante', 'Edificante', 'Impressionismo', 'Martedì', 'Architettura', 'Progresso', 'Stelle', 'Comunità', 'Indimenticabile ', 'Splendido', 'Collina', 'Ambiente', 'Rinfresco', 'Crepuscolo', 'Innocenza', 'Mais', 'Coraggio', 'Sorpresa', 'Esercizio', 'Aspetta', 'Fotografia', ' Realtà', 'Bello', 'Incanto', 'Crepuscolo', 'Deserto', 'Impressionato', 'Triste', 'Petrolio', 'Euforia', 'Pittura', 'Benessere', 'Villaggio', 'Bagliore ' , 'Riflesso', 'Danza', 'Piuma', 'Dedica', 'Delizia', 'Risate', 'Innamorarsi', 'Torta', 'Sport', 'Reinvenzione', 'Cacao', 'Gastronomia ', ' Simmetria', 'Fratellanza', 'Ingegnere', 'Soddisfacente', 'Cacao', 'Aspirazione', 'Autenticità', 'Umiltà', 'Intrigo', 'Piacere', 'Coscienza', 'Esilarante', 'Avvocato', 'Soldi', 'Yogurt', 'Drive', 'Computer', 'Succo', 'Fuoco', 'Backwind', 'Fascino', 'Pianeta', 'Felicità', 'Gatto', 'Grandezza ', ' Elefante', 'Dolce', 'Coniglio', 'Semplice', 'Amaro', 'Acqua', 'Libro', 'Inverno', 'Lavoro', 'Attraente', 'Ottimismo', 'Scultura', 'Gastronomia', 'Bello', 'Occhiali', 'Calcio', 'Prodigio', 'Esperienza', 'Ispirati', 'Mare', 'Mistico', 'Natura', 'Scrivi', 'Fantasia', 'Camminare', 'Gioia', 'Universo', 'Te', 'Espressione', 'Risate', 'Spiritualità', 'Ringiovanimento', 'Fiume', 'Felicità', 'Banana', 'Yoga', 'Emotivo' , 'Opportunità', 'Casa', 'Penna', 'Pazienza', 'Strada', 'Gioia', 'Fiducia', 'Attrazione', 'Sogno', 'Fantastico', 'Compleanno', 'Incubo', 'Stupore', 'Nuvole', 'Splendido', 'Equilibrio', 'Collaborazione', 'Spazio', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing' , 'Empatia' , 'Interni', 'Sbalorditivo', 'Indimenticabile', 'Ammirazione', 'Bellissimo', 'Montagna', 'Realizzazione', 'Acido', 'Scrivi', 'Abbraccio', 'Ceramica', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motocycle', 'Birra', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passtime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Sfida', 'Nuoto', 'Analisi', 'Squisito', 'Patrimonio', 'Televisione', 'Pantaloni', 'Regalo', 'Ricompensa', 'Desolazione', 'Nobiltà', 'Connessione', ' Story', 'School', 'Maturity', 'Rain', 'Lamp', 'Spontaneity', 'Clear', 'Constellation', 'Topo', 'Culture', 'Fresh', 'Ispiration', 'Sun Guitar ', 'Libro', 'Diversità', 'Rischio', 'Orange', 'Università', 'Determinazione', 'Festival', 'Gentilezza', 'Brezza', 'Criceto', 'Autostrada', 'Meraviglia', 'Ape', 'Speranza', 'Conoscenza', 'Collina', 'Criceto', 'Delicato', 'Energia', 'Radiante', 'Medicina', 'Nuoto', 'Cascata', 'Affettuoso', 'Caldo' , 'Friendship', 'Telephone', 'Rabbit', 'Lunedì', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning' , 'Sincerità', 'Sostenibilità', 'Gentilezza', 'Giungla', 'Leggerezza', 'Focus', 'Cane', 'Università', 'Nutrizione', 'Scoperta', 'Giardino', 'Abilità', ' Treno ', 'Illuminazione', 'Pianificazione', 'Sabbia', 'Tennis', 'Lussureggiante', 'Superamento', 'Estate', 'Ingegnere', 'Foresta', 'Tempesta', 'Trascendenza', 'Divorziato' , 'Armonia', 'Empatia', 'Rispetto', 'Orologio', 'Amico', 'Filo', 'Yogurt', 'Scuola', 'Serendipità', 'Aeroplano', 'Gioco', 'Risate', 'Pienezza', 'Scultura', 'Ospedale', 'Sorriso', 'Accattivante', 'Intuizione', 'Esperienza', 'Splendore', 'Oceano', 'Prosperità', 'Coscienza', 'Tequila', 'Anniversario' , 'Seduzione', 'Comando', 'Eccezionale', 'Cortese', 'Rinnovamento', 'Valle', 'Mattina', 'Notte', 'Inverno', 'Carisma', 'Evoluzione', 'Flessibilità', 'Energia', 'Cambiamento', 'Basket', 'Professionalità', 'Ispirazione', 'Emozionante', 'Meraviglioso', 'Successo', 'Solidarietà', 'Rinascimento', 'Verdure', 'Vestito', 'Conchiglie' , 'Mare', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Laughing', 'Gratefulness', ' Avventura', 'Pepe', 'Primavera', 'Esilarante', 'Soffitto', 'Zucchero', 'Vestito', 'Calma', 'Libertà', 'Tranquillità', 'Coscienza', 'Anniversario', 'Momenti ' , 'Felice', 'Galaxy', 'Autenticità', 'Meditazione', 'Competenza', 'Albero', 'Nutrizione', 'Glorioso', 'Scienza', 'Elevazione', 'Aria', 'Giustizia', ' Efficienza', 'Fascino', 'Fuoco', 'Tradizione', 'Oasi', 'Sorpresa', 'Insegnamento', 'Gioia', 'Sogno', 'Traboccante', 'Avventura', 'Televisione', 'Scarpe ' , 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Angry', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', ' Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Entusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting ' , 'Pasta', 'Esuberanza', 'Equità', 'Cinema', 'Perseveranza', 'Organizzazione', 'Perseveranza', 'Carriera', 'Incredibile', 'Sogni', 'Originalità', 'Straordinario', ' Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking ' , 'Serenità', 'Fantasia', 'Emancipatore', 'Attento', 'Gelato', 'Sera', 'Matita', 'Appartenenza', 'Imprenditorialità', 'Integrità', 'Innocenza', 'Armonia' , 'Autostima', 'Gioia', 'Tè', 'Quaderno', 'Pittura', 'Riso', 'Arricchimento', 'Motivatore', 'Inclusione', 'mela', 'Consapevolezza', 'Rispetto' , 'Esplorazione', 'Vicino', 'Ricchezza', 'Trasformazione', 'Dipinto', 'Gioia', 'Caos', 'Terra', 'Farfalla', 'Ammirazione', 'Esotico', 'Sostenibilità', 'Passionate', 'Vanilla', 'Affascinante', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Vegetable', 'Invigorating' , 'Whisky', 'Teatro', 'Paesaggio', 'Sensazione', 'Fortezza', 'Strada', 'Porta', 'Carne', 'Mistero', 'Teatro', 'Pasta', 'Sabato', 'Engagement', 'Trionfo', 'Affascinante', 'Coraggio', 'Grano', 'Gentilezza', 'Pace', 'Sostenibilità', 'Persistenza', 'Città', 'Architettura', 'Festa', 'Sognatore' , 'Nursing' , 'Forza', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', ' Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt' , 'Compagno' , 'Famiglia', 'Vivace', 'Ambiente', 'Apprendimento', 'Avvocato', 'Intrattenimento', 'Valori', 'Negozio', 'Accettazione', 'Famiglia', 'Conoscenza', ' Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Scout', 'Beach', 'Couch', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment' , 'Montagna', 'Foresta', 'Sopravvivenza', 'Incomparabile', 'Ospedale', 'Giardino', 'Leggenda', 'Viale', 'Sublimazione', 'Insalata', 'Destino', 'Gentile', ' Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart', 'Steady', 'Chair', 'Master', 'Auto', 'Metropolis', 'Vibrant', 'Tea', 'Subjugated', 'Brush', 'Harmony', 'Plenitude', 'Addictive', 'Violin', 'Meta', ' Plethoric', 'Thought', 'Lamp', 'Enjoy', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning', 'Angry', 'Honesty' , 'Fantastico', 'Accattivante', 'Sorpresa', 'Trasformazione', 'Estate', 'Matematica', 'Calma', 'Motociclista', 'Leone', 'Comfort', 'Ricordi', 'Compagnia', ' Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic', 'Medical', 'Souvenir' , 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', ' Equality', 'Evening', 'Soft Drink', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning', 'Generous ', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elefant', 'Widower', 'Noon', ' Felice', 'Incredibile', 'Inebriante', 'Promettente', 'Istruzione', 'Sushi', 'Paziente', 'Innovazione', 'Agricoltura', 'Determinazione', 'Tuono', 'Energia', 'Libellula ' , 'Incredibile', 'Soluzione', 'Fulmine', 'Tigre', 'Gatto', 'Dedizione', 'Barca', 'Esaltazione', 'Risciacquo', 'Passione', 'Ecologia', 'Onestà', ' Emotion', 'Running', 'Technology', 'Revealer', 'Explore', 'Glare', 'Awakening', 'Wine', 'Trisness', 'Story', 'Luna', 'Study', 'Health ' , 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', ' Storia', 'Benessere', 'Benedizione', 'Divertimento', 'Esplorazione', 'Natura', 'Irrequietezza', 'Melodia', 'Filantropia', 'Sciarpa', 'Rinvigorente', 'Canto', 'Tolleranza', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage ', ' Calcio', 'Comunità', 'Splendido', 'Arcobaleno', 'Incoraggiamento', 'Disciplina', 'Nursery', 'Fantastico', 'Desiderio', 'Dedizione', 'Musica', 'Utile', 'Salute', 'Porta', 'Affari', 'Finestra', 'Sensibilità', 'Treno', 'Stabilità', 'Giraffa', 'Enigma', 'Coraggio', 'Succo', 'Magia', 'Parola ', 'Unico', 'Pianoforte', 'Metropoli', 'Produttività', 'Euforia', 'Pittoresco', 'Metropoli', 'Rinfrescante', 'Shock', 'Viaggio', 'Coraggio', 'Scioccante', 'Canta', 'Celebrazione', 'Cooperazione', 'Danza', 'Risciacquo', 'Incanto', 'Religione', 'Idillio', 'Generazione', 'Trascendente', 'Piuma', 'Grano', 'Soddisfazione ', ' Affari', 'Rettile', 'Frutta', 'Tavolo', 'Organizzazione', 'Stelle', 'Stampante', 'Obiettivo', 'Motivazione', 'Impavidità', 'Equilibrio', 'Calma', 'Compleanno' , 'Divorziato', 'Brillante', 'Collaborazione', 'Verde', 'Dessert', 'Malinconia', 'Fotografia', 'Risate', 'Aroma', 'Frutta', 'Relax', 'Rugiada ', 'Vigore', 'Generosità', 'Sorriso', 'Autunno', 'Impulso', 'Fascino', 'Incantevole', 'Salato', 'Lucidità', 'Blu', 'Entusiasmo', 'Bellezza', 'Crescita', 'Zucchero', 'Petrolio', 'Arcobaleno', 'Viaggio', 'Criceto', 'Sorpresa', 'Avventuriero', 'Caffè', 'Incredibile', 'Curiosità', 'Filo', 'Pesce ', ' Notevole', 'Comprensione', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Scopo' , 'Bacio', 'Felino', 'Singolo', 'Pace', 'Tecnico', 'Pera', 'Danza', 'Colibrì', 'Aereo', 'Lago', 'Inebriante', 'Euforico', 'Emozionante', 'Festival', 'Sole', 'Pantaloni', 'Salto', 'Barca', 'Ceramica', 'Interdipendenza', 'Gioco', 'Eloquenza', 'Stimolato', 'Essenza', 'Salto' , 'Trust' , 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Wish', 'Noble', ' Spiritualità', 'Cooperazione', 'Armonia', 'Pepe', 'Miglioramento', 'Sublime', 'Accecante', 'Tradizione', 'Flessibilità', 'Universo', 'Giraffa', 'Strada', 'Diversità' , 'Act' , ' Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt' , 'Dawn', 'Abbondanza', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Enterpreneurship', ' Tuono', 'Eccentricità', 'Villaggio', 'Sentimenti', 'Elettrificato', 'Affascinante', 'Gratitudine', 'Cannella', 'Vittoria', 'Lealtà', 'Bicicletta', 'Mais', 'Successo' , 'Emozione', 'Istruzione', 'Cascata', 'Libertà', 'Odontoiatria', 'Integrità', 'Divano', 'Ricerca', 'Formaggio', 'Illuminazione', 'Generosità', 'Passione', 'Terra', 'Poesia', 'Sacrificio', 'Resilienza', 'Meravigliosamente', 'Energia', 'Finestra']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Parola:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("indovina una lettera: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Corretto!")

                    else:
                        intentos_restantes -= 1
                        print("Errato. Te ne sei andato", intentos_restantes, "tentativi.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Vinto! hai indovinato la parola:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Hai perso! la parola era:", palabra)


            print("Giocatore 1:")
            jugar_ahorcado()


        elif b == 3:

            import random
            lista = ['Compagnia', 'Biscotto', 'Abbraccio', 'Lealtà', 'Arricchimento', 'Autunno', 'Ambizione', 'Brillante', 'Immobilità', 'Scienza', 'Rosso', 'Matita', 'Cannella ', 'Air', 'Love', 'Highway', 'Patience', 'Loneliness', 'Strategy', 'Breakthrough', 'Fashion', 'Crowth', 'Tenacity', 'Excited', 'Literature', 'Festa', 'Speranza', 'Ispiratrice', 'Innovazione', 'Creatività', 'Elettrizzante', 'Stupore', 'Carne', 'Orologio', 'Silenzio', 'Intestazione', 'Neve', 'Bow ', 'Capacità', 'Sonno', 'Arancione', 'Meraviglia', 'Cordialità', 'Cambiamento', 'Computer', 'Musica', 'Uva', 'Epifania', 'Corsa', 'Gratitudine', 'Leadership', 'Mistero', 'Occhiali', 'Comunicazione', 'Rivelazione', 'Acclamato', 'Lacrime', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery' , 'Stile', 'Incantevole', 'Sport', 'Letteratura', 'Guarigione', 'Serenità', 'Cane', 'Rinfrescante', 'Meraviglia', 'Ufficio', 'Relax', 'Stile' , 'Vitalità', 'Conservazione', 'Dignità', 'Redenzione', 'Nuoto', 'Riposo', 'Emozionante', 'Carriera', 'Farina d avena', 'Risultato', 'Applauso', 'Tempo', 'Yogurt', 'Oceano', 'Cinema', 'Villaggio', 'Soddisfazione', 'Caffè', 'Chitarra', 'Acqua', 'Gesso', 'Responsabilità', 'Prestigio', 'Piacere', 'Piangere ', 'Ottimismo', 'Squadra', 'Uguaglianza', 'Vaniglia', 'Danza', 'Autobus', 'Hobby', 'Immaginazione', 'Irresistibile', 'Bagliore', 'Adattabilità', 'Apprezzamento', 'Penna', 'Volontariato', 'Speranza', 'Intrigante', 'Illuminante', 'Edificante', 'Impressionismo', 'Martedì', 'Architettura', 'Progresso', 'Stelle', 'Comunità', 'Indimenticabile ', 'Splendido', 'Collina', 'Ambiente', 'Rinfresco', 'Crepuscolo', 'Innocenza', 'Mais', 'Coraggio', 'Sorpresa', 'Esercizio', 'Aspetta', 'Fotografia', ' Realtà', 'Bello', 'Incanto', 'Crepuscolo', 'Deserto', 'Impressionato', 'Triste', 'Petrolio', 'Euforia', 'Pittura', 'Benessere', 'Villaggio', 'Bagliore ' , 'Riflesso', 'Danza', 'Piuma', 'Dedica', 'Delizia', 'Risate', 'Innamorarsi', 'Torta', 'Sport', 'Reinvenzione', 'Cacao', 'Gastronomia ', ' Simmetria', 'Fratellanza', 'Ingegnere', 'Soddisfacente', 'Cacao', 'Aspirazione', 'Autenticità', 'Umiltà', 'Intrigo', 'Piacere', 'Coscienza', 'Esilarante', 'Avvocato', 'Soldi', 'Yogurt', 'Drive', 'Computer', 'Succo', 'Fuoco', 'Backwind', 'Fascino', 'Pianeta', 'Felicità', 'Gatto', 'Grandezza ', ' Elefante', 'Dolce', 'Coniglio', 'Semplice', 'Amaro', 'Acqua', 'Libro', 'Inverno', 'Lavoro', 'Attraente', 'Ottimismo', 'Scultura', 'Gastronomia', 'Bello', 'Occhiali', 'Calcio', 'Prodigio', 'Esperienza', 'Ispirati', 'Mare', 'Mistico', 'Natura', 'Scrivi', 'Fantasia', 'Camminare', 'Gioia', 'Universo', 'Te', 'Espressione', 'Risate', 'Spiritualità', 'Ringiovanimento', 'Fiume', 'Felicità', 'Banana', 'Yoga', 'Emotivo' , 'Opportunità', 'Casa', 'Penna', 'Pazienza', 'Strada', 'Gioia', 'Fiducia', 'Attrazione', 'Sogno', 'Fantastico', 'Compleanno', 'Incubo', 'Stupore', 'Nuvole', 'Splendido', 'Equilibrio', 'Collaborazione', 'Spazio', 'Empowerment', 'Design', 'Study', 'Emotionally', 'Resilience', 'Basketball', 'Glowing' , 'Empatia' , 'Interni', 'Sbalorditivo', 'Indimenticabile', 'Ammirazione', 'Bellissimo', 'Montagna', 'Realizzazione', 'Acido', 'Scrivi', 'Abbraccio', 'Ceramica', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Motocycle', 'Birra', 'Shoes', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passtime', 'Colorful', 'Travel', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Sfida', 'Nuoto', 'Analisi', 'Squisito', 'Patrimonio', 'Televisione', 'Pantaloni', 'Regalo', 'Ricompensa', 'Desolazione', 'Nobiltà', 'Connessione', ' Story', 'School', 'Maturity', 'Rain', 'Lamp', 'Spontaneity', 'Clear', 'Constellation', 'Topo', 'Culture', 'Fresh', 'Ispiration', 'Sun Guitar ', 'Libro', 'Diversità', 'Rischio', 'Orange', 'Università', 'Determinazione', 'Festival', 'Gentilezza', 'Brezza', 'Criceto', 'Autostrada', 'Meraviglia', 'Ape', 'Speranza', 'Conoscenza', 'Collina', 'Criceto', 'Delicato', 'Energia', 'Radiante', 'Medicina', 'Nuoto', 'Cascata', 'Affettuoso', 'Caldo' , 'Friendship', 'Telephone', 'Rabbit', 'Lunedì', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning' , 'Sincerità', 'Sostenibilità', 'Gentilezza', 'Giungla', 'Leggerezza', 'Focus', 'Cane', 'Università', 'Nutrizione', 'Scoperta', 'Giardino', 'Abilità', ' Treno ', 'Illuminazione', 'Pianificazione', 'Sabbia', 'Tennis', 'Lussureggiante', 'Superamento', 'Estate', 'Ingegnere', 'Foresta', 'Tempesta', 'Trascendenza', 'Divorziato' , 'Armonia', 'Empatia', 'Rispetto', 'Orologio', 'Amico', 'Filo', 'Yogurt', 'Scuola', 'Serendipità', 'Aeroplano', 'Gioco', 'Risate', 'Pienezza', 'Scultura', 'Ospedale', 'Sorriso', 'Accattivante', 'Intuizione', 'Esperienza', 'Splendore', 'Oceano', 'Prosperità', 'Coscienza', 'Tequila', 'Anniversario' , 'Seduzione', 'Comando', 'Eccezionale', 'Cortese', 'Rinnovamento', 'Valle', 'Mattina', 'Notte', 'Inverno', 'Carisma', 'Evoluzione', 'Flessibilità', 'Energia', 'Cambiamento', 'Basket', 'Professionalità', 'Ispirazione', 'Emozionante', 'Meraviglioso', 'Successo', 'Solidarietà', 'Rinascimento', 'Verdure', 'Vestito', 'Conchiglie' , 'Mare', 'Medical', 'Faith', 'T-shirt', 'Creativity', 'Bitter', 'Celebration', 'Vitality', 'Flowers', 'Night', 'Laughing', 'Gratefulness', ' Avventura', 'Pepe', 'Primavera', 'Esilarante', 'Soffitto', 'Zucchero', 'Vestito', 'Calma', 'Libertà', 'Tranquillità', 'Coscienza', 'Anniversario', 'Momenti ' , 'Felice', 'Galaxy', 'Autenticità', 'Meditazione', 'Competenza', 'Albero', 'Nutrizione', 'Glorioso', 'Scienza', 'Elevazione', 'Aria', 'Giustizia', ' Efficienza', 'Fascino', 'Fuoco', 'Tradizione', 'Oasi', 'Sorpresa', 'Insegnamento', 'Gioia', 'Sogno', 'Traboccante', 'Avventura', 'Televisione', 'Scarpe ' , 'Chocolate', 'Dog', 'Inspiration', 'Wedding', 'Angry', 'Passionate', 'Medicine', 'Brush', 'Clarity', 'Surround', 'Pizza', 'Moon', ' Justice', 'Empowerment', 'Chair', 'Overflow', 'Wind', 'Wealth', 'Memories', 'Entusiasm', 'Technology', 'Shop', 'Galaxy', 'Magic', 'Enchanting ' , 'Pasta', 'Esuberanza', 'Equità', 'Cinema', 'Perseveranza', 'Organizzazione', 'Perseveranza', 'Carriera', 'Incredibile', 'Sogni', 'Originalità', 'Straordinario', ' Momentous', 'Office', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking ' , 'Serenità', 'Fantasia', 'Emancipatore', 'Attento', 'Gelato', 'Sera', 'Matita', 'Appartenenza', 'Imprenditorialità', 'Integrità', 'Innocenza', 'Armonia' , 'Autostima', 'Gioia', 'Tè', 'Quaderno', 'Pittura', 'Riso', 'Arricchimento', 'Motivatore', 'Inclusione', 'mela', 'Consapevolezza', 'Rispetto' , 'Esplorazione', 'Vicino', 'Ricchezza', 'Trasformazione', 'Dipinto', 'Gioia', 'Caos', 'Terra', 'Farfalla', 'Ammirazione', 'Esotico', 'Sostenibilità', 'Passionate', 'Vanilla', 'Affascinante', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Vegetable', 'Invigorating' , 'Whisky', 'Teatro', 'Paesaggio', 'Sensazione', 'Fortezza', 'Strada', 'Porta', 'Carne', 'Mistero', 'Teatro', 'Pasta', 'Sabato', 'Engagement', 'Trionfo', 'Affascinante', 'Coraggio', 'Grano', 'Gentilezza', 'Pace', 'Sostenibilità', 'Persistenza', 'Città', 'Architettura', 'Festa', 'Sognatore' , 'Nursing' , 'Forza', 'Sigh', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Cheerful', ' Revitalizing', 'Friendly', 'Excitedly', 'Avenue', 'Beauty', 'Yellow', 'Defiance', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt' , 'Compagno' , 'Famiglia', 'Vivace', 'Ambiente', 'Apprendimento', 'Avvocato', 'Intrattenimento', 'Valori', 'Negozio', 'Accettazione', 'Famiglia', 'Conoscenza', ' Strength', 'Spirit', 'Brave', 'Revolution', 'Care', 'Scout', 'Beach', 'Couch', 'Friendship', 'Bus', 'Fish', 'Dance', 'Enchantment' , 'Montagna', 'Foresta', 'Sopravvivenza', 'Incomparabile', 'Ospedale', 'Giardino', 'Leggenda', 'Viale', 'Sublimazione', 'Insalata', 'Destino', 'Gentile', ' Sweet', 'Eternity', 'Hat', 'Eternal', 'Loving', 'Paint', 'Heart', 'Steady', 'Chair', 'Master', 'Auto', 'Metropolis', 'Vibrant', 'Tea', 'Subjugated', 'Brush', 'Harmony', 'Plenitude', 'Addictive', 'Violin', 'Meta', ' Plethoric', 'Thought', 'Lamp', 'Enjoy', 'Ingenuity', 'Challenges', 'Amazing', 'Work', 'Beach', 'Shelter', 'Morning', 'Angry', 'Honesty' , 'Fantastico', 'Accattivante', 'Sorpresa', 'Trasformazione', 'Estate', 'Matematica', 'Calma', 'Motociclista', 'Leone', 'Comfort', 'Ricordi', 'Compagnia', ' Drop', 'Dream', 'Touching', 'Development', 'Wisdom', 'Married', 'Married', 'Love', 'Fashion', 'Art', 'Heroic', 'Medical', 'Souvenir' , 'Transcendental', 'Autonomy', 'Roof', 'Philosophy', 'Amazing', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', ' Equality', 'Evening', 'Soft Drink', 'Future', 'Paradise', 'Engineering', 'Sublime', 'Rest', 'Butter', 'Romance', 'Noon', 'Lightning', 'Generous ', 'Motivation', 'Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividness', 'Outdoors', 'Independence', 'Elefant', 'Widower', 'Noon', ' Felice', 'Incredibile', 'Inebriante', 'Promettente', 'Istruzione', 'Sushi', 'Paziente', 'Innovazione', 'Agricoltura', 'Determinazione', 'Tuono', 'Energia', 'Libellula ' , 'Incredibile', 'Soluzione', 'Fulmine', 'Tigre', 'Gatto', 'Dedizione', 'Barca', 'Esaltazione', 'Risciacquo', 'Passione', 'Ecologia', 'Onestà', ' Emotion', 'Running', 'Technology', 'Revealer', 'Explore', 'Glare', 'Awakening', 'Wine', 'Trisness', 'Story', 'Luna', 'Study', 'Health ' , 'Wisdom', 'Exorbitant', 'Lovely', 'Milk', 'Goals', 'Scarf', 'Swim', 'Art', 'Valley', 'River', 'Nature', 'Hamburger', ' Storia', 'Benessere', 'Benedizione', 'Divertimento', 'Esplorazione', 'Natura', 'Irrequietezza', 'Melodia', 'Filantropia', 'Sciarpa', 'Rinvigorente', 'Canto', 'Tolleranza', 'Drop', 'Glance', 'Discover', 'Salt', 'Fun', 'City', 'Pardon', 'People', 'Serendipity', 'Solidarity', 'Sunday', 'Heritage ', ' Calcio', 'Comunità', 'Splendido', 'Arcobaleno', 'Incoraggiamento', 'Disciplina', 'Nursery', 'Fantastico', 'Desiderio', 'Dedizione', 'Musica', 'Utile', 'Salute', 'Porta', 'Affari', 'Finestra', 'Sensibilità', 'Treno', 'Stabilità', 'Giraffa', 'Enigma', 'Coraggio', 'Succo', 'Magia', 'Parola ', 'Unico', 'Pianoforte', 'Metropoli', 'Produttività', 'Euforia', 'Pittoresco', 'Metropoli', 'Rinfrescante', 'Shock', 'Viaggio', 'Coraggio', 'Scioccante', 'Canta', 'Celebrazione', 'Cooperazione', 'Danza', 'Risciacquo', 'Incanto', 'Religione', 'Idillio', 'Generazione', 'Trascendente', 'Piuma', 'Grano', 'Soddisfazione ', ' Affari', 'Rettile', 'Frutta', 'Tavolo', 'Organizzazione', 'Stelle', 'Stampante', 'Obiettivo', 'Motivazione', 'Impavidità', 'Equilibrio', 'Calma', 'Compleanno' , 'Divorziato', 'Brillante', 'Collaborazione', 'Verde', 'Dessert', 'Malinconia', 'Fotografia', 'Risate', 'Aroma', 'Frutta', 'Relax', 'Rugiada ', 'Vigore', 'Generosità', 'Sorriso', 'Autunno', 'Impulso', 'Fascino', 'Incantevole', 'Salato', 'Lucidità', 'Blu', 'Entusiasmo', 'Bellezza', 'Crescita', 'Zucchero', 'Petrolio', 'Arcobaleno', 'Viaggio', 'Criceto', 'Sorpresa', 'Avventuriero', 'Caffè', 'Incredibile', 'Curiosità', 'Filo', 'Pesce ', ' Notevole', 'Comprensione', 'Butter', 'Early Morning', 'Student', 'Spring', 'Lake', 'Therapy', 'Skill', 'Grace', 'Unmatched', 'Scopo' , 'Bacio', 'Felino', 'Singolo', 'Pace', 'Tecnico', 'Pera', 'Danza', 'Colibrì', 'Aereo', 'Lago', 'Inebriante', 'Euforico', 'Emozionante', 'Festival', 'Sole', 'Pantaloni', 'Salto', 'Barca', 'Ceramica', 'Interdipendenza', 'Gioco', 'Eloquenza', 'Stimolato', 'Essenza', 'Salto' , 'Trust' , 'Oats', 'Ethics', 'Initiative', 'Banana', 'Cloud', 'Lush', 'Write', 'Encounter', 'Nutrition', 'Wish', 'Noble', ' Spiritualità', 'Cooperazione', 'Armonia', 'Pepe', 'Miglioramento', 'Sublime', 'Accecante', 'Tradizione', 'Flessibilità', 'Universo', 'Giraffa', 'Strada', 'Diversità' , 'Act' , ' Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-shirt' , 'Dawn', 'Abbondanza', 'Companionship', 'Challenging', 'Stunning', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Enterpreneurship', ' Tuono', 'Eccentricità', 'Villaggio', 'Sentimenti', 'Elettrificato', 'Affascinante', 'Gratitudine', 'Cannella', 'Vittoria', 'Lealtà', 'Bicicletta', 'Mais', 'Successo' , 'Emozione', 'Istruzione', 'Cascata', 'Libertà', 'Odontoiatria', 'Integrità', 'Divano', 'Ricerca', 'Formaggio', 'Illuminazione', 'Generosità', 'Passione', 'Terra', 'Poesia', 'Sacrificio', 'Resilienza', 'Meravigliosamente', 'Energia', 'Finestra']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Parola:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("indovina una lettera: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Corretto!")
                    else:
                        intentos_restantes -= 1
                        print("Errato. Te ne sei andato", intentos_restantes, "tentativi.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Vinto! hai indovinato la parola:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Hai perso! la parola era:", palabra)
            print("Giocatore 1:")
            jugar_ahorcado()



elif a == 4:
    Multiplayer = int(input("Wählen Sie die Anzahl der Spieler 1-2:"))
    if Multiplayer == 2:
        b=int(input("Bitte wählen Sie einen Schwierigkeitsgrad aus:\n1.einfach\n2.mittel\n3.schwer" ))
        if b == 1:

            lista = ['Kameradschaft' , 'Keks', 'Umarmung', 'Loyalität', 'Bereichernd', 'Herbst', 'Ehrgeiz', 'Hell', 'Stille', 'Wissenschaft', 'Rot', 'Bleistift', 'Zimt', 'Luft', 'Liebe', 'Autobahn', 'Geduld', 'Einsamkeit', 'Strategie', 'Durchbruch', 'Mode', 'Wachstum', 'Hartnäckigkeit', 'Aufgeregt', 'Literatur', 'Party', 'Hoffnung', 'Inspirierend', 'Innovation', 'Kreativität', 'Elektrisierend', 'Staunen', 'Fleisch', 'Uhr', 'Stille', 'Überschrift', 'Schnee', 'Bogen', 'Fähigkeit', 'Schlaf', 'Orange', 'Wunder', 'Freundlichkeit', 'Veränderung', 'Computer', 'Musik', 'Traube', 'Epiphanie', 'Laufen', 'Dankbarkeit', 'Führung', 'Geheimnis', 'Brille', 'Kommunikation', 'Offenbarung', 'Gefeiert', 'Tränen', 'Wegbereiter', 'Flüstern', 'Schnee', 'Horizont', 'Anzeigetafel', 'Entdeckung', 'Stil', 'Bezaubernd', 'Sport', 'Literatur', 'Heilen', 'Gelassenheit', 'Hund', 'Erfrischend', 'Wunder', 'Büro', 'Entspannung', 'Stil' , 'Vitalität', 'Erhaltung', 'Würde', 'Erlösung', 'Schwimmen', 'Ruhe', 'Aufregend', 'Karriere', 'Haferflocken', 'Leistung', 'Applaudiert', 'Zeit', ' Joghurt', 'Ozean', 'Kino', 'Dorf', 'Zufriedenheit', 'Kaffee', 'Gitarre', 'Wasser', 'Kreide', 'Verantwortung', 'Prestige', 'Vergnügen', 'Weinen' , 'Optimismus', 'Team', 'Gleichheit', 'Vanilla', 'Tanz', 'Bus', 'Hobby', 'Fantasie', 'Unwiderstehlich', 'Glühen', 'Anpassungsfähigkeit', 'Wertschätzung', 'Stift', 'Freiwilligenarbeit', 'Hoffnung', 'Faszinierend', 'Aufklärend', 'Erhebend', 'Impressionismus', 'Dienstag', 'Architektur', 'Fortschritt', 'Sterne', 'Gemeinschaft', 'Bedeutsam' , 'Herrlich', 'Hügel', 'Umgebung', 'Erfrischung', 'Dämmerung', 'Unschuld', 'Mais', 'Mut', 'Überrascht', 'Übung', 'Warten', 'Foto', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Dorf', 'Glow' , 'Reflexion', 'Tanz', 'Feder', 'Widmung', 'Freude', 'Lachen', 'Verlieben', 'Kuchen', 'Sport', 'Neuerfindung', 'Kakao', 'Gastronomie', 'Symmetrie', 'Brüderlichkeit', 'Ingenieur', 'Erfüllend', 'Kakao', 'Aspiration', 'Authentizität', 'Demut', 'Intrige', 'Vergnügen', 'Bewusstsein', 'Berauschend', 'Anwalt', 'Geld', 'Joghurt', 'Fahrt', 'Computer', 'Saft', 'Feuer', 'Rückenwind', 'Faszination', 'Planet', 'Glück', 'Katze', 'Größe' , 'Elefant', 'Süß', 'Kaninchen', 'Einfach', 'Bitter', 'Wasser', 'Buch', 'Winter', 'Arbeit', 'Attraktiv', 'Optimismus', 'Skulptur', 'Gastronomie', 'Schön', 'Brillen', 'Fußball', 'Wunderkind', 'Erlebnis', 'Lassen Sie sich inspirieren', 'Meer', 'Mystisch', 'Natur', 'Schreiben', 'Fantasie', ' Gehen', 'Freude', 'Universum', 'Te', 'Ausdruck', 'Lachen', 'Spiritualität', 'Verjüngung', 'Fluss', 'Glück', 'Banane', 'Yoga', 'Emotional' , 'Gelegenheit', 'Zuhause', 'Stift', 'Geduld', 'Straße', 'Freude', 'Vertrauen', 'Anziehung', 'Träumen', 'Fantastisch', 'Geburtstag', 'Albtraum', ' Staunen', 'Wolken', 'Herrlich', 'Balance', 'Zusammenarbeit', 'Raum', 'Empowerment', 'Design', 'Lernen', 'Emotional', 'Belastbarkeit', 'Basketball', 'Glühen' , 'Empathie', 'Innenräume', 'Atemberaubend', 'Unvergesslich', 'Bewunderung', 'Schön', 'Berg', 'Verwirklichung', 'Säure', 'Schreiben', 'Umarmung', 'Keramik', ' Springen', 'Aktion', 'Seufz', 'Wütend', 'Tisch', 'Hut', 'Motorrad', 'Bier', 'Schuhe', 'Wahrheit', 'Aufregend', 'Stern', 'Urlaub' , 'Rhythmus', 'Himmel', 'Zeitvertreib', 'Bunt', 'Reisen', 'Tau', 'Wunderbar', 'Psychologie', 'Sonnenaufgang', 'Dankbarkeit', 'Herausforderung', 'Schwimmen', ' Analyse', 'Exquisit', 'Erbe', 'Fernsehen', 'Hosen', 'Geschenk', 'Belohnung', 'Wüste', 'Adel', 'Verbindung', 'Geschichte', 'Schule', 'Reife' , 'Regen', 'Lampe', 'Spontanität', 'Claro', 'Sternbild', 'Maus', 'Kultur', 'Frisch', 'Inspiration', 'Sonnengitarre', 'Buch', 'Vielfalt', 'Risiko', 'Orange', 'Universität', 'Entschlossenheit', 'Festival', 'Freundlichkeit', 'Brise', 'Hamster', 'Autobahn', 'Wunder', 'Biene', 'Hoffnung', 'Wissen', 'Hügel', 'Hamster', 'Sanft', 'Energie', 'Strahlend', 'Medizin', 'Schwimmen', 'Wasserfall', 'Zärtlich', 'Warm', 'Freundschaft', 'Telefon', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Aufrichtigkeit', 'Nachhaltigkeit', 'Freundlichkeit', 'Dschungel', 'Leuchtkraft', 'Fokus', 'Hund', 'Universität', 'Pflege', 'Entdeckung', 'Garten', 'Fähigkeit', 'Trainieren', 'Beleuchtung', 'Planung', 'Sand', 'Tennis', 'Überschwänglich', 'Überwindung', 'Sommer', 'Ingenieur', 'Wald', 'Sturm', 'Transzendenz', 'Geschieden', 'Harmonie', 'Empathie', 'Respekt', ' Uhr', 'Freund', 'Garn', 'Joghurt', 'Schule', 'Serendipity', 'Flugzeug', 'Spiel', 'Lachen', 'Fülle', 'Skulptur', 'Krankenhaus', 'Lächeln', 'Fesselnd', 'Intuition', 'Erfahrung', 'Pracht', 'Ozean', 'Wohlstand', 'Bewusstsein', ' Tequila', 'Jubiläum', 'Verführung', 'Führung', 'hervorragend', 'Schnitte', 'Erneuerung', 'Valle', 'Morgen', 'Nacht', 'Winter', 'Charisma', 'Evolution' , 'Flexibilität', 'Energetisch', 'Veränderung', 'Basketball', 'Professionalität', 'Inspiration', 'Aufregend', 'Wunderbar', 'Erfolg', 'Solidarität', 'Wiedergeburt', 'Gemüse', ' Kleid', 'Muscheln', 'Meer', 'Medizin', 'Glaube', 'T-Shirt', 'Kreativität', 'Bitter', 'Feier', 'Vitalität', 'Blumen', 'Nacht', ' Lachen', 'Bonus', 'Abenteuer', 'Pfeffer', 'Frühling', 'Aufregung', 'Dach', 'Zucker', 'Kleid', 'Ruhe', 'Freiheit', 'Ruhe', 'Bewusstsein' , 'Jubiläum', 'Momente', 'Glücklich', 'Galaxie', 'Authentizität', 'Meditation', 'Kompetenz', 'Baum', 'Ernährung', 'Herrlich', 'Wissenschaft', 'Erhebung', ' Luft', 'Gerechtigkeit', 'Effizienz', 'Charme', 'Feuer', 'Tradition', 'Oase', 'Überraschung', 'Lehre', 'Freude', 'Träumen', 'Überfließend', 'Abenteuer' , 'Fernsehen', 'Schuhe', 'Schokolade', 'Hund', 'Inspiration', 'Hochzeit', 'Anger', 'Leidenschaftlich', 'Medizin', 'Pinsel', 'Klarheit', 'Surround', ' Pizza', 'Mond', 'Gerechtigkeit', 'Ermächtigung', 'Stuhl', 'Überlauf', 'Wind', 'Reichtum', 'Erinnerungen', 'Begeisterung', 'Technologie', 'Shop', 'Galaxie' , 'Magie', 'Charmant', 'Pasta', 'Überschwänglichkeit', 'Gerechtigkeit', 'Kino', 'Ausdauer', 'Organisation', 'Ausdauer', 'Karriere', 'Erstaunlich', 'Träume', ' Originalität', 'Außergewöhnlich', 'Bedeutsam', 'Büro', 'Einfach', 'Milch', 'Skateboard', 'Mobilfunk', 'Intelligenz', 'Entspannend', 'Sound', 'Ausbruch', 'Sonnenuntergang' , 'Inspirierend', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Watchful', 'Ice Cream', 'Evening', 'Bleistift', 'Zugehörigkeit', 'Unternehmertum', 'Integrität', 'Unschuld', 'Harmonie', 'Selbstwertgefühl', 'Freude', 'Tee', 'Notizbuch', 'Malerei', 'Reis', 'Bereicherung', 'Motivator', 'Inklusion', 'Apfel', 'Achtsamkeit', 'Respekt', 'Erforschung', 'Nachbar', 'Reichtum', 'Transformation', 'Farbe', 'Freude', 'Chaos', 'Erde', 'Schmetterling', 'Bewunderung', 'Exotisch', 'Nachhaltigkeit', 'Leidenschaftlich', 'Vanille', 'Faszinierend', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Gemüse', 'Belebend', 'Whisky', 'Theater', 'Landschaft', 'Gefühl', 'Festung', 'Straße', 'Tür', 'Fleisch', 'Geheimnis', 'Theater', 'Pasta', 'Samstag', 'Engagement', 'Triumph', 'Faszinierend', 'Mut', 'Weizen', 'Freundlichkeit', 'Frieden', 'Nachhaltigkeit', 'Beharrlichkeit', 'Stadt', 'Architektur', 'Party', 'Träumer', 'Pflegen', 'Stärke', 'Seufz', 'Zärtlichkeit', 'Demut', 'Aufstieg', 'Apfel', 'Auto', 'Glänzen', 'Single', 'Beziehungen', 'Fröhlich', 'Belebend', 'Freundlich', 'Aufregend', 'Avenue', 'Beauty', 'Gelb', 'Defiance', 'Kultur', 'Effizienz', 'Batterie', 'Majestätisch', 'Scanner', 'Salz', 'Begleiter', 'Familie', 'Lebendig', 'Umgebung', 'Lernen', 'Anwalt', 'Unterhaltung', 'Werte', 'Shop', 'Akzeptanz', 'Familie', 'Wissen', 'Stärke', 'Geist', 'Mutig', 'Revolution', 'Fürsorge', 'Entdecker', 'Strand', 'Sofa', 'Freundschaft', 'Bus', 'Fisch', 'Tanz', 'Verzauberung', 'Berg', 'Wald', 'Überleben', 'Unvergleichlich', 'Krankenhaus', 'Garten', 'Legende', 'Allee', 'Sublimation', 'Salat', 'Schicksal', 'Art', 'Süß', 'Ewigkeit', 'Hut', 'Ewig', 'Liebend', 'Farbe', 'Herz', 'Konstanz', 'Stuhl', 'Meister', 'Automobil', 'Metropolis', 'Vibrant', 'Tea', 'Dezent', 'Brush', 'Harmony', 'Fullness', 'Addictive', 'Violine', 'Meta', 'Plethoric', 'Thought', 'Lamp', 'Vergnügen', 'Einfallsreichtum', 'Herausforderungen', 'Erstaunlich', 'Job', 'Strand', 'Schutz', 'Morgen', 'Wütend', 'Ehrlichkeit', 'Fantastisch', 'Fesselnd' , 'Überrascht', 'Verwandlung', 'Sommer', 'Mathe', 'Ruhe', 'Motorrad', 'Löwe', 'Komfort', 'Erinnerungen', 'Gesellschaft', 'Drop', 'Traum', ' Bewegen', 'Entwicklung', 'Weisheit', 'Verheiratet', 'Verheiratet', 'Liebe', 'Mode', 'Kunst', 'Heroisch', 'Medizin', 'Souvenir', 'Transzendental', 'Autonomie', 'Decke', 'Philosophie', 'Erstaunlich', 'Sorority', 'Papier', 'Toleranz', 'Wand', 'Schule', 'Aufstieg', 'Zucker', 'Gleichheit', 'Nachmittag', 'Soda', 'Zukunft', 'Paradise', 'Ingenieurwesen', 'Erhaben', 'Ruhe', 'Butter', 'Romantik', 'Mittag', 'Blitz', 'Großzügig', 'Motivation', ' Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividity', 'Exteriors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder' , 'Berauschend', 'Vielversprechend', 'Bildung', 'Sushi', 'Patient', 'Innovation', 'Landwirtschaft', 'Entschlossenheit', 'Donner', 'Energie', 'Libelle', 'Erstaunlich', 'Lösung', 'Blitz', 'Tiger', 'Katze', 'Widmung', 'Boot', 'Exaltation', 'Spülung', 'Leidenschaft', 'Ökologie', 'Ehrlichkeit', ' Emotion', 'Laufen', 'Technologie', 'Enthüller', 'Erkunden', 'Glare', 'Erwachen', 'Wein', 'Traurigkeit', 'Geschichte', 'Mond', 'Studie', 'Gesundheit' , 'Weisheit', 'Exorbitant', 'Schön', 'Milch', 'Ziele', 'Schal', 'Schwimmen', 'Kunst', 'Tal', 'Fluss', 'Natur', 'Hamburger', ' Geschichte', 'Wohlbefinden', 'Segen', 'Spaß', 'Erkundung', 'Natur', 'Unruhe', 'Melodie', 'Philanthropie', 'Schal', 'Belebend', 'Gesang', ' Toleranz', 'Drop', 'Blick', 'Entdecken', 'Salz', 'Spaß', 'Stadt', 'Verzeihung', 'Menschen', 'Serendipity', 'Solidarität', 'Sonntag', 'Erbe' , 'Fußball', 'Gemeinschaft', 'Herrlich', 'Regenbogen', 'Ermutigung', 'Disziplin', 'Kindergarten', 'Großartig', 'Sehnsucht', 'Hingabe', 'Musik', 'Hilfreich', ' Gesundheit', 'Tür', 'Geschäft', 'Fenster', 'Sensibilität', 'Zug', 'Stabilität', 'Giraffe', 'Rätsel', 'Mut', 'Saft', 'Magie', 'Wort' , 'Einzigartig', 'Klavier', 'Metropolis', 'Produktivität', 'Exhilaration', 'Malerisch', 'Metropolis', 'Erfrischend', 'Schock', 'Reise', 'Mut', 'Schockierend', ' Singen', 'Feier', 'Zusammenarbeit', 'Tanz', 'Spülen', 'Verzauberung', 'Religion', 'Idylle', 'Generation', 'Transzendent', 'Feder', 'Weizen', 'Zufriedenheit' , 'Geschäft', 'Reptil', 'Obst', 'Tisch', 'Organisation', 'Sterne', 'Drucker', 'Ziel', 'Motivation', 'Furchtlosigkeit', 'Gleichgewicht', 'Ruhe', ' Geburtstag', 'Geschieden', 'Glanz', 'Zusammenarbeit', 'Grün', 'Dessert', 'Melancholie', 'Fotografie', 'Lachen', 'Aroma', 'Frucht', 'Entspannung', 'Tau' , 'Kraft', 'Großzügigkeit', 'Lächeln', 'Herbst', 'Impuls', 'Charme', 'Bezaubernd', 'Salzig', 'Klarheit', 'Blau', 'Begeisterung', 'Schönheit', ' Wachstum', 'Zucker', 'Öl', 'Regenbogen', 'Reise', 'Hamster', 'Überraschung', 'Abenteurer', 'Kaffee', 'Erstaunlich', 'Neugier', 'Faden', 'Fisch' , 'Bemerkenswert', 'Verständnis', 'Butter', 'Früher Morgen', 'Student', 'Frühling', 'See', 'Therapie', 'Fähigkeit', 'Anmut', 'Unübertroffen', 'Zweck', 'Kuss', 'Feline', 'Single', 'Frieden', 'Techniker', 'Birne', 'Tanz', 'Kolibri', 'Flugzeug', 'See', 'Berauschend', 'Euphorisch', 'Aufregend', ' Festival', 'Sonne', 'Pants', 'Sprung', 'Boot', 'Keramik', 'Interdependenz', 'Spiel', 'Eloquenz', 'Stimuliert', 'Essenz', 'Salzig', 'Vertrauen', 'Hafer', 'Ethik', 'Initiative', 'Banane', 'Wolke', 'Üppig', 'Schreiben', 'Begegnung', 'Ernährung', 'Wunsch', 'Edel', 'Spiritualität', 'Kooperation', 'Harmonie', 'Pfeffer', 'Verbesserung', 'Erhaben', 'Schillernd', 'Tradition', 'Flexibilität', 'Universum', 'Giraffe', 'Straße', 'Vielfalt', 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-Shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Atemberaubend', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Unternehmertum', 'Thunder', 'Exzentrizität', 'Dorf', 'Gefühle', 'Elektrisiert', 'Faszinierend', 'Dankbarkeit', 'Zimt', 'Sieg', 'Loyalität', 'Fahrrad', 'Mais', 'Erfolg', 'Emotion', 'Bildung', 'Wasserfall', 'Freiheit', 'Zahnmedizin', 'Integrität', 'Sofa', 'Forschung', 'Käse', 'Erleuchtung', 'Großzügigkeit', 'Leidenschaft', 'Erde', 'Poesie', 'Opfer', 'Belastbarkeit', 'Wunderbar', 'Energetisch', 'Fenster']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Wort", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("errate einen Buchstaben: ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Richtig!")

                    else:
                        intentos_restantes -= 1
                        print("Falsch. Du bist gegangen", intentos_restantes, "Versuche.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gewonnen! Sie haben das Wort erraten:", palabra)
                        break

                if intentos_restantes == 0:
                        print("Du hast verloren! Das Wort war:", palabra)


            print("Spieler 1:")
            jugar_ahorcado()
            print("Spieler 2:")
            jugar_ahorcado()
            
        elif b == 2:


            lista = ['Kameradschaft' , 'Keks', 'Umarmung', 'Loyalität', 'Bereichernd', 'Herbst', 'Ehrgeiz', 'Hell', 'Stille', 'Wissenschaft', 'Rot', 'Bleistift', 'Zimt', 'Luft', 'Liebe', 'Autobahn', 'Geduld', 'Einsamkeit', 'Strategie', 'Durchbruch', 'Mode', 'Wachstum', 'Hartnäckigkeit', 'Aufgeregt', 'Literatur', 'Party', 'Hoffnung', 'Inspirierend', 'Innovation', 'Kreativität', 'Elektrisierend', 'Staunen', 'Fleisch', 'Uhr', 'Stille', 'Überschrift', 'Schnee', 'Bogen', 'Fähigkeit', 'Schlaf', 'Orange', 'Wunder', 'Freundlichkeit', 'Veränderung', 'Computer', 'Musik', 'Traube', 'Epiphanie', 'Laufen', 'Dankbarkeit', 'Führung', 'Geheimnis', 'Brille', 'Kommunikation', 'Offenbarung', 'Gefeiert', 'Tränen', 'Wegbereiter', 'Flüstern', 'Schnee', 'Horizont', 'Anzeigetafel', 'Entdeckung', 'Stil', 'Bezaubernd', 'Sport', 'Literatur', 'Heilen', 'Gelassenheit', 'Hund', 'Erfrischend', 'Wunder', 'Büro', 'Entspannung', 'Stil' , 'Vitalität', 'Erhaltung', 'Würde', 'Erlösung', 'Schwimmen', 'Ruhe', 'Aufregend', 'Karriere', 'Haferflocken', 'Leistung', 'Applaudiert', 'Zeit', ' Joghurt', 'Ozean', 'Kino', 'Dorf', 'Zufriedenheit', 'Kaffee', 'Gitarre', 'Wasser', 'Kreide', 'Verantwortung', 'Prestige', 'Vergnügen', 'Weinen' , 'Optimismus', 'Team', 'Gleichheit', 'Vanilla', 'Tanz', 'Bus', 'Hobby', 'Fantasie', 'Unwiderstehlich', 'Glühen', 'Anpassungsfähigkeit', 'Wertschätzung', 'Stift', 'Freiwilligenarbeit', 'Hoffnung', 'Faszinierend', 'Aufklärend', 'Erhebend', 'Impressionismus', 'Dienstag', 'Architektur', 'Fortschritt', 'Sterne', 'Gemeinschaft', 'Bedeutsam' , 'Herrlich', 'Hügel', 'Umgebung', 'Erfrischung', 'Dämmerung', 'Unschuld', 'Mais', 'Mut', 'Überrascht', 'Übung', 'Warten', 'Foto', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Dorf', 'Glow' , 'Reflexion', 'Tanz', 'Feder', 'Widmung', 'Freude', 'Lachen', 'Verlieben', 'Kuchen', 'Sport', 'Neuerfindung', 'Kakao', 'Gastronomie', 'Symmetrie', 'Brüderlichkeit', 'Ingenieur', 'Erfüllend', 'Kakao', 'Aspiration', 'Authentizität', 'Demut', 'Intrige', 'Vergnügen', 'Bewusstsein', 'Berauschend', 'Anwalt', 'Geld', 'Joghurt', 'Fahrt', 'Computer', 'Saft', 'Feuer', 'Rückenwind', 'Faszination', 'Planet', 'Glück', 'Katze', 'Größe' , 'Elefant', 'Süß', 'Kaninchen', 'Einfach', 'Bitter', 'Wasser', 'Buch', 'Winter', 'Arbeit', 'Attraktiv', 'Optimismus', 'Skulptur', 'Gastronomie', 'Schön', 'Brillen', 'Fußball', 'Wunderkind', 'Erlebnis', 'Lassen Sie sich inspirieren', 'Meer', 'Mystisch', 'Natur', 'Schreiben', 'Fantasie', ' Gehen', 'Freude', 'Universum', 'Te', 'Ausdruck', 'Lachen', 'Spiritualität', 'Verjüngung', 'Fluss', 'Glück', 'Banane', 'Yoga', 'Emotional' , 'Gelegenheit', 'Zuhause', 'Stift', 'Geduld', 'Straße', 'Freude', 'Vertrauen', 'Anziehung', 'Träumen', 'Fantastisch', 'Geburtstag', 'Albtraum', ' Staunen', 'Wolken', 'Herrlich', 'Balance', 'Zusammenarbeit', 'Raum', 'Empowerment', 'Design', 'Lernen', 'Emotional', 'Belastbarkeit', 'Basketball', 'Glühen' , 'Empathie', 'Innenräume', 'Atemberaubend', 'Unvergesslich', 'Bewunderung', 'Schön', 'Berg', 'Verwirklichung', 'Säure', 'Schreiben', 'Umarmung', 'Keramik', ' Springen', 'Aktion', 'Seufz', 'Wütend', 'Tisch', 'Hut', 'Motorrad', 'Bier', 'Schuhe', 'Wahrheit', 'Aufregend', 'Stern', 'Urlaub' , 'Rhythmus', 'Himmel', 'Zeitvertreib', 'Bunt', 'Reisen', 'Tau', 'Wunderbar', 'Psychologie', 'Sonnenaufgang', 'Dankbarkeit', 'Herausforderung', 'Schwimmen', ' Analyse', 'Exquisit', 'Erbe', 'Fernsehen', 'Hosen', 'Geschenk', 'Belohnung', 'Wüste', 'Adel', 'Verbindung', 'Geschichte', 'Schule', 'Reife' , 'Regen', 'Lampe', 'Spontanität', 'Claro', 'Sternbild', 'Maus', 'Kultur', 'Frisch', 'Inspiration', 'Sonnengitarre', 'Buch', 'Vielfalt', 'Risiko', 'Orange', 'Universität', 'Entschlossenheit', 'Festival', 'Freundlichkeit', 'Brise', 'Hamster', 'Autobahn', 'Wunder', 'Biene', 'Hoffnung', 'Wissen', 'Hügel', 'Hamster', 'Sanft', 'Energie', 'Strahlend', 'Medizin', 'Schwimmen', 'Wasserfall', 'Zärtlich', 'Warm', 'Freundschaft', 'Telefon', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Aufrichtigkeit', 'Nachhaltigkeit', 'Freundlichkeit', 'Dschungel', 'Leuchtkraft', 'Fokus', 'Hund', 'Universität', 'Pflege', 'Entdeckung', 'Garten', 'Fähigkeit', 'Trainieren', 'Beleuchtung', 'Planung', 'Sand', 'Tennis', 'Überschwänglich', 'Überwindung', 'Sommer', 'Ingenieur', 'Wald', 'Sturm', 'Transzendenz', 'Geschieden', 'Harmonie', 'Empathie', 'Respekt', ' Uhr', 'Freund', 'Garn', 'Joghurt', 'Schule', 'Serendipity', 'Flugzeug', 'Spiel', 'Lachen', 'Fülle', 'Skulptur', 'Krankenhaus', 'Lächeln', 'Fesselnd', 'Intuition', 'Erfahrung', 'Pracht', 'Ozean', 'Wohlstand', 'Bewusstsein', ' Tequila', 'Jubiläum', 'Verführung', 'Führung', 'hervorragend', 'Schnitte', 'Erneuerung', 'Valle', 'Morgen', 'Nacht', 'Winter', 'Charisma', 'Evolution' , 'Flexibilität', 'Energetisch', 'Veränderung', 'Basketball', 'Professionalität', 'Inspiration', 'Aufregend', 'Wunderbar', 'Erfolg', 'Solidarität', 'Wiedergeburt', 'Gemüse', ' Kleid', 'Muscheln', 'Meer', 'Medizin', 'Glaube', 'T-Shirt', 'Kreativität', 'Bitter', 'Feier', 'Vitalität', 'Blumen', 'Nacht', ' Lachen', 'Bonus', 'Abenteuer', 'Pfeffer', 'Frühling', 'Aufregung', 'Dach', 'Zucker', 'Kleid', 'Ruhe', 'Freiheit', 'Ruhe', 'Bewusstsein' , 'Jubiläum', 'Momente', 'Glücklich', 'Galaxie', 'Authentizität', 'Meditation', 'Kompetenz', 'Baum', 'Ernährung', 'Herrlich', 'Wissenschaft', 'Erhebung', ' Luft', 'Gerechtigkeit', 'Effizienz', 'Charme', 'Feuer', 'Tradition', 'Oase', 'Überraschung', 'Lehre', 'Freude', 'Träumen', 'Überfließend', 'Abenteuer' , 'Fernsehen', 'Schuhe', 'Schokolade', 'Hund', 'Inspiration', 'Hochzeit', 'Anger', 'Leidenschaftlich', 'Medizin', 'Pinsel', 'Klarheit', 'Surround', ' Pizza', 'Mond', 'Gerechtigkeit', 'Ermächtigung', 'Stuhl', 'Überlauf', 'Wind', 'Reichtum', 'Erinnerungen', 'Begeisterung', 'Technologie', 'Shop', 'Galaxie' , 'Magie', 'Charmant', 'Pasta', 'Überschwänglichkeit', 'Gerechtigkeit', 'Kino', 'Ausdauer', 'Organisation', 'Ausdauer', 'Karriere', 'Erstaunlich', 'Träume', ' Originalität', 'Außergewöhnlich', 'Bedeutsam', 'Büro', 'Einfach', 'Milch', 'Skateboard', 'Mobilfunk', 'Intelligenz', 'Entspannend', 'Sound', 'Ausbruch', 'Sonnenuntergang' , 'Inspirierend', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Watchful', 'Ice Cream', 'Evening', 'Bleistift', 'Zugehörigkeit', 'Unternehmertum', 'Integrität', 'Unschuld', 'Harmonie', 'Selbstwertgefühl', 'Freude', 'Tee', 'Notizbuch', 'Malerei', 'Reis', 'Bereicherung', 'Motivator', 'Inklusion', 'Apfel', 'Achtsamkeit', 'Respekt', 'Erforschung', 'Nachbar', 'Reichtum', 'Transformation', 'Farbe', 'Freude', 'Chaos', 'Erde', 'Schmetterling', 'Bewunderung', 'Exotisch', 'Nachhaltigkeit', 'Leidenschaftlich', 'Vanille', 'Faszinierend', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Gemüse', 'Belebend', 'Whisky', 'Theater', 'Landschaft', 'Gefühl', 'Festung', 'Straße', 'Tür', 'Fleisch', 'Geheimnis', 'Theater', 'Pasta', 'Samstag', 'Engagement', 'Triumph', 'Faszinierend', 'Mut', 'Weizen', 'Freundlichkeit', 'Frieden', 'Nachhaltigkeit', 'Beharrlichkeit', 'Stadt', 'Architektur', 'Party', 'Träumer', 'Pflegen', 'Stärke', 'Seufz', 'Zärtlichkeit', 'Demut', 'Aufstieg', 'Apfel', 'Auto', 'Glänzen', 'Single', 'Beziehungen', 'Fröhlich', 'Belebend', 'Freundlich', 'Aufregend', 'Avenue', 'Beauty', 'Gelb', 'Defiance', 'Kultur', 'Effizienz', 'Batterie', 'Majestätisch', 'Scanner', 'Salz', 'Begleiter', 'Familie', 'Lebendig', 'Umgebung', 'Lernen', 'Anwalt', 'Unterhaltung', 'Werte', 'Shop', 'Akzeptanz', 'Familie', 'Wissen', 'Stärke', 'Geist', 'Mutig', 'Revolution', 'Fürsorge', 'Entdecker', 'Strand', 'Sofa', 'Freundschaft', 'Bus', 'Fisch', 'Tanz', 'Verzauberung', 'Berg', 'Wald', 'Überleben', 'Unvergleichlich', 'Krankenhaus', 'Garten', 'Legende', 'Allee', 'Sublimation', 'Salat', 'Schicksal', 'Art', 'Süß', 'Ewigkeit', 'Hut', 'Ewig', 'Liebend', 'Farbe', 'Herz', 'Konstanz', 'Stuhl', 'Meister', 'Automobil', 'Metropolis', 'Vibrant', 'Tea', 'Dezent', 'Brush', 'Harmony', 'Fullness', 'Addictive', 'Violine', 'Meta', 'Plethoric', 'Thought', 'Lamp', 'Vergnügen', 'Einfallsreichtum', 'Herausforderungen', 'Erstaunlich', 'Job', 'Strand', 'Schutz', 'Morgen', 'Wütend', 'Ehrlichkeit', 'Fantastisch', 'Fesselnd' , 'Überrascht', 'Verwandlung', 'Sommer', 'Mathe', 'Ruhe', 'Motorrad', 'Löwe', 'Komfort', 'Erinnerungen', 'Gesellschaft', 'Drop', 'Traum', ' Bewegen', 'Entwicklung', 'Weisheit', 'Verheiratet', 'Verheiratet', 'Liebe', 'Mode', 'Kunst', 'Heroisch', 'Medizin', 'Souvenir', 'Transzendental', 'Autonomie', 'Decke', 'Philosophie', 'Erstaunlich', 'Sorority', 'Papier', 'Toleranz', 'Wand', 'Schule', 'Aufstieg', 'Zucker', 'Gleichheit', 'Nachmittag', 'Soda', 'Zukunft', 'Paradise', 'Ingenieurwesen', 'Erhaben', 'Ruhe', 'Butter', 'Romantik', 'Mittag', 'Blitz', 'Großzügig', 'Motivation', ' Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividity', 'Exteriors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder' , 'Berauschend', 'Vielversprechend', 'Bildung', 'Sushi', 'Patient', 'Innovation', 'Landwirtschaft', 'Entschlossenheit', 'Donner', 'Energie', 'Libelle', 'Erstaunlich', 'Lösung', 'Blitz', 'Tiger', 'Katze', 'Widmung', 'Boot', 'Exaltation', 'Spülung', 'Leidenschaft', 'Ökologie', 'Ehrlichkeit', ' Emotion', 'Laufen', 'Technologie', 'Enthüller', 'Erkunden', 'Glare', 'Erwachen', 'Wein', 'Traurigkeit', 'Geschichte', 'Mond', 'Studie', 'Gesundheit' , 'Weisheit', 'Exorbitant', 'Schön', 'Milch', 'Ziele', 'Schal', 'Schwimmen', 'Kunst', 'Tal', 'Fluss', 'Natur', 'Hamburger', ' Geschichte', 'Wohlbefinden', 'Segen', 'Spaß', 'Erkundung', 'Natur', 'Unruhe', 'Melodie', 'Philanthropie', 'Schal', 'Belebend', 'Gesang', ' Toleranz', 'Drop', 'Blick', 'Entdecken', 'Salz', 'Spaß', 'Stadt', 'Verzeihung', 'Menschen', 'Serendipity', 'Solidarität', 'Sonntag', 'Erbe' , 'Fußball', 'Gemeinschaft', 'Herrlich', 'Regenbogen', 'Ermutigung', 'Disziplin', 'Kindergarten', 'Großartig', 'Sehnsucht', 'Hingabe', 'Musik', 'Hilfreich', ' Gesundheit', 'Tür', 'Geschäft', 'Fenster', 'Sensibilität', 'Zug', 'Stabilität', 'Giraffe', 'Rätsel', 'Mut', 'Saft', 'Magie', 'Wort' , 'Einzigartig', 'Klavier', 'Metropolis', 'Produktivität', 'Exhilaration', 'Malerisch', 'Metropolis', 'Erfrischend', 'Schock', 'Reise', 'Mut', 'Schockierend', ' Singen', 'Feier', 'Zusammenarbeit', 'Tanz', 'Spülen', 'Verzauberung', 'Religion', 'Idylle', 'Generation', 'Transzendent', 'Feder', 'Weizen', 'Zufriedenheit' , 'Geschäft', 'Reptil', 'Obst', 'Tisch', 'Organisation', 'Sterne', 'Drucker', 'Ziel', 'Motivation', 'Furchtlosigkeit', 'Gleichgewicht', 'Ruhe', ' Geburtstag', 'Geschieden', 'Glanz', 'Zusammenarbeit', 'Grün', 'Dessert', 'Melancholie', 'Fotografie', 'Lachen', 'Aroma', 'Frucht', 'Entspannung', 'Tau' , 'Kraft', 'Großzügigkeit', 'Lächeln', 'Herbst', 'Impuls', 'Charme', 'Bezaubernd', 'Salzig', 'Klarheit', 'Blau', 'Begeisterung', 'Schönheit', ' Wachstum', 'Zucker', 'Öl', 'Regenbogen', 'Reise', 'Hamster', 'Überraschung', 'Abenteurer', 'Kaffee', 'Erstaunlich', 'Neugier', 'Faden', 'Fisch' , 'Bemerkenswert', 'Verständnis', 'Butter', 'Früher Morgen', 'Student', 'Frühling', 'See', 'Therapie', 'Fähigkeit', 'Anmut', 'Unübertroffen', 'Zweck', 'Kuss', 'Feline', 'Single', 'Frieden', 'Techniker', 'Birne', 'Tanz', 'Kolibri', 'Flugzeug', 'See', 'Berauschend', 'Euphorisch', 'Aufregend', ' Festival', 'Sonne', 'Pants', 'Sprung', 'Boot', 'Keramik', 'Interdependenz', 'Spiel', 'Eloquenz', 'Stimuliert', 'Essenz', 'Salzig', 'Vertrauen', 'Hafer', 'Ethik', 'Initiative', 'Banane', 'Wolke', 'Üppig', 'Schreiben', 'Begegnung', 'Ernährung', 'Wunsch', 'Edel', 'Spiritualität', 'Kooperation', 'Harmonie', 'Pfeffer', 'Verbesserung', 'Erhaben', 'Schillernd', 'Tradition', 'Flexibilität', 'Universum', 'Giraffe', 'Straße', 'Vielfalt', 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-Shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Atemberaubend', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Unternehmertum', 'Thunder', 'Exzentrizität', 'Dorf', 'Gefühle', 'Elektrisiert', 'Faszinierend', 'Dankbarkeit', 'Zimt', 'Sieg', 'Loyalität', 'Fahrrad', 'Mais', 'Erfolg', 'Emotion', 'Bildung', 'Wasserfall', 'Freiheit', 'Zahnmedizin', 'Integrität', 'Sofa', 'Forschung', 'Käse', 'Erleuchtung', 'Großzügigkeit', 'Leidenschaft', 'Erde', 'Poesie', 'Opfer', 'Belastbarkeit', 'Wunderbar', 'Energetisch', 'Fenster']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Wort:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("errate einen Buchstaben: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Richtig!")

                    else:
                        intentos_restantes -= 1
                        print("Falsch. Du bist gegangen", intentos_restantes, "Versuche.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gewonnen! Sie haben das Wort erraten:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Du hast verloren! Das Wort war:", palabra)



            print("Spieler 1:")
            jugar_ahorcado()
            print("Spieler 2:")
            jugar_ahorcado()


        elif b == 3:

            import random
            lista = ['Kameradschaft' , 'Keks', 'Umarmung', 'Loyalität', 'Bereichernd', 'Herbst', 'Ehrgeiz', 'Hell', 'Stille', 'Wissenschaft', 'Rot', 'Bleistift', 'Zimt', 'Luft', 'Liebe', 'Autobahn', 'Geduld', 'Einsamkeit', 'Strategie', 'Durchbruch', 'Mode', 'Wachstum', 'Hartnäckigkeit', 'Aufgeregt', 'Literatur', 'Party', 'Hoffnung', 'Inspirierend', 'Innovation', 'Kreativität', 'Elektrisierend', 'Staunen', 'Fleisch', 'Uhr', 'Stille', 'Überschrift', 'Schnee', 'Bogen', 'Fähigkeit', 'Schlaf', 'Orange', 'Wunder', 'Freundlichkeit', 'Veränderung', 'Computer', 'Musik', 'Traube', 'Epiphanie', 'Laufen', 'Dankbarkeit', 'Führung', 'Geheimnis', 'Brille', 'Kommunikation', 'Offenbarung', 'Gefeiert', 'Tränen', 'Wegbereiter', 'Flüstern', 'Schnee', 'Horizont', 'Anzeigetafel', 'Entdeckung', 'Stil', 'Bezaubernd', 'Sport', 'Literatur', 'Heilen', 'Gelassenheit', 'Hund', 'Erfrischend', 'Wunder', 'Büro', 'Entspannung', 'Stil' , 'Vitalität', 'Erhaltung', 'Würde', 'Erlösung', 'Schwimmen', 'Ruhe', 'Aufregend', 'Karriere', 'Haferflocken', 'Leistung', 'Applaudiert', 'Zeit', ' Joghurt', 'Ozean', 'Kino', 'Dorf', 'Zufriedenheit', 'Kaffee', 'Gitarre', 'Wasser', 'Kreide', 'Verantwortung', 'Prestige', 'Vergnügen', 'Weinen' , 'Optimismus', 'Team', 'Gleichheit', 'Vanilla', 'Tanz', 'Bus', 'Hobby', 'Fantasie', 'Unwiderstehlich', 'Glühen', 'Anpassungsfähigkeit', 'Wertschätzung', 'Stift', 'Freiwilligenarbeit', 'Hoffnung', 'Faszinierend', 'Aufklärend', 'Erhebend', 'Impressionismus', 'Dienstag', 'Architektur', 'Fortschritt', 'Sterne', 'Gemeinschaft', 'Bedeutsam' , 'Herrlich', 'Hügel', 'Umgebung', 'Erfrischung', 'Dämmerung', 'Unschuld', 'Mais', 'Mut', 'Überrascht', 'Übung', 'Warten', 'Foto', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Dorf', 'Glow' , 'Reflexion', 'Tanz', 'Feder', 'Widmung', 'Freude', 'Lachen', 'Verlieben', 'Kuchen', 'Sport', 'Neuerfindung', 'Kakao', 'Gastronomie', 'Symmetrie', 'Brüderlichkeit', 'Ingenieur', 'Erfüllend', 'Kakao', 'Aspiration', 'Authentizität', 'Demut', 'Intrige', 'Vergnügen', 'Bewusstsein', 'Berauschend', 'Anwalt', 'Geld', 'Joghurt', 'Fahrt', 'Computer', 'Saft', 'Feuer', 'Rückenwind', 'Faszination', 'Planet', 'Glück', 'Katze', 'Größe' , 'Elefant', 'Süß', 'Kaninchen', 'Einfach', 'Bitter', 'Wasser', 'Buch', 'Winter', 'Arbeit', 'Attraktiv', 'Optimismus', 'Skulptur', 'Gastronomie', 'Schön', 'Brillen', 'Fußball', 'Wunderkind', 'Erlebnis', 'Lassen Sie sich inspirieren', 'Meer', 'Mystisch', 'Natur', 'Schreiben', 'Fantasie', ' Gehen', 'Freude', 'Universum', 'Te', 'Ausdruck', 'Lachen', 'Spiritualität', 'Verjüngung', 'Fluss', 'Glück', 'Banane', 'Yoga', 'Emotional' , 'Gelegenheit', 'Zuhause', 'Stift', 'Geduld', 'Straße', 'Freude', 'Vertrauen', 'Anziehung', 'Träumen', 'Fantastisch', 'Geburtstag', 'Albtraum', ' Staunen', 'Wolken', 'Herrlich', 'Balance', 'Zusammenarbeit', 'Raum', 'Empowerment', 'Design', 'Lernen', 'Emotional', 'Belastbarkeit', 'Basketball', 'Glühen' , 'Empathie', 'Innenräume', 'Atemberaubend', 'Unvergesslich', 'Bewunderung', 'Schön', 'Berg', 'Verwirklichung', 'Säure', 'Schreiben', 'Umarmung', 'Keramik', ' Springen', 'Aktion', 'Seufz', 'Wütend', 'Tisch', 'Hut', 'Motorrad', 'Bier', 'Schuhe', 'Wahrheit', 'Aufregend', 'Stern', 'Urlaub' , 'Rhythmus', 'Himmel', 'Zeitvertreib', 'Bunt', 'Reisen', 'Tau', 'Wunderbar', 'Psychologie', 'Sonnenaufgang', 'Dankbarkeit', 'Herausforderung', 'Schwimmen', ' Analyse', 'Exquisit', 'Erbe', 'Fernsehen', 'Hosen', 'Geschenk', 'Belohnung', 'Wüste', 'Adel', 'Verbindung', 'Geschichte', 'Schule', 'Reife' , 'Regen', 'Lampe', 'Spontanität', 'Claro', 'Sternbild', 'Maus', 'Kultur', 'Frisch', 'Inspiration', 'Sonnengitarre', 'Buch', 'Vielfalt', 'Risiko', 'Orange', 'Universität', 'Entschlossenheit', 'Festival', 'Freundlichkeit', 'Brise', 'Hamster', 'Autobahn', 'Wunder', 'Biene', 'Hoffnung', 'Wissen', 'Hügel', 'Hamster', 'Sanft', 'Energie', 'Strahlend', 'Medizin', 'Schwimmen', 'Wasserfall', 'Zärtlich', 'Warm', 'Freundschaft', 'Telefon', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Aufrichtigkeit', 'Nachhaltigkeit', 'Freundlichkeit', 'Dschungel', 'Leuchtkraft', 'Fokus', 'Hund', 'Universität', 'Pflege', 'Entdeckung', 'Garten', 'Fähigkeit', 'Trainieren', 'Beleuchtung', 'Planung', 'Sand', 'Tennis', 'Überschwänglich', 'Überwindung', 'Sommer', 'Ingenieur', 'Wald', 'Sturm', 'Transzendenz', 'Geschieden', 'Harmonie', 'Empathie', 'Respekt', ' Uhr', 'Freund', 'Garn', 'Joghurt', 'Schule', 'Serendipity', 'Flugzeug', 'Spiel', 'Lachen', 'Fülle', 'Skulptur', 'Krankenhaus', 'Lächeln', 'Fesselnd', 'Intuition', 'Erfahrung', 'Pracht', 'Ozean', 'Wohlstand', 'Bewusstsein', ' Tequila', 'Jubiläum', 'Verführung', 'Führung', 'hervorragend', 'Schnitte', 'Erneuerung', 'Valle', 'Morgen', 'Nacht', 'Winter', 'Charisma', 'Evolution' , 'Flexibilität', 'Energetisch', 'Veränderung', 'Basketball', 'Professionalität', 'Inspiration', 'Aufregend', 'Wunderbar', 'Erfolg', 'Solidarität', 'Wiedergeburt', 'Gemüse', ' Kleid', 'Muscheln', 'Meer', 'Medizin', 'Glaube', 'T-Shirt', 'Kreativität', 'Bitter', 'Feier', 'Vitalität', 'Blumen', 'Nacht', ' Lachen', 'Bonus', 'Abenteuer', 'Pfeffer', 'Frühling', 'Aufregung', 'Dach', 'Zucker', 'Kleid', 'Ruhe', 'Freiheit', 'Ruhe', 'Bewusstsein' , 'Jubiläum', 'Momente', 'Glücklich', 'Galaxie', 'Authentizität', 'Meditation', 'Kompetenz', 'Baum', 'Ernährung', 'Herrlich', 'Wissenschaft', 'Erhebung', ' Luft', 'Gerechtigkeit', 'Effizienz', 'Charme', 'Feuer', 'Tradition', 'Oase', 'Überraschung', 'Lehre', 'Freude', 'Träumen', 'Überfließend', 'Abenteuer' , 'Fernsehen', 'Schuhe', 'Schokolade', 'Hund', 'Inspiration', 'Hochzeit', 'Anger', 'Leidenschaftlich', 'Medizin', 'Pinsel', 'Klarheit', 'Surround', ' Pizza', 'Mond', 'Gerechtigkeit', 'Ermächtigung', 'Stuhl', 'Überlauf', 'Wind', 'Reichtum', 'Erinnerungen', 'Begeisterung', 'Technologie', 'Shop', 'Galaxie' , 'Magie', 'Charmant', 'Pasta', 'Überschwänglichkeit', 'Gerechtigkeit', 'Kino', 'Ausdauer', 'Organisation', 'Ausdauer', 'Karriere', 'Erstaunlich', 'Träume', ' Originalität', 'Außergewöhnlich', 'Bedeutsam', 'Büro', 'Einfach', 'Milch', 'Skateboard', 'Mobilfunk', 'Intelligenz', 'Entspannend', 'Sound', 'Ausbruch', 'Sonnenuntergang' , 'Inspirierend', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Watchful', 'Ice Cream', 'Evening', 'Bleistift', 'Zugehörigkeit', 'Unternehmertum', 'Integrität', 'Unschuld', 'Harmonie', 'Selbstwertgefühl', 'Freude', 'Tee', 'Notizbuch', 'Malerei', 'Reis', 'Bereicherung', 'Motivator', 'Inklusion', 'Apfel', 'Achtsamkeit', 'Respekt', 'Erforschung', 'Nachbar', 'Reichtum', 'Transformation', 'Farbe', 'Freude', 'Chaos', 'Erde', 'Schmetterling', 'Bewunderung', 'Exotisch', 'Nachhaltigkeit', 'Leidenschaftlich', 'Vanille', 'Faszinierend', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Gemüse', 'Belebend', 'Whisky', 'Theater', 'Landschaft', 'Gefühl', 'Festung', 'Straße', 'Tür', 'Fleisch', 'Geheimnis', 'Theater', 'Pasta', 'Samstag', 'Engagement', 'Triumph', 'Faszinierend', 'Mut', 'Weizen', 'Freundlichkeit', 'Frieden', 'Nachhaltigkeit', 'Beharrlichkeit', 'Stadt', 'Architektur', 'Party', 'Träumer', 'Pflegen', 'Stärke', 'Seufz', 'Zärtlichkeit', 'Demut', 'Aufstieg', 'Apfel', 'Auto', 'Glänzen', 'Single', 'Beziehungen', 'Fröhlich', 'Belebend', 'Freundlich', 'Aufregend', 'Avenue', 'Beauty', 'Gelb', 'Defiance', 'Kultur', 'Effizienz', 'Batterie', 'Majestätisch', 'Scanner', 'Salz', 'Begleiter', 'Familie', 'Lebendig', 'Umgebung', 'Lernen', 'Anwalt', 'Unterhaltung', 'Werte', 'Shop', 'Akzeptanz', 'Familie', 'Wissen', 'Stärke', 'Geist', 'Mutig', 'Revolution', 'Fürsorge', 'Entdecker', 'Strand', 'Sofa', 'Freundschaft', 'Bus', 'Fisch', 'Tanz', 'Verzauberung', 'Berg', 'Wald', 'Überleben', 'Unvergleichlich', 'Krankenhaus', 'Garten', 'Legende', 'Allee', 'Sublimation', 'Salat', 'Schicksal', 'Art', 'Süß', 'Ewigkeit', 'Hut', 'Ewig', 'Liebend', 'Farbe', 'Herz', 'Konstanz', 'Stuhl', 'Meister', 'Automobil', 'Metropolis', 'Vibrant', 'Tea', 'Dezent', 'Brush', 'Harmony', 'Fullness', 'Addictive', 'Violine', 'Meta', 'Plethoric', 'Thought', 'Lamp', 'Vergnügen', 'Einfallsreichtum', 'Herausforderungen', 'Erstaunlich', 'Job', 'Strand', 'Schutz', 'Morgen', 'Wütend', 'Ehrlichkeit', 'Fantastisch', 'Fesselnd' , 'Überrascht', 'Verwandlung', 'Sommer', 'Mathe', 'Ruhe', 'Motorrad', 'Löwe', 'Komfort', 'Erinnerungen', 'Gesellschaft', 'Drop', 'Traum', ' Bewegen', 'Entwicklung', 'Weisheit', 'Verheiratet', 'Verheiratet', 'Liebe', 'Mode', 'Kunst', 'Heroisch', 'Medizin', 'Souvenir', 'Transzendental', 'Autonomie', 'Decke', 'Philosophie', 'Erstaunlich', 'Sorority', 'Papier', 'Toleranz', 'Wand', 'Schule', 'Aufstieg', 'Zucker', 'Gleichheit', 'Nachmittag', 'Soda', 'Zukunft', 'Paradise', 'Ingenieurwesen', 'Erhaben', 'Ruhe', 'Butter', 'Romantik', 'Mittag', 'Blitz', 'Großzügig', 'Motivation', ' Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividity', 'Exteriors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder' , 'Berauschend', 'Vielversprechend', 'Bildung', 'Sushi', 'Patient', 'Innovation', 'Landwirtschaft', 'Entschlossenheit', 'Donner', 'Energie', 'Libelle', 'Erstaunlich', 'Lösung', 'Blitz', 'Tiger', 'Katze', 'Widmung', 'Boot', 'Exaltation', 'Spülung', 'Leidenschaft', 'Ökologie', 'Ehrlichkeit', ' Emotion', 'Laufen', 'Technologie', 'Enthüller', 'Erkunden', 'Glare', 'Erwachen', 'Wein', 'Traurigkeit', 'Geschichte', 'Mond', 'Studie', 'Gesundheit' , 'Weisheit', 'Exorbitant', 'Schön', 'Milch', 'Ziele', 'Schal', 'Schwimmen', 'Kunst', 'Tal', 'Fluss', 'Natur', 'Hamburger', ' Geschichte', 'Wohlbefinden', 'Segen', 'Spaß', 'Erkundung', 'Natur', 'Unruhe', 'Melodie', 'Philanthropie', 'Schal', 'Belebend', 'Gesang', ' Toleranz', 'Drop', 'Blick', 'Entdecken', 'Salz', 'Spaß', 'Stadt', 'Verzeihung', 'Menschen', 'Serendipity', 'Solidarität', 'Sonntag', 'Erbe' , 'Fußball', 'Gemeinschaft', 'Herrlich', 'Regenbogen', 'Ermutigung', 'Disziplin', 'Kindergarten', 'Großartig', 'Sehnsucht', 'Hingabe', 'Musik', 'Hilfreich', ' Gesundheit', 'Tür', 'Geschäft', 'Fenster', 'Sensibilität', 'Zug', 'Stabilität', 'Giraffe', 'Rätsel', 'Mut', 'Saft', 'Magie', 'Wort' , 'Einzigartig', 'Klavier', 'Metropolis', 'Produktivität', 'Exhilaration', 'Malerisch', 'Metropolis', 'Erfrischend', 'Schock', 'Reise', 'Mut', 'Schockierend', ' Singen', 'Feier', 'Zusammenarbeit', 'Tanz', 'Spülen', 'Verzauberung', 'Religion', 'Idylle', 'Generation', 'Transzendent', 'Feder', 'Weizen', 'Zufriedenheit' , 'Geschäft', 'Reptil', 'Obst', 'Tisch', 'Organisation', 'Sterne', 'Drucker', 'Ziel', 'Motivation', 'Furchtlosigkeit', 'Gleichgewicht', 'Ruhe', ' Geburtstag', 'Geschieden', 'Glanz', 'Zusammenarbeit', 'Grün', 'Dessert', 'Melancholie', 'Fotografie', 'Lachen', 'Aroma', 'Frucht', 'Entspannung', 'Tau' , 'Kraft', 'Großzügigkeit', 'Lächeln', 'Herbst', 'Impuls', 'Charme', 'Bezaubernd', 'Salzig', 'Klarheit', 'Blau', 'Begeisterung', 'Schönheit', ' Wachstum', 'Zucker', 'Öl', 'Regenbogen', 'Reise', 'Hamster', 'Überraschung', 'Abenteurer', 'Kaffee', 'Erstaunlich', 'Neugier', 'Faden', 'Fisch' , 'Bemerkenswert', 'Verständnis', 'Butter', 'Früher Morgen', 'Student', 'Frühling', 'See', 'Therapie', 'Fähigkeit', 'Anmut', 'Unübertroffen', 'Zweck', 'Kuss', 'Feline', 'Single', 'Frieden', 'Techniker', 'Birne', 'Tanz', 'Kolibri', 'Flugzeug', 'See', 'Berauschend', 'Euphorisch', 'Aufregend', ' Festival', 'Sonne', 'Pants', 'Sprung', 'Boot', 'Keramik', 'Interdependenz', 'Spiel', 'Eloquenz', 'Stimuliert', 'Essenz', 'Salzig', 'Vertrauen', 'Hafer', 'Ethik', 'Initiative', 'Banane', 'Wolke', 'Üppig', 'Schreiben', 'Begegnung', 'Ernährung', 'Wunsch', 'Edel', 'Spiritualität', 'Kooperation', 'Harmonie', 'Pfeffer', 'Verbesserung', 'Erhaben', 'Schillernd', 'Tradition', 'Flexibilität', 'Universum', 'Giraffe', 'Straße', 'Vielfalt', 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-Shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Atemberaubend', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Unternehmertum', 'Thunder', 'Exzentrizität', 'Dorf', 'Gefühle', 'Elektrisiert', 'Faszinierend', 'Dankbarkeit', 'Zimt', 'Sieg', 'Loyalität', 'Fahrrad', 'Mais', 'Erfolg', 'Emotion', 'Bildung', 'Wasserfall', 'Freiheit', 'Zahnmedizin', 'Integrität', 'Sofa', 'Forschung', 'Käse', 'Erleuchtung', 'Großzügigkeit', 'Leidenschaft', 'Erde', 'Poesie', 'Opfer', 'Belastbarkeit', 'Wunderbar', 'Energetisch', 'Fenster']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Wort:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("errate einen Buchstaben: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Richtig!")
                    else:
                        intentos_restantes -= 1
                        print("Falsch. Du bist gegangen", intentos_restantes, "Versuche.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gewonnen! Sie haben das Wort erraten:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Du hast verloren! Das Wort war:", palabra)

            print("Spieler 1:")
            jugar_ahorcado()
            print("Spieler 2:")
            jugar_ahorcado()

    if Multiplayer == 1:
        b=int(input("Bitte wählen Sie einen Schwierigkeitsgrad aus:\n1.einfach\n2.mittel\n3.schwer" ))
        if b == 1:

            lista = ['Kameradschaft' , 'Keks', 'Umarmung', 'Loyalität', 'Bereichernd', 'Herbst', 'Ehrgeiz', 'Hell', 'Stille', 'Wissenschaft', 'Rot', 'Bleistift', 'Zimt', 'Luft', 'Liebe', 'Autobahn', 'Geduld', 'Einsamkeit', 'Strategie', 'Durchbruch', 'Mode', 'Wachstum', 'Hartnäckigkeit', 'Aufgeregt', 'Literatur', 'Party', 'Hoffnung', 'Inspirierend', 'Innovation', 'Kreativität', 'Elektrisierend', 'Staunen', 'Fleisch', 'Uhr', 'Stille', 'Überschrift', 'Schnee', 'Bogen', 'Fähigkeit', 'Schlaf', 'Orange', 'Wunder', 'Freundlichkeit', 'Veränderung', 'Computer', 'Musik', 'Traube', 'Epiphanie', 'Laufen', 'Dankbarkeit', 'Führung', 'Geheimnis', 'Brille', 'Kommunikation', 'Offenbarung', 'Gefeiert', 'Tränen', 'Wegbereiter', 'Flüstern', 'Schnee', 'Horizont', 'Anzeigetafel', 'Entdeckung', 'Stil', 'Bezaubernd', 'Sport', 'Literatur', 'Heilen', 'Gelassenheit', 'Hund', 'Erfrischend', 'Wunder', 'Büro', 'Entspannung', 'Stil' , 'Vitalität', 'Erhaltung', 'Würde', 'Erlösung', 'Schwimmen', 'Ruhe', 'Aufregend', 'Karriere', 'Haferflocken', 'Leistung', 'Applaudiert', 'Zeit', ' Joghurt', 'Ozean', 'Kino', 'Dorf', 'Zufriedenheit', 'Kaffee', 'Gitarre', 'Wasser', 'Kreide', 'Verantwortung', 'Prestige', 'Vergnügen', 'Weinen' , 'Optimismus', 'Team', 'Gleichheit', 'Vanilla', 'Tanz', 'Bus', 'Hobby', 'Fantasie', 'Unwiderstehlich', 'Glühen', 'Anpassungsfähigkeit', 'Wertschätzung', 'Stift', 'Freiwilligenarbeit', 'Hoffnung', 'Faszinierend', 'Aufklärend', 'Erhebend', 'Impressionismus', 'Dienstag', 'Architektur', 'Fortschritt', 'Sterne', 'Gemeinschaft', 'Bedeutsam' , 'Herrlich', 'Hügel', 'Umgebung', 'Erfrischung', 'Dämmerung', 'Unschuld', 'Mais', 'Mut', 'Überrascht', 'Übung', 'Warten', 'Foto', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Dorf', 'Glow' , 'Reflexion', 'Tanz', 'Feder', 'Widmung', 'Freude', 'Lachen', 'Verlieben', 'Kuchen', 'Sport', 'Neuerfindung', 'Kakao', 'Gastronomie', 'Symmetrie', 'Brüderlichkeit', 'Ingenieur', 'Erfüllend', 'Kakao', 'Aspiration', 'Authentizität', 'Demut', 'Intrige', 'Vergnügen', 'Bewusstsein', 'Berauschend', 'Anwalt', 'Geld', 'Joghurt', 'Fahrt', 'Computer', 'Saft', 'Feuer', 'Rückenwind', 'Faszination', 'Planet', 'Glück', 'Katze', 'Größe' , 'Elefant', 'Süß', 'Kaninchen', 'Einfach', 'Bitter', 'Wasser', 'Buch', 'Winter', 'Arbeit', 'Attraktiv', 'Optimismus', 'Skulptur', 'Gastronomie', 'Schön', 'Brillen', 'Fußball', 'Wunderkind', 'Erlebnis', 'Lassen Sie sich inspirieren', 'Meer', 'Mystisch', 'Natur', 'Schreiben', 'Fantasie', ' Gehen', 'Freude', 'Universum', 'Te', 'Ausdruck', 'Lachen', 'Spiritualität', 'Verjüngung', 'Fluss', 'Glück', 'Banane', 'Yoga', 'Emotional' , 'Gelegenheit', 'Zuhause', 'Stift', 'Geduld', 'Straße', 'Freude', 'Vertrauen', 'Anziehung', 'Träumen', 'Fantastisch', 'Geburtstag', 'Albtraum', ' Staunen', 'Wolken', 'Herrlich', 'Balance', 'Zusammenarbeit', 'Raum', 'Empowerment', 'Design', 'Lernen', 'Emotional', 'Belastbarkeit', 'Basketball', 'Glühen' , 'Empathie', 'Innenräume', 'Atemberaubend', 'Unvergesslich', 'Bewunderung', 'Schön', 'Berg', 'Verwirklichung', 'Säure', 'Schreiben', 'Umarmung', 'Keramik', ' Springen', 'Aktion', 'Seufz', 'Wütend', 'Tisch', 'Hut', 'Motorrad', 'Bier', 'Schuhe', 'Wahrheit', 'Aufregend', 'Stern', 'Urlaub' , 'Rhythmus', 'Himmel', 'Zeitvertreib', 'Bunt', 'Reisen', 'Tau', 'Wunderbar', 'Psychologie', 'Sonnenaufgang', 'Dankbarkeit', 'Herausforderung', 'Schwimmen', ' Analyse', 'Exquisit', 'Erbe', 'Fernsehen', 'Hosen', 'Geschenk', 'Belohnung', 'Wüste', 'Adel', 'Verbindung', 'Geschichte', 'Schule', 'Reife' , 'Regen', 'Lampe', 'Spontanität', 'Claro', 'Sternbild', 'Maus', 'Kultur', 'Frisch', 'Inspiration', 'Sonnengitarre', 'Buch', 'Vielfalt', 'Risiko', 'Orange', 'Universität', 'Entschlossenheit', 'Festival', 'Freundlichkeit', 'Brise', 'Hamster', 'Autobahn', 'Wunder', 'Biene', 'Hoffnung', 'Wissen', 'Hügel', 'Hamster', 'Sanft', 'Energie', 'Strahlend', 'Medizin', 'Schwimmen', 'Wasserfall', 'Zärtlich', 'Warm', 'Freundschaft', 'Telefon', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Aufrichtigkeit', 'Nachhaltigkeit', 'Freundlichkeit', 'Dschungel', 'Leuchtkraft', 'Fokus', 'Hund', 'Universität', 'Pflege', 'Entdeckung', 'Garten', 'Fähigkeit', 'Trainieren', 'Beleuchtung', 'Planung', 'Sand', 'Tennis', 'Überschwänglich', 'Überwindung', 'Sommer', 'Ingenieur', 'Wald', 'Sturm', 'Transzendenz', 'Geschieden', 'Harmonie', 'Empathie', 'Respekt', ' Uhr', 'Freund', 'Garn', 'Joghurt', 'Schule', 'Serendipity', 'Flugzeug', 'Spiel', 'Lachen', 'Fülle', 'Skulptur', 'Krankenhaus', 'Lächeln', 'Fesselnd', 'Intuition', 'Erfahrung', 'Pracht', 'Ozean', 'Wohlstand', 'Bewusstsein', ' Tequila', 'Jubiläum', 'Verführung', 'Führung', 'hervorragend', 'Schnitte', 'Erneuerung', 'Valle', 'Morgen', 'Nacht', 'Winter', 'Charisma', 'Evolution' , 'Flexibilität', 'Energetisch', 'Veränderung', 'Basketball', 'Professionalität', 'Inspiration', 'Aufregend', 'Wunderbar', 'Erfolg', 'Solidarität', 'Wiedergeburt', 'Gemüse', ' Kleid', 'Muscheln', 'Meer', 'Medizin', 'Glaube', 'T-Shirt', 'Kreativität', 'Bitter', 'Feier', 'Vitalität', 'Blumen', 'Nacht', ' Lachen', 'Bonus', 'Abenteuer', 'Pfeffer', 'Frühling', 'Aufregung', 'Dach', 'Zucker', 'Kleid', 'Ruhe', 'Freiheit', 'Ruhe', 'Bewusstsein' , 'Jubiläum', 'Momente', 'Glücklich', 'Galaxie', 'Authentizität', 'Meditation', 'Kompetenz', 'Baum', 'Ernährung', 'Herrlich', 'Wissenschaft', 'Erhebung', ' Luft', 'Gerechtigkeit', 'Effizienz', 'Charme', 'Feuer', 'Tradition', 'Oase', 'Überraschung', 'Lehre', 'Freude', 'Träumen', 'Überfließend', 'Abenteuer' , 'Fernsehen', 'Schuhe', 'Schokolade', 'Hund', 'Inspiration', 'Hochzeit', 'Anger', 'Leidenschaftlich', 'Medizin', 'Pinsel', 'Klarheit', 'Surround', ' Pizza', 'Mond', 'Gerechtigkeit', 'Ermächtigung', 'Stuhl', 'Überlauf', 'Wind', 'Reichtum', 'Erinnerungen', 'Begeisterung', 'Technologie', 'Shop', 'Galaxie' , 'Magie', 'Charmant', 'Pasta', 'Überschwänglichkeit', 'Gerechtigkeit', 'Kino', 'Ausdauer', 'Organisation', 'Ausdauer', 'Karriere', 'Erstaunlich', 'Träume', ' Originalität', 'Außergewöhnlich', 'Bedeutsam', 'Büro', 'Einfach', 'Milch', 'Skateboard', 'Mobilfunk', 'Intelligenz', 'Entspannend', 'Sound', 'Ausbruch', 'Sonnenuntergang' , 'Inspirierend', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Watchful', 'Ice Cream', 'Evening', 'Bleistift', 'Zugehörigkeit', 'Unternehmertum', 'Integrität', 'Unschuld', 'Harmonie', 'Selbstwertgefühl', 'Freude', 'Tee', 'Notizbuch', 'Malerei', 'Reis', 'Bereicherung', 'Motivator', 'Inklusion', 'Apfel', 'Achtsamkeit', 'Respekt', 'Erforschung', 'Nachbar', 'Reichtum', 'Transformation', 'Farbe', 'Freude', 'Chaos', 'Erde', 'Schmetterling', 'Bewunderung', 'Exotisch', 'Nachhaltigkeit', 'Leidenschaftlich', 'Vanille', 'Faszinierend', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Gemüse', 'Belebend', 'Whisky', 'Theater', 'Landschaft', 'Gefühl', 'Festung', 'Straße', 'Tür', 'Fleisch', 'Geheimnis', 'Theater', 'Pasta', 'Samstag', 'Engagement', 'Triumph', 'Faszinierend', 'Mut', 'Weizen', 'Freundlichkeit', 'Frieden', 'Nachhaltigkeit', 'Beharrlichkeit', 'Stadt', 'Architektur', 'Party', 'Träumer', 'Pflegen', 'Stärke', 'Seufz', 'Zärtlichkeit', 'Demut', 'Aufstieg', 'Apfel', 'Auto', 'Glänzen', 'Single', 'Beziehungen', 'Fröhlich', 'Belebend', 'Freundlich', 'Aufregend', 'Avenue', 'Beauty', 'Gelb', 'Defiance', 'Kultur', 'Effizienz', 'Batterie', 'Majestätisch', 'Scanner', 'Salz', 'Begleiter', 'Familie', 'Lebendig', 'Umgebung', 'Lernen', 'Anwalt', 'Unterhaltung', 'Werte', 'Shop', 'Akzeptanz', 'Familie', 'Wissen', 'Stärke', 'Geist', 'Mutig', 'Revolution', 'Fürsorge', 'Entdecker', 'Strand', 'Sofa', 'Freundschaft', 'Bus', 'Fisch', 'Tanz', 'Verzauberung', 'Berg', 'Wald', 'Überleben', 'Unvergleichlich', 'Krankenhaus', 'Garten', 'Legende', 'Allee', 'Sublimation', 'Salat', 'Schicksal', 'Art', 'Süß', 'Ewigkeit', 'Hut', 'Ewig', 'Liebend', 'Farbe', 'Herz', 'Konstanz', 'Stuhl', 'Meister', 'Automobil', 'Metropolis', 'Vibrant', 'Tea', 'Dezent', 'Brush', 'Harmony', 'Fullness', 'Addictive', 'Violine', 'Meta', 'Plethoric', 'Thought', 'Lamp', 'Vergnügen', 'Einfallsreichtum', 'Herausforderungen', 'Erstaunlich', 'Job', 'Strand', 'Schutz', 'Morgen', 'Wütend', 'Ehrlichkeit', 'Fantastisch', 'Fesselnd' , 'Überrascht', 'Verwandlung', 'Sommer', 'Mathe', 'Ruhe', 'Motorrad', 'Löwe', 'Komfort', 'Erinnerungen', 'Gesellschaft', 'Drop', 'Traum', ' Bewegen', 'Entwicklung', 'Weisheit', 'Verheiratet', 'Verheiratet', 'Liebe', 'Mode', 'Kunst', 'Heroisch', 'Medizin', 'Souvenir', 'Transzendental', 'Autonomie', 'Decke', 'Philosophie', 'Erstaunlich', 'Sorority', 'Papier', 'Toleranz', 'Wand', 'Schule', 'Aufstieg', 'Zucker', 'Gleichheit', 'Nachmittag', 'Soda', 'Zukunft', 'Paradise', 'Ingenieurwesen', 'Erhaben', 'Ruhe', 'Butter', 'Romantik', 'Mittag', 'Blitz', 'Großzügig', 'Motivation', ' Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividity', 'Exteriors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder' , 'Berauschend', 'Vielversprechend', 'Bildung', 'Sushi', 'Patient', 'Innovation', 'Landwirtschaft', 'Entschlossenheit', 'Donner', 'Energie', 'Libelle', 'Erstaunlich', 'Lösung', 'Blitz', 'Tiger', 'Katze', 'Widmung', 'Boot', 'Exaltation', 'Spülung', 'Leidenschaft', 'Ökologie', 'Ehrlichkeit', ' Emotion', 'Laufen', 'Technologie', 'Enthüller', 'Erkunden', 'Glare', 'Erwachen', 'Wein', 'Traurigkeit', 'Geschichte', 'Mond', 'Studie', 'Gesundheit' , 'Weisheit', 'Exorbitant', 'Schön', 'Milch', 'Ziele', 'Schal', 'Schwimmen', 'Kunst', 'Tal', 'Fluss', 'Natur', 'Hamburger', ' Geschichte', 'Wohlbefinden', 'Segen', 'Spaß', 'Erkundung', 'Natur', 'Unruhe', 'Melodie', 'Philanthropie', 'Schal', 'Belebend', 'Gesang', ' Toleranz', 'Drop', 'Blick', 'Entdecken', 'Salz', 'Spaß', 'Stadt', 'Verzeihung', 'Menschen', 'Serendipity', 'Solidarität', 'Sonntag', 'Erbe' , 'Fußball', 'Gemeinschaft', 'Herrlich', 'Regenbogen', 'Ermutigung', 'Disziplin', 'Kindergarten', 'Großartig', 'Sehnsucht', 'Hingabe', 'Musik', 'Hilfreich', ' Gesundheit', 'Tür', 'Geschäft', 'Fenster', 'Sensibilität', 'Zug', 'Stabilität', 'Giraffe', 'Rätsel', 'Mut', 'Saft', 'Magie', 'Wort' , 'Einzigartig', 'Klavier', 'Metropolis', 'Produktivität', 'Exhilaration', 'Malerisch', 'Metropolis', 'Erfrischend', 'Schock', 'Reise', 'Mut', 'Schockierend', ' Singen', 'Feier', 'Zusammenarbeit', 'Tanz', 'Spülen', 'Verzauberung', 'Religion', 'Idylle', 'Generation', 'Transzendent', 'Feder', 'Weizen', 'Zufriedenheit' , 'Geschäft', 'Reptil', 'Obst', 'Tisch', 'Organisation', 'Sterne', 'Drucker', 'Ziel', 'Motivation', 'Furchtlosigkeit', 'Gleichgewicht', 'Ruhe', ' Geburtstag', 'Geschieden', 'Glanz', 'Zusammenarbeit', 'Grün', 'Dessert', 'Melancholie', 'Fotografie', 'Lachen', 'Aroma', 'Frucht', 'Entspannung', 'Tau' , 'Kraft', 'Großzügigkeit', 'Lächeln', 'Herbst', 'Impuls', 'Charme', 'Bezaubernd', 'Salzig', 'Klarheit', 'Blau', 'Begeisterung', 'Schönheit', ' Wachstum', 'Zucker', 'Öl', 'Regenbogen', 'Reise', 'Hamster', 'Überraschung', 'Abenteurer', 'Kaffee', 'Erstaunlich', 'Neugier', 'Faden', 'Fisch' , 'Bemerkenswert', 'Verständnis', 'Butter', 'Früher Morgen', 'Student', 'Frühling', 'See', 'Therapie', 'Fähigkeit', 'Anmut', 'Unübertroffen', 'Zweck', 'Kuss', 'Feline', 'Single', 'Frieden', 'Techniker', 'Birne', 'Tanz', 'Kolibri', 'Flugzeug', 'See', 'Berauschend', 'Euphorisch', 'Aufregend', ' Festival', 'Sonne', 'Pants', 'Sprung', 'Boot', 'Keramik', 'Interdependenz', 'Spiel', 'Eloquenz', 'Stimuliert', 'Essenz', 'Salzig', 'Vertrauen', 'Hafer', 'Ethik', 'Initiative', 'Banane', 'Wolke', 'Üppig', 'Schreiben', 'Begegnung', 'Ernährung', 'Wunsch', 'Edel', 'Spiritualität', 'Kooperation', 'Harmonie', 'Pfeffer', 'Verbesserung', 'Erhaben', 'Schillernd', 'Tradition', 'Flexibilität', 'Universum', 'Giraffe', 'Straße', 'Vielfalt', 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-Shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Atemberaubend', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Unternehmertum', 'Thunder', 'Exzentrizität', 'Dorf', 'Gefühle', 'Elektrisiert', 'Faszinierend', 'Dankbarkeit', 'Zimt', 'Sieg', 'Loyalität', 'Fahrrad', 'Mais', 'Erfolg', 'Emotion', 'Bildung', 'Wasserfall', 'Freiheit', 'Zahnmedizin', 'Integrität', 'Sofa', 'Forschung', 'Käse', 'Erleuchtung', 'Großzügigkeit', 'Leidenschaft', 'Erde', 'Poesie', 'Opfer', 'Belastbarkeit', 'Wunderbar', 'Energetisch', 'Fenster']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Wort", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("errate einen Buchstaben: ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Richtig!")

                    else:
                        intentos_restantes -= 1
                        print("Falsch. Du bist gegangen", intentos_restantes, "Versuche.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gewonnen! Sie haben das Wort erraten:", palabra)
                        break

                if intentos_restantes == 0:
                        print("Du hast verloren! Das Wort war:", palabra)


            print("Spieler 1:")
            jugar_ahorcado()

            
        elif b == 2:


            lista = ['Kameradschaft' , 'Keks', 'Umarmung', 'Loyalität', 'Bereichernd', 'Herbst', 'Ehrgeiz', 'Hell', 'Stille', 'Wissenschaft', 'Rot', 'Bleistift', 'Zimt', 'Luft', 'Liebe', 'Autobahn', 'Geduld', 'Einsamkeit', 'Strategie', 'Durchbruch', 'Mode', 'Wachstum', 'Hartnäckigkeit', 'Aufgeregt', 'Literatur', 'Party', 'Hoffnung', 'Inspirierend', 'Innovation', 'Kreativität', 'Elektrisierend', 'Staunen', 'Fleisch', 'Uhr', 'Stille', 'Überschrift', 'Schnee', 'Bogen', 'Fähigkeit', 'Schlaf', 'Orange', 'Wunder', 'Freundlichkeit', 'Veränderung', 'Computer', 'Musik', 'Traube', 'Epiphanie', 'Laufen', 'Dankbarkeit', 'Führung', 'Geheimnis', 'Brille', 'Kommunikation', 'Offenbarung', 'Gefeiert', 'Tränen', 'Wegbereiter', 'Flüstern', 'Schnee', 'Horizont', 'Anzeigetafel', 'Entdeckung', 'Stil', 'Bezaubernd', 'Sport', 'Literatur', 'Heilen', 'Gelassenheit', 'Hund', 'Erfrischend', 'Wunder', 'Büro', 'Entspannung', 'Stil' , 'Vitalität', 'Erhaltung', 'Würde', 'Erlösung', 'Schwimmen', 'Ruhe', 'Aufregend', 'Karriere', 'Haferflocken', 'Leistung', 'Applaudiert', 'Zeit', ' Joghurt', 'Ozean', 'Kino', 'Dorf', 'Zufriedenheit', 'Kaffee', 'Gitarre', 'Wasser', 'Kreide', 'Verantwortung', 'Prestige', 'Vergnügen', 'Weinen' , 'Optimismus', 'Team', 'Gleichheit', 'Vanilla', 'Tanz', 'Bus', 'Hobby', 'Fantasie', 'Unwiderstehlich', 'Glühen', 'Anpassungsfähigkeit', 'Wertschätzung', 'Stift', 'Freiwilligenarbeit', 'Hoffnung', 'Faszinierend', 'Aufklärend', 'Erhebend', 'Impressionismus', 'Dienstag', 'Architektur', 'Fortschritt', 'Sterne', 'Gemeinschaft', 'Bedeutsam' , 'Herrlich', 'Hügel', 'Umgebung', 'Erfrischung', 'Dämmerung', 'Unschuld', 'Mais', 'Mut', 'Überrascht', 'Übung', 'Warten', 'Foto', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Dorf', 'Glow' , 'Reflexion', 'Tanz', 'Feder', 'Widmung', 'Freude', 'Lachen', 'Verlieben', 'Kuchen', 'Sport', 'Neuerfindung', 'Kakao', 'Gastronomie', 'Symmetrie', 'Brüderlichkeit', 'Ingenieur', 'Erfüllend', 'Kakao', 'Aspiration', 'Authentizität', 'Demut', 'Intrige', 'Vergnügen', 'Bewusstsein', 'Berauschend', 'Anwalt', 'Geld', 'Joghurt', 'Fahrt', 'Computer', 'Saft', 'Feuer', 'Rückenwind', 'Faszination', 'Planet', 'Glück', 'Katze', 'Größe' , 'Elefant', 'Süß', 'Kaninchen', 'Einfach', 'Bitter', 'Wasser', 'Buch', 'Winter', 'Arbeit', 'Attraktiv', 'Optimismus', 'Skulptur', 'Gastronomie', 'Schön', 'Brillen', 'Fußball', 'Wunderkind', 'Erlebnis', 'Lassen Sie sich inspirieren', 'Meer', 'Mystisch', 'Natur', 'Schreiben', 'Fantasie', ' Gehen', 'Freude', 'Universum', 'Te', 'Ausdruck', 'Lachen', 'Spiritualität', 'Verjüngung', 'Fluss', 'Glück', 'Banane', 'Yoga', 'Emotional' , 'Gelegenheit', 'Zuhause', 'Stift', 'Geduld', 'Straße', 'Freude', 'Vertrauen', 'Anziehung', 'Träumen', 'Fantastisch', 'Geburtstag', 'Albtraum', ' Staunen', 'Wolken', 'Herrlich', 'Balance', 'Zusammenarbeit', 'Raum', 'Empowerment', 'Design', 'Lernen', 'Emotional', 'Belastbarkeit', 'Basketball', 'Glühen' , 'Empathie', 'Innenräume', 'Atemberaubend', 'Unvergesslich', 'Bewunderung', 'Schön', 'Berg', 'Verwirklichung', 'Säure', 'Schreiben', 'Umarmung', 'Keramik', ' Springen', 'Aktion', 'Seufz', 'Wütend', 'Tisch', 'Hut', 'Motorrad', 'Bier', 'Schuhe', 'Wahrheit', 'Aufregend', 'Stern', 'Urlaub' , 'Rhythmus', 'Himmel', 'Zeitvertreib', 'Bunt', 'Reisen', 'Tau', 'Wunderbar', 'Psychologie', 'Sonnenaufgang', 'Dankbarkeit', 'Herausforderung', 'Schwimmen', ' Analyse', 'Exquisit', 'Erbe', 'Fernsehen', 'Hosen', 'Geschenk', 'Belohnung', 'Wüste', 'Adel', 'Verbindung', 'Geschichte', 'Schule', 'Reife' , 'Regen', 'Lampe', 'Spontanität', 'Claro', 'Sternbild', 'Maus', 'Kultur', 'Frisch', 'Inspiration', 'Sonnengitarre', 'Buch', 'Vielfalt', 'Risiko', 'Orange', 'Universität', 'Entschlossenheit', 'Festival', 'Freundlichkeit', 'Brise', 'Hamster', 'Autobahn', 'Wunder', 'Biene', 'Hoffnung', 'Wissen', 'Hügel', 'Hamster', 'Sanft', 'Energie', 'Strahlend', 'Medizin', 'Schwimmen', 'Wasserfall', 'Zärtlich', 'Warm', 'Freundschaft', 'Telefon', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Aufrichtigkeit', 'Nachhaltigkeit', 'Freundlichkeit', 'Dschungel', 'Leuchtkraft', 'Fokus', 'Hund', 'Universität', 'Pflege', 'Entdeckung', 'Garten', 'Fähigkeit', 'Trainieren', 'Beleuchtung', 'Planung', 'Sand', 'Tennis', 'Überschwänglich', 'Überwindung', 'Sommer', 'Ingenieur', 'Wald', 'Sturm', 'Transzendenz', 'Geschieden', 'Harmonie', 'Empathie', 'Respekt', ' Uhr', 'Freund', 'Garn', 'Joghurt', 'Schule', 'Serendipity', 'Flugzeug', 'Spiel', 'Lachen', 'Fülle', 'Skulptur', 'Krankenhaus', 'Lächeln', 'Fesselnd', 'Intuition', 'Erfahrung', 'Pracht', 'Ozean', 'Wohlstand', 'Bewusstsein', ' Tequila', 'Jubiläum', 'Verführung', 'Führung', 'hervorragend', 'Schnitte', 'Erneuerung', 'Valle', 'Morgen', 'Nacht', 'Winter', 'Charisma', 'Evolution' , 'Flexibilität', 'Energetisch', 'Veränderung', 'Basketball', 'Professionalität', 'Inspiration', 'Aufregend', 'Wunderbar', 'Erfolg', 'Solidarität', 'Wiedergeburt', 'Gemüse', ' Kleid', 'Muscheln', 'Meer', 'Medizin', 'Glaube', 'T-Shirt', 'Kreativität', 'Bitter', 'Feier', 'Vitalität', 'Blumen', 'Nacht', ' Lachen', 'Bonus', 'Abenteuer', 'Pfeffer', 'Frühling', 'Aufregung', 'Dach', 'Zucker', 'Kleid', 'Ruhe', 'Freiheit', 'Ruhe', 'Bewusstsein' , 'Jubiläum', 'Momente', 'Glücklich', 'Galaxie', 'Authentizität', 'Meditation', 'Kompetenz', 'Baum', 'Ernährung', 'Herrlich', 'Wissenschaft', 'Erhebung', ' Luft', 'Gerechtigkeit', 'Effizienz', 'Charme', 'Feuer', 'Tradition', 'Oase', 'Überraschung', 'Lehre', 'Freude', 'Träumen', 'Überfließend', 'Abenteuer' , 'Fernsehen', 'Schuhe', 'Schokolade', 'Hund', 'Inspiration', 'Hochzeit', 'Anger', 'Leidenschaftlich', 'Medizin', 'Pinsel', 'Klarheit', 'Surround', ' Pizza', 'Mond', 'Gerechtigkeit', 'Ermächtigung', 'Stuhl', 'Überlauf', 'Wind', 'Reichtum', 'Erinnerungen', 'Begeisterung', 'Technologie', 'Shop', 'Galaxie' , 'Magie', 'Charmant', 'Pasta', 'Überschwänglichkeit', 'Gerechtigkeit', 'Kino', 'Ausdauer', 'Organisation', 'Ausdauer', 'Karriere', 'Erstaunlich', 'Träume', ' Originalität', 'Außergewöhnlich', 'Bedeutsam', 'Büro', 'Einfach', 'Milch', 'Skateboard', 'Mobilfunk', 'Intelligenz', 'Entspannend', 'Sound', 'Ausbruch', 'Sonnenuntergang' , 'Inspirierend', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Watchful', 'Ice Cream', 'Evening', 'Bleistift', 'Zugehörigkeit', 'Unternehmertum', 'Integrität', 'Unschuld', 'Harmonie', 'Selbstwertgefühl', 'Freude', 'Tee', 'Notizbuch', 'Malerei', 'Reis', 'Bereicherung', 'Motivator', 'Inklusion', 'Apfel', 'Achtsamkeit', 'Respekt', 'Erforschung', 'Nachbar', 'Reichtum', 'Transformation', 'Farbe', 'Freude', 'Chaos', 'Erde', 'Schmetterling', 'Bewunderung', 'Exotisch', 'Nachhaltigkeit', 'Leidenschaftlich', 'Vanille', 'Faszinierend', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Gemüse', 'Belebend', 'Whisky', 'Theater', 'Landschaft', 'Gefühl', 'Festung', 'Straße', 'Tür', 'Fleisch', 'Geheimnis', 'Theater', 'Pasta', 'Samstag', 'Engagement', 'Triumph', 'Faszinierend', 'Mut', 'Weizen', 'Freundlichkeit', 'Frieden', 'Nachhaltigkeit', 'Beharrlichkeit', 'Stadt', 'Architektur', 'Party', 'Träumer', 'Pflegen', 'Stärke', 'Seufz', 'Zärtlichkeit', 'Demut', 'Aufstieg', 'Apfel', 'Auto', 'Glänzen', 'Single', 'Beziehungen', 'Fröhlich', 'Belebend', 'Freundlich', 'Aufregend', 'Avenue', 'Beauty', 'Gelb', 'Defiance', 'Kultur', 'Effizienz', 'Batterie', 'Majestätisch', 'Scanner', 'Salz', 'Begleiter', 'Familie', 'Lebendig', 'Umgebung', 'Lernen', 'Anwalt', 'Unterhaltung', 'Werte', 'Shop', 'Akzeptanz', 'Familie', 'Wissen', 'Stärke', 'Geist', 'Mutig', 'Revolution', 'Fürsorge', 'Entdecker', 'Strand', 'Sofa', 'Freundschaft', 'Bus', 'Fisch', 'Tanz', 'Verzauberung', 'Berg', 'Wald', 'Überleben', 'Unvergleichlich', 'Krankenhaus', 'Garten', 'Legende', 'Allee', 'Sublimation', 'Salat', 'Schicksal', 'Art', 'Süß', 'Ewigkeit', 'Hut', 'Ewig', 'Liebend', 'Farbe', 'Herz', 'Konstanz', 'Stuhl', 'Meister', 'Automobil', 'Metropolis', 'Vibrant', 'Tea', 'Dezent', 'Brush', 'Harmony', 'Fullness', 'Addictive', 'Violine', 'Meta', 'Plethoric', 'Thought', 'Lamp', 'Vergnügen', 'Einfallsreichtum', 'Herausforderungen', 'Erstaunlich', 'Job', 'Strand', 'Schutz', 'Morgen', 'Wütend', 'Ehrlichkeit', 'Fantastisch', 'Fesselnd' , 'Überrascht', 'Verwandlung', 'Sommer', 'Mathe', 'Ruhe', 'Motorrad', 'Löwe', 'Komfort', 'Erinnerungen', 'Gesellschaft', 'Drop', 'Traum', ' Bewegen', 'Entwicklung', 'Weisheit', 'Verheiratet', 'Verheiratet', 'Liebe', 'Mode', 'Kunst', 'Heroisch', 'Medizin', 'Souvenir', 'Transzendental', 'Autonomie', 'Decke', 'Philosophie', 'Erstaunlich', 'Sorority', 'Papier', 'Toleranz', 'Wand', 'Schule', 'Aufstieg', 'Zucker', 'Gleichheit', 'Nachmittag', 'Soda', 'Zukunft', 'Paradise', 'Ingenieurwesen', 'Erhaben', 'Ruhe', 'Butter', 'Romantik', 'Mittag', 'Blitz', 'Großzügig', 'Motivation', ' Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividity', 'Exteriors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder' , 'Berauschend', 'Vielversprechend', 'Bildung', 'Sushi', 'Patient', 'Innovation', 'Landwirtschaft', 'Entschlossenheit', 'Donner', 'Energie', 'Libelle', 'Erstaunlich', 'Lösung', 'Blitz', 'Tiger', 'Katze', 'Widmung', 'Boot', 'Exaltation', 'Spülung', 'Leidenschaft', 'Ökologie', 'Ehrlichkeit', ' Emotion', 'Laufen', 'Technologie', 'Enthüller', 'Erkunden', 'Glare', 'Erwachen', 'Wein', 'Traurigkeit', 'Geschichte', 'Mond', 'Studie', 'Gesundheit' , 'Weisheit', 'Exorbitant', 'Schön', 'Milch', 'Ziele', 'Schal', 'Schwimmen', 'Kunst', 'Tal', 'Fluss', 'Natur', 'Hamburger', ' Geschichte', 'Wohlbefinden', 'Segen', 'Spaß', 'Erkundung', 'Natur', 'Unruhe', 'Melodie', 'Philanthropie', 'Schal', 'Belebend', 'Gesang', ' Toleranz', 'Drop', 'Blick', 'Entdecken', 'Salz', 'Spaß', 'Stadt', 'Verzeihung', 'Menschen', 'Serendipity', 'Solidarität', 'Sonntag', 'Erbe' , 'Fußball', 'Gemeinschaft', 'Herrlich', 'Regenbogen', 'Ermutigung', 'Disziplin', 'Kindergarten', 'Großartig', 'Sehnsucht', 'Hingabe', 'Musik', 'Hilfreich', ' Gesundheit', 'Tür', 'Geschäft', 'Fenster', 'Sensibilität', 'Zug', 'Stabilität', 'Giraffe', 'Rätsel', 'Mut', 'Saft', 'Magie', 'Wort' , 'Einzigartig', 'Klavier', 'Metropolis', 'Produktivität', 'Exhilaration', 'Malerisch', 'Metropolis', 'Erfrischend', 'Schock', 'Reise', 'Mut', 'Schockierend', ' Singen', 'Feier', 'Zusammenarbeit', 'Tanz', 'Spülen', 'Verzauberung', 'Religion', 'Idylle', 'Generation', 'Transzendent', 'Feder', 'Weizen', 'Zufriedenheit' , 'Geschäft', 'Reptil', 'Obst', 'Tisch', 'Organisation', 'Sterne', 'Drucker', 'Ziel', 'Motivation', 'Furchtlosigkeit', 'Gleichgewicht', 'Ruhe', ' Geburtstag', 'Geschieden', 'Glanz', 'Zusammenarbeit', 'Grün', 'Dessert', 'Melancholie', 'Fotografie', 'Lachen', 'Aroma', 'Frucht', 'Entspannung', 'Tau' , 'Kraft', 'Großzügigkeit', 'Lächeln', 'Herbst', 'Impuls', 'Charme', 'Bezaubernd', 'Salzig', 'Klarheit', 'Blau', 'Begeisterung', 'Schönheit', ' Wachstum', 'Zucker', 'Öl', 'Regenbogen', 'Reise', 'Hamster', 'Überraschung', 'Abenteurer', 'Kaffee', 'Erstaunlich', 'Neugier', 'Faden', 'Fisch' , 'Bemerkenswert', 'Verständnis', 'Butter', 'Früher Morgen', 'Student', 'Frühling', 'See', 'Therapie', 'Fähigkeit', 'Anmut', 'Unübertroffen', 'Zweck', 'Kuss', 'Feline', 'Single', 'Frieden', 'Techniker', 'Birne', 'Tanz', 'Kolibri', 'Flugzeug', 'See', 'Berauschend', 'Euphorisch', 'Aufregend', ' Festival', 'Sonne', 'Pants', 'Sprung', 'Boot', 'Keramik', 'Interdependenz', 'Spiel', 'Eloquenz', 'Stimuliert', 'Essenz', 'Salzig', 'Vertrauen', 'Hafer', 'Ethik', 'Initiative', 'Banane', 'Wolke', 'Üppig', 'Schreiben', 'Begegnung', 'Ernährung', 'Wunsch', 'Edel', 'Spiritualität', 'Kooperation', 'Harmonie', 'Pfeffer', 'Verbesserung', 'Erhaben', 'Schillernd', 'Tradition', 'Flexibilität', 'Universum', 'Giraffe', 'Straße', 'Vielfalt', 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-Shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Atemberaubend', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Unternehmertum', 'Thunder', 'Exzentrizität', 'Dorf', 'Gefühle', 'Elektrisiert', 'Faszinierend', 'Dankbarkeit', 'Zimt', 'Sieg', 'Loyalität', 'Fahrrad', 'Mais', 'Erfolg', 'Emotion', 'Bildung', 'Wasserfall', 'Freiheit', 'Zahnmedizin', 'Integrität', 'Sofa', 'Forschung', 'Käse', 'Erleuchtung', 'Großzügigkeit', 'Leidenschaft', 'Erde', 'Poesie', 'Opfer', 'Belastbarkeit', 'Wunderbar', 'Energetisch', 'Fenster']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Wort:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("errate einen Buchstaben: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Richtig!")

                    else:
                        intentos_restantes -= 1
                        print("Falsch. Du bist gegangen", intentos_restantes, "Versuche.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gewonnen! Sie haben das Wort erraten:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Du hast verloren! Das Wort war:", palabra)



            print("Spieler 1:")
            jugar_ahorcado()


        elif b == 3:

            import random
            lista = ['Kameradschaft' , 'Keks', 'Umarmung', 'Loyalität', 'Bereichernd', 'Herbst', 'Ehrgeiz', 'Hell', 'Stille', 'Wissenschaft', 'Rot', 'Bleistift', 'Zimt', 'Luft', 'Liebe', 'Autobahn', 'Geduld', 'Einsamkeit', 'Strategie', 'Durchbruch', 'Mode', 'Wachstum', 'Hartnäckigkeit', 'Aufgeregt', 'Literatur', 'Party', 'Hoffnung', 'Inspirierend', 'Innovation', 'Kreativität', 'Elektrisierend', 'Staunen', 'Fleisch', 'Uhr', 'Stille', 'Überschrift', 'Schnee', 'Bogen', 'Fähigkeit', 'Schlaf', 'Orange', 'Wunder', 'Freundlichkeit', 'Veränderung', 'Computer', 'Musik', 'Traube', 'Epiphanie', 'Laufen', 'Dankbarkeit', 'Führung', 'Geheimnis', 'Brille', 'Kommunikation', 'Offenbarung', 'Gefeiert', 'Tränen', 'Wegbereiter', 'Flüstern', 'Schnee', 'Horizont', 'Anzeigetafel', 'Entdeckung', 'Stil', 'Bezaubernd', 'Sport', 'Literatur', 'Heilen', 'Gelassenheit', 'Hund', 'Erfrischend', 'Wunder', 'Büro', 'Entspannung', 'Stil' , 'Vitalität', 'Erhaltung', 'Würde', 'Erlösung', 'Schwimmen', 'Ruhe', 'Aufregend', 'Karriere', 'Haferflocken', 'Leistung', 'Applaudiert', 'Zeit', ' Joghurt', 'Ozean', 'Kino', 'Dorf', 'Zufriedenheit', 'Kaffee', 'Gitarre', 'Wasser', 'Kreide', 'Verantwortung', 'Prestige', 'Vergnügen', 'Weinen' , 'Optimismus', 'Team', 'Gleichheit', 'Vanilla', 'Tanz', 'Bus', 'Hobby', 'Fantasie', 'Unwiderstehlich', 'Glühen', 'Anpassungsfähigkeit', 'Wertschätzung', 'Stift', 'Freiwilligenarbeit', 'Hoffnung', 'Faszinierend', 'Aufklärend', 'Erhebend', 'Impressionismus', 'Dienstag', 'Architektur', 'Fortschritt', 'Sterne', 'Gemeinschaft', 'Bedeutsam' , 'Herrlich', 'Hügel', 'Umgebung', 'Erfrischung', 'Dämmerung', 'Unschuld', 'Mais', 'Mut', 'Überrascht', 'Übung', 'Warten', 'Foto', 'Reality', 'Nice', 'Enchantment', 'Dusk', 'Desert', 'Impressed', 'Sad', 'Oil', 'Euphoria', 'Painting', 'Wellness', 'Dorf', 'Glow' , 'Reflexion', 'Tanz', 'Feder', 'Widmung', 'Freude', 'Lachen', 'Verlieben', 'Kuchen', 'Sport', 'Neuerfindung', 'Kakao', 'Gastronomie', 'Symmetrie', 'Brüderlichkeit', 'Ingenieur', 'Erfüllend', 'Kakao', 'Aspiration', 'Authentizität', 'Demut', 'Intrige', 'Vergnügen', 'Bewusstsein', 'Berauschend', 'Anwalt', 'Geld', 'Joghurt', 'Fahrt', 'Computer', 'Saft', 'Feuer', 'Rückenwind', 'Faszination', 'Planet', 'Glück', 'Katze', 'Größe' , 'Elefant', 'Süß', 'Kaninchen', 'Einfach', 'Bitter', 'Wasser', 'Buch', 'Winter', 'Arbeit', 'Attraktiv', 'Optimismus', 'Skulptur', 'Gastronomie', 'Schön', 'Brillen', 'Fußball', 'Wunderkind', 'Erlebnis', 'Lassen Sie sich inspirieren', 'Meer', 'Mystisch', 'Natur', 'Schreiben', 'Fantasie', ' Gehen', 'Freude', 'Universum', 'Te', 'Ausdruck', 'Lachen', 'Spiritualität', 'Verjüngung', 'Fluss', 'Glück', 'Banane', 'Yoga', 'Emotional' , 'Gelegenheit', 'Zuhause', 'Stift', 'Geduld', 'Straße', 'Freude', 'Vertrauen', 'Anziehung', 'Träumen', 'Fantastisch', 'Geburtstag', 'Albtraum', ' Staunen', 'Wolken', 'Herrlich', 'Balance', 'Zusammenarbeit', 'Raum', 'Empowerment', 'Design', 'Lernen', 'Emotional', 'Belastbarkeit', 'Basketball', 'Glühen' , 'Empathie', 'Innenräume', 'Atemberaubend', 'Unvergesslich', 'Bewunderung', 'Schön', 'Berg', 'Verwirklichung', 'Säure', 'Schreiben', 'Umarmung', 'Keramik', ' Springen', 'Aktion', 'Seufz', 'Wütend', 'Tisch', 'Hut', 'Motorrad', 'Bier', 'Schuhe', 'Wahrheit', 'Aufregend', 'Stern', 'Urlaub' , 'Rhythmus', 'Himmel', 'Zeitvertreib', 'Bunt', 'Reisen', 'Tau', 'Wunderbar', 'Psychologie', 'Sonnenaufgang', 'Dankbarkeit', 'Herausforderung', 'Schwimmen', ' Analyse', 'Exquisit', 'Erbe', 'Fernsehen', 'Hosen', 'Geschenk', 'Belohnung', 'Wüste', 'Adel', 'Verbindung', 'Geschichte', 'Schule', 'Reife' , 'Regen', 'Lampe', 'Spontanität', 'Claro', 'Sternbild', 'Maus', 'Kultur', 'Frisch', 'Inspiration', 'Sonnengitarre', 'Buch', 'Vielfalt', 'Risiko', 'Orange', 'Universität', 'Entschlossenheit', 'Festival', 'Freundlichkeit', 'Brise', 'Hamster', 'Autobahn', 'Wunder', 'Biene', 'Hoffnung', 'Wissen', 'Hügel', 'Hamster', 'Sanft', 'Energie', 'Strahlend', 'Medizin', 'Schwimmen', 'Wasserfall', 'Zärtlich', 'Warm', 'Freundschaft', 'Telefon', 'Rabbit', 'Monday', 'Outdoors', 'Road', 'Shining', 'Saxophone', 'Ethics', 'Tennis', 'Truck', 'Learning', 'Aufrichtigkeit', 'Nachhaltigkeit', 'Freundlichkeit', 'Dschungel', 'Leuchtkraft', 'Fokus', 'Hund', 'Universität', 'Pflege', 'Entdeckung', 'Garten', 'Fähigkeit', 'Trainieren', 'Beleuchtung', 'Planung', 'Sand', 'Tennis', 'Überschwänglich', 'Überwindung', 'Sommer', 'Ingenieur', 'Wald', 'Sturm', 'Transzendenz', 'Geschieden', 'Harmonie', 'Empathie', 'Respekt', ' Uhr', 'Freund', 'Garn', 'Joghurt', 'Schule', 'Serendipity', 'Flugzeug', 'Spiel', 'Lachen', 'Fülle', 'Skulptur', 'Krankenhaus', 'Lächeln', 'Fesselnd', 'Intuition', 'Erfahrung', 'Pracht', 'Ozean', 'Wohlstand', 'Bewusstsein', ' Tequila', 'Jubiläum', 'Verführung', 'Führung', 'hervorragend', 'Schnitte', 'Erneuerung', 'Valle', 'Morgen', 'Nacht', 'Winter', 'Charisma', 'Evolution' , 'Flexibilität', 'Energetisch', 'Veränderung', 'Basketball', 'Professionalität', 'Inspiration', 'Aufregend', 'Wunderbar', 'Erfolg', 'Solidarität', 'Wiedergeburt', 'Gemüse', ' Kleid', 'Muscheln', 'Meer', 'Medizin', 'Glaube', 'T-Shirt', 'Kreativität', 'Bitter', 'Feier', 'Vitalität', 'Blumen', 'Nacht', ' Lachen', 'Bonus', 'Abenteuer', 'Pfeffer', 'Frühling', 'Aufregung', 'Dach', 'Zucker', 'Kleid', 'Ruhe', 'Freiheit', 'Ruhe', 'Bewusstsein' , 'Jubiläum', 'Momente', 'Glücklich', 'Galaxie', 'Authentizität', 'Meditation', 'Kompetenz', 'Baum', 'Ernährung', 'Herrlich', 'Wissenschaft', 'Erhebung', ' Luft', 'Gerechtigkeit', 'Effizienz', 'Charme', 'Feuer', 'Tradition', 'Oase', 'Überraschung', 'Lehre', 'Freude', 'Träumen', 'Überfließend', 'Abenteuer' , 'Fernsehen', 'Schuhe', 'Schokolade', 'Hund', 'Inspiration', 'Hochzeit', 'Anger', 'Leidenschaftlich', 'Medizin', 'Pinsel', 'Klarheit', 'Surround', ' Pizza', 'Mond', 'Gerechtigkeit', 'Ermächtigung', 'Stuhl', 'Überlauf', 'Wind', 'Reichtum', 'Erinnerungen', 'Begeisterung', 'Technologie', 'Shop', 'Galaxie' , 'Magie', 'Charmant', 'Pasta', 'Überschwänglichkeit', 'Gerechtigkeit', 'Kino', 'Ausdauer', 'Organisation', 'Ausdauer', 'Karriere', 'Erstaunlich', 'Träume', ' Originalität', 'Außergewöhnlich', 'Bedeutsam', 'Büro', 'Einfach', 'Milch', 'Skateboard', 'Mobilfunk', 'Intelligenz', 'Entspannend', 'Sound', 'Ausbruch', 'Sonnenuntergang' , 'Inspirierend', 'Walking', 'Serenity', 'Fantasy', 'Emancipating', 'Watchful', 'Ice Cream', 'Evening', 'Bleistift', 'Zugehörigkeit', 'Unternehmertum', 'Integrität', 'Unschuld', 'Harmonie', 'Selbstwertgefühl', 'Freude', 'Tee', 'Notizbuch', 'Malerei', 'Reis', 'Bereicherung', 'Motivator', 'Inklusion', 'Apfel', 'Achtsamkeit', 'Respekt', 'Erforschung', 'Nachbar', 'Reichtum', 'Transformation', 'Farbe', 'Freude', 'Chaos', 'Erde', 'Schmetterling', 'Bewunderung', 'Exotisch', 'Nachhaltigkeit', 'Leidenschaftlich', 'Vanille', 'Faszinierend', 'Acid', 'Tiger', 'Sadness', 'Vision', 'Lightning', 'Satellite', 'Honest', 'Cellular', 'Gemüse', 'Belebend', 'Whisky', 'Theater', 'Landschaft', 'Gefühl', 'Festung', 'Straße', 'Tür', 'Fleisch', 'Geheimnis', 'Theater', 'Pasta', 'Samstag', 'Engagement', 'Triumph', 'Faszinierend', 'Mut', 'Weizen', 'Freundlichkeit', 'Frieden', 'Nachhaltigkeit', 'Beharrlichkeit', 'Stadt', 'Architektur', 'Party', 'Träumer', 'Pflegen', 'Stärke', 'Seufz', 'Zärtlichkeit', 'Demut', 'Aufstieg', 'Apfel', 'Auto', 'Glänzen', 'Single', 'Beziehungen', 'Fröhlich', 'Belebend', 'Freundlich', 'Aufregend', 'Avenue', 'Beauty', 'Gelb', 'Defiance', 'Kultur', 'Effizienz', 'Batterie', 'Majestätisch', 'Scanner', 'Salz', 'Begleiter', 'Familie', 'Lebendig', 'Umgebung', 'Lernen', 'Anwalt', 'Unterhaltung', 'Werte', 'Shop', 'Akzeptanz', 'Familie', 'Wissen', 'Stärke', 'Geist', 'Mutig', 'Revolution', 'Fürsorge', 'Entdecker', 'Strand', 'Sofa', 'Freundschaft', 'Bus', 'Fisch', 'Tanz', 'Verzauberung', 'Berg', 'Wald', 'Überleben', 'Unvergleichlich', 'Krankenhaus', 'Garten', 'Legende', 'Allee', 'Sublimation', 'Salat', 'Schicksal', 'Art', 'Süß', 'Ewigkeit', 'Hut', 'Ewig', 'Liebend', 'Farbe', 'Herz', 'Konstanz', 'Stuhl', 'Meister', 'Automobil', 'Metropolis', 'Vibrant', 'Tea', 'Dezent', 'Brush', 'Harmony', 'Fullness', 'Addictive', 'Violine', 'Meta', 'Plethoric', 'Thought', 'Lamp', 'Vergnügen', 'Einfallsreichtum', 'Herausforderungen', 'Erstaunlich', 'Job', 'Strand', 'Schutz', 'Morgen', 'Wütend', 'Ehrlichkeit', 'Fantastisch', 'Fesselnd' , 'Überrascht', 'Verwandlung', 'Sommer', 'Mathe', 'Ruhe', 'Motorrad', 'Löwe', 'Komfort', 'Erinnerungen', 'Gesellschaft', 'Drop', 'Traum', ' Bewegen', 'Entwicklung', 'Weisheit', 'Verheiratet', 'Verheiratet', 'Liebe', 'Mode', 'Kunst', 'Heroisch', 'Medizin', 'Souvenir', 'Transzendental', 'Autonomie', 'Decke', 'Philosophie', 'Erstaunlich', 'Sorority', 'Papier', 'Toleranz', 'Wand', 'Schule', 'Aufstieg', 'Zucker', 'Gleichheit', 'Nachmittag', 'Soda', 'Zukunft', 'Paradise', 'Ingenieurwesen', 'Erhaben', 'Ruhe', 'Butter', 'Romantik', 'Mittag', 'Blitz', 'Großzügig', 'Motivation', ' Will', 'Widower', 'Engineering', 'Dawn', 'Wall', 'Vividity', 'Exteriors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder' , 'Berauschend', 'Vielversprechend', 'Bildung', 'Sushi', 'Patient', 'Innovation', 'Landwirtschaft', 'Entschlossenheit', 'Donner', 'Energie', 'Libelle', 'Erstaunlich', 'Lösung', 'Blitz', 'Tiger', 'Katze', 'Widmung', 'Boot', 'Exaltation', 'Spülung', 'Leidenschaft', 'Ökologie', 'Ehrlichkeit', ' Emotion', 'Laufen', 'Technologie', 'Enthüller', 'Erkunden', 'Glare', 'Erwachen', 'Wein', 'Traurigkeit', 'Geschichte', 'Mond', 'Studie', 'Gesundheit' , 'Weisheit', 'Exorbitant', 'Schön', 'Milch', 'Ziele', 'Schal', 'Schwimmen', 'Kunst', 'Tal', 'Fluss', 'Natur', 'Hamburger', ' Geschichte', 'Wohlbefinden', 'Segen', 'Spaß', 'Erkundung', 'Natur', 'Unruhe', 'Melodie', 'Philanthropie', 'Schal', 'Belebend', 'Gesang', ' Toleranz', 'Drop', 'Blick', 'Entdecken', 'Salz', 'Spaß', 'Stadt', 'Verzeihung', 'Menschen', 'Serendipity', 'Solidarität', 'Sonntag', 'Erbe' , 'Fußball', 'Gemeinschaft', 'Herrlich', 'Regenbogen', 'Ermutigung', 'Disziplin', 'Kindergarten', 'Großartig', 'Sehnsucht', 'Hingabe', 'Musik', 'Hilfreich', ' Gesundheit', 'Tür', 'Geschäft', 'Fenster', 'Sensibilität', 'Zug', 'Stabilität', 'Giraffe', 'Rätsel', 'Mut', 'Saft', 'Magie', 'Wort' , 'Einzigartig', 'Klavier', 'Metropolis', 'Produktivität', 'Exhilaration', 'Malerisch', 'Metropolis', 'Erfrischend', 'Schock', 'Reise', 'Mut', 'Schockierend', ' Singen', 'Feier', 'Zusammenarbeit', 'Tanz', 'Spülen', 'Verzauberung', 'Religion', 'Idylle', 'Generation', 'Transzendent', 'Feder', 'Weizen', 'Zufriedenheit' , 'Geschäft', 'Reptil', 'Obst', 'Tisch', 'Organisation', 'Sterne', 'Drucker', 'Ziel', 'Motivation', 'Furchtlosigkeit', 'Gleichgewicht', 'Ruhe', ' Geburtstag', 'Geschieden', 'Glanz', 'Zusammenarbeit', 'Grün', 'Dessert', 'Melancholie', 'Fotografie', 'Lachen', 'Aroma', 'Frucht', 'Entspannung', 'Tau' , 'Kraft', 'Großzügigkeit', 'Lächeln', 'Herbst', 'Impuls', 'Charme', 'Bezaubernd', 'Salzig', 'Klarheit', 'Blau', 'Begeisterung', 'Schönheit', ' Wachstum', 'Zucker', 'Öl', 'Regenbogen', 'Reise', 'Hamster', 'Überraschung', 'Abenteurer', 'Kaffee', 'Erstaunlich', 'Neugier', 'Faden', 'Fisch' , 'Bemerkenswert', 'Verständnis', 'Butter', 'Früher Morgen', 'Student', 'Frühling', 'See', 'Therapie', 'Fähigkeit', 'Anmut', 'Unübertroffen', 'Zweck', 'Kuss', 'Feline', 'Single', 'Frieden', 'Techniker', 'Birne', 'Tanz', 'Kolibri', 'Flugzeug', 'See', 'Berauschend', 'Euphorisch', 'Aufregend', ' Festival', 'Sonne', 'Pants', 'Sprung', 'Boot', 'Keramik', 'Interdependenz', 'Spiel', 'Eloquenz', 'Stimuliert', 'Essenz', 'Salzig', 'Vertrauen', 'Hafer', 'Ethik', 'Initiative', 'Banane', 'Wolke', 'Üppig', 'Schreiben', 'Begegnung', 'Ernährung', 'Wunsch', 'Edel', 'Spiritualität', 'Kooperation', 'Harmonie', 'Pfeffer', 'Verbesserung', 'Erhaben', 'Schillernd', 'Tradition', 'Flexibilität', 'Universum', 'Giraffe', 'Straße', 'Vielfalt', 'Act', 'Sensitive', 'Technical', 'Compassion', 'Spectacular', 'Rice', 'Bird', 'Notebook', 'Genuine', 'Silence', 'Cheese', 'T-Shirt', 'Dawn', 'Abundance', 'Companionship', 'Challenging', 'Atemberaubend', 'Impression', 'Institute', 'Sunset', 'Achievement', 'Tablet', 'Storm', 'Unternehmertum', 'Thunder', 'Exzentrizität', 'Dorf', 'Gefühle', 'Elektrisiert', 'Faszinierend', 'Dankbarkeit', 'Zimt', 'Sieg', 'Loyalität', 'Fahrrad', 'Mais', 'Erfolg', 'Emotion', 'Bildung', 'Wasserfall', 'Freiheit', 'Zahnmedizin', 'Integrität', 'Sofa', 'Forschung', 'Käse', 'Erleuchtung', 'Großzügigkeit', 'Leidenschaft', 'Erde', 'Poesie', 'Opfer', 'Belastbarkeit', 'Wunderbar', 'Energetisch', 'Fenster']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Wort:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("errate einen Buchstaben: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("Richtig!")
                    else:
                        intentos_restantes -= 1
                        print("Falsch. Du bist gegangen", intentos_restantes, "Versuche.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gewonnen! Sie haben das Wort erraten:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Du hast verloren! Das Wort war:", palabra)

            print("Spieler 1:")
            jugar_ahorcado()

            
elif a == 5:
    Multiplayer = int(input("sélectionner le nombre de joueurs 1-2:"))
    if Multiplayer == 2:
        
        b=int(input("Veuillez sélectionner une difficulté:\n1.facile\n2.moyen\n3.difficile" ))
        if b == 1:

            lista = ['Compagnie', 'Biscuit', 'Câlin', 'Fidélité', 'Enrichissant', 'Automne', 'Ambition', 'Lumineux', 'Immobilité', 'Science', 'Rouge', 'Crayon', 'Cannelle ', 'Air', 'Amour', 'Autoroute', 'Patience', 'Solitude', 'Stratégie', 'Percée', 'Mode', 'Croissance', 'Ténacité', 'Excité', 'Littérature', 'Fête ', ' Espoir ', ' Inspirant ', ' Innovation ', ' Créativité ', ' Électrifiant ', ' Émerveillement ', ' Viande ', ' Horloge ', ' Silence ', ' Cap ', ' Neige ', ' Arc ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystère', 'Lunettes', 'Communication', 'Révélation', 'Acclamé', 'Larmes', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery ' , 'Style', 'Enchanteur', 'Sport', 'Littérature', 'Soin', 'Sérénité', 'Chien', 'Rafraîchissant', 'Merveille', 'Bureau', 'Détente', 'Style' , 'Vitalité', 'Conservation', 'Dignité', 'Rédemption', 'Nage', 'Repos', 'Excitant', 'Carrière', 'Avoine', 'Réussite', 'Applaudis', 'Temps', ' Yaourt', 'Océan', 'Cinéma', 'Village', 'Satisfaction', 'Café', 'Guitare', 'Eau', 'Craie', 'Responsabilité', 'Prestige', 'Plaisir', 'Pleurer ', 'Optimisme', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Stylo', 'Bénévolat', 'Espoir', 'Intrigant', 'Éclairant', 'Édifiant', 'Impressionnisme', 'Mardi', 'Architecture', 'Progrès', 'Stars', 'Communauté', 'Momentous ', 'Splendide', 'Colline', 'Environnement', 'Rafraîchissement', 'Crépuscule', 'Innocence', 'Maïs', 'Courage', 'Surpris', 'Exercice', 'Attendre', 'Photographier', 'Réalité', 'Nice', 'Enchantement', 'Crépuscule', 'Désert', 'Impressionné', 'Triste', 'Huile', 'Euphoria', 'Peinture', 'Bien-être', 'Village', 'Glow ' , 'Réflexion', 'Danse', 'Plume', 'Dévouement', 'Plaisir', 'Rire', 'Tomber amoureux', 'Gâteau', 'Sport', 'Réinvention', 'Cacao', 'Gastronomie ', 'Symétrie', 'Fraternité', 'Ingénieur', 'Épanouissant', 'Cacao', 'Aspiration', 'Authenticité', 'Humilité', 'Intrigue', 'Plaisir', 'Conscience', 'Exaltant', 'Avocat', 'Argent', 'Yaourt', 'Conduite', 'Ordinateur', 'Jus', 'Feu', 'Recul', 'Fascination', 'Planète', 'Bonheur', 'Chat', 'Grandeur ', 'Éléphant', 'Doux', 'Lapin', 'Unique', 'Amer', 'Eau', 'Livre', 'Hiver', 'Travail', 'Attractif', 'Optimisme', 'Sculpture', 'Gastronomie', 'Belle', 'Lunettes', 'Football', 'Prodige', 'Expérience', 'Inspirez-vous', 'Mer', 'Mystique', 'Nature', 'Ecrire', 'Fantaisie', ' Marche ', ' Joie ', ' Univers ', ' Te ', ' Expression ', ' Rire ', ' Spiritualité ', ' Rajeunissement ', ' Rivière ', ' Bonheur ', ' Banane ', ' Yoga ', ' Émotionnel' , 'Opportunité' , 'Accueil', 'Stylo', 'Patience', 'Route', 'Joie', 'Confiance', 'Attraction', 'Rêver', 'Génial', 'Anniversaire', 'Cauchemar', ' Émerveillement', 'Nuages', 'Magnifique', 'Équilibre', 'Collaboration', 'Espace', 'Autonomisation', 'Design', 'Étude', 'Émotionnellement', 'Résilience', 'Basketball', 'Éclatant' , 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Moto', 'Beer', 'Chaussures', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passetime', 'Colorful', 'Voyage', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', ' Analyse', 'Exquis', 'Héritage', 'Télévision', 'Pantalon', 'Cadeau', 'Récompense', 'Désert', 'Noblesse', 'Connexion', 'Histoire', 'École', 'Maturité' , 'Pluie' , 'Lampe', 'Spontanéité', 'Claro', 'Constellation', 'Souris', 'Culture', 'Frais', 'Inspiration', 'Sun Guitar', 'Livre', 'Diversité', 'Risque', 'orange', 'Université', 'Détermination', 'Festival', 'Gentillesse', 'Brise', 'Hamster', 'Autoroute', 'Merveille', 'Abeille', 'Espoir', 'Connaissance ', 'Hill', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Lapin', 'Lundi', 'Extérieur', 'Route', 'Shining', 'Saxophone', 'Éthique', 'Tennis', 'Camion', 'Apprentissage', 'Sincérité', 'Durabilité', 'Gentillesse ', ' Jungle ', ' Luminosité ', ' Focus ', ' Chien ', ' Université ', ' Nourrir ', ' Découverte ', ' Jardin ', ' Compétence ', ' Train ', ' Éclairage ', 'Planning', 'Arena', 'Tennis', 'Lush', 'Surmonter', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendance', 'Divorced', 'Harmony', ' Empathie', 'Respect', 'Horloge', 'Ami', 'Fil', 'Yaourt', 'Ecole', 'Sérendipité', 'Avion', 'Jeu', 'Rire', 'Plénitude', 'Sculpture' , 'Hôpital', 'Sourire', 'Captivant', 'Intuition', 'Expérience', 'Splendeur', 'Océan', 'Prospérité', 'Conscience', 'Tequila', 'Anniversaire', 'Séduction', ' Leadership', 'Excellent', 'Courtois', 'Renouveau', 'Valley', 'Matin', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change' , 'Basketball', 'Professionnalisme', 'Inspiration', 'Passionnant', 'Merveilleux', 'Succès', 'Solidarité', 'Renaissance', 'Légumes', 'Robe', 'Coquillages', 'Mer', ' Docteur', 'Foi', 'T-shirt', 'Créativité', 'Amer', 'Célébration', 'Vitalité', 'Fleurs', 'Nuit', 'Rire', 'Reconnaissance', 'Aventure', ' Poivre', 'Printemps', 'Exaltant', 'Plafond', 'Sucre', 'Robe', 'Calme', 'Liberté', 'Tranquillité', 'Conscience', 'Anniversaire', 'Moments', 'Heureux' , ' Galaxie ', ' Authenticité ', ' Méditation ', ' Compétence ', ' Arbre ', ' Nutrition ', ' Glorieux ', ' Science ', ' Altitude ', ' Air ', ' Justice ', ' Efficacité ', ' Charme', 'Feu', 'Tradition', 'Oasis', 'Surprise', 'Enseignement', 'Joie', 'Rêve', 'Débordant', 'Aventure', 'Télévision', 'Chaussures', 'Chocolat' , 'Chien', 'Inspiration', 'Mariage', 'Colère', 'Passionné', 'Médecine', 'Pinceau', 'Clarté', 'Entourage', 'Pizza', 'Lune', 'Justice', ' Autonomisation', 'Chaise', 'Débordement', 'Vent', 'Richesse', 'Souvenirs', 'Enthousiasme', 'Technologie', 'Boutique', 'Galaxy', 'Magie', 'Charmant', 'Pâtes' , 'Exubérance', 'Équité', 'Cinéma', 'Persévérance', 'Organisation', 'Persévérance', 'Carrière', 'Incroyable', 'Rêve', 'Originalité', 'Extraordinaire', 'Transcendantale', ' Bureau', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity' , ' Fantasy', 'Emancipator', 'Watchful', 'Ice Cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-estime ', 'Joie' , 'Thé', 'Cahier', 'Peinture', 'Riz', 'Enrichissement', 'Motivateur', 'Inclusion', 'Pomme', 'Mindfulness', 'Respect', 'Exploration',  'Voisin ', ' Richesse ', ' Transformation ', ' Peinture ', ' Joie ', ' Chaos ', ' Terre ', ' Papillon ', ' Émerveillement ', ' Exotique ', ' Durabilité ', ' Passionné ', ' Vanille ', 'Fascinant' , 'Acide', 'Tigre', 'Tristesse', 'Vision', 'Foudre', 'Satellite', 'Honnête', 'Cellulaire', 'Végétal', 'Revigorant', 'Whisky', 'Théâtre', 'Paysage', 'Sensation', 'Forteresse', 'Rue', 'Porte', 'Viande', 'Mystère', 'Théâtre', 'Pâtes', 'Samedi', 'Fiançailles', 'Triumph ', 'Fascinant' , 'Courage', 'Blé', 'Gentillesse', 'Paix', 'Durabilité', 'Persistance', 'Ville', 'Architecture', 'Fête', 'Rêveur', 'Infirmier', 'Fortitude', 'Soupir', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Gai', 'Revitalizing', 'Friendly ', 'Excitant' , 'Avenue', 'Beauty', 'Yellow', 'Challenge', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Famille', 'Vibrant', 'Environnement', 'Apprentissage', 'Avocat', 'Divertissement', 'Valeurs', 'Boutique', 'Acceptation', 'Famille', 'Connaissance', 'Force', 'Esprit ', 'Brave', 'Révolution', 'Care', 'Explorateur', 'Plage', 'Canapé', 'Amitié', 'Bus', 'Poisson', 'Danse', 'Enchantement', 'Montagne', 'Forêt', 'Survie', 'Incomparable', 'Hôpital', 'Jardin', 'Légende', 'Avenue', 'Sublimation', 'Salade', 'Destiny', 'Gentil', 'Doux', 'Eternité ', 'Chapeau', 'Éternel', 'Amoureux', 'Peinture', 'Coeur', 'Constance', 'Chaise', 'Maître', 'Automobile', 'Metropolis', 'Vibrant', 'Thé', 'Maîtrisé', 'Pinceau', 'Harmonie', 'Plénitude', 'Addictif', 'Violon', 'Méta', 'Pléthorique', 'Pensée', 'Lampe', 'Plaisir', 'Ingéniosité', 'Défis ', 'Incroyable', 'Travail', 'Plage', 'Refuge', 'Matin', 'En colère', 'Honnêteté', 'Fantastique', 'Captivant', 'Émerveillé', 'Transformation', 'Été', 'Math', 'Calme', 'Moto', 'Lion', 'Confort', 'Mémoires', 'Entreprise', 'Drop', 'Rêve', 'Move', 'Développement', 'Sagesse', 'Marié ', 'Marié', 'Amour', 'Mode', 'Art', 'Héroïque', 'Médical', 'Souvenir', 'Transcendental', 'Autonomie', 'Toit', 'Philosophie', 'Incroyable', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', 'Equality', 'Afternoon', 'Soda', 'Future', 'Paradise', 'Engineering ', 'Sublime', 'Repos', 'Beurre', 'Romance', 'Midi', 'Foudre', 'Généreux', 'Motivation', 'Volonté', 'Veuve', 'Ingénierie', 'Dawn', 'Wall', 'Vividity', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder', 'Heady', 'Promising', ' Éducation', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Détermination', 'Tonnerre', 'Énergie', 'Libellule', 'Incroyable', 'Solution', 'Foudre', 'Tigre' , 'Chat', 'Dévouement', 'Bateau', 'Exaltation', 'Rinçage', 'Passion', 'Écologie', 'Honnêteté', 'Émotion', 'Course', 'Technologie', 'Révélateur', ' Explore', 'Dazzle', 'Awaken', 'Wine', 'Tristness', 'History', 'Moon', 'Study', 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk' , 'Objectifs', 'Écharpe', 'Nager', 'Art', 'Vallée', 'Rivière', 'Nature', 'Hamburger', 'Histoire', 'Bien-être', 'Bénédiction', 'Fun', ' Exploration', 'Nature', 'Agitation', 'Mélodie', 'Philanthropie', 'Foulard', 'Revigorant', 'Chant', 'Tolérance', 'Drop', 'Regard', 'Découvrir', 'Sel' , 'Fun', 'Ville', 'Désolé', 'Ville', 'Sérendipité', 'Solidarité', 'Dimanche', 'Patrimoine', 'Football', 'Communauté', 'Magnifique', 'Arc-en-ciel', ' Encouragement', 'Discipline', 'Pépinière', 'Super', 'Désir', 'Dévouement', 'Musique', 'Utile', 'Santé', 'Porte', 'Affaires', 'Fenêtre', 'Sensibilité' , 'Train', 'Stabilité', 'Girafe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', ' Exaltation', 'Picturesque', 'Metropolis', 'Renewal', 'Shudder', 'Journey', 'Courage', 'Shocking', 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinsing' , 'Enchantement', 'Religion', 'Idyllique', 'Génération', 'Transcendant', 'Plume', 'Blé', 'Satisfaction', 'Affaires', 'Reptile', 'Fruit', 'Table',  'Organisation', 'Stars', 'Imprimante', 'Objectif', 'Motivation', 'Intrépidité', 'Équilibre', 'Calme', 'Anniversaire', 'Divorcé', 'Briller', 'Collaboration', 'Vert' , 'Dessert', 'Mélancolie', 'Photographie', 'Rire', 'Arôme', 'Fruit', 'Détente', 'Rosée', 'Vigueur', 'Générosité', 'Sourire', 'Automne', ' Impulsion', 'Charme', 'Enchanteur', 'Salé', 'Lucidité', 'Bleu', 'Enthousiasme', 'Beauté', 'Croissance', 'Sucre', 'Huile', 'Arc-en-ciel', 'Voyage' , 'Hamster', 'Surprise', 'Aventurier', 'Café', 'Surprenant', 'Curiosité', 'Fil', 'Poisson', 'Remarquable', 'Comprendre', 'Beurre', 'Tôt le matin', 'Étudiant', 'Printemps', 'Lac', 'Thérapie', 'Compétence', 'Grâce', 'Inégalé', 'Objectif', 'Baiser', 'Félin', 'Célibataire', 'Paix', 'Technicien ' , ' Poire ', ' Danse ', ' Colibri ', ' Avion ', ' Lac ', ' Enivrant ', ' Euphorique ', ' Excitant ', ' Fête ', ' Soleil ', ' Pantalon ', ' Sauter ', 'Bateau', 'Céramique', 'Interdépendance', 'Jeu', 'Eloquence', 'Stimulé', 'Essence', 'Salé', 'Confiance', 'Avoine', 'Ethique', 'Initiative', 'Banane ' , 'Nuage', 'Lush', 'Ecrire', 'Rencontre', 'Nourriture', 'Souhait', 'Noble', 'Spiritualité', 'Coopération', 'Harmonie', 'Poivre', 'Améliorer', 'Sublime', 'Éblouissant', 'Tradition', 'Souplesse', 'Univers', 'Girafe', 'Street', 'Diversity', 'Acting', 'Sensitive', 'Technical', 'Compassion', 'Spectacular ' , 'Riz', 'Oiseau', 'Cahier', 'Authentique', 'Silence', 'Fromage', 'T-shirt', 'Aube', 'Abondance', 'Compagnie', 'Défi', 'Astonante ', 'Impression', 'Institut', 'Sunset', 'Réussite', 'Tablette', 'Tempête', 'Entrepreneuriat', 'Tonnerre', 'Excentricité', 'Village', 'Sentiments', 'Électrifié',  'Fascinant ', ' Gratitude ', ' Cannelle ', ' Victoire ', ' Loyauté ', ' Vélo ', ' Maïs ', ' Succès ', ' Émotion ', ' Éducation ', ' Cascade ', ' Liberté ', ' Dentisterie ' , 'Intégrité', 'Canapé', 'Recherche', 'Fromage', 'Illumination', 'Générosité', 'Passion', 'Terre', 'Poésie', 'Sacrifice', 'Résilience', 'Merveilleusement', 'Énergétique' , 'Fenêtre']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Mot:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Devinez une lettre : ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("C'est Correct!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrect. Ils te donnent", intentos_restantes, "tentatives.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gagné! Vous avez deviné le mot:", palabra)
                        break

                if intentos_restantes == 0:
                        print("Tu as perdu! Le mot était:", palabra)


            print("joueur 1:")
            jugar_ahorcado()
            print("joueur 2:")
            jugar_ahorcado()
            
        elif b == 2:


            lista = ['Compagnie', 'Biscuit', 'Câlin', 'Fidélité', 'Enrichissant', 'Automne', 'Ambition', 'Lumineux', 'Immobilité', 'Science', 'Rouge', 'Crayon', 'Cannelle ', 'Air', 'Amour', 'Autoroute', 'Patience', 'Solitude', 'Stratégie', 'Percée', 'Mode', 'Croissance', 'Ténacité', 'Excité', 'Littérature', 'Fête ', ' Espoir ', ' Inspirant ', ' Innovation ', ' Créativité ', ' Électrifiant ', ' Émerveillement ', ' Viande ', ' Horloge ', ' Silence ', ' Cap ', ' Neige ', ' Arc ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystère', 'Lunettes', 'Communication', 'Révélation', 'Acclamé', 'Larmes', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery ' , 'Style', 'Enchanteur', 'Sport', 'Littérature', 'Soin', 'Sérénité', 'Chien', 'Rafraîchissant', 'Merveille', 'Bureau', 'Détente', 'Style' , 'Vitalité', 'Conservation', 'Dignité', 'Rédemption', 'Nage', 'Repos', 'Excitant', 'Carrière', 'Avoine', 'Réussite', 'Applaudis', 'Temps', ' Yaourt', 'Océan', 'Cinéma', 'Village', 'Satisfaction', 'Café', 'Guitare', 'Eau', 'Craie', 'Responsabilité', 'Prestige', 'Plaisir', 'Pleurer ', 'Optimisme', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Stylo', 'Bénévolat', 'Espoir', 'Intrigant', 'Éclairant', 'Édifiant', 'Impressionnisme', 'Mardi', 'Architecture', 'Progrès', 'Stars', 'Communauté', 'Momentous ', 'Splendide', 'Colline', 'Environnement', 'Rafraîchissement', 'Crépuscule', 'Innocence', 'Maïs', 'Courage', 'Surpris', 'Exercice', 'Attendre', 'Photographier', 'Réalité', 'Nice', 'Enchantement', 'Crépuscule', 'Désert', 'Impressionné', 'Triste', 'Huile', 'Euphoria', 'Peinture', 'Bien-être', 'Village', 'Glow ' , 'Réflexion', 'Danse', 'Plume', 'Dévouement', 'Plaisir', 'Rire', 'Tomber amoureux', 'Gâteau', 'Sport', 'Réinvention', 'Cacao', 'Gastronomie ', 'Symétrie', 'Fraternité', 'Ingénieur', 'Épanouissant', 'Cacao', 'Aspiration', 'Authenticité', 'Humilité', 'Intrigue', 'Plaisir', 'Conscience', 'Exaltant', 'Avocat', 'Argent', 'Yaourt', 'Conduite', 'Ordinateur', 'Jus', 'Feu', 'Recul', 'Fascination', 'Planète', 'Bonheur', 'Chat', 'Grandeur ', 'Éléphant', 'Doux', 'Lapin', 'Unique', 'Amer', 'Eau', 'Livre', 'Hiver', 'Travail', 'Attractif', 'Optimisme', 'Sculpture', 'Gastronomie', 'Belle', 'Lunettes', 'Football', 'Prodige', 'Expérience', 'Inspirez-vous', 'Mer', 'Mystique', 'Nature', 'Ecrire', 'Fantaisie', ' Marche ', ' Joie ', ' Univers ', ' Te ', ' Expression ', ' Rire ', ' Spiritualité ', ' Rajeunissement ', ' Rivière ', ' Bonheur ', ' Banane ', ' Yoga ', ' Émotionnel' , 'Opportunité' , 'Accueil', 'Stylo', 'Patience', 'Route', 'Joie', 'Confiance', 'Attraction', 'Rêver', 'Génial', 'Anniversaire', 'Cauchemar', ' Émerveillement', 'Nuages', 'Magnifique', 'Équilibre', 'Collaboration', 'Espace', 'Autonomisation', 'Design', 'Étude', 'Émotionnellement', 'Résilience', 'Basketball', 'Éclatant' , 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Moto', 'Beer', 'Chaussures', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passetime', 'Colorful', 'Voyage', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', ' Analyse', 'Exquis', 'Héritage', 'Télévision', 'Pantalon', 'Cadeau', 'Récompense', 'Désert', 'Noblesse', 'Connexion', 'Histoire', 'École', 'Maturité' , 'Pluie' , 'Lampe', 'Spontanéité', 'Claro', 'Constellation', 'Souris', 'Culture', 'Frais', 'Inspiration', 'Sun Guitar', 'Livre', 'Diversité', 'Risque', 'orange', 'Université', 'Détermination', 'Festival', 'Gentillesse', 'Brise', 'Hamster', 'Autoroute', 'Merveille', 'Abeille', 'Espoir', 'Connaissance ', 'Hill', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Lapin', 'Lundi', 'Extérieur', 'Route', 'Shining', 'Saxophone', 'Éthique', 'Tennis', 'Camion', 'Apprentissage', 'Sincérité', 'Durabilité', 'Gentillesse ', ' Jungle ', ' Luminosité ', ' Focus ', ' Chien ', ' Université ', ' Nourrir ', ' Découverte ', ' Jardin ', ' Compétence ', ' Train ', ' Éclairage ', 'Planning', 'Arena', 'Tennis', 'Lush', 'Surmonter', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendance', 'Divorced', 'Harmony', ' Empathie', 'Respect', 'Horloge', 'Ami', 'Fil', 'Yaourt', 'Ecole', 'Sérendipité', 'Avion', 'Jeu', 'Rire', 'Plénitude', 'Sculpture' , 'Hôpital', 'Sourire', 'Captivant', 'Intuition', 'Expérience', 'Splendeur', 'Océan', 'Prospérité', 'Conscience', 'Tequila', 'Anniversaire', 'Séduction', ' Leadership', 'Excellent', 'Courtois', 'Renouveau', 'Valley', 'Matin', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change' , 'Basketball', 'Professionnalisme', 'Inspiration', 'Passionnant', 'Merveilleux', 'Succès', 'Solidarité', 'Renaissance', 'Légumes', 'Robe', 'Coquillages', 'Mer', ' Docteur', 'Foi', 'T-shirt', 'Créativité', 'Amer', 'Célébration', 'Vitalité', 'Fleurs', 'Nuit', 'Rire', 'Reconnaissance', 'Aventure', ' Poivre', 'Printemps', 'Exaltant', 'Plafond', 'Sucre', 'Robe', 'Calme', 'Liberté', 'Tranquillité', 'Conscience', 'Anniversaire', 'Moments', 'Heureux' , ' Galaxie ', ' Authenticité ', ' Méditation ', ' Compétence ', ' Arbre ', ' Nutrition ', ' Glorieux ', ' Science ', ' Altitude ', ' Air ', ' Justice ', ' Efficacité ', ' Charme', 'Feu', 'Tradition', 'Oasis', 'Surprise', 'Enseignement', 'Joie', 'Rêve', 'Débordant', 'Aventure', 'Télévision', 'Chaussures', 'Chocolat' , 'Chien', 'Inspiration', 'Mariage', 'Colère', 'Passionné', 'Médecine', 'Pinceau', 'Clarté', 'Entourage', 'Pizza', 'Lune', 'Justice', ' Autonomisation', 'Chaise', 'Débordement', 'Vent', 'Richesse', 'Souvenirs', 'Enthousiasme', 'Technologie', 'Boutique', 'Galaxy', 'Magie', 'Charmant', 'Pâtes' , 'Exubérance', 'Équité', 'Cinéma', 'Persévérance', 'Organisation', 'Persévérance', 'Carrière', 'Incroyable', 'Rêve', 'Originalité', 'Extraordinaire', 'Transcendantale', ' Bureau', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity' , ' Fantasy', 'Emancipator', 'Watchful', 'Ice Cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-estime ', 'Joie' , 'Thé', 'Cahier', 'Peinture', 'Riz', 'Enrichissement', 'Motivateur', 'Inclusion', 'Pomme', 'Mindfulness', 'Respect', 'Exploration',  'Voisin ', ' Richesse ', ' Transformation ', ' Peinture ', ' Joie ', ' Chaos ', ' Terre ', ' Papillon ', ' Émerveillement ', ' Exotique ', ' Durabilité ', ' Passionné ', ' Vanille ', 'Fascinant' , 'Acide', 'Tigre', 'Tristesse', 'Vision', 'Foudre', 'Satellite', 'Honnête', 'Cellulaire', 'Végétal', 'Revigorant', 'Whisky', 'Théâtre', 'Paysage', 'Sensation', 'Forteresse', 'Rue', 'Porte', 'Viande', 'Mystère', 'Théâtre', 'Pâtes', 'Samedi', 'Fiançailles', 'Triumph ', 'Fascinant' , 'Courage', 'Blé', 'Gentillesse', 'Paix', 'Durabilité', 'Persistance', 'Ville', 'Architecture', 'Fête', 'Rêveur', 'Infirmier', 'Fortitude', 'Soupir', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Gai', 'Revitalizing', 'Friendly ', 'Excitant' , 'Avenue', 'Beauty', 'Yellow', 'Challenge', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Famille', 'Vibrant', 'Environnement', 'Apprentissage', 'Avocat', 'Divertissement', 'Valeurs', 'Boutique', 'Acceptation', 'Famille', 'Connaissance', 'Force', 'Esprit ', 'Brave', 'Révolution', 'Care', 'Explorateur', 'Plage', 'Canapé', 'Amitié', 'Bus', 'Poisson', 'Danse', 'Enchantement', 'Montagne', 'Forêt', 'Survie', 'Incomparable', 'Hôpital', 'Jardin', 'Légende', 'Avenue', 'Sublimation', 'Salade', 'Destiny', 'Gentil', 'Doux', 'Eternité ', 'Chapeau', 'Éternel', 'Amoureux', 'Peinture', 'Coeur', 'Constance', 'Chaise', 'Maître', 'Automobile', 'Metropolis', 'Vibrant', 'Thé', 'Maîtrisé', 'Pinceau', 'Harmonie', 'Plénitude', 'Addictif', 'Violon', 'Méta', 'Pléthorique', 'Pensée', 'Lampe', 'Plaisir', 'Ingéniosité', 'Défis ', 'Incroyable', 'Travail', 'Plage', 'Refuge', 'Matin', 'En colère', 'Honnêteté', 'Fantastique', 'Captivant', 'Émerveillé', 'Transformation', 'Été', 'Math', 'Calme', 'Moto', 'Lion', 'Confort', 'Mémoires', 'Entreprise', 'Drop', 'Rêve', 'Move', 'Développement', 'Sagesse', 'Marié ', 'Marié', 'Amour', 'Mode', 'Art', 'Héroïque', 'Médical', 'Souvenir', 'Transcendental', 'Autonomie', 'Toit', 'Philosophie', 'Incroyable', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', 'Equality', 'Afternoon', 'Soda', 'Future', 'Paradise', 'Engineering ', 'Sublime', 'Repos', 'Beurre', 'Romance', 'Midi', 'Foudre', 'Généreux', 'Motivation', 'Volonté', 'Veuve', 'Ingénierie', 'Dawn', 'Wall', 'Vividity', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder', 'Heady', 'Promising', ' Éducation', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Détermination', 'Tonnerre', 'Énergie', 'Libellule', 'Incroyable', 'Solution', 'Foudre', 'Tigre' , 'Chat', 'Dévouement', 'Bateau', 'Exaltation', 'Rinçage', 'Passion', 'Écologie', 'Honnêteté', 'Émotion', 'Course', 'Technologie', 'Révélateur', ' Explore', 'Dazzle', 'Awaken', 'Wine', 'Tristness', 'History', 'Moon', 'Study', 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk' , 'Objectifs', 'Écharpe', 'Nager', 'Art', 'Vallée', 'Rivière', 'Nature', 'Hamburger', 'Histoire', 'Bien-être', 'Bénédiction', 'Fun', ' Exploration', 'Nature', 'Agitation', 'Mélodie', 'Philanthropie', 'Foulard', 'Revigorant', 'Chant', 'Tolérance', 'Drop', 'Regard', 'Découvrir', 'Sel' , 'Fun', 'Ville', 'Désolé', 'Ville', 'Sérendipité', 'Solidarité', 'Dimanche', 'Patrimoine', 'Football', 'Communauté', 'Magnifique', 'Arc-en-ciel', ' Encouragement', 'Discipline', 'Pépinière', 'Super', 'Désir', 'Dévouement', 'Musique', 'Utile', 'Santé', 'Porte', 'Affaires', 'Fenêtre', 'Sensibilité' , 'Train', 'Stabilité', 'Girafe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', ' Exaltation', 'Picturesque', 'Metropolis', 'Renewal', 'Shudder', 'Journey', 'Courage', 'Shocking', 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinsing' , 'Enchantement', 'Religion', 'Idyllique', 'Génération', 'Transcendant', 'Plume', 'Blé', 'Satisfaction', 'Affaires', 'Reptile', 'Fruit', 'Table',  'Organisation', 'Stars', 'Imprimante', 'Objectif', 'Motivation', 'Intrépidité', 'Équilibre', 'Calme', 'Anniversaire', 'Divorcé', 'Briller', 'Collaboration', 'Vert' , 'Dessert', 'Mélancolie', 'Photographie', 'Rire', 'Arôme', 'Fruit', 'Détente', 'Rosée', 'Vigueur', 'Générosité', 'Sourire', 'Automne', ' Impulsion', 'Charme', 'Enchanteur', 'Salé', 'Lucidité', 'Bleu', 'Enthousiasme', 'Beauté', 'Croissance', 'Sucre', 'Huile', 'Arc-en-ciel', 'Voyage' , 'Hamster', 'Surprise', 'Aventurier', 'Café', 'Surprenant', 'Curiosité', 'Fil', 'Poisson', 'Remarquable', 'Comprendre', 'Beurre', 'Tôt le matin', 'Étudiant', 'Printemps', 'Lac', 'Thérapie', 'Compétence', 'Grâce', 'Inégalé', 'Objectif', 'Baiser', 'Félin', 'Célibataire', 'Paix', 'Technicien ' , ' Poire ', ' Danse ', ' Colibri ', ' Avion ', ' Lac ', ' Enivrant ', ' Euphorique ', ' Excitant ', ' Fête ', ' Soleil ', ' Pantalon ', ' Sauter ', 'Bateau', 'Céramique', 'Interdépendance', 'Jeu', 'Eloquence', 'Stimulé', 'Essence', 'Salé', 'Confiance', 'Avoine', 'Ethique', 'Initiative', 'Banane ' , 'Nuage', 'Lush', 'Ecrire', 'Rencontre', 'Nourriture', 'Souhait', 'Noble', 'Spiritualité', 'Coopération', 'Harmonie', 'Poivre', 'Améliorer', 'Sublime', 'Éblouissant', 'Tradition', 'Souplesse', 'Univers', 'Girafe', 'Street', 'Diversity', 'Acting', 'Sensitive', 'Technical', 'Compassion', 'Spectacular ' , 'Riz', 'Oiseau', 'Cahier', 'Authentique', 'Silence', 'Fromage', 'T-shirt', 'Aube', 'Abondance', 'Compagnie', 'Défi', 'Astonante ', 'Impression', 'Institut', 'Sunset', 'Réussite', 'Tablette', 'Tempête', 'Entrepreneuriat', 'Tonnerre', 'Excentricité', 'Village', 'Sentiments', 'Électrifié',  'Fascinant ', ' Gratitude ', ' Cannelle ', ' Victoire ', ' Loyauté ', ' Vélo ', ' Maïs ', ' Succès ', ' Émotion ', ' Éducation ', ' Cascade ', ' Liberté ', ' Dentisterie ' , 'Intégrité', 'Canapé', 'Recherche', 'Fromage', 'Illumination', 'Générosité', 'Passion', 'Terre', 'Poésie', 'Sacrifice', 'Résilience', 'Merveilleusement', 'Énergétique' , 'Fenêtre']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Mot:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Devinez une lettre: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("C'est Correct!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrect. Ils te donnent", intentos_restantes, "tentatives.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gagné! Vous avez deviné le mot:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Tu as perdu! Le mot était:", palabra)



            print("joueur 1:")
            jugar_ahorcado()
            print("joueur 2:")
            jugar_ahorcado()


        elif b == 3:

            import random
            lista = ['Compagnie', 'Biscuit', 'Câlin', 'Fidélité', 'Enrichissant', 'Automne', 'Ambition', 'Lumineux', 'Immobilité', 'Science', 'Rouge', 'Crayon', 'Cannelle ', 'Air', 'Amour', 'Autoroute', 'Patience', 'Solitude', 'Stratégie', 'Percée', 'Mode', 'Croissance', 'Ténacité', 'Excité', 'Littérature', 'Fête ', ' Espoir ', ' Inspirant ', ' Innovation ', ' Créativité ', ' Électrifiant ', ' Émerveillement ', ' Viande ', ' Horloge ', ' Silence ', ' Cap ', ' Neige ', ' Arc ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystère', 'Lunettes', 'Communication', 'Révélation', 'Acclamé', 'Larmes', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery ' , 'Style', 'Enchanteur', 'Sport', 'Littérature', 'Soin', 'Sérénité', 'Chien', 'Rafraîchissant', 'Merveille', 'Bureau', 'Détente', 'Style' , 'Vitalité', 'Conservation', 'Dignité', 'Rédemption', 'Nage', 'Repos', 'Excitant', 'Carrière', 'Avoine', 'Réussite', 'Applaudis', 'Temps', ' Yaourt', 'Océan', 'Cinéma', 'Village', 'Satisfaction', 'Café', 'Guitare', 'Eau', 'Craie', 'Responsabilité', 'Prestige', 'Plaisir', 'Pleurer ', 'Optimisme', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Stylo', 'Bénévolat', 'Espoir', 'Intrigant', 'Éclairant', 'Édifiant', 'Impressionnisme', 'Mardi', 'Architecture', 'Progrès', 'Stars', 'Communauté', 'Momentous ', 'Splendide', 'Colline', 'Environnement', 'Rafraîchissement', 'Crépuscule', 'Innocence', 'Maïs', 'Courage', 'Surpris', 'Exercice', 'Attendre', 'Photographier', 'Réalité', 'Nice', 'Enchantement', 'Crépuscule', 'Désert', 'Impressionné', 'Triste', 'Huile', 'Euphoria', 'Peinture', 'Bien-être', 'Village', 'Glow ' , 'Réflexion', 'Danse', 'Plume', 'Dévouement', 'Plaisir', 'Rire', 'Tomber amoureux', 'Gâteau', 'Sport', 'Réinvention', 'Cacao', 'Gastronomie ', 'Symétrie', 'Fraternité', 'Ingénieur', 'Épanouissant', 'Cacao', 'Aspiration', 'Authenticité', 'Humilité', 'Intrigue', 'Plaisir', 'Conscience', 'Exaltant', 'Avocat', 'Argent', 'Yaourt', 'Conduite', 'Ordinateur', 'Jus', 'Feu', 'Recul', 'Fascination', 'Planète', 'Bonheur', 'Chat', 'Grandeur ', 'Éléphant', 'Doux', 'Lapin', 'Unique', 'Amer', 'Eau', 'Livre', 'Hiver', 'Travail', 'Attractif', 'Optimisme', 'Sculpture', 'Gastronomie', 'Belle', 'Lunettes', 'Football', 'Prodige', 'Expérience', 'Inspirez-vous', 'Mer', 'Mystique', 'Nature', 'Ecrire', 'Fantaisie', ' Marche ', ' Joie ', ' Univers ', ' Te ', ' Expression ', ' Rire ', ' Spiritualité ', ' Rajeunissement ', ' Rivière ', ' Bonheur ', ' Banane ', ' Yoga ', ' Émotionnel' , 'Opportunité' , 'Accueil', 'Stylo', 'Patience', 'Route', 'Joie', 'Confiance', 'Attraction', 'Rêver', 'Génial', 'Anniversaire', 'Cauchemar', ' Émerveillement', 'Nuages', 'Magnifique', 'Équilibre', 'Collaboration', 'Espace', 'Autonomisation', 'Design', 'Étude', 'Émotionnellement', 'Résilience', 'Basketball', 'Éclatant' , 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Moto', 'Beer', 'Chaussures', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passetime', 'Colorful', 'Voyage', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', ' Analyse', 'Exquis', 'Héritage', 'Télévision', 'Pantalon', 'Cadeau', 'Récompense', 'Désert', 'Noblesse', 'Connexion', 'Histoire', 'École', 'Maturité' , 'Pluie' , 'Lampe', 'Spontanéité', 'Claro', 'Constellation', 'Souris', 'Culture', 'Frais', 'Inspiration', 'Sun Guitar', 'Livre', 'Diversité', 'Risque', 'orange', 'Université', 'Détermination', 'Festival', 'Gentillesse', 'Brise', 'Hamster', 'Autoroute', 'Merveille', 'Abeille', 'Espoir', 'Connaissance ', 'Hill', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Lapin', 'Lundi', 'Extérieur', 'Route', 'Shining', 'Saxophone', 'Éthique', 'Tennis', 'Camion', 'Apprentissage', 'Sincérité', 'Durabilité', 'Gentillesse ', ' Jungle ', ' Luminosité ', ' Focus ', ' Chien ', ' Université ', ' Nourrir ', ' Découverte ', ' Jardin ', ' Compétence ', ' Train ', ' Éclairage ', 'Planning', 'Arena', 'Tennis', 'Lush', 'Surmonter', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendance', 'Divorced', 'Harmony', ' Empathie', 'Respect', 'Horloge', 'Ami', 'Fil', 'Yaourt', 'Ecole', 'Sérendipité', 'Avion', 'Jeu', 'Rire', 'Plénitude', 'Sculpture' , 'Hôpital', 'Sourire', 'Captivant', 'Intuition', 'Expérience', 'Splendeur', 'Océan', 'Prospérité', 'Conscience', 'Tequila', 'Anniversaire', 'Séduction', ' Leadership', 'Excellent', 'Courtois', 'Renouveau', 'Valley', 'Matin', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change' , 'Basketball', 'Professionnalisme', 'Inspiration', 'Passionnant', 'Merveilleux', 'Succès', 'Solidarité', 'Renaissance', 'Légumes', 'Robe', 'Coquillages', 'Mer', ' Docteur', 'Foi', 'T-shirt', 'Créativité', 'Amer', 'Célébration', 'Vitalité', 'Fleurs', 'Nuit', 'Rire', 'Reconnaissance', 'Aventure', ' Poivre', 'Printemps', 'Exaltant', 'Plafond', 'Sucre', 'Robe', 'Calme', 'Liberté', 'Tranquillité', 'Conscience', 'Anniversaire', 'Moments', 'Heureux' , ' Galaxie ', ' Authenticité ', ' Méditation ', ' Compétence ', ' Arbre ', ' Nutrition ', ' Glorieux ', ' Science ', ' Altitude ', ' Air ', ' Justice ', ' Efficacité ', ' Charme', 'Feu', 'Tradition', 'Oasis', 'Surprise', 'Enseignement', 'Joie', 'Rêve', 'Débordant', 'Aventure', 'Télévision', 'Chaussures', 'Chocolat' , 'Chien', 'Inspiration', 'Mariage', 'Colère', 'Passionné', 'Médecine', 'Pinceau', 'Clarté', 'Entourage', 'Pizza', 'Lune', 'Justice', ' Autonomisation', 'Chaise', 'Débordement', 'Vent', 'Richesse', 'Souvenirs', 'Enthousiasme', 'Technologie', 'Boutique', 'Galaxy', 'Magie', 'Charmant', 'Pâtes' , 'Exubérance', 'Équité', 'Cinéma', 'Persévérance', 'Organisation', 'Persévérance', 'Carrière', 'Incroyable', 'Rêve', 'Originalité', 'Extraordinaire', 'Transcendantale', ' Bureau', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity' , ' Fantasy', 'Emancipator', 'Watchful', 'Ice Cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-estime ', 'Joie' , 'Thé', 'Cahier', 'Peinture', 'Riz', 'Enrichissement', 'Motivateur', 'Inclusion', 'Pomme', 'Mindfulness', 'Respect', 'Exploration',  'Voisin ', ' Richesse ', ' Transformation ', ' Peinture ', ' Joie ', ' Chaos ', ' Terre ', ' Papillon ', ' Émerveillement ', ' Exotique ', ' Durabilité ', ' Passionné ', ' Vanille ', 'Fascinant' , 'Acide', 'Tigre', 'Tristesse', 'Vision', 'Foudre', 'Satellite', 'Honnête', 'Cellulaire', 'Végétal', 'Revigorant', 'Whisky', 'Théâtre', 'Paysage', 'Sensation', 'Forteresse', 'Rue', 'Porte', 'Viande', 'Mystère', 'Théâtre', 'Pâtes', 'Samedi', 'Fiançailles', 'Triumph ', 'Fascinant' , 'Courage', 'Blé', 'Gentillesse', 'Paix', 'Durabilité', 'Persistance', 'Ville', 'Architecture', 'Fête', 'Rêveur', 'Infirmier', 'Fortitude', 'Soupir', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Gai', 'Revitalizing', 'Friendly ', 'Excitant' , 'Avenue', 'Beauty', 'Yellow', 'Challenge', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Famille', 'Vibrant', 'Environnement', 'Apprentissage', 'Avocat', 'Divertissement', 'Valeurs', 'Boutique', 'Acceptation', 'Famille', 'Connaissance', 'Force', 'Esprit ', 'Brave', 'Révolution', 'Care', 'Explorateur', 'Plage', 'Canapé', 'Amitié', 'Bus', 'Poisson', 'Danse', 'Enchantement', 'Montagne', 'Forêt', 'Survie', 'Incomparable', 'Hôpital', 'Jardin', 'Légende', 'Avenue', 'Sublimation', 'Salade', 'Destiny', 'Gentil', 'Doux', 'Eternité ', 'Chapeau', 'Éternel', 'Amoureux', 'Peinture', 'Coeur', 'Constance', 'Chaise', 'Maître', 'Automobile', 'Metropolis', 'Vibrant', 'Thé', 'Maîtrisé', 'Pinceau', 'Harmonie', 'Plénitude', 'Addictif', 'Violon', 'Méta', 'Pléthorique', 'Pensée', 'Lampe', 'Plaisir', 'Ingéniosité', 'Défis ', 'Incroyable', 'Travail', 'Plage', 'Refuge', 'Matin', 'En colère', 'Honnêteté', 'Fantastique', 'Captivant', 'Émerveillé', 'Transformation', 'Été', 'Math', 'Calme', 'Moto', 'Lion', 'Confort', 'Mémoires', 'Entreprise', 'Drop', 'Rêve', 'Move', 'Développement', 'Sagesse', 'Marié ', 'Marié', 'Amour', 'Mode', 'Art', 'Héroïque', 'Médical', 'Souvenir', 'Transcendental', 'Autonomie', 'Toit', 'Philosophie', 'Incroyable', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', 'Equality', 'Afternoon', 'Soda', 'Future', 'Paradise', 'Engineering ', 'Sublime', 'Repos', 'Beurre', 'Romance', 'Midi', 'Foudre', 'Généreux', 'Motivation', 'Volonté', 'Veuve', 'Ingénierie', 'Dawn', 'Wall', 'Vividity', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder', 'Heady', 'Promising', ' Éducation', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Détermination', 'Tonnerre', 'Énergie', 'Libellule', 'Incroyable', 'Solution', 'Foudre', 'Tigre' , 'Chat', 'Dévouement', 'Bateau', 'Exaltation', 'Rinçage', 'Passion', 'Écologie', 'Honnêteté', 'Émotion', 'Course', 'Technologie', 'Révélateur', ' Explore', 'Dazzle', 'Awaken', 'Wine', 'Tristness', 'History', 'Moon', 'Study', 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk' , 'Objectifs', 'Écharpe', 'Nager', 'Art', 'Vallée', 'Rivière', 'Nature', 'Hamburger', 'Histoire', 'Bien-être', 'Bénédiction', 'Fun', ' Exploration', 'Nature', 'Agitation', 'Mélodie', 'Philanthropie', 'Foulard', 'Revigorant', 'Chant', 'Tolérance', 'Drop', 'Regard', 'Découvrir', 'Sel' , 'Fun', 'Ville', 'Désolé', 'Ville', 'Sérendipité', 'Solidarité', 'Dimanche', 'Patrimoine', 'Football', 'Communauté', 'Magnifique', 'Arc-en-ciel', ' Encouragement', 'Discipline', 'Pépinière', 'Super', 'Désir', 'Dévouement', 'Musique', 'Utile', 'Santé', 'Porte', 'Affaires', 'Fenêtre', 'Sensibilité' , 'Train', 'Stabilité', 'Girafe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', ' Exaltation', 'Picturesque', 'Metropolis', 'Renewal', 'Shudder', 'Journey', 'Courage', 'Shocking', 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinsing' , 'Enchantement', 'Religion', 'Idyllique', 'Génération', 'Transcendant', 'Plume', 'Blé', 'Satisfaction', 'Affaires', 'Reptile', 'Fruit', 'Table',  'Organisation', 'Stars', 'Imprimante', 'Objectif', 'Motivation', 'Intrépidité', 'Équilibre', 'Calme', 'Anniversaire', 'Divorcé', 'Briller', 'Collaboration', 'Vert' , 'Dessert', 'Mélancolie', 'Photographie', 'Rire', 'Arôme', 'Fruit', 'Détente', 'Rosée', 'Vigueur', 'Générosité', 'Sourire', 'Automne', ' Impulsion', 'Charme', 'Enchanteur', 'Salé', 'Lucidité', 'Bleu', 'Enthousiasme', 'Beauté', 'Croissance', 'Sucre', 'Huile', 'Arc-en-ciel', 'Voyage' , 'Hamster', 'Surprise', 'Aventurier', 'Café', 'Surprenant', 'Curiosité', 'Fil', 'Poisson', 'Remarquable', 'Comprendre', 'Beurre', 'Tôt le matin', 'Étudiant', 'Printemps', 'Lac', 'Thérapie', 'Compétence', 'Grâce', 'Inégalé', 'Objectif', 'Baiser', 'Félin', 'Célibataire', 'Paix', 'Technicien ' , ' Poire ', ' Danse ', ' Colibri ', ' Avion ', ' Lac ', ' Enivrant ', ' Euphorique ', ' Excitant ', ' Fête ', ' Soleil ', ' Pantalon ', ' Sauter ', 'Bateau', 'Céramique', 'Interdépendance', 'Jeu', 'Eloquence', 'Stimulé', 'Essence', 'Salé', 'Confiance', 'Avoine', 'Ethique', 'Initiative', 'Banane ' , 'Nuage', 'Lush', 'Ecrire', 'Rencontre', 'Nourriture', 'Souhait', 'Noble', 'Spiritualité', 'Coopération', 'Harmonie', 'Poivre', 'Améliorer', 'Sublime', 'Éblouissant', 'Tradition', 'Souplesse', 'Univers', 'Girafe', 'Street', 'Diversity', 'Acting', 'Sensitive', 'Technical', 'Compassion', 'Spectacular ' , 'Riz', 'Oiseau', 'Cahier', 'Authentique', 'Silence', 'Fromage', 'T-shirt', 'Aube', 'Abondance', 'Compagnie', 'Défi', 'Astonante ', 'Impression', 'Institut', 'Sunset', 'Réussite', 'Tablette', 'Tempête', 'Entrepreneuriat', 'Tonnerre', 'Excentricité', 'Village', 'Sentiments', 'Électrifié',  'Fascinant ', ' Gratitude ', ' Cannelle ', ' Victoire ', ' Loyauté ', ' Vélo ', ' Maïs ', ' Succès ', ' Émotion ', ' Éducation ', ' Cascade ', ' Liberté ', ' Dentisterie ' , 'Intégrité', 'Canapé', 'Recherche', 'Fromage', 'Illumination', 'Générosité', 'Passion', 'Terre', 'Poésie', 'Sacrifice', 'Résilience', 'Merveilleusement', 'Énergétique' , 'Fenêtre']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Mot:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Devinez une lettre: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("C'est Correct!")
                    else:
                        intentos_restantes -= 1
                        print("Incorrect. Ils te donnent", intentos_restantes, "tentatives.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gagné! Vous avez deviné le mot :", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Tu as perdu! Le mot était :", palabra)

            print("joueur 1:")
            jugar_ahorcado()
            print("joueur 2:")
            jugar_ahorcado()


    if Multiplayer == 1:
        b=int(input("Veuillez sélectionner une difficulté:\n1.facile\n2.moyen\n3.difficile" ))
        if b == 1:

            lista = ['Compagnie', 'Biscuit', 'Câlin', 'Fidélité', 'Enrichissant', 'Automne', 'Ambition', 'Lumineux', 'Immobilité', 'Science', 'Rouge', 'Crayon', 'Cannelle ', 'Air', 'Amour', 'Autoroute', 'Patience', 'Solitude', 'Stratégie', 'Percée', 'Mode', 'Croissance', 'Ténacité', 'Excité', 'Littérature', 'Fête ', ' Espoir ', ' Inspirant ', ' Innovation ', ' Créativité ', ' Électrifiant ', ' Émerveillement ', ' Viande ', ' Horloge ', ' Silence ', ' Cap ', ' Neige ', ' Arc ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystère', 'Lunettes', 'Communication', 'Révélation', 'Acclamé', 'Larmes', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery ' , 'Style', 'Enchanteur', 'Sport', 'Littérature', 'Soin', 'Sérénité', 'Chien', 'Rafraîchissant', 'Merveille', 'Bureau', 'Détente', 'Style' , 'Vitalité', 'Conservation', 'Dignité', 'Rédemption', 'Nage', 'Repos', 'Excitant', 'Carrière', 'Avoine', 'Réussite', 'Applaudis', 'Temps', ' Yaourt', 'Océan', 'Cinéma', 'Village', 'Satisfaction', 'Café', 'Guitare', 'Eau', 'Craie', 'Responsabilité', 'Prestige', 'Plaisir', 'Pleurer ', 'Optimisme', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Stylo', 'Bénévolat', 'Espoir', 'Intrigant', 'Éclairant', 'Édifiant', 'Impressionnisme', 'Mardi', 'Architecture', 'Progrès', 'Stars', 'Communauté', 'Momentous ', 'Splendide', 'Colline', 'Environnement', 'Rafraîchissement', 'Crépuscule', 'Innocence', 'Maïs', 'Courage', 'Surpris', 'Exercice', 'Attendre', 'Photographier', 'Réalité', 'Nice', 'Enchantement', 'Crépuscule', 'Désert', 'Impressionné', 'Triste', 'Huile', 'Euphoria', 'Peinture', 'Bien-être', 'Village', 'Glow ' , 'Réflexion', 'Danse', 'Plume', 'Dévouement', 'Plaisir', 'Rire', 'Tomber amoureux', 'Gâteau', 'Sport', 'Réinvention', 'Cacao', 'Gastronomie ', 'Symétrie', 'Fraternité', 'Ingénieur', 'Épanouissant', 'Cacao', 'Aspiration', 'Authenticité', 'Humilité', 'Intrigue', 'Plaisir', 'Conscience', 'Exaltant', 'Avocat', 'Argent', 'Yaourt', 'Conduite', 'Ordinateur', 'Jus', 'Feu', 'Recul', 'Fascination', 'Planète', 'Bonheur', 'Chat', 'Grandeur ', 'Éléphant', 'Doux', 'Lapin', 'Unique', 'Amer', 'Eau', 'Livre', 'Hiver', 'Travail', 'Attractif', 'Optimisme', 'Sculpture', 'Gastronomie', 'Belle', 'Lunettes', 'Football', 'Prodige', 'Expérience', 'Inspirez-vous', 'Mer', 'Mystique', 'Nature', 'Ecrire', 'Fantaisie', ' Marche ', ' Joie ', ' Univers ', ' Te ', ' Expression ', ' Rire ', ' Spiritualité ', ' Rajeunissement ', ' Rivière ', ' Bonheur ', ' Banane ', ' Yoga ', ' Émotionnel' , 'Opportunité' , 'Accueil', 'Stylo', 'Patience', 'Route', 'Joie', 'Confiance', 'Attraction', 'Rêver', 'Génial', 'Anniversaire', 'Cauchemar', ' Émerveillement', 'Nuages', 'Magnifique', 'Équilibre', 'Collaboration', 'Espace', 'Autonomisation', 'Design', 'Étude', 'Émotionnellement', 'Résilience', 'Basketball', 'Éclatant' , 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Moto', 'Beer', 'Chaussures', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passetime', 'Colorful', 'Voyage', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', ' Analyse', 'Exquis', 'Héritage', 'Télévision', 'Pantalon', 'Cadeau', 'Récompense', 'Désert', 'Noblesse', 'Connexion', 'Histoire', 'École', 'Maturité' , 'Pluie' , 'Lampe', 'Spontanéité', 'Claro', 'Constellation', 'Souris', 'Culture', 'Frais', 'Inspiration', 'Sun Guitar', 'Livre', 'Diversité', 'Risque', 'orange', 'Université', 'Détermination', 'Festival', 'Gentillesse', 'Brise', 'Hamster', 'Autoroute', 'Merveille', 'Abeille', 'Espoir', 'Connaissance ', 'Hill', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Lapin', 'Lundi', 'Extérieur', 'Route', 'Shining', 'Saxophone', 'Éthique', 'Tennis', 'Camion', 'Apprentissage', 'Sincérité', 'Durabilité', 'Gentillesse ', ' Jungle ', ' Luminosité ', ' Focus ', ' Chien ', ' Université ', ' Nourrir ', ' Découverte ', ' Jardin ', ' Compétence ', ' Train ', ' Éclairage ', 'Planning', 'Arena', 'Tennis', 'Lush', 'Surmonter', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendance', 'Divorced', 'Harmony', ' Empathie', 'Respect', 'Horloge', 'Ami', 'Fil', 'Yaourt', 'Ecole', 'Sérendipité', 'Avion', 'Jeu', 'Rire', 'Plénitude', 'Sculpture' , 'Hôpital', 'Sourire', 'Captivant', 'Intuition', 'Expérience', 'Splendeur', 'Océan', 'Prospérité', 'Conscience', 'Tequila', 'Anniversaire', 'Séduction', ' Leadership', 'Excellent', 'Courtois', 'Renouveau', 'Valley', 'Matin', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change' , 'Basketball', 'Professionnalisme', 'Inspiration', 'Passionnant', 'Merveilleux', 'Succès', 'Solidarité', 'Renaissance', 'Légumes', 'Robe', 'Coquillages', 'Mer', ' Docteur', 'Foi', 'T-shirt', 'Créativité', 'Amer', 'Célébration', 'Vitalité', 'Fleurs', 'Nuit', 'Rire', 'Reconnaissance', 'Aventure', ' Poivre', 'Printemps', 'Exaltant', 'Plafond', 'Sucre', 'Robe', 'Calme', 'Liberté', 'Tranquillité', 'Conscience', 'Anniversaire', 'Moments', 'Heureux' , ' Galaxie ', ' Authenticité ', ' Méditation ', ' Compétence ', ' Arbre ', ' Nutrition ', ' Glorieux ', ' Science ', ' Altitude ', ' Air ', ' Justice ', ' Efficacité ', ' Charme', 'Feu', 'Tradition', 'Oasis', 'Surprise', 'Enseignement', 'Joie', 'Rêve', 'Débordant', 'Aventure', 'Télévision', 'Chaussures', 'Chocolat' , 'Chien', 'Inspiration', 'Mariage', 'Colère', 'Passionné', 'Médecine', 'Pinceau', 'Clarté', 'Entourage', 'Pizza', 'Lune', 'Justice', ' Autonomisation', 'Chaise', 'Débordement', 'Vent', 'Richesse', 'Souvenirs', 'Enthousiasme', 'Technologie', 'Boutique', 'Galaxy', 'Magie', 'Charmant', 'Pâtes' , 'Exubérance', 'Équité', 'Cinéma', 'Persévérance', 'Organisation', 'Persévérance', 'Carrière', 'Incroyable', 'Rêve', 'Originalité', 'Extraordinaire', 'Transcendantale', ' Bureau', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity' , ' Fantasy', 'Emancipator', 'Watchful', 'Ice Cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-estime ', 'Joie' , 'Thé', 'Cahier', 'Peinture', 'Riz', 'Enrichissement', 'Motivateur', 'Inclusion', 'Pomme', 'Mindfulness', 'Respect', 'Exploration',  'Voisin ', ' Richesse ', ' Transformation ', ' Peinture ', ' Joie ', ' Chaos ', ' Terre ', ' Papillon ', ' Émerveillement ', ' Exotique ', ' Durabilité ', ' Passionné ', ' Vanille ', 'Fascinant' , 'Acide', 'Tigre', 'Tristesse', 'Vision', 'Foudre', 'Satellite', 'Honnête', 'Cellulaire', 'Végétal', 'Revigorant', 'Whisky', 'Théâtre', 'Paysage', 'Sensation', 'Forteresse', 'Rue', 'Porte', 'Viande', 'Mystère', 'Théâtre', 'Pâtes', 'Samedi', 'Fiançailles', 'Triumph ', 'Fascinant' , 'Courage', 'Blé', 'Gentillesse', 'Paix', 'Durabilité', 'Persistance', 'Ville', 'Architecture', 'Fête', 'Rêveur', 'Infirmier', 'Fortitude', 'Soupir', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Gai', 'Revitalizing', 'Friendly ', 'Excitant' , 'Avenue', 'Beauty', 'Yellow', 'Challenge', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Famille', 'Vibrant', 'Environnement', 'Apprentissage', 'Avocat', 'Divertissement', 'Valeurs', 'Boutique', 'Acceptation', 'Famille', 'Connaissance', 'Force', 'Esprit ', 'Brave', 'Révolution', 'Care', 'Explorateur', 'Plage', 'Canapé', 'Amitié', 'Bus', 'Poisson', 'Danse', 'Enchantement', 'Montagne', 'Forêt', 'Survie', 'Incomparable', 'Hôpital', 'Jardin', 'Légende', 'Avenue', 'Sublimation', 'Salade', 'Destiny', 'Gentil', 'Doux', 'Eternité ', 'Chapeau', 'Éternel', 'Amoureux', 'Peinture', 'Coeur', 'Constance', 'Chaise', 'Maître', 'Automobile', 'Metropolis', 'Vibrant', 'Thé', 'Maîtrisé', 'Pinceau', 'Harmonie', 'Plénitude', 'Addictif', 'Violon', 'Méta', 'Pléthorique', 'Pensée', 'Lampe', 'Plaisir', 'Ingéniosité', 'Défis ', 'Incroyable', 'Travail', 'Plage', 'Refuge', 'Matin', 'En colère', 'Honnêteté', 'Fantastique', 'Captivant', 'Émerveillé', 'Transformation', 'Été', 'Math', 'Calme', 'Moto', 'Lion', 'Confort', 'Mémoires', 'Entreprise', 'Drop', 'Rêve', 'Move', 'Développement', 'Sagesse', 'Marié ', 'Marié', 'Amour', 'Mode', 'Art', 'Héroïque', 'Médical', 'Souvenir', 'Transcendental', 'Autonomie', 'Toit', 'Philosophie', 'Incroyable', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', 'Equality', 'Afternoon', 'Soda', 'Future', 'Paradise', 'Engineering ', 'Sublime', 'Repos', 'Beurre', 'Romance', 'Midi', 'Foudre', 'Généreux', 'Motivation', 'Volonté', 'Veuve', 'Ingénierie', 'Dawn', 'Wall', 'Vividity', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder', 'Heady', 'Promising', ' Éducation', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Détermination', 'Tonnerre', 'Énergie', 'Libellule', 'Incroyable', 'Solution', 'Foudre', 'Tigre' , 'Chat', 'Dévouement', 'Bateau', 'Exaltation', 'Rinçage', 'Passion', 'Écologie', 'Honnêteté', 'Émotion', 'Course', 'Technologie', 'Révélateur', ' Explore', 'Dazzle', 'Awaken', 'Wine', 'Tristness', 'History', 'Moon', 'Study', 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk' , 'Objectifs', 'Écharpe', 'Nager', 'Art', 'Vallée', 'Rivière', 'Nature', 'Hamburger', 'Histoire', 'Bien-être', 'Bénédiction', 'Fun', ' Exploration', 'Nature', 'Agitation', 'Mélodie', 'Philanthropie', 'Foulard', 'Revigorant', 'Chant', 'Tolérance', 'Drop', 'Regard', 'Découvrir', 'Sel' , 'Fun', 'Ville', 'Désolé', 'Ville', 'Sérendipité', 'Solidarité', 'Dimanche', 'Patrimoine', 'Football', 'Communauté', 'Magnifique', 'Arc-en-ciel', ' Encouragement', 'Discipline', 'Pépinière', 'Super', 'Désir', 'Dévouement', 'Musique', 'Utile', 'Santé', 'Porte', 'Affaires', 'Fenêtre', 'Sensibilité' , 'Train', 'Stabilité', 'Girafe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', ' Exaltation', 'Picturesque', 'Metropolis', 'Renewal', 'Shudder', 'Journey', 'Courage', 'Shocking', 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinsing' , 'Enchantement', 'Religion', 'Idyllique', 'Génération', 'Transcendant', 'Plume', 'Blé', 'Satisfaction', 'Affaires', 'Reptile', 'Fruit', 'Table',  'Organisation', 'Stars', 'Imprimante', 'Objectif', 'Motivation', 'Intrépidité', 'Équilibre', 'Calme', 'Anniversaire', 'Divorcé', 'Briller', 'Collaboration', 'Vert' , 'Dessert', 'Mélancolie', 'Photographie', 'Rire', 'Arôme', 'Fruit', 'Détente', 'Rosée', 'Vigueur', 'Générosité', 'Sourire', 'Automne', ' Impulsion', 'Charme', 'Enchanteur', 'Salé', 'Lucidité', 'Bleu', 'Enthousiasme', 'Beauté', 'Croissance', 'Sucre', 'Huile', 'Arc-en-ciel', 'Voyage' , 'Hamster', 'Surprise', 'Aventurier', 'Café', 'Surprenant', 'Curiosité', 'Fil', 'Poisson', 'Remarquable', 'Comprendre', 'Beurre', 'Tôt le matin', 'Étudiant', 'Printemps', 'Lac', 'Thérapie', 'Compétence', 'Grâce', 'Inégalé', 'Objectif', 'Baiser', 'Félin', 'Célibataire', 'Paix', 'Technicien ' , ' Poire ', ' Danse ', ' Colibri ', ' Avion ', ' Lac ', ' Enivrant ', ' Euphorique ', ' Excitant ', ' Fête ', ' Soleil ', ' Pantalon ', ' Sauter ', 'Bateau', 'Céramique', 'Interdépendance', 'Jeu', 'Eloquence', 'Stimulé', 'Essence', 'Salé', 'Confiance', 'Avoine', 'Ethique', 'Initiative', 'Banane ' , 'Nuage', 'Lush', 'Ecrire', 'Rencontre', 'Nourriture', 'Souhait', 'Noble', 'Spiritualité', 'Coopération', 'Harmonie', 'Poivre', 'Améliorer', 'Sublime', 'Éblouissant', 'Tradition', 'Souplesse', 'Univers', 'Girafe', 'Street', 'Diversity', 'Acting', 'Sensitive', 'Technical', 'Compassion', 'Spectacular ' , 'Riz', 'Oiseau', 'Cahier', 'Authentique', 'Silence', 'Fromage', 'T-shirt', 'Aube', 'Abondance', 'Compagnie', 'Défi', 'Astonante ', 'Impression', 'Institut', 'Sunset', 'Réussite', 'Tablette', 'Tempête', 'Entrepreneuriat', 'Tonnerre', 'Excentricité', 'Village', 'Sentiments', 'Électrifié',  'Fascinant ', ' Gratitude ', ' Cannelle ', ' Victoire ', ' Loyauté ', ' Vélo ', ' Maïs ', ' Succès ', ' Émotion ', ' Éducation ', ' Cascade ', ' Liberté ', ' Dentisterie ' , 'Intégrité', 'Canapé', 'Recherche', 'Fromage', 'Illumination', 'Générosité', 'Passion', 'Terre', 'Poésie', 'Sacrifice', 'Résilience', 'Merveilleusement', 'Énergétique' , 'Fenêtre']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Mot:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Devinez une lettre : ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("C'est Correct!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrect. Ils te donnent", intentos_restantes, "tentatives.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gagné! Vous avez deviné le mot:", palabra)
                        break

                if intentos_restantes == 0:
                        print("Tu as perdu! Le mot était:", palabra)


            print("joueur 1:")
            jugar_ahorcado()

            
        elif b == 2:


            lista = ['Compagnie', 'Biscuit', 'Câlin', 'Fidélité', 'Enrichissant', 'Automne', 'Ambition', 'Lumineux', 'Immobilité', 'Science', 'Rouge', 'Crayon', 'Cannelle ', 'Air', 'Amour', 'Autoroute', 'Patience', 'Solitude', 'Stratégie', 'Percée', 'Mode', 'Croissance', 'Ténacité', 'Excité', 'Littérature', 'Fête ', ' Espoir ', ' Inspirant ', ' Innovation ', ' Créativité ', ' Électrifiant ', ' Émerveillement ', ' Viande ', ' Horloge ', ' Silence ', ' Cap ', ' Neige ', ' Arc ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystère', 'Lunettes', 'Communication', 'Révélation', 'Acclamé', 'Larmes', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery ' , 'Style', 'Enchanteur', 'Sport', 'Littérature', 'Soin', 'Sérénité', 'Chien', 'Rafraîchissant', 'Merveille', 'Bureau', 'Détente', 'Style' , 'Vitalité', 'Conservation', 'Dignité', 'Rédemption', 'Nage', 'Repos', 'Excitant', 'Carrière', 'Avoine', 'Réussite', 'Applaudis', 'Temps', ' Yaourt', 'Océan', 'Cinéma', 'Village', 'Satisfaction', 'Café', 'Guitare', 'Eau', 'Craie', 'Responsabilité', 'Prestige', 'Plaisir', 'Pleurer ', 'Optimisme', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Stylo', 'Bénévolat', 'Espoir', 'Intrigant', 'Éclairant', 'Édifiant', 'Impressionnisme', 'Mardi', 'Architecture', 'Progrès', 'Stars', 'Communauté', 'Momentous ', 'Splendide', 'Colline', 'Environnement', 'Rafraîchissement', 'Crépuscule', 'Innocence', 'Maïs', 'Courage', 'Surpris', 'Exercice', 'Attendre', 'Photographier', 'Réalité', 'Nice', 'Enchantement', 'Crépuscule', 'Désert', 'Impressionné', 'Triste', 'Huile', 'Euphoria', 'Peinture', 'Bien-être', 'Village', 'Glow ' , 'Réflexion', 'Danse', 'Plume', 'Dévouement', 'Plaisir', 'Rire', 'Tomber amoureux', 'Gâteau', 'Sport', 'Réinvention', 'Cacao', 'Gastronomie ', 'Symétrie', 'Fraternité', 'Ingénieur', 'Épanouissant', 'Cacao', 'Aspiration', 'Authenticité', 'Humilité', 'Intrigue', 'Plaisir', 'Conscience', 'Exaltant', 'Avocat', 'Argent', 'Yaourt', 'Conduite', 'Ordinateur', 'Jus', 'Feu', 'Recul', 'Fascination', 'Planète', 'Bonheur', 'Chat', 'Grandeur ', 'Éléphant', 'Doux', 'Lapin', 'Unique', 'Amer', 'Eau', 'Livre', 'Hiver', 'Travail', 'Attractif', 'Optimisme', 'Sculpture', 'Gastronomie', 'Belle', 'Lunettes', 'Football', 'Prodige', 'Expérience', 'Inspirez-vous', 'Mer', 'Mystique', 'Nature', 'Ecrire', 'Fantaisie', ' Marche ', ' Joie ', ' Univers ', ' Te ', ' Expression ', ' Rire ', ' Spiritualité ', ' Rajeunissement ', ' Rivière ', ' Bonheur ', ' Banane ', ' Yoga ', ' Émotionnel' , 'Opportunité' , 'Accueil', 'Stylo', 'Patience', 'Route', 'Joie', 'Confiance', 'Attraction', 'Rêver', 'Génial', 'Anniversaire', 'Cauchemar', ' Émerveillement', 'Nuages', 'Magnifique', 'Équilibre', 'Collaboration', 'Espace', 'Autonomisation', 'Design', 'Étude', 'Émotionnellement', 'Résilience', 'Basketball', 'Éclatant' , 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Moto', 'Beer', 'Chaussures', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passetime', 'Colorful', 'Voyage', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', ' Analyse', 'Exquis', 'Héritage', 'Télévision', 'Pantalon', 'Cadeau', 'Récompense', 'Désert', 'Noblesse', 'Connexion', 'Histoire', 'École', 'Maturité' , 'Pluie' , 'Lampe', 'Spontanéité', 'Claro', 'Constellation', 'Souris', 'Culture', 'Frais', 'Inspiration', 'Sun Guitar', 'Livre', 'Diversité', 'Risque', 'orange', 'Université', 'Détermination', 'Festival', 'Gentillesse', 'Brise', 'Hamster', 'Autoroute', 'Merveille', 'Abeille', 'Espoir', 'Connaissance ', 'Hill', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Lapin', 'Lundi', 'Extérieur', 'Route', 'Shining', 'Saxophone', 'Éthique', 'Tennis', 'Camion', 'Apprentissage', 'Sincérité', 'Durabilité', 'Gentillesse ', ' Jungle ', ' Luminosité ', ' Focus ', ' Chien ', ' Université ', ' Nourrir ', ' Découverte ', ' Jardin ', ' Compétence ', ' Train ', ' Éclairage ', 'Planning', 'Arena', 'Tennis', 'Lush', 'Surmonter', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendance', 'Divorced', 'Harmony', ' Empathie', 'Respect', 'Horloge', 'Ami', 'Fil', 'Yaourt', 'Ecole', 'Sérendipité', 'Avion', 'Jeu', 'Rire', 'Plénitude', 'Sculpture' , 'Hôpital', 'Sourire', 'Captivant', 'Intuition', 'Expérience', 'Splendeur', 'Océan', 'Prospérité', 'Conscience', 'Tequila', 'Anniversaire', 'Séduction', ' Leadership', 'Excellent', 'Courtois', 'Renouveau', 'Valley', 'Matin', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change' , 'Basketball', 'Professionnalisme', 'Inspiration', 'Passionnant', 'Merveilleux', 'Succès', 'Solidarité', 'Renaissance', 'Légumes', 'Robe', 'Coquillages', 'Mer', ' Docteur', 'Foi', 'T-shirt', 'Créativité', 'Amer', 'Célébration', 'Vitalité', 'Fleurs', 'Nuit', 'Rire', 'Reconnaissance', 'Aventure', ' Poivre', 'Printemps', 'Exaltant', 'Plafond', 'Sucre', 'Robe', 'Calme', 'Liberté', 'Tranquillité', 'Conscience', 'Anniversaire', 'Moments', 'Heureux' , ' Galaxie ', ' Authenticité ', ' Méditation ', ' Compétence ', ' Arbre ', ' Nutrition ', ' Glorieux ', ' Science ', ' Altitude ', ' Air ', ' Justice ', ' Efficacité ', ' Charme', 'Feu', 'Tradition', 'Oasis', 'Surprise', 'Enseignement', 'Joie', 'Rêve', 'Débordant', 'Aventure', 'Télévision', 'Chaussures', 'Chocolat' , 'Chien', 'Inspiration', 'Mariage', 'Colère', 'Passionné', 'Médecine', 'Pinceau', 'Clarté', 'Entourage', 'Pizza', 'Lune', 'Justice', ' Autonomisation', 'Chaise', 'Débordement', 'Vent', 'Richesse', 'Souvenirs', 'Enthousiasme', 'Technologie', 'Boutique', 'Galaxy', 'Magie', 'Charmant', 'Pâtes' , 'Exubérance', 'Équité', 'Cinéma', 'Persévérance', 'Organisation', 'Persévérance', 'Carrière', 'Incroyable', 'Rêve', 'Originalité', 'Extraordinaire', 'Transcendantale', ' Bureau', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity' , ' Fantasy', 'Emancipator', 'Watchful', 'Ice Cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-estime ', 'Joie' , 'Thé', 'Cahier', 'Peinture', 'Riz', 'Enrichissement', 'Motivateur', 'Inclusion', 'Pomme', 'Mindfulness', 'Respect', 'Exploration',  'Voisin ', ' Richesse ', ' Transformation ', ' Peinture ', ' Joie ', ' Chaos ', ' Terre ', ' Papillon ', ' Émerveillement ', ' Exotique ', ' Durabilité ', ' Passionné ', ' Vanille ', 'Fascinant' , 'Acide', 'Tigre', 'Tristesse', 'Vision', 'Foudre', 'Satellite', 'Honnête', 'Cellulaire', 'Végétal', 'Revigorant', 'Whisky', 'Théâtre', 'Paysage', 'Sensation', 'Forteresse', 'Rue', 'Porte', 'Viande', 'Mystère', 'Théâtre', 'Pâtes', 'Samedi', 'Fiançailles', 'Triumph ', 'Fascinant' , 'Courage', 'Blé', 'Gentillesse', 'Paix', 'Durabilité', 'Persistance', 'Ville', 'Architecture', 'Fête', 'Rêveur', 'Infirmier', 'Fortitude', 'Soupir', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Gai', 'Revitalizing', 'Friendly ', 'Excitant' , 'Avenue', 'Beauty', 'Yellow', 'Challenge', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Famille', 'Vibrant', 'Environnement', 'Apprentissage', 'Avocat', 'Divertissement', 'Valeurs', 'Boutique', 'Acceptation', 'Famille', 'Connaissance', 'Force', 'Esprit ', 'Brave', 'Révolution', 'Care', 'Explorateur', 'Plage', 'Canapé', 'Amitié', 'Bus', 'Poisson', 'Danse', 'Enchantement', 'Montagne', 'Forêt', 'Survie', 'Incomparable', 'Hôpital', 'Jardin', 'Légende', 'Avenue', 'Sublimation', 'Salade', 'Destiny', 'Gentil', 'Doux', 'Eternité ', 'Chapeau', 'Éternel', 'Amoureux', 'Peinture', 'Coeur', 'Constance', 'Chaise', 'Maître', 'Automobile', 'Metropolis', 'Vibrant', 'Thé', 'Maîtrisé', 'Pinceau', 'Harmonie', 'Plénitude', 'Addictif', 'Violon', 'Méta', 'Pléthorique', 'Pensée', 'Lampe', 'Plaisir', 'Ingéniosité', 'Défis ', 'Incroyable', 'Travail', 'Plage', 'Refuge', 'Matin', 'En colère', 'Honnêteté', 'Fantastique', 'Captivant', 'Émerveillé', 'Transformation', 'Été', 'Math', 'Calme', 'Moto', 'Lion', 'Confort', 'Mémoires', 'Entreprise', 'Drop', 'Rêve', 'Move', 'Développement', 'Sagesse', 'Marié ', 'Marié', 'Amour', 'Mode', 'Art', 'Héroïque', 'Médical', 'Souvenir', 'Transcendental', 'Autonomie', 'Toit', 'Philosophie', 'Incroyable', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', 'Equality', 'Afternoon', 'Soda', 'Future', 'Paradise', 'Engineering ', 'Sublime', 'Repos', 'Beurre', 'Romance', 'Midi', 'Foudre', 'Généreux', 'Motivation', 'Volonté', 'Veuve', 'Ingénierie', 'Dawn', 'Wall', 'Vividity', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder', 'Heady', 'Promising', ' Éducation', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Détermination', 'Tonnerre', 'Énergie', 'Libellule', 'Incroyable', 'Solution', 'Foudre', 'Tigre' , 'Chat', 'Dévouement', 'Bateau', 'Exaltation', 'Rinçage', 'Passion', 'Écologie', 'Honnêteté', 'Émotion', 'Course', 'Technologie', 'Révélateur', ' Explore', 'Dazzle', 'Awaken', 'Wine', 'Tristness', 'History', 'Moon', 'Study', 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk' , 'Objectifs', 'Écharpe', 'Nager', 'Art', 'Vallée', 'Rivière', 'Nature', 'Hamburger', 'Histoire', 'Bien-être', 'Bénédiction', 'Fun', ' Exploration', 'Nature', 'Agitation', 'Mélodie', 'Philanthropie', 'Foulard', 'Revigorant', 'Chant', 'Tolérance', 'Drop', 'Regard', 'Découvrir', 'Sel' , 'Fun', 'Ville', 'Désolé', 'Ville', 'Sérendipité', 'Solidarité', 'Dimanche', 'Patrimoine', 'Football', 'Communauté', 'Magnifique', 'Arc-en-ciel', ' Encouragement', 'Discipline', 'Pépinière', 'Super', 'Désir', 'Dévouement', 'Musique', 'Utile', 'Santé', 'Porte', 'Affaires', 'Fenêtre', 'Sensibilité' , 'Train', 'Stabilité', 'Girafe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', ' Exaltation', 'Picturesque', 'Metropolis', 'Renewal', 'Shudder', 'Journey', 'Courage', 'Shocking', 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinsing' , 'Enchantement', 'Religion', 'Idyllique', 'Génération', 'Transcendant', 'Plume', 'Blé', 'Satisfaction', 'Affaires', 'Reptile', 'Fruit', 'Table',  'Organisation', 'Stars', 'Imprimante', 'Objectif', 'Motivation', 'Intrépidité', 'Équilibre', 'Calme', 'Anniversaire', 'Divorcé', 'Briller', 'Collaboration', 'Vert' , 'Dessert', 'Mélancolie', 'Photographie', 'Rire', 'Arôme', 'Fruit', 'Détente', 'Rosée', 'Vigueur', 'Générosité', 'Sourire', 'Automne', ' Impulsion', 'Charme', 'Enchanteur', 'Salé', 'Lucidité', 'Bleu', 'Enthousiasme', 'Beauté', 'Croissance', 'Sucre', 'Huile', 'Arc-en-ciel', 'Voyage' , 'Hamster', 'Surprise', 'Aventurier', 'Café', 'Surprenant', 'Curiosité', 'Fil', 'Poisson', 'Remarquable', 'Comprendre', 'Beurre', 'Tôt le matin', 'Étudiant', 'Printemps', 'Lac', 'Thérapie', 'Compétence', 'Grâce', 'Inégalé', 'Objectif', 'Baiser', 'Félin', 'Célibataire', 'Paix', 'Technicien ' , ' Poire ', ' Danse ', ' Colibri ', ' Avion ', ' Lac ', ' Enivrant ', ' Euphorique ', ' Excitant ', ' Fête ', ' Soleil ', ' Pantalon ', ' Sauter ', 'Bateau', 'Céramique', 'Interdépendance', 'Jeu', 'Eloquence', 'Stimulé', 'Essence', 'Salé', 'Confiance', 'Avoine', 'Ethique', 'Initiative', 'Banane ' , 'Nuage', 'Lush', 'Ecrire', 'Rencontre', 'Nourriture', 'Souhait', 'Noble', 'Spiritualité', 'Coopération', 'Harmonie', 'Poivre', 'Améliorer', 'Sublime', 'Éblouissant', 'Tradition', 'Souplesse', 'Univers', 'Girafe', 'Street', 'Diversity', 'Acting', 'Sensitive', 'Technical', 'Compassion', 'Spectacular ' , 'Riz', 'Oiseau', 'Cahier', 'Authentique', 'Silence', 'Fromage', 'T-shirt', 'Aube', 'Abondance', 'Compagnie', 'Défi', 'Astonante ', 'Impression', 'Institut', 'Sunset', 'Réussite', 'Tablette', 'Tempête', 'Entrepreneuriat', 'Tonnerre', 'Excentricité', 'Village', 'Sentiments', 'Électrifié',  'Fascinant ', ' Gratitude ', ' Cannelle ', ' Victoire ', ' Loyauté ', ' Vélo ', ' Maïs ', ' Succès ', ' Émotion ', ' Éducation ', ' Cascade ', ' Liberté ', ' Dentisterie ' , 'Intégrité', 'Canapé', 'Recherche', 'Fromage', 'Illumination', 'Générosité', 'Passion', 'Terre', 'Poésie', 'Sacrifice', 'Résilience', 'Merveilleusement', 'Énergétique' , 'Fenêtre']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Mot:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Devinez une lettre: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("C'est Correct!")

                    else:
                        intentos_restantes -= 1
                        print("Incorrect. Ils te donnent", intentos_restantes, "tentatives.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gagné! Vous avez deviné le mot:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Tu as perdu! Le mot était:", palabra)



            print("joueur 1:")
            jugar_ahorcado()



        elif b == 3:

            import random
            lista = ['Compagnie', 'Biscuit', 'Câlin', 'Fidélité', 'Enrichissant', 'Automne', 'Ambition', 'Lumineux', 'Immobilité', 'Science', 'Rouge', 'Crayon', 'Cannelle ', 'Air', 'Amour', 'Autoroute', 'Patience', 'Solitude', 'Stratégie', 'Percée', 'Mode', 'Croissance', 'Ténacité', 'Excité', 'Littérature', 'Fête ', ' Espoir ', ' Inspirant ', ' Innovation ', ' Créativité ', ' Électrifiant ', ' Émerveillement ', ' Viande ', ' Horloge ', ' Silence ', ' Cap ', ' Neige ', ' Arc ', 'Ability', 'Sleep', 'Orange', 'Wonder', 'Friendliness', 'Change', 'Computer', 'Music', 'Grape', 'Epiphany', 'Running', 'Thankfulness', 'Leadership', 'Mystère', 'Lunettes', 'Communication', 'Révélation', 'Acclamé', 'Larmes', 'Groundbreaker', 'Whisper', 'Snow', 'Horizon', 'Scoreboard', 'Discovery ' , 'Style', 'Enchanteur', 'Sport', 'Littérature', 'Soin', 'Sérénité', 'Chien', 'Rafraîchissant', 'Merveille', 'Bureau', 'Détente', 'Style' , 'Vitalité', 'Conservation', 'Dignité', 'Rédemption', 'Nage', 'Repos', 'Excitant', 'Carrière', 'Avoine', 'Réussite', 'Applaudis', 'Temps', ' Yaourt', 'Océan', 'Cinéma', 'Village', 'Satisfaction', 'Café', 'Guitare', 'Eau', 'Craie', 'Responsabilité', 'Prestige', 'Plaisir', 'Pleurer ', 'Optimisme', 'Team', 'Equality', 'Vanilla', 'Dance', 'Bus', 'Hobby', 'Imagination', 'Irresistible', 'Glow', 'Adaptability', 'Appreciation', 'Stylo', 'Bénévolat', 'Espoir', 'Intrigant', 'Éclairant', 'Édifiant', 'Impressionnisme', 'Mardi', 'Architecture', 'Progrès', 'Stars', 'Communauté', 'Momentous ', 'Splendide', 'Colline', 'Environnement', 'Rafraîchissement', 'Crépuscule', 'Innocence', 'Maïs', 'Courage', 'Surpris', 'Exercice', 'Attendre', 'Photographier', 'Réalité', 'Nice', 'Enchantement', 'Crépuscule', 'Désert', 'Impressionné', 'Triste', 'Huile', 'Euphoria', 'Peinture', 'Bien-être', 'Village', 'Glow ' , 'Réflexion', 'Danse', 'Plume', 'Dévouement', 'Plaisir', 'Rire', 'Tomber amoureux', 'Gâteau', 'Sport', 'Réinvention', 'Cacao', 'Gastronomie ', 'Symétrie', 'Fraternité', 'Ingénieur', 'Épanouissant', 'Cacao', 'Aspiration', 'Authenticité', 'Humilité', 'Intrigue', 'Plaisir', 'Conscience', 'Exaltant', 'Avocat', 'Argent', 'Yaourt', 'Conduite', 'Ordinateur', 'Jus', 'Feu', 'Recul', 'Fascination', 'Planète', 'Bonheur', 'Chat', 'Grandeur ', 'Éléphant', 'Doux', 'Lapin', 'Unique', 'Amer', 'Eau', 'Livre', 'Hiver', 'Travail', 'Attractif', 'Optimisme', 'Sculpture', 'Gastronomie', 'Belle', 'Lunettes', 'Football', 'Prodige', 'Expérience', 'Inspirez-vous', 'Mer', 'Mystique', 'Nature', 'Ecrire', 'Fantaisie', ' Marche ', ' Joie ', ' Univers ', ' Te ', ' Expression ', ' Rire ', ' Spiritualité ', ' Rajeunissement ', ' Rivière ', ' Bonheur ', ' Banane ', ' Yoga ', ' Émotionnel' , 'Opportunité' , 'Accueil', 'Stylo', 'Patience', 'Route', 'Joie', 'Confiance', 'Attraction', 'Rêver', 'Génial', 'Anniversaire', 'Cauchemar', ' Émerveillement', 'Nuages', 'Magnifique', 'Équilibre', 'Collaboration', 'Espace', 'Autonomisation', 'Design', 'Étude', 'Émotionnellement', 'Résilience', 'Basketball', 'Éclatant' , 'Empathy' , 'Interiors', 'Stunning', 'Unforgettable', 'Admiration', 'Beautiful', 'Mountain', 'Realization', 'Acid', 'Write', 'Hug', 'Ceramic', ' Jump', 'Action', 'Sigh', 'Angry', 'Table', 'Hat', 'Moto', 'Beer', 'Chaussures', 'Truth', 'Excitingly', 'Star', 'Holiday' , 'Rhythm' , 'Sky', 'Passetime', 'Colorful', 'Voyage', 'Dew', 'Wonderful', 'Psychology', 'Sunrise', 'Gratitude', 'Challenge', 'Swimming', ' Analyse', 'Exquis', 'Héritage', 'Télévision', 'Pantalon', 'Cadeau', 'Récompense', 'Désert', 'Noblesse', 'Connexion', 'Histoire', 'École', 'Maturité' , 'Pluie' , 'Lampe', 'Spontanéité', 'Claro', 'Constellation', 'Souris', 'Culture', 'Frais', 'Inspiration', 'Sun Guitar', 'Livre', 'Diversité', 'Risque', 'orange', 'Université', 'Détermination', 'Festival', 'Gentillesse', 'Brise', 'Hamster', 'Autoroute', 'Merveille', 'Abeille', 'Espoir', 'Connaissance ', 'Hill', 'Hamster', 'Gentle', 'Energy', 'Radiant', 'Medicine', 'Swimming', 'Waterfall', 'Affectionate', 'Warm', 'Friendship', 'Telephone', 'Lapin', 'Lundi', 'Extérieur', 'Route', 'Shining', 'Saxophone', 'Éthique', 'Tennis', 'Camion', 'Apprentissage', 'Sincérité', 'Durabilité', 'Gentillesse ', ' Jungle ', ' Luminosité ', ' Focus ', ' Chien ', ' Université ', ' Nourrir ', ' Découverte ', ' Jardin ', ' Compétence ', ' Train ', ' Éclairage ', 'Planning', 'Arena', 'Tennis', 'Lush', 'Surmonter', 'Summer', 'Engineer', 'Forest', 'Storm', 'Transcendance', 'Divorced', 'Harmony', ' Empathie', 'Respect', 'Horloge', 'Ami', 'Fil', 'Yaourt', 'Ecole', 'Sérendipité', 'Avion', 'Jeu', 'Rire', 'Plénitude', 'Sculpture' , 'Hôpital', 'Sourire', 'Captivant', 'Intuition', 'Expérience', 'Splendeur', 'Océan', 'Prospérité', 'Conscience', 'Tequila', 'Anniversaire', 'Séduction', ' Leadership', 'Excellent', 'Courtois', 'Renouveau', 'Valley', 'Matin', 'Night', 'Winter', 'Charisma', 'Evolution', 'Flexibility', 'Energetic', 'Change' , 'Basketball', 'Professionnalisme', 'Inspiration', 'Passionnant', 'Merveilleux', 'Succès', 'Solidarité', 'Renaissance', 'Légumes', 'Robe', 'Coquillages', 'Mer', ' Docteur', 'Foi', 'T-shirt', 'Créativité', 'Amer', 'Célébration', 'Vitalité', 'Fleurs', 'Nuit', 'Rire', 'Reconnaissance', 'Aventure', ' Poivre', 'Printemps', 'Exaltant', 'Plafond', 'Sucre', 'Robe', 'Calme', 'Liberté', 'Tranquillité', 'Conscience', 'Anniversaire', 'Moments', 'Heureux' , ' Galaxie ', ' Authenticité ', ' Méditation ', ' Compétence ', ' Arbre ', ' Nutrition ', ' Glorieux ', ' Science ', ' Altitude ', ' Air ', ' Justice ', ' Efficacité ', ' Charme', 'Feu', 'Tradition', 'Oasis', 'Surprise', 'Enseignement', 'Joie', 'Rêve', 'Débordant', 'Aventure', 'Télévision', 'Chaussures', 'Chocolat' , 'Chien', 'Inspiration', 'Mariage', 'Colère', 'Passionné', 'Médecine', 'Pinceau', 'Clarté', 'Entourage', 'Pizza', 'Lune', 'Justice', ' Autonomisation', 'Chaise', 'Débordement', 'Vent', 'Richesse', 'Souvenirs', 'Enthousiasme', 'Technologie', 'Boutique', 'Galaxy', 'Magie', 'Charmant', 'Pâtes' , 'Exubérance', 'Équité', 'Cinéma', 'Persévérance', 'Organisation', 'Persévérance', 'Carrière', 'Incroyable', 'Rêve', 'Originalité', 'Extraordinaire', 'Transcendantale', ' Bureau', 'Plain', 'Milk', 'Skateboard', 'Cellular', 'Intelligence', 'Relaxing', 'Sound', 'Outburst', 'Sunset', 'Inspirational', 'Walking', 'Serenity' , ' Fantasy', 'Emancipator', 'Watchful', 'Ice Cream', 'Afternoon', 'Pencil', 'Belonging', 'Entrepreneurship', 'Integrity', 'Innocence', 'Harmony', 'Self-estime ', 'Joie' , 'Thé', 'Cahier', 'Peinture', 'Riz', 'Enrichissement', 'Motivateur', 'Inclusion', 'Pomme', 'Mindfulness', 'Respect', 'Exploration',  'Voisin ', ' Richesse ', ' Transformation ', ' Peinture ', ' Joie ', ' Chaos ', ' Terre ', ' Papillon ', ' Émerveillement ', ' Exotique ', ' Durabilité ', ' Passionné ', ' Vanille ', 'Fascinant' , 'Acide', 'Tigre', 'Tristesse', 'Vision', 'Foudre', 'Satellite', 'Honnête', 'Cellulaire', 'Végétal', 'Revigorant', 'Whisky', 'Théâtre', 'Paysage', 'Sensation', 'Forteresse', 'Rue', 'Porte', 'Viande', 'Mystère', 'Théâtre', 'Pâtes', 'Samedi', 'Fiançailles', 'Triumph ', 'Fascinant' , 'Courage', 'Blé', 'Gentillesse', 'Paix', 'Durabilité', 'Persistance', 'Ville', 'Architecture', 'Fête', 'Rêveur', 'Infirmier', 'Fortitude', 'Soupir', 'Tender', 'Humility', 'Climb', 'Apple', 'Car', 'Shining', 'Single', 'Relationships', 'Gai', 'Revitalizing', 'Friendly ', 'Excitant' , 'Avenue', 'Beauty', 'Yellow', 'Challenge', 'Culture', 'Efficiency', 'Drums', 'Majestic', 'Scanner', 'Salt', 'Companion', 'Famille', 'Vibrant', 'Environnement', 'Apprentissage', 'Avocat', 'Divertissement', 'Valeurs', 'Boutique', 'Acceptation', 'Famille', 'Connaissance', 'Force', 'Esprit ', 'Brave', 'Révolution', 'Care', 'Explorateur', 'Plage', 'Canapé', 'Amitié', 'Bus', 'Poisson', 'Danse', 'Enchantement', 'Montagne', 'Forêt', 'Survie', 'Incomparable', 'Hôpital', 'Jardin', 'Légende', 'Avenue', 'Sublimation', 'Salade', 'Destiny', 'Gentil', 'Doux', 'Eternité ', 'Chapeau', 'Éternel', 'Amoureux', 'Peinture', 'Coeur', 'Constance', 'Chaise', 'Maître', 'Automobile', 'Metropolis', 'Vibrant', 'Thé', 'Maîtrisé', 'Pinceau', 'Harmonie', 'Plénitude', 'Addictif', 'Violon', 'Méta', 'Pléthorique', 'Pensée', 'Lampe', 'Plaisir', 'Ingéniosité', 'Défis ', 'Incroyable', 'Travail', 'Plage', 'Refuge', 'Matin', 'En colère', 'Honnêteté', 'Fantastique', 'Captivant', 'Émerveillé', 'Transformation', 'Été', 'Math', 'Calme', 'Moto', 'Lion', 'Confort', 'Mémoires', 'Entreprise', 'Drop', 'Rêve', 'Move', 'Développement', 'Sagesse', 'Marié ', 'Marié', 'Amour', 'Mode', 'Art', 'Héroïque', 'Médical', 'Souvenir', 'Transcendental', 'Autonomie', 'Toit', 'Philosophie', 'Incroyable', 'Sorority', 'Paper', 'Tolerance', 'Wall', 'School', 'Climb', 'Sugar', 'Equality', 'Afternoon', 'Soda', 'Future', 'Paradise', 'Engineering ', 'Sublime', 'Repos', 'Beurre', 'Romance', 'Midi', 'Foudre', 'Généreux', 'Motivation', 'Volonté', 'Veuve', 'Ingénierie', 'Dawn', 'Wall', 'Vividity', 'Outdoors', 'Independence', 'Elephant', 'Widower', 'Noon', 'Happy', 'Wonder', 'Heady', 'Promising', ' Éducation', 'Sushi', 'Patient', 'Innovation', 'Agriculture', 'Détermination', 'Tonnerre', 'Énergie', 'Libellule', 'Incroyable', 'Solution', 'Foudre', 'Tigre' , 'Chat', 'Dévouement', 'Bateau', 'Exaltation', 'Rinçage', 'Passion', 'Écologie', 'Honnêteté', 'Émotion', 'Course', 'Technologie', 'Révélateur', ' Explore', 'Dazzle', 'Awaken', 'Wine', 'Tristness', 'History', 'Moon', 'Study', 'Health', 'Wisdom', 'Exorbitant', 'Lovely', 'Milk' , 'Objectifs', 'Écharpe', 'Nager', 'Art', 'Vallée', 'Rivière', 'Nature', 'Hamburger', 'Histoire', 'Bien-être', 'Bénédiction', 'Fun', ' Exploration', 'Nature', 'Agitation', 'Mélodie', 'Philanthropie', 'Foulard', 'Revigorant', 'Chant', 'Tolérance', 'Drop', 'Regard', 'Découvrir', 'Sel' , 'Fun', 'Ville', 'Désolé', 'Ville', 'Sérendipité', 'Solidarité', 'Dimanche', 'Patrimoine', 'Football', 'Communauté', 'Magnifique', 'Arc-en-ciel', ' Encouragement', 'Discipline', 'Pépinière', 'Super', 'Désir', 'Dévouement', 'Musique', 'Utile', 'Santé', 'Porte', 'Affaires', 'Fenêtre', 'Sensibilité' , 'Train', 'Stabilité', 'Girafe', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', ' Exaltation', 'Picturesque', 'Metropolis', 'Renewal', 'Shudder', 'Journey', 'Courage', 'Shocking', 'Sing', 'Celebration', 'Cooperation', 'Dance', 'Rinsing' , 'Enchantement', 'Religion', 'Idyllique', 'Génération', 'Transcendant', 'Plume', 'Blé', 'Satisfaction', 'Affaires', 'Reptile', 'Fruit', 'Table',  'Organisation', 'Stars', 'Imprimante', 'Objectif', 'Motivation', 'Intrépidité', 'Équilibre', 'Calme', 'Anniversaire', 'Divorcé', 'Briller', 'Collaboration', 'Vert' , 'Dessert', 'Mélancolie', 'Photographie', 'Rire', 'Arôme', 'Fruit', 'Détente', 'Rosée', 'Vigueur', 'Générosité', 'Sourire', 'Automne', ' Impulsion', 'Charme', 'Enchanteur', 'Salé', 'Lucidité', 'Bleu', 'Enthousiasme', 'Beauté', 'Croissance', 'Sucre', 'Huile', 'Arc-en-ciel', 'Voyage' , 'Hamster', 'Surprise', 'Aventurier', 'Café', 'Surprenant', 'Curiosité', 'Fil', 'Poisson', 'Remarquable', 'Comprendre', 'Beurre', 'Tôt le matin', 'Étudiant', 'Printemps', 'Lac', 'Thérapie', 'Compétence', 'Grâce', 'Inégalé', 'Objectif', 'Baiser', 'Félin', 'Célibataire', 'Paix', 'Technicien ' , ' Poire ', ' Danse ', ' Colibri ', ' Avion ', ' Lac ', ' Enivrant ', ' Euphorique ', ' Excitant ', ' Fête ', ' Soleil ', ' Pantalon ', ' Sauter ', 'Bateau', 'Céramique', 'Interdépendance', 'Jeu', 'Eloquence', 'Stimulé', 'Essence', 'Salé', 'Confiance', 'Avoine', 'Ethique', 'Initiative', 'Banane ' , 'Nuage', 'Lush', 'Ecrire', 'Rencontre', 'Nourriture', 'Souhait', 'Noble', 'Spiritualité', 'Coopération', 'Harmonie', 'Poivre', 'Améliorer', 'Sublime', 'Éblouissant', 'Tradition', 'Souplesse', 'Univers', 'Girafe', 'Street', 'Diversity', 'Acting', 'Sensitive', 'Technical', 'Compassion', 'Spectacular ' , 'Riz', 'Oiseau', 'Cahier', 'Authentique', 'Silence', 'Fromage', 'T-shirt', 'Aube', 'Abondance', 'Compagnie', 'Défi', 'Astonante ', 'Impression', 'Institut', 'Sunset', 'Réussite', 'Tablette', 'Tempête', 'Entrepreneuriat', 'Tonnerre', 'Excentricité', 'Village', 'Sentiments', 'Électrifié',  'Fascinant ', ' Gratitude ', ' Cannelle ', ' Victoire ', ' Loyauté ', ' Vélo ', ' Maïs ', ' Succès ', ' Émotion ', ' Éducation ', ' Cascade ', ' Liberté ', ' Dentisterie ' , 'Intégrité', 'Canapé', 'Recherche', 'Fromage', 'Illumination', 'Générosité', 'Passion', 'Terre', 'Poésie', 'Sacrifice', 'Résilience', 'Merveilleusement', 'Énergétique' , 'Fenêtre']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Mot:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Devinez une lettre: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("C'est Correct!")
                    else:
                        intentos_restantes -= 1
                        print("Incorrect. Ils te donnent", intentos_restantes, "tentatives.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Gagné! Vous avez deviné le mot :", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Tu as perdu! Le mot était :", palabra)

            print("joueur 1:")
            jugar_ahorcado()


elif a == 6:
    Multiplayer = int(input("válassza ki a játékosok számát 1-2:"))
    if Multiplayer == 2:
        b=int(input("Kérjük, válasszon nehézséget:\n1.easy\n2.medium\n3.hard" ))
        if b == 1:

            lista = ['Társság', 'Keksz', 'ölelés', 'Hűség', 'Dúsító', 'Ősz', 'Ambíció', 'Fényes', 'Csend', 'Tudomány', 'Piros', 'ceruza', 'fahéj' , 'Levegő', 'Szerelem', 'Highway', 'Türelem', 'Magány', 'Stratégia', 'Áttörés', 'Divat', 'Növekedés', 'Kitartás', 'Izgatott', 'Irodalom', 'Parti', 'Remény', 'Inspiráló', 'Innováció', 'Kreativitás', 'Felvillanyozó', 'Csodálkozás', 'Hús', 'Óra', 'Csend', 'irány', 'hó', 'íj', 'Képesség', 'Alvás', 'Narancs', 'Csoda', 'Barátság', 'Változás', 'Számítógép', 'Zene', 'Szőlő', 'Vízkereszt', 'Futás', 'Hála', 'Vezetés', 'Rejtély', 'Szemüveg', 'Kommunikáció', 'Kinyilatkoztatás', 'Edicsért', 'Könnyek', 'Újtörő', 'Suttogás', 'Hó', 'Horizont', 'Eredménytábla', 'Felfedezés' , 'Stílus', 'Varázslatos', 'Sport', 'Irodalom', 'Gyógy', 'Serenity', 'Kutya', 'Frissítés', 'Csoda', 'Iroda', 'Relaxáció', 'Stílus', 'Vitalitás', 'Konzerválás', 'Méltóság', 'Megváltás', 'Úszás', 'Pihenés', 'Izgalmas', 'Karrier', 'Zabpehely', 'Eredmény', 'Taps', 'Idő', 'Joghurt', 'Óceán', 'Mozi', 'Falu', 'Kielégedettség', 'Kávé', 'Gitár', 'Víz', 'Kréta', 'Felelősség', 'Presztízs', 'Öröm', 'Sírás' , 'Optimizmus', 'Csapat', 'Egyenlőség', 'Vanília', 'Tánc', 'Busz', 'Hobby', 'Képzelet', 'Ellenállhatatlan', 'Ragyog', 'Alkalmazkodóképesség', 'Megbecsülés', 'Pen', 'Önkéntesség', 'Remény', 'Érdekes', 'Felvilágosító', 'Felemelő', 'Impresszionizmus', 'Kedd', 'Építészet', 'Haladás', 'Csillagok', 'Közösség', 'Momentor', 'Csodálatos', 'Hegy', 'Környezet', 'Frissítés', 'Alkonyat', 'Innocence', 'Kukorica', 'Bátorság', 'Meglepett', 'Gyakorlat', 'Várj', 'Fénykép', "Valóság', 'Szép', 'Varázslat', 'Alkonyat', 'Sivatag', 'Lenyűgözött', 'Szomorú', 'Olaj', 'Eufória', 'Festmény', 'Wellness', 'Falu', 'Ragyogás' ", 'Tükröződés', 'Tánc', 'Toll', 'Dedikáció', 'Gyönyörű', 'Nevetés', 'Szerelem', 'Torta', 'Sport', 'Újrafeltalálás', 'Kakaó', 'Gasztronómia', 'Szimmetria', 'Testvériség', 'Mérnök', 'Beteljesülés', 'Kakaó', 'Aspiráció', 'Hitelesség', 'Alázat', 'Intrika', 'Öröm', 'Tudat', 'IzgatóÜgyvéd', 'Pénz', 'Joghurt', 'Vezetés', 'Számítógép', 'Lé', 'Tűz', 'Hátszél', 'Bűvölet', 'Bolygó', 'Boldogság', 'Macska', 'Nagyszerűség', 'Elefánt', 'Édes', 'Nyúl', 'Sima', 'Keserű', 'Víz', 'Könyv', 'Tél', 'Munka', 'Vonzó', 'Optimizmus', 'Szobor', 'Gasztronómia', 'Gyönyörű', 'Szemüveg', 'Futball', 'Csodagyerek', 'Tapasztalat', 'Szerezzen ihletet', 'Tenger', 'Misztikus', 'Természet', 'Írás', 'Fantázia', " Séta', 'Öröm', 'Univerzum', 'Te', 'Kifejezés', 'Nevetés', 'Spiritualitás', 'Megfiatalodás', 'Folyó', 'Boldogság', 'Banán', 'Jóga', 'Érzelmi", 'Lehetőség', 'Otthon', 'Toll', 'Türelem', 'Út', 'Öröm', 'Bizalom', 'Vonzás', 'Álmodozás', 'Félelmetes', 'Születésnap', 'Rémálom', ' Csodálkozás', 'Felhők', 'Gyönyörű', 'Egyensúly', 'Együttműködés', 'Tér', 'Empowerment', 'Dizájn', 'Tanulmány', 'Érzelmileg', 'rugalmasság', 'Kosárlabda', 'Izzó', 'Empátia', 'Belső terek', 'Lenyűgöző', 'Felejthetetlen', 'Csodálat', 'Gyönyörű', 'Hegy', 'Megvalósítás', 'Sav', 'Ír', 'Ölelés', 'Kerámia', 'Ugrás', 'Akció', 'Sóhaj', 'Dühös', 'Asztal', 'Kalap', 'Motor', 'Sör', 'Cipők', 'Igazság', 'Izgalmasan', 'Csillag', 'Ünnep' , 'Ritmus', 'Ég', 'Számidő', 'Színes', 'Utazás', 'Harmat', 'Csodálatos', 'Pszichológia', 'Napfelkelte', 'Hála', 'Kihívás', 'Úszás', ' Elemzés', 'Kiváló', 'Örökség', 'Televízió', 'Nadrág', 'Ajándék', 'Jutalom', 'Sivatag', 'Nemesség', 'Kapcsolat', 'Sztori', 'Iskola', 'Érettség', 'Eső', 'Lámpa', 'Spontanitás', 'Claro', 'Csillagkép', 'Egér', 'Kultúra', 'Friss', 'Inspiráció', 'Napgitár', 'Könyv', 'Sokszínűség', 'Kockázat', 'narancs', 'egyetem', 'elszántság', 'fesztivál', 'kedvesség', 'szellő', 'hörcsög', 'autópálya', 'csoda', 'méh', 'remény', 'tudás' , 'Hill', 'Hamster', 'Gentle', 'Energia', 'Ragyogó', 'Gyógyszer', 'Úszás', 'Vízesés', 'Szeretettel', 'Meleg', 'Barátság', 'Telefon', 'Nyúl', 'Hétfő', 'Kültéri', 'Út', 'Ragyog', 'Szaxofon', 'Etika', 'Tenisz', 'Teherautó', 'Tanulás', 'Őszinteség', 'Fenntarthatóság', 'Kedvesség', 'Jungle', 'Ragyog', 'Fókusz', 'Kutya', 'Egyetem', 'Nevelés', 'Felfedezés', 'Kert', 'Képesség', 'Vonat', 'Világítás', 'Tervezés', 'Aréna', 'Tenisz', 'Lush', 'Legyőzni', 'Nyár', 'Mérnök', 'Erdő', 'Vihar', 'Transcendencia', 'Elvált', 'Harmónia', 'Empátia', 'Tisztelet', 'Óra', 'Barát', 'Cérna' , 'Joghurt', 'Iskola', 'Serendipity', 'Repülőgép', 'Játék', 'Nevetés', 'Bőség', 'Szobor', 'Kórház', 'Mosoly', 'Elbűvölő', 'Intuíció', ' Tapasztalat', 'Pompás', 'Óceán', 'Jólét', 'Tudat', 'Tequila', 'Évforduló', 'Csábítás', 'Vezetés', 'Kiváló', 'Udvarias', 'Megújulás', 'Völgy' , 'Reggel', 'Éjszaka', 'Tél', 'Karizma', 'Evolúció', 'Rugalmasság', 'Energikus', 'Változás', 'Kosárlabda', 'Professzionalizmus', 'Inspiráció', 'Izgalmas', ' Csodálatos', 'Siker', 'Szolidaritás', 'Reneszánsz', 'Zöldség', 'Ruha', 'Kagylók', 'Tenger', 'Orvosi', 'Hit', 'Póló', 'Kreativitás', ' Keserű ', 'Ünnep', 'Vitalitás', 'Virágok', 'Éjszaka', 'Kuncogás', 'Jutalom', 'Kaland', 'Paprika', 'Tavasz', 'Izgató', 'Mennyezet', 'Cukor', 'Ruha', 'Nyugalom', 'Szabadság', 'Nyugalom', 'Eszmélet', 'Évforduló', 'Pillanatok', 'Boldog', 'Galaxis', 'Hiteles', 'Meditáció', 'Kompetencia', 'Fa ', 'Táplálkozás', 'Dicsőséges', 'Tudomány', 'Emelkedés', 'Levegő', 'Igazságosság', 'Hatékonyság', 'Varázs', 'Tűz', 'Hagyomány', 'Oázis', 'Meglepetés' , 'Tanítás', 'Öröm', 'Álmodozás', 'Túlcsordulás', 'Kaland', 'Televízió', 'Cipők', 'Csokoládé', 'Kutya', 'Inspiráció', 'Esküvő', 'Harag', 'Szenvedélyes ', 'Gyógyászat', 'Ecset', 'Tiszta', 'Surround', 'Pizza', 'Hold', 'Igazságosság', 'Empowerment', 'Szék', 'Túlcsordulás', 'Szél', 'Bőség ', 'Emlékek', 'Lelkesség', 'Technológia', 'Üzlet', 'Galaxy', 'Varázslat', 'Varázslatos', 'Tészta', 'Exuberance', 'Equity', 'Mozi', 'Kitartás', 'Szervezet', 'Kitartás', 'Karrier', 'Kábult', 'Álmok', 'Eredetiség', 'Rendkívüli', 'Momentous', 'Office', 'Sima', 'Tej', 'Gördeszka', 'Mobiltelefon ', 'Intelligencia', 'Relaxáló', 'Hang', 'Kitörés', 'Naplemente', 'Inspiráló', 'Séta', 'Serenity', 'Fantázia', 'Emancipáló', 'Figyelmes', 'Jéges', 'Este', 'ceruza', 'tartozás', 'Vállalkozás', 'Integrity', 'Innocence', 'Harmónia', 'Önbecsülés', 'Öröm', 'Tea', 'Jegyzetfüzet', 'Festészet', 'Rizs', 'Dúsítás', 'Motivátor', 'Befogadás', 'alma', 'Mindfulness', 'Tisztelet', 'Felfedezés', 'Szomszéd', 'Gazdagság', 'Átalakulás', 'Festészet', 'Öröm ', 'Káosz', 'Föld', 'Pillangó', 'Csodálkozás', 'Egzotikus', 'Fenntarthatóság', 'Szenvedélyes', 'Vanília', 'Lenyűgöző', 'Sav', 'Tigris', 'Szomorúság', 'Látás', 'Villám', 'Műhold', 'Candid', 'Cellular', 'Zöldség', 'Pedig', 'Whisky', 'Színház', 'Táj', 'Érzés', 'Erőd', 'Utca', 'Ajtó', 'Hús', 'Rejtély', 'Színház', 'Tészta', 'Szombat', 'Elkötelezettség', 'Triumph', 'Lenyűgöző', 'Bátorság', 'Búza', 'Kedvesség', 'Béke', 'Fenntarthatóság', 'Kitartás', 'Város', 'Architektúra', 'Parti', 'Álmodozó', 'Ápolás', 'Szilárdság', 'Sóhaj', 'Gyengéd', 'Alázat', 'Mászás ', 'Alma', 'Autó', 'Ragyogó', 'Szingli', 'Kapcsolatok', 'Vidám', 'Revitalizáló', 'Barátságos', 'Izgatottan', 'Avenue', 'Szépség', 'Sárga', 'Defiance', 'Kultúra', 'Hatékonyság', 'Dobok', 'Fenséges', 'Scanner', 'Só', 'Társ', 'Család', 'Vibráns', 'Környezet', 'Tanulás', 'Jogász', 'Szórakozás', 'Értékek', 'Üzlet', 'Elfogadás', 'Család', 'Tudás', 'Erő', 'Szellem', 'Bátor', 'Forradalom', 'Gondoskodás', 'Felfedező', 'Strand', 'Szófa', 'Barátság', 'Busz', 'Hal', 'Tánc', 'Varázslat', 'Hegy', 'Erdő', 'Túlélés', 'Összehasonlíthatatlan', 'Kórház', 'Kert', 'legenda', 'sugárút', 'szublimáció', 'saláta', 'sors', 'kedves', 'édes', 'örökkévalóság', 'sapka', 'örökkévaló', 'szerető', 'festék', 'Szív', 'Állandóság', 'Szék', 'Mester', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive ', 'Hegedű', 'Cél', 'Rengeteg', 'Gondolat', 'Lámpa', 'Élvezet', 'Leleményesség', 'Kihívások', 'Csodálatos', 'Munka', 'Strand', 'Menhely', 'Reggel', 'Dühös', 'Őszinteség', 'Fantasztikus', 'Lenyűgöző', 'Meglepett', 'Átalakulás', 'Nyár', 'Matek', 'Nyugodt', 'Motor', 'Oroszlán', 'Kényelem' , 'Ajándéktárgy', 'Cég', 'Csepp', 'Álom', 'Megható', 'Fejlődés', 'Bölcsesség', 'Házas', 'Házas', 'Szerelem', 'Divat', 'Művészet', 'Heroic', 'Medical', 'Memory', 'Transcendentális', 'Autonómia', 'Tető', 'Filozófia', 'Csodálatos', 'Sorority', 'Papír', 'Tolerancia', 'Fal', 'Iskola', 'Mászás', 'Cukor', 'Egyenlőség', 'Este', 'Szóda', 'Jövő', 'Paradicsom', 'Mérnökség', ' Sublime', 'Pihenés', 'Vaj', 'Romantika', 'Dél', 'Villám', 'Bőkezű', 'Motiváció', 'Akarat', 'Özvegy', 'Műszaki', 'Hajnal', 'Fal', 'Vivacity', 'Outdoors', 'Independence', 'Elefánt', 'Özvegy', 'Dél', 'Boldog', 'Csodálatos', 'Heady', 'Ígéretes', 'Oktatás', 'Sushi', "Beteg', 'Innováció', 'Mezőgazdaság', 'Elszántság', 'Mennydörgés', 'Energia', 'Statakötő', 'Hihetetlen', 'Megoldás', 'Villám', 'Tigris', 'Macska', 'Elköteleződés", 'Csónak', 'Magasztosulás', 'Öblítés', 'Szenvedély', 'Ökológia', 'Őszinteség', 'Érzelem', 'Futás', 'Technológia', 'Revealer', 'Felfedezés', 'Káprázat', 'Ébredjen fel, bor, szomorúság, történelem, hold, tanulmány, egészség, bölcsesség, túlzott, kedves, tej, cél, sál ' , 'Úszás', 'Művészet', 'Völgy', 'Folyó', 'Természet', 'Hamburger', 'Történelem', 'Wellness', 'Áldás', 'Szórakozás', 'Felfedezés', 'Természet', 'Nyugtalanság', 'Dallam', 'Jótékonyság', 'Sál', 'Élénkítő', 'Énekelj', 'Tolerancia', 'Csepp', 'Pillantás', 'Fedezze fel', 'Só', 'Szórakozás', 'Város' , 'Sajnálom', 'Emberek', 'Serendipity', 'Szolidaritás', 'Vasárnap', 'Örökség', 'Futball', 'Közösség', 'Csodálatos', 'Szivárvány', 'Bátorítás', 'Fegyelem', 'Bölcsőde', 'Remek', 'Vágyakozás', 'Szállítás', 'Zene', 'Hasznos', 'Egészség', 'Ajtó', 'Üzleti', 'Ablak', 'Érzékenység', 'Vonat', 'Stabilitás ', 'Zsiráf', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Joy', 'Picturesque', 'Metropolisz', 'Megújulás', 'Reszketés', 'Utazás', 'Bátorság', 'Sokkoló', 'Énekel', 'Ünnep', 'Együttműködés', 'Tánc', 'Öblítés', 'Varázslat', "Vallás ' , 'Idilli', 'Nemzedék', 'Transzcendens', 'Toll', 'Búza', 'Elégedettség', 'Üzlet', 'Hüllő', 'Gyümölcs', 'Asztal', 'Szervezet', 'Csillagok', 'Nyomtató', 'Cél', 'Motiváció', 'Félelemnélküliség', 'Egyensúly', 'Nyugalom', 'Születésnap', 'Elvált', 'Fényerő', 'Együttműködés', 'Zöld', 'Deszert', 'Mélankólia' ", 'Fényképezés', 'Nevetés', 'Aroma', 'Gyümölcs', 'Relaxáció', 'Harmat', 'Vigor', 'Bőkezűség', 'Mosoly', 'Ősz', 'Impulzus', 'Varázs', 'Elbűvölő', 'Sós', 'Lucidity', 'Kék', 'Lelkesség', 'Szépség', 'Növekedés', 'Cukor', 'Olaj', 'Szivárvány', 'Utazás', 'Hörcsög', 'Meglepetés', 'Kalandor', 'Kávé', 'Csodálatos', 'Kíváncsiság', 'Cérna', 'Hal', 'Nevezetes', 'Megértés', 'Vaj', 'Kora reggel', 'Diák', 'Tavasz', 'tó', 'terápia', 'képesség', 'kegyelem', 'egyedi', 'cél', 'csók', 'macskaféle', 'egyedülálló', 'béke', 'technikus', 'körte', ' Tánc', 'Kolibri', 'Repülő', 'Tó', 'Bódító', 'Eufórikus', 'Izgalmas', 'Ünnepi', 'Nap', 'Nadrág', 'Ugrás', 'Csónak', 'Kerámia', 'Kölcsönös' , 'függőség', 'Játék', 'Eloquence', 'Stimulated', 'Essence', 'Sós', 'Trust', 'Zabpehely', 'Etika', 'Kezdeményezés', 'Banán', 'Felhő', ' Lush', 'Írni', 'Találkozás', 'Nevelés', 'Kívánság', 'Nemes', 'Spiritualitás', 'Együttműködés', 'Harmónia', 'Paprika', 'Javulás', 'Fenséges', 'Kápráztató', 'Hagyomány', 'Rugalmasság', 'Univerzum', 'Zsiráf', 'Utca', 'Sokszínűség', 'Cselekedet', 'Érzékeny', 'Műszaki', 'Együttérzés', 'Látványos', 'Rizs', " Madár', 'Jegyzetfüzet', 'Eredeti', 'Csend', 'Sajt', 'Póló', 'Hajnal', 'Bőség', 'Társság', 'Kihívás', 'Astonante', 'Benyomás', ' Intézet', 'Naplemente', 'Eredmény', 'Tábla', 'Vihar', 'Vállalkozás', 'Mennydörgés', 'Különlegesség', 'Falu', 'Érzések', 'Felvillanyozó', 'Lenyűgöző', 'Hála' , 'Fahéj", 'Győzelem', 'Hűség', 'Bringa', 'Kukorica', 'Siker', 'Érzelem', 'Oktatás', 'Vízesés', 'Szabadság', 'Fogászat', 'Integrity',  'Kanapé', 'Kutatás', 'Sajt', 'Megvilágosodás', 'Nagylelkűség', 'Szenvedély', 'Föld', 'Költészet', 'Áldozat', 'Rengalmasság', 'Csodálatos', 'Energikus', 'Ablak']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Szó:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Adivina una letra: ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("helyes!")

                    else:
                        intentos_restantes -= 1
                        print("Helytelen. elmentél", intentos_restantes, "kísérletek.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Nyerte! Kitaláltad a szót:", palabra)
                        break

                if intentos_restantes == 0:
                        print("Vesztettél! A szó ez volt:", palabra)


            print("játékos 1:")
            jugar_ahorcado()
            print("játékos 2:")
            jugar_ahorcado()
        elif b == 2:


            lista = ['Társság', 'Keksz', 'ölelés', 'Hűség', 'Dúsító', 'Ősz', 'Ambíció', 'Fényes', 'Csend', 'Tudomány', 'Piros', 'ceruza', 'fahéj' , 'Levegő', 'Szerelem', 'Highway', 'Türelem', 'Magány', 'Stratégia', 'Áttörés', 'Divat', 'Növekedés', 'Kitartás', 'Izgatott', 'Irodalom', 'Parti', 'Remény', 'Inspiráló', 'Innováció', 'Kreativitás', 'Felvillanyozó', 'Csodálkozás', 'Hús', 'Óra', 'Csend', 'irány', 'hó', 'íj', 'Képesség', 'Alvás', 'Narancs', 'Csoda', 'Barátság', 'Változás', 'Számítógép', 'Zene', 'Szőlő', 'Vízkereszt', 'Futás', 'Hála', 'Vezetés', 'Rejtély', 'Szemüveg', 'Kommunikáció', 'Kinyilatkoztatás', 'Edicsért', 'Könnyek', 'Újtörő', 'Suttogás', 'Hó', 'Horizont', 'Eredménytábla', 'Felfedezés' , 'Stílus', 'Varázslatos', 'Sport', 'Irodalom', 'Gyógy', 'Serenity', 'Kutya', 'Frissítés', 'Csoda', 'Iroda', 'Relaxáció', 'Stílus', 'Vitalitás', 'Konzerválás', 'Méltóság', 'Megváltás', 'Úszás', 'Pihenés', 'Izgalmas', 'Karrier', 'Zabpehely', 'Eredmény', 'Taps', 'Idő', 'Joghurt', 'Óceán', 'Mozi', 'Falu', 'Kielégedettség', 'Kávé', 'Gitár', 'Víz', 'Kréta', 'Felelősség', 'Presztízs', 'Öröm', 'Sírás' , 'Optimizmus', 'Csapat', 'Egyenlőség', 'Vanília', 'Tánc', 'Busz', 'Hobby', 'Képzelet', 'Ellenállhatatlan', 'Ragyog', 'Alkalmazkodóképesség', 'Megbecsülés', 'Pen', 'Önkéntesség', 'Remény', 'Érdekes', 'Felvilágosító', 'Felemelő', 'Impresszionizmus', 'Kedd', 'Építészet', 'Haladás', 'Csillagok', 'Közösség', 'Momentor', 'Csodálatos', 'Hegy', 'Környezet', 'Frissítés', 'Alkonyat', 'Innocence', 'Kukorica', 'Bátorság', 'Meglepett', 'Gyakorlat', 'Várj', 'Fénykép', "Valóság', 'Szép', 'Varázslat', 'Alkonyat', 'Sivatag', 'Lenyűgözött', 'Szomorú', 'Olaj', 'Eufória', 'Festmény', 'Wellness', 'Falu', 'Ragyogás' ", 'Tükröződés', 'Tánc', 'Toll', 'Dedikáció', 'Gyönyörű', 'Nevetés', 'Szerelem', 'Torta', 'Sport', 'Újrafeltalálás', 'Kakaó', 'Gasztronómia', 'Szimmetria', 'Testvériség', 'Mérnök', 'Beteljesülés', 'Kakaó', 'Aspiráció', 'Hitelesség', 'Alázat', 'Intrika', 'Öröm', 'Tudat', 'IzgatóÜgyvéd', 'Pénz', 'Joghurt', 'Vezetés', 'Számítógép', 'Lé', 'Tűz', 'Hátszél', 'Bűvölet', 'Bolygó', 'Boldogság', 'Macska', 'Nagyszerűség', 'Elefánt', 'Édes', 'Nyúl', 'Sima', 'Keserű', 'Víz', 'Könyv', 'Tél', 'Munka', 'Vonzó', 'Optimizmus', 'Szobor', 'Gasztronómia', 'Gyönyörű', 'Szemüveg', 'Futball', 'Csodagyerek', 'Tapasztalat', 'Szerezzen ihletet', 'Tenger', 'Misztikus', 'Természet', 'Írás', 'Fantázia', " Séta', 'Öröm', 'Univerzum', 'Te', 'Kifejezés', 'Nevetés', 'Spiritualitás', 'Megfiatalodás', 'Folyó', 'Boldogság', 'Banán', 'Jóga', 'Érzelmi", 'Lehetőség', 'Otthon', 'Toll', 'Türelem', 'Út', 'Öröm', 'Bizalom', 'Vonzás', 'Álmodozás', 'Félelmetes', 'Születésnap', 'Rémálom', ' Csodálkozás', 'Felhők', 'Gyönyörű', 'Egyensúly', 'Együttműködés', 'Tér', 'Empowerment', 'Dizájn', 'Tanulmány', 'Érzelmileg', 'rugalmasság', 'Kosárlabda', 'Izzó', 'Empátia', 'Belső terek', 'Lenyűgöző', 'Felejthetetlen', 'Csodálat', 'Gyönyörű', 'Hegy', 'Megvalósítás', 'Sav', 'Ír', 'Ölelés', 'Kerámia', 'Ugrás', 'Akció', 'Sóhaj', 'Dühös', 'Asztal', 'Kalap', 'Motor', 'Sör', 'Cipők', 'Igazság', 'Izgalmasan', 'Csillag', 'Ünnep' , 'Ritmus', 'Ég', 'Számidő', 'Színes', 'Utazás', 'Harmat', 'Csodálatos', 'Pszichológia', 'Napfelkelte', 'Hála', 'Kihívás', 'Úszás', ' Elemzés', 'Kiváló', 'Örökség', 'Televízió', 'Nadrág', 'Ajándék', 'Jutalom', 'Sivatag', 'Nemesség', 'Kapcsolat', 'Sztori', 'Iskola', 'Érettség', 'Eső', 'Lámpa', 'Spontanitás', 'Claro', 'Csillagkép', 'Egér', 'Kultúra', 'Friss', 'Inspiráció', 'Napgitár', 'Könyv', 'Sokszínűség', 'Kockázat', 'narancs', 'egyetem', 'elszántság', 'fesztivál', 'kedvesség', 'szellő', 'hörcsög', 'autópálya', 'csoda', 'méh', 'remény', 'tudás' , 'Hill', 'Hamster', 'Gentle', 'Energia', 'Ragyogó', 'Gyógyszer', 'Úszás', 'Vízesés', 'Szeretettel', 'Meleg', 'Barátság', 'Telefon', 'Nyúl', 'Hétfő', 'Kültéri', 'Út', 'Ragyog', 'Szaxofon', 'Etika', 'Tenisz', 'Teherautó', 'Tanulás', 'Őszinteség', 'Fenntarthatóság', 'Kedvesség', 'Jungle', 'Ragyog', 'Fókusz', 'Kutya', 'Egyetem', 'Nevelés', 'Felfedezés', 'Kert', 'Képesség', 'Vonat', 'Világítás', 'Tervezés', 'Aréna', 'Tenisz', 'Lush', 'Legyőzni', 'Nyár', 'Mérnök', 'Erdő', 'Vihar', 'Transcendencia', 'Elvált', 'Harmónia', 'Empátia', 'Tisztelet', 'Óra', 'Barát', 'Cérna' , 'Joghurt', 'Iskola', 'Serendipity', 'Repülőgép', 'Játék', 'Nevetés', 'Bőség', 'Szobor', 'Kórház', 'Mosoly', 'Elbűvölő', 'Intuíció', ' Tapasztalat', 'Pompás', 'Óceán', 'Jólét', 'Tudat', 'Tequila', 'Évforduló', 'Csábítás', 'Vezetés', 'Kiváló', 'Udvarias', 'Megújulás', 'Völgy' , 'Reggel', 'Éjszaka', 'Tél', 'Karizma', 'Evolúció', 'Rugalmasság', 'Energikus', 'Változás', 'Kosárlabda', 'Professzionalizmus', 'Inspiráció', 'Izgalmas', ' Csodálatos', 'Siker', 'Szolidaritás', 'Reneszánsz', 'Zöldség', 'Ruha', 'Kagylók', 'Tenger', 'Orvosi', 'Hit', 'Póló', 'Kreativitás', ' Keserű ', 'Ünnep', 'Vitalitás', 'Virágok', 'Éjszaka', 'Kuncogás', 'Jutalom', 'Kaland', 'Paprika', 'Tavasz', 'Izgató', 'Mennyezet', 'Cukor', 'Ruha', 'Nyugalom', 'Szabadság', 'Nyugalom', 'Eszmélet', 'Évforduló', 'Pillanatok', 'Boldog', 'Galaxis', 'Hiteles', 'Meditáció', 'Kompetencia', 'Fa ', 'Táplálkozás', 'Dicsőséges', 'Tudomány', 'Emelkedés', 'Levegő', 'Igazságosság', 'Hatékonyság', 'Varázs', 'Tűz', 'Hagyomány', 'Oázis', 'Meglepetés' , 'Tanítás', 'Öröm', 'Álmodozás', 'Túlcsordulás', 'Kaland', 'Televízió', 'Cipők', 'Csokoládé', 'Kutya', 'Inspiráció', 'Esküvő', 'Harag', 'Szenvedélyes ', 'Gyógyászat', 'Ecset', 'Tiszta', 'Surround', 'Pizza', 'Hold', 'Igazságosság', 'Empowerment', 'Szék', 'Túlcsordulás', 'Szél', 'Bőség ', 'Emlékek', 'Lelkesség', 'Technológia', 'Üzlet', 'Galaxy', 'Varázslat', 'Varázslatos', 'Tészta', 'Exuberance', 'Equity', 'Mozi', 'Kitartás', 'Szervezet', 'Kitartás', 'Karrier', 'Kábult', 'Álmok', 'Eredetiség', 'Rendkívüli', 'Momentous', 'Office', 'Sima', 'Tej', 'Gördeszka', 'Mobiltelefon ', 'Intelligencia', 'Relaxáló', 'Hang', 'Kitörés', 'Naplemente', 'Inspiráló', 'Séta', 'Serenity', 'Fantázia', 'Emancipáló', 'Figyelmes', 'Jéges', 'Este', 'ceruza', 'tartozás', 'Vállalkozás', 'Integrity', 'Innocence', 'Harmónia', 'Önbecsülés', 'Öröm', 'Tea', 'Jegyzetfüzet', 'Festészet', 'Rizs', 'Dúsítás', 'Motivátor', 'Befogadás', 'alma', 'Mindfulness', 'Tisztelet', 'Felfedezés', 'Szomszéd', 'Gazdagság', 'Átalakulás', 'Festészet', 'Öröm ', 'Káosz', 'Föld', 'Pillangó', 'Csodálkozás', 'Egzotikus', 'Fenntarthatóság', 'Szenvedélyes', 'Vanília', 'Lenyűgöző', 'Sav', 'Tigris', 'Szomorúság', 'Látás', 'Villám', 'Műhold', 'Candid', 'Cellular', 'Zöldség', 'Pedig', 'Whisky', 'Színház', 'Táj', 'Érzés', 'Erőd', 'Utca', 'Ajtó', 'Hús', 'Rejtély', 'Színház', 'Tészta', 'Szombat', 'Elkötelezettség', 'Triumph', 'Lenyűgöző', 'Bátorság', 'Búza', 'Kedvesség', 'Béke', 'Fenntarthatóság', 'Kitartás', 'Város', 'Architektúra', 'Parti', 'Álmodozó', 'Ápolás', 'Szilárdság', 'Sóhaj', 'Gyengéd', 'Alázat', 'Mászás ', 'Alma', 'Autó', 'Ragyogó', 'Szingli', 'Kapcsolatok', 'Vidám', 'Revitalizáló', 'Barátságos', 'Izgatottan', 'Avenue', 'Szépség', 'Sárga', 'Defiance', 'Kultúra', 'Hatékonyság', 'Dobok', 'Fenséges', 'Scanner', 'Só', 'Társ', 'Család', 'Vibráns', 'Környezet', 'Tanulás', 'Jogász', 'Szórakozás', 'Értékek', 'Üzlet', 'Elfogadás', 'Család', 'Tudás', 'Erő', 'Szellem', 'Bátor', 'Forradalom', 'Gondoskodás', 'Felfedező', 'Strand', 'Szófa', 'Barátság', 'Busz', 'Hal', 'Tánc', 'Varázslat', 'Hegy', 'Erdő', 'Túlélés', 'Összehasonlíthatatlan', 'Kórház', 'Kert', 'legenda', 'sugárút', 'szublimáció', 'saláta', 'sors', 'kedves', 'édes', 'örökkévalóság', 'sapka', 'örökkévaló', 'szerető', 'festék', 'Szív', 'Állandóság', 'Szék', 'Mester', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive ', 'Hegedű', 'Cél', 'Rengeteg', 'Gondolat', 'Lámpa', 'Élvezet', 'Leleményesség', 'Kihívások', 'Csodálatos', 'Munka', 'Strand', 'Menhely', 'Reggel', 'Dühös', 'Őszinteség', 'Fantasztikus', 'Lenyűgöző', 'Meglepett', 'Átalakulás', 'Nyár', 'Matek', 'Nyugodt', 'Motor', 'Oroszlán', 'Kényelem' , 'Ajándéktárgy', 'Cég', 'Csepp', 'Álom', 'Megható', 'Fejlődés', 'Bölcsesség', 'Házas', 'Házas', 'Szerelem', 'Divat', 'Művészet', 'Heroic', 'Medical', 'Memory', 'Transcendentális', 'Autonómia', 'Tető', 'Filozófia', 'Csodálatos', 'Sorority', 'Papír', 'Tolerancia', 'Fal', 'Iskola', 'Mászás', 'Cukor', 'Egyenlőség', 'Este', 'Szóda', 'Jövő', 'Paradicsom', 'Mérnökség', ' Sublime', 'Pihenés', 'Vaj', 'Romantika', 'Dél', 'Villám', 'Bőkezű', 'Motiváció', 'Akarat', 'Özvegy', 'Műszaki', 'Hajnal', 'Fal', 'Vivacity', 'Outdoors', 'Independence', 'Elefánt', 'Özvegy', 'Dél', 'Boldog', 'Csodálatos', 'Heady', 'Ígéretes', 'Oktatás', 'Sushi', "Beteg', 'Innováció', 'Mezőgazdaság', 'Elszántság', 'Mennydörgés', 'Energia', 'Statakötő', 'Hihetetlen', 'Megoldás', 'Villám', 'Tigris', 'Macska', 'Elköteleződés", 'Csónak', 'Magasztosulás', 'Öblítés', 'Szenvedély', 'Ökológia', 'Őszinteség', 'Érzelem', 'Futás', 'Technológia', 'Revealer', 'Felfedezés', 'Káprázat', 'Ébredjen fel, bor, szomorúság, történelem, hold, tanulmány, egészség, bölcsesség, túlzott, kedves, tej, cél, sál ' , 'Úszás', 'Művészet', 'Völgy', 'Folyó', 'Természet', 'Hamburger', 'Történelem', 'Wellness', 'Áldás', 'Szórakozás', 'Felfedezés', 'Természet', 'Nyugtalanság', 'Dallam', 'Jótékonyság', 'Sál', 'Élénkítő', 'Énekelj', 'Tolerancia', 'Csepp', 'Pillantás', 'Fedezze fel', 'Só', 'Szórakozás', 'Város' , 'Sajnálom', 'Emberek', 'Serendipity', 'Szolidaritás', 'Vasárnap', 'Örökség', 'Futball', 'Közösség', 'Csodálatos', 'Szivárvány', 'Bátorítás', 'Fegyelem', 'Bölcsőde', 'Remek', 'Vágyakozás', 'Szállítás', 'Zene', 'Hasznos', 'Egészség', 'Ajtó', 'Üzleti', 'Ablak', 'Érzékenység', 'Vonat', 'Stabilitás ', 'Zsiráf', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Joy', 'Picturesque', 'Metropolisz', 'Megújulás', 'Reszketés', 'Utazás', 'Bátorság', 'Sokkoló', 'Énekel', 'Ünnep', 'Együttműködés', 'Tánc', 'Öblítés', 'Varázslat', "Vallás ' , 'Idilli', 'Nemzedék', 'Transzcendens', 'Toll', 'Búza', 'Elégedettség', 'Üzlet', 'Hüllő', 'Gyümölcs', 'Asztal', 'Szervezet', 'Csillagok', 'Nyomtató', 'Cél', 'Motiváció', 'Félelemnélküliség', 'Egyensúly', 'Nyugalom', 'Születésnap', 'Elvált', 'Fényerő', 'Együttműködés', 'Zöld', 'Deszert', 'Mélankólia' ", 'Fényképezés', 'Nevetés', 'Aroma', 'Gyümölcs', 'Relaxáció', 'Harmat', 'Vigor', 'Bőkezűség', 'Mosoly', 'Ősz', 'Impulzus', 'Varázs', 'Elbűvölő', 'Sós', 'Lucidity', 'Kék', 'Lelkesség', 'Szépség', 'Növekedés', 'Cukor', 'Olaj', 'Szivárvány', 'Utazás', 'Hörcsög', 'Meglepetés', 'Kalandor', 'Kávé', 'Csodálatos', 'Kíváncsiság', 'Cérna', 'Hal', 'Nevezetes', 'Megértés', 'Vaj', 'Kora reggel', 'Diák', 'Tavasz', 'tó', 'terápia', 'képesség', 'kegyelem', 'egyedi', 'cél', 'csók', 'macskaféle', 'egyedülálló', 'béke', 'technikus', 'körte', ' Tánc', 'Kolibri', 'Repülő', 'Tó', 'Bódító', 'Eufórikus', 'Izgalmas', 'Ünnepi', 'Nap', 'Nadrág', 'Ugrás', 'Csónak', 'Kerámia', 'Kölcsönös' , 'függőség', 'Játék', 'Eloquence', 'Stimulated', 'Essence', 'Sós', 'Trust', 'Zabpehely', 'Etika', 'Kezdeményezés', 'Banán', 'Felhő', ' Lush', 'Írni', 'Találkozás', 'Nevelés', 'Kívánság', 'Nemes', 'Spiritualitás', 'Együttműködés', 'Harmónia', 'Paprika', 'Javulás', 'Fenséges', 'Kápráztató', 'Hagyomány', 'Rugalmasság', 'Univerzum', 'Zsiráf', 'Utca', 'Sokszínűség', 'Cselekedet', 'Érzékeny', 'Műszaki', 'Együttérzés', 'Látványos', 'Rizs', " Madár', 'Jegyzetfüzet', 'Eredeti', 'Csend', 'Sajt', 'Póló', 'Hajnal', 'Bőség', 'Társság', 'Kihívás', 'Astonante', 'Benyomás', ' Intézet', 'Naplemente', 'Eredmény', 'Tábla', 'Vihar', 'Vállalkozás', 'Mennydörgés', 'Különlegesség', 'Falu', 'Érzések', 'Felvillanyozó', 'Lenyűgöző', 'Hála' , 'Fahéj", 'Győzelem', 'Hűség', 'Bringa', 'Kukorica', 'Siker', 'Érzelem', 'Oktatás', 'Vízesés', 'Szabadság', 'Fogászat', 'Integrity',  'Kanapé', 'Kutatás', 'Sajt', 'Megvilágosodás', 'Nagylelkűség', 'Szenvedély', 'Föld', 'Költészet', 'Áldozat', 'Rengalmasság', 'Csodálatos', 'Energikus', 'Ablak']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Szó:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Adivina una letra: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("helyes!")

                    else:
                        intentos_restantes -= 1
                        print("Helytelen. elmentél", intentos_restantes, "kísérletek.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Nyerte! Kitaláltad a szót:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Vesztettél! A szó ez volt:", palabra)



            print("játékos 1:")
            jugar_ahorcado()
            print("játékos 2:")
            jugar_ahorcado()


        elif b == 3:

            import random
            lista = ['Társság', 'Keksz', 'ölelés', 'Hűség', 'Dúsító', 'Ősz', 'Ambíció', 'Fényes', 'Csend', 'Tudomány', 'Piros', 'ceruza', 'fahéj' , 'Levegő', 'Szerelem', 'Highway', 'Türelem', 'Magány', 'Stratégia', 'Áttörés', 'Divat', 'Növekedés', 'Kitartás', 'Izgatott', 'Irodalom', 'Parti', 'Remény', 'Inspiráló', 'Innováció', 'Kreativitás', 'Felvillanyozó', 'Csodálkozás', 'Hús', 'Óra', 'Csend', 'irány', 'hó', 'íj', 'Képesség', 'Alvás', 'Narancs', 'Csoda', 'Barátság', 'Változás', 'Számítógép', 'Zene', 'Szőlő', 'Vízkereszt', 'Futás', 'Hála', 'Vezetés', 'Rejtély', 'Szemüveg', 'Kommunikáció', 'Kinyilatkoztatás', 'Edicsért', 'Könnyek', 'Újtörő', 'Suttogás', 'Hó', 'Horizont', 'Eredménytábla', 'Felfedezés' , 'Stílus', 'Varázslatos', 'Sport', 'Irodalom', 'Gyógy', 'Serenity', 'Kutya', 'Frissítés', 'Csoda', 'Iroda', 'Relaxáció', 'Stílus', 'Vitalitás', 'Konzerválás', 'Méltóság', 'Megváltás', 'Úszás', 'Pihenés', 'Izgalmas', 'Karrier', 'Zabpehely', 'Eredmény', 'Taps', 'Idő', 'Joghurt', 'Óceán', 'Mozi', 'Falu', 'Kielégedettség', 'Kávé', 'Gitár', 'Víz', 'Kréta', 'Felelősség', 'Presztízs', 'Öröm', 'Sírás' , 'Optimizmus', 'Csapat', 'Egyenlőség', 'Vanília', 'Tánc', 'Busz', 'Hobby', 'Képzelet', 'Ellenállhatatlan', 'Ragyog', 'Alkalmazkodóképesség', 'Megbecsülés', 'Pen', 'Önkéntesség', 'Remény', 'Érdekes', 'Felvilágosító', 'Felemelő', 'Impresszionizmus', 'Kedd', 'Építészet', 'Haladás', 'Csillagok', 'Közösség', 'Momentor', 'Csodálatos', 'Hegy', 'Környezet', 'Frissítés', 'Alkonyat', 'Innocence', 'Kukorica', 'Bátorság', 'Meglepett', 'Gyakorlat', 'Várj', 'Fénykép', "Valóság', 'Szép', 'Varázslat', 'Alkonyat', 'Sivatag', 'Lenyűgözött', 'Szomorú', 'Olaj', 'Eufória', 'Festmény', 'Wellness', 'Falu', 'Ragyogás' ", 'Tükröződés', 'Tánc', 'Toll', 'Dedikáció', 'Gyönyörű', 'Nevetés', 'Szerelem', 'Torta', 'Sport', 'Újrafeltalálás', 'Kakaó', 'Gasztronómia', 'Szimmetria', 'Testvériség', 'Mérnök', 'Beteljesülés', 'Kakaó', 'Aspiráció', 'Hitelesség', 'Alázat', 'Intrika', 'Öröm', 'Tudat', 'IzgatóÜgyvéd', 'Pénz', 'Joghurt', 'Vezetés', 'Számítógép', 'Lé', 'Tűz', 'Hátszél', 'Bűvölet', 'Bolygó', 'Boldogság', 'Macska', 'Nagyszerűség', 'Elefánt', 'Édes', 'Nyúl', 'Sima', 'Keserű', 'Víz', 'Könyv', 'Tél', 'Munka', 'Vonzó', 'Optimizmus', 'Szobor', 'Gasztronómia', 'Gyönyörű', 'Szemüveg', 'Futball', 'Csodagyerek', 'Tapasztalat', 'Szerezzen ihletet', 'Tenger', 'Misztikus', 'Természet', 'Írás', 'Fantázia', " Séta', 'Öröm', 'Univerzum', 'Te', 'Kifejezés', 'Nevetés', 'Spiritualitás', 'Megfiatalodás', 'Folyó', 'Boldogság', 'Banán', 'Jóga', 'Érzelmi", 'Lehetőség', 'Otthon', 'Toll', 'Türelem', 'Út', 'Öröm', 'Bizalom', 'Vonzás', 'Álmodozás', 'Félelmetes', 'Születésnap', 'Rémálom', ' Csodálkozás', 'Felhők', 'Gyönyörű', 'Egyensúly', 'Együttműködés', 'Tér', 'Empowerment', 'Dizájn', 'Tanulmány', 'Érzelmileg', 'rugalmasság', 'Kosárlabda', 'Izzó', 'Empátia', 'Belső terek', 'Lenyűgöző', 'Felejthetetlen', 'Csodálat', 'Gyönyörű', 'Hegy', 'Megvalósítás', 'Sav', 'Ír', 'Ölelés', 'Kerámia', 'Ugrás', 'Akció', 'Sóhaj', 'Dühös', 'Asztal', 'Kalap', 'Motor', 'Sör', 'Cipők', 'Igazság', 'Izgalmasan', 'Csillag', 'Ünnep' , 'Ritmus', 'Ég', 'Számidő', 'Színes', 'Utazás', 'Harmat', 'Csodálatos', 'Pszichológia', 'Napfelkelte', 'Hála', 'Kihívás', 'Úszás', ' Elemzés', 'Kiváló', 'Örökség', 'Televízió', 'Nadrág', 'Ajándék', 'Jutalom', 'Sivatag', 'Nemesség', 'Kapcsolat', 'Sztori', 'Iskola', 'Érettség', 'Eső', 'Lámpa', 'Spontanitás', 'Claro', 'Csillagkép', 'Egér', 'Kultúra', 'Friss', 'Inspiráció', 'Napgitár', 'Könyv', 'Sokszínűség', 'Kockázat', 'narancs', 'egyetem', 'elszántság', 'fesztivál', 'kedvesség', 'szellő', 'hörcsög', 'autópálya', 'csoda', 'méh', 'remény', 'tudás' , 'Hill', 'Hamster', 'Gentle', 'Energia', 'Ragyogó', 'Gyógyszer', 'Úszás', 'Vízesés', 'Szeretettel', 'Meleg', 'Barátság', 'Telefon', 'Nyúl', 'Hétfő', 'Kültéri', 'Út', 'Ragyog', 'Szaxofon', 'Etika', 'Tenisz', 'Teherautó', 'Tanulás', 'Őszinteség', 'Fenntarthatóság', 'Kedvesség', 'Jungle', 'Ragyog', 'Fókusz', 'Kutya', 'Egyetem', 'Nevelés', 'Felfedezés', 'Kert', 'Képesség', 'Vonat', 'Világítás', 'Tervezés', 'Aréna', 'Tenisz', 'Lush', 'Legyőzni', 'Nyár', 'Mérnök', 'Erdő', 'Vihar', 'Transcendencia', 'Elvált', 'Harmónia', 'Empátia', 'Tisztelet', 'Óra', 'Barát', 'Cérna' , 'Joghurt', 'Iskola', 'Serendipity', 'Repülőgép', 'Játék', 'Nevetés', 'Bőség', 'Szobor', 'Kórház', 'Mosoly', 'Elbűvölő', 'Intuíció', ' Tapasztalat', 'Pompás', 'Óceán', 'Jólét', 'Tudat', 'Tequila', 'Évforduló', 'Csábítás', 'Vezetés', 'Kiváló', 'Udvarias', 'Megújulás', 'Völgy' , 'Reggel', 'Éjszaka', 'Tél', 'Karizma', 'Evolúció', 'Rugalmasság', 'Energikus', 'Változás', 'Kosárlabda', 'Professzionalizmus', 'Inspiráció', 'Izgalmas', ' Csodálatos', 'Siker', 'Szolidaritás', 'Reneszánsz', 'Zöldség', 'Ruha', 'Kagylók', 'Tenger', 'Orvosi', 'Hit', 'Póló', 'Kreativitás', ' Keserű ', 'Ünnep', 'Vitalitás', 'Virágok', 'Éjszaka', 'Kuncogás', 'Jutalom', 'Kaland', 'Paprika', 'Tavasz', 'Izgató', 'Mennyezet', 'Cukor', 'Ruha', 'Nyugalom', 'Szabadság', 'Nyugalom', 'Eszmélet', 'Évforduló', 'Pillanatok', 'Boldog', 'Galaxis', 'Hiteles', 'Meditáció', 'Kompetencia', 'Fa ', 'Táplálkozás', 'Dicsőséges', 'Tudomány', 'Emelkedés', 'Levegő', 'Igazságosság', 'Hatékonyság', 'Varázs', 'Tűz', 'Hagyomány', 'Oázis', 'Meglepetés' , 'Tanítás', 'Öröm', 'Álmodozás', 'Túlcsordulás', 'Kaland', 'Televízió', 'Cipők', 'Csokoládé', 'Kutya', 'Inspiráció', 'Esküvő', 'Harag', 'Szenvedélyes ', 'Gyógyászat', 'Ecset', 'Tiszta', 'Surround', 'Pizza', 'Hold', 'Igazságosság', 'Empowerment', 'Szék', 'Túlcsordulás', 'Szél', 'Bőség ', 'Emlékek', 'Lelkesség', 'Technológia', 'Üzlet', 'Galaxy', 'Varázslat', 'Varázslatos', 'Tészta', 'Exuberance', 'Equity', 'Mozi', 'Kitartás', 'Szervezet', 'Kitartás', 'Karrier', 'Kábult', 'Álmok', 'Eredetiség', 'Rendkívüli', 'Momentous', 'Office', 'Sima', 'Tej', 'Gördeszka', 'Mobiltelefon ', 'Intelligencia', 'Relaxáló', 'Hang', 'Kitörés', 'Naplemente', 'Inspiráló', 'Séta', 'Serenity', 'Fantázia', 'Emancipáló', 'Figyelmes', 'Jéges', 'Este', 'ceruza', 'tartozás', 'Vállalkozás', 'Integrity', 'Innocence', 'Harmónia', 'Önbecsülés', 'Öröm', 'Tea', 'Jegyzetfüzet', 'Festészet', 'Rizs', 'Dúsítás', 'Motivátor', 'Befogadás', 'alma', 'Mindfulness', 'Tisztelet', 'Felfedezés', 'Szomszéd', 'Gazdagság', 'Átalakulás', 'Festészet', 'Öröm ', 'Káosz', 'Föld', 'Pillangó', 'Csodálkozás', 'Egzotikus', 'Fenntarthatóság', 'Szenvedélyes', 'Vanília', 'Lenyűgöző', 'Sav', 'Tigris', 'Szomorúság', 'Látás', 'Villám', 'Műhold', 'Candid', 'Cellular', 'Zöldség', 'Pedig', 'Whisky', 'Színház', 'Táj', 'Érzés', 'Erőd', 'Utca', 'Ajtó', 'Hús', 'Rejtély', 'Színház', 'Tészta', 'Szombat', 'Elkötelezettség', 'Triumph', 'Lenyűgöző', 'Bátorság', 'Búza', 'Kedvesség', 'Béke', 'Fenntarthatóság', 'Kitartás', 'Város', 'Architektúra', 'Parti', 'Álmodozó', 'Ápolás', 'Szilárdság', 'Sóhaj', 'Gyengéd', 'Alázat', 'Mászás ', 'Alma', 'Autó', 'Ragyogó', 'Szingli', 'Kapcsolatok', 'Vidám', 'Revitalizáló', 'Barátságos', 'Izgatottan', 'Avenue', 'Szépség', 'Sárga', 'Defiance', 'Kultúra', 'Hatékonyság', 'Dobok', 'Fenséges', 'Scanner', 'Só', 'Társ', 'Család', 'Vibráns', 'Környezet', 'Tanulás', 'Jogász', 'Szórakozás', 'Értékek', 'Üzlet', 'Elfogadás', 'Család', 'Tudás', 'Erő', 'Szellem', 'Bátor', 'Forradalom', 'Gondoskodás', 'Felfedező', 'Strand', 'Szófa', 'Barátság', 'Busz', 'Hal', 'Tánc', 'Varázslat', 'Hegy', 'Erdő', 'Túlélés', 'Összehasonlíthatatlan', 'Kórház', 'Kert', 'legenda', 'sugárút', 'szublimáció', 'saláta', 'sors', 'kedves', 'édes', 'örökkévalóság', 'sapka', 'örökkévaló', 'szerető', 'festék', 'Szív', 'Állandóság', 'Szék', 'Mester', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive ', 'Hegedű', 'Cél', 'Rengeteg', 'Gondolat', 'Lámpa', 'Élvezet', 'Leleményesség', 'Kihívások', 'Csodálatos', 'Munka', 'Strand', 'Menhely', 'Reggel', 'Dühös', 'Őszinteség', 'Fantasztikus', 'Lenyűgöző', 'Meglepett', 'Átalakulás', 'Nyár', 'Matek', 'Nyugodt', 'Motor', 'Oroszlán', 'Kényelem' , 'Ajándéktárgy', 'Cég', 'Csepp', 'Álom', 'Megható', 'Fejlődés', 'Bölcsesség', 'Házas', 'Házas', 'Szerelem', 'Divat', 'Művészet', 'Heroic', 'Medical', 'Memory', 'Transcendentális', 'Autonómia', 'Tető', 'Filozófia', 'Csodálatos', 'Sorority', 'Papír', 'Tolerancia', 'Fal', 'Iskola', 'Mászás', 'Cukor', 'Egyenlőség', 'Este', 'Szóda', 'Jövő', 'Paradicsom', 'Mérnökség', ' Sublime', 'Pihenés', 'Vaj', 'Romantika', 'Dél', 'Villám', 'Bőkezű', 'Motiváció', 'Akarat', 'Özvegy', 'Műszaki', 'Hajnal', 'Fal', 'Vivacity', 'Outdoors', 'Independence', 'Elefánt', 'Özvegy', 'Dél', 'Boldog', 'Csodálatos', 'Heady', 'Ígéretes', 'Oktatás', 'Sushi', "Beteg', 'Innováció', 'Mezőgazdaság', 'Elszántság', 'Mennydörgés', 'Energia', 'Statakötő', 'Hihetetlen', 'Megoldás', 'Villám', 'Tigris', 'Macska', 'Elköteleződés", 'Csónak', 'Magasztosulás', 'Öblítés', 'Szenvedély', 'Ökológia', 'Őszinteség', 'Érzelem', 'Futás', 'Technológia', 'Revealer', 'Felfedezés', 'Káprázat', 'Ébredjen fel, bor, szomorúság, történelem, hold, tanulmány, egészség, bölcsesség, túlzott, kedves, tej, cél, sál ' , 'Úszás', 'Művészet', 'Völgy', 'Folyó', 'Természet', 'Hamburger', 'Történelem', 'Wellness', 'Áldás', 'Szórakozás', 'Felfedezés', 'Természet', 'Nyugtalanság', 'Dallam', 'Jótékonyság', 'Sál', 'Élénkítő', 'Énekelj', 'Tolerancia', 'Csepp', 'Pillantás', 'Fedezze fel', 'Só', 'Szórakozás', 'Város' , 'Sajnálom', 'Emberek', 'Serendipity', 'Szolidaritás', 'Vasárnap', 'Örökség', 'Futball', 'Közösség', 'Csodálatos', 'Szivárvány', 'Bátorítás', 'Fegyelem', 'Bölcsőde', 'Remek', 'Vágyakozás', 'Szállítás', 'Zene', 'Hasznos', 'Egészség', 'Ajtó', 'Üzleti', 'Ablak', 'Érzékenység', 'Vonat', 'Stabilitás ', 'Zsiráf', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Joy', 'Picturesque', 'Metropolisz', 'Megújulás', 'Reszketés', 'Utazás', 'Bátorság', 'Sokkoló', 'Énekel', 'Ünnep', 'Együttműködés', 'Tánc', 'Öblítés', 'Varázslat', "Vallás ' , 'Idilli', 'Nemzedék', 'Transzcendens', 'Toll', 'Búza', 'Elégedettség', 'Üzlet', 'Hüllő', 'Gyümölcs', 'Asztal', 'Szervezet', 'Csillagok', 'Nyomtató', 'Cél', 'Motiváció', 'Félelemnélküliség', 'Egyensúly', 'Nyugalom', 'Születésnap', 'Elvált', 'Fényerő', 'Együttműködés', 'Zöld', 'Deszert', 'Mélankólia' ", 'Fényképezés', 'Nevetés', 'Aroma', 'Gyümölcs', 'Relaxáció', 'Harmat', 'Vigor', 'Bőkezűség', 'Mosoly', 'Ősz', 'Impulzus', 'Varázs', 'Elbűvölő', 'Sós', 'Lucidity', 'Kék', 'Lelkesség', 'Szépség', 'Növekedés', 'Cukor', 'Olaj', 'Szivárvány', 'Utazás', 'Hörcsög', 'Meglepetés', 'Kalandor', 'Kávé', 'Csodálatos', 'Kíváncsiság', 'Cérna', 'Hal', 'Nevezetes', 'Megértés', 'Vaj', 'Kora reggel', 'Diák', 'Tavasz', 'tó', 'terápia', 'képesség', 'kegyelem', 'egyedi', 'cél', 'csók', 'macskaféle', 'egyedülálló', 'béke', 'technikus', 'körte', ' Tánc', 'Kolibri', 'Repülő', 'Tó', 'Bódító', 'Eufórikus', 'Izgalmas', 'Ünnepi', 'Nap', 'Nadrág', 'Ugrás', 'Csónak', 'Kerámia', 'Kölcsönös' , 'függőség', 'Játék', 'Eloquence', 'Stimulated', 'Essence', 'Sós', 'Trust', 'Zabpehely', 'Etika', 'Kezdeményezés', 'Banán', 'Felhő', ' Lush', 'Írni', 'Találkozás', 'Nevelés', 'Kívánság', 'Nemes', 'Spiritualitás', 'Együttműködés', 'Harmónia', 'Paprika', 'Javulás', 'Fenséges', 'Kápráztató', 'Hagyomány', 'Rugalmasság', 'Univerzum', 'Zsiráf', 'Utca', 'Sokszínűség', 'Cselekedet', 'Érzékeny', 'Műszaki', 'Együttérzés', 'Látványos', 'Rizs', " Madár', 'Jegyzetfüzet', 'Eredeti', 'Csend', 'Sajt', 'Póló', 'Hajnal', 'Bőség', 'Társság', 'Kihívás', 'Astonante', 'Benyomás', ' Intézet', 'Naplemente', 'Eredmény', 'Tábla', 'Vihar', 'Vállalkozás', 'Mennydörgés', 'Különlegesség', 'Falu', 'Érzések', 'Felvillanyozó', 'Lenyűgöző', 'Hála' , 'Fahéj", 'Győzelem', 'Hűség', 'Bringa', 'Kukorica', 'Siker', 'Érzelem', 'Oktatás', 'Vízesés', 'Szabadság', 'Fogászat', 'Integrity',  'Kanapé', 'Kutatás', 'Sajt', 'Megvilágosodás', 'Nagylelkűség', 'Szenvedély', 'Föld', 'Költészet', 'Áldozat', 'Rengalmasság', 'Csodálatos', 'Energikus', 'Ablak']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Szó:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Adivina una letra: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("helyes!")
                    else:
                        intentos_restantes -= 1
                        print("Helytelen. elmentél", intentos_restantes, "kísérletek.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Nyerte! Kitaláltad a szót:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Vesztettél! A szó ez volt:", palabra)

            print("játékos 1:")
            jugar_ahorcado()
            print("játékos 2:")
    if Multiplayer == 1:
        b=int(input("Kérjük, válasszon nehézséget:\n1.easy\n2.medium\n3.hard" ))
        if b == 1:

            lista = ['Társság', 'Keksz', 'ölelés', 'Hűség', 'Dúsító', 'Ősz', 'Ambíció', 'Fényes', 'Csend', 'Tudomány', 'Piros', 'ceruza', 'fahéj' , 'Levegő', 'Szerelem', 'Highway', 'Türelem', 'Magány', 'Stratégia', 'Áttörés', 'Divat', 'Növekedés', 'Kitartás', 'Izgatott', 'Irodalom', 'Parti', 'Remény', 'Inspiráló', 'Innováció', 'Kreativitás', 'Felvillanyozó', 'Csodálkozás', 'Hús', 'Óra', 'Csend', 'irány', 'hó', 'íj', 'Képesség', 'Alvás', 'Narancs', 'Csoda', 'Barátság', 'Változás', 'Számítógép', 'Zene', 'Szőlő', 'Vízkereszt', 'Futás', 'Hála', 'Vezetés', 'Rejtély', 'Szemüveg', 'Kommunikáció', 'Kinyilatkoztatás', 'Edicsért', 'Könnyek', 'Újtörő', 'Suttogás', 'Hó', 'Horizont', 'Eredménytábla', 'Felfedezés' , 'Stílus', 'Varázslatos', 'Sport', 'Irodalom', 'Gyógy', 'Serenity', 'Kutya', 'Frissítés', 'Csoda', 'Iroda', 'Relaxáció', 'Stílus', 'Vitalitás', 'Konzerválás', 'Méltóság', 'Megváltás', 'Úszás', 'Pihenés', 'Izgalmas', 'Karrier', 'Zabpehely', 'Eredmény', 'Taps', 'Idő', 'Joghurt', 'Óceán', 'Mozi', 'Falu', 'Kielégedettség', 'Kávé', 'Gitár', 'Víz', 'Kréta', 'Felelősség', 'Presztízs', 'Öröm', 'Sírás' , 'Optimizmus', 'Csapat', 'Egyenlőség', 'Vanília', 'Tánc', 'Busz', 'Hobby', 'Képzelet', 'Ellenállhatatlan', 'Ragyog', 'Alkalmazkodóképesség', 'Megbecsülés', 'Pen', 'Önkéntesség', 'Remény', 'Érdekes', 'Felvilágosító', 'Felemelő', 'Impresszionizmus', 'Kedd', 'Építészet', 'Haladás', 'Csillagok', 'Közösség', 'Momentor', 'Csodálatos', 'Hegy', 'Környezet', 'Frissítés', 'Alkonyat', 'Innocence', 'Kukorica', 'Bátorság', 'Meglepett', 'Gyakorlat', 'Várj', 'Fénykép', "Valóság', 'Szép', 'Varázslat', 'Alkonyat', 'Sivatag', 'Lenyűgözött', 'Szomorú', 'Olaj', 'Eufória', 'Festmény', 'Wellness', 'Falu', 'Ragyogás' ", 'Tükröződés', 'Tánc', 'Toll', 'Dedikáció', 'Gyönyörű', 'Nevetés', 'Szerelem', 'Torta', 'Sport', 'Újrafeltalálás', 'Kakaó', 'Gasztronómia', 'Szimmetria', 'Testvériség', 'Mérnök', 'Beteljesülés', 'Kakaó', 'Aspiráció', 'Hitelesség', 'Alázat', 'Intrika', 'Öröm', 'Tudat', 'IzgatóÜgyvéd', 'Pénz', 'Joghurt', 'Vezetés', 'Számítógép', 'Lé', 'Tűz', 'Hátszél', 'Bűvölet', 'Bolygó', 'Boldogság', 'Macska', 'Nagyszerűség', 'Elefánt', 'Édes', 'Nyúl', 'Sima', 'Keserű', 'Víz', 'Könyv', 'Tél', 'Munka', 'Vonzó', 'Optimizmus', 'Szobor', 'Gasztronómia', 'Gyönyörű', 'Szemüveg', 'Futball', 'Csodagyerek', 'Tapasztalat', 'Szerezzen ihletet', 'Tenger', 'Misztikus', 'Természet', 'Írás', 'Fantázia', " Séta', 'Öröm', 'Univerzum', 'Te', 'Kifejezés', 'Nevetés', 'Spiritualitás', 'Megfiatalodás', 'Folyó', 'Boldogság', 'Banán', 'Jóga', 'Érzelmi", 'Lehetőség', 'Otthon', 'Toll', 'Türelem', 'Út', 'Öröm', 'Bizalom', 'Vonzás', 'Álmodozás', 'Félelmetes', 'Születésnap', 'Rémálom', ' Csodálkozás', 'Felhők', 'Gyönyörű', 'Egyensúly', 'Együttműködés', 'Tér', 'Empowerment', 'Dizájn', 'Tanulmány', 'Érzelmileg', 'rugalmasság', 'Kosárlabda', 'Izzó', 'Empátia', 'Belső terek', 'Lenyűgöző', 'Felejthetetlen', 'Csodálat', 'Gyönyörű', 'Hegy', 'Megvalósítás', 'Sav', 'Ír', 'Ölelés', 'Kerámia', 'Ugrás', 'Akció', 'Sóhaj', 'Dühös', 'Asztal', 'Kalap', 'Motor', 'Sör', 'Cipők', 'Igazság', 'Izgalmasan', 'Csillag', 'Ünnep' , 'Ritmus', 'Ég', 'Számidő', 'Színes', 'Utazás', 'Harmat', 'Csodálatos', 'Pszichológia', 'Napfelkelte', 'Hála', 'Kihívás', 'Úszás', ' Elemzés', 'Kiváló', 'Örökség', 'Televízió', 'Nadrág', 'Ajándék', 'Jutalom', 'Sivatag', 'Nemesség', 'Kapcsolat', 'Sztori', 'Iskola', 'Érettség', 'Eső', 'Lámpa', 'Spontanitás', 'Claro', 'Csillagkép', 'Egér', 'Kultúra', 'Friss', 'Inspiráció', 'Napgitár', 'Könyv', 'Sokszínűség', 'Kockázat', 'narancs', 'egyetem', 'elszántság', 'fesztivál', 'kedvesség', 'szellő', 'hörcsög', 'autópálya', 'csoda', 'méh', 'remény', 'tudás' , 'Hill', 'Hamster', 'Gentle', 'Energia', 'Ragyogó', 'Gyógyszer', 'Úszás', 'Vízesés', 'Szeretettel', 'Meleg', 'Barátság', 'Telefon', 'Nyúl', 'Hétfő', 'Kültéri', 'Út', 'Ragyog', 'Szaxofon', 'Etika', 'Tenisz', 'Teherautó', 'Tanulás', 'Őszinteség', 'Fenntarthatóság', 'Kedvesség', 'Jungle', 'Ragyog', 'Fókusz', 'Kutya', 'Egyetem', 'Nevelés', 'Felfedezés', 'Kert', 'Képesség', 'Vonat', 'Világítás', 'Tervezés', 'Aréna', 'Tenisz', 'Lush', 'Legyőzni', 'Nyár', 'Mérnök', 'Erdő', 'Vihar', 'Transcendencia', 'Elvált', 'Harmónia', 'Empátia', 'Tisztelet', 'Óra', 'Barát', 'Cérna' , 'Joghurt', 'Iskola', 'Serendipity', 'Repülőgép', 'Játék', 'Nevetés', 'Bőség', 'Szobor', 'Kórház', 'Mosoly', 'Elbűvölő', 'Intuíció', ' Tapasztalat', 'Pompás', 'Óceán', 'Jólét', 'Tudat', 'Tequila', 'Évforduló', 'Csábítás', 'Vezetés', 'Kiváló', 'Udvarias', 'Megújulás', 'Völgy' , 'Reggel', 'Éjszaka', 'Tél', 'Karizma', 'Evolúció', 'Rugalmasság', 'Energikus', 'Változás', 'Kosárlabda', 'Professzionalizmus', 'Inspiráció', 'Izgalmas', ' Csodálatos', 'Siker', 'Szolidaritás', 'Reneszánsz', 'Zöldség', 'Ruha', 'Kagylók', 'Tenger', 'Orvosi', 'Hit', 'Póló', 'Kreativitás', ' Keserű ', 'Ünnep', 'Vitalitás', 'Virágok', 'Éjszaka', 'Kuncogás', 'Jutalom', 'Kaland', 'Paprika', 'Tavasz', 'Izgató', 'Mennyezet', 'Cukor', 'Ruha', 'Nyugalom', 'Szabadság', 'Nyugalom', 'Eszmélet', 'Évforduló', 'Pillanatok', 'Boldog', 'Galaxis', 'Hiteles', 'Meditáció', 'Kompetencia', 'Fa ', 'Táplálkozás', 'Dicsőséges', 'Tudomány', 'Emelkedés', 'Levegő', 'Igazságosság', 'Hatékonyság', 'Varázs', 'Tűz', 'Hagyomány', 'Oázis', 'Meglepetés' , 'Tanítás', 'Öröm', 'Álmodozás', 'Túlcsordulás', 'Kaland', 'Televízió', 'Cipők', 'Csokoládé', 'Kutya', 'Inspiráció', 'Esküvő', 'Harag', 'Szenvedélyes ', 'Gyógyászat', 'Ecset', 'Tiszta', 'Surround', 'Pizza', 'Hold', 'Igazságosság', 'Empowerment', 'Szék', 'Túlcsordulás', 'Szél', 'Bőség ', 'Emlékek', 'Lelkesség', 'Technológia', 'Üzlet', 'Galaxy', 'Varázslat', 'Varázslatos', 'Tészta', 'Exuberance', 'Equity', 'Mozi', 'Kitartás', 'Szervezet', 'Kitartás', 'Karrier', 'Kábult', 'Álmok', 'Eredetiség', 'Rendkívüli', 'Momentous', 'Office', 'Sima', 'Tej', 'Gördeszka', 'Mobiltelefon ', 'Intelligencia', 'Relaxáló', 'Hang', 'Kitörés', 'Naplemente', 'Inspiráló', 'Séta', 'Serenity', 'Fantázia', 'Emancipáló', 'Figyelmes', 'Jéges', 'Este', 'ceruza', 'tartozás', 'Vállalkozás', 'Integrity', 'Innocence', 'Harmónia', 'Önbecsülés', 'Öröm', 'Tea', 'Jegyzetfüzet', 'Festészet', 'Rizs', 'Dúsítás', 'Motivátor', 'Befogadás', 'alma', 'Mindfulness', 'Tisztelet', 'Felfedezés', 'Szomszéd', 'Gazdagság', 'Átalakulás', 'Festészet', 'Öröm ', 'Káosz', 'Föld', 'Pillangó', 'Csodálkozás', 'Egzotikus', 'Fenntarthatóság', 'Szenvedélyes', 'Vanília', 'Lenyűgöző', 'Sav', 'Tigris', 'Szomorúság', 'Látás', 'Villám', 'Műhold', 'Candid', 'Cellular', 'Zöldség', 'Pedig', 'Whisky', 'Színház', 'Táj', 'Érzés', 'Erőd', 'Utca', 'Ajtó', 'Hús', 'Rejtély', 'Színház', 'Tészta', 'Szombat', 'Elkötelezettség', 'Triumph', 'Lenyűgöző', 'Bátorság', 'Búza', 'Kedvesség', 'Béke', 'Fenntarthatóság', 'Kitartás', 'Város', 'Architektúra', 'Parti', 'Álmodozó', 'Ápolás', 'Szilárdság', 'Sóhaj', 'Gyengéd', 'Alázat', 'Mászás ', 'Alma', 'Autó', 'Ragyogó', 'Szingli', 'Kapcsolatok', 'Vidám', 'Revitalizáló', 'Barátságos', 'Izgatottan', 'Avenue', 'Szépség', 'Sárga', 'Defiance', 'Kultúra', 'Hatékonyság', 'Dobok', 'Fenséges', 'Scanner', 'Só', 'Társ', 'Család', 'Vibráns', 'Környezet', 'Tanulás', 'Jogász', 'Szórakozás', 'Értékek', 'Üzlet', 'Elfogadás', 'Család', 'Tudás', 'Erő', 'Szellem', 'Bátor', 'Forradalom', 'Gondoskodás', 'Felfedező', 'Strand', 'Szófa', 'Barátság', 'Busz', 'Hal', 'Tánc', 'Varázslat', 'Hegy', 'Erdő', 'Túlélés', 'Összehasonlíthatatlan', 'Kórház', 'Kert', 'legenda', 'sugárút', 'szublimáció', 'saláta', 'sors', 'kedves', 'édes', 'örökkévalóság', 'sapka', 'örökkévaló', 'szerető', 'festék', 'Szív', 'Állandóság', 'Szék', 'Mester', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive ', 'Hegedű', 'Cél', 'Rengeteg', 'Gondolat', 'Lámpa', 'Élvezet', 'Leleményesség', 'Kihívások', 'Csodálatos', 'Munka', 'Strand', 'Menhely', 'Reggel', 'Dühös', 'Őszinteség', 'Fantasztikus', 'Lenyűgöző', 'Meglepett', 'Átalakulás', 'Nyár', 'Matek', 'Nyugodt', 'Motor', 'Oroszlán', 'Kényelem' , 'Ajándéktárgy', 'Cég', 'Csepp', 'Álom', 'Megható', 'Fejlődés', 'Bölcsesség', 'Házas', 'Házas', 'Szerelem', 'Divat', 'Művészet', 'Heroic', 'Medical', 'Memory', 'Transcendentális', 'Autonómia', 'Tető', 'Filozófia', 'Csodálatos', 'Sorority', 'Papír', 'Tolerancia', 'Fal', 'Iskola', 'Mászás', 'Cukor', 'Egyenlőség', 'Este', 'Szóda', 'Jövő', 'Paradicsom', 'Mérnökség', ' Sublime', 'Pihenés', 'Vaj', 'Romantika', 'Dél', 'Villám', 'Bőkezű', 'Motiváció', 'Akarat', 'Özvegy', 'Műszaki', 'Hajnal', 'Fal', 'Vivacity', 'Outdoors', 'Independence', 'Elefánt', 'Özvegy', 'Dél', 'Boldog', 'Csodálatos', 'Heady', 'Ígéretes', 'Oktatás', 'Sushi', "Beteg', 'Innováció', 'Mezőgazdaság', 'Elszántság', 'Mennydörgés', 'Energia', 'Statakötő', 'Hihetetlen', 'Megoldás', 'Villám', 'Tigris', 'Macska', 'Elköteleződés", 'Csónak', 'Magasztosulás', 'Öblítés', 'Szenvedély', 'Ökológia', 'Őszinteség', 'Érzelem', 'Futás', 'Technológia', 'Revealer', 'Felfedezés', 'Káprázat', 'Ébredjen fel, bor, szomorúság, történelem, hold, tanulmány, egészség, bölcsesség, túlzott, kedves, tej, cél, sál ' , 'Úszás', 'Művészet', 'Völgy', 'Folyó', 'Természet', 'Hamburger', 'Történelem', 'Wellness', 'Áldás', 'Szórakozás', 'Felfedezés', 'Természet', 'Nyugtalanság', 'Dallam', 'Jótékonyság', 'Sál', 'Élénkítő', 'Énekelj', 'Tolerancia', 'Csepp', 'Pillantás', 'Fedezze fel', 'Só', 'Szórakozás', 'Város' , 'Sajnálom', 'Emberek', 'Serendipity', 'Szolidaritás', 'Vasárnap', 'Örökség', 'Futball', 'Közösség', 'Csodálatos', 'Szivárvány', 'Bátorítás', 'Fegyelem', 'Bölcsőde', 'Remek', 'Vágyakozás', 'Szállítás', 'Zene', 'Hasznos', 'Egészség', 'Ajtó', 'Üzleti', 'Ablak', 'Érzékenység', 'Vonat', 'Stabilitás ', 'Zsiráf', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Joy', 'Picturesque', 'Metropolisz', 'Megújulás', 'Reszketés', 'Utazás', 'Bátorság', 'Sokkoló', 'Énekel', 'Ünnep', 'Együttműködés', 'Tánc', 'Öblítés', 'Varázslat', "Vallás ' , 'Idilli', 'Nemzedék', 'Transzcendens', 'Toll', 'Búza', 'Elégedettség', 'Üzlet', 'Hüllő', 'Gyümölcs', 'Asztal', 'Szervezet', 'Csillagok', 'Nyomtató', 'Cél', 'Motiváció', 'Félelemnélküliség', 'Egyensúly', 'Nyugalom', 'Születésnap', 'Elvált', 'Fényerő', 'Együttműködés', 'Zöld', 'Deszert', 'Mélankólia' ", 'Fényképezés', 'Nevetés', 'Aroma', 'Gyümölcs', 'Relaxáció', 'Harmat', 'Vigor', 'Bőkezűség', 'Mosoly', 'Ősz', 'Impulzus', 'Varázs', 'Elbűvölő', 'Sós', 'Lucidity', 'Kék', 'Lelkesség', 'Szépség', 'Növekedés', 'Cukor', 'Olaj', 'Szivárvány', 'Utazás', 'Hörcsög', 'Meglepetés', 'Kalandor', 'Kávé', 'Csodálatos', 'Kíváncsiság', 'Cérna', 'Hal', 'Nevezetes', 'Megértés', 'Vaj', 'Kora reggel', 'Diák', 'Tavasz', 'tó', 'terápia', 'képesség', 'kegyelem', 'egyedi', 'cél', 'csók', 'macskaféle', 'egyedülálló', 'béke', 'technikus', 'körte', ' Tánc', 'Kolibri', 'Repülő', 'Tó', 'Bódító', 'Eufórikus', 'Izgalmas', 'Ünnepi', 'Nap', 'Nadrág', 'Ugrás', 'Csónak', 'Kerámia', 'Kölcsönös' , 'függőség', 'Játék', 'Eloquence', 'Stimulated', 'Essence', 'Sós', 'Trust', 'Zabpehely', 'Etika', 'Kezdeményezés', 'Banán', 'Felhő', ' Lush', 'Írni', 'Találkozás', 'Nevelés', 'Kívánság', 'Nemes', 'Spiritualitás', 'Együttműködés', 'Harmónia', 'Paprika', 'Javulás', 'Fenséges', 'Kápráztató', 'Hagyomány', 'Rugalmasság', 'Univerzum', 'Zsiráf', 'Utca', 'Sokszínűség', 'Cselekedet', 'Érzékeny', 'Műszaki', 'Együttérzés', 'Látványos', 'Rizs', " Madár', 'Jegyzetfüzet', 'Eredeti', 'Csend', 'Sajt', 'Póló', 'Hajnal', 'Bőség', 'Társság', 'Kihívás', 'Astonante', 'Benyomás', ' Intézet', 'Naplemente', 'Eredmény', 'Tábla', 'Vihar', 'Vállalkozás', 'Mennydörgés', 'Különlegesség', 'Falu', 'Érzések', 'Felvillanyozó', 'Lenyűgöző', 'Hála' , 'Fahéj", 'Győzelem', 'Hűség', 'Bringa', 'Kukorica', 'Siker', 'Érzelem', 'Oktatás', 'Vízesés', 'Szabadság', 'Fogászat', 'Integrity',  'Kanapé', 'Kutatás', 'Sajt', 'Megvilágosodás', 'Nagylelkűség', 'Szenvedély', 'Föld', 'Költészet', 'Áldozat', 'Rengalmasság', 'Csodálatos', 'Energikus', 'Ablak']


            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Szó:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Adivina una letra: ")

            def Stickman(intentos):
                if intentos == range(1, 1000):
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 1000
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("helyes!")

                    else:
                        intentos_restantes -= 1
                        print("Helytelen. elmentél", intentos_restantes, "kísérletek.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Nyerte! Kitaláltad a szót:", palabra)
                        break

                if intentos_restantes == 0:
                        print("Vesztettél! A szó ez volt:", palabra)


            print("játékos 1:")
            jugar_ahorcado()

        elif b == 2:


            lista = ['Társság', 'Keksz', 'ölelés', 'Hűség', 'Dúsító', 'Ősz', 'Ambíció', 'Fényes', 'Csend', 'Tudomány', 'Piros', 'ceruza', 'fahéj' , 'Levegő', 'Szerelem', 'Highway', 'Türelem', 'Magány', 'Stratégia', 'Áttörés', 'Divat', 'Növekedés', 'Kitartás', 'Izgatott', 'Irodalom', 'Parti', 'Remény', 'Inspiráló', 'Innováció', 'Kreativitás', 'Felvillanyozó', 'Csodálkozás', 'Hús', 'Óra', 'Csend', 'irány', 'hó', 'íj', 'Képesség', 'Alvás', 'Narancs', 'Csoda', 'Barátság', 'Változás', 'Számítógép', 'Zene', 'Szőlő', 'Vízkereszt', 'Futás', 'Hála', 'Vezetés', 'Rejtély', 'Szemüveg', 'Kommunikáció', 'Kinyilatkoztatás', 'Edicsért', 'Könnyek', 'Újtörő', 'Suttogás', 'Hó', 'Horizont', 'Eredménytábla', 'Felfedezés' , 'Stílus', 'Varázslatos', 'Sport', 'Irodalom', 'Gyógy', 'Serenity', 'Kutya', 'Frissítés', 'Csoda', 'Iroda', 'Relaxáció', 'Stílus', 'Vitalitás', 'Konzerválás', 'Méltóság', 'Megváltás', 'Úszás', 'Pihenés', 'Izgalmas', 'Karrier', 'Zabpehely', 'Eredmény', 'Taps', 'Idő', 'Joghurt', 'Óceán', 'Mozi', 'Falu', 'Kielégedettség', 'Kávé', 'Gitár', 'Víz', 'Kréta', 'Felelősség', 'Presztízs', 'Öröm', 'Sírás' , 'Optimizmus', 'Csapat', 'Egyenlőség', 'Vanília', 'Tánc', 'Busz', 'Hobby', 'Képzelet', 'Ellenállhatatlan', 'Ragyog', 'Alkalmazkodóképesség', 'Megbecsülés', 'Pen', 'Önkéntesség', 'Remény', 'Érdekes', 'Felvilágosító', 'Felemelő', 'Impresszionizmus', 'Kedd', 'Építészet', 'Haladás', 'Csillagok', 'Közösség', 'Momentor', 'Csodálatos', 'Hegy', 'Környezet', 'Frissítés', 'Alkonyat', 'Innocence', 'Kukorica', 'Bátorság', 'Meglepett', 'Gyakorlat', 'Várj', 'Fénykép', "Valóság', 'Szép', 'Varázslat', 'Alkonyat', 'Sivatag', 'Lenyűgözött', 'Szomorú', 'Olaj', 'Eufória', 'Festmény', 'Wellness', 'Falu', 'Ragyogás' ", 'Tükröződés', 'Tánc', 'Toll', 'Dedikáció', 'Gyönyörű', 'Nevetés', 'Szerelem', 'Torta', 'Sport', 'Újrafeltalálás', 'Kakaó', 'Gasztronómia', 'Szimmetria', 'Testvériség', 'Mérnök', 'Beteljesülés', 'Kakaó', 'Aspiráció', 'Hitelesség', 'Alázat', 'Intrika', 'Öröm', 'Tudat', 'IzgatóÜgyvéd', 'Pénz', 'Joghurt', 'Vezetés', 'Számítógép', 'Lé', 'Tűz', 'Hátszél', 'Bűvölet', 'Bolygó', 'Boldogság', 'Macska', 'Nagyszerűség', 'Elefánt', 'Édes', 'Nyúl', 'Sima', 'Keserű', 'Víz', 'Könyv', 'Tél', 'Munka', 'Vonzó', 'Optimizmus', 'Szobor', 'Gasztronómia', 'Gyönyörű', 'Szemüveg', 'Futball', 'Csodagyerek', 'Tapasztalat', 'Szerezzen ihletet', 'Tenger', 'Misztikus', 'Természet', 'Írás', 'Fantázia', " Séta', 'Öröm', 'Univerzum', 'Te', 'Kifejezés', 'Nevetés', 'Spiritualitás', 'Megfiatalodás', 'Folyó', 'Boldogság', 'Banán', 'Jóga', 'Érzelmi", 'Lehetőség', 'Otthon', 'Toll', 'Türelem', 'Út', 'Öröm', 'Bizalom', 'Vonzás', 'Álmodozás', 'Félelmetes', 'Születésnap', 'Rémálom', ' Csodálkozás', 'Felhők', 'Gyönyörű', 'Egyensúly', 'Együttműködés', 'Tér', 'Empowerment', 'Dizájn', 'Tanulmány', 'Érzelmileg', 'rugalmasság', 'Kosárlabda', 'Izzó', 'Empátia', 'Belső terek', 'Lenyűgöző', 'Felejthetetlen', 'Csodálat', 'Gyönyörű', 'Hegy', 'Megvalósítás', 'Sav', 'Ír', 'Ölelés', 'Kerámia', 'Ugrás', 'Akció', 'Sóhaj', 'Dühös', 'Asztal', 'Kalap', 'Motor', 'Sör', 'Cipők', 'Igazság', 'Izgalmasan', 'Csillag', 'Ünnep' , 'Ritmus', 'Ég', 'Számidő', 'Színes', 'Utazás', 'Harmat', 'Csodálatos', 'Pszichológia', 'Napfelkelte', 'Hála', 'Kihívás', 'Úszás', ' Elemzés', 'Kiváló', 'Örökség', 'Televízió', 'Nadrág', 'Ajándék', 'Jutalom', 'Sivatag', 'Nemesség', 'Kapcsolat', 'Sztori', 'Iskola', 'Érettség', 'Eső', 'Lámpa', 'Spontanitás', 'Claro', 'Csillagkép', 'Egér', 'Kultúra', 'Friss', 'Inspiráció', 'Napgitár', 'Könyv', 'Sokszínűség', 'Kockázat', 'narancs', 'egyetem', 'elszántság', 'fesztivál', 'kedvesség', 'szellő', 'hörcsög', 'autópálya', 'csoda', 'méh', 'remény', 'tudás' , 'Hill', 'Hamster', 'Gentle', 'Energia', 'Ragyogó', 'Gyógyszer', 'Úszás', 'Vízesés', 'Szeretettel', 'Meleg', 'Barátság', 'Telefon', 'Nyúl', 'Hétfő', 'Kültéri', 'Út', 'Ragyog', 'Szaxofon', 'Etika', 'Tenisz', 'Teherautó', 'Tanulás', 'Őszinteség', 'Fenntarthatóság', 'Kedvesség', 'Jungle', 'Ragyog', 'Fókusz', 'Kutya', 'Egyetem', 'Nevelés', 'Felfedezés', 'Kert', 'Képesség', 'Vonat', 'Világítás', 'Tervezés', 'Aréna', 'Tenisz', 'Lush', 'Legyőzni', 'Nyár', 'Mérnök', 'Erdő', 'Vihar', 'Transcendencia', 'Elvált', 'Harmónia', 'Empátia', 'Tisztelet', 'Óra', 'Barát', 'Cérna' , 'Joghurt', 'Iskola', 'Serendipity', 'Repülőgép', 'Játék', 'Nevetés', 'Bőség', 'Szobor', 'Kórház', 'Mosoly', 'Elbűvölő', 'Intuíció', ' Tapasztalat', 'Pompás', 'Óceán', 'Jólét', 'Tudat', 'Tequila', 'Évforduló', 'Csábítás', 'Vezetés', 'Kiváló', 'Udvarias', 'Megújulás', 'Völgy' , 'Reggel', 'Éjszaka', 'Tél', 'Karizma', 'Evolúció', 'Rugalmasság', 'Energikus', 'Változás', 'Kosárlabda', 'Professzionalizmus', 'Inspiráció', 'Izgalmas', ' Csodálatos', 'Siker', 'Szolidaritás', 'Reneszánsz', 'Zöldség', 'Ruha', 'Kagylók', 'Tenger', 'Orvosi', 'Hit', 'Póló', 'Kreativitás', ' Keserű ', 'Ünnep', 'Vitalitás', 'Virágok', 'Éjszaka', 'Kuncogás', 'Jutalom', 'Kaland', 'Paprika', 'Tavasz', 'Izgató', 'Mennyezet', 'Cukor', 'Ruha', 'Nyugalom', 'Szabadság', 'Nyugalom', 'Eszmélet', 'Évforduló', 'Pillanatok', 'Boldog', 'Galaxis', 'Hiteles', 'Meditáció', 'Kompetencia', 'Fa ', 'Táplálkozás', 'Dicsőséges', 'Tudomány', 'Emelkedés', 'Levegő', 'Igazságosság', 'Hatékonyság', 'Varázs', 'Tűz', 'Hagyomány', 'Oázis', 'Meglepetés' , 'Tanítás', 'Öröm', 'Álmodozás', 'Túlcsordulás', 'Kaland', 'Televízió', 'Cipők', 'Csokoládé', 'Kutya', 'Inspiráció', 'Esküvő', 'Harag', 'Szenvedélyes ', 'Gyógyászat', 'Ecset', 'Tiszta', 'Surround', 'Pizza', 'Hold', 'Igazságosság', 'Empowerment', 'Szék', 'Túlcsordulás', 'Szél', 'Bőség ', 'Emlékek', 'Lelkesség', 'Technológia', 'Üzlet', 'Galaxy', 'Varázslat', 'Varázslatos', 'Tészta', 'Exuberance', 'Equity', 'Mozi', 'Kitartás', 'Szervezet', 'Kitartás', 'Karrier', 'Kábult', 'Álmok', 'Eredetiség', 'Rendkívüli', 'Momentous', 'Office', 'Sima', 'Tej', 'Gördeszka', 'Mobiltelefon ', 'Intelligencia', 'Relaxáló', 'Hang', 'Kitörés', 'Naplemente', 'Inspiráló', 'Séta', 'Serenity', 'Fantázia', 'Emancipáló', 'Figyelmes', 'Jéges', 'Este', 'ceruza', 'tartozás', 'Vállalkozás', 'Integrity', 'Innocence', 'Harmónia', 'Önbecsülés', 'Öröm', 'Tea', 'Jegyzetfüzet', 'Festészet', 'Rizs', 'Dúsítás', 'Motivátor', 'Befogadás', 'alma', 'Mindfulness', 'Tisztelet', 'Felfedezés', 'Szomszéd', 'Gazdagság', 'Átalakulás', 'Festészet', 'Öröm ', 'Káosz', 'Föld', 'Pillangó', 'Csodálkozás', 'Egzotikus', 'Fenntarthatóság', 'Szenvedélyes', 'Vanília', 'Lenyűgöző', 'Sav', 'Tigris', 'Szomorúság', 'Látás', 'Villám', 'Műhold', 'Candid', 'Cellular', 'Zöldség', 'Pedig', 'Whisky', 'Színház', 'Táj', 'Érzés', 'Erőd', 'Utca', 'Ajtó', 'Hús', 'Rejtély', 'Színház', 'Tészta', 'Szombat', 'Elkötelezettség', 'Triumph', 'Lenyűgöző', 'Bátorság', 'Búza', 'Kedvesség', 'Béke', 'Fenntarthatóság', 'Kitartás', 'Város', 'Architektúra', 'Parti', 'Álmodozó', 'Ápolás', 'Szilárdság', 'Sóhaj', 'Gyengéd', 'Alázat', 'Mászás ', 'Alma', 'Autó', 'Ragyogó', 'Szingli', 'Kapcsolatok', 'Vidám', 'Revitalizáló', 'Barátságos', 'Izgatottan', 'Avenue', 'Szépség', 'Sárga', 'Defiance', 'Kultúra', 'Hatékonyság', 'Dobok', 'Fenséges', 'Scanner', 'Só', 'Társ', 'Család', 'Vibráns', 'Környezet', 'Tanulás', 'Jogász', 'Szórakozás', 'Értékek', 'Üzlet', 'Elfogadás', 'Család', 'Tudás', 'Erő', 'Szellem', 'Bátor', 'Forradalom', 'Gondoskodás', 'Felfedező', 'Strand', 'Szófa', 'Barátság', 'Busz', 'Hal', 'Tánc', 'Varázslat', 'Hegy', 'Erdő', 'Túlélés', 'Összehasonlíthatatlan', 'Kórház', 'Kert', 'legenda', 'sugárút', 'szublimáció', 'saláta', 'sors', 'kedves', 'édes', 'örökkévalóság', 'sapka', 'örökkévaló', 'szerető', 'festék', 'Szív', 'Állandóság', 'Szék', 'Mester', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive ', 'Hegedű', 'Cél', 'Rengeteg', 'Gondolat', 'Lámpa', 'Élvezet', 'Leleményesség', 'Kihívások', 'Csodálatos', 'Munka', 'Strand', 'Menhely', 'Reggel', 'Dühös', 'Őszinteség', 'Fantasztikus', 'Lenyűgöző', 'Meglepett', 'Átalakulás', 'Nyár', 'Matek', 'Nyugodt', 'Motor', 'Oroszlán', 'Kényelem' , 'Ajándéktárgy', 'Cég', 'Csepp', 'Álom', 'Megható', 'Fejlődés', 'Bölcsesség', 'Házas', 'Házas', 'Szerelem', 'Divat', 'Művészet', 'Heroic', 'Medical', 'Memory', 'Transcendentális', 'Autonómia', 'Tető', 'Filozófia', 'Csodálatos', 'Sorority', 'Papír', 'Tolerancia', 'Fal', 'Iskola', 'Mászás', 'Cukor', 'Egyenlőség', 'Este', 'Szóda', 'Jövő', 'Paradicsom', 'Mérnökség', ' Sublime', 'Pihenés', 'Vaj', 'Romantika', 'Dél', 'Villám', 'Bőkezű', 'Motiváció', 'Akarat', 'Özvegy', 'Műszaki', 'Hajnal', 'Fal', 'Vivacity', 'Outdoors', 'Independence', 'Elefánt', 'Özvegy', 'Dél', 'Boldog', 'Csodálatos', 'Heady', 'Ígéretes', 'Oktatás', 'Sushi', "Beteg', 'Innováció', 'Mezőgazdaság', 'Elszántság', 'Mennydörgés', 'Energia', 'Statakötő', 'Hihetetlen', 'Megoldás', 'Villám', 'Tigris', 'Macska', 'Elköteleződés", 'Csónak', 'Magasztosulás', 'Öblítés', 'Szenvedély', 'Ökológia', 'Őszinteség', 'Érzelem', 'Futás', 'Technológia', 'Revealer', 'Felfedezés', 'Káprázat', 'Ébredjen fel, bor, szomorúság, történelem, hold, tanulmány, egészség, bölcsesség, túlzott, kedves, tej, cél, sál ' , 'Úszás', 'Művészet', 'Völgy', 'Folyó', 'Természet', 'Hamburger', 'Történelem', 'Wellness', 'Áldás', 'Szórakozás', 'Felfedezés', 'Természet', 'Nyugtalanság', 'Dallam', 'Jótékonyság', 'Sál', 'Élénkítő', 'Énekelj', 'Tolerancia', 'Csepp', 'Pillantás', 'Fedezze fel', 'Só', 'Szórakozás', 'Város' , 'Sajnálom', 'Emberek', 'Serendipity', 'Szolidaritás', 'Vasárnap', 'Örökség', 'Futball', 'Közösség', 'Csodálatos', 'Szivárvány', 'Bátorítás', 'Fegyelem', 'Bölcsőde', 'Remek', 'Vágyakozás', 'Szállítás', 'Zene', 'Hasznos', 'Egészség', 'Ajtó', 'Üzleti', 'Ablak', 'Érzékenység', 'Vonat', 'Stabilitás ', 'Zsiráf', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Joy', 'Picturesque', 'Metropolisz', 'Megújulás', 'Reszketés', 'Utazás', 'Bátorság', 'Sokkoló', 'Énekel', 'Ünnep', 'Együttműködés', 'Tánc', 'Öblítés', 'Varázslat', "Vallás ' , 'Idilli', 'Nemzedék', 'Transzcendens', 'Toll', 'Búza', 'Elégedettség', 'Üzlet', 'Hüllő', 'Gyümölcs', 'Asztal', 'Szervezet', 'Csillagok', 'Nyomtató', 'Cél', 'Motiváció', 'Félelemnélküliség', 'Egyensúly', 'Nyugalom', 'Születésnap', 'Elvált', 'Fényerő', 'Együttműködés', 'Zöld', 'Deszert', 'Mélankólia' ", 'Fényképezés', 'Nevetés', 'Aroma', 'Gyümölcs', 'Relaxáció', 'Harmat', 'Vigor', 'Bőkezűség', 'Mosoly', 'Ősz', 'Impulzus', 'Varázs', 'Elbűvölő', 'Sós', 'Lucidity', 'Kék', 'Lelkesség', 'Szépség', 'Növekedés', 'Cukor', 'Olaj', 'Szivárvány', 'Utazás', 'Hörcsög', 'Meglepetés', 'Kalandor', 'Kávé', 'Csodálatos', 'Kíváncsiság', 'Cérna', 'Hal', 'Nevezetes', 'Megértés', 'Vaj', 'Kora reggel', 'Diák', 'Tavasz', 'tó', 'terápia', 'képesség', 'kegyelem', 'egyedi', 'cél', 'csók', 'macskaféle', 'egyedülálló', 'béke', 'technikus', 'körte', ' Tánc', 'Kolibri', 'Repülő', 'Tó', 'Bódító', 'Eufórikus', 'Izgalmas', 'Ünnepi', 'Nap', 'Nadrág', 'Ugrás', 'Csónak', 'Kerámia', 'Kölcsönös' , 'függőség', 'Játék', 'Eloquence', 'Stimulated', 'Essence', 'Sós', 'Trust', 'Zabpehely', 'Etika', 'Kezdeményezés', 'Banán', 'Felhő', ' Lush', 'Írni', 'Találkozás', 'Nevelés', 'Kívánság', 'Nemes', 'Spiritualitás', 'Együttműködés', 'Harmónia', 'Paprika', 'Javulás', 'Fenséges', 'Kápráztató', 'Hagyomány', 'Rugalmasság', 'Univerzum', 'Zsiráf', 'Utca', 'Sokszínűség', 'Cselekedet', 'Érzékeny', 'Műszaki', 'Együttérzés', 'Látványos', 'Rizs', " Madár', 'Jegyzetfüzet', 'Eredeti', 'Csend', 'Sajt', 'Póló', 'Hajnal', 'Bőség', 'Társság', 'Kihívás', 'Astonante', 'Benyomás', ' Intézet', 'Naplemente', 'Eredmény', 'Tábla', 'Vihar', 'Vállalkozás', 'Mennydörgés', 'Különlegesség', 'Falu', 'Érzések', 'Felvillanyozó', 'Lenyűgöző', 'Hála' , 'Fahéj", 'Győzelem', 'Hűség', 'Bringa', 'Kukorica', 'Siker', 'Érzelem', 'Oktatás', 'Vízesés', 'Szabadság', 'Fogászat', 'Integrity',  'Kanapé', 'Kutatás', 'Sajt', 'Megvilágosodás', 'Nagylelkűség', 'Szenvedély', 'Föld', 'Költészet', 'Áldozat', 'Rengalmasság', 'Csodálatos', 'Energikus', 'Ablak']

            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Szó:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Adivina una letra: ")

            def Stickman(intentos):
                if intentos == 0:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    /")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |\\")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 5:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 6:
                    print("  -------")
                    print("  |     |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 7:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 8:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 9:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")
                elif intentos == 10:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 10
                intentos_restantes = intentos_totales


                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("helyes!")

                    else:
                        intentos_restantes -= 1
                        print("Helytelen. elmentél", intentos_restantes, "kísérletek.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Nyerte! Kitaláltad a szót:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Vesztettél! A szó ez volt:", palabra)



            print("játékos 1:")
            jugar_ahorcado()



        elif b == 3:

            import random
            lista = ['Társság', 'Keksz', 'ölelés', 'Hűség', 'Dúsító', 'Ősz', 'Ambíció', 'Fényes', 'Csend', 'Tudomány', 'Piros', 'ceruza', 'fahéj' , 'Levegő', 'Szerelem', 'Highway', 'Türelem', 'Magány', 'Stratégia', 'Áttörés', 'Divat', 'Növekedés', 'Kitartás', 'Izgatott', 'Irodalom', 'Parti', 'Remény', 'Inspiráló', 'Innováció', 'Kreativitás', 'Felvillanyozó', 'Csodálkozás', 'Hús', 'Óra', 'Csend', 'irány', 'hó', 'íj', 'Képesség', 'Alvás', 'Narancs', 'Csoda', 'Barátság', 'Változás', 'Számítógép', 'Zene', 'Szőlő', 'Vízkereszt', 'Futás', 'Hála', 'Vezetés', 'Rejtély', 'Szemüveg', 'Kommunikáció', 'Kinyilatkoztatás', 'Edicsért', 'Könnyek', 'Újtörő', 'Suttogás', 'Hó', 'Horizont', 'Eredménytábla', 'Felfedezés' , 'Stílus', 'Varázslatos', 'Sport', 'Irodalom', 'Gyógy', 'Serenity', 'Kutya', 'Frissítés', 'Csoda', 'Iroda', 'Relaxáció', 'Stílus', 'Vitalitás', 'Konzerválás', 'Méltóság', 'Megváltás', 'Úszás', 'Pihenés', 'Izgalmas', 'Karrier', 'Zabpehely', 'Eredmény', 'Taps', 'Idő', 'Joghurt', 'Óceán', 'Mozi', 'Falu', 'Kielégedettség', 'Kávé', 'Gitár', 'Víz', 'Kréta', 'Felelősség', 'Presztízs', 'Öröm', 'Sírás' , 'Optimizmus', 'Csapat', 'Egyenlőség', 'Vanília', 'Tánc', 'Busz', 'Hobby', 'Képzelet', 'Ellenállhatatlan', 'Ragyog', 'Alkalmazkodóképesség', 'Megbecsülés', 'Pen', 'Önkéntesség', 'Remény', 'Érdekes', 'Felvilágosító', 'Felemelő', 'Impresszionizmus', 'Kedd', 'Építészet', 'Haladás', 'Csillagok', 'Közösség', 'Momentor', 'Csodálatos', 'Hegy', 'Környezet', 'Frissítés', 'Alkonyat', 'Innocence', 'Kukorica', 'Bátorság', 'Meglepett', 'Gyakorlat', 'Várj', 'Fénykép', "Valóság', 'Szép', 'Varázslat', 'Alkonyat', 'Sivatag', 'Lenyűgözött', 'Szomorú', 'Olaj', 'Eufória', 'Festmény', 'Wellness', 'Falu', 'Ragyogás' ", 'Tükröződés', 'Tánc', 'Toll', 'Dedikáció', 'Gyönyörű', 'Nevetés', 'Szerelem', 'Torta', 'Sport', 'Újrafeltalálás', 'Kakaó', 'Gasztronómia', 'Szimmetria', 'Testvériség', 'Mérnök', 'Beteljesülés', 'Kakaó', 'Aspiráció', 'Hitelesség', 'Alázat', 'Intrika', 'Öröm', 'Tudat', 'IzgatóÜgyvéd', 'Pénz', 'Joghurt', 'Vezetés', 'Számítógép', 'Lé', 'Tűz', 'Hátszél', 'Bűvölet', 'Bolygó', 'Boldogság', 'Macska', 'Nagyszerűség', 'Elefánt', 'Édes', 'Nyúl', 'Sima', 'Keserű', 'Víz', 'Könyv', 'Tél', 'Munka', 'Vonzó', 'Optimizmus', 'Szobor', 'Gasztronómia', 'Gyönyörű', 'Szemüveg', 'Futball', 'Csodagyerek', 'Tapasztalat', 'Szerezzen ihletet', 'Tenger', 'Misztikus', 'Természet', 'Írás', 'Fantázia', " Séta', 'Öröm', 'Univerzum', 'Te', 'Kifejezés', 'Nevetés', 'Spiritualitás', 'Megfiatalodás', 'Folyó', 'Boldogság', 'Banán', 'Jóga', 'Érzelmi", 'Lehetőség', 'Otthon', 'Toll', 'Türelem', 'Út', 'Öröm', 'Bizalom', 'Vonzás', 'Álmodozás', 'Félelmetes', 'Születésnap', 'Rémálom', ' Csodálkozás', 'Felhők', 'Gyönyörű', 'Egyensúly', 'Együttműködés', 'Tér', 'Empowerment', 'Dizájn', 'Tanulmány', 'Érzelmileg', 'rugalmasság', 'Kosárlabda', 'Izzó', 'Empátia', 'Belső terek', 'Lenyűgöző', 'Felejthetetlen', 'Csodálat', 'Gyönyörű', 'Hegy', 'Megvalósítás', 'Sav', 'Ír', 'Ölelés', 'Kerámia', 'Ugrás', 'Akció', 'Sóhaj', 'Dühös', 'Asztal', 'Kalap', 'Motor', 'Sör', 'Cipők', 'Igazság', 'Izgalmasan', 'Csillag', 'Ünnep' , 'Ritmus', 'Ég', 'Számidő', 'Színes', 'Utazás', 'Harmat', 'Csodálatos', 'Pszichológia', 'Napfelkelte', 'Hála', 'Kihívás', 'Úszás', ' Elemzés', 'Kiváló', 'Örökség', 'Televízió', 'Nadrág', 'Ajándék', 'Jutalom', 'Sivatag', 'Nemesség', 'Kapcsolat', 'Sztori', 'Iskola', 'Érettség', 'Eső', 'Lámpa', 'Spontanitás', 'Claro', 'Csillagkép', 'Egér', 'Kultúra', 'Friss', 'Inspiráció', 'Napgitár', 'Könyv', 'Sokszínűség', 'Kockázat', 'narancs', 'egyetem', 'elszántság', 'fesztivál', 'kedvesség', 'szellő', 'hörcsög', 'autópálya', 'csoda', 'méh', 'remény', 'tudás' , 'Hill', 'Hamster', 'Gentle', 'Energia', 'Ragyogó', 'Gyógyszer', 'Úszás', 'Vízesés', 'Szeretettel', 'Meleg', 'Barátság', 'Telefon', 'Nyúl', 'Hétfő', 'Kültéri', 'Út', 'Ragyog', 'Szaxofon', 'Etika', 'Tenisz', 'Teherautó', 'Tanulás', 'Őszinteség', 'Fenntarthatóság', 'Kedvesség', 'Jungle', 'Ragyog', 'Fókusz', 'Kutya', 'Egyetem', 'Nevelés', 'Felfedezés', 'Kert', 'Képesség', 'Vonat', 'Világítás', 'Tervezés', 'Aréna', 'Tenisz', 'Lush', 'Legyőzni', 'Nyár', 'Mérnök', 'Erdő', 'Vihar', 'Transcendencia', 'Elvált', 'Harmónia', 'Empátia', 'Tisztelet', 'Óra', 'Barát', 'Cérna' , 'Joghurt', 'Iskola', 'Serendipity', 'Repülőgép', 'Játék', 'Nevetés', 'Bőség', 'Szobor', 'Kórház', 'Mosoly', 'Elbűvölő', 'Intuíció', ' Tapasztalat', 'Pompás', 'Óceán', 'Jólét', 'Tudat', 'Tequila', 'Évforduló', 'Csábítás', 'Vezetés', 'Kiváló', 'Udvarias', 'Megújulás', 'Völgy' , 'Reggel', 'Éjszaka', 'Tél', 'Karizma', 'Evolúció', 'Rugalmasság', 'Energikus', 'Változás', 'Kosárlabda', 'Professzionalizmus', 'Inspiráció', 'Izgalmas', ' Csodálatos', 'Siker', 'Szolidaritás', 'Reneszánsz', 'Zöldség', 'Ruha', 'Kagylók', 'Tenger', 'Orvosi', 'Hit', 'Póló', 'Kreativitás', ' Keserű ', 'Ünnep', 'Vitalitás', 'Virágok', 'Éjszaka', 'Kuncogás', 'Jutalom', 'Kaland', 'Paprika', 'Tavasz', 'Izgató', 'Mennyezet', 'Cukor', 'Ruha', 'Nyugalom', 'Szabadság', 'Nyugalom', 'Eszmélet', 'Évforduló', 'Pillanatok', 'Boldog', 'Galaxis', 'Hiteles', 'Meditáció', 'Kompetencia', 'Fa ', 'Táplálkozás', 'Dicsőséges', 'Tudomány', 'Emelkedés', 'Levegő', 'Igazságosság', 'Hatékonyság', 'Varázs', 'Tűz', 'Hagyomány', 'Oázis', 'Meglepetés' , 'Tanítás', 'Öröm', 'Álmodozás', 'Túlcsordulás', 'Kaland', 'Televízió', 'Cipők', 'Csokoládé', 'Kutya', 'Inspiráció', 'Esküvő', 'Harag', 'Szenvedélyes ', 'Gyógyászat', 'Ecset', 'Tiszta', 'Surround', 'Pizza', 'Hold', 'Igazságosság', 'Empowerment', 'Szék', 'Túlcsordulás', 'Szél', 'Bőség ', 'Emlékek', 'Lelkesség', 'Technológia', 'Üzlet', 'Galaxy', 'Varázslat', 'Varázslatos', 'Tészta', 'Exuberance', 'Equity', 'Mozi', 'Kitartás', 'Szervezet', 'Kitartás', 'Karrier', 'Kábult', 'Álmok', 'Eredetiség', 'Rendkívüli', 'Momentous', 'Office', 'Sima', 'Tej', 'Gördeszka', 'Mobiltelefon ', 'Intelligencia', 'Relaxáló', 'Hang', 'Kitörés', 'Naplemente', 'Inspiráló', 'Séta', 'Serenity', 'Fantázia', 'Emancipáló', 'Figyelmes', 'Jéges', 'Este', 'ceruza', 'tartozás', 'Vállalkozás', 'Integrity', 'Innocence', 'Harmónia', 'Önbecsülés', 'Öröm', 'Tea', 'Jegyzetfüzet', 'Festészet', 'Rizs', 'Dúsítás', 'Motivátor', 'Befogadás', 'alma', 'Mindfulness', 'Tisztelet', 'Felfedezés', 'Szomszéd', 'Gazdagság', 'Átalakulás', 'Festészet', 'Öröm ', 'Káosz', 'Föld', 'Pillangó', 'Csodálkozás', 'Egzotikus', 'Fenntarthatóság', 'Szenvedélyes', 'Vanília', 'Lenyűgöző', 'Sav', 'Tigris', 'Szomorúság', 'Látás', 'Villám', 'Műhold', 'Candid', 'Cellular', 'Zöldség', 'Pedig', 'Whisky', 'Színház', 'Táj', 'Érzés', 'Erőd', 'Utca', 'Ajtó', 'Hús', 'Rejtély', 'Színház', 'Tészta', 'Szombat', 'Elkötelezettség', 'Triumph', 'Lenyűgöző', 'Bátorság', 'Búza', 'Kedvesség', 'Béke', 'Fenntarthatóság', 'Kitartás', 'Város', 'Architektúra', 'Parti', 'Álmodozó', 'Ápolás', 'Szilárdság', 'Sóhaj', 'Gyengéd', 'Alázat', 'Mászás ', 'Alma', 'Autó', 'Ragyogó', 'Szingli', 'Kapcsolatok', 'Vidám', 'Revitalizáló', 'Barátságos', 'Izgatottan', 'Avenue', 'Szépség', 'Sárga', 'Defiance', 'Kultúra', 'Hatékonyság', 'Dobok', 'Fenséges', 'Scanner', 'Só', 'Társ', 'Család', 'Vibráns', 'Környezet', 'Tanulás', 'Jogász', 'Szórakozás', 'Értékek', 'Üzlet', 'Elfogadás', 'Család', 'Tudás', 'Erő', 'Szellem', 'Bátor', 'Forradalom', 'Gondoskodás', 'Felfedező', 'Strand', 'Szófa', 'Barátság', 'Busz', 'Hal', 'Tánc', 'Varázslat', 'Hegy', 'Erdő', 'Túlélés', 'Összehasonlíthatatlan', 'Kórház', 'Kert', 'legenda', 'sugárút', 'szublimáció', 'saláta', 'sors', 'kedves', 'édes', 'örökkévalóság', 'sapka', 'örökkévaló', 'szerető', 'festék', 'Szív', 'Állandóság', 'Szék', 'Mester', 'Automobile', 'Metropolis', 'Vibrant', 'Tea', 'Subdued', 'Brush', 'Harmony', 'Plenitude', 'Addictive ', 'Hegedű', 'Cél', 'Rengeteg', 'Gondolat', 'Lámpa', 'Élvezet', 'Leleményesség', 'Kihívások', 'Csodálatos', 'Munka', 'Strand', 'Menhely', 'Reggel', 'Dühös', 'Őszinteség', 'Fantasztikus', 'Lenyűgöző', 'Meglepett', 'Átalakulás', 'Nyár', 'Matek', 'Nyugodt', 'Motor', 'Oroszlán', 'Kényelem' , 'Ajándéktárgy', 'Cég', 'Csepp', 'Álom', 'Megható', 'Fejlődés', 'Bölcsesség', 'Házas', 'Házas', 'Szerelem', 'Divat', 'Művészet', 'Heroic', 'Medical', 'Memory', 'Transcendentális', 'Autonómia', 'Tető', 'Filozófia', 'Csodálatos', 'Sorority', 'Papír', 'Tolerancia', 'Fal', 'Iskola', 'Mászás', 'Cukor', 'Egyenlőség', 'Este', 'Szóda', 'Jövő', 'Paradicsom', 'Mérnökség', ' Sublime', 'Pihenés', 'Vaj', 'Romantika', 'Dél', 'Villám', 'Bőkezű', 'Motiváció', 'Akarat', 'Özvegy', 'Műszaki', 'Hajnal', 'Fal', 'Vivacity', 'Outdoors', 'Independence', 'Elefánt', 'Özvegy', 'Dél', 'Boldog', 'Csodálatos', 'Heady', 'Ígéretes', 'Oktatás', 'Sushi', "Beteg', 'Innováció', 'Mezőgazdaság', 'Elszántság', 'Mennydörgés', 'Energia', 'Statakötő', 'Hihetetlen', 'Megoldás', 'Villám', 'Tigris', 'Macska', 'Elköteleződés", 'Csónak', 'Magasztosulás', 'Öblítés', 'Szenvedély', 'Ökológia', 'Őszinteség', 'Érzelem', 'Futás', 'Technológia', 'Revealer', 'Felfedezés', 'Káprázat', 'Ébredjen fel, bor, szomorúság, történelem, hold, tanulmány, egészség, bölcsesség, túlzott, kedves, tej, cél, sál ' , 'Úszás', 'Művészet', 'Völgy', 'Folyó', 'Természet', 'Hamburger', 'Történelem', 'Wellness', 'Áldás', 'Szórakozás', 'Felfedezés', 'Természet', 'Nyugtalanság', 'Dallam', 'Jótékonyság', 'Sál', 'Élénkítő', 'Énekelj', 'Tolerancia', 'Csepp', 'Pillantás', 'Fedezze fel', 'Só', 'Szórakozás', 'Város' , 'Sajnálom', 'Emberek', 'Serendipity', 'Szolidaritás', 'Vasárnap', 'Örökség', 'Futball', 'Közösség', 'Csodálatos', 'Szivárvány', 'Bátorítás', 'Fegyelem', 'Bölcsőde', 'Remek', 'Vágyakozás', 'Szállítás', 'Zene', 'Hasznos', 'Egészség', 'Ajtó', 'Üzleti', 'Ablak', 'Érzékenység', 'Vonat', 'Stabilitás ', 'Zsiráf', 'Enigma', 'Courage', 'Juice', 'Magic', 'Word', 'Unique', 'Piano', 'Metropolis', 'Productivity', 'Joy', 'Picturesque', 'Metropolisz', 'Megújulás', 'Reszketés', 'Utazás', 'Bátorság', 'Sokkoló', 'Énekel', 'Ünnep', 'Együttműködés', 'Tánc', 'Öblítés', 'Varázslat', "Vallás ' , 'Idilli', 'Nemzedék', 'Transzcendens', 'Toll', 'Búza', 'Elégedettség', 'Üzlet', 'Hüllő', 'Gyümölcs', 'Asztal', 'Szervezet', 'Csillagok', 'Nyomtató', 'Cél', 'Motiváció', 'Félelemnélküliség', 'Egyensúly', 'Nyugalom', 'Születésnap', 'Elvált', 'Fényerő', 'Együttműködés', 'Zöld', 'Deszert', 'Mélankólia' ", 'Fényképezés', 'Nevetés', 'Aroma', 'Gyümölcs', 'Relaxáció', 'Harmat', 'Vigor', 'Bőkezűség', 'Mosoly', 'Ősz', 'Impulzus', 'Varázs', 'Elbűvölő', 'Sós', 'Lucidity', 'Kék', 'Lelkesség', 'Szépség', 'Növekedés', 'Cukor', 'Olaj', 'Szivárvány', 'Utazás', 'Hörcsög', 'Meglepetés', 'Kalandor', 'Kávé', 'Csodálatos', 'Kíváncsiság', 'Cérna', 'Hal', 'Nevezetes', 'Megértés', 'Vaj', 'Kora reggel', 'Diák', 'Tavasz', 'tó', 'terápia', 'képesség', 'kegyelem', 'egyedi', 'cél', 'csók', 'macskaféle', 'egyedülálló', 'béke', 'technikus', 'körte', ' Tánc', 'Kolibri', 'Repülő', 'Tó', 'Bódító', 'Eufórikus', 'Izgalmas', 'Ünnepi', 'Nap', 'Nadrág', 'Ugrás', 'Csónak', 'Kerámia', 'Kölcsönös' , 'függőség', 'Játék', 'Eloquence', 'Stimulated', 'Essence', 'Sós', 'Trust', 'Zabpehely', 'Etika', 'Kezdeményezés', 'Banán', 'Felhő', ' Lush', 'Írni', 'Találkozás', 'Nevelés', 'Kívánság', 'Nemes', 'Spiritualitás', 'Együttműködés', 'Harmónia', 'Paprika', 'Javulás', 'Fenséges', 'Kápráztató', 'Hagyomány', 'Rugalmasság', 'Univerzum', 'Zsiráf', 'Utca', 'Sokszínűség', 'Cselekedet', 'Érzékeny', 'Műszaki', 'Együttérzés', 'Látványos', 'Rizs', " Madár', 'Jegyzetfüzet', 'Eredeti', 'Csend', 'Sajt', 'Póló', 'Hajnal', 'Bőség', 'Társság', 'Kihívás', 'Astonante', 'Benyomás', ' Intézet', 'Naplemente', 'Eredmény', 'Tábla', 'Vihar', 'Vállalkozás', 'Mennydörgés', 'Különlegesség', 'Falu', 'Érzések', 'Felvillanyozó', 'Lenyűgöző', 'Hála' , 'Fahéj", 'Győzelem', 'Hűség', 'Bringa', 'Kukorica', 'Siker', 'Érzelem', 'Oktatás', 'Vízesés', 'Szabadság', 'Fogászat', 'Integrity',  'Kanapé', 'Kutatás', 'Sajt', 'Megvilágosodás', 'Nagylelkűség', 'Szenvedély', 'Föld', 'Költészet', 'Áldozat', 'Rengalmasság', 'Csodálatos', 'Energikus', 'Ablak']



            def Palabra_Aleatoria(lista_palabras):
                palabra_aleatoria = random.choice(lista_palabras)
                return palabra_aleatoria

            def ocultar_palabra(palabra):
                oculta = "_" * len(palabra)
                return oculta

            def mostrar_palabra(palabra_oculta):
                print("Szó:", " ".join(palabra_oculta))

            def adivinar_letra():
                return input("Adivina una letra: ")

            def Stickman(intentos):
                if intentos == 1:
                    print("  -------")
                    print("  |     |")
                    print("  |     O")
                    print("  |    /|\\")
                    print("  |    / \\")
                    print("  |")
                    print("=====")
                elif intentos == 2:
                    print("  -------")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 3:
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("  |")
                    print("=====")
                elif intentos == 4:
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("")
                    print("=====")

            def jugar_ahorcado():
                palabra = Palabra_Aleatoria(lista)
                palabra_oculta = ocultar_palabra(palabra)
                intentos_totales = 4
                intentos_restantes = intentos_totales

                while intentos_restantes > 0:
                    mostrar_palabra(palabra_oculta)
                    Stickman(intentos_restantes)
                    letra = adivinar_letra()
                    acierto = False
                    nueva_palabra_oculta = ""

                    for i in range(len(palabra)):
                        if palabra[i].lower() == letra.lower():
                            nueva_palabra_oculta += letra
                            acierto = True
                        else:
                            nueva_palabra_oculta += palabra_oculta[i]

                    if acierto:
                        palabra_oculta = nueva_palabra_oculta
                        print("helyes!")
                    else:
                        intentos_restantes -= 1
                        print("Helytelen. elmentél", intentos_restantes, "kísérletek.")

                    if palabra_oculta.lower() == palabra.lower():
                        print("Nyerte! Kitaláltad a szót:", palabra)
                        break

                    if intentos_restantes == 0:
                        print("Vesztettél! A szó ez volt:", palabra)

            print("játékos 1:")
            jugar_ahorcado()

```
