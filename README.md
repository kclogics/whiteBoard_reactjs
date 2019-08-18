const [counter, setCounter] = useState(0); // Array destructing
return <button>{Math.random()}</button>

   function logRandom() {
     console.log(Math.random());
   }


    function Button() {
      const [counter, setCounter] = useState(42);
      return <button onClick={logRandom}>{counter}</button>
    }
 
    function Button_arrowfunction() {
      const [counter, setCounter] = useState(0);
      return <button onClick={() => alert(Math.random())}>{counter}</button>
    }
 
    
 
