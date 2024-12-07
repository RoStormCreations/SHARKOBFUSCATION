<html>
<head>
    <title>Lua Obfuscator</title>
    <link rel="icon" type="image/x-icon" href="images/eee.ico">
    <style>
        html {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            background-color: #2b2e4a;
            color: #ffffff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            box-sizing: border-box;
        }

        #container {
            width: 90%;
            max-width: 800px;
            padding: 40px;
            background-color: #3c3f58;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            text-align: center;
        }

        h1 {
            margin-bottom: 20px;
            font-size: 2rem;
            color: #f67280;
        }

        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }

        label {
            font-size: 1.1rem;
            font-weight: bold;
            color: #f67280;
        }

        textarea {
            width: 90%;
            max-width: 750px;
            padding: 15px;
            border: 1px solid #4f5274;
            border-radius: 10px;
            background-color: #4f5274;
            color: #ffffff;
            font-size: 1rem;
            resize: none;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            transition: box-shadow 0.3s ease;
        }

        textarea:focus {
            box-shadow: 0 0 10px rgba(255, 105, 180, 0.7);
            outline: none;
        }

        input[type="submit"] {
            background-color: #f67280;
            color: #ffffff;
            padding: 12px 30px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.1rem;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: background-color 0.3s ease, transform 0.2s ease;
        }

        input[type="submit"]:hover {
            background-color: #ee6c7d;
            transform: scale(1.05);
        }

        h2 {
            font-size: 1.5rem;
            margin-top: 30px;
            color: #f67280;
        }

        .tt {
            white-space: pre-wrap;
            word-wrap: break-word;
            background-color: #4f5274;
            border-radius: 10px;
            padding: 15px;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            font-size: 1rem;
            color: #ffffff;
            pointer-events: none;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        #downloadButton {
            background-color: #f67280;
            color: #ffffff;
            padding: 12px 30px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.1rem;
            margin-top: 20px;
            display: none;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: background-color 0.3s ease, transform 0.2s ease;
        }

        #downloadButton:hover {
            background-color: #943743;
            transform: scale(1.05);
        }
    </style>
</head>

<body>
    <div id="container">
        <h1>LUAU Jammer</h1>
        <form id="luaForm">
            <label for="luaCode">Enter Lua Code:</label>
            <textarea id="luaCode" name="luaCode" rows="10" cols="50" onfocus="clearDefaultText(this)"
                onblur="setDefaultText(this)">Paste your script</textarea>
            <input type="submit" value="Obfuscate">
        </form>
        <button id="downloadButton">Download Obfuscated Script</button>
        <h2>Obfuscated Script:</h2>
        <p class="tt" id="encodedOutput">Obfuscated code will appear here after obfuscation.</p>
    </div>

    <script>
        document.getElementById("luaForm").addEventListener("submit", function (event) {
            event.preventDefault();
            const luaCode = document.getElementById("luaCode").value;
            if (luaCode.trim() === "" || luaCode === "Enter your Lua code here.") {
                const encodedOutput = document.getElementById("encodedOutput");
                encodedOutput.textContent = "Please enter a script.";
                document.getElementById("downloadButton").style.display = "none";
            } else {
                minifyAndObfuscate(luaCode);
            }
        });

        function minifyAndObfuscate(luaCode) {
            const minifiedLua = luaCode.replace(/--.*$/gm, '').replace(/\s+/g, ' ');

            const encoded = minifiedLua.replace(/./g, function (bb) {
                const byteValue = bb.charCodeAt(0);
                return "\\" + byteValue;
            });

            const loadstringCall = `function IllIlllIllIlllIlllIlllIll(IllIlllIllIllIll) if (IllIlllIllIllIll==(((((919 + 636)-636)*3147)/3147)+919)) then return not true end if (IllIlllIllIllIll==(((((968 + 670)-670)*3315)/3315)+968)) then return not false end end; local IIllllIIllll = (7*3-9/9+3*2/0+3*3);local IIlllIIlllIIlllIIlllII = (3*4-7/7+6*4/3+9*9); function IllIIIIllIIIIIl(IIllllIIllll) function IIllllIIllll(IIllllIIllll) function IIllllIIllll(IllIllIllIllI) end end end;IllIIIIllIIIIIl(900283);function IllIlllIllIlllIlllIlllIllIlllIIIlll(IIlllIIlllIIlllIIlllII) function IIllllIIllll(IllIllIllIllI) local IIlllIIlllIIlllIIlllII = (9*0-7/5+3*1/3+8*2) end end;IllIlllIllIlllIlllIlllIllIlllIIIlll(9083);local IllIIllIIllIII = loadstring;local IlIlIlIlIlIlIlIlII = "${encoded}"IllIIllIIllIII(IlIlIlIlIlIlIlIlII,IIIIIIIIllllllllIIIIIIII)()`;

            const encodedOutput = document.getElementById("encodedOutput");
            encodedOutput.textContent = loadstringCall;

            const downloadButton = document.getElementById("downloadButton");
            downloadButton.style.display = "block";

            downloadButton.addEventListener("click", function () {
                const encodedBlob = new Blob([loadstringCall], { type: "text/plain;charset=utf-8" });
                const downloadLink = document.createElement("a");
                downloadLink.href = URL.createObjectURL(encodedBlob);
                downloadLink.download = "obfuscated_script.txt";
                downloadLink.style.display = "none";

                document.body.appendChild(downloadLink);
                downloadLink.click();
                document.body.removeChild(downloadLink);
            });
        }

        function clearDefaultText(element) {
            if (element.value === "Enter your Lua code here.") {
                element.value = "";
            }
        }

        function setDefaultText(element) {
            if (element.value === "") {
                element.value = "Enter your Lua code here.";
            }
        }
    </script>
</body>

</html>
