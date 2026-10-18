# Revisión editorial del repositorio — 2026-10-18

> **Revisora:** Alejandra Medina · **Para:** Chuy · **Proyecto:** *The Jesús Fujioka Story* (fanfic de *Kanojo, Okarishimasu* / 彼女、お借りします)
>
> **Alcance:** lectura completa de los 14 archivos versionados (12 secciones de la biblia, el índice y el README), revisión de los dos pósters y verificación cruzada de los datos de producción, reparto y obra original con fuentes japonesas.
>
> **Método:** lectura línea por línea, conteo de palabras, validación de enlaces internos, cotejo de fechas, staff, tomos y capítulos, y auditoría de la lógica narrativa de la biblia (quién sabe qué, qué se promete y qué se paga).

---

## 0. Ficha técnica

| Dato | Valor |
|---|---|
| Archivos versionados | 15 de documentación (13 secciones + índice + README) + pósters |
| Palabras (aprox., *antes* de la corrección) | **25,186** |
| Palabras (aprox., *después* de la corrección) | **27,056** |
| Tamaño de la documentación (*después*) | **168,205 bytes** (~164 KB) |
| Commits al momento de la auditoría | **1** (`181c058`) |
| Líneas añadidas en el commit original | 1,555 |
| Secciones completas | 12 de 12 + la 13 en estado de stub (anunciada) |
| Enlaces internos rotos | 0 |
| Pósters | Originales de 1.4 MB y 1.3 MB; versiones de fan en WebP de **131 KB** y **93 KB** |

> **✅ Estado de aplicación (18/10/2026, misma fecha):** todos los hallazgos de las secciones 2 y 3 de este documento fueron corregidos en la biblia, el índice, el README y los pósters. El detalle de lo aplicado está al final, en la sección 11. Este documento se conserva como registro de la auditoría.

**Diagnóstico en una línea:** la biblia es un trabajo de investigación serio, bien escrito y con una columna vertebral clara; lo que todavía no existe es **la historia**. Hay mapa, no viaje. Y el mapa tiene tres o cuatro coordenadas que hay que corregir antes de dibujar la ruta.

---

## 1. Lo que ya está a nivel de publicación

No empiezo por lo que falta porque sería injusto. Esto es lo que ya funciona y que no hay que tocar:

1. **La investigación tiene profundidad real.** No es una biblia de Wikipedia resumida: hay datos de producción (el cambio de horario por COVID, el ending especial de Ruka, las dos peticiones de Miyajima al staff), de doblaje (Amamiya Sora en los PV de 2017), de música (Hyadain, halca, las canciones de personaje) y de la industria del rental dating. Eso se nota y se agradece.
2. **La estructura por episodios es utilísima para escribir.** Cada temporada tiene títulos oficiales, staff por episodio, sinopsis y notas de continuidad. Es exactamente lo que una fanfic necesita para no contradecir el canon.
3. **La tabla “quién sabe qué” de la Sección 8 es el mejor artefacto del repo.** Esa tabla es la máquina narrativa de かのかり: casi todos los giros consisten en mover a un personaje de la columna “no sabe” a la columna “sabe”. De ahí van a salir las mejores escenas del fanfic.
4. **La Sección 12 es el corazón del proyecto.** La historia de 1609 (Onjuku), 1614 (Acapulco), 1897 (Chiapas), el dato de los 3,954 mexicanos en Japón, el ajolote como puente con Kazuya, el microagravio del “日本語上手”… Esa sección no es contexto: es la tesis del fanfic. El personaje de Jesús ya tiene un lugar histórico y emocional donde pararse.
5. **La voz de la biblia es consistente.** Seria, precisa, con japonés donde aporta y sin caer en el exotismo. La frase “El corazón no se alquila… se gana” es una gran columna temática.
6. **Los pósters tienen una identidad visual clara.** El primero se lee como comedia romántica; el segundo, como drama. La playera de Chivas de Jesús es un detalle de caracterización excelente: dice de dónde viene sin que nadie lo explique.

---

## 2. Hallazgos críticos (corregir antes de seguir)

