<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Actividad Bootstrap</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous"
    />

  </head>
  <body>
    <header>
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Codo a Codo</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#"
                  >Inicio</a
                >
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled">Desactivado</a>
              </li>
            </ul>
            <form class="d-flex">
              <input
                class="form-control me-2"
                type="search"
                placeholder="Buscar"
                aria-label="search"
              />
              <button class="btn btn-outline-success" type="submit">
                Buscar
              </button>
            </form>
          </div>
        </div>
      </nav>
    </header>

    <main>
          <div class="card-group">
            <div class="card">
              <img src="
https://raw.githubusercontent.com/Furgiuele/CodoaCodo/main/Actividad%20practica%20obligatoria/html.png?token=GHSAT0AAAAAABTW3GRJGGVJBYVKCE5WP5EGYS6X2KQ
" class="card-img-top" alt="html5">
              <div class="card-body">
                <h5 class="card-title">Html</h5>
                <p class="card-text">Contenido de la tarjeta</p>
                <p class="card-text"><small class="text-muted">Ultima actualización: 1</small></p>
              </div>
            </div>
            <div class="card">
              <img src="
https://raw.githubusercontent.com/Furgiuele/CodoaCodo/main/Actividad%20practica%20obligatoria/css.png?token=GHSAT0AAAAAABTW3GRI3WYCFCUNWAHMJIZQYS6XZ5Q
" class="card-img-top" alt="CSS">
              <div class="card-body">
                <h5 class="card-title">Css</h5>
                <p class="card-text">Contenido de la tarjeta</p>
                <p class="card-text"><small class="text-muted">Ultima actualización: 1</small></p>
              </div>
            </div>
            <div class="card">
              <img src="
https://raw.githubusercontent.com/Furgiuele/CodoaCodo/main/Actividad%20practica%20obligatoria/bootstrap.png?token=GHSAT0AAAAAABTW3GRJFGALD24HX3PZ4LRIYS6X2SQ
" class="card-img-top" alt="Bootstrap">
              <div class="card-body">
                <h5 class="card-title">Bootstrap</h5>
                <p class="card-text">Contenido de la tarjeta</p>
                <p class="card-text"><small class="text-muted">Ultima actualización: 1</small></p>
              </div>
            </div>
          </div>
          <form>
            <div class="form-group">
              <label for="exampleInputEmail1">Email</label>
              <input
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
                placeholder="Ingrese su email"
              />
              <small id="emailHelp" class="form-text text-muted"
                >Nunca comparta su email.</small
              >
            </div>
            <br>

            <div class="form-group">
              <label for="exampleInputPassword1">Contraseña</label>
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Contraseña"
              />
            </div>
            <br>
            <div class="form-check">
              <input
                type="checkbox"
                class="form-check-input"
                id="exampleCheck1"
              />
              <label class="form-check-label" for="exampleCheck1"
                >Verificar</label>
               
            </div>
            <br>
            <button type="submit" class="btn btn-primary">Enviar</button>
         
        </div>
    </main>

    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
