# webtools
all different web tools to get problems  done in a rush.

JS function to get number of month from shortened form.  
```
function getMonthInNumber(name) {
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
function getMonthInNumber(number) {
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
