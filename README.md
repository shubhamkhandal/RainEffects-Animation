# RainEffects-Animation
In This Animation, I only use a HTML 5 and CSS 3


this is only animation effect with html and css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.main{
    width: 100%;
    height: 100vh;
    background: linear-gradient(rgba(0, 0, 0, 0.473),rgba(0,0,0,0.473)),
                 url('/1.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}
.rain{
    height: 100vh;
    background: url('./rain_PNG13470.png');
    animation: rain .3s linear infinite;
}
@keyframes rain{
    from{
        background-position: 0% 0%;
    }
    to{
        background-position: 30% 100%;
    }
}
