#include <iostream>

int main() {
    int n;

    // 1. Get the upper limit from the user
    std::cout << "Enter the upper limit (n): ";
    std::cin >> n;

    // Input validation (optional but recommended)
    if (n < 1) {
        std::cout << "Please enter a positive integer." << std::endl;
        return 1; // Indicate an error
    }

    std::cout << "Printing numbers from 1 to " << n << ":" << std::endl;

    // 2. Loop and print the numbers
    // The loop starts at i=1, continues as long as i <= n, and increments i by 1 each time.
    for (int i = 1; i <= n; ++i) {
        std::cout << i << std::endl;
    }

    return 0;
}
