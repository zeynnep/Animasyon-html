# Animasyon-html
Html ile animasyonlu yazım çalışması kodlarım
<!DOCTYPE html>
<html>
    <head>
        <style>
            *,
            ::before,
            ::after{
                margin: 0;
                padding: 0;
                box-sizing:border-box;
            }
            body{
                background-color: black;
                height: 100vh;
                display: flex ;
                justify-content: center;
                align-items: center;
            }
            .Name {
                font-size: 10rem;
                font-family: sans;
                font-variant: inherit;
                font-weight: 900;
                background: conic-gradient(
                    #dff2ae 0 25%,
                    #ff904f 25% 50%,
                    #feefe7 50% 75%,
                    #2bfff8 75%
                );
                background-size: 400% 400%;
                animation: animateBackground 4.5s ease-in-out infinite;
                color: blueviolet;
                background-clip: text;
                -webkit-background-clip: content-box;
            }

            @keyframes animateBackground {
                25% {
                    background-position: 0 100%;
                }

                50% {
                    background-position:100% 100%;
                }

                75% {
                    background-position: 100% 0%;
                }

                100% {
                    background-position: 0 0;
                }
            }
        </style>

    </head>
    <body>
        <div class="Name">
            zeyN
        </div>
    </body>
</html>
