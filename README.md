# animatione-sheos
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
 .frame {
  
    position: absolute;
    top: 50%;
    left: 50%;
    width: 50%;
    height: 400px;
    margin-top: -250px;
    margin-left: -200px;
    border-radius: 2px;
    box-shadow: 4px 8px 16px 0 ;
    overflow: hidden;
    background: radial-gradient(deepskyblue);
    color: green;
}
.center {
  height: 100%;
  box-shadow: inset 0 -100px 0 greenyellow;
  background-color: deepskyblue;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}
.shoe {
   width: 180px;
  animation: 1.8s step linear infinite;
  animation-fill-mode: none;
  position: absolute;
  transform-origin: top;
  img {
    width: 180px;
  }
  &:last-child {
    animation-delay: -0.9s;
  }
}

@keyframes step {
  0% {
    transform: rotate(50deg);
    left: 60px;
    bottom: 100px;
  }
  11% {
    transform: rotate(70deg);
    left: 110px;
    bottom: 90px;
  }
  22% {
    transform: rotate(60deg);
    left: 150px;
    bottom: 120px
  }
  33% {
    transform: rotate(40deg);
    left: 170px;
    bottom: 155px
  }
  44% {
    transform: rotate(20deg);
    left: 180px;
    bottom: 160px
  }
  55% {
    transform: rotate(-15deg);
    left: 190px;
    bottom: 110px
  }
  66% {
    transform: rotate(-5deg);
    left: 200px;
    bottom: 80px
  }
  77% {
    transform: rotate(10deg);
    left: 110px;
    bottom: 80px
  }
  88% {
    transform: rotate(20deg);
    left: 80px;
    bottom: 95px
  }
  100% {
    transform: rotate(50deg);
    left: 60px;
    bottom: 100px;
  }
}


    </style>
</head>
<body>
    <div class="frame">
        <div class="center">
          <img src="./shopping-Photoroom.png-Photoroom.png" class="shoe" />
          <img src="./shopping-Photoroom.png-Photoroom.png" class="shoe" />
        </div>
      </div>
             
</body>
</html>
