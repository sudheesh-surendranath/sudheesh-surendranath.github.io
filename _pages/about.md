---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
analytics: true
---


I am a fourth year Mathematics Ph.D. student at the <a href="https://www.math.utah.edu/">University of Utah</a> advised by <a href="https://www.math.utah.edu/~davar/">Davar Khoshnevisan</a>. My research focuses on probability and stochastic analysis, including stochastic partial differential equations.

<div id="xkcd">
</div>

<script type="text/javascript">

var imagesArray = [

"purity.png", 
"unsolved_math_problems.png", 
"coffee_cup_holes.png", 
"applied_math.png", 
"complex_conjugate.png", 
"existence_proof.png",  
"konigsberg.png", 
"taylorseries.png", 
"dangerous_fields.png", 
"fairy_tales.png", 
"investing.png", 
"math_paper.png", 
"mathematically_annoying.png",  
"matrix_transform.png", 
"newton_and_leibniz.png", 
"prediction.png", 
"proofs.png", 
"pumpkin_carving.png", 
"sudoku.png", 
"travelling_salesman_problem.png",  
"well_ordering_principle.png"

   ];

function displayImage(){

    var num = Math.floor(Math.random() * (imagesArray.length));
    if (imagesArray[num]=="konigsberg.png" || imagesArray[num]=="matrix_transform.png"){
       document.getElementById("xkcd").innerHTML +=
         '<img src="/xkcd/' + imagesArray[num] + '" alt="drawing" width=700px/>';
    } else if (imagesArray[num]=="taylorseries.png") {
       document.getElementById("xkcd").innerHTML +=
         '<img src="/xkcd/' + imagesArray[num] + '" alt="drawing" width=200px/>';
 
    } else if (imagesArray[num]=="sudoku.png") {
       document.getElementById("xkcd").innerHTML +=
         '<img src="/xkcd/' + imagesArray[num] + '" alt="drawing" width=300px/>'; 
    } else {
       document.getElementById("xkcd").innerHTML +=
      '<img src="/xkcd/' + imagesArray[num] + '" alt="drawing" width=900px/>';
    }
       
}

displayImage();

</script>


