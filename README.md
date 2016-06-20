interface shape { 
    void draw();
    static int area(float x,float y){
        return xy;
    }
        
}
class Rectangle implements shape { 
    public void area(float x,float y) {
        return xy; 
        }
    public void draw() {
        draw(); 
        }
    }
class Square implements shape {
    public void area(float x,float y) {
        return xy;
        } 
    public void draw() {
        draw(); 
        } 
    }
class mainclass { 
    public static void main(String[] args) {
        Rectangle r =new Rectangle(); 
        Square s=new Square();
        shape A; 
        A=r; 
        System.out.println("area of rect" +A); 
        A=s;
        System.out.println("area of squa" +A);
        }
    }