### 2.1. El director de la T3 no fue Koga Kazuomi

**Dónde está el error:** `biblia/01-historia-produccion.md:60-61` afirma que el estudio, el departamento y el director son “el mismo trío en TODAS las temporadas (1 a 5)”, y presenta a **Koga Kazuomi** como director sin excepción. La Sección 4 (T3) no lo desmiente: no incluye una línea de dirección en su encabezado y, en cambio, acredita a Une Nobuya en varios episodios.

**Lo que dicen las fuentes:** la T3 (2023) tuvo como director a **Une Nobuya (宇根信也)**. Koga dirigió T1, T2, T4 y T5; regresó para la T4. La propia biblia lo delata sin querer: en `biblia/04-temporada-iii.md:15, 21, 81`, varios episodios de la T3 están acreditados con **Une Nobuya en storyboard y/o dirección**. Eso no es casualidad: era el director de la temporada.

**Evidencia:**
- Wikipedia japonesa, ficha de staff: “監督: 古賀一臣（第3期を除く） / 宇根信也（第3期）”.
- Anime Hack, ficha de la T3: “監督: 宇根信也”.
- Anime Hack, nota del 18 de febrero de 2023: “「彼女、お借りします」第3期、7月放送開始 **監督が宇根信也に変更**”.
- Animate Times y Natalie, fichas de staff de la T3: dirección de **宇根信也**.

**Corrección propuesta:**
- En `01-historia-produccion.md`, cambiar el bloque de equipo por: “Director: **Koga Kazuomi** (T1, T2, T4, T5) y **Une Nobuya** (T3). Koga regresó para la T4.”
- En la tabla de temporadas, añadir una columna “Dirección” o una nota al pie.
- En `04-temporada-iii.md`, añadir en el encabezado: “Dirección: **Une Nobuya**; Koga regresa en la T4.”
- Revisar la frase “mismo trío en todas las temporadas”: es una simplificación que ya no se sostiene.

**Por qué importa:** no es un dato de trivia. La T3 es la temporada más comprimida y la que más cambia de tono (el arco de la película, la muerte de Sayuri). Saber que la dirigió otra persona ayuda a explicar por qué se siente distinta. Y si el fanfic va a citar “el estilo Koga”, necesita saber cuándo Koga no estaba.

### 2.2. “Mismo trío en todas las temporadas” y Studio Comet

**Dónde está:** `01-historia-produccion.md:60`.

**Matiz:** TMS Entertainment (6.º estudio) sí es constante en las cinco temporadas. **Studio Comet** aparece como “cooperación de animación” en T1 y T3 (Animate Times la acredita expresamente en la T3); en las fichas oficiales de T4 y T5 no aparece con el mismo rango. La frase “es el mismo trío estudio/departamento en TODAS las temporadas” es, como mínimo, una afirmación que hay que verificar temporada por temporada antes de dejarla escrita.

**Corrección propuesta:** “TMS Entertainment (6.º estudio) en las cinco temporadas; Studio Comet como cooperación en T1 y T3 (verificar T2, T4 y T5).”

### 2.3. La música de la T3: Hyadain no está solo

**Dónde está:** `01-historia-produccion.md:64` y los encabezados de “staff sin cambios” de T4/T5.

**Matiz:** el sitio oficial acredita a **Hyadain** como compositor principal, pero las bases de datos de staff de la T3 y la ficha de Wikipedia añaden a **Itagaki Yūsuke (板垣祐介)**, **Otake Tomoyuki (大竹智之)** y **Tsukada Tadaaki (塚田忠昭)** en la música de esa temporada. No es un error de fondo, pero “staff sin cambios” es una simplificación que un lector técnico va a notar.

**Corrección propuesta:** “Música: Hyadain como compositor principal; la T3 suma a Itagaki, Otake y Tsukada en la ficha de staff.”

### 2.4. La fila de Kuribayashi en la tabla “quién sabe qué”

**Dónde está:** `biblia/08-personajes-secundarios.md:187`.

