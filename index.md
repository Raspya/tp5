
<html lang="fr">
<head>
    <meta charset="UTF-8">
</head>
<body>

    <div>
        <h3>Lien externe</h3>
        <a href="https://fr.wikipedia.org/wiki/Donovan_(musicien)">Ceci est un lien vers une page Wikipedia</a>
    </div>

    <div>
        <h3>Lien interne</h3>
        <a href="page2.html">Ceci est un lien vers une deuxieme page interne</a>
    </div>

    <div>
        <h3>Image externe insérée</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Donovan_%281965%29.jpg/440px-Donovan_%281965%29.jpg" alt="Image de Donovan">
        <p>Image du chanteur Donovan</p>
    </div>

    <div>
        <h3>Image interne insérée</h3>
        <img src="image-rationnelle.jpg" alt="Image rationnelle">
        <p>Image rationnelle d'un éléphant</p>
    </div>

    <div>
        <h3>Style CSS</h3>
        <div class="style">
            <p>Ceci est un exemple de style css appliqué</p>
        </div>
    </div>

    <div>
        <h3>Tableau d'exemple</h3>
        <table>
            <tr>
                <th>Elements</th>
                <th>Prix</th>
                <th>Stock</th>
            </tr>
            <tr>
                <td>Banane</td>
                <td>0.30</td>
                <td>182</td>
            </tr>
            <tr>
                <td>Sandwich</td>
                <td>2.70</td>
                <td>34</td>
            </tr>

        </table>
    </div>

    <div>
        <h3>Insertion d'une vidéo youtube</h3>
        <iframe width="420" height="315" src="https://www.youtube.com/embed/tgbNymZ7vqY"></iframe>
    </div>



    <style>
        img{
            width: 100px;
        }
        div{
            width: 30%;
            margin: 0 auto;
            margin-top:60px;
            text-align: center;
            border: 1px solid black;
            padding: 10px;
            
        }
        .style{
            width:80%;
            margin: 0 auto;
            background-color: #00E4FF;
            border-radius: 5px;
            border: 1px solid black;

            box-shadow: 10px 5px 15px black;
        }
        .style:hover{
            background-color: #FF0093;
        }

        table{
            margin:0 auto;
        }

        th, td{
            padding: 10px;
            padding-right: 40px;
            padding-left: 40px;
            border: 1px solid black;
        }
        th{
            color: #FFF;
            background-color: #000;
        }
        td{
            color: #000;
            background-color: #ccc;
        }
    </style>

    
</body>
</html>
