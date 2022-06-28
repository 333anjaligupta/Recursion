# Recursion(fibonacci series)
class Fibonacci{
if(n==o){
return 0;
if(n==1)
return 1;
int recResults1=fibo(n-1);
int recResults2=fibo(n-2);
int smallCal=recResults1+recResults2;
return smallcal;
}
}

