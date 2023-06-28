# Mrs.Stikman_Tan_tan
Proyecto final de programación de computadores.
 ### Integrantes del grupo ###
 - Maria Paula Machuca Hortua
 - Aarón Alejandro Suarez Bonilla
 - Diego Alejandro Muñoz Penna
 ### Nombre del grupo Pythonbrokers. ###
 [![logo.jpg](https://i.postimg.cc/HL4kxVwv/logo.jpg)](https://postimg.cc/4Kyg24Fp)

## Situación problema
La situación problema consiste en la necesidad de construir una aplicación en Python que emule el juego del ahorcado. El objetivo es desarrollar un programa interactivo que permita a los usuarios jugar el clásico juego del ahorcado en la consola.

La aplicación debe cumplir con las siguientes condiciones:

- Código original: Se requiere que el código de la aplicación sea escrito desde cero, utilizando las habilidades y conocimientos adquiridos en el curso.
- Uso de herramientas vistas en el curso: La aplicación debe hacer uso de las herramientas y técnicas de programación que se han enseñado en el curso de Python.
- Interacción y manejo a través de la consola: La aplicación debe permitir una interacción sencilla y amigable con el usuario a través de la consola. Esto implica que el usuario podrá ingresar letras, seleccionar el nivel de dificultad y recibir retroalimentación sobre su progreso en el juego.
- Base de datos de al menos 1000 palabras: Se requiere una base de datos que contenga una amplia variedad de palabras para que el juego pueda seleccionar una palabra aleatoria en cada partida. La base de datos debe incluir al menos 1000 palabras para asegurar la diversidad y la jugabilidad a largo plazo.
- Dibujo de hangman en integración gráfica: La aplicación debe incluir la representación visual del ahorcado a medida que el jugador comete errores en sus intentos de adivinar la palabra. 
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

# El codigo del proyecto estaria dividido en diferentes secciones 
- Primera Funcion "Palabra_Aleatoria(lista_palabras)" Esta función toma una lista de palabras como argumento y devuelve una palabra aleatoria de esa lista utilizando la función random.choice(). Es útil para seleccionar una palabra para el juego.
- Segunda Función "ocultar_palabra(palabra)" Esta función toma una palabra como argumento y devuelve una versión oculta de la palabra. La palabra oculta se representa como una secuencia de guiones bajos (_) con la misma longitud que la palabra original. Se utiliza para mostrar al jugador la palabra a adivinar inicialmente oculta.
- Tercer función "mostrar_palabra(palabra_oculta)" Esta función toma la palabra oculta como argumento y la muestra en la consola. La palabra oculta se muestra reemplazando los guiones bajos con espacios en blanco y separando cada letra por un espacio. Es útil para mostrar la palabra oculta al jugador.
- Cuarta Función "adivinar_letra()" Esta función solicita al usuario que ingrese una letra y devuelve la letra ingresada. Se utiliza para que el jugador adivine una letra.
- Quinta Función "Stickman(intentos)" Esta función dibuja un "muñeco de palitos" (stickman) en base al número de intentos proporcionados como argumento. El muñeco de palitos representa el progreso del jugador en el juego de adivinar la palabra. A medida que el número de intentos fallidos aumenta, se dibuja una parte del muñeco. Esta función se encarga de mostrar el muñeco en la consola.
### Todas estas funciones las llamaremos en la función principal

- Diagrama de flujo de la función principal anterior.
[![](https://mermaid.ink/img/pako:eNp1Vctu2zAQ_BVCpxZIgJx9KJDETdLCRZM4zUXKYUOtZSIUqfLhxnH8Vf2E_lh3SdmWY9gXG9LO7OzskF4V0tZYjIqZtn_kHFwQD-PKCPqcl-dz6yTU9kmcnn55v4pGqn9_jeicol8d6HdxUU5RaA0tCBAaxIxrrBG_IwrUqkERDQgqhWdHJRohWKfgKXe4YF5xWY7RdxG98CisjDokqg0INTaqBiGJNprcgVT0FJeJYkwUM2VUaz1DJZhAkFrUKJQJaAI9R5O0LID6P2tkPEO_lpMjAFIDugWJBgyjbXCH8KtBZ9QiKGw7SxxKKtDJN3H96XgHYm5haR25d_Y5U96UE_Yzj-K3jhKOHpEEt3WGHXFagGtiy4RcMzAuW9kL_VbqiI3Nu-ptGi5rZl3LXgsf1EtLspgcP5ITbiO-5_1eTvZ592IAtVooQ5I1snncaOAqm5pe9FwvJb2UDhPFxmgBUjlqz9gFOjVTElIq-AW6JEyL6CPV255owqkEGSJo9cbVA1eWQwUONrEwERcH2_2x8rumScFgx-gDMtpYg-tcb7gvvVT4xueBLAw0-xZCrFT0s98EZVkqqS1bLxxK6xzyUoGynu3aW-eTSOjb1VTx01yhTOPQ0wkVnU2Neh9InFANjZ_XkU6jD4mR-6jaronrLtlEDA3sKOEwQjsra17VLUHvS6-MTVZm_P7OsvLs6YbrMJk00T1xTXmkfplk5B0_qsyUvh7KwRw8xKE0OkLDSbc3zU4xi1Qt3VltHh5l4E0w_688ReesRJIMtAbPG-NARJOOK-yFPqdnTtnhZigj5BuRwD10l4-O0-XhGV2SPrwA-gp6nAwlJY_9Wo8b_2GlB1cqOffARJV5pK_X8hpMH3Zn245vY56zcXRMqeUr1Sy553YyuxftbaszDsobH0xKtSPtRymLk6JFukRUTf8mK76dqyLMscWqGNHPGtxLVVRmTXUQg50ujSxGwUU8KWJXQ8CxAuYqRjPQHtf_AcXQUxg?type=png)](https://mermaid.live/edit#pako:eNp1Vctu2zAQ_BVCpxZIgJx9KJDETdLCRZM4zUXKYUOtZSIUqfLhxnH8Vf2E_lh3SdmWY9gXG9LO7OzskF4V0tZYjIqZtn_kHFwQD-PKCPqcl-dz6yTU9kmcnn55v4pGqn9_jeicol8d6HdxUU5RaA0tCBAaxIxrrBG_IwrUqkERDQgqhWdHJRohWKfgKXe4YF5xWY7RdxG98CisjDokqg0INTaqBiGJNprcgVT0FJeJYkwUM2VUaz1DJZhAkFrUKJQJaAI9R5O0LID6P2tkPEO_lpMjAFIDugWJBgyjbXCH8KtBZ9QiKGw7SxxKKtDJN3H96XgHYm5haR25d_Y5U96UE_Yzj-K3jhKOHpEEt3WGHXFagGtiy4RcMzAuW9kL_VbqiI3Nu-ptGi5rZl3LXgsf1EtLspgcP5ITbiO-5_1eTvZ592IAtVooQ5I1snncaOAqm5pe9FwvJb2UDhPFxmgBUjlqz9gFOjVTElIq-AW6JEyL6CPV255owqkEGSJo9cbVA1eWQwUONrEwERcH2_2x8rumScFgx-gDMtpYg-tcb7gvvVT4xueBLAw0-xZCrFT0s98EZVkqqS1bLxxK6xzyUoGynu3aW-eTSOjb1VTx01yhTOPQ0wkVnU2Neh9InFANjZ_XkU6jD4mR-6jaronrLtlEDA3sKOEwQjsra17VLUHvS6-MTVZm_P7OsvLs6YbrMJk00T1xTXmkfplk5B0_qsyUvh7KwRw8xKE0OkLDSbc3zU4xi1Qt3VltHh5l4E0w_688ReesRJIMtAbPG-NARJOOK-yFPqdnTtnhZigj5BuRwD10l4-O0-XhGV2SPrwA-gp6nAwlJY_9Wo8b_2GlB1cqOffARJV5pK_X8hpMH3Zn245vY56zcXRMqeUr1Sy553YyuxftbaszDsobH0xKtSPtRymLk6JFukRUTf8mK76dqyLMscWqGNHPGtxLVVRmTXUQg50ujSxGwUU8KWJXQ8CxAuYqRjPQHtf_AcXQUxg)
- Diagrama de flujo de la ultima actualizacion de la función principal.
[![](https://mermaid.ink/img/pako:eNqFVU1v2zAM_SuCTxvQAjvnMKBt1m5D2rVN14vdAyszjlZZ8mQpa_rxq_YT9sdGSkriNAuWiwOZfHx8j6KfC2lrLEbFTNtfcg7Oi5txZQT9jsqjuXUSansnDg8_vpwGI9Wf30Z0TtG_DvSLOC6nKLSGFgQIDWLGMdaInwEFatWgCAYEhcK9oxCN4K1TcJcqHDOuOCnH2HcBe9GjsDJoH6FWSaixUTUISbDBpArEIkOcRIgxQcyUUa3tOVWC8ZRSixqFMh6Np3M0kcsCqP69Rs7n1E_lZE8CsQHdgkQDhrOtd7vpp4PKqIVX2HaWMJRUoKNumiWSDmGrfFRoBe-4YWKOVKHP2onQB4q1Yg4E1zjs2QjCO3u3nzARbWFpHZnx4X1i-LmcsD1JmX5tEOXREdVza6FZYKcFuCa0DMgxAx-SM7nvL6UO2NhkfVZ96P3MupatE71XDy3RYnB8C055K_IZ92s52cbdmiqo1UKRXEmpWGhgEnsUX2Ssh7LPwuuB7iCVo_Kcu0CnZkpCHDJ-gS4SW2ufgSbsIEgfQKunZNZaleWQgYPVlJmAi51hOX-eKs5N7FemUk7vE_k94zEYjteEZOK1Q1EryWHiR2hoOlzMWhdYsnC4qcMszin5ouyVsZs4boBCmnyF_0dhAxhNM4T4rTIX_MhDQbdUKqktT4FwKK1zyPPFvaaSW5N1JyoGufynOlZ0BDK4DrQmVENOJLLxrrB8hMh1VG1fCesqOpaaWkPC7jRvXI3yXFLqdVJnnyiJebJ3hbV7Saija8Kackt5rsi5Kz6qzJQeN-Wgj-zaG2p0m4edrnfohjGTVC1t4zY1j9LzyDL-99RF56xEogxkA6nk4mwGEzcHbN2_NMhzMpuLoQyQdj0l59TNdut40Hu4xzRww12UI-g4CkpMbrOt-4V_Y-nOx4KUu2GgytzS47E8A5PvnbNtF3cl9dk42hhU8pFillxz3ZkdUB-U-sCD8sQ7oiODiPteyOKgaJH2marpO_nM352q8HNssSpG9LcG91AVlXmlOAjeTpdGFiPvAh4UoavB41gBYxWjGegeX_8C5oiggQ?type=png)](https://mermaid.live/edit#pako:eNqFVU1v2zAM_SuCTxvQAjvnMKBt1m5D2rVN14vdAyszjlZZ8mQpa_rxq_YT9sdGSkriNAuWiwOZfHx8j6KfC2lrLEbFTNtfcg7Oi5txZQT9jsqjuXUSansnDg8_vpwGI9Wf30Z0TtG_DvSLOC6nKLSGFgQIDWLGMdaInwEFatWgCAYEhcK9oxCN4K1TcJcqHDOuOCnH2HcBe9GjsDJoH6FWSaixUTUISbDBpArEIkOcRIgxQcyUUa3tOVWC8ZRSixqFMh6Np3M0kcsCqP69Rs7n1E_lZE8CsQHdgkQDhrOtd7vpp4PKqIVX2HaWMJRUoKNumiWSDmGrfFRoBe-4YWKOVKHP2onQB4q1Yg4E1zjs2QjCO3u3nzARbWFpHZnx4X1i-LmcsD1JmX5tEOXREdVza6FZYKcFuCa0DMgxAx-SM7nvL6UO2NhkfVZ96P3MupatE71XDy3RYnB8C055K_IZ92s52cbdmiqo1UKRXEmpWGhgEnsUX2Ssh7LPwuuB7iCVo_Kcu0CnZkpCHDJ-gS4SW2ufgSbsIEgfQKunZNZaleWQgYPVlJmAi51hOX-eKs5N7FemUk7vE_k94zEYjteEZOK1Q1EryWHiR2hoOlzMWhdYsnC4qcMszin5ouyVsZs4boBCmnyF_0dhAxhNM4T4rTIX_MhDQbdUKqktT4FwKK1zyPPFvaaSW5N1JyoGufynOlZ0BDK4DrQmVENOJLLxrrB8hMh1VG1fCesqOpaaWkPC7jRvXI3yXFLqdVJnnyiJebJ3hbV7Saija8Kackt5rsi5Kz6qzJQeN-Wgj-zaG2p0m4edrnfohjGTVC1t4zY1j9LzyDL-99RF56xEogxkA6nk4mwGEzcHbN2_NMhzMpuLoQyQdj0l59TNdut40Hu4xzRww12UI-g4CkpMbrOt-4V_Y-nOx4KUu2GgytzS47E8A5PvnbNtF3cl9dk42hhU8pFillxz3ZkdUB-U-sCD8sQ7oiODiPteyOKgaJH2marpO_nM352q8HNssSpG9LcG91AVlXmlOAjeTpdGFiPvAh4UoavB41gBYxWjGegeX_8C5oiggQ)


### Espacio publicitario📽️
[![Imagen-de-Whats-App-2023-06-25-a-las-16-10-36.jpg](https://i.postimg.cc/50gScPz6/Imagen-de-Whats-App-2023-06-25-a-las-16-10-36.jpg)](https://postimg.cc/ygJZcyvH)
[![Imagen-de-Whats-App-2023-06-25-a-las-15-21-40.jpg](https://i.postimg.cc/tTbGvgd9/Imagen-de-Whats-App-2023-06-25-a-las-15-21-40.jpg)](https://postimg.cc/LqxWn20W)
