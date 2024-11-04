- 👋 Hi, I’m @LiBP111
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
LiBP111/LiBP111 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<iostream>
using namespace std;
int main()
{
	int arr[3];
	for (int i = 0; i < 3; i++) {
		cin >> arr[i];
	}
	for (int j = 0; j < 3; j++) {
		for (int i = 0; i < 3; i++) {
			if (arr[i] > arr[i + 1]) {
				int a = arr[i];
				arr[i] = arr[i + 1];
				arr[i + 1] = a;
			}
		}
	}
	for (int i = 0; i < 3; i++) {
			cout << arr[i] << ",";
	}
}
