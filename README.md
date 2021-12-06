# ApdateAnnonce
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.106"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.131"
        tools:srcCompat="@tools:sample/avatars" />

    <EditText
        android:id="@+id/editTextTextMultiLine"
        android:layout_width="191dp"
        android:layout_height="390dp"
        android:ems="10"
        android:gravity="start|top"
        android:hint="Description du stage"
        android:inputType="textMultiLine"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.967"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.355" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Deposer"
        app:background_color="red"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.977"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editTextTextMultiLine"
        app:layout_constraintVertical_bias="0.302"/>

    <LinearLayout
        android:layout_width="200dp"
        android:layout_height="223dp"
        android:orientation="vertical"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.472">

        <EditText
            android:id="@+id/editTextTextPostalAddress2"
            android:layout_width="match_parent"
            android:layout_height="70dp"
            android:ems="10"
            android:hint="Adresse"
            android:inputType="textPostalAddress" />

        <EditText
            android:id="@+id/editTextTextEmailAddress2"
            android:layout_width="match_parent"
            android:layout_height="76dp"
            android:ems="10"
            android:hint="Email de l'entreprise"
            android:inputType="textEmailAddress" />

        <EditText
            android:id="@+id/editTextDate2"
            android:layout_width="match_parent"
            android:layout_height="75dp"
            android:ems="10"
            android:hint="Date de dernier delai"
            android:inputType="date" />
    </LinearLayout>

    <com.google.android.material.floatingactionbutton.FloatingActionButton
        android:id="@+id/floatingActionButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:clickable="true"
        app:srcCompat="@android:drawable/ic_menu_edit"
        tools:layout_editor_absoluteX="348dp"
        tools:layout_editor_absoluteY="53dp"
        tools:ignore="MissingConstraints" />

</androidx.constraintlayout.widget.ConstraintLayout>
