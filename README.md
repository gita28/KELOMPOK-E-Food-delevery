# KELOMPOK-E-Food-delevery
KELOMPOK E Food delevery


Activity spLash screen
<?xml version="1.0" encoding="utf-8"?>

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">


    <ImageView
        android:id="@+id/imageView3"
        android:layout_width="432dp"
        android:layout_height="742dp"
        android:src="@drawable/si3"
        tools:ignore="MissingConstraints"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="-7dp" />

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="382dp"
        android:layout_height="427dp"
        android:src="@drawable/aku1"
        app:layout_constraintBottom_toBottomOf="@+id/imageView3"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.482"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.569" />

</androidx.constraintlayout.widget.ConstraintLayout>

Order sate kambing
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <androidx.constraintlayout.widget.ConstraintLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">


        <ImageView
            android:id="@+id/kembali"
            android:layout_width="99dp"
            android:layout_height="84dp"
            android:src="@drawable/kembali"
            app:layout_constraintBottom_toTopOf="@+id/imageView2"
            app:layout_constraintEnd_toStartOf="@+id/ranting"
            app:layout_constraintHorizontal_bias="0.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <ImageView
            android:id="@+id/ranting"
            android:layout_width="126dp"
            android:layout_height="78dp"
            android:layout_marginTop="16dp"
            android:src="@drawable/ranting"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="1.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

        <ImageView
            android:id="@+id/imageView2"
            android:layout_width="223dp"
            android:layout_height="88dp"
            android:src="@drawable/indonesia"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.146" />

        <ImageView
            android:id="@+id/imagefood2"
            android:layout_width="398dp"
            android:layout_height="158dp"
            android:layout_marginStart="1dp"
            android:layout_marginTop="28dp"
            android:layout_marginEnd="1dp"
            android:src="@drawable/food2"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/imageView2" />

        <ImageView
            android:id="@+id/imageView5"
            android:layout_width="398dp"
            android:layout_height="158dp"
            android:layout_marginStart="1dp"
            android:layout_marginTop="24dp"
            android:layout_marginEnd="1dp"
            android:src="@drawable/gado"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/imagefood2" />

        <ImageView
            android:id="@+id/imageView4"
            android:layout_width="398dp"
            android:layout_height="158dp"
            android:layout_marginStart="1dp"
            android:layout_marginTop="20dp"
            android:layout_marginEnd="1dp"
            android:src="@drawable/rendang"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHorizontal_bias="0.0"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/imageView5" />


    </androidx.constraintlayout.widget.ConstraintLayout>


</ScrollView>








Order sate

<?xml version="1.0" encoding="utf-8"?>

    <androidx.constraintlayout.widget.ConstraintLayout
        xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        android:layout_width="match_parent"
        android:layout_height="match_parent">


    <ImageView
        android:id="@+id/kembali"
        android:layout_width="157dp"
        android:layout_height="86dp"
        android:src="@drawable/kembali"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />


    <ImageView
        android:id="@+id/ranting"
        android:layout_width="147dp"
        android:layout_height="86dp"
        android:src="@drawable/ranting"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <ImageView
        android:id="@+id/place"
        android:layout_width="287dp"
        android:layout_height="128dp"
        android:src="@drawable/place"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView7" />

    <ImageView
        android:id="@+id/imageView6"
        android:layout_width="248dp"
        android:layout_height="211dp"
        android:layout_marginTop="16dp"
        android:src="@drawable/sate"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.306"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/kembali" />

    <ImageView
        android:id="@+id/imageView7"
        android:layout_width="257dp"
        android:layout_height="226dp"
        android:src="@drawable/dowon1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView6" />
    </androidx.constraintlayout.widget.ConstraintLayout

<?xml version="1.0" encoding="utf-8"?>

    <androidx.constraintlayout.widget.ConstraintLayout
        xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:tools="http://schemas.android.com/tools"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        android:layout_width="match_parent"
        android:layout_height="match_parent">


    <ImageView
        android:id="@+id/kembali"
        android:layout_width="109dp"
        android:layout_height="93dp"
        android:src="@drawable/kembali"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/rating"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <ImageView
        android:id="@+id/rating"
        android:layout_width="86dp"
        android:layout_height="98dp"
        android:src="@drawable/ranting"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />


    <ImageView
        android:id="@+id/gi"
        android:layout_width="326dp"
        android:layout_height="145dp"
        android:layout_marginTop="36dp"
        android:src="@drawable/gi"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/kembali" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:background="#FFC107"
        android:text="jumlah"
        android:textAllCaps="true"
        android:textSize="25dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/gi"
        app:layout_constraintVertical_bias="0.085" />

    <Button
        android:id="@+id/button3"
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:background="#FFC107"
        android:layout_marginTop="56dp"
        android:onClick="decrement"
        android:text="-"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.68"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2" />

    <Button
        android:id="@+id/button4"
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:background="#FFC107"
        android:layout_marginTop="56dp"
        android:onClick="increment"
        android:text="+"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.355"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2" />

    <TextView
        android:id="@+id/quantity_textview"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginTop="56dp"
        android:paddingLeft="8dp"
        android:paddingRight="8dp"
        android:text="0"
        android:textColor="#212121"
        android:textSize="25dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/button3"
        app:layout_constraintHorizontal_bias="0.525"
        app:layout_constraintStart_toEndOf="@+id/button4"
        app:layout_constraintTop_toBottomOf="@+id/textView2"
        app:layout_constraintVertical_bias="0.023" />

    <View
            android:layout_marginTop="10dp"
            android:layout_width="match_parent"
            android:layout_height="2dp"
            android:background="@color/colorAccent"
        tools:ignore="MissingConstraints" />

    <TextView
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="36dp"
        android:text="Harga"
        android:textAllCaps="true"
        android:textSize="30dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/button4" />

    <TextView
        android:id="@+id/price_textview"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:text="0"
        android:textColor="#212121"
        android:textSize="25dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView3" />

    <Button
        android:id="@+id/sumbitorder"
        android:layout_width="324dp"
        android:layout_height="38dp"
        android:onClick="Submitorder"
        android:text="Pesan Sekarang"
        android:background="#FFC107"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.494"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/price_textview"
        app:layout_constraintVertical_bias="0.228" />

</androidx.constraintlayout.widget.ConstraintLayout>




