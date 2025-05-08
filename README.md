/topup-ff
  ├── index.html
  ├── style.css
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Jasa Top Up FF Murah</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>TOP UP FF MURAH</h1>
    <p>Proses Cepat, Harga Murah, 24 Jam</p>
  </header>

  <section class="form-section">
    <h2>Formulir Top Up</h2>
    <form>
      <label for="id">ID Pemain:</label>
      <input type="text" id="id" name="id" required>

      <label for="jumlah">Jumlah Diamond:</label>
      <select id="jumlah" name="jumlah">
        <option value="70">70 DM - Rp10.000</option>
        <option value="140">140 DM - Rp19.000</option>
        <option value="355">355 DM - Rp49.000</option>
      </select>

      <label for="metode">Metode Pembayaran:</label>
      <select id="metode" name="metode">
        <option value="dana">DANA</option>
        <option value="ovo">OVO</option>
        <option value="gopay">Gopay</option>
      </select>

      <button type="submit">Kirim Pesanan</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Jasa Top Up FF. Hubungi via WhatsApp: 08xxxxxxx</p>
  </footer>
</body>
</html>
body {
  font-family: sans-serif;
  background: #f4f4f4;
  margin: 0;
  padding: 0;
}

header {
  background: #ff4444;
  color: white;
  text-align: center;
  padding: 20px;
}

.form-section {
  background: white;
  max-width: 500px;
  margin: 20px auto;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 0 10px #ccc;
}

form {
  display: flex;
  flex-direction: column;
}

label, select, input, button {
  margin-bottom: 15px;
}

button {
  background: #ff4444;
  color: white;
  padding: 10px;
  border: none;
  cursor: pointer;
}

button:hover {
  background: #cc0000;
}

footer {
  text-align: center;
  padding: 10px;
  background: #ddd;
}

