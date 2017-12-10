<div class="row">
        <div class="col-md-12">
            <h2>Andra lagret</h2>
            <p>När första lagret är löst ska vi lösa andra lagret utan att förstöra något i det första lagret. Börja med att vänd kuben upp och ner så den vita lösta sidan är på kubens undersida. </p>
            <p>
            Andra lagret löser vi med två algoritmer som flyttar ner kantbitar från det översta lagret till det mittersta lagret. Kantbitarna kan flyttas ner till höger eller vänster om en centrumbit. 
            </p>
            <p>Till höger: U R U' R' - U' F' U F</p>
            <p>Till vänster: U' L' U L - U F U' F'</p>
            <p>Vrid det översta lagret tills en kantbit som ska sitta i andra lagret matchar med en centrumbit i det andra lagret. Håll kuben så kantbiten matchar med färgen på centrumbiten på framsidan av kuben. Om kantbitens färg som inte matchar med centrumbiten är på vänster sida av kuben ska algoritmen för vänster göras. Sitter centrumbiten istället på kubens högra sidan ska algoritmen för höger göras. </p>
        </div>
    </div>
    <div class="row">
        <div class="col-md-8">
            Vrid först det övre lagret tills en kantbit matchar med en centrumbit i andra lagret och rotera kuben så kantbiten finns på framsidan. 
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=F U R U' R' F' U R U' R' U' F' U F&move=U Z" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-8">
            Om kantbiten ska sättas ner till vänster gör vi algoritmen för vänster. U' L' U L - U F U' F'
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=F U R U' R' F' U R U' R' U' F' U F U Z&move=U' L' U L U F U' F'" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>
    <div class="row">
        <div class="col-md-8">
            Om kantbiten ska sättas ner till höger gör vi algoritmen för höger:  U R U' R' - U' F' U F
        </div>
        <div class="col-md-4">
            <iframe src="/AnimCubeJS/cube.html?config=AnimCube.cfg&edit=0&buttonbar=1&colorscheme=ywgbor&initmove=F U R U' R' F' U' L' U L U F U' F' U' Z'&move=U R U' R' U' F' U F" frameborder="0" height="100%" width="100%"></iframe>
        </div>
    </div>