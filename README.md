>>> Array destructing
>>> Arrow function
>>> 

 

    function Button() {
      const [counter, setCounter] = useState(42); // Array destructing
      return <button onClick={logRandom}>{counter}</button>
    }
 
    function Button_arrowfunction() {
      const [counter, setCounter] = useState(0);
      return <button onClick={() => alert(Math.random())}>{counter}</button>
    }
    
    
 
    
 
