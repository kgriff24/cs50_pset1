//# cs50_pset1
//# this is my first real issue with this class mario.c


#include <stdio.h>
#include <cs50.h>

int main(void)
{
    int tall;
    int rows;
    int spaces;
    int hashes;

    do
    {
        // User input
        printf("Height: ");
        int tall = get_int();

    while (tall < 0 || tall > 23);
}
    // Rowspaces
    for (rows = 0; rows < tall; rows++)
    {
        // Spaces
        for (spaces = tall - 1; spaces > rows; spaces--)
        {
            printf(" ");
        }
        // Hasp
        for (hashes = tall - spaces; hashes < tall + 2; hashes++)
        {
            printf("#");
        }
        printf("\n");
    }
}
