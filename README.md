# JavaScript-1-Assignment-
Basic methods  used in JavaScript 

let num=20;
if(num%10===0){
    console.log("Good");
}
else{
    console.log("Bad");
}

 let username=prompt("Enter the username" );
let Age=prompt("Enter the age ");
alert(`${username} is ${Age} years old.`);
  

let quarter=1;
switch(quarter){
case 1:
    console.log("January","February","March");
    break;

    case 2:
        console.log("April","May","June");
        break;

        case 3:
        console.log("July","August","September");
        break;

        case 4:
        console.log("October","November","December");
        break;

        default:
           console.log("Wrong Input");
           break;

}

     let str="Ayush goyal";
     if((str[0]=='A'||str[0]=='a') && str.length>5){

        console.log("Golden String");

     }

     else{
        console.log(" Not a Golden String");
     }

     let a=4;
      let b=3;
      let c=2;


      if(a>b){
        if(a>c){
            console.log("a is largest");
        }
        else{
            console.log("c is largest");
        }
        }

       else{
        if(b>c){
            console.log("b is largest");
        }
        else{
            console.log("c is largest");
        }
        }

    let num1=32;
    let num2=47852;

    if((num1%10)==(num2%10)){
        console.log("Numbers have same last digit",num1%10);

    }

    else{
        console.log("Numbers  don't have same last digit");
    }
        
       
      


