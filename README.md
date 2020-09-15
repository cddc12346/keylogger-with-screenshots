# keylogger-with-screenshots
This executable is a consoleless executable.Creates a log file (log.txt) in the same folder as the executable. Takes screenshot and save in the images directory every 10 seconds. 

How to use:
1) Paste the code into visual studio
2) Compile with settings _CRT_SECURE_NO_WARNINGS 
    Configuration Properties >> C/C++ >> Preporocessor >> Preprocessor Definitions >> _CRT_SECURE_NO_WARNINGS
3) Create a images folder directory in the same folder as the executable. Name the folder "images".
4) Run the executable
5) log file is log.txt, screenshots taken every 10seconds and saved in image folder(can manually change)
6) Remove the executable by:
    - tasklist
    - find the PID of application
    - taskkill /PID number /F
