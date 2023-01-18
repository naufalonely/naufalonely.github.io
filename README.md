<html>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="w3.css">

    <div class="container w3-blue">
        <center>
            <img src="banner.png" width="100%">
        </center>
    </div>

    <div class="w3-bar w3-black">
        <button class="w3-bar-item w3-button" onclick="openKota('Home')">Home</button>
        <button class="w3-bar-item w3-button" onclick="openKota('Playboi Carti')">Playboi Carti</button>
        <button class="w3-bar-item w3-button" onclick="openKota('Ken Carson')">Ken Carson</button>
        <button class="w3-bar-item w3-button" onclick="openKota('Destroy Lonely')">Destroy Lonely</button>
        <button class="w3-bar-item w3-button" onclick="openKota('Homixide Gang')">Homixide Gang</button>
        <button class="w3-bar-item w3-button" onclick="openKota('Album')">Album</button>
        <button class="w3-bar-item w3-button" onclick="openKota('Profile')">Profile</button>
    </div>

    <div id="Home" class="w3-container kota w3-animate-zoom" style="display: block">
        <center>
        <h1><b>Welcome*</h1>
    </center>
    </div>
    
    <div id="Playboi Carti" class="w3-container kota w3-animate-top" style="display: none">
    <center>
        <h2><b>Playboi Carti</h2>
        <img src="carti.png" width="25%">
        <p align="left">Jordan Terrell Carter (born September 13, 1996), known professionally as Playboi Carti, is an American rapper. 
            Carter was initially signed to local underground label Awful Records prior to signing with ASAP Mob's AWGE Label under Interscope Records. 
            After gaining a cult following early in his career, Carter garnered mainstream attention in 2017.

            Carter's debut mixtape was released in April 2017, and included the Billboard Hot 100 charting singles "Magnolia" and "Woke Up Like This" (featuring Lil Uzi Vert). 
            His debut studio album Die Lit (2018) peaked at number 3 on the US Billboard 200. 
            Following a two-year hiatus with little-to-no new music released, Carter's highly anticipated second album, Whole Lotta Red (2020), debuted at number one on the Billboard 200 and became his first chart-topping release.
            
            Aside from his solo career, Carter established his Opium record label in 2019 which has since signed artists such as Ken Carson and Destroy Lonely.</p>
    </center>
    </div>

    <div id="Ken Carson" class="w3-container kota w3-animate-bottom" style="display: none">
        <center>
            <h2><b>Ken Carson</h2>
            <img src="ken.png" width="25%">
            <p align="left">Kenyatta Lee Frazier Jr. (born April 11, 2000), known professionally as Ken Carson 
                (formerly stylized as Ken Car$on), is an American rapper, singer, songwriter, and record producer. 
                He is known for his studio album X which peaked at number 115 on the Billboard 200 and for being 
                signed to Opium, the record label belonging to Playboi Carti.</p>
        </center>
        </div>

        <div id="Destroy Lonely" class="w3-container kota w3-animate-left" style="display: none">
            <center>
                <h2><b>Destroy Lonely</h2>
                <img src="lone.png" width="25%">
                <p align="left">Bobby Wardell Sandimanie III (born July 30, 2001), known professionally as Destroy Lonely, 
                    is an American rapper. He is best known for his studio album No Stylist which peaked at 
                    number 91 on the Billboard 200. He is also the son of American rapper I-20 who was signed 
                    to Ludacris' label Disturbing tha Peace. Destroy Lonely signed to Playboi Carti's Opium label 
                    through Interscope Records and Ingrooves in early 2021 and is often affiliated with his 
                    labelmate Ken Carson.</p>
            </center>
            </div>
            
            <div id="Homixide Gang" class="w3-container kota w3-animate-right" style="display: none">
                <center>
                    <h2><b>Homixide Gang</h2>
                    <img src="gang.png" width="25%">
                    <p>Homixide Gang is a rap duo from Atlanta Georgia, the group consists of two members, 
                        Homixide Beno! and Homixide Meechie. The members are affiliated with Playboi Carti's label, 
                        Opium.</p>
                </center>
                </div>

                <div id="Album" class="w3-container kota w3-animate-opacity" style="display: none">
                    <center>
                        <h2><b>Album</h2>
                        <table>
                            <tr>
                                <td>
                                    <img src="wlr.jpeg" width="50%">
                                    <h2><b>Whole Lotta Red</h2>
                                    <p>by Playboi Carti</p>
                                </td>
                                <td>
                                    <img src="x.jpeg" width="50%">
                                    <h2><b>X</h2>
                                    <p>by Ken Carson</p>
                                </td>
                                <td>
                                    <img src="nostylist.jpeg" width="50%">
                                    <h2><b>NOSTYLIST</h2>
                                    <p>by Destroy Lonely</p>
                                </td>
                                <td>
                                    <img src="hg.jpeg" width="50%">
                                    <h2><b>Homixide Gang</h2>
                                    <p>by Homixide Gang</p>
                                </td>
                            </tr>
                        </table>
                    </center>
                    </div>

                    <div id="Profile" class="w3-container kota w3-animate-zoom" style="display: none">
                        <center>
                            <h2><b>M. Naufal Ghifari - 10122264 - IF 7</h2>
                        </center>
                        </div>

    <script>
        function openKota(namaKota) {
            var i;
            var x = document.getElementsByClassName("kota");
            for (i = 0; i < x.length; i++) {
                x[i].style.display="none";
            }
            document.getElementById(namaKota).style.display = "block";
        }
    </script>
</html>