La fila dice: “Kuribayashi | Chizuru es rental; Ruka era rental | El double date (T1) y el ‘date de recepción’ (T2)”. El problema es que **el double date de la T1 fue con Ruka**, no con Chizuru. Kuribayashi supo que **Ruka** era rental en ese double date; supo que **Chizuru** era rental en el “date de recepción” de la T2. La prosa de la misma sección (líneas 25-35) lo explica bien; la tabla lo mezcla.

**Corrección propuesta:** separar en dos hechos o reescribir la fila: “Ruka era rental (double date, T1); Chizuru es rental (date de recepción, T2).” Es un detalle pequeño, pero esa tabla es una herramienta de escritura: si está imprecisa, las escenas de “quién descubre qué” se pueden escribir mal.

### 2.5. El estado del manga: 443 vs. 444

**Dónde está:** `biblia/09-anime-vs-manga.md:7, 15, 70, 103` y `11-datos-curiosos.md:21`.

El repo dice que el manga va por **満足度443 “前日と彼女”** (2026年45号). En la fecha de esta revisión, Magapoke ya muestra **満足度444 “ラーメンと彼女①”**. No es un error grave (443 existió y el texto está fechado), pero conviene actualizar a “443-444” o “444 en curso” y poner una fecha de corte explícita (“estado al 18 de octubre de 2026”). En un documento que se va a citar durante meses, la fecha de corte es parte de la precisión.

### 2.6. El póster y la línea de copyright oficial

**Dónde está:** `assets/poster.png` incluye la leyenda “©宮島礼吏・講談社／「彼女、お借りします」製作委員会2025” y el texto “放送決定！” (“¡emisión confirmada!”), además del logo oficial de la obra.

**Por qué conviene revisarlo:** un fanfic puede usar personajes con un disclaimer claro, pero **no debe presentarse como material licenciado ni anunciar una emisión oficial**. Esa línea y el “放送決定” hacen que el póster parezca una pieza promocional de la franquicia.

**Corrección aplicada (revisada tras conversación con Chuy):** **el arte es de Chuy y se respeta tal como lo creó.** No se edita la imagen. El disclaimer va en **texto**, en el README y en la sinopsis de Wattpad:
> “Fan art no oficial — homenaje a 彼女、お借りします. Personajes y obra original ©宮島礼吏・講談社. Sin afiliación ni fines comerciales.”

Si en algún momento se quiere una versión sin el texto japonés ni el logo, se hace **una pieza nueva** y con su aprobación, nunca retocando la original.

### 2.7. El README no está a la altura de la biblia

**Dónde está:** `README.md:1-17`.

El README actual son dos imágenes de 500 px, el título, una línea de subtítulo y el tagline. No tiene:
- sinopsis de la historia;
- índice de la biblia;
- estado del proyecto (qué está listo, qué falta);
- disclaimer de fanfic;
- créditos y fuentes;
- instrucciones para leer/navegar el repo.

**Corrección propuesta:** reescribirlo con esta estructura:
1. Título + tagline.
2. Póster principal (uno solo, comprimido).
3. Sinopsis de 150-200 palabras.
4. Estado del proyecto (tabla: biblia ✅, ficha de Jesús ⏳, outline ⏳, capítulo 1 ⏳).
5. Índice de la biblia (enlace a `biblia/README.md`).
6. Disclaimer de fanfic.
7. Créditos y fuentes.

### 2.8. La Sección 13 está anunciada pero no existe

**Dónde está:** `biblia/README.md:19`: “13. Temporada VI (同棲編) — cuando se emita (⏳ pendiente)”.

No hay archivo `13-temporada-vi.md`. En la fecha de esta revisión, la T6 ya está **confirmada** (anuncio del 26/27 de junio de 2026, tras el episodio 60), con el arco 同棲編. Recomiendo crear un stub con los datos confirmados (staff, estudio, arco, fecha de anuncio) y marcar lo demás como “por emitir”. Así el índice no promete un archivo inexistente y el fanfic tiene un lugar donde crecer.

---

## 3. Hallazgos medios (estilo, precisión, navegación)

