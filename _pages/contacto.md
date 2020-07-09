---
layout: page
title: Contacto
permalink: /contacto
comments: false
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Hola viajeros! Si necesitan información o requieren ayuda planificando su viaje no duden en escribirme a través del correo imdavid.springbok@gmail.com o mediante el formulario de contacto. Estaré feliz en ayudarte! Prometo responder lo más pronto posible. Un saludo virtual --{{site.name}}. </p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nombre*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Mensaje*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Enviar">
</form>