#include <iostream>
using namespace std;

int main() {
    string pattern[5] = {
        "  *****      *       *****     *****  ",
        " *          * *      *     *   *     * ",
        "  *****    *****     *****     *****  ",
        "       *   *   *     *     *   *     * ",
        "  *****    *   *     *****     *****  "
    };

    for (int i = 0; i < 5; i++) {
        cout << pattern[i] << endl;
    }

    return 0;
}