| # | Hallazgo | Dónde | Fix |
|---|---|---|---|
| 3.1 | “Elrodaje” (sin espacio) | `01-historia-produccion.md:87` | “El rodaje” |
| 3.2 | Fechas de T4/T5: se usa la fecha calendario de la madrugada (sábado) pero se describe como “viernes 2:23 a.m.” | `05-temporada-iv.md:3`, `06-temporada-v.md:3` | Añadir una nota: “fecha de emisión en TV; la madrugada del viernes corresponde al sábado calendario” |
| 3.3 | El “tomo 20 compartido” entre T3 y T4 parece un error y no lo es | `09-anime-vs-manga.md:32-33` | Añadir nota: “el tomo 20 contiene el cierre de T3 (cap. 167) y la apertura de T4 (cap. 168)” |
| 3.4 | Pósters de 1.5 MB y 1.3 MB en el README | `assets/` | Comprimir a WebP (~200-300 KB) y usar uno solo como hero |
| 3.5 | El índice no tiene fecha de versión ni “cómo usar esta biblia” | `biblia/README.md` | Añadir “Versión 1.0 — 18/10/2026” y una guía de 4 pasos |
| 3.6 | “16 millones de ejemplares” y “47 tomos” están bien, pero sin fecha de corte | `01`, `09`, `11` | Añadir “(octubre de 2026)” en cada mención |
| 3.7 | El mapa de relaciones en ASCII es difícil de leer en móvil | `07-personajes-principales.md` | Reemplazar por un diagrama Mermaid o una tabla de relaciones |
| 3.8 | No hay glosario de términos japoneses | todo el repo | Crear `biblia/13-glosario.md` o un anexo con 30 términos (レンカノ, 仮カノ, 満足度, 同棲, 遺品整理, etc.) |
| 3.9 | La ley de nacionalidad está simplificada: la biblia dice “al llegar a la mayoría de edad” | `12-hafu-extranjeros-japon.md` | Precisar: desde 2022 la mayoría es 18, pero el plazo de elección es **a los 20** si la doble nacionalidad se adquirió antes de los 18 (o 2 años después de adquirirla). Para Jesús, el reloj es su cumpleaños 20. |

---

## 4. El hueco estructural: no hay historia

Esto es lo más importante de toda la revisión, y lo digo con cariño: **el repo se llama “Rent-a-Girlfriend”, el README promete “The Jesús Fujioka Story”, pero no hay un solo capítulo, ni una sinopsis, ni un outline, ni una ficha de Jesús.** Hay una biblia de investigación excelente; falta la biblia de la historia.

### 4.1. Lo que falta, en orden de urgencia

1. **Ficha de Jesús Fujioka Hernández.** La Sección 12 da el contexto cultural, no al personaje. Faltan: edad, universidad, carrera, familia (padre japonés, madre mexicana, abuela materna, abuela paterna), herida, deseo, miedo, mentira, virtud, defecto, voz, trabajo, nivel de japonés, situación migratoria, nacionalidad, hobby (ajolote/acuario), relación con México y con Japón.
2. **Decisión de canon.** ¿El fanfic es un insert que respeta T1-T5? ¿Una línea divergente? ¿Post-T5? ¿AU? Sin esta decisión, cada capítulo va a pelear con el canon.
3. **Premisa en una frase.** “Un hāfu mexicano que trabaja en una agencia de alquiler de familias conoce a la rental girlfriend más famosa de Nerima y descubre que los dos venden lo mismo: la sensación de no estar solo.” Algo así. Una frase que se pueda decir en voz alta.
4. **Sinopsis de 150-200 palabras** para Wattpad.
5. **Outline de la primera temporada** (12 capítulos, 4,500 palabras cada uno = ~54,000 palabras).
6. **Guía de voces** (cómo habla cada personaje, con 5 líneas de muestra).
7. **Hoja de continuidad** (fechas, quién sabe qué, props, dinero, promesas).
8. **Disclaimer y créditos** (ver 2.6).

### 4.2. La ventana temporal que recomiendo

