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
         
