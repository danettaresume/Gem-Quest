#include <iostream>
int main() {
    int number;
    int place;

    std::cout << "Hello Doom. I'm daring you to find 1 of 3 gems. The MG is in Asgard, the RG is in the Savage Land, and the TG is on Krakoa.\n";
    std::cout << "Where would you like to go? (Enter 1 for Asgard, 2 for Savage Land, 3 for Krakoa)\n";
    std::cin >> place;

    if (place == 1) {
        std::cout << "Welcome to Asgard!\n";
        std::cout << "Answer this question correctly and you will get the Mind Gem. How many people are in the FF?\n";
        std::cin >> number;
        if (number == 4) std::cout << "✅ You found the Mind Gem!\n";
        else std::cout << "❌ Wrong answer.\n";
    } else if (place == 2) {
        std::cout << "Welcome to the Savage Land!\n";
        std::cout << "Answer this question correctly and you will get the Reality Gem. What is the number on Reed Richard's suit?\n";
        std::cin >> number;
        if (number == 4) std::cout << "✅ You found the Reality Gem!\n";
        else std::cout << "❌ Wrong answer.\n";
    } else if (place == 3) {
        std::cout << "Welcome to Krakoa!\n";
        std::cout << "Answer this question correctly and you will get the Time Gem. How many letters are in the word 'Four'?\n";
        std::cin >> number;
        if (number == 4) std::cout << "✅ You found the Time Gem!\n";
        else std::cout << "❌ Wrong answer.\n";
    } else {
        std::cout << "Invalid choice. Please enter 1, 2, or 3.\n";
    }
    return 0;
}
