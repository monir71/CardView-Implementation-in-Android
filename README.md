activity_main.xml File:

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="300sp"
        android:elevation="20sp"
        app:cardCornerRadius="11sp"
        app:cardUseCompatPadding="true"
        app:cardBackgroundColor="@color/black">

        <androidx.cardview.widget.CardView
            android:layout_width="100sp"
            android:layout_height="100sp"
            android:layout_margin="10sp"
            android:elevation="11sp"
            app:cardCornerRadius="11sp"
            app:cardBackgroundColor="#f00">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Red"
                android:textStyle="bold"
                android:textSize="20sp"
                android:layout_gravity="center"
                android:textColor="@color/white"/>

        </androidx.cardview.widget.CardView>

        <androidx.cardview.widget.CardView
            android:layout_width="100sp"
            android:layout_height="100sp"
            android:layout_margin="10sp"
            android:elevation="11sp"
            app:cardCornerRadius="11sp"
            app:cardBackgroundColor="#0f0"
            android:layout_gravity="end">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Green"
                android:textStyle="bold"
                android:textSize="20sp"
                android:layout_gravity="center"
                android:textColor="@color/white"/>

        </androidx.cardview.widget.CardView>

        <androidx.cardview.widget.CardView
            android:layout_width="100sp"
            android:layout_height="100sp"
            android:layout_margin="10sp"
            android:elevation="11sp"
            app:cardCornerRadius="11sp"
            app:cardBackgroundColor="#00f"
            android:layout_gravity="center">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Blue"
                android:textStyle="bold"
                android:textSize="20sp"
                android:layout_gravity="center"
                android:textColor="@color/white"/>

        </androidx.cardview.widget.CardView>


    </androidx.cardview.widget.CardView>

</androidx.constraintlayout.widget.ConstraintLayout>
```
