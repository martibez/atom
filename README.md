# 3D Atom

To a 2D atom visualization, use this code below on CSS file:

circle:nth-child(1) {
    transform: rotateX(80deg) rotateY(20deg) rotateZ(90deg);
    animation-name: drawCircle, rotateCircle1;
}

@keyframes rotateCircle1 {
    to {
        transform: rotateX(80deg) rotateY(20deg) rotateZ(360deg);
    }
}
 
circle:nth-child(2) {
    transform: rotateX(75deg) rotateY(60deg) rotateZ(0deg);
    animation-name: drawCircle, rotateCircle2;
    animation-delay: 0.125s;
}

@keyframes rotateCircle2 {
    to {
        transform: rotateX(75deg) rotateY(60deg) rotateZ(360deg);
    }
}

circle:nth-child(3) {
    transform: rotateX(-75deg) rotateY(60deg) rotateZ(0deg);
    animation-name: drawCircle, rotateCircle3;
    animation-delay: 0.25s;
}

@keyframes rotateCircle3 {
    to {
        transform: rotateX(-75deg) rotateY(60deg) rotateZ(360deg);
    }
}

circle:nth-child(4) {
    transform: rotateX(-80deg) rotateY(20deg) rotateZ(0deg);
    animation-name: drawCircle, rotateCircle4;
    animation-delay: 0.375s;
}

@keyframes rotateCircle4 {
    to {
        transform: rotateX(-80deg) rotateY(20deg) rotateZ(360deg);
    }
}
