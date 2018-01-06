# project-2-
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"


    tools:context="com.udacity.myapplication.MainActivity">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"
        android:src="@drawable/stad" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:orientation="vertical">

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif-medium"
                android:gravity="center_horizontal"
                android:padding="16dp"
                android:text="Team A"
                android:textColor="#FF6F00"
                android:textSize="20sp"
                android:textStyle="bold" />


            <TextView

                android:id="@+id/team_a_score"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif-light"
                android:gravity="center_horizontal"
                android:text="0"
                android:textAllCaps="true"
                android:textColor="#ffff"
                android:textSize="56sp" />

            <Button
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="53dp"
                android:layout_marginLeft="24dp"
                android:layout_marginRight="24dp"
                android:onClick="goalA"
                android:text="Goal"
                android:textSize="16sp"
                android:textStyle="bold" />

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif-medium"
                android:gravity="center_horizontal"
                android:padding="10dp"
                android:text="fouls"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold"

                />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:gravity="center_horizontal"
                android:orientation="horizontal"
                android:weightSum="1">

                <Button
                    android:layout_width="44dp"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="8dp"
                    android:layout_marginLeft="10dp"
                    android:layout_marginRight="10dp"
                    android:layout_weight="0.12"
                    android:onClick="decreaseFoulForTeamA"
                    android:text="-"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/team_a_fouls"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:fontFamily="sans-serif-medium"
                    android:padding="10dp"
                    android:text="0"
                    android:textColor="#FF6F00"
                    android:textSize="20sp"
                    android:textStyle="bold" />

                <Button
                    android:layout_width="44dp"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="8dp"
                    android:layout_marginLeft="10dp"
                    android:layout_marginRight="10dp"
                    android:layout_weight="0.12"
                    android:onClick="increaseFoulForTeamA"
                    android:text="+"
                    android:textSize="16sp" />
            </LinearLayout>

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif-medium"
                android:gravity="center_horizontal"
                android:padding="10dp"
                android:text="Free Kicks"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:gravity="center_horizontal"
                android:orientation="horizontal"
                android:weightSum="1">

                <Button
                    android:layout_width="44dp"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="8dp"
                    android:layout_marginLeft="10dp"
                    android:layout_marginRight="10dp"
                    android:layout_weight="0.12"
                    android:onClick="decreaseFreeKickForTeamA"
                    android:text="-" />

                <TextView
                    android:id="@+id/team_a_free_kick"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:fontFamily="sans-serif-medium"
                    android:padding="10dp"
                    android:text="0"
                    android:textColor="#FF6F00"
                    android:textSize="20sp"
                    android:textStyle="bold" />

                <Button
                    android:layout_width="44dp"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="8dp"
                    android:layout_marginLeft="10dp"
                    android:layout_marginRight="10dp"
                    android:layout_weight="0.12"
                    android:onClick="increaseFreeKickForTeamA"
                    android:text="+"
                    android:textSize="16sp" />
            </LinearLayout>

        </LinearLayout>

        <View
            android:layout_width="1dp"
            android:layout_height="match_parent"
            android:layout_marginTop="10dp"
            android:background="@android:color/darker_gray" />

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:orientation="vertical">


            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif-medium"
                android:gravity="center_horizontal"
                android:padding="16dp"
                android:text="Team B"
                android:textColor="#FF6F00"
                android:textSize="20sp"
                android:textStyle="bold" />


            <TextView

                android:id="@+id/team_b_score"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif-light"
                android:gravity="center_horizontal"
                android:text="0"
                android:textAllCaps="true"
                android:textColor="#ffffff"
                android:textSize="56sp" />

            <Button
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="53dp"
                android:layout_marginLeft="24dp"
                android:layout_marginRight="24dp"
                android:onClick="goalB"
                android:text="Goal"
                android:textStyle="bold" />

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif-medium"
                android:gravity="center_horizontal"
                android:padding="10dp"
                android:text="fouls"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:gravity="center_horizontal"
                android:orientation="horizontal"
                android:weightSum="1">

                <Button
                    android:layout_width="44dp"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="8dp"
                    android:layout_marginLeft="10dp"
                    android:layout_marginRight="10dp"
                    android:layout_weight="0.12"
                    android:onClick="decreaseFoulForTeamB"
                    android:text="-"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/team_b_fouls"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:fontFamily="sans-serif-medium"
                    android:padding="10dp"
                    android:text="0"
                    android:textColor="#FF6F00"
                    android:textSize="20sp"
                    android:textStyle="bold" />

                <Button
                    android:layout_width="44dp"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="8dp"
                    android:layout_marginLeft="10dp"
                    android:layout_marginRight="10dp"
                    android:layout_weight="0.12"
                    android:onClick="increaseFoulForTeamB"
                    android:text="+"
                    android:textSize="16sp" />
            </LinearLayout>

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif-medium"
                android:gravity="center_horizontal"
                android:padding="10dp"
                android:text="Free Kicks"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:gravity="center_horizontal"
                android:orientation="horizontal"
                android:weightSum="1">

                <Button
                    android:layout_width="44dp"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="8dp"
                    android:layout_marginLeft="10dp"
                    android:layout_marginRight="10dp"
                    android:layout_weight="0.12"
                    android:onClick="decreaseFreeKickForTeamB"
                    android:text="-"
                    android:textSize="16sp" />

                <TextView
                    android:id="@+id/team_b_free_kicks"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:fontFamily="sans-serif-medium"
                    android:padding="10dp"
                    android:text="0"
                    android:textColor="#FF6F00"
                    android:textSize="20sp"
                    android:textStyle="bold" />

                <Button
                    android:layout_width="44dp"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="8dp"
                    android:layout_marginLeft="10dp"
                    android:layout_marginRight="10dp"
                    android:layout_weight="0.12"
                    android:onClick="increaseFreeKickForTeamB"
                    android:text="+"
                    android:textSize="16sp" />
            </LinearLayout>
            />


            />
        </LinearLayout>
    </LinearLayout>


    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_margin="10dp"
        android:onClick="reset"
        android:text="Reset"
        android:textSize="16sp" />


</RelativeLayout>
