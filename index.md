<!DOCTYPE html>
<html>
    <head>
        <title>SPRAWDZIAN</title>
        <meta charset="UTF-8">

        <style>
            body{
                background-color: black;
            }
            ul{
                margin: 0;
            }
            ul:hover{
                color: black;
            }
            header{
                font-weight: bold;
                font-size: 20px;
            }
            .all{
                display: flex;
                flex-direction: column;

                margin: auto;
                width: 50%;
                padding-left: 80px;
                padding-right: 80px;
                border: 2px solid white;
                border-radius: 25px;
            }
            .obiekt{
                color: white;
                font-size: 18px;
                line-height: 27px;
                padding-bottom: 20px;
                padding-top: 20px;
                border-bottom: 2px solid white;
            }
            #first{border-top: 0;}
            #last{border-bottom: 0;}
        </style>
    </head>
    <body>
        <div class="all">
            <div class="obiekt" id="first">
                <header>1. Procesory w smarfonach</header>
                <ul>
                    <li>MediaTek - Helio</li>
                    <li>Qualcomm - Snapdragon</li>
                    <li>Apple - A Bionic</li>
                    <li>HiSilicon - Kirin</li>
                    <li>Samsung - Exynos</li>
                </ul>
            </div>
            <div class="obiekt">
                <header>2. Marki smartfonów</header>
                <ul>
                    <li>Samsung</li>
                    <li>Huawei</li>
                    <li>Apple</li>
                    <li>HTC</li>
                    <li>LG</li>
                    <li>Sony</li>
                    <li>Motorola</li>
                </ul>
            </div>
            <div class="obiekt">
                <header>3. Parametry aparatu w smarfonach</header>
                <ul>
                    <li>rozdzielczość</li>
                    <li>ilość obiektywów</li>
                    <li>zoom optyczny/cyfrowy</li>
                    <li>slow motion</li>
                    <li>rozdzielczość nagrywania filmów</li>
                    <li>stabilizacja</li>
                </ul>
            </div>
            <div  class="obiekt">
                <header>4. Parametry smarfona</header>
                <ul>
                    <li>liczba rdzeni/wątków procesora</li>
                    <li>taktowanie procesora</li>
                    <li>ilość pamięci RAM</li>
                    <li>ilość pamięci dysku</li>
                    <li>rozdzielczość ekranu</li>
                    <li>system operacyjny</li>
                    <li>wodoodporność</li>
                    <li>materiał wykoniania</li>
                    <li>waga</li>
                    <li>rodzaj matrycy</li>
                    <li>screen to body ratio</li>
                </ul>
            </div>
            <div class="obiekt">
                <header>5. Parametry wyświetlacza</header>
                <ul>
                    <li>rozdzielczość</li>
                    <li>rodzaj matrycy</li>
                    <li>liczba kolorów</li>
                    <li>wielkość</li>
                </ul>
            </div>
            <div class="obiekt">
                <header>6. Technologie</header>
                <ul>
                    <li>Bluetooth</li>
                    <li>Wi-Fi</li>
                    <li>NFC</li>
                    <li>4G, 5G</li>
                    <li>IrDA</li>
                    <li>GPS</li>
                    <li>GSM</li>
                </ul>
            </div>
            <div class="obiekt" id="last">
                <header>7. Zastosowania smartwatchy/smartbandów</header>
                <ul>
                    <li>pulsometr</li>
                    <li>krokomierz</li>
                    <li>mierzenie jakości i czasu snu</li>
                    <li>motywowanie</li>
                    <li>obsługa SMS</li>
                    <li>dzwonienie</li>
                    <li>rozrywka</li>
                    <li>łatwy dostęp do powiadomień</li>
                </ul>
            </div>
        </div>
    </body>
</html>
