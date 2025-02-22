<!DOCTYPE html>
<html>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@400;700&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: #000000;
    font-family: 'Raleway', sans-serif;
    cursor: cell;
}

button{
  position: fixed;
  padding: 30px 35px;
  font-size: 25px;
  background-color: rgb(96, 8, 8);
  color: #000000;
  font-weight: bold;
  border: none;
  border-radius: 5px;
  letter-spacing: 4px;
  overflow: hidden;
  transition: 0.5s;
  cursor: pointer;
}

button:hover{
    background: #1096b1;
    color: black;
    box-shadow: 0 0 5px black,
                0 0 25px black,
                0 0 50px black,
                0 0 200px black;
     -webkit-box-reflect:below 1px linear-gradient(transparent, #0005);
}

h1 {
    position: fixed;
    font-size: 50px;
    font-weight: bold;
    bottom: 30%;
    top: 12%;
    color: rgb(96, 8, 8);
}
h2 {position: fixed;
    font-size: 50px;
    font-weight: bold;
    bottom: 90%;
    top: 5%;
    color: rgb(96, 8, 8);

}

</style>                                         
<body>

    <h1>By Expert Code</h1>
    <h2>Premium Cloak</h2>
    <button onclick="openGame()">Open Cloaked Page</button>
    <script>
        var url;
        let huh = prompt("Enter URL DO NOT Have https:// \nFor Help With tunnels Type info or help\n(If a website has www in it add www. to the start url)");

        if(huh == "hop") {
            let tunnel = prompt("Enter Password");
            url = "https://" + tunnel + ".hop.sh";}
        else if(huh == "vercel") {
            let tunnel = prompt("Enter Password");
            url = "https://" + tunnel + ".vercel.app";
        }
        else if(huh == "eu") {
            let tunnel = prompt("Enter Password");
            url = "https://" + tunnel + ".eu.org";
        }
        else if(huh == "com") {
            let tunnel = prompt("Enter Password");
            url = "https://" + tunnel + ".com";
        }
        else if(huh == "org ") {
            let tunnel = prompt("Enter Password");
            url = "https://" + tunnel + ".org";
        }
        else if(huh == "edu") {
            let tunnel = prompt("Enter Password");
            url = "https://" + tunnel + ".edu";
        }
        else if(huh == "net") {
            let tunnel = prompt("Enter Password");
            url = "https://" + tunnel + ".net";
        }
        else if(huh == "dev") {
            let tunnel = prompt("Enter Password");
            url = "https://" + tunnel + "-basic-10.us";
        }
        else if (huh == "Dev3754"){
            let infoInput = alert("PASSWORDS\nGame: geography\n")
           alert("Please Refresh Page") }  
        else if (huh == "info" || huh == "help") {
            let infoInput = alert("tunnel1: .hop.sh\ntunnel2: .vercel.app\nTunnel3: .eu.org\ntunnel4: .com\ntunnel5: .org\ntunnel6: .edu\ntunnel7: .net\nPlease Refresh to Open a New Cloaked Page");
        }
        else {
            url = "https://" + huh;
        }
        if (url) {
            var win;
            var webReplace = 'https://www.google.com';

            document.querySelector('button').onclick = function() {
                if (win) {
                    win.focus();
                } else {
                    win = window.open();
                    win.document.body.style.margin = '0';
                    win.document.body.style.height = '100vh';
                    var iframe = win.document.createElement('iframe');
                    iframe.style.border = 'none';
                    iframe.style.width = '100%';
                    iframe.style.height = '100%';
                    iframe.style.margin = '0';
                    iframe.src = url;
                    win.document.body.appendChild(iframe);
                    window.location.replace(webReplace);
                }
            };
        }
    </script>
</body>
</html>
