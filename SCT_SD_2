#include <iostream>
#include <cstdlib>  // For rand() and srand()
#include <ctime>    // For time()

using namespace std;

int main() {
    // Initialize random seed
    srand(time(0));

    // Generate a random number between 1 and 100
    int target = rand() % 100 + 1;
    int guess;
    int attempts = 0;

    cout << "Welcome to the Number Guessing Game!" << endl;
    cout << "I have chosen a number between 1 and 100." << endl;
    cout << "Try to guess it!" << endl;

    // Game loop
    do {
        cout << "\nEnter your guess: ";
        cin >> guess;
        attempts++;

        if (guess > target) {
            cout << "Too high! Try again.";
        } else if (guess < target) {
            cout << "Too low! Try again.";
        } else {
            cout << "Congratulations! You guessed the number in " << attempts << " attempts!" << endl;
        }

    } while (guess != target);

    return 0;
}
