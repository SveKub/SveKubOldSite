<div class="row">
        <div class="col-md-8">
            <h2>Hörnbitarna</h2>
            <p>För att sätta de fyra sist hörnbitarna på rätt plats ska vi använda den sista algoritmen vi behöver lära oss. Den ser ut så här</p>
            <p>U R U' L' - U R' U' L</p>
            För att den ska fungera ska ett hörn vara på rätt plats. Vrid på kuben (hela kuben, om vi bara vrider på det övre lagret nu kommer vi sätta kantbitarna på fel plats och det vill vi inte eftersom vi i steget innan satte dem på sina rätta platser) och leta efter ett hörn som sitter mellan sina tre centrumbitar. Om inget av de fyra hörnen sitter på rätt plats utför vi algoritmen en gång. Därefter kommer ett hörn sitta på sin rätta plats och vi kan leta efter det. Rotera kuben så det hörn som sitter på rätt plats ligger närmast dig på höger sida och utför algoritmen. 
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ylllll&move=U R U' L' U R' U' L" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-8">
        Vrid hela kuben så en hörnbit sitter på rätt plats när den är på höger sidan närmast dig och utför algoritmen. Titta på alla fyra hörn och se om de sitter på rätt plats. Om de inte gör det letar du efter ett som sitter på rätt plats, vrider på kuben så det sitter närmast dig på höger sida och utför algoritmen igen. 
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=R' F' L F R F' L' F U R U' L' U R' U' L&move=z2 U R U' L' U R' U' L" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-8">
        <h2>Sista steget</h2>
            <p>I sista steget ska vi vända hörnbitarna så de sitter rättvända. Det gör vi med den första algoritmen du lärde dig. </p>
            <p>R' D' R D</p>
            <p>Vrid på kuben så det hörn du vill vända på sitter till närmast dig till höger. Utför algoritmen tills hörnet hamnar med den gula sidan uppåt. Nu kan det se ut som att mycket annat på kuben blivit förstört men så är det inte. Så länge som du fortsätter att utföra algoritmen rätt kommer det rätta till sig när du vänt på alla hörn. När det första hörnet är vänt rätt vrider vi det översta lagret så ett annat hörn som är felvänt hamnar närmast dig till höger. Sedan utför vi algoritmen igen tills det hörnet vänds rätt. Fortsätt så med alla hörn som är felvridna. </p>
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=R' D' R D2 F D' F' U F D F' D2 R' D R U'&move=R' D' R D R' D' R D R' D' R D R' D' R D U R' D' R D R' D' R D U'" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>