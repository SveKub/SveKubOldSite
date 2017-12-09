---
layout: page
title: Testar AnimCubeJS
permalink: /Losningar/Test
activeMenu: Losningar
---

<div class="container margin-top">
    <div class="row">
        <div class="col-md-6">
            <h2>Korset</h2>
            Första steget i att lösa Rubiks kub är att göra ett vitt kors. För det behövs det ingen algoritm. Försök vrida de fyra vita kantbitarna så de matchar med den vita centerbiten och var av en av de andra fyra färgerna. 
        </div>
        <div class="col-md-4">
          <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=2&facelets=lWlWWWlWlllllllllllllgglllllllBBlllllollolllllllRRllll" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-6">
            <h2>Första lagret</h2>
            För att lösa första lagret är det efter korsets fyra kantbitar, fyra hörnbitar som ska sättas på rätt plats vända åt rätt håll. För att göra det används en algoritm som är 4 drag lång. </br>
            Algoritmen som ska användas är: R' D' R D
            </br>
            Börja med att leta efter en vit hörnbit i det undre lagret. När du hittar en titta du vilka två andra färger samma hörnbit har. De andra två färgerna ska matchas med två andra centerbitar. Vrid det undre lagret tills hörnbiten sitter mellan de två andra färgernas centerbitar. 
        </div>
        <div class="col-md-4">
          <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=wygbor&initmove=L D L' B D B' R D R' F D F D2&move=D R' D' R D" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>

</div>