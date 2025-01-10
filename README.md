# hello First Program java 
#All java 
#generic method
class Addition<T>
{
T a,b,z;
void sum(Number a,Number b)
{
Integer z=a.intValue() + b.intValue();
System.out.println(z+"sum ");
}
public static void main(String arg[])
{
Addition <Float> k=new Addition <Float>();
k.sum(23,28);
}
}
