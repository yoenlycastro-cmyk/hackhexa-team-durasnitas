Variables elegidas

  - Movimiento
  - Ruido

Explicación de variables

  - Movimiento: Detecta si existen movimientos diferentes al promedio, muy rápidos o bruscos.  
  - Ruido: Detecta cambios bruscos en el ruido de la ciudad.

Ejemplos

- Si el sensor de movimiento detecta un movimiento inusual en la velocidad de los carros, puede ser indicador de algún problema.
- El sensor de ruido nos podría ayudar por ejemplo en la noche, cuando se supone que la gente duerme, si se detecta mucho ruido podría ser un indicador de actividad sospechosa.

Código

if (movimiento > movimiento_promedio){
  cout<<"Hay una actividad sospechosa";  
}

if (ruido > ruido_promedio){
  cout<<"Hay una actividad sospechosa";  
}