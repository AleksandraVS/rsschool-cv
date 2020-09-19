# Aleksandra Vrublevskaya

## Contacts

* VK --- [https://vk.com/egorkres](https://vk.com/egorkres)  
* Telegram ---  [https://t.me/vrublevskaya](https://t.me/vrublevskaya)
* Instagram ---  [https://www.instagram.com/vrublevska.ya/](https://www.instagram.com/vrublevska.ya/)
* Gmail --- [avrublevskaa@gmail.com](avrublevskaa@gmail.com)  
* Mobile number --- +375445498306  

## Details about me
> My goal is JS learning and employment. Now I am 2nd year student of BSU at the Faculty of Applied Mathematics and Computer science. I try to combine RS course and studying at the university.I have been studying C++, HTML and CSS for a year there. I realized that I like to solve problems more than to make up sites. So I also want to explore backend development. Perhaps my strength is the interest in the task, and the desire to learn new information.


## Skills
  - The beggining level of C++, HTML, CSS and JS

## Examples of code
### C++
```
#include <iostream>
using namespace std;
int main()
{
setlocale(0, "");
int rows, cols;
cout << "Введите число строк и столбцов:";
cin >> rows >> cols;
if (cols == rows || cols <= 1 || rows <= 1)
cout << "Недопустимое число столбцов или строк";
else
{

	int** arr = new int* [rows];
	for (int i = 0; i < rows; i++)
	{
		arr[i] = new int[cols];
	}

	for (int i = 0; i < rows; i++) {
		for (int j = 0; j < cols; j++)
		{
			cin >> arr[i][j];
		}
	}

	for (int i = 0; i < rows; i++) {
		for (int j = 0; j < cols; j++)
		{
			cout << arr[i][j] << " ";
		}
		cout << endl;
	}
	cout << endl;
	int sum = 0;
	for (int i = 0; i < rows; i++) {
		for (int j = 0; j < cols; j++)
		{
			if (arr[i][j] == 0)
			{
				for (int k = 0; k < rows; k++)
				{
					sum += arr[k][j];
				}
			}
		}
	}
	cout << " Сумма элементов в столбцах, содержащих хотя бы один ноль:" <<" "<< sum;
	for (int i = 0; i < rows; i++)
	{
		delete[] arr[i];
	}
	delete[] arr;
}
return 0;
}
```
# Education
### Completed courses
* [https://ru.code-basics.com/languages/javascript](https://ru.code-basics.com/languages/javascript) - JavaScript for beginners!
* [https://ru.code-basics.com/languages/css](https://ru.code-basics.com/languages/css)- CSS for beginners
* [https://ru.code-basics.com/languages/html](https://ru.code-basics.com/languages/html)- HTML for beginners
* [https://ru.hexlet.io/courses/introduction_to_programming](https://ru.hexlet.io/courses/introduction_to_programming) - Introduction to the programming

### English

The level of language proficiency: B1




