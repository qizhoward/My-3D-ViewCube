# My-3D-ViewCube

>My Idea 
>>Want To Write programm and Hand Drawing
>>>img pic
>>>>Embedded Opera（open public) CubeView System 


 I want to use Java c c# and c++ to write a program platform spport 3dmax solidworks and blender viewcube... </br>
 But I don't know how to write it... 


O(0,0,0); X,0; Y,0; Z,0;***** ****space**********//ordinary point 普通点            </br>
XY(0,0);**********space*************************//ordinary surface 普通面           </br>
XZ;XY;ZY**********space*************************//组合体                            </br>

3D use vector show box :***************************space***********************</br>                                            
O(0,0,0)******space*************//vector point 向量点                           </br>
O(0,0);(0,0)******space*********//vector 向量                                   </br>
Ov(0,0);(0,H/Z)******space******//vector 向量                                   </br>
Xv(0,0)(H,0)******space*********//vector 向量                                   </br>
Yv(0,0)(W,0)******space*********//vector 向量                                   </br>
Zv(0,H/Z)(H,W)******space*******//vector 向量                                   </br>
or 或                                                             </br>
Zv(0,H/Z);(0,0)(H,0);(0,0)(W,0) //vector 向量                     </br>
vector point v1;vector point v2;vector point v3; //点1；点2；点3   </br>

              north                    north               north                      north
                1                       +1                    +1           +1             1             1
               (2)                     (+2)                    (+2)     (+2)                (2)     （2）
                1                       +1                       +1    +1                     1     1
      -1/(-2)-1.0.1(2)/1       -1/(-2)-1.0.+1(+2)/+1                 0                           0
               -1                       -1                       -1    -1                    -1    -1
              (-2)                     (-2)                    (-2)     (-2)                (-2)    （-2） 
               -1                       -1                   -1            -1             -1           -1
              west                     west                                west                          west  
              
     north                       north                     north                      north
        1           1             2           2               2           2               0            0
         (2)     (2)2              (1)      (1)                (1)     (1)                 (1)      (1)
            1   1   1                2     2                     0     0                      0     0
              0 2 1 2                   1                           1                            1
           -1  -1                   -2    -2                     0     0                      0     0
         (-2)   (-2)              (-1)     (-1)               (-1)     (-1)                (-1)     (-1)
       -1          -1           -2            -2             -2           -2              0             0
                     west                     west                         west                          west
                       |   
                       | 
    like a Stereoscopic（three dimensional）Interlayer？ 
    
    north                      
        1           1                   1            0
         (2)     (2)2            north  2            2          2         0         2         1
            1   1   1                   1            1          1         1         1   north 2
              0 2 1 2             0 2 1 2      1 2 1 2      2 1 2     0 1 0     2 1 2     1 2 1
           -1  -1                      west                                                   west
         (-2)   (-2)             
       -1          -1                   >          >          >         >         >       new
                     west              <          <          <         <         <        old
                     
                                        >          >          >         >         >    next oled?
                                       <          <          <         <         <      
                                     |      >      >          >         >    >       | 
                                     |     <      <          <         <    <        | 
                                     |      >                >               >       |
                                     |-----------------------------------------------| 
                                                      
                                a new (shower room / bathroom)and girlfriend japan noodles 
                                                                                     spaghetti?                            
                                                                          
    Recon structing
    again structure
     iug nre
     struct                      v
    like a wave............   haha~:)    
    like apple............       v
             
___ [] the work? Like?as? time box?</br>
        some container box..........</br>
   you must thinking before..........</br>
       
         2           2          2         2                           2                    2
       1<->1     1<<<->>>1     1-1       <->                        1<->1                1<->1
      2<<->>2     2<<->>2     2<->2    2<<->>2     0<->0           2<<->>2              2<<->>2
     1<<<0>>>1     1<0>1     1<<0>>1    1<0>1     1<<0>>1         1<<<0>>>1            1<<<0>>>1  
      2<<->>2     2<<->>2     2<->2    2<<->>2     0<->0       1 1 2<<->>2 1 1      1 1 2<<->>2 1 1 
       1<->1     1<<<->>>1     1-1       <->                    2   1<->1   2        2   1<->1   2
         2           2          2         2                    1<<<<<<0>>>>>>1      1<<<<<<2>>>>>>1
                                                                2<1-1>1<1-1>2        2<1-1>1<1-1>2
                                                                  <0>   <0>            <2>   <2>
                                                                   1     1              1     1 
------------------------------------------------------------------------------------------------------------------------    

         2           2          2         2                           2                 1     1
       1<->1     1<<<->>>1     1-1       <->                        1<->1              <2>   <2>
      2<<->>2     2<<->>2     2<->2    2<<->>2     0<->0           2<<->>2           2<1-1>1<1-1>2
     1<<<+>>>1     1<+>1     1<<+>>1    1<+>1     1<<+>>1         1<<<+>>>1         1<<<<<<2>>>>>>1
      2<<->>2     2<<->>2     2<->2    2<<->>2     0<->0         1 2<<->>2 1         2   1<->1   2
       1<->1     1<<<->>>1     1-1       <->                    2   1<->1   2       1 1 2<<->>2 1 1
         2           2          2         2                    1<<<<<<2>>>>>>1         1<<<0>>>1
                                                                2<1-1>1<1-1>2           2<<->>2
                                                                  <2>   <2>              1<->1
                                                                   1     1                 2
