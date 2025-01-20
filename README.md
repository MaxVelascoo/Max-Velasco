![github-header-image](https://github.com/user-attachments/assets/cf5a8a3a-32e6-44f3-9bd3-ccde1144f923)
```c++
#include <iostream>
#include <string>
#include <vector>
using namespace std;

class SoftwareEngineer {
public:
    string name, role;
    vector<string> languagesSpoken;

    SoftwareEngineer(const string& n, const string& r, const vector<string>& lang)
        : name(n), role(r), languagesSpoken(lang) {}

    void sayHi() const {
        cout << "Hi, I am " << name << ". " << role << "\n";
    }
};

int main() {
    SoftwareEngineer max("Max Velasco Rajo", "Curious Explorer", {"es_ES", "en_US"});

    max.sayHi();

    return 0;
}
```
