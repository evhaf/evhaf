<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Insurance Verification</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Insurance Verification</h1>
    <form id="verification-form">
      <label for="insurance-number">Insurance Number:</label>
      <input type="text" id="insurance-number" name="insurance-number" required />
      
      <button type="submit">Verify</button>
    </form>

    <div id="result"></div>
  </div>

  <script src="app.js"></script>
</body>
</html>
