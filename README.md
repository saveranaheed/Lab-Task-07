# Lab-Task-07
TASK#01:
```cpp
#include <iostream>
using namespace std;
int main() {
    int size;
    cout << "Enter the number of scores: ";
    cin >> size;
    int* scores = new int[size];
    for (int i = 0; i < size; i++) {
        cout << "Enter score " << (i + 1) << ": ";
        cin >> scores[i];
    }
    cout << "\nScores:\n";
    for (int i = 0; i < size; i++) {
        cout << scores[i] << endl;
    }
    delete[] scores;
    return 0;
}
```

OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/8f3e3a87-ef23-4aa1-8c9d-9dd5293fde6e)

TASK#02:
```cpp
#include <iostream>
using namespace std;
int main() {
    const int numStudents = 10;
    int hours[numStudents];
    for (int i = 0; i < numStudents; i++) {
        cout << "Enter hours studied by student " << (i + 1) << ": ";
        cin >> hours[i];
    }
    cout << "\nHours studied by each student:\n";
    for (int i = 0; i < numStudents; i++) {
        cout << "Student " << (i + 1) << " studied for " << hours[i] << " hours.\n";
    }
    return 0;
}
```

OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/59de20f4-64a9-4023-8532-94469857e527).

TASK#03:
```cpp
#include <iostream>
using namespace std;
int main() {
    int count = 0, num;
    cout << "Enter 7 integers:\n";
    for (int i = 0; i < 7; i++) {
        cin >> num;
        if (num % 5 == 0) {
            count++;
        }
    }
    cout << "There are " << count << " multiples of 5.\n";
    return 0;
}
```

OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/13a24b63-6288-4351-9d15-9adafde55241)

TASK#04
```cpp
#include <iostream>
using namespace std;
int main() {
    int numbers[10];
    for (int i = 0; i < 10; i++) {
        cin >> numbers[i];
    }
    for (int i = 9; i >= 0; i--) {
        cout << numbers[i] << " ";
    }
    return 0;
}
```
OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/a0b8df2b-070d-4331-9e26-9dcff60ba832)

TASK#05
```cpp
#include <iostream>
using namespace std;
int main() {
    int num, positive = 0, negative = 0, odd = 0, even = 0, zero = 0;
    for (int i = 0; i < 10; i++) {
        cin >> num;
        if (num > 0) positive++;
        else if (num < 0) negative++;
        else zero++;
        if (num != 0) {
            if (num % 2 == 0) even++;
            else odd++;
        }
    }
    cout << "Positive: " << positive << "\n";
    cout << "Negative: " << negative << "\n";
    cout << "Odd: " << odd << "\n";
    cout << "Even: " << even << "\n";
    cout << "Zero: " << zero << "\n";
    return 0;
}
```

OUTPUT:

![Program
Output](https://github.com/user-attachments/assets/d9ce6936-4187-4ec0-b0dd-3ba0bd430000)



