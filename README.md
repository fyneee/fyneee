<html> 
 <head></head> 
 <body> 
  <div class="wrapper"> 
   <div class="container"> 
    <center></center> 
    <p id="question">do you love me?</p> <button class="btn" id="yes">Yes</button> <button class="btn" id="no">No</button> 
   </div> 
  </div> 
  <script>
   const noBtn = document.getElementById('no');
   const yesBtn = document.getElementById('yes');
   const ques = document.getElementById('question');
   noBtn.addEventListener("click", ()=>{
       let rand = Math.floor(Math.random() * (500 - 100) + 1);
       let rand2 = Math.floor(Math.random() * (300 - 100) + 1);
       noBtn.style.transform= "translate("+rand+"px,"+rand2+"px)";
       
   });
   yesBtn.addEventListener("click", ()=>{
       ques.innerHTML = "i love you more, tine"
   })
</script> 
 </body>
</html>
