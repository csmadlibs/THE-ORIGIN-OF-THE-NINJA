<head>
<style>
        #adj1{
            background-color orange
        }
        #pn1{
            background-color orange
        }
        #place1{
            background-color orange
        }
        #num1{
            background-color orange
        }
       #sillwrd1{
            background-color orange
        }
        #verb1{
            background-color orange
        }
        #adverb1{
            background-color orange
        }
        #pn2{
            background-color orange
        }
        #pn3{
            background-color orange
        }
        #adj2{
            background-color orange
        }
        #pn4{
            background-color orange
        }
        #pn5{
            background-color orange
        }
        #verbing1{
            background-color orange
        }
        #bodyprt1{
            background-color orange
        } 
        #story{
            background-color = orange
        }
</style>
</head>
<body>
    <ul>
        <li>Adjective: <input type="text" id="adj1"></li>
        <li>Plural noun: <input type="text" id="pn1"></li>
        <li>A place: <input type="text" id="place1"></li>
        <li>Number: <input type="text" id="num1"></li>
        <li>Silly word: <input type="text" id="sillwrd1"></li>
        <li>Verb: <input type="text" id="verb1"></li>
        <li>Adverb: <input type="text" id="adverb1"></li>
        <li>Plural noun: <input type="text" id="pn2"></li>
        <li>Plural noun: <input type="text" id="pn3"></li>
        <li>Adjective: <input type="text" id="adj2"></li>
        <li>Plural noun: <input type="text" id="pn4"></li>
        <li>Plural noun: <input type="text" id="pn5"></li>
        <li>Verb ending in "ing": <input type="text" id="verbing1"></li>
        <li>Part of the body (Plural): <input type="text" id="bodyprt1"></li>
    </ul>
    <button id="lib-button">Lib it!</button>
 <p>Generated story: 
    <span id="story"></span>
    </p>
    <script>
    var libButton = document.getElementById("lib-button")
    var onButtonClick = function(){
        var story = document.getElementById("story")
        var adj1 = document.getElementById("adj1").value
        var pn1 = document.getElementById("pn1").value
        var place1 = document.getElementById("place1").value 
        var num1 = document.getElementById("num1").value
        var sillwrd1 = document.getElementById("sillwrd1").value
        var verb1 = document.getElementById("verb1").value
        var adverb1 = document.getElementById("adverb1").value
        var pn2 = document.getElementById("pn2").value
        var pn3 = document.getElementById("pn3").value
        var adj2 = document.getElementById("adj2").value
        var pn4 = document.getElementById("pn4").value
        var pn5 = document.getElementById("pn5").value
        var verbing1 = document.getElementById("verbing1").value
        var bodyprt1 = document.getElementById("bodyprt1").value
        story.innerHTML = "Where do ninjas come from? Their beginnings are as mysterious and as " + adj1 + " as those of any of the ancient " + pn1 + " of the 14th century. Historians claim the ninjas originated in (the) " + place1 + " around " + num1 + " year(s) ago. The word ninja comes from the Japanese word " + sillwrd1 + " which means to '" + verb1 + adverb1  + ".' Espionage was their primary job- they acted as secret " + pn2 + ", spying on the bad guys. They were hired by royalty and other powerful " + pn3 + " to discover an enemy's " + adj2 + " weaknesses. They would sneak into opposing camps to steal passwords, battle plans, or " + pn4 + ". Known for their stealth movements, ninjas avoided detection by disguising themselves as " + pn5 + " and " + verbing1 + " quietly in the shadows. When it came to dealing with ninjas, people learned to have " + bodyprt1 +  " in the back of their heads!" 
    }
    libButton.addEventListener("click", onButtonClick)
</script>
</body>
       