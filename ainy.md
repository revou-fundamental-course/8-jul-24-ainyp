# 8-jul-24-ainyp
8-jul-24-ainyp created by GitHub Classroom
S git clone https://github.com/revou-fundamental-course/8-jul-24-ainyp.git
/kalkulator-bmi
|-- index.html
|-- css/
|   |-- styles.css
|-- js/
    |-- script.js
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator BMI</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="container">
        <h1>Kalkulator BMI</h1>
        <p>Berat badan ideal adalah impian semua orang...</p>

        <form id="bmiForm">
            <label for="gender">Jenis Kelamin:</label>
            <select id="gender">
                <option value="pria">Pria</option>
                <option value="wanita">Wanita</option>
            </select>

            <label for="weight">Berat Badan (kg):</label>
            <input type="number" id="weight" required>

            <label for="age">Usia (tahun):</label>
            <input type="number" id="age" required>

            <label for="height">Tinggi badan (cm):</label>
            <input type="number" id="height" required>

            <button type="submit">Hitung BMI</button>
        </form>

        <div id="bmiResult" class="hidden">
            <h2>Hasil</h2>
            <p id="bmiValue"></p>
            <p id="bmiCategory"></p>
        </div>
    </div>

    <script src="js/script.js"></script>
</body>
</html>
