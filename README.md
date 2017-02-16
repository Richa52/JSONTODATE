# JSONTODATE


 var jsonDate = "/Date(1349301600000+0200)/";
var date1 = new Date(parseInt(jsonDate.substr(6))).format("mm/dd/yy");
       
