<style>
    body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: #222;
        }

 .animation-container {
            text-align: ;
            color: #fff;
            font-size: 24px;
        }

        .loader {
            border: 4px solid rgba(255, 255, 255, 0.3);
            border-top: 4px solid #fff;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 2s linear infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        body {
  margin: 0;
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: #333;
}

.warning-logo {
  width: 100px;
  height: 100px;
  background-color: #ff8c00; /* Warning color */
  border-radius: 50%;
  position: relative;
}

.warning-logo:before,
.warning-logo:after {
  content: '';
  position: absolute;
  width: 10px;
  height: 40px;
  background-color: #fff; /* White color */
  border-radius: 5px;
}

.warning-logo:before {
  top: 10px;
  left: 45px;
  transform: rotate(-45deg);
}

.warning-logo:after {
  top: 10px;
  left: 45px;
  transform: rotate(45deg);
}
P{
    color: white;
    text-align: center;
    text-shadow: #fff;
    text-transform: uppercase;
    font-style: ATOMICAGI;
}

</style>

  <div class="warning-logo"></div>
  <p>Please Enable Your Device "DESKTOP SITE" And Wait a 20 Second</p>


<br>
<p id="adviceText"></p>
    <div class="animation-container">
        <div class="loader"></div>
      
    </div>
    <script>
        // Function to redirect to the second page after 10 seconds
        function redirectToSecondPage() {
            window.location.href = "second_page.html";
        }

        // Add event listeners to each button (like in your original code)

        // Call redirectToSecondPage after a 20-second delay
        setTimeout(redirectToSecondPage, 20000); // 20000 milliseconds = 20 seconds
    </script>
