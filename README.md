# EvaluacionParcialApp
## Pastelería "Dulce Amor"



Aqui se muestra la interfaz de nuestro aplicativo para nuestra pasteleria llamada "DULCE AMOR",donde muestra  en la parte superior  el nombre de nuestra pastelerìa y su logo, seguidamente hemos colocado imagen referente a un postre, en este caso "TRES LECHES",e indicando de bajo de ella una pequeña información de su elaboración, seguidamente hay para calificar mediante estrellas la calidad del servicio,  e indicar las porciones a comprar.Luego esta habilitado la opcion de compras  para realizar los pedidos.

<img width="480" height="957" alt="image" src="https://github.com/user-attachments/assets/409942ba-3f74-47f1-865d-881c92139ef6" />






                    

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



