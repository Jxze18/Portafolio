# Portafolio
Mi Proyecto 
[Hoja De Vida](https://github.com/Jxze18/Hoja-De-Vida.git)
```
Sub proyecto()
  h = InputBox("por favor ingrese la cantidad:")
  If h < 1000 Then
   MsgBox (" no se va a pagar impuestos ")
   
    Else
       If h >= 1001 And h < 10001 Then
       ingresos = 0.05
        MsgBox ("el pago del ingreso anual es:") & h * ingresos
         Else
          If h >= 10001 And h < 100000 Then
           ingresos = 0.01
            MsgBox ("el pago del ingreso anual es:") & h * ingresos
             Else
              If h >= 100001 And h < 1000000 Then
               ingresos = 0.15
                MsgBox ("el pago del ingreso anuales:") & h * ingresos
                 Else
                  If h >= 1000001 And h < 10000000 Then
                   ingresos = 0.02
                    MsgBox ("el pago del ingreso anuales:") & h * ingresos
                     Else
                      If h >= 100000001 Then
                       ingresos = 0.25
                        MsgBox ("el pago del ingreso anuales:") & h * ingresos
                    End If
                End If
            End If
        End If
    End If
End If
```

```
Sub registro()
    fila = datos.Cells(1, 6)
    datos.Cells(fila, 1) = registro.Cells(6, 4)
    datos.Cells(fila, 2) = registro.Cells(8, 4)
    datos.Cells(fila, 3) = registro.Cells(10, 4)
    datos.Cells(fila, 4) = registro.Cells(12, 4)
    MsgBox "Datos Guardados"
    datos.Cells(1, 6) = fila + 1
End Sub
```

```
Sub inicio()
     For x = 1 To 15
   c = InputBox(" ingrese un nombre: ")
        fila = dato.Cells(1, 6)
         dato.Cells(fila, 2) = c
         dato.Cells(1, 6) = fila + 1
          Next x
           MsgBox ("Muchas gracias")
end sub 
```
```
Sub proyect()
    For j = 2 To 21
  nombre = nomb.Cells(j, 1)
   ulti = Len(nombre) - 1
    nomb.Cells(j, 2) = Mid(nombre, ulti, 2)
    Next j
    
    
End Sub
```

```
Private Sub btnBuscar_Click()
         frmbuscar.Show
       btnEditar.Enabled = True
     btnEliminar.Enabled = True
      Txtnombre.Enabled = False
       Txtcedula.Enabled = False
        Txtcorreo.Enabled = False
         Txttelefono.Enabled = False

    
End Sub

Private Sub btneditar_Click()
     Txtnombre.Enabled = True
      Txtcedula.Enabled = False
      Txtcorreo.Enabled = True
       Txttelefono.Enabled = True
       Txtnombre.SetFocus
         btnGuardar.Enabled = True
     btnNuevo.Enabled = False
      btnBuscar.Enabled = False
     btnEditar.Enabled = False
    btnEliminar.Enabled = False
        
       
       

End Sub

Private Sub btnEliminar_Click()
      actual = datos.Cells(1, 8)
        datos.Rows(actual).EntireRow.Delete
        Txtnombre.Text = Empty
        Txtcedula.Text = Empty
        Txtcorreo.Text = Empty
        Txttelefono.Text = Empty
          reg.Cells(1, 8) = reg.Cells(1, 8) - 1
          

End Sub

Private Sub btnGuardar_Click()
       fila = datos.Cells(1, 7)
       datos.Cells(fila, 1) = Txtnombre.Text
      datos.Cells(fila, 2) = Txtcedula.Text
        datos.Cells(fila, 3) = Txtcorreo.Text
      datos.Cells(fila, 4) = Txttelefono.Text
    MsgBox "Tus datos se han guardado"
     Txtnombre.Text = Empty
      Txtcedula.Text = Empty
       Txtcorreo.Text = Empty
        Txttelefono.Text = Empty
     btnGuardar.Enabled = False
    btnNuevo.Enabled = True
    btnBuscar.Enabled = False
    
    
    
    
    
End Sub

Private Sub btnnuevo_Click()
     Txtnombre.Enabled = True
      Txtcedula.Enabled = True
     Txtcorreo.Enabled = True
    Txttelefono.Enabled = True
    frmreg.Caption = "Nuevo Registro"
     btnGuardar.Enabled = True
    btnBuscar.Enabled = True
      btnNuevo.Enabled = True
      
    
     Txtnombre.SetFocus
    datos.Cells(1, 7) = datos.Cells(1, 7) + 1
    
    
    
    
    
    
End Sub
```
```
void main() {

  Person j = new Person (x;"Hombre", p; "Jose");
  
   j.apellido = "argote";
   j.edad = 17;
   print("el nombre es: ${j.nombre}");
   print("el sexo es: ${j.sexo}");
   print("la edad es: ${j.edad}");
   print("el nombre completo es: ${j.nombrecompleto()}");
   j.edadmas(numer2: 3);
   
  
  
   
          
}

  class Person{
   String? nombre,sexo,apellido;
   int? edad;
  
   Person({String? x, p}){
    nombre = x;
      sexo = p;
  }  
    String? nombrecompleto(){
     String nom = nombre! + apellido!;
      return nom;
    }  
     void edadmas ({int? numer2}){
      int w = edad! + numer2!;
       print ("la suma de la edad es $w");
      
    }
   ``` 
   ```
void main() {
    Operacion z = new Operacion();
  
    z.number1 = 9.0;  
    z.number2 = 8.0;
  print("la suma es:${z.sumar()}");       
   (z.restar)();
  print("la multiplicacion es:${z.multiplicar()}");      
  
  
  
}
 class Operacion{
   double? number1;
   double? number2; 
   double sumar(){
   double x = number1! + number2!;
     return x;
   }     
     
    void restar(){
      void p = number1! - number2!;
      return p;
    }
      
    double multiplicar(){
      double c = number1! * number2!;
       return c;
    }
    ```
     ```
void main() {
   Operacion z = new Operacion();
  
    z.number1 = 9.0;  
    z.number2 = 8.0;
   print("la suma es:${z.sumar()}");       
   (z.restar)();
   print("la multiplicacion es:${z.multiplicar()}");      
  
  
  
}
   class Operacion{
    double? number1;
    double? number2; 
    double sumar(){
    double x = number1! + number2!;
     return x;
   }     
     
    void restar(){
      void p = number1! - number2!;
      return p;
    }
      
   double multiplicar(){
     double c = number1! * number2!;
       return c;
    }
    
    ```
         
    ```
void main() {
  Empresa empresa = Empresa(pais: 'Colombia', numero: 90142, oficina: 'la trinidad');
  Empresa empresaB = Empresa(pais: 'Mexico', numero: 44117, oficina: 'Monterrey');
  
  print("""
   Pais: ${empresa.pais}.
    numero: ${empresa.numero}.
   oficina: ${empresa.oficina}.
 
 Codigo: ${empresa.generarCodigo()}.

""");
  empresa.cantCaracteres();

  print(""" 
   Pais: ${empresaB.pais}.
    numero: ${empresaB.numero}.
   oficina: ${empresaB.oficina}.



Codigo: ${empresaB.generarCodigo()}.
""");


empresaB.cantCaracteres();
    
  
}
  
 class Empresa{
   String? pais, oficina;
   int? numero;
     
 Empresa({this.pais, this.numero, this.oficina});
    
   
 String? generarCodigo (){
     String? paisx = pais!.substring(0, 3);
      int? cantOfi = oficina?.length;
     int? posOfi = cantOfi! - 3;
     String? ofi = oficina!.substring(posOfi,cantOfi);
     String? numerotostr = numero.toString();
     String? num = numerotostr.substring(0, 3);
     String? codigo = '$paisx$num$ofi';
     return codigo;
     
    
 }      
  void canCaracteres(){   
    int cantPais = pais!.length; 
    int cantOfi = oficina!.length;
   String? convNum = numero.toString();
   int cantNum = convNum.length;
   print("""
   la cantidad de caracteres son: $cantOfi
   los caracteres de el pais son: $cantPais
   la cantidad de caracteres de los numeros: $cantNum
   
   """);
   }
 }

```

```
void main(){
   Conejo conejo = Conejo();
    conejo.nombre = "cacio";
     conejo.edad = 4;
   conejo.comida = "zanahoria";
   print("""
   El nombre es: ${conejo.nombre}
   La edad es: ${conejo.edad}
   Una de las comida que come es: ${conejo.comida}
  """);
  
  
   Leon leon = Leon();
    leon.nombre = "fabra";
     leon.edad = 3;
   print("""
   El nombre es: ${leon.nombre}
   La edad  es: ${leon.edad}
  """);
  
  
   Hiena hiena = Hiena();
    hiena.nombre = "rin";
     hiena.edad = 9;
      hiena.peso = "42 Kg";
   print("""
   El nombre es: ${hiena.nombre}
   La edad es: ${hiena.edad}
   El peso : ${hiena.peso}
  """);
  
  
   Hombre hombre = Hombre();
    hombre.nombre = "Jose";
     hombre.apellido = "Argote";
      hombre.edad = 17;
   print("""
   El nombre es: ${hombre.nombre}
   El apellido es: ${hombre.apellido}
   La edad es: ${hombre.edad}
  """);
  
}
class Animal{
  String? nombre; 
}
class Herviboro extends Animal{
  int? edad;
}
class Conejo extends Herviboro{
  String? comida;
}
class Carnivoro extends Animal{
  int? edad;
}
class Leon extends Carnivoro{
  String? peso;
}
class Hiena extends Carnivoro{
  String? peso;
}
class Omnivoro extends Animal{
  int? edad;
}
class Hombre extends Omnivoro{
  String? apellido;
}
  ```
  
  ```
 public class MyClass { 
    
   public static void main(String[] args) {
  	 Person person = new Person("Argote");
  	   Person.nombre = "Jose";
     System.out.println(person.nombre);
      System.out.println(person.getApellido());
    person.setGenero("Heterosexual");
       System.out.println(person.imc(72, 155));
    
  }
}
class Person {
	 public String nombre;
      private String apellido;
       private String genero;
    
    Person(String x){
    	this.apellido = x;
 }
        
    String getApellido(){
    	return this.apellido
}
            
    void setGenero(String z){
        this.genero = z;
            
}
        
    double imc(int peso, int altura){
    return peso * altura;
        }
}
  
   ```
    
   ```
   void main() { 
   Car car = Car();
  Accesorios accesorio_1 = Accesorios("tapete");
  Accesorios accesorio_2 = Accesorios("retrovisor");
  Accesorios accesorio_3 = Accesorios("neumatico");
   car.placa = "IQI62D";
   car.setAccesorio(accesorio_1);
  car.setAccesorio(accesorio_2);
  car.setAccesorio(accesorio_3);
     print("La placa es: ${car.placa}");
  print(car.getAccesorios());
   
  
   

}
 class Car{
  List<Accesorios> _accesorios=[];
  String? placa;
    void setAccesorio (Accesorios accesorio){
      _accesorios.add(accesorio);
     
    }
  List<Accesorios> getAccesorios(){
    return _accesorios;
  
  
}
 }
 class Accesorios{
  String? nombre;
   Accesorios(this.nombre);
  
   String toString(){
    return nombre!;
  }
    
} 
   ```
  

   ```
  import 'dart:convert' as convert;

import 'package:http/http.dart' as https;
 
void main() async {
     final url = Uri.https('regres.in','api/users/3');
     final response = await https.get(url);
   if (response.statusCode == 200){
     final json = convert.jsonDecode(response.body);
     print(json['data']['email']);
      print(json['data']['first_name']);
      print(json['support']['url']);
    
     }else{
     print('problemas con la peticion');
   }
  
}
   ```
 
 ```
  import 'dart:convert' as convert;

import 'package:http/http.dart' as https;
 
void main() async {
     final url = Uri.https('jsonplaceholder.typicode.com','/posts/4');
     final response = await https.get(url);
   if (response.statusCode == 200){
     final json = convert.jsonDecode(response.body);
     print(json['"userid"']);
      print(json['id']);
      print(json['title']);
    
     }else{
     print('problemas con la peticion');
   }
  
}
  ```
