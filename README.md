# yatheesh-22nov.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    
    .pie-container {
      position: relative;
      width: 200px;
      height: 200px;
      margin: 50px auto;
    }

    
    .pie-button {
      position: absolute;
      width: 0;
      height: 0;
      border-radius: 50%;
      clip-path: polygon(50% 50%, 100% 0, 100% 100%);
      cursor: pointer;
      transition: background-color 0.3s ease-in-out;
    }

    .pie-button:nth-child(1) {
      width: 100%;
      height: 100%;
      background-color: #ffffff;
      transform: rotate(0deg);
    }

    .pie-button:nth-child(2) {
      width: 100%;
      height: 100%;
      background-color: #ffffff;
      transform: rotate(90deg);
    }

    .pie-button:nth-child(3) {
      width: 100%;
      height: 100%;
      background-color: #ffffff;
      transform: rotate(180deg);
    }

    .pie-button:nth-child(4) {
      width: 100%;
      height: 100%;
      background-color: #ffffff;
      transform: rotate(270deg);
    }
    .pie-button:not(:last-child) {
      margin-right: 10px;
    }

    .pie-button:hover {
      background-color: #555;
    }
  </style>
</head>
<body>

  
  <div class="pie-container">
    <div class="pie-button">
    <img src="https://unsplash.com/images" alt="1st">
    </div>
    <div class="pie-button">
     <img src="https://unsplash.com/images" alt="2nd">   
    </div>
    <div class="pie-button">
     <img src="https://unsplash.com/images" alt="3rd">
    </div>
    <div class="pie-button">
      <img src="https://unsplash.com/images" alt="4th">   
    </div>
  <center>
    <input type="checkbox"
           id="switch"
           class="checkbox" />
            
    <label for="switch"
           class="toggle">
        <p>
            searchoff   searchon
        </p>
    </label>
  </center>
</div>
</body>
</html>

