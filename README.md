#include <stdio.h>  // For printf

#include <cs50.h>   // For get-string

int main(void)
{
    // Get user's name as a string
    string name = get_string("What's your name? ");

    // Print greeting
    printf("Hello, %s!\n", name);

    return 0;
}
