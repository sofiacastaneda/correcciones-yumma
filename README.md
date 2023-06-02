# correcciones-yumma

# TODO
[] Añadir pin a página login <br>
[x] Cambiar el botón menú hamburguesa (ícono) por botón con la palabra menú en *todas* las pantallas<br>
[x] Cambiar el favicon en *todas* las pantallas<br>
[x] Ajustar ameba seguimientos por dupla anual<br>
[x] Ajustar ameba seguimientos por dupla mensual<br>
[x] Ajustar ameba seguimientos a crónicos<br>
[x] Ajustar ameba canalizaciones anual<br>
[x] Ajustar ameba canalizaciones mensual<br>
[x] Ajustar amebas total de evaluacion de riesgo por beneficiarios<br>
[x] Ajustar amebas total de canalizaciones por beneficiarios<br>
[x] Ajustar amebas desglose actividades por beneficiarios<br>
[x] Ajustar amebas datos cruzados salarios mínimos<br>
[x] Ajustar amebas datos cruzados discapacidad<br>


________________________________________

# Log de cambios

## 1. Ajuste botón menú de hamburguesa *TODAS* las pantallas
### Modificación en el archivo HTML:
AÑADIR:
<div class="rectangle-172"></div>
<div class="men calibri-bold-black-16px">
<span class="calibri-bold-black-16px">MENÚ</span></div>
<div class="men calibri-bold-black-16px"><span class="calibri-bold-black-16px">MENÚ</span></div>
ELIMINAR:
<div class="rectangle-173"></div>
<div class="rectangle-174"></div>
<div class="rectangle-175"></div>

### Modificación en el archivo CSS de cada pantalla:
.//nombre del archivo// .rectangle-172 {
  background-color: var(--white);
  border-radius: 29px;
  box-shadow: 0px 4px 4px #00000040;
  height: 87px;
  left: 44px;
  position: absolute;
  top: 0;
  width: 96px;
}
.//nombre del archivo// .men {
  left: 46px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 48px;
  white-space: nowrap;
  width: 89px;
}
### Nota: asegurarse de que la siguiente clase se encuentra en la hoja de estilos *styleguide.css*
.calibri-bold-black-16px {
  color: var(--black);
  font-family: var(--font-family-calibri-bold);
  font-size: var(--font-size-m);
  font-style: normal;
  font-weight: 700;
}

## 2. Cambiar favicon en *TODAS* las pantallas
### Modificación archivo HTML:
REEMPLAZAR:
<link rel="shortcut icon" type="image/png" href="https://animaproject.s3.amazonaws.com/home/favicon.png" />
POR:
<link rel="shortcut icon" type="image/png" href="img/favicons/favicon-192.png" />


## 3. Ajuste tamaño amebas pantalla de datos total de seguimientos por dupla anual
Para aplicar en el doc: 6-1-1-seguimientos-dupla-anual.html
Archivos modificados:
### correcciones-yumma/css/6-1-1-seguimientos-dupla-anual.css
.x6-1-1-seguimientos-dupla-anual .ellipse-130 {
  height: 300px;
  width: 300px;
  left: calc(50% - 135px);
  top: calc(50% - 100px);
  position: absolute;
}

## 4. Ajuste tamaño amebas pantalla de datos total de seguimientos por dupla mensual
Para aplicar en el doc: 6-1-1-seguimientos-dupla-mensual.html
Archivos modificados:
### correcciones-yumma/css/6-1-1-seguimientos-dupla-mensual.css
.x6-1-1-seguimientos-dupla-mensual .ellipse-130 {
  height: 300px;
  width: 300px;
  left: calc(50% - 135px);
  top: calc(50% - 100px);
  position: absolute;
}

## 5. Ajuste tamaño amebas pantalla de datos seguimientos a crónicos
Para aplicar en el doc: 6-1-1a-seguimientos-dupla-cronicos.html
Archivos modificados:
### correcciones-yumma/css/6-1-1a-seguimientos-dupla-cronicos.css
.x6-1-1a-seguimientos-dupla-cronicos .ellipse-127 {
  height: 300px;
  width: 300px;
  left: calc(50% - 135px);
  top: calc(50% - 100px);
  position: absolute;
}

## 6. Ajuste tamaño amebas pantalla de datos canalizaciones anuales
Para aplicar en el doc: 6-1-2-canalizaciones-anual.html
Archivos modificados:
### correcciones-yumma/css/6-1-2-canalizaciones-anual.css
.x6-1-2-canalizaciones-anual .ellipse-130 {
  height: 300px;
  width: 300px;
  left: calc(50% - 135px);
  top: calc(50% - 120px);
  position: absolute;
}

