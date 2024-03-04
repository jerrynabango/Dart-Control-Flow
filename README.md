## Control Flow in Dart

Control flow in Dart refers to how the program's execution path is determined based on conditions and decisions made during runtime. Dart provides various control flow structures to manage the flow of execution in your code.

### Conditional Statements

Conditional statements allow you to execute different blocks of code based on specified conditions. Dart supports the following conditional statements:

- **if Statement:** Executes a block of code if a specified condition is true.
- **else Statement:** Executes a block of code if the same condition of the if statement is false.
- **else if Statement:** Executes a block of code if the preceding condition of the if statement is false and the specified condition is true.
- **switch Statement:** Allows you to select one of many blocks of code to be executed based on the value of an expression.

### Looping Statements

Looping statements enable you to execute a block of code repeatedly based on certain conditions. Dart provides the following looping statements:

- **for Loop:** Executes a block of code a specified number of times.
- **while Loop:** Executes a block of code as long as a specified condition is true.
- **do-while Loop:** Executes a block of code once before checking if the condition is true, then repeats the loop as long as the condition is true.

### Example:

```dart
void main() {
  int number = 5;

  // if-else conditional statement
  if (number > 0) {
    print('$number is a positive number.');
  } else {
    print('$number is a negative number.');
  }

  // for loop
  print('Counting from 1 to 5:');
  for (int i = 1; i <= 5; i++) {
    print(i);
  }

  // while loop
  int countdown = 3;
  print('Counting down:');
  while (countdown > 0) {
    print(countdown);
    countdown--;
  }

  // do-while loop
  int countdownBackwards = 3;
  print('Counting backwards:');
  do {
    print(countdownBackwards);
    countdownBackwards--;
  } while (countdownBackwards > 0);
}
```