La biblia dice que el canon de referencia es el anime hasta la T5 y que el manga sigue desde el tomo 30. Pero para un insert, la mejor ventana no es después de la T5: es **entre la T3 y la T4**, en el hueco que va de la muerte de Sayuri al viaje a Hawaiians.

¿Por qué?
- La mentira sigue viva (el motor de la serie).
- El elenco ya está completo (Mini incluida).
- Kazuya está en duelo y Chizuru está distante: hay espacio emocional para un personaje nuevo.
- Ruka está en tregua; Mami todavía no ha lanzado su ofensiva final; la abuela Nagomi está viva y feliz.
- El viaje a Hawaiians es un evento futuro que puede funcionar como clímax de temporada sin tener que reescribir la T4.

Esto se llama **“canon-divergente controlado”**: el fanfic respeta T1-T3, inserta a Jesús en el hueco, y al final de su temporada 1 puede reconciliarse con el canon (Jesús se va, o se queda pero la historia principal sigue) o divergir con consecuencias. Es la opción más segura y la más rica.

---

## 5. Decisiones creativas que te tocan (con mi recomendación)

### 5.1. ¿Quién es Jesús en el mundo del rental?

| Opción | Premisa | Pros | Contras |
|---|---|---|---|
| **A. El cliente accidental** | Jesús renta a Chizuru para una cena familiar y queda atrapado en la mentira. | Entrada directa; paralelismo con Kazuya; comedia inmediata. | Repite la premisa original; riesgo de ser “Kazuya 2.0”. |
| **B. El vecino del 205** | Jesús se muda al edificio y ve las idas y venidas de los 202-203-204. | Mirada externa fresca; comedia de vecindad; puede ser el único que ve la verdad. | Protagonista pasivo; necesita una trama propia. |
| **C. El rental boyfriend** | Jesús trabaja en una agencia de novios de alquiler; coincide con Chizuru como colega. | Espejo temático perfecto; original; explora el lado masculino de la industria. | Requiere investigación; riesgo de tono; puede caer en cliché. |
| **D. El hijo de alquiler** (mi recomendación) | Jesús trabaja en una agencia de **familias de alquiler** (レンタル家族): le pagan por ser el hijo, el nieto o el hermano perfecto de gente sola. | Espejo perfecto con Chizuru y con la mentira de Kazuya; tema de la soledad y la familia; original; permite escenas íntimas sin romance forzado. | Hay que documentar la industria; el tono debe ser cuidadoso. |

**Recomendación:** **D + B**. Jesús vive en el 205 y trabaja en una agencia de familias de alquiler. Así tiene agencia (trabajo), proximidad (vecindad) y un espejo temático con Chizuru (los dos actúan el afecto por dinero). No es un rival de Kazuya: es un colega de oficio y un vecino incómodo.

### 5.2. El medidor de los capítulos

El canon numera con **満足度** (“grado de satisfacción”), como si cada capítulo fuera una reseña de rental girlfriend. El fanfic necesita su propio contador. Mi propuesta: **共感度 (kyōkando, “grado de empatía”)**, porque mide lo contrario que la agencia: no qué tan satisfecho sale el cliente, sino qué tan cerca están dos personas. Ejemplo: “共感度1 — El chico del ajolote”. Es un guiño al canon sin copiarlo.

### 5.3. El título

“The Jesús Fujioka Story” funciona como título de trabajo, pero para Wattpad en español es frío y en inglés. La frase que ya tienes es mejor título que el título: **“El corazón no se alquila”**. Propongo:

- **Título:** *El corazón no se alquila*
- **Subtítulo:** *The Jesús Fujioka Story*
- **Tagline:** “El corazón no se alquila… se gana.”

Alternativas: *Renta de corazón* (más suave), *El chico del 205* (misterioso), *Mil grullas y un ajolote* (poético, pero opaco). La primera es la más fuerte.

### 5.4. El reloj de la nacionalidad

