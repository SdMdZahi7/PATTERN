# PATTERN

## 1)CREATE A PROGRAM FOR THE FOLLOWING PATTERN

![image](https://user-images.githubusercontent.com/94187572/224883208-e54268d1-99cd-4d93-8fa7-4638aad6c29b.png)


 
## INPUT CODE:
~~~
public class pattern1
{
    public static void main(String[]args)
    {
        for (int i=1;i<=5;i++)
        {
            for(int j=1;j<=5;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
~~~
## OUTPUT:
![image](https://user-images.githubusercontent.com/94187572/224883170-e8f31773-ddb5-4526-8443-cee915a7a61a.png)

## 2)CREATE A PROGRAM FOR THE FOLLOWING PATTERN
![image](https://user-images.githubusercontent.com/94187572/224883492-8a2319d2-9a90-4698-b2d6-32f64ddac927.png)

## INPUT CODE:
~~~
public class pattern2
{
    public static void main(String[]args)
    {
        int rows = 5;
        int count = 1;
        for (int i = rows; i >= 1; i--) 
	{
            for (int j = 1; j <= count; j++) 
	    {
                System.out.print(" ");
            }
            for (int k = 1; k <= 2 * i - 1; k++) 
	    {
                System.out.print("*");
            }
            System.out.println();
            count++;
        }
    }
}
~~~
## OUTPUT:
![image](https://user-images.githubusercontent.com/94187572/224883611-b106d510-0ca3-4f9d-9557-eb7465285d49.png)

## 3)CREATE A PROGRAM FOR THE FOLLOWING PATTERN
![image](https://user-images.githubusercontent.com/94187572/224883849-ab845d8a-d8a4-4bf2-aa88-8914504cb052.png)
 ## INPUT CODE:
 ~~~
 public class pattern3
{
    public static void main(String[]args)
    {
        int rows=5;
        for(int i=1; i<=rows;i++)
        {
            for(int j=1;j<=i;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
        for(int i=rows-1;i>=1;i--)
        {
            for (int j=1;j<=i;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
~~~

## OUTPUT:
![image](https://user-images.githubusercontent.com/94187572/224883955-60010aec-2dbc-4085-be55-98cecc661e38.png)



