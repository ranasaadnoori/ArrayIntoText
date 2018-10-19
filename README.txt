# ArrayIntoText
started by assuming array members are fixed 
var a = [1, 2, 1, 24];
 
for (var i=0; i< a.length;i++)
     {
       if (myFunction(a[i])) {
         document.write( "'" + myFunction(a[i]) + "'" + " ");}
     else{
          document.write("'" + "more than 2 digit" + "'" );
     }
         
    }
   
   function myFunction(p1) {
     if (p1==1 ) {return ("one")}
     if (p1==2 ) {return ("two")}
     if (p1==3 ) {return ("Three")}
     if (p1==4 ) {return ("Four")}
     if (p1==5 ) {return ("Five")}
     if (p1==6 ) {return ("Six")}
     if (p1==7 ) {return ("Seven")}
     if (p1==8 ) {return ("Eight")}
     if (p1==9 ) {return ("Nine")}
     if (p1==0 ) {return ("zero")}
2 started looking on how to insert dynamic array found a useful article on stack overflow and started editing from there.
3 finished the job
