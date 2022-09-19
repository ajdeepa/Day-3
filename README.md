# Day-3
For Given Json iterate over all for loops(for ,for in)
var json = [{
    "Name" : "Deepa", 
    "msg" : "Task",
    "task" : "for loop",
    "mail": "ajdeepacuty@gmail.com"
},
{
    "Name" : "Kumaran", 
    "msg" : "Related Task",
    "task" : "for in loop",
    "mail": "ikcutekumaran@gmail.com"
}];
//for loop
for(var i=0;i<json.length;i++){
    console.log(json[i].Name);
    console.log(json[i].msg);
    console.log(json[i].task);
    console.log(json[i].mail);

}
//for in loop
for(var key in json){
    console.log(json[key].Name)
}
//to print key as well as value in output
for(var i=0;i<json.length;i++)
for(var key in json[i]){
    console.log(key,json[i][key])
}
