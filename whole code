<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Responsive Layout</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  
  .container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    box-sizing: border-box;
  }
  
  .section {
    float: left;
    width: 33.33%;
    box-sizing: border-box;
    padding: 20px;
    border: 1px solid black;
    margin-bottom: 20px;
    position: relative;
  }
  
  .section h2 {
    margin-top: 0;
  }
  
  .section-title {
    position: absolute;
    top: 0;
    right: 0;
    background-color: #FFD700; /* Gold */
    color: black;
    padding: 5px 10px;
    border: 1px solid black;
    border-bottom-left-radius: 5px;
    font-size: 14px;
  }
  
  @media screen and (max-width: 991px) {
    .section {
      width: 50%;
    }
    .section:nth-child(3) {
      clear: both;
    }
  }
  
  @media screen and (max-width: 767px) {
    .section {
      width: 100%;
    }
  }
</style>
</head>
<body>

<div class="container">
  <div class="section">
    <div class="section-title">Chicken</div>
    <h2>Chicken Section</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vehicula accumsan elit, id sodales ex condimentum et.</p>
  </div>
  <div class="section">
    <div class="section-title">Beef</div>
    <h2>Beef Section</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vehicula accumsan elit, id sodales ex condimentum et.</p>
  </div>
  <div class="section">
    <div class="section-title">Sushi</div>
    <h2>Sushi Section</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vehicula accumsan elit, id sodales ex condimentum et.</p>
  </div>
</div>

</body>
</html>
