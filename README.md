# emergency

''' 


this is a script is used to automate the call of emergency numbers with any sim card in TN region using the uiautomator2 & weditor package
this code can lunch an automatic test case and return test results and other parameters

prequisites:
1- insert any sim card in DUT
2- install latest SW version in the DUT
3- install necessary packages in the computer and in the DUT to enable the communication
4- install any python editor or run the weditor tool via windows shell

tesks executed by this script:
1- connect the DUT to the computer and pop up a UI selector (ATXWeditor)
2- open the phone dialer and tap the emergency number
3- make the call & open the speaker mode
4- let the call run for 10s then end it
5- return the test result and the speaker status

QTTN ©

'''
