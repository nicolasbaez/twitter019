# twitter019
#つぶやきProcessing void setup(){size(500,500);}float i,k,n=375,m=250,q=125,o=50;void draw(){clear();stroke(255,o);fill(#666699,random(o));rect(q,o,m,n);line(m,o,m,425);line(q,q,n,q);for(i=q;i&lt;n;i++){line(i,o,i+100,map(sin(radians(i/2+k))+cos(radians(2*i+k)),-2,2,500,m));}k+=9;}
