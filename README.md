class addition
{
    void add(int a, int b)
    {
        System.out.println("The sum is: "+(a+b));
    }
    void add(double a, double b)
    {
        System.out.println("The sum is: "+(a+b));
    }
    void add(float c,float d)
    {
        System.out.println("The sum is: "+(c+d));
    }
    void add(int h, double f)
    {
        System.out.println("The ans is: "+(h+f));
    }
    public static void main()
    {
        addition obj = new addition();
        obj.add(7,8.5);
        obj.add(9,11);
        obj.add(6.7f,11.2f);
        obj.add(2.3,7.5);
    }
