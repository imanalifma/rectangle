class HelloWorld {
    public static void main(String[] args) {
       Rectangle rect = new Rectangle(5,9,"blue");
       //rect.calculateArea();
       System.out.println("Area = "+ rect.calculateArea());
           Rectangle obj = new Rectangle(4,6,"blue");
           System.out.println("NewArea = "+ obj.calculateArea());
           Rectangle clr = new Rectangle(3,2,"blue");
            String colour = clr.getColour();
           System.out.println("NewArea = "+ colour);
       
    }
}
class Rectangle{
            
           int _length;
           int _width;
           String _colour;
          // int _area;
           
           public Rectangle(int length, int width, String colour){
           _length = length;
           _width = width;
           _colour=colour;
           
           
              
           }
          public int calculateArea(){
         
            return _width * _length;
      }
      public String getColour(){
           String mycolour=_colour;
          return mycolour;
          
      }
}
