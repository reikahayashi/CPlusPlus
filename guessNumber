#include <iostream>

using namespace std;



int main(){
 
    int secretNum = 10;
    int guess;
    int guessCount = 0;
    int guessLimit = 5;
    bool outOfGuesses = false;
    
    
    while (secretNum != guess && !outOfGuesses){
        if (guessCount < guessLimit){
            cout << "Enter guess: ";
            cin >> guess;
            guessCount++;
        }
        else {
            outOfGuesses = true;
        }
        
    }
    
    if (outOfGuesses){
        cout << "You Lose! \n";
        
    }
    else{
        cout << "You Win!\n";
    }
    return 0;
}
