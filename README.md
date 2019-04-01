# Practica6

Puntero que apunta a un array y que se ordene el puntero que apunta al array.
Se utilizaran los argunentos del main, .

int main(int argc, char * argv[ ]){ 
  if(argc<3){
    cout << "Error"
  }else{
     for(int i=1; i<argc; i++){
        cout << argv[i] << " ";
      }
}

char * argv[ ] == char ** argv

comando: encontrar -c cadena
         encontrar -s subcadena
         
"El programa devuelve las veces que se encuentra la subcadena [-s] dentro de cadena [-c]

Ejemplo:

encontrar -s la -c lalala --> corecto
encontrar -c lalala -s la --> correcto tambien

Incorrectos

-c lalala -s la
encontrar -c lalala -c la
