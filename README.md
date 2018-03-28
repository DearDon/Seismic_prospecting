# Seismic_prospecting
repo for shalow seismic prospecting calculation. It's the programming assignment for seismic prospecting class in May, 2012.

Problem set:
求4层介质的反射波的射线速度，均方根速度，平均速度,4层介质的速度与厚度分别为v1=1800m/s,h1=500m,v2=2000m/s,h2=1000m,v3=2500m/s,h3=1200m,v4=3000m/s,h4=1500m.

Solution from calculation
    解：由介质穿透4层介质可知在第三层界面的入射角必须小于临界角，由snell定理可推得第一层的入射角范围为［0，36.669297］（度），以步长为0.01rad编程根据推导公式计算不同入射角下的各速度，计算得均方根速度为2419.630000m/s,由于平均速度其实是射线速度的特例，用程序一并计算得出结果如下   
	angle           vr <br>
     0.000000  2389.380531 <br>
     0.572958  2389.396077 <br>
     1.145916  2389.442745 <br>
     1.718873  2389.520626 <br>
     2.291831  2389.629872 <br>
     2.864789  2389.770700 <br>
     3.437747  2389.943386 <br>
     4.010704  2390.148273 <br>
     4.583662  2390.385772 <br>
     5.156620  2390.656359 <br>
     5.729578  2390.960586 <br>
     6.302535  2391.299076 <br>
     6.875493  2391.672531 <br>
     7.448451  2392.081738 <br>
     8.021409  2392.527566 <br>
     8.594366  2393.010979 <br>
     9.167324  2393.533040 <br>
     9.740282  2394.094912 <br>
    10.313240  2394.697876 <br>
    10.886198  2395.343329 <br>
    11.459155  2396.032802 <br>
    12.032113  2396.767963 <br>
    12.605071  2397.550636 <br>
    13.178029  2398.382811 <br>
    13.750986  2399.266662 <br>
    14.323944  2400.204562 <br>
    14.896902  2401.199103 <br>
    15.469860  2402.253123 <br>
    16.042817  2403.369727 <br>
    16.615775  2404.552321 <br>
    17.188733  2405.804644 <br>
    17.761691  2407.130807 <br>
    18.334649  2408.535342 <br>
    18.907606  2410.023253 <br>
    19.480564  2411.600077 <br>
    20.053522  2413.271962 <br>
    20.626480  2415.045747 <br>
    21.199437  2416.929066 <br>
    21.772395  2418.930470 <br>
    22.345353  2421.059572 <br>
    22.918311  2423.327221 <br>
    23.491268  2425.745714 <br>
    24.064226  2428.329055 <br>
    24.637184  2431.093280 <br>
    25.210142  2434.056852 <br>
    25.783099  2437.241161 <br>
    26.356057  2440.671163 <br>
    26.929015  2444.376196 <br>
    27.501973  2448.391042 <br>
    28.074931  2452.757335 <br>
    28.647888  2457.525437 <br>
    29.220846  2462.757009 <br>
    29.793804  2468.528587 <br>
    30.366762  2474.936671 <br>
    30.939719  2482.105179 <br>
    31.512677  2490.196675 <br>
    32.085635  2499.429932 <br>
    32.658593  2510.108612 <br>
    33.231550  2522.670661 <br>
    33.804508  2537.779302 <br>
    34.377466  2556.505960 <br>
    34.950424  2580.744880 <br>
    35.523382  2614.334483 <br>
    36.096339  2667.141081 <br>
    36.669297  2785.349735 <br>
