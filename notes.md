
#  error  #


## error / trait.php ##


 - global function `error (  anyToStringAble  $msg,   anyToStringAble  $add_data  ) `
 
 - - ` (function(){ error_log("Test"); })() `


 - method `error (  anyToStringAble  $msg,   anyToStringAble  $add_data  ) `

 - method `error_log (  anyToStringAble  $msg,   anyToStringAble  $add_data  ) `

 - method `error_die `


 - gen_error

 - on_shutdown


 ? - global function `error (  anyToStringAble  $msg,   anyToStringAble  $add_data  ) ` (f_error.php)





##  Identification  ##


###  Hash-ID  ###

[...]



###  Categorization  ###


####  "PHP_THOUGHT"  ####

`trigger_error(..)` / `new Exception(...)` / `error(..)`


[...]


####  "JS_THOUGHT" ####

`trigger_error(..)` / `new Exception(...)` / `error(..)`

[...]


####  "PHP_EXEC" & "JS_EXEC"  ####

`Unexpected typeof arg...`

[...]






##  error / rules.php  ##







##  Real Error Samples  ##


=================================================
[1] [JS_OWN] [2020-07-20 11:56:11] e7ff320223da44d527b6817ecfa1c0ef

Maximum length of 2 exceeded on field "sygdom", but got "4"

[UPDATE] /API/shifts-activities/shifts-edit.php:218->getUpdateQuery (inst. of cl. "vagter")



=================================================
[JS_OWN] e7ff320223da44d527b6817ecfa1c0ef

[1] 2020-07-19 14:47:59

Failed to create user. Error "Failed to fetch" TypeError: Failed to fetch

https://cdn.onesignal.com/sdks/OneSignalPageSDKES6.js



=================================================
[UNKNWN] 2a898b756a437591f1bd529047d6af27

[1] 2020-07-17 23:17:37

[POST] /API/employees-schedule/vacation.php:80
DB_Models/vagter.php:93->getInsertQuery
Data-type mismatch on field "vagt_slut"; expected "time", but got "x" as "string"

[native code]
https://cdn.onesignal.com/sdks/OneSignalPageSDKES6.js?v=151002:1:63166



=================================================
[JS_OWN] f0dd3de343726be3f86e5ae41e134a33

[2] 2020-07-08 19:52:04 - 2020-07-08 19:52:04

Database PUT Transaction Error:

[native code]
https://cdn.onesignal.com/sdks/OneSignalPageSDKES6.js?v=151002:1:63166



=================================================
[JS_OWN] 3bd99bb27f17becd16e5b608cbba64db

[1] 2020-07-17 11:25:39

Error in AJAX request

[GET] /API/login



=================================================
[UNKNWN] a0b904f03caad873fec8ada5a3e40b9c

[3] 2020-07-17 09:36:11
  - 2020-07-17 09:35:29

Error in AJAX request

[POST] /API/statistics
{
	"date_from":"2020-06-19",
	"date_to":"2020-07-18",
	"module":"va",
	"employees":[],
	"dep":-3,
	"method":"GET_VA_DATA"
}

AJAX_REL: 41e3251028d3dca0d7b444de778d7235





