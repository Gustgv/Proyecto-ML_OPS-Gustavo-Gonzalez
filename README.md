Proyecto Individual - Data Engineer
Licenciado: Gustavo Rafael Gonzalez

En este README encontrarán toda la documentación, e instrucciones necesarias, para poder utilizar la API que se me solicitó desarrollar.

Video explicativo

🟣 MENU: 🟣

Raw - las bases de datos que recibí para trabajar.
ML_proyecto.ipynb - notebook del proyecto de Machine Learning
transformacion.ipynb - notebook que contiene el trabajo de ETL de los datos
querys.ipynb - notebook que contienen el proceso de desarrollo de las queries.
rating_data.parquet - dataset que contiene registros de rating de peliculas por usuario.
movie_data.csv - dataset con tiene peliculas por plataforma como netfli, disney, entre otros.

🟣 Las funciones que componen la API son: 🟣

🔹 get_max_duration: Consulta de pelicula con mayor duration, expresado en min o season.
🔹 get_score_count: Conteo de peliculas por plataforma con un puntaje mayor a X valor en determinado año.
🔹 get_count_platform: Conteo de películas por plataforma.
🔹 get_actor: Presentar el actor que mas se repite segun plataforma y año.

🟣 Cómo escribir cada función en el navegador: 🟣

◽ https://twj1kq.deta.dev/get_word_count/{plataforma}/{keyword}
◽ https://twj1kq.deta.dev/get_score_count/{plataforma}/{puntaje}/{ano}
◽ https://twj1kq.deta.dev/get_second_score/{plataforma}
◽ https://twj1kq.deta.dev/get_longest/{plataforma}/{duration_type}/{ano}
◽ https://twj1kq.deta.dev/get_rating_count/{rating}

🟣 Queries de ejemplo para probar la api 🟣

◽ https://twj1kq.deta.dev/get_word_count/netflix/love
◽ https://twj1kq.deta.dev/get_score_count/netflix/85/2010
◽ https://twj1kq.deta.dev/get_second_score/amazon
◽ https://twj1kq.deta.dev/get_longest/netflix/min/2016
◽ https://twj1kq.deta.dev/get_rating_count/18+

⚠️ Sintaxis a tener en cuenta al escribir una consulta: ⚠️
🔹 Todo debe estar escrito en minúsculas.
🔹 Las plataformas que admite son: Amazon, Disney, Hulu y Netflix.
🔹 Evite utilizar caracteres hispanos.
🔹 En caso de la query no arroje resultados, un mensaje explicativo se imprimirá en pantalla.
🔹 En caso de que se ingrese una plataforma inválida, un mensaje explicativo se imprimirá en pantalla.

🟣 Funciones extra 🟣
🔹 Función Presentación: /
Simplemente invocando el link vacío, muestra el nombre y a quien pertenece la api.
🔹 Función menú: /menu
Muestra una lista de las funciones disponibles para consultar.
🔹 Función Contacto: /contacto
Muestra dos maneras de contactar conmigo, en caso de necesidad.
🔹 Función docs: /docs
Muestra el menú principal de la api, donde también se puede testear las consultas.

🟣 Notas finales: 🟣
😇 Muchas gracias por testear mi api!
Todo el feedback es bien recibido. ☕
