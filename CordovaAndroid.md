#How to install Android plugin in Cordova

Step1 :<br/>
  cordova create <FOLDER_NAME> <APP_EXTENTION> <DISPLAY_NAME><br/>
  cordova create HelloWorld com.skc.HelloWorld HelloWorld<br/>
Step2 :<br/>
  Go inside the directory<br/>
  cd HelloWorld<br/>
Step3 : <br/>
  Add platform into it <br/>
  cordova platform add <PLATFORM_NAME><br/>
  cordova platform add android<br/>
Step4 :<br/>
  Install splash screen if you want to add (use $cordovaSplashScreen plugin)<br/>
Step5 :<br/>
  Replace your CSS/JS/HTML which is there is www directory<br/>
Step6 :<br/>
  Build the cordova platform<br/>
  cordova build <PLATFORM><br/>
  cordova build android<br/>
Step7:<br/>
  Import the build system into Android studio<br/>
  APP_DIR/platform/android<br/>
  
  <br/><br/><br/><br/><br/>
  
  https://www.youtube.com/watch?v=4jc6GqOaQl8
  
