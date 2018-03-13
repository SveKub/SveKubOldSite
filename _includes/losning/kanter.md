<div class="row">
        <div class="col-md-8">
            <h2>Övre korset</h2>
            <p>Med två lösta lager är det dags att göra kors nummer två. Till det använder vi en ytterligare en algoritm, den här är sex drag lång och ser ut så här: </p>
            <p>F R U – R' U' F'</p>
            <p>De fyra gula kantbitarna ska bilda ett kors, har man tur är det redan ett kors när man kommer hit och då är det bara att gå vidare till nästa steg. Är det gula korset inte löst finns det tre olika lägen och för att lösa dem gör man algoritmen en, två eller tre gånger. </p>
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ylllll&move=F R U R' U' F'" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-12">
            <p>För att algoritmen ska skapa ett kors ska man utföra den med två gula kantbitar mitt emot varandra på varsin sida om centrumbiten. Om ingen gul kantbit förutom centrumbiten finns på ovansidan görs algoritmen först en gång. Då kommer två kantbitar bredvid varandra att vändas rätt. Vrid det över lagret så de gula kantbitarna pekar till vänster och uppåt och utför algoritmen en gång till. Nu kommer det tredje fallet med två gula kantbitar på varsin sida om centrumbiten. Vrid det övre lagret så två gula bitarna pekar till vänster och höger och utför algoritmen en sista gång. 
            De tre olika fallen visas nedan. </p>
        </div>
    </div>
    <div class="row">
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=L2 U' F' B L2 F B' U' L2 R' F R' B2 R F' R' B2 R2 F R U R' U' F' U2 F R U R' U' F' F R U R' U' F'&move=F R U R' U' F' U2 F R U R' U' F' F R U R' U' F'" frameborder="0" height="100%" width="100%"></iframe>
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=L2 U' F' B L2 F B' U' L2 R' F R' B2 R F' R' B2 R2 F R U R' U' F'&move=F R U R' U' F' F R U R' U' F'" frameborder="0" height="100%" width="100%"></iframe>
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=L2 U' F' B L2 F B' U' L2 R' F R' B2 R F' R' B2 R2 F R U R' U' F' U2 F R U R' U' F'&move=U F R U R' U' F'" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-8">
            <h2>Fixa korset</h2>
            <p>När det övre korset är löst måste de fyra kanterna matchas med de fyra centrarna i andra lagret. Det görs med att utföra en algoritm en eller två gånger. Algoritmen som används kallas Sune och ser ut så här</p>
            <p>R U R' U - R U2 R'</p>
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ylllll&move=R U R' U R U2 R'" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-8">
            <p>Vrid det övre lagret så två kantbitar matchar med centrumbitarna i andra lagret. Om de två bitarna sitter bredvid varandra vrider vi på hela kuben så de två bitar som matchar pekar uppåt och till höger. Sedan utför vi algoritmen och avslutar med att vrida det över lagret tills alla fyra kantbitar matchar med centrumbitarna i andra lagret. </p>
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=L2 U' F' B L2 F B' U' L2 R' F' L F R F' L' F&move=U z R U R' U R U2 R' U" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-8">
            <p>Om de två kantbitaran som matchar centrumbitarna ligger på motsatt sida måste algoritmen utföras två gånger. Vrid kuben så det två bitarna pekar mot dig och ifrån dig och utför algoritmen. Efter det kommer du kunna vrida det övre lagret så två kantbitar bredvid varandra matchar med centumbitarna i andra lagret och du kan utföra algoritmen en gång till som i första fallet. </p>
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=L2 U' F' B L2 F B' U' L2 U' L2 U' F' B L2 F B' U' L2  R' F' L F R F' L' F z U&move=U z2 R U R' U R U2 R' z' R U R' U R U2 R' U" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
