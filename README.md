>>> Array destructing
>>> Arrow function
>>> 

 

    function Button() {
      const [counter, setCounter] = useState(42); // Array destructing
      return <button onClick={logRandom}>{counter}</button>
    }
 
   
    function Button() {
      const [counter, setCounter] = useState(0); // Array destructing
      return <button onClick={() => setCounter(counter+1)}>{counter}</button>; // Arrow Function
    }
 
    ReactDOM.render(<Button />, mountNode);
    
    --------------------------------------------------------------------------------------------
    
      
 
    
 
    
 
