<div class="header clearfix">
    <nav class="navbar navbar-toggleable-md navbar-inverse fixed-top navbar-propio">
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <a class="navbar-brand" href="{{"/"}}">CodeLabora</a>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item {{%if page.url == "/"}}active{{%endif}}"">
            <a class="nav-link " href="{{"/"}}">Inicio </a>
          </li>
          <li class="nav-item {{%if page.url == "/nosotros"}}active{{%endif}}">
            <a class="nav-link " href="{{"/nosotros"}}">Nosotros </a>
          </li>
          <li class="nav-item {{%if page.url == "/participa"}}active{{%endif}}">
            <a class="nav-link " href="{{"/participa"}}">Participa</a>
          </li>
          <li class="nav-item {{%if page.url == "/contacto"}}active{{%endif}}">
            <a class="nav-link " href="{{"/contacto"}}">Contacto</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
