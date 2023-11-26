<!DOCTYPE html>
<html>
  <style>
    body {
      font-family: 'Tahoma';
      text-align: center;
      margin: 10px;
      background-color: #c1cdcd;
    }
    table {
      margin: 20px auto;
      border: 10px solid rgb(0 104 139);
    }
    td {
      width: 30px;
      height: 30px;
      border: 1px solid rgb(17, 1, 1);
      text-align: center;
      font-size: 16px;
    }
    .bold {
      font-weight: bold;
    }
    .sudoku {
      display: grid;
      grid-template-columns: repeat(9, 1fr);
    }
    .cell1 {
      width: 45px;
      height: 45px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.5em;
      font-weight: bold;
      background-color: #add8e6;
      border: 2px solid rgb(47 79 79);
    }
    .cell2 {
      width: 45px;
      height: 45px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.5em;
      font-weight: bold;
      background-color: #528b8b;
      border: 2px solid rgb(47 79 79);
    }
    h1 {
      font-family: Arial Black;
      max-width: 485px;
      margin: 50px auto;
      padding: 20px;
      border-radius: 5px;
      color: #1c6071;
    }
  </style>

  <body>
    <h1>-SUDOKU-</h1>
    <table>
      <tr class="sudoku">
        <td class="cell2">6</td>
        <td class="cell2">2</td>
        <td class="cell2">4</td>
        <td class="cell1">3</td>
        <td class="cell1">5</td>
        <td class="cell1">7</td>
        <td class="cell2">1</td>
        <td class="cell2">8</td>
        <td class="cell2">9</td>
      </tr>
      <tr class="sudoku">
        <td class="cell2">9</td>
        <td class="cell2">7</td>
        <td class="cell2">1</td>
        <td class="cell1">6</td>
        <td class="cell1">2</td>
        <td class="cell1">8</td>
        <td class="cell2">3</td>
        <td class="cell2">5</td>
        <td class="cell2">4</td>
      </tr>
      <tr class="sudoku">
        <td class="cell2">8</td>
        <td class="cell2">3</td>
        <td class="cell2">5</td>
        <td class="cell1">4</td>
        <td class="cell1">9</td>
        <td class="cell1">1</td>
        <td class="cell2">7</td>
        <td class="cell2">2</td>
        <td class="cell2">6</td>
      </tr>
        <tr class="sudoku">
        <td class="cell1">5</td>
        <td class="cell1">6</td>
        <td class="cell1">3</td>
        <td class="cell2">8</td>
        <td class="cell2">7</td>
        <td class="cell2">2</td>
        <td class="cell1">9</td>
        <td class="cell1">4</td>
        <td class="cell1">1</td>
      </tr>
      <tr class="sudoku">
        <td class="cell1">2</td>
        <td class="cell1">8</td>
        <td class="cell1">9</td>
        <td class="cell2">1</td>
        <td class="cell2">3</td>
        <td class="cell2">4</td>
        <td class="cell1">6</td>
        <td class="cell1">7</td>
        <td class="cell1">5</td>
      </tr>
      <tr class="sudoku">
        <td class="cell1">4</td>
        <td class="cell1">1</td>
        <td class="cell1">7</td>
        <td class="cell2">5</td>
        <td class="cell2">6</td>
        <td class="cell2">9</td>
        <td class="cell1">2</td>
        <td class="cell1">3</td>
        <td class="cell1">8</td>
      </tr>
      <tr class="sudoku">
        <td class="cell2">3</td>
        <td class="cell2">4</td>
        <td class="cell2">6</td>
        <td class="cell1">2</td>
        <td class="cell1">1</td>
        <td class="cell1">5</td>
        <td class="cell2">8</td>
        <td class="cell2">9</td>
        <td class="cell2">7</td>
      </tr>
      <tr class="sudoku">
        <td class="cell2">7</td>
        <td class="cell2">5</td>
        <td class="cell2">2</td>
        <td class="cell1">9</td>
        <td class="cell1">8</td>
        <td class="cell1">6</td>
        <td class="cell2">4</td>
        <td class="cell2">1</td>
        <td class="cell2">3</td>
      </tr>
      <tr class="sudoku">
        <td class="cell2">1</td>
        <td class="cell2">9</td>
        <td class="cell2">8</td>
        <td class="cell1">7</td>
        <td class="cell1">4</td>
        <td class="cell1">3</td>
        <td class="cell2">5</td>
        <td class="cell2">6</td>
        <td class="cell2">2</td>
      </tr>
    </table>
    <h3>Ahmet Yıldız</h3>
  </body>
</html>
