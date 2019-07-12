# Ud2_Ejemplo13
_Ejemplo 13 de la Unidad 2._ 

Vemos como al utilizar atributos del espacio de nombres _tools_ aparecen en el diseño pero no en la aplicación.

Sólo hemos de fijarnos en el fichero _activity_main.xml_:

```
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        tools:text="Texto tools"/>

</LinearLayout>
```
