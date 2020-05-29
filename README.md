# webtools
all different web tools to get problems  done in a rush.

JS function to get number of month from shortened form.  
```
function getMonthFromShortName(name) {
  var month = new Array();
  month["Jan"] = 0;
  month["Feb"] = 1;
  month["Mar"] = 2;
  month["Apr"] = 3;
  month["May"] = 4;
  month["Jun"] = 5;
  month["Jul"] = 6;
  month["Aug"] = 7;
  month["Sep"] = 8;
  month["Oct"] = 9;
  month["Nov"] = 10;
  month["Dec"] = 11;

  return  month[name];
}
```
JS function to get name of month from number form. 
```
function getMonthNumber(number) {
  var d = new Date();
  var month = new Array();
  month[0] = "January";
  month[1] = "February";
  month[2] = "March";
  month[3] = "April";
  month[4] = "May";
  month[5] = "June";
  month[6] = "July";
  month[7] = "August";
  month[8] = "September";
  month[9] = "October";
  month[10] = "November";
  month[11] = "December";
  if(number === null)
    return month[d.getMonth()];
   else return month[number];
}
```
UZBEK Language months
```
function getMonthFromNumber(number) {
    var d = new Date();
    var month = new Array();
    month[0] = "Yanvar";
    month[1] = "Fevral";
    month[2] = "Mart";
    month[3] = "Aprel";
    month[4] = "May";
    month[5] = "Iyun";
    month[6] = "Iyul";
    month[7] = "Avgust";
    month[8] = "Sentabr";
    month[9] = "Oktabr";
    month[10] = "Noyabr";
    month[11] = "Dekabr";
    if(number === null)
        return month[d.getMonth()];
    else return month[number];
}
```


week days with form short names 
```
function getWeekDayInNumber(name) {
  var weekDay = new Array();
  month["Mon"] = 0;
  month["Tue"] = 1;
  month["Wed"] = 2;
  month["Thu"] = 3;
  month["Fri"] = 4;
  month["Sat"] = 5;
  month["Sun"] = 6;

  return  weekDay[name];
}
```
Uzbek Language week days
```
function getDayInName(number = null) {
    var d = new Date();
    var week = new Array();
    week[1] = "Dushanba";
    week[2] = "Seshanba";
    week[3] = "Chorshanba";
    week[4] = "Payshanba";
    week[5] = "Juma";
    week[6] = "Shanba";
    week[7] = "Yakshanba";
    if(number === null)
        return week[d.getDay()];
    else return week[number];
}
```
