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

