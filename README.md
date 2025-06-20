# Guardar la descripción como archivo .txt y .html
descripcion_txt = """Mi TV Station - Plataforma de Reproducción Multicanal Integrada

Mi TV Station es una plataforma web avanzada que permite a los usuarios ver miles de canales IPTV y contenidos de YouTube desde una interfaz moderna, fluida y personalizable.

Nuevas funciones destacadas:

- Carga automática de listas M3U internas
  El sistema carga automáticamente un archivo de canales predefinido con más de 10.000 entradas al iniciar la app, sin necesidad de que el usuario suba archivos manualmente.

- Buscador de canales en tiempo real
  Encuentra rápidamente tu canal favorito escribiendo su nombre o parte del mismo.

- Selector de pantalla elegante (4 pantallas)
  Al tocar cualquier canal del listado, aparece un modal visual donde puedes elegir en qué reproductor (1 a 4) quieres verlo.

- Sistema de favoritos personalizable
  Guarda tus canales preferidos con un solo clic y accede a ellos desde el panel dedicado.

- Reproducción aleatoria y control temporal
  Activa la función aleatoria para que un canal empiece desde un punto al azar o deténla cuando lo desees.

- Carga externa de archivos .m3u o .json
  También puedes subir tus propias listas personalizadas desde tu dispositivo Android, PC o navegador compatible.

- Modo adultos protegido por desbloqueo visual
  Sección de contenido para adultos oculta, accesible solo mediante acción específica del usuario.

- Estilo oscuro elegante y diseño adaptativo
  Perfecto para Smart TVs, tablets o móviles, con una interfaz limpia, moderna y cómoda para la vista.

Ideal para:
- Reproducir contenido IPTV desde varias fuentes.
- Visualizar múltiples canales en simultáneo (hasta 4).
- Centralizar listas de reproducción privadas y públicas.
- Uso doméstico, en presentaciones o para coleccionistas de canales online.
"""

descripcion_html = f"""<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Descripción - Mi TV Station</title>
  <style>
    body {{
      background-color: #111;
      color: #fff;
      font-family: Arial, sans-serif;
      padding: 2rem;
      line-height: 1.6;
    }}
    h1 {{
      color: #00ffff;
    }}
    ul {{
      margin-left: 1.5rem;
    }}
  </style>
</head>
<body>
  <h1>🛰️ Mi TV Station - Plataforma de Reproducción Multicanal Integrada</h1>
  <p>Mi TV Station es una plataforma web avanzada que permite a los usuarios <strong>ver miles de canales IPTV y contenidos de YouTube</strong> desde una interfaz moderna, fluida y personalizable.</p>

  <h2>🔧 Nuevas funciones destacadas:</h2>
  <ul>
    <li><strong>📡 Carga automática de listas M3U internas:</strong> carga automáticamente un archivo de canales con más de 10.000 entradas al iniciar.</li>
    <li><strong>🔍 Buscador de canales en tiempo real:</strong> encuentra canales rápidamente escribiendo su nombre.</li>
    <li><strong>📺 Selector de pantalla elegante (4 pantallas):</strong> elige visualmente dónde ver cada canal.</li>
    <li><strong>💾 Sistema de favoritos:</strong> guarda tus canales preferidos fácilmente.</li>
    <li><strong>🎲 Reproducción aleatoria:</strong> activa reproducción desde un punto aleatorio.</li>
    <li><strong>📁 Carga externa de archivos:</strong> permite subir tus propias listas .m3u o .json.</li>
    <li><strong>🔐 Modo adultos con desbloqueo:</strong> acceso visual protegido para contenido sensible.</li>
    <li><strong>🖼️ Estilo oscuro adaptativo:</strong> ideal para TV, móviles y tablets.</li>
  </ul>

  <h2>📦 Ideal para:</h2>
  <ul>
    <li>Reproducir contenido IPTV desde múltiples fuentes.</li>
    <li>Visualizar hasta 4 canales en simultáneo.</li>
    <li>Centralizar listas de reproducción privadas o públicas.</li>
    <li>Uso doméstico o profesional.</li>
  </ul>
</body>
</html>"""

# Guardar los archivos
txt_path = "/mnt/data/descripcion_mi_tv_station.txt"
html_path = "/mnt/data/descripcion_mi_tv_station.html"

with open(txt_path, "w", encoding="utf-8") as f:
    f.write(descripcion_txt)

with open(html_path, "w", encoding="utf-8") as f:
    f.write(descripcion_html)

txt_path, html_path
