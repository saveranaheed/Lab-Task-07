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

