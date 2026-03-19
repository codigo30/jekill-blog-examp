---
layout: default
title: Inicio
---

<div class="container-fluid" style="background: linear-gradient(135deg, #004200 0%, #006600 100%); height: 100px; display: flex; align-items: center; justify-content: center;">
  <h2 class="text-white text-center m-0">Huellas de Barrio</h2>
</div>

<div class="container" style="padding: 30px 15px">
  <div class="row">
    <div class="col-12 text-center mb-5">
      <h1 style="color: #004200; font-weight: bold;">Bienvenidos</h1>
      <p style="font-size: 18px; color: #555;">
        Grupo de investigación Medio Ambiente y Sociedad - MASO<br>
        Facultad de Ciencias Sociales y Humanas - Universidad de Antioquia
      </p>
    </div>
  </div>

  <div class="row">
    <div class="col-lg-4 col-md-6 mb-4">
      <div class="card h-100" style="border: none; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); border-radius: 8px;">
        <div class="card-body">
          <h3 style="color: #004200;">Investigación</h3>
          <p>Proyectos de investigación participativa en barrios populares enfocados en la apropiación social del territorio.</p>
          <a href="{{ '/blog/' | relative_url }}" class="btn btn-green">Ver más</a>
        </div>
      </div>
    </div>

    <div class="col-lg-4 col-md-6 mb-4">
      <div class="card h-100" style="border: none; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); border-radius: 8px;">
        <div class="card-body">
          <h3 style="color: #004200;">Memoria Urbana</h3>
          <p>Reconstrucción colectiva de la memoria mediante recorridos territoriales en barrios populares.</p>
          <a href="{{ '/blog/' | relative_url }}" class="btn btn-green">Ver más</a>
        </div>
      </div>
    </div>

    <div class="col-lg-4 col-md-6 mb-4">
      <div class="card h-100" style="border: none; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); border-radius: 8px;">
        <div class="card-body">
          <h3 style="color: #004200;">Transformación Social</h3>
          <p>Análisis de dinámicas de urbanización, participación y transformación en contextos urbanos.</p>
          <a href="{{ '/blog/' | relative_url }}" class="btn btn-green">Ver más</a>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
.btn-green {
  background-color: #33cc66;
  color: white;
  padding: 12px 24px;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
  display: inline-block;
}

.btn-green:hover {
  background-color: #28a745;
  color: white;
  transform: scale(1.05);
  transition: all 0.3s ease;
}
</style>
