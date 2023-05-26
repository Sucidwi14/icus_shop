# icus_shop

| Nama      | SUCI DWI FRATIWI |
| ----------- | ----------- |
| NIM     | 312010143      |
| Kelas   | TI.20.D.1    |

### 1. Tampilan login icus_shop

![WhatsApp Image 2023-05-26 at 16 29 19](https://github.com/Sucidwi14/icus_shop/assets/101787968/4c786113-d5b3-4415-a03f-dc28f9da871d)

- ini adalah sourcode tampilan login 
  <?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

   <TextView
       android:layout_width="wrap_content"
       android:layout_height="wrap_content"
       android:text="ICUS_SHOP"
       android:fontFamily="@font/roboto"
       android:textColor="@color/icuscolor"
       android:textSize="50dp"
       android:layout_marginLeft="10dp"
       android:layout_marginTop="30dp"
       android:layout_centerHorizontal="true"
       android:id="@+id/icus"/>

   <ImageView
       android:layout_width="97dp"
       android:layout_height="118dp"
       android:layout_below="@id/icus"
       android:layout_marginLeft="10dp"
       android:layout_marginTop="11dp"
       android:background="@drawable/keranjang"
       android:layout_centerHorizontal="true"
       android:id="@+id/keranjang"/>

   <TextView
       android:layout_width="wrap_content"
       android:layout_height="wrap_content"
       android:text="Username"
       android:fontFamily="@font/robotoregular"
      android:textColor="@color/usernamecolor"
      android:textSize="20dp"
      android:layout_below="@+id/keranjang"
      android:layout_marginLeft="20dp"
      android:layout_marginTop="30dp"
      android:id="@+id/username"/>

      <ImageView
          android:layout_width="wrap_content"
          android:layout_height="wrap_content"
         android:layout_below="@id/username"
         android:layout_marginLeft="20dp"
         android:layout_marginTop="30dp"
         android:background="@drawable/garisssss"
         android:id="@+id/garis"/>

      <TextView
          android:layout_width="wrap_content"
          android:layout_height="wrap_content"
         android:text="Password"
         android:fontFamily="@font/robotoregular"
         android:textColor="@color/usernamecolor"
         android:textSize="20dp"
         android:layout_below="@id/garis"
         android:layout_marginLeft="20dp"
         android:layout_marginTop="30dp"
         android:id="@+id/password"/>

      <ImageView
          android:layout_width="wrap_content"
          android:layout_height="wrap_content"
         android:layout_below="@id/password"
         android:layout_marginLeft="20dp"
         android:layout_marginTop="30dp"
         android:background="@drawable/garisssss"
         android:id="@+id/panjang"/>

      <Button
          android:layout_width="wrap_content"
          android:layout_height="wrap_content"
          android:layout_below="@id/panjang"
          android:width="100dp"
          android:text="Login"
          android:textColor="@color/secondaryColor"
          android:layout_centerHorizontal="true"
          android:background="@drawable/button_shape"
          android:textSize="20dp"
          android:fontFamily="@font/roboto"
          android:layout_marginTop="90dp"
          android:id="@+id/login"/>
   
</RelativeLayout>

### 2. Tampilan Sign Up

![WhatsApp Image 2023-05-26 at 16 52 11](https://github.com/Sucidwi14/icus_shop/assets/101787968/56c99aa7-efd1-4eaa-9138-65f00367ef93)

- Source code Sign Up

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".register">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="ICUS_SHOP"
        android:fontFamily="@font/roboto"
        android:textColor="@color/icuscolor"
        android:textSize="50dp"
        android:layout_marginLeft="10dp"
        android:layout_marginTop="30dp"
        android:layout_centerHorizontal="true"
        android:id="@+id/icus"/>

    <ImageView
        android:layout_width="97dp"
        android:layout_height="118dp"
        android:layout_below="@id/icus"
        android:layout_marginLeft="10dp"
        android:layout_marginTop="11dp"
        android:background="@drawable/keranjang"
        android:layout_centerHorizontal="true"
        android:id="@+id/keranjang"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Username"
        android:fontFamily="@font/robotoregular"
        android:textColor="@color/usernamecolor"
        android:textSize="20dp"
        android:layout_below="@+id/keranjang"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="30dp"
        android:id="@+id/username"/>

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/username"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="30dp"
        android:background="@drawable/garisssss"
        android:id="@+id/garis"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Password"
        android:fontFamily="@font/robotoregular"
        android:textColor="@color/usernamecolor"
        android:textSize="20dp"
        android:layout_below="@id/garis"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="30dp"
        android:id="@+id/password"/>

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/password"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="30dp"
        android:background="@drawable/garisssss"
        android:id="@+id/panjang"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Re-enter Password"
        android:fontFamily="@font/robotoregular"
        android:textColor="@color/usernamecolor"
        android:textSize="20dp"
        android:layout_below="@id/panjang"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="30dp"
        android:id="@+id/enter"/>

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/enter"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="30dp"
        android:background="@drawable/garisssss"
        android:id="@+id/risris"/>

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/panjang"
        android:width="200dp"
        android:text="Sign Up"
        android:textColor="@color/secondaryColor"
        android:layout_centerHorizontal="true"
        android:background="@drawable/button_shape"
        android:textSize="20dp"
        android:fontFamily="@font/roboto"
        android:layout_marginTop="200dp"
        android:id="@+id/login"/>

</RelativeLayout>
