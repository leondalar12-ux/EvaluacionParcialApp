# EvaluacionParcialApp
## 1.   Titulo de la Aplicación:
### Pastelería "Dulce Amor"

## 2.  Descripción de la aplicación
Aqui se muestra la interfaz de nuestro aplicativo para nuestra pasteleria llamada "DULCE AMOR",donde muestra  en la parte superior  el nombre de nuestra pastelerìa y su logo, seguidamente hemos colocado imagen referente a un postre, en este caso "TRES LECHES",e indicando de bajo de ella una pequeña información de su elaboración, seguidamente hay para calificar mediante estrellas la calidad del servicio,  e indicar las porciones a comprar.Luego esta habilitado la opcion de compras  para realizar los pedidos.

<img width="480" height="957" alt="image" src="https://github.com/user-attachments/assets/409942ba-3f74-47f1-865d-881c92139ef6" /> 

## 3. Imagen final de la descripción : 
<img width="635" height="426" alt="image" src="https://github.com/user-attachments/assets/aa582d0d-7a1d-4511-b2a9-e201594af389" />

En esta fase se muestra el interfaz final de la aplicación, con una imagen centrada de la torta de 3 leches, su descripción centrada , asi mismo botones  de compra y agregar al carrito al marcar cambian de color, un widget de calificación el froma de estrellas amararillas que al seleccionar cambian o oscurecen.

## 4. Imagen de plantilla blanca: 
<img width="343" height="593" alt="image" src="https://github.com/user-attachments/assets/1a06a8d1-ca92-4f65-879c-f3564fa98fdc" />

Esta imagen muestra la plantilla blanca que es la base de la aplicación, aqui se realizan los cambios que se pueden observar , sirven para organizar los elemntos como las imagenes, texto, botones y widgets.

## 5. Imagen de plantilla turquesa :

<img width="262" height="492" alt="image" src="https://github.com/user-attachments/assets/1da1d4ed-0aa6-4f4c-a9c5-68acdd4210b8" />

En esta imagen observamos la referencias visuales que hemos realizado en la plantilla blanca que nos  ayudan  para la implementación de nuestro Android Studio.





                    

Colocar el titulo de tu app
Colocar una descripción de la aplicación
Imagen final de la aplicación terminada con pequeña explicación.
Imagen de la Plantilla blanca donde se realiza la aplicación con explicación.
Imagen de la plantilla turquesa (maqueta de la app)






Todos tienen lo sgte:
Imagen
Texto
Aporte
Widget
Botones Explicar que atributos usaron y sustentar para cada elemento.
Se debe cambiar en textos el color y tamaño según convenga
En widget cambiar color
En botones cambiar el color del botón y el color del texto
si quieren colocar un título hacerlo con un solo # y si desean subtítulo con #
 <CODE>
 <?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <!--Pasteleria-->

    <!-- Imagen como sello de agua -->

    <ImageView
        android:id="@+id/watermark"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:alpha="0.2"
        android:contentDescription="Sello de agua"
        android:scaleType="fitEnd"
        android:src="@drawable/fondo1"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="TRES LECHES"
        android:textColor="#C71C54"
        android:textSize="18sp"
        android:textStyle="italic"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.494"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.455" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="87dp"
        android:layout_height="21dp"
        android:text="Pastelería"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.524"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <EditText
        android:id="@+id/editTextText3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:hint="Cantidad a comprar:"
        android:inputType="text"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.762" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:backgroundTint="#DC54BC"
        android:text="Comprar"
        android:textColor="#DED1D1"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.885"
        app:rippleColor="#5B1CCA" />

    <RatingBar
        android:id="@+id/ratingBar"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:progressBackgroundTint="@color/fondo1"
        android:progressTint="@android:color/holo_orange_light"
        android:secondaryProgressTint="@color/fondo1"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.709" />

    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:backgroundTint="#673AB7"
        android:text="Agregar al carrito"
        android:textColorLink="#D35FE7"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.976"
        app:rippleColor="#C938CC" />

    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="117dp"
        android:layout_height="90dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.487"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.024"
        app:srcCompat="@drawable/fondo" />

    <ImageView
        android:id="@+id/imageView4"
        android:layout_width="273dp"
        android:layout_height="229dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.186"
        app:srcCompat="@drawable/_lech_png" />

    <TextView
        android:id="@+id/textView3"
        android:layout_width="348dp"
        android:layout_height="151dp"
        android:gravity="center"
        android:text="La Torta Tres Leches es pura dulzura: bizcocho esponjoso bañado en leche evaporada, condensada y crema, creando una textura húmeda y deliciosa. Coronada con merengue y un toque de canela, ¡cada bocado es una fiesta de sabor que conquista corazones!"
        android:textColor="#370F7E"
        android:textSize="17sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.424"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.579" />

</androidx.constraintlayout.widget.ConstraintLayout>