Japón no reconoce la doble nacionalidad en la adultez: quien la tiene debe elegir. El plazo actual (desde la reforma de 2022) es **a los 20 años** si la doble nacionalidad se adquirió antes de los 18; si se adquirió después, es de dos años desde ese momento. Para Jesús, que tiene 20, el reloj no es futuro: **ya está encima**. Su cumpleaños 20 puede ser el deadline de la temporada 1. Su madre mexicana quiere que conserve la mexicana; su abuela paterna japonesa quiere que conserve la japonesa; él no quiere elegir porque elegir es renunciar a una mitad. Eso es un conflicto personal que no depende de Chizuru, y que hace que Jesús sea protagonista, no satélite.

### 5.5. El romance

No recomiendo convertirlo en “el quinto pretendiente” de Chizuru. La serie ya tiene cuatro heroínas y un protagonista; añadir un rival romántico directo desequilibra la balanza y hace que el fanfic se sienta como una invasión. Mejor:
- **Jesús y Chizuru:** un vínculo de espejo, complicidad y casi-algo, con una tensión que no se resuelve en la temporada 1. Si hay romance, que sea lento, consciente de que Chizuru ya está enredada con Kazuya, y que no la convierta en premio.
- **Jesús y una clienta/o:** un romance con una persona fuera del elenco canon (una clienta de la agencia de familias, una compañera de trabajo, una estudiante mexicana en Tokio) puede darle a Jesús una vida propia.
- **Jesús y Kazuya:** la amistad masculina es el gran tema no explotado de かのかり. Dos hombres que mienten para proteger a sus abuelas, que se admiran y se envidian, es una mina de oro.

### 5.6. El tono

かのかり es comedia romántica con un fondo de soledad y duelo. El fanfic debe respetar ese equilibrio: **70% comedia de enredos, 30% drama emocional**, con los mismos recursos (monólogo interno, cliffhangers, escenas de comida, balcones, lluvia, trenes). Si se va todo al drama, traiciona la obra; si se va todo a la comedia, traiciona a Jesús.

---

## 6. Propuesta de Temporada 1 (12 capítulos, ~4,500 palabras cada uno)

| Cap. | Título | Beat principal | Cliffhanger |
|---|---|---|---|
| 1 | 共感度1 — El chico del ajolote | Jesús llega al 205; conoce a Kazuya en la tienda de acuarios; su ajolote se escapa y Chizuru lo encuentra. | Chizuru lo saluda por su nombre de agencia: “Mizuhara”. |
| 2 | 共感度2 — El hijo de alquiler | Primer trabajo de Jesús en la agencia de familias; interpreta al hijo de una viuda. Ve a Chizuru en un date de alquiler. | Los dos se reconocen y ninguno dice nada. |
| 3 | 共感度3 — La cena de los Fujioka | La abuela paterna le exige novia; Jesús renta a Chizuru. | Chizuru acepta… con una condición. |
| 4 | 共感度4 — Las reglas del 204 | Chizuru le pone reglas; Jesús descubre que es la vecina de Kazuya; Mini los espía. | Mini ya sabe que Jesús sabe. |
| 5 | 共感度5 — El doble date | Kazuya, Chizuru, Jesús y Ruka en un doble date; las mentiras se multiplican. | Ruka huele a un rival y ataca. |
| 6 | 共感度6 — La abuela de Guadalajara | Llamada de México: la salud de su abuela; el reloj de la nacionalidad. | Jesús miente a su familia sobre su vida en Tokio. |
| 7 | 共感度7 — La película de Sayuri | Jesús ve la película de Chizuru; llora; ella lo ve. | La primera conversación honesta. |
| 8 | 共感度8 — El anillo de Nagomi | Nagomi confunde a Jesús con un pariente; la mentira familiar se espesa. | Kazuya entra en pánico. |
| 9 | 共感度9 — La noche de las grullas | Jesús y Chizuru hacen senbazuru y hablan de sus abuelas. | Casi beso; Chizuru se retira. |
| 10 | 共感度10 — El cliente del hijo | Una clienta le pide a Jesús que interprete a su hijo muerto; no puede. | Chizuru lo ayuda; los dos se ven al desnudo. |
| 11 | 共感度11 — El secreto del 203 | Jesús descubre la mentira familiar; Mami se le acerca. | Debe elegir: decir la verdad o proteger a Kazuya. |
| 12 | 共感度12 — Lo que no se alquila | Clímax en el festival de verano; Jesús confiesa su propia mentira; Chizuru confronta la suya. | Invitación al viaje a Hawaiians; temporada 2. |

