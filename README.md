interface twoimpl()
{
display(integer x);
}
class first implements Twoimpl()
{
public display (integer x)
{
return x;
}
}
class second implements twoimpl()
{
public display (integer x)
{
return x*x;
}
}
class both()
{
public static void main(string[] args){
first one =new first();
second two =new second();
Twoimpl twoimpl;
twoimpl=one;
system.out.println("value is " +twoimpl);
twoimpl=two;
system.out.println("value is " +twoimpl);
}
}
