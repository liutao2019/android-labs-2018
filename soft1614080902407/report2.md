#�ڶ���ʵ��

## 1.ʵ��Ŀ��
��1����Issues�д����Լ���ѡ�⣺https://github.com/hzuapps/android-labs-2018/issues ��
��2��������ѡ��Ŀ����дһ������Activity�����о�����ѧ��ǰ׺���ŵ��Լ���Java���£���
��3������������Ϊ�Լ���ѧ��+��Ӧ�Ĺ��ܻ���Ŀ��
��4�������Լ�ѡ�����Ŀʵ��Activity�е��������õȹ��ܣ�ѡ������
## 2.ʵ�鲽��
��1���Ķ�ʵ��Ҫ��https://github.com/hzuapps/android-labs-2018/labels/Lab
��2���ڵ�����Android Studio��д����
// ����Ҫ�������У�
��3��ʹ��Git�������ύ���Լ��Ŀ��У�https://github.com/Qiujialin/android-labs-2018
$ git pull
$ git add soft1614080902407/*
$ git commit "#2 #1015 ����¼ "
$ git push
��4�����Լ���GitHub���ϴ����ͷ���Pull Request��ע��鿴Changed files��
// �Ƿ�ֻ�޸����Լ����ļ���
��5����GitHub��ʹ��Markdown�ļ���дʵ�鱨�棨report1.md, report2.md��
// �������Լ����ļ�����
## 3.ʵ����
1.AndroidManifest.xml

<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.example.hzu.soft1614080902407">

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/AppTheme">
        <activity android:name=".Soft1614080902407Activity_1">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>

2.Soft1614080902407Activity_1.java

package com.example.hzu.soft1614080902407;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;

public class Soft1614080902407Activity_1 extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_soft1614080902407_1);
    }
}

3.activity_soft1614080902407_1.xml

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".Soft1614080902407Activity_1">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="#1015 ����¼"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</android.support.constraint.ConstraintLayout>

4.strings.xml

<resources>
    <string name="app_name">Soft1614080902407����¼</string>
</resources>

##4.ʵ�����
�˴�ʵ���֮ǰ��ʵ��Ҫ����һ�㣬������ѧ�����������֪ʶ��Ҳ������ϤAndroid Studio�Ĳ���