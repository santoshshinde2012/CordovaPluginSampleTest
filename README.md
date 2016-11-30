# CordovaPluginSampleTest

#Commands
#Step1 :
       plugman create --name Test --plugin_id cordova.plugin.test --plugin_version 0.0.1
#Step2 :
       plugman platform add --platform_name android
#Step3 :
       plugman platform add --platform_name ios
#Stepe4 :
       ionic start IonicCordovaPluginTestApp blank
#Stepe5 : (In App Dir)
       ionic plugin add [Your local test plugin path]

       example :

       
       ionic plugin add /Users/Workspace/Test/CordovaPluginSampleTest/Test
#Step6 :  
       ionic platform add android or ios
