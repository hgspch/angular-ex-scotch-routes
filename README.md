# Angular 2 routing course

- Routing
  * **Child** route
  * **Lazy loading** de module
  * **Resolve**, au lieu d’appel à service, pour avoir les données
  prêtes dès le chargement du composant

- Sous modules
  * Pour avoir les directives basiques (*ngIf…), ne réimporte pas le
  BrowserModule comme dans app.module car il ne doit y en avoir qu’un
  par appli.
  Mais importe juste le CommonModule :
  { CommonModule } from '@angular/common';
- Bootstrap

tourne avec system.js

_from Scotch.io_