------------------------------------------------------------------------------------------------------------------------
       
         2           2          2         2                           2                 1     1
       1<+>1     1<<<+>>>1     1+1       <+>                        1<+>1              <2>   <2>
      2<<+>>2     2<<+>>2     2<+>2    2<<+>>2     0<+>0           2<<+>>2           2<1+1>1<1+1>2
     1<<<->>>1     1<->1     1<<->>1    1<->1     1<<->>1         1<<<->>>1         1<<<<<<2>>>>>>1
      2<<+>>2     2<<+>>2     2<+>2    2<<+>>2     0<+>0         1 2<<+>>2 1         2   1<+>1   2
       1<+>1     1<<<+>>>1     1+1       <+>                    2   1<+>1   2       1 1 2<<+>>2 1 1
         2           2          2         2                    1<<<<<<2>>>>>>1         1<<<0>>>1
                                                                2<1+1>1<1+1>2           2<<+>>2
                                                                  <2>   <2>              1<+>1
                                                                   1     1                 2
------------------------------------------------------------------------------------------------------------------------   
         
         2           2          2         2                           2                    2
       1<+>1     1<<<+>>>1     1+1       <+>                        1<+>1                1<+>1
      2<<+>>2     2<<+>>2     2<+>2    2<<+>>2     0<+>0           2<<+>>2              2<<+>>2
     1<<<0>>>1     1<0>1     1<<0>>1    1<0>1     1<<0>>1         1<<<0>>>1            1<<<0>>>1  
      2<<+>>2     2<<+>>2     2<+>2    2<<+>>2     0<+>0       1 1 2<<+>>2 1 1      1 1 2<<+>>2 1 1 
       1<+>1     1<<<+>>>1     1+1       <+>                    2   1<+>1   2        2   1<+>1   2
         2           2          2         2                    1<<<<<<0>>>>>>1      1<<<<<<2>>>>>>1
                                                                2<1+1>1<1+1>2        2<1+1>1<1+1>2
                                                                  <0>   <0>            <2>   <2>
                                                                   1     1              1     1 
------------------------------------------------------------------------------------------------------------------------  
                                                                                
                                      
     1+1   1+1   1+1 1+1   1+1   1+1   
      1  +  1     1 + 1     1  +  1     
         1    +     1     +    1       
              1     +     1             
                    1                   
                    |                           
                    1                   
              1     +     1             
         1    +     1     +    1                 
      1  +  1     1 + 1     1  +  1     
     1+1   1+1   1+1 1+1   1+1   1+1    
------------------------------------------------------------------------------------------------------------------------   

                    1                   
              1     +     1             
         1    +     1     +    1                   
       1  +  1    1 + 1     1  +  1     
     1+1   1+1   1+1 1+1   1+1   1+1    
    ----------------|---------------   
     1+1   1+1   1+1 1+1   1+1   1+1    
      1  +  1     1 + 1     1  +  1     
         1    +     1     +    1        
              1     +     1             
                    1                   
------------------------------------------------------------------------------------------------------------------------                     
                    
                    1
              1     +     1
         1    +     1     +    1                  
      1  +  1     1 + 1     1  +  1 
     1+1   1+1   1+1 1+1   1+1   1+1 
    ----------------|--------------- 
        1+1   1+1   1+1 1+1   1+1   1+1
         1  +  1     1 + 1     1  +  1
            1    +     1     +    1
                 1     +     1
                       1
                       
                       
                       
                       
                       
                       
                       
                       
        I want to learn international chess and what is King car translocation...........
                                                        car king ?
            A B C D E F G H
          1                 1
          2                 2
          3                 3
          4                 4
          5                 5
          6                 6
          7                 7
          8 A B C D E F G H 8   Mr. ?
          
          
                            cool card...................
                            It means three heart two love
               
               
           the wows game is...
            (World of warships)
            
            A B C D E F G H I J
          1                    1
          2                    2
          3                    3
          4                    4
          5                    5
          6                    6
          7                    7
          8                    8         
          9                    9
          10                   10
            A B C D E F G H I J                
                            
                           
                            
                           
                            
                 
------------------------------------------------------------------------------------------------------------------------ 
      
      maybe the key house is u_dish ? 8kb 8mb 8gb 8tb..... c c++ c# but more chinese people don't know..
                                                                    just like Snail...slow.. and too people growing old.
           /------\
          /        \
         /          \
        /            \    
       |--------------|
       |              |
       |      ---     |
       |     | . |    |
       |-----|---|----|
      
        Iron Man key .......
      
      YuPeng 2018.09.21    </br>
       余鹏 2018.09.21     </br>
       
