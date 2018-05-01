cpp work1
```
#include <iostream>
using namespace std;

int main()
{
  const int NUMBER_OF_ELEMENTS = 5;
  double numbers[NUMBER_OF_ELEMENTS];
  double numbers_squared[NUMBER_OF_ELEMENTS];
  double sum = 0;

  for (int i = 0; i < NUMBER_OF_ELEMENTS; i++)
  {
    cout << "請輸入一個整數: ";
    cin >> numbers[i];
    sum += numbers[i];
    numbers_squared[i]=numbers[i]*numbers[i];
  }
  
  cout << "numbers[1] is " << numbers[1] << endl;
  cout << "numbers_squared[1] is " << numbers_squared[1] << endl;

  double average = sum / NUMBER_OF_ELEMENTS;

  int count = 0; // The number of elements above average
  for (int i = 0; i < NUMBER_OF_ELEMENTS; i++)
    if (numbers[i] > average)
      count++;



  return 0;
}
```
![image](https://github.com/s0970755289/CPP/blob/master/diary/%E6%93%B7%E5%8F%96.PNG)
```
CPP WORK2

#include <iostream>
#include <iomanip>
using namespace std;
int fun(int array[3][3])
{
	int i,j,t;
	for(i=0;i<3;i++)
		for(j=0;j<i;j++)
		{
			t=array[i][j];
			array[i][j]=array[j][i];
			array[j][i]=t;
		}
		return 0;
}
int main()
{
	int i,j;
	int array[3][3]={{1,2,3},{4,5,6},{7,8,9}};
	
	cout << "Converted Front" <<endl;
	for(i=0;i<3;i++)
	{
		for(j=0;j<3;j++)
			cout << setw(7) << array[i][j] ;
		cout<< endl;
	}
	fun(array);
	cout << "Converted result" <<endl;
	for(i=0;i<3;i++)
	{
		for(j=0;j<3;j++)
			cout << setw(7) << array[i][j] ;
		cout<< endl;
	}
    return 0;
}
```
![image](https://github.com/s0970755289/CPP/blob/master/02.PNG)
```
物件導向作業1
```
#include <iostream>
using namespace std;

class Sphere
{
public:
  // The radius of this circle
  double radius;

  // Construct a default circle object
  Sphere()
  {
    radius = 1;
  }

  // Construct a circle object
  Sphere(double newRadius)
  {
    radius = newRadius;
  }

  // Return the area of this circle
  double getArea()
  {
    return radius * radius * radius * 4/3 * 3.14159;
  }
};  // Must place a semicolon here

int main()
{
  Sphere Sphere1(1.0);
  Sphere Sphere2(25);
  Sphere Sphere3(125);

  cout << "The area of the Sphere of radius "
    << Sphere1.radius << " is " << Sphere1.getArea() << endl;
  cout << "The area of the Sphere of radius "
    << Sphere2.radius << " is " << Sphere2.getArea() << endl;
  cout << "The area of the Sphere of radius "
    << Sphere3.radius << " is " << Sphere3.getArea() << endl;

  // Modify circle radius
  Sphere2.radius = 100;
  cout << "The area of the Sphere of radius "
    << Sphere2.radius << " is " << Sphere2.getArea() << endl;

  return 0;
}
```
![image](https://github.com/s0970755289/CPP/blob/master/diary/%E7%89%A9%E4%BB%B6%E5%B0%8E%E5%90%91.PNG)
```
exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

exercise1

