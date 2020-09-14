# keylogger-with-screenshots
How to use:
1) Paste the code into visual studio
2) Compile with settings _CRT_SECURE_NO_WARNINGS 
Configuration Properties >> C/C++ >> Preporocessor >> Preprocessor Definitions >> _CRT_SECURE_NO_WARNINGS
3) Create a image folder directory in the same folder as the executable
4) Run the executable
5) log file is log.txt, screenshots taken every 10seconds and saved in image folder(can manually change)
6) Remove the executable by:
    - tasklist
    - find the PID of application
    - taskkill /PID number /F