**Nota:** los capítulos 1-4 son de instalación; 5-8, de enredo; 9-12, de revelación. Cada capítulo debe tener **4-5 escenas**, **un monólogo interno** y **un cliffhanger**. La meta de 4,500 palabras es ambiciosa para Wattpad; recomiendo publicar en “partes” de 2,000-2,500 palabras dentro de cada capítulo, con un corte en el punto de tensión.

---

## 7. Guía de voces (muestra)

| Personaje | Registro | Línea de muestra |
|---|---|---|
| **Jesús** | Primera persona, ironía suave, español mexicano de Guadalajara; japonés neutro con algún tropiezo de kanji. | “No es que no extrañe México. Es que aquí aprendí a extrañarlo en silencio.” |
| **Chizuru** | Dos registros: Mizuhara (dulce, profesional) e Ichinose (seca, honesta). | “No estoy actuando. Es peor: estoy siendo amable.” |
| **Kazuya** | Monólogo ansioso, frases entrecortadas, culpa. | “Yo solo quería que mi abuela fuera feliz. ¿En qué momento eso se volvió una deuda?” |
| **Ruka** | Ráfagas, exclamaciones, corazón en la manga. | “¡No me digas que no siento! ¡Si mi corazón no late rápido, es porque tú no estás!” |
| **Mami** | Doble discurso: dulce en público, quirúrgica en privado. | “No te estoy amenazando. Te estoy describiendo.” |
| **Mini** | Jerga de internet, “-ssu”, entusiasmo. | “¡Shishō! ¡Esto es material de primera! ¡Voy a hacer un hilo!” |
| **Sumi** | Casi sin palabras; gestos, cuaderno, pulgar arriba. | (Escribe en su cuaderno: “Yo también quiero ayudar.”) |

---

## 8. Plan de entregas

| Entrega | Contenido | Tiempo estimado |
|---|---|---|
| **D1** | Correcciones factuales de la biblia + README + disclaimer + índice + stub T6. | 1 sesión |
| **D2** | Ficha de Jesús (30 preguntas) + árbol familiar + línea de tiempo personal. | 1 sesión |
| **D3** | Matriz de canon + premisa + sinopsis de 300 palabras. | 1 sesión |
| **D4** | Outline de la Temporada 1 (12 capítulos, beats, cliffhangers). | 1 sesión |
| **D5** | Capítulo 1 (4,500 palabras) + guía de voces completa. | 2-3 sesiones |
| **D6** | Hoja de continuidad + glosario + estrategia de Wattpad. | 1 sesión |

**Mi recomendación de orden:** D1 (porque los errores factuales se propagan), D2 (porque sin Jesús no hay historia), D3 (porque sin canon no hay brújula), D4, D5, D6.

---

## 9. Preguntas para Chuy

1. ¿El fanfic es un insert que respeta el canon o una línea divergente? ¿Te late la ventana entre T3 y T4?
2. ¿Jesús es cliente, vecino, rental boyfriend o hijo de alquiler? ¿Te convence la opción D + B?
3. ¿Quieres romance entre Jesús y Chizuru, o un vínculo de espejo/amistad que no rompa la pareja canónica?
4. ¿Mantemos “The Jesús Fujioka Story” o pasamos a “El corazón no se alquila”?
5. ¿Empiezo por las correcciones de la biblia o por la ficha de Jesús?

---

## 10. Fuentes de la revisión

