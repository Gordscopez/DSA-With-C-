# c++ Notes

 :white_check_mark: Compilers for windows <br>
    :pushpin: <b>MinGW</b> - provide gcc comppiler for windows.  (windows, Linux, Mac) <br>
    :pushpin: <b>MSVC</b>&nbsp;&nbsp; - microsoft visual studio code compiler. <br>
    :pushpin: <b>Clang llvm</b> (windows, Linux, Mac)
    
    
:white_check_mark: Look for c++ compiler support for c++20 standards


:white_check_mark: How to download<br>
    :pushpin: go to Winlibs.com <br>
    :pushpin: download latest version which contains LLVM/CLANG<br>
    <img src="https://user-images.githubusercontent.com/88723655/180235344-d822a621-d0e0-4c26-adc2-055b93ce0fe6.png" width="900" height="350" /> <br>
   :pushpin:  export content to <b>C Drive</b> using folder <b>MingW</b>.<br>
   :pushpin:  add bin folder to environment path variable. <br>
    <img src="https://user-images.githubusercontent.com/88723655/180237179-d9eaedce-2c35-49fe-8a37-52ec2100d5f1.png" width="700" height="350" /> <br>
    :relaxed::relaxed: Installation part is done :relaxed::relaxed:

:white_check_mark: Configure c/c++ in vscode. <br>
    :pushpin: Install c/c++ Extenstion by microsoft. <br>
    :pushpin: Terminal :point_right: configure tasks :point_right: select g++.exe :point_right: you get tasks.json. <br>
    change these in tasks.json :point_right: configuring which compiler to usee for c++ application <br>
    ![Screenshot 2022-07-21 195919](https://user-images.githubusercontent.com/88723655/180239486-1202d183-e133-4a09-be0c-e8128257defc.png) <br>
    :pushpin: for to make the compiler to work on c++20 standards, add "-std=c++20" in args array. <br>
    :pushpin: open new terminal, then terminal :point_right: run tasks :point_right: select compiler :point_right: builds our application. <b> .exe file</b> <br>
    ![Screenshot 2022-07-21 200911](https://user-images.githubusercontent.com/88723655/180241673-74d0f6d8-fdef-4030-b58d-d0e0eae88c17.png)<br>
    :pushpin: In terminal, execute application by <b>.\main.exe</b><br>
    ![Screenshot 2022-07-21 200846](https://user-images.githubusercontent.com/88723655/180241656-a0d2cdfa-e4cf-483d-bfe9-9b4d6d65e0bd.png) <br>
    :pushpin: settings :point_right: command palette :point_right: c/c++"Edit Configuration(UI) :point_right: c++ standard : c++20
    ![Screenshot 2022-07-21 200658](https://user-images.githubusercontent.com/88723655/180241165-c36eb427-5830-4c23-80df-194dcfe648b6.png) <br>

