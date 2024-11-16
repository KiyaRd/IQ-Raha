<!>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IQ Test</title>
</head>
<body>
    <h1>Be nazaret IQ Raha chande?</h1>
    <p>(manfi ham mitooni bezani)</p>
    <input type="number" id="inputIQ" placeholder="Adade khod ra vared konid">
    <button onclick="checkIQ()">Submit</button>
    <p id="result"></p>

    <script>
        function checkIQ() {
            const x = parseInt(document.getElementById('inputIQ').value);
            const result = document.getElementById('result');
            if (x > 0) {
                result.innerHTML = "ریدی کصخل خایمال واقعا چی توی مغزت میگذشت که این رو انتخاب کردی؟";
            } else {
                result.innerHTML = "افرین تو بردی";
            }
        }
    </script>
</body>
</html>
