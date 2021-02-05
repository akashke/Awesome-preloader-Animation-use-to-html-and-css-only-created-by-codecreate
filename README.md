<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name = "viewport" content="width = device-width, initial-scale = 1.0">
        <title>Loading Page</title>
    </head>
    <body>
        <div class="centrer">
            <div class="trait"></div>
            <div class="trait"></div>
            <div class="trait"></div>
            <div class="trait"></div>
            <div class="trait"></div>
            <div class="trait"></div>
            <div class="trait"></div>
            <div class="trait"></div>
        </div>
        <style>
            
body, html{
    min-width: 365px;
    margin: 0px;
    padding: 0px;
    width: 100%;
    height: 100%;
    background-color: #85DCBB;
}

.centrer{
    width: 100px;
    height: 100px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    align-items: center;
}

.trait{
    width: 8px;
    height: 60px;
    margin: 3px;
    background-color: darkgreen;
    animation: anim 0.8s infinite;
}

.trait:nth-child(2){
    animation-delay: 0.1s;
}

.trait:nth-child(3){
    animation-delay: 0.2s;
}

.trait:nth-child(4){
    animation-delay: 0.3s;
}

.trait:nth-child(5){
    animation-delay: 0.4s;
}

.trait:nth-child(6){
    animation-delay: 0.5s;
}

.trait:nth-child(7){
    animation-delay: 0.6s;
}

.trait:nth-child(8){
    animation-delay: 0.7s;
}

@keyframes anim{
    100%{
        height: 0px;
    }
    0%{
        height: 60px;
    }
}


        </style>
    </body>
</html>





