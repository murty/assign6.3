interface shape()
{
draw();
area(float x,float y);
}
class rect implements shape()
{
public area(float x,float y)
{
return(x*y);
}
public draw()
{
draw(rectangle);
}
}
class squa implements shape()
{
public area(float x,float y)
{
return(x*y);
}
public draw()
{
draw(square);
}
}
class mainclass(){
public static void main(string[] args)
{
rect r =new rect();
squa s=new squr();
shape A;
A=r;
system.out.println("area of rect"+A);
A=s;
system.out.println("area of squr"+A);
}
}
