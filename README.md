# React-Interview--Preparation-

"""
`import {useState} from 'react';
function isNumber(str){
  return !isNaN(Number(str));
}
function isString(str){
  return /^[a-zA-Z_]+$/.test(str);
}
function display(str){
  if(str===""){
    return "invalid input";
  }
  if(isNumber(str)){
    if(str%2===0){
      return "even";
    }
    else{
      return "odd";
    }
  }
  else if(isString(str)){
    return str.toUpperCase();
  }
  else{
    return "invalid input";
  }
}

export default function App(){
  const [val,setVal]=useState("");
  
  return(
    <>
      <form>
        <label>
          Input<input  onChange={(event)=>{
            setVal(event.target.value)
          }}type="text"></input>
        </label>
        </form> 
        <h1>Result:</h1>
        <h1>{display(val)}</h1>
     </>
  )
}`
"""
