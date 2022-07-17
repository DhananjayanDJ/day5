Print odd numbers in an array using arrow and anonymous function

arrow function

var foo=((arr)=>{
    var temp=0;
    for(i=0;i<arr.length;i++)
{
    temp=temp+arr[i];
    
}
 console.log(temp);
})
    
foo([1,2,3,3,5,6,70])


 anonymous function

function foo(arr){
var temp=0;

for(i=0;i<arr.length;i++)
{
    temp=temp+arr[i];
    
}
 console.log(temp);
}

foo([1,2,3,3,5,6,70])

Print odd numbers in an array

 anonymous function

function foo(arr){
    for(let i=0;i<arr.length;i++)
    {
        if(arr[i]%2!=0)
        {
            console.log(arr[i]);
        }
    }

}
foo([1,2,3,4,5,6,7,8,9])


arrow function
var foo = ((arr)=>{
    for(let i=0;i<arr.length;i++)
    {
        if(arr[i]%2!=0)
        {
            console.log(arr[i]);
        }
    }
})
foo([1,2,3,4,5,6,7,8,9])
