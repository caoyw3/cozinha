# cozinha
app for cooking 
<?xml version="1.0" encoding="utf-8"?> 
2    <ScrollView xmlns:android="http://schemas.android.com/apk/res/android" 
3        xmlns:tools="http://schemas.android.com/tools" 
4        android:layout_width="match_parent" 
5        android:layout_height="match_parent" 
6        tools:context="com.example.android.cozinha.COZINHA"> 
7     
8        <LinearLayout 
9            android:layout_width="match_parent" 
10           android:layout_height="match_parent" 
11           android:orientation="vertical"> 
12    
13           <RelativeLayout 
14               android:layout_width="match_parent" 
15               android:layout_height="300dp"> 
16    
17               <ImageView 
18                   android:layout_width="match_parent" 
19                   android:layout_height="290dp" 
20                   android:src="@drawable/fan" /> 
21    
22               <TextView 
23                   android:layout_width="wrap_content" 
24                   android:layout_height="wrap_content" 
25                   android:layout_alignParentBottom="true" 
26                   android:padding="16dp" 
27                   android:text="番茄炒蛋" 
28                   android:textColor="#673ab7" 
29                   android:textSize="30sp" /> 
30           </RelativeLayout> 
31    
32           <LinearLayout 
33               android:layout_width="match_parent " 
34               android:layout_height="wrap_content" 
35               android:orientation="vertical"> 
36    
37               <Button 
38                   android:layout_width="match_parent" 
39                   android:layout_height="wrap_content" 
40                   android:layout_margin="24dp" 
41                   android:onClick="submit营养" 
42                   android:text="营养" /> 
43    
44               <TextView 
45                   android:id="@+id/yingyang_text_view" 
46                   android:layout_width="match_parent" 
47                   android:layout_height="wrap_content" 
48                   android:gravity="center_horizontal" 
49                   android:text="surprise when you click on 营养！" /> 
50    
51               <Button 
52                   android:layout_width="match_parent" 
53                   android:layout_height="wrap_content" 
54                   android:layout_margin="24dp" 
55                   android:onClick="submit选材" 
56                   android:text="选材" /> 
57    
58               <TextView 
59                   android:id="@+id/xuancai_text_view" 
60                   android:layout_width="match_parent" 
61                   android:layout_height="wrap_content" 
62                   android:gravity="center_horizontal" 
63                   android:text="surprise when you click on选材 ！" /> 
64    
65               <Button 
66                   android:layout_width="match_parent" 
67                   android:layout_height="wrap_content" 
68                   android:layout_margin="24dp" 
69                   android:onClick="submit制作" 
70                   android:text="制作" /> 
71    
72               <TextView 
73                   android:id="@+id/zhizuo_text_view" 
74                   android:layout_width="match_parent" 
75                   android:layout_height="wrap_content" 
76                   android:gravity="center_horizontal" 
77                   android:text="surprise when you click on制作 ！" /> 
78    
79    
80               <Button 
81                   android:layout_width="match_parent" 
82                   android:layout_height="wrap_content" 
83                   android:layout_margin="24dp" 
84                   android:onClick="submit火候" 
85                   android:text="火候" /> 
86    
87               <TextView 
88                   android:id="@+id/huohou_text_view" 
89                   android:layout_width="match_parent" 
90                   android:layout_height="wrap_content" 
91                   android:gravity="center_horizontal" 
92                   android:text="surprise when you click on火候 ！" /> 
93    
94    
95               <Button 
96                   android:layout_width="match_parent" 
97                   android:layout_height="wrap_content" 
98                   android:layout_margin="24dp" 
99                   android:onClick="submit摆放" 
100                  android:text="摆放" /> 
101   
102              <TextView 
103                  android:id="@+id/baifang_text_view" 
104                  android:layout_width="match_parent" 
105                  android:layout_height="wrap_content" 
106                  android:gravity="center_horizontal" 
107                  android:text="surprise when you click on摆放！" /> 
108   
109   
110          </LinearLayout> 
111      </LinearLayout> 
112  </ScrollView>
