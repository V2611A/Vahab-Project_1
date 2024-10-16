# Vahab-Project_1
APJ Abdul Kalam Wikipedia


HTML CODE:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About APJ Abdul Kalam</title>
    <link rel="stylesheet" href="stylesheet.css">
</head>
<body>
    <div class="container">
        <div class="content">
            <section class="top_section">
                <div class="image_container">
                    <img src="./images/A._P._J._Abdul_Kalam.jpg" alt="APJ Abdul kalam Image">
                </div>
                <div>
                    <h1>A.P.J  Abdul  Kalam</h1>
                    <h4>1931 - 2015</h4>
                </div>
            </section>



            <section>
                <div class="about_section">
                    <h2>Missile Man Of India</h2>
                    <p><b>Avul Pakir Jainulabdeen Abdul Kalam</b>(15 October 1931 – 27 July 2015) was an Indian aerospace scientist and statesman who served as the 11th president of India from 2002 to 2007. Born and raised in a Muslim family in Rameswaram, Tamil Nadu, he studied physics and aerospace engineering. He spent the next four decades as a scientist and science administrator, mainly at the Defence Research and Development Organisation (DRDO) and Indian Space Research Organisation (ISRO) and was intimately involved in India's civilian space programme and military missile development efforts.[2] He thus came to be known as the Missile Man of India for his work on the development of ballistic missile and launch vehicle technology.</p>
                </div>
            </section>


            <secion class="bio_section">
                <h3>Biographies</h3>
                <ul>
                    <li>Developments in Fluid Mechanics and Space Technology by A P J Abdul Kalam and Roddam Narasimha; Indian Academy of Sciences, 1988.</li>
                    <li>India 2020: A Vision for the New Millennium by A P J Abdul Kalam, Y. S. Rajan; New York, 1998.</li>
                    <li>Wings of Fire: An Autobiography by A P J Abdul Kalam, Arun Tiwari; Universities Press, 1999</li>
                    <li>Ignited Minds: Unleashing the Power Within India by A P J Abdul Kalam; Viking, 2002.</li>
                    <li>The Luminous Sparks by A P J Abdul Kalam, by; Punya Publishing Pvt Ltd., 2004</li>
                    <li>Mission India by A P J Abdul Kalam, Paintings by Manav Gupta; Penguin Books, 2005</li>
                </ul>
            </secion>

            <footer>
                <p> -Read more About A.P.J Abdul kalam on <a href="https://en.wikipedia.org/wiki/A._P._J._Abdul_Kalam">Wikipedia</a></p>
            </footer>
        </div>
    </div>
</body>
</html>



CSS CODE:

*{
    margin:0px;
    padding:0px;
    box-sizing: border-box;
}
.container{
    background-color: #EDEDFD;
    min-height:100vh;
    background-size: cover;
    border:#1d1e4c solid 10px;
    
}
.content{
    max-width: 900px;
    margin:0 auto;
}
.image_container,img{
    height:320px;
    width:300px
}
.image_container{
    border-radius: 50%;
    overflow: hidden;
}
.top_section{
    display: flex;
    justify-content: space-between;
    margin-top:100px;
    align-items: flex-end;

}
.top_section h1{
    font-weight:bold;
    font-size:45px;
    color:#1d1e4c;
    text-transform: uppercase;
}
.top_section h4{
    text-align: end;
    font-size: 30px;
}
.about_section{
    margin:50px 0;
}
.about_section h2{
    font-size:70px;
    font-weight:400;
    margin-bottom: 20px;
}
.about_section p{
    font-size:20px;
    line-height:30px;
    letter-spacing:1.8px;
    text-align: justify;
}
.bio_section{
    margin-top:50px ;
}
.bio_section h3{
    margin-top: 20px;
    margin-bottom: 20px;
}
.bio_section ul{
    margin-left: 50px;
    
}
.bio_section li{
    margin-bottom: 10px;
}
.footer{
    margin:50px 0;
}
.footer p{
    text-align: end;
    
}

IMG FILE: https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcQELRJNIDJxadkcbt9_NATcqHwCayKGYUoqwvwkjPgQKaMlcnwM
