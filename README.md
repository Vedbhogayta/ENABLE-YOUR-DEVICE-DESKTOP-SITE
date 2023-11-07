
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mood Advice</title>
</head>
<body>
    <style>
        /* Style the mood buttons */
button {
  margin: 10px;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  font-size: 16px;
  background-color: #fff; /* Default background color */
  border: 2px solid #333; /* Default border */
  color: #333; /* Default text color */
}
#h1{
    background-color: #333;
}
/* Style each button based on its mood */
#happyButton {
  background-color: #FFD700; /* Yellow for Happy */
  color: #333;
}

#sadButton {
  background-color: #4682B4; /* Steel Blue for Sad */
  color: #fff;
}

#angryButton {
  background-color: #FF0000; /* Red for Angry */
  color: #fff;
}

/* Add styles for other mood buttons here */

/* Style the color boxes for advice */


/* Style color boxes for different moods */
#adviceText.happy {
  background-color: #FFD700; /* Yellow background for Happy */
  color: #333;
}

#adviceText.sad {
  background-color: #4682B4; /* Steel Blue background for Sad */
  color: #fff;
}

#adviceText.angry {
  background-color: #FF0000; /* Red background for Angry */
  color: #fff;
}

#gloomy {
    background-color: gray;
    color: white;
}

#calm {
    background-color: lightblue;
    color: black;
}

#mournful {
    background-color: darkslategray;
    color: white;
}

#romantic {
    background-color: pink;
    color: black;
}

#Bitter {
    background-color: darkred;
    color: white;
}

#confused {
    background-color: lightgray;
    color: black;
}

#Enjoyment {
    background-color: yellow;
    color: black;
}

#Exitement {
    background-color: red;
    color: white;
}

#fear {
    background-color: darkorange;
    color: black;
}

#insulted {
    background-color: purple;
    color: white;
}

#major {
    background-color: darkgreen;
    color: silver;
}

#spirit {
    background-color: darkblue;
    color: white;
}

h1 {
    font-size: 36px; /* Adjust the font size as desired */
    color: #4a90e2; /* Choose a nice blue color for the heading text */
    padding: 20px; /* Add some padding for spacing */
    background-color: #333; /* Use a bright yellow background color */
    border-radius: 10px; /* Add rounded corners for a colorful box effect */
    display: inline-block; /* Make it an inline-block to center-align it properly */
}

    </style>
    <center><h1>Choose Your Currunt Mood</h1>
    <button id="happyButton">Happy</button>
    <button id="sadButton">Sad</button>
    <button id="angryButton">Angry</button>
    <button id="gloomy">Gloomy</button>
    <button id="calm">Calm</button>
    <button id="mournful">Mournful</button>
    <button id="romantic">Romantic</button>
    <button id="Bitter">Bitter</button>
    <button id="confused">Confused</button>
    <button id="Enjoyment">Enjoyment</button>
    <button id="Exitement">Exitement</button>
    <button id="fear">Fear</button>
    <button id="insulted">Insulted</button>
    <button id="major depression">Major Depression</button>
    <button id="spirit">spirit</button>

    <p id="adviceText"></p>

    <script>
         // Function to provide mood advice
function provideMoodAdvice(mood) {
    switch (mood) {
        case "happyButton":
            alert("Embrace your happiness and spread positivity to those around you.");
            break;
        case "sadButton":
            alert("If you're feeling sad, it's okay to reach out to friends or family for support.");
            break;
        case "angryButton":
            alert("When you're angry, take a moment to calm down and address the situation rationally.");
            break;
        case "gloomy":
            alert("When you're feeling gloomy, it's important to talk to someone you trust and seek emotional support.");
            break;
        case "calm":
            alert("Enjoy the calm moments in life, take deep breaths, and practice relaxation techniques.");
            break;
        case "mournful":
            alert("If you're feeling mournful, allow yourself to grieve and remember that it's okay to seek professional help if needed.");
            break;
        case "romantic":
            alert("Embrace the romantic feelings and consider planning a special date or spending quality time with your loved one.");
            break;
        case "Bitter":
            alert("Dealing with bitterness can be challenging. It's important to let go of negative emotions and find ways to forgive and move forward.");
            break;
        case "confused":
            alert("When you're feeling confused, take a step back, analyze the situation, and seek advice or guidance from others.");
            break;
        case "Enjoyment":
            alert("Enjoyment is important for your well-being. Engage in activities that bring you joy and happiness.");
            break;
        case "Exitement":
            alert("Embrace excitement and consider trying something new or adventurous to keep life interesting.");
            break;
        case "fear":
            alert("If you're feeling fear, it's normal. Try to identify the source of your fear and take steps to address it.");
            break;
        case "insulted":
            alert("Dealing with feeling insulted can be tough. Remember your self-worth and consider addressing the situation calmly and assertively.");
            break;
        case "major depression":
            alert("Major depression is a serious condition. It's crucial to seek professional help and support from friends and family.");
            break;
        case "spirit":
            alert("Nurture your spirit by engaging in activities that bring you a sense of purpose and fulfillment.");
            break;
        default:
            alert("Select a mood to receive advice.");
            break;
    }
}

// Add event listeners to each button
document.getElementById("happyButton").addEventListener("click", function() {
    provideMoodAdvice("happyButton");
});

document.getElementById("sadButton").addEventListener("click", function() {
    provideMoodAdvice("sadButton");
});

document.getElementById("angryButton").addEventListener("click", function() {
    provideMoodAdvice("angryButton");
});

document.getElementById("gloomy").addEventListener("click", function() {
    provideMoodAdvice("gloomy");
});

document.getElementById("calm").addEventListener("click", function() {
    provideMoodAdvice("calm");
});

document.getElementById("mournful").addEventListener("click", function() {
    provideMoodAdvice("mournful");
});

document.getElementById("romantic").addEventListener("click", function() {
    provideMoodAdvice("romantic");
});

document.getElementById("Bitter").addEventListener("click", function() {
    provideMoodAdvice("Bitter");
});

document.getElementById("confused").addEventListener("click", function() {
    provideMoodAdvice("confused");
});

document.getElementById("Enjoyment").addEventListener("click", function() {
    provideMoodAdvice("Enjoyment");
});

document.getElementById("Exitement").addEventListener("click", function() {
    provideMoodAdvice("Exitement");
});

document.getElementById("fear").addEventListener("click", function() {
    provideMoodAdvice("fear");
});

document.getElementById("insulted").addEventListener("click", function() {
    provideMoodAdvice("insulted");
});

document.getElementById("major depression").addEventListener("click", function() {
    provideMoodAdvice("major depression");
});

document.getElementById("spirit").addEventListener("click", function() {
    provideMoodAdvice("spirit");
});

        
    </script>

