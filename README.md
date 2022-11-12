# Opisaniee
Описание персонажа


<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:background="#730000"
    android:orientation="vertical">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:gravity="center"
        android:text="Родившийся и выросший в Бостоне, что в штате Массачусетс, разведчик — быстро бегающий задира с бейсбольной битой, имеющий вычурную привычку высказывать всё «прямо в лицо». Он очень грубый и думает, что ему всё по плечу. Это самый быстрый наёмник на поле боя, что позволяет ему оставлять противников далеко позади, а двойной прыжок помогает ему перемещаться по местности и уклоняться от встречных снарядов. Разведчик вооружен обрезом, пистолетом и битой, что делает его идеальным классом для агрессивного боя и захода в тыл. Он эффективно использует тактику «ударь и беги» — подбегает, быстро атакует врага и убегает прочь, пока никто ничего не понял."
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="1.0"
        android:textColor="#FFFFFF"
        android:textStyle="bold"/>

    <Button
        android:id="@+id/button4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="*ТЫК*"
        android:layout_gravity="center"
        android:gravity="center"
        android:background="#330000"
        android:textSize="30sp"
        android:textStyle="italic"
        />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:gravity="center"
        android:text="ВСЕ ПОНЯТНО"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="1.0"
        android:textColor="#FFFFFF"
        android:textStyle="bold"
        android:textSize="30sp"
        />

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:srcCompat="@drawable/android" />


</LinearLayout>
