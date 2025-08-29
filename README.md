[index.html](https://github.com/user-attachments/files/22050510/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Curriculum Vitae Form - Ayush Kar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      background: #eef2f7;
    }
    .form-container {
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      max-width: 850px;
      margin: auto;
    }
    h1 {
      text-align: center;
      color: #222;
    }
    label {
      font-weight: bold;
      display: block;
      margin-top: 15px;
    }
    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 14px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }
    table, th, td {
      border: 1px solid #888;
      padding: 10px;
      text-align: center;
    }
    button {
      margin-top: 20px;
      padding: 12px 25px;
      background: #007BFF;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h1>Curriculum Vitae - Ayush Kar</h1>
    <form>
      <label>Full Name</label>
      <input type="text" value="Ayush Kar" required>

      <label>Father's Name</label>
      <input type="text" value="Pradip Kar" required>

      <label>Address</label>
      <textarea rows="3" required>Bogapar, Jagannath Nagar, South 24 Parganas, P.S. Maheshtala, P.O. Jagannath Nagar, Kolkata-700141</textarea>

      <label>Date of Birth</label>
      <input type="date" value="2009-02-13" required>

      <label>Nationality</label>
      <input type="text" value="Indian">

      <label>Religion</label>
      <input type="text" value="Hinduism">

      <label>Marital Status</label>
      <select>
        <option selected>Unmarried</option>
        <option>Married</option>
      </select>

      <label>Sex</label>
      <select>
        <option selected>Male</option>
        <option>Female</option>
      </select>

      <label>Category</label>
      <input type="text" value="General">

      <label>Contact Number</label>
      <input type="tel" value="629058801">

      <label>Email ID</label>
      <input type="email" value="ayushkar@gmail.com">

      <h3>Educational Background</h3>
      <table>
        <tr>
          <th>Examination</th>
          <th>Board</th>
          <th>Year of Passing</th>
          <th>Percentage</th>
        </tr>
        <tr>
          <td>Secondary</td>
          <td>W.B.B.S.E</td>
          <td><input type="text" value="2024"></td>
          <td><input type="text" value="Appeared"></td>
        </tr>
        <tr>
          <td>Class XI (Commerce)</td>
          <td>W.B.C.H.S.E</td>
          <td><input type="text" value="2025"></td>
          <td><input type="text" value="Appearing"></td>
        </tr>
      </table>

      <label>Computer Knowledge</label>
      <input type="text" value="Basic Knowledge of Computer">

      <label>Working Experience</label>
      <input type="text" value="Fresher">

      <label>Languages Known</label>
      <input type="text" value="Bengali, Hindi & English">

      <label>Declaration</label>
      <textarea rows="3">I do hereby declare that all the information furnished above are true to the best of my knowledge.</textarea>

      <label>Date</label>
      <input type="date">

      <label>Place</label>
      <input type="text" value="Kolkata">

      <button type="submit">Submit CV</button>
    </form>
  </div>
</body>
</html>
