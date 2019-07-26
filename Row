 <div id="main-wrap">
            <img class="logo" src="logo.png">
            <div id="leftside"><br>
                <strong>%u_actualProfileName%</strong><br><br>
                <strong>Username:</strong> <br>%u_username%<br><br>
                <strong>Password:</strong> <br>%u_password%<br><br>

            </div>
            <div id="rightside"><br>SCAN TO LOG IN<br>
                <div class="qrcode" id="%u_username%"></div>
                <script> jQuery(function(){jQuery('#%u_username%').qrcode(
    {
        "render": 'div',
        "size": 150,
        "minVersion": 5,
        "maxVersion": 5,
        "ecLevel": 'L',
        "mode": 0,
        "text": "http://hotspot-ip/login?username=%u_username%&password=%u_password%",
        "quiet": 0,
    }

); }) </script>
                <span style= "font-size: 12px">Or browse to: <br>http://hotspot-dns-name<br></span>
            </div>
            <div class="bottom">
                Ask your host for more information
            </div>   
        </div>
