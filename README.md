# Stack-Data-Structure

## A Stack is a linear data structure that follows a particular order in which the operations are performed. The order may be LIFO(Last In First Out) or FILO(First In Last Out). LIFO implies that the element that is inserted last, comes out first and FILO implies that the element that is inserted first, comes out last.

<h2>It behaves like a stack of plates, where the last plate added is the first one to be removed. Think of it this way:

Pushing an element onto the stack is like adding a new plate on top.
Popping an element removes the top plate from the stack.</h2>

<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20230726165552/Stack-Data-Structure.png"> 

# Code :

```
#include <iostream>
#include <stack>
using namespace std;

int main() {
    stack<int> st;

    // Pushing elements onto the stack
    st.push(1);
    st.push(2);
    st.push(3);

    while(!st.empty()) {
        cout << st.top() << " ";
        st.pop();
    }
    return 0;
}

```

# Output 
```
3 2 1 
```
# Complexity
Time Complexity : O(1)
