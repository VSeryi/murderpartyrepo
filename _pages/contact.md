---
title: "Contacto"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p>¿Deseas mandarnos un mensaje?. ¡Contestaremos lo antes posible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nombre*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="Dirección Email*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Mensaje*" required></textarea>  
<input type="hidden" name="_language" value="es" />  
<input class="btn btn-success" type="submit" value="Enviar">
</form>