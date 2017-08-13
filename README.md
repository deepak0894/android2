# android2
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.android.example.accelerometergraphdisp.MainActivity"
    tools:layout_editor_absoluteY="81dp"
    tools:layout_editor_absoluteX="0dp">

    <Button
        android:id="@+id/btnStart"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="START"
        app:layout_constraintBottom_toTopOf="@+id/chart_container"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintRight_toLeftOf="@+id/btnStop"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintHorizontal_bias="1.0" />

    <Button
        android:id="@+id/btnStop"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="STOP"
        app:layout_constraintBottom_toTopOf="@+id/chart_container"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintRight_toLeftOf="@+id/btnUpload"
        app:layout_constraintLeft_toRightOf="@+id/btnStart" />

    <Button
        android:id="@+id/btnUpload"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="UPLOAD"
        app:layout_constraintBottom_toTopOf="@+id/chart_container"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintLeft_toRightOf="@+id/btnStop"
        app:layout_constraintVertical_bias="0.531" />

    <LinearLayout
        android:id="@+id/chart_container"
        android:layout_width="334dp"
        android:layout_height="444dp"
        android:layout_alignLeft="@+id/btnStop"
        android:layout_alignStart="@+id/btnUpload"
        android:layout_below="@+id/btnStart"
        android:orientation="vertical"
        tools:layout_editor_absoluteX="16dp"
        tools:layout_editor_absoluteY="119dp"></LinearLayout>

</android.support.constraint.ConstraintLayout>
