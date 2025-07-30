### 🧵 Pointer Constness Summary in C

| Declaration                | What is `const`?               | Can change pointer? | Can change value via pointer? |
|----------------------------|--------------------------------|---------------------|-------------------------------|
| `int *ptr`                 | Nothing                        | ✅ Yes              | ✅ Yes                        |
| `const int *ptr`           | The value pointed to           | ✅ Yes              | ❌ No                         |
| `int const *ptr`           | The value pointed to (same as above) | ✅ Yes        | ❌ No                         |
| `int * const ptr`          | The pointer itself             | ❌ No               | ✅ Yes                        |
| `const int * const ptr`    | Both pointer and pointed value | ❌ No               | ❌ No                         |
| `int const * const ptr`    | Both pointer and pointed value | ❌ No               | ❌ No                         |

