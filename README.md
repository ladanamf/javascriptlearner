# javascriptlearner

console.log("Hello world");
let firstname = "ali"
let lastname = "sadri"
let fullmame = firstname +" "+ lastname;
console.log(firstname);
console.log(fullmame);

let num1 = 10
let num2 = 20
let sum = num1 + num2
console.log(sum)
let res1 = num1+num2+fullmame
let res2 = fullmame + num2 + num1;
console.log(res1)
console.log(res2)

let age = 22
if (age < 12) {
     console.log("child")
}

if (age > 12) {
    console.log("young")
}

let validEmail = true
let validPassword = false
if (validEmail && validPassword){
    console.log('logged in')
}
if (validEmail || validPassword){
    console.log('ERROR')
}

let isuser=true
let useradmin='admin'

if (isuser){
    console.log('welcome')
}else if (useradmin === 'admin'){
    console.log('welcom!!')
}else {
    console.log('wrong')
}


let iceCream = 'chocolate';
if(iceCream === 'chocolate') {
  alert('Yay, I love chocolate ice cream!');
} else {
  alert('Awwww, but chocolate is my favorite…');
}

/*let firstnames = "ahmad"

if(true) {
    let lastnames = "sadri"
    console.log(lastnames)
}
console.log(lastnames)*/



let name1 = "sepid"
if(true) {
    let last1 = "sadri"
    console.log(last1)
    if(true) {
        let age1 =30
        console.log(age1) 
    }
}

console.log(name1)

let first = "saead"
if(true){
    let first = "sadr"
    if(true){
        let first = "ali"
        console.log(first)
    }
}

let message=function(){
    console.log("kala")
}
message()
message()
message()


let userid = function(id){
    console.log(id)
}
userid(6)

let userid2 = function(id){
    let res = "user id: " + id
    return id
}

let show = userid2(4)
console.log(show)



let sumi = function(sum1 , sum2, sum3){
    let s = sum1 + sum2+ sum3
    return s
}

let showd = sumi(8, 5, 2)
console.log(showd)


let getuserinfo = function(name="masoud" , id=22){
     return "name:" + name + " , "  + "id:"+ id
} 
let showde = getuserinfo("negin", 23)
console.log(showde)

//روش 2 بالایی

let getuserinfo2 = function(name3 , id){
       return `name: ${name3}
        - id: ${id}`
}
let showdetail=getuserinfo2("mahsa" ,34)
console.log(showdetail)


//key mitavanad adad ya string bashad.
let userinfo1 = {
    username : "navid",
    userid : 52,
    role : "admin"
}
console.log(`user role info: ${userinfo1.role}`)

let userinfo2 ={
    username : "vahid",
    userid: 87,
    role: "user"
}

let userinfo3 ={
    username : "vahid",
    userid: 87,
    role: "user"
}

console.log("---------------------------------------------------------")

let fetchuserdata = function(user) {
    console.log(`user info : ${user.username}`)
    
}

fetchuserdata(userinfo2)
fetchuserdata(userinfo1)



