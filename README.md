Maureen Lucia P. Quizon
INF247MWA
2024-1000141

Laboratory 0: Discussion

Discussion:  
The first problem I had was during the installation. I installed the Flutter SDK through VS Code, and after the download finished, nothing showed up, so I thought it was already done. The instructions said to click “Add SDK to PATH” after downloading, but that option never appeared to me. So, when I ran “flutter doctor -v” in cmd it didn’t work. I went to the environment variables settings and added the Flutter bin folder to PATH, after that the command worked. Another problem came from the flutter doctor itself. It showed that three things were missing: Android Studio, Visual Studio, and Chrome, since none of them are installed on my laptop. Android Studio is for the Android tools and emulators; Visual Studio is for Windows desktop apps, and Chrome is for running web apps. I didn’t install them for this activity because I could still run the project without them. 

  

The hands-on part went fine, and I didn’t have any problem there. The only thing I changed was the device. Since I don’t have Chrome, I ran the app on my Edge browser instead, and it worked the same way. Pushing to GitHub was also fine. I’ve already done it in my past projects, so the git commands were familiar to me and I didn’t need to look anything up. 

  

I learned that flutter doctor shows exactly which parts of the setup are still incomplete, so it’s good to run it right after installing. I also learned that PATH is what lets cmd find the flutter command, so if the SDK doesn’t add it by itself, I have to check it manually. For the next lab activity/project, I’ll check PATH right after installing the SDK and installing the tools I need (like Android Studio and Chrome) before starting. 