## 7. Ajuste tamaño amebas pantalla de datos canalizaciones mensuales
Para aplicar en el doc: css/6-1-3-canalizaciones-mensual.css
Archivos modificados:
### correcciones-yumma/css/6-1-3-canalizaciones-mensual.css
.x6-1-3-canalizaciones-mensual .ellipse-127 {
  height: 300px;
  width: 300px;
  left: calc(50% - 135px);
  top: calc(50% - 120px);
  position: absolute;
}

## 8. Ajuste tamaño amebas pantalla de datos cruzados salarios mínimos
Para aplicar en el doc: 6-3-1-datos-salario-minimo.html
Archivos modificados:
### correcciones-yumma/css/6-3-1-datos-salario-minimo.css
.x6-3-1-datos-salario-minimo .ellipse-127 {
  height: 160px;
  width: 160px;
  left: calc(50% - 85px);
  top: calc(50% - 160px);
  position: absolute;
}
.x6-3-1-datos-salario-minimo .ellipse-127-1 {
  height: 180px;
  width: 180px;
  left: calc(50% - 90px);
  top: calc(50% - -60px);
  position: absolute;
}


## 9. Ajuste tamaño amebas pantalla de datos alertas de riesgo desglose por beneficiario
Para aplicar en el doc: 6-1-2-alertas-riesgo-desglose-beneficiario-anual.html
Archivos modificados:
### correcciones-yumma/css/6-1-2-alertas-riesgo-desglose-beneficiario-anual.css
.x6-1-2-alertas-riesgo-desglose-beneficiario-anual .ellipse-127 {
  height: 180px;
  width: 180px;
  left: calc(50% - 155px);
  top: calc(50% - 80px);
  position: absolute;
}
.x6-1-2-alertas-riesgo-desglose-beneficiario-anual .ellipse-192 {
  height: 180px;
  width: 180px;
  left: calc(50% - 0px);
  top: calc(50% - 20px);
  position: absolute;
}
.x6-1-2-alertas-riesgo-desglose-beneficiario-anual .ellipse-191 {
  height: 180px;
  width: 180px;
  left: calc(50% - 120px);
  top: calc(50% - -100px);
  position: absolute;
}

## 10. Ajuste tamaño amebas pantalla de datos de actividades desglose por beneficiario
Para aplicar en el doc: 6-1-3c-desglose-actividades.html
Archivos modificados:
### correcciones-yumma/css/6-1-3c-desglose-actividades.css
.x6-1-3c-desglose-actividades .ellipse-196 {
  height: 170px;
  width: 170px;
  left: calc(50% - 155px);
  top: calc(50% - 110px);
  position: absolute;
}
.x6-1-3c-desglose-actividades .ellipse-197 {
  height: 170px;
  width: 170px;
  left: calc(50% - 5px);
  top: calc(50% - 10px);
  position: absolute;
}
.x6-1-3c-desglose-actividades .ellipse-198 {
  height: 170px;
  width: 170px;
  left: calc(50% - 135px);
  top: calc(50% - -40px);
  position: absolute;
}
.x6-1-3c-desglose-actividades .ellipse-199 {
  height: 170px;
  width: 170px;
  left: calc(50% - 15px);
  top: calc(50% - 150px);
  position: absolute;
}

## 11. Ajuste tamaño amebas pantalla de datos cruzados usuarios discapacitados
Para aplicar en el doc: 6-3-2-datos-beneficiarios-discapacitados.html
Archivos modificados:
### correcciones-yumma/css/6-3-2-datos-beneficiarios-discapacitados.css
.x6-3-2-datos-beneficiarios-discapacitados .ellipse-127 {
  height: 160px;
  width: 160px;
  left: calc(50% - 80px);
  top: calc(50% - 155px);
  position: absolute;
}
.x6-3-2-datos-beneficiarios-discapacitados .ellipse-127-1 {
  height: 170px;
  width: 170px;
  left: calc(50% - 80px);
  top: calc(50% - -75px);
  position: absolute;
}

## 12. Ajuste tamaño amebas pantalla de datos total de canalizaciones desglose por beneficiario
Para aplicar en el doc: 6-1-2-canalizaciones-desglose-beneficiario-mensual.html
Archivos modificados:
### correcciones-yumma/css/6-1-2-canalizaciones-desglose-beneficiario-mensual.css
.x6-1-2-canalizaciones-desglose-beneficiario-mensual .ellipse-127 {
  height: 180px;
  width: 180px;
  left: calc(50% - 160px);
  top: calc(50% - 75px);
  position: absolute;
}
.x6-1-2-canalizaciones-desglose-beneficiario-mensual .ellipse-192 {
  height: 180px;
  width: 180px;
  left: calc(50% - 0px);
  top: calc(50% - 20px);
  position: absolute;
}
.x6-1-2-canalizaciones-desglose-beneficiario-mensual .ellipse-191 {
  height: 180px;
  width: 180px;
  left: calc(50% - 120px);
  top: calc(50% - -110px);
  position: absolute;
}