- Wikipedia japonesa — 彼女、お借りします (staff por temporada, fechas, música, volúmenes, ventas): https://ja.wikipedia.org/wiki/彼女、お借りします
- Anime Hack — ficha de la T3 (dirección de Une Nobuya): https://anime.eiga.com/program/110665/
- Animate Times — ficha de la T3 (staff y emisión): https://www.animatetimes.com/tag/details.php?id=17488
- Natalie — ficha de la T3 (staff): https://natalie.mu/comic/anime/723
- Animate Times — ficha de la T5 (staff, fechas, OP/ED): https://www.animatetimes.com/tag/details.php?id=26827
- Sitio oficial de la T5: https://kanokari-official.com/
- Animate Times — final de la T5 (満足度60): https://www.animatetimes.com/news/details.php?id=1782123144
- Animate Times — anuncio de la T6 (同棲編): https://www.animatetimes.com/news/details.php?id=1782457542
- Anime Hack — anuncio de la T6: https://anime.eiga.com/news/126863/
- Magapoke — 満足度443: https://pocket.shonenmagazine.com/title/00289/episode/445047
- Animate Times — listado de tomos y sinopsis: https://www.animatetimes.com/news/details.php?id=1598245407
- Real Sound — efecto sinérgico anime/manga: https://realsound.jp/movie/2020/08/post-609003.html
- レンタル彼女®PREMIUM【東京】 — la agencia real: https://rentalkanojo.com/
- Secciones 1-12 de la biblia del repo (lectura completa).

---

*Revisión editorial — Alejandra Medina · 18 de octubre de 2026*

---

## 11. Registro de correcciones aplicadas

| # | Hallazgo | Archivo(s) corregido(s) | Estado |
|---|---|---|---|
| 2.1 | Dirección de la T3 (Une Nobuya, no Koga) | `01` (equipo + tabla con columna "Dirección"), `02`, `03`, `04`, `05`, `06` | ✅ |
| 2.2 | "Mismo trío en todas las temporadas" / Studio Comet | `01` | ✅ |
| 2.3 | Música de la T3 (Itagaki, Otake, Tsukada) | `01`, `04` | ✅ |
| 2.4 | Fila de Kuribayashi en la tabla "quién sabe qué" | `08` (dos filas separadas) | ✅ |
| 2.5 | Estado del manga (443 → 444) | `09`, `11` y ficha técnica del índice | ✅ |
| 2.6 | Póster con copyright y "放送決定" | README (disclaimer en texto); **los pósters originales se conservan sin editar** | ✅ |
| 2.7 | README sin sinopsis, índice ni disclaimer | `README.md` reescrito | ✅ |
| 2.8 | Sección 13 anunciada sin archivo | `biblia/13-temporada-vi.md` (stub) + índice actualizado | ✅ |
| 3.1 | "Elrodaje" | `01` | ✅ |
| 3.2 | Convención de fechas T4/T5 | `05`, `06` | ✅ |
| 3.3 | Tomo 20 compartido T3/T4 | `09` (nota explicativa) | ✅ |
| 3.4 | Pósters de 1.4 MB | versiones WebP de ~130 KB y ~93 KB | ✅ |
| 3.5 | Índice sin fecha ni guía de uso | `biblia/README.md` (versión 1.1 + "cómo usar") | ✅ |
| 3.6 | Fechas de corte ausentes | `01`, `09`, `11` | ✅ |
| 3.8 | Glosario | pendiente (propuesto como entrega D6) | ⏳ |
| 3.9 | Ley de nacionalidad simplificada | `12` (plazo de 20 años + 催告) | ✅ |
| — | Bradicardia de Ruka (precisión médica) | `02`, `07` | ✅ |
| — | Cobertura T2 (~96 → 103) y T5 (tomos 25-30) | `03`, `06`, `09` | ✅ |

**Pendiente por decisión de Chuy:** el glosario (3.8) y la sustitución del mapa ASCII por un diagrama (3.7).

**Nota de proceso:** las versiones retocadas de los pósters (`*-fan.*`) se eliminaron del repo el 18/10/2026. Fue un error de mi parte intervenir el arte original sin consultarlo; queda registrado aquí para que no se repita.

---

*Fin del registro — revisión editorial cerrada el 18 de octubre de 2026.*
