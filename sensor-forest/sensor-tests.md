
 
  cin>> mov;
  cin>> ruido;
  cin>> luz;

if (mov=si && ruido=no){
  cout<<"Hay un movimiento sospechoso sin ruido";  
}

if (mov=no && ruido=si){
  cout<<"Hay un ruido sospechoso pero no se detectó movimiento";  
}

if (luz = no && ruido=si){
  cout<<"Hay un ruido extraño en la obscuridad";  
}

if (mov=si && ruido=si && luz=no){
  cout<<"Hay un movimiento y ruido sospechoso en la obscuridad";  
}

if (mov=no && luz=si){
  cout<<"Todo parece seguro";  
}